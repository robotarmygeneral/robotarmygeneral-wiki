I got sick of previous semesters of downloading homework files, moving them to my working directory, copying, renaming, etc. It isn’t the worst thing in the world, but it’s often enough to dim that tiny spark of energy I have for grinding through homework at that moment.

Now my entire homework session looks like this (for doing homework set “2a” in this example):

1. Open terminal and move to my homework directory (actually I just always keep this open in its own Space).
2. Type ./hw 2a.
3. Do the homework in the solution LaTeX file that pops up.
4. Type ./compile 2a
5. Print the PDF file that pops up.

One of the nice effects is not once having to open my browser, something that inevitably leads to distractions.

Read on to see how to do it yourself.

This was an adventure into shell scripting for me. I’m afraid Linux power users will scoff at this post, but this was actually quite simple and it works. I did this on my Mac. It won’t work on Windows, but I could try that by request.

Create a file called “hw” in your homework directory with these contents:

   #!/bin/sh
   
   if [ -f ps$1-sol.tex ]
   then
   echo File exists. Not downloading.
   else
   curl http://www.cs.pomona.edu/classes/cs140/ProblemSets/ps$1.tex -o "ps$1.tex"
   curl http://www.cs.pomona.edu/classes/cs140/ProblemSets/ps$1.pdf -o "ps$1.pdf"
   cp ps$1.tex ps$1-sol.tex
   fi
   open ps$1.pdf
   mate ps$1-sol.tex

What this script does is check whether the problem set has been downloaded. If not, it downloads it and makes a copy of the TeX file for the solutions. Then, either way, it opens the TeX file for my solutions in Textmate and the pdf with the problems.
It should be pretty straightforward, but here are some things to note about fixing it for your own stuff:

* #!/bin/sh lets the OS know to execute this as a shell script. I’m assuming this is standard on OS X, but Linux users may have another location.
* Any occurrence of $1 is replaced with the first parameter given to the call of the script. In this case, ./hw 2a will download ps2a.tex and ps2a.pdf.
* curl is a program that comes with Mac OS X and downloads files given their URL. Just give your URL with the $1.
* Replace mate with your text editor of choice if it has command line invocation. Otherwise, “open” may do the trick if it’s set as a default.

The file to compile the LaTeX then view the PDF is dead simple. I called it “compile”:

   #!/bin/sh
   
   pdflatex ps$1-sol.tex
   open ps$1-sol.pdf

One more thing. You need to make this user-executable. Just type chmod u+rwx hw compile in the directory.

And that’s it! OK, it’s initially a bit of work for a little efficiency boost, but it will more than pay for itself by the end of the semester. And there’s undoubtedly lots more you can do with a similar idea. Extending scripting to Applescript will give you the ability to play with Finder windows and other applications, and using Perl could let you do more powerful things like generating solution TeX files. To do your own experimenting, try starting with this article: http://macdevcenter.com/pub/a/mac/2003/11/07/scripting_osx.html Let me know what you make!
