## Forum and blog discussions

Just C&Ping stuff from the old forum. This can be combined with some of our other ideas, somehow. A lot of the stuff seems so similar that I just want to do a grand unifying project that solves all of education and learning. More thoughts on that later.

Me:

> We’ve started discussion on publishing an online mathematics textbook. The topic? Everything! The reason? Fuck publishers! The plan? ….
> 
> Seriously though.
> 
> Do we want to have a Wiki-style (limited or public access) site for compiling, or maybe use collaboration with Google Docs or some other service (there are tons now). Of course it’ll probably be LaTeX-heavy so we’d need something that supports that. We can use Texify and copy+paste the images, especially since we’re going to need to go with images rather than PDF if it’s going to be web-accessible.
> 
> Wikipedia has a ton of definitions & proofs for free already – though we could reuse that as long as we license ours the same way.
> 
> I’ll let someone else take over how we want to start organizing content, if we even do want to start right now.
> 
> I also earlier had laid out an idea for a problems book: Quote: I want to start compiling a list of math problems that have nice solutions or common tricks. (To borrow Seva’s term (if I remember correctly): nuggets) The general format I want to use includes a) topic b) problem c) summary of trick/theorem used c) 1 sentence-1 paragraph of motivation d) solution/proof. I’m envisioning three phases of implementation: 1) loose collection of nuggets 2) periodically updated blog 3) coffee table book collection of the best solutions with glossy pages and full color illustrations
> 
> I’m hoping to get as much help with this as possible. I also need to decide how to best organize them to accomplish a couple goals simultaneously. For one, vaguely remembered problems can be easily found and accessed. Grouping by topic will help, but I may also try using tags/keywords for each nugget and compiling an index. Also, this could also be an easy way to review a topic and pick up several of the tricks for someone familiar with the subject. Let me know any ideas you have.

Marko:

> One thing I was thinking is that we have the text book be half interactive. I don’t mean anything silly like “click here to guess the answer through the help of Mathasaurous Rex!”, but if we prove something and use a previous theorem you can click on it and it’ll open a window for the theorem, or take you to it in the text.
> 
> I think wiki style will be great for building it up, but that we eventually want to transition it to something more “textbooky”

Ryan:

> As I’m trying to organize my notes on econ, I’ve got a few ideas for making a more interactive type of (digital) textbook that would allow a more linear reading style but have any kind of additional explanation at your hands.
> 
> This may work best for more introductory level stuff, but a program where you can import some original equation and the steps to derive a new expression, and it animates the steps in place, like in those old physics movies. For a really simple example, B = xP_x + yP_y going to the linear form y = B/P_y – P_x/P_y*x. It would show subtracting from both sides then dividing through by P_y.
> 
> To explain an algorithm that you need to learn, it shows each step in a very straightforward manner. However, for each step there’s an icon you can click that shows the derivation so you can get a better understanding of how each step works.
> 
> Same thing for definition of terms. Screw glossaries.
> 
> Back to the algorithm learning: it originally shows it symbolically, then you can choose to illustrate with numeric examples and play around with the values, with dynamically updating graphs/illustrations and everything.

Yonatan:

> I read over your post and do find writing a textbook potentially interesting, but I have a few notes/questions.
> 
> 1. What will this new system accomplish that something like wikibooks doesn’t? (example: http://en.wikibooks.org/wiki/Real_analysis/Counting_Numbers )
> 2. In response to “I want to start compiling a list of math problems that have nice solutions or common tricks. “, there already exists a website tricki ( http://tricki.org ) which has many really decent math tricks in many difficulty levels.
> 3. I’ve heard that LaTeX2html works well (though I haven’t tried it myself). If that works, you can just \ref another section/proof which will link you to it.
> 4. For the dynamic graphs for algorithms, do you have any specific ideas in mind? I can’t think of many examples where such a system would be very relevant in mainstream mathematics. It could be because I’m tired, but I can’t think of many basic algorithms besides the Euclidean algorithm and random ones such as the Gram-Schmidt process. Maybe this would be better suited for something like computer science (or something that’s part mainstream math part computer science like graph theory).
> Sorry if I misread something or said something useless.

Ryan: 

I think it was Marko or Seva who started with the textbook idea, so you’ll have to ask them for motivation. I think that now with some of the ideas of C2T/MathBrowser, we will have a lot to offer to improve the experience of studying online over something like Wikibooks. It would be awesome to copy the content that already exists in Wikibooks to our improved interface (which you can read about in many other posts, or will be more elegantly expressed later). Again, ask Marko or Seva for other content ideas. Sadly, I never got them to post anything.

I actually posted about Tricki. This idea was written before that came out. This post is pretty old, I was just trying to dig up everything we’ve talked about.

The graph idea came to me when studying economics. But you can find several examples of where this is nice in a variety of fields with Mathematica’s demonstrations in Mathematica Player. See http://demonstrations.wolfram.com/ Another idea that I later discovered was already implemented…


## Other thoughts

* Given course objectives, generate textbook from database (perhaps structured as in [Learnstream Atomic]())
* E.g., can have different levels of rigor
* Example: Light and Matter textbook uses LaTeX conditionals and other code to generate two different versions of some of its mechanics material. However, there should be another layer so no one has to dig through and rewrite code in the tex files.
* Actually, Learnstream-like systems should just replace textbooks (obviously, supporting tablets/e-readers at some point)


