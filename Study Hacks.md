Study Hacks is a blog written by MIT computer science grad student Cal Newport whose philosophy definitely resonates with my ideals: getting high quality stuff done without superfluous effort. However, I’ve never really taken the effort to try to hone my study skills, and often fall short of those whether by overdoing ineffective perfectionism or just being lazy. This semester marks my attempt to improve my studying techniques, and starting now this blog will record some of that (as well as some other, less boring things).

To start, some tips courtesy of Cal.

# Philosophy

Stick to a small number of things and excel at them. No one cares about extracurricular laundry lists after high school.

Only work when you’re most productive, and only in the most productive manner.

# Time Management

Block scheduling - Divide your 9-5 day up into large blocks, where you focus on one thing in each one. No more than three projects in one day. Plan this out each day for five minutes in the morning.

Recurring tasks – Schedule recurring tasks at specific times so that you can go into [autopilot](http://calnewport.com/blog/2008/04/07/monday-master-class-how-to-reduce-stress-and-get-more-done-by-building-an-autopilot-schedule/).

Administrative day - Get all your small tasks done. Laundry, bills, etc.

Review your calendar and to-do lists on Sunday and set up for the next week.

# Organization & Collection

GTDCS (Getting Things Done for College Students) - This is based on the famous Getting Things Done system by David Allen. You can spend your life studying blog posts about GTD and trying various software, but here’s all you need to know: Collect all of the junk that you need to know later onto paper so you can get it out of your head. Have a file folder system for storing necessary papers. Have a to-do list but break up your tasks into small actionable items: Don’t make a “Write research paper” task. Make a “Email professor to discuss paper” task. Or if you can do it right away, do it. Cal also [gives a simple description and some specific tips](http://calnewport.com/blog/2008/10/06/monday-master-class-getting-things-done-for-college-studentsmade-easy/). Now never read anything about GTD again, and go get some things done already.

One notebook, one folder for each class.

# Studying

Form a study group. Do these things in this order: 1. Work on the problems alone. 2. Discuss the problems with your group. 3. (if necessary) Go to TA and/or office hours. That means you have to start early. Your group should also [discuss stress, studying techniques, etc.](http://www.calnewport.com/blog/?p=257)

Here’s a bunch of methods you should read if they sound appealing:

* [Notebook Method](http://calnewport.com/blog/2009/03/20/the-notebook-method-how-pen-and-paper-can-transform-you-into-an-star-student/)/[Adventure Studying](http://calnewport.com/blog/2008/05/02/adventure-studying-an-unconventional-new-approach-to-exam-preperation/) – (for difficult assignments/projects) Take pen and paper somewhere exotic and isolated and sketch out your ideas for a couple hours.
* [Quiz and recall method](http://www.studenthelpforum.com/2007/09/10/the-single-most-important-study-strategy-you-will-ever-hear/) – (for humanities/social science classes) Reduce your notes to a series of questions paired with conclusions. Between each question and conclusion should be a collection of evidence that connects the two. Spend 5-10 after class cleaning up results. Use AutoCorrect in word to quickly generate the format. To study look at question, then recreate the conclusion and some of the evidence.
* [Mini-textbook](http://calnewport.com/blog/2008/06/23/monday-master-class-conquer-complicated-material-with-the-mini-textbook-method/) - (for complicated, difficult material) From your notes, create a document of major concepts, definitions, theories.
* [Question clusters](http://calnewport.com/blog/?p=103) – (for multiple-choice tests on detailed material)
* [Technical explanations](Technical explanations) – (for technical courses) Pretend to give a lecture by answering questions about the material in a technical manner.
* [Audio study cues](http://calnewport.com/blog/2008/12/10/how-allison-used-her-ipod-to-ace-biology/#more-548) – (for any kind of lecture) Record lectures, break up with favorite audio editing software, put on mp3 player.
* [Morse code method](http://calnewport.com/blog/2008/02/18/monday-master-class-rapid-note-taking-with-the-morse-code-method/) – (for readings)    Put a dot by big, interesting ideas. Put a dash by examples or explanations that support the big idea. When you’re done, translate this to notes by paraphasing the dots, then paraphasing the dashes as bullet points for each dot. Condense to question and conclusion.
* [Don’t go into a difficult reading cold](http://calnewport.com/blog/2008/01/07/monday-master-class-how-to-read-hard-readings/) – Talk to the prof, search for related articles.

Some technical things:

* [Taking notes on a powerpoint](http://www.calnewport.com/blog/?p=194)
* [Gmail open questions](http://calnewport.com/blog/2007/10/29/monday-master-class-how-to-use-gmail-to-reduce-your-study-time-by-half/) – Process your gaps in knowledge through Gmail labels.
* [Research database](http://calnewport.com/blog/2007/10/01/monday-master-class-how-to-build-a-paper-research-database/) – use Excel to create a table of quotes and their sources, and if something historical/biographical, sort by a column of the time they refer to.

Ok, that’s my several hours of reading the blog this summer in a nutshell. If you liked this stuff, buy his book. I feel that this offers a good foundation, but in the future I’ll be talking about 1) actual results trying some of these techniques and further implementation details, if necessary; 2) some additional more specific and in-depth techniques that I have started using, particularly in math and language (Chinese) learning. Furthermore, I’ll start to introduce the tool that I’m developing that is meant to be an all-in-one web application for learning, understanding, and remembering anything and everything. It’s gonna be awesome.

# Neal: Reading with morse code

I was cued into the morse code reading technique by my roommate (see his post), and thought I would give it a whirl.  The reading in question was a rather dense set of chapters and philosophical articles on Identity for my Phil. of Language and Mind class.  For those of you unfamiliar, the morse code technique is a way of (in a sense) annotating your reading without breaking your cadence.  As described by Cal Newport, you make a dot by lines that contain key ideas and a dash by lines that offer supporting evidence for those ideas.  That way you can come back later and quickly paraphrase all of the important points in an article and synthesize what you have read.  There also seems to be the possibility of using the morse code technique to extract a sort of network-type structure from your reading, but the method needs to be extended to encompass further layers or argumental complexity.  For example, you may have some idea and then evidence both supporting and contradicting that idea.  Additionally, supporting (or contradicting) evidence could have its own support/contradiction.  I tried using a system where key points (mini-thesis statements) got a dot, and then supporting statements got a dash while contradictory statements got an X.  I then applied this method recursively, so evidence supporting a contradiction to the thesis would be labeled (X)–.  Your page might look something like this:

  <THESIS STATEMENT>

– <support of the thesis>

– <support of the thesis>

X <contradiction of the thesis>

(X)– <support of contradiction of thesis>

(X)X <counter argument to contradiction of thesis>,  etc.

I quickly found out that on paper, this method becomes too unwieldy and almost defeats the purpose of simplifying the argument without interrupting your reading flow.  But, given the organizational capabilities of software+relational databases, the extended morse code technique could become a useful study technique.

I’m envisioning this system working as follows:  Your reading would be digitized (if a .pdf scan of a book, there are tools to convert to text) and presented as a whole document.  As you read, there would be a way to quickly pick out sentences that represent key ideas (a “dot”), supporting evidence (a “dash”), contradictions to the key idea/supporting evidence, definitions, etc.  Because of the way in which articles are usually organized, it should be pretty clear that <supporting evidence E> applies to the most recent key point, but if not there would be a way to easily relate the new information chunk you have created to the idea it supports.  When you are done, the computer has formed a graph where each node is a chunk from the reading, and each edge is a relation to some other chunk.  This could be easily visualized, but to offer yourself higher synthesis you would want to go through and convert the raw graph into your own conceptual model of the reading.  In other words, you would paraphrase key points and their supporting evidence, which could then be put to use through an SRS learning system!  But, because everything is linked together semantically, if for some reason you want to see the context of some idea, you could easily follow a link back to the original text (or to your graph of raw chunks).  That way, you have synthesized the reading (via the paraphrase process and SRS) in a way which allows you to easily reference the primary source.

For now, I’m left to my own paper-and-pencil devices but I can easily imagine the utility of such an electronic system.
