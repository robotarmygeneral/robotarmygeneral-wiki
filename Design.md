# Procedure

Although I'd really like an expert's take on this, here's what I've come up with as the guesstimated expert's approach to web design. An approach I have never really taken. (I've done steps 2 & 3 a few times but many years ago.)

Step 1. Understand the purpose and audience of the site

This is one of those cliche things that seems not too productive, but one thing that I do really like and have seen immediate benefits from is "researching" by which I mean "ripping off" related sites. But it's important to choose the correct sites. 

As I've discussed before some of the most similar sites are Khan Academy, Alcumus, the former smart.fm.

In addition, here are some non-trivial properties of LS:

- Users will spend a large amount of time interacting with the site directly.
Pretty broad, but it can help us eliminate some sites from the radar (Google front page, Amazon, product pages) -- although those can be considered for minor design elements. The obvious "success" example here is Facebook, with Twitter and Reddit as some secondary sources.

- Users interact with video on the site.
Examples: YouTube, Hulu, Netflix are the most popular sites, but they don't really do video plus another area of focus the way we are. In fact, I'm having trouble thinking of anything where the video isn't the sole primary focus.

- Users maintain some form of state with the site.
Examples: Other than KA and Alcumus?? There are a lot that do points and achievements (which we haven't really even started thinking about yet). Email/Reader are kind of like maintaining a state... Other than things that are strictly games, I'm having trouble thinking of sites that allow you to progress through and keep track of it. Some things to thing about: Mint, Scvnger, daily deal sites (you progress through the days and keep track of the deals you've earned?) It seems like the most compelling sites either have a lot of aggregated or regularly produced content and/or are social. Oh, and Quora/StackOverflow are for a certain type of learning and have progression. Other general badge/achievements/points sites and services: Kongregate, zynga, xbox, foursquare, http://getglue.com/ (hadn't heard of it, kinda like my last Ideas post), http://www.score.ly/ lol

- Users go to the site to learn.
Examples: Well, we've collected many many, but let's consider some that are popular other than those mentioned above. 
Nixty (still can't figure out how to log in), Udemy, and Academic Earth, for example, have seemed to have trouble getting off the ground.
A really really cool looking, new site is codeschool.com
Other sites with decent to good design: http://openstudy.com/ http://www.knewton.com/ http://sat.collegeboard.org/home http://www.wiziq.com/ http://www.spaceded.com/ http://education.skype.com/ http://www.nature.com/scitable/study-center http://www.skillshare.com/learn http://www.studyblue.com/
mmm...white and blue

In a later installment, I'll actually grab some screens from some of these sites and discuss some of the details. Unless.. someone beats me to it??!? 

Step 2. Design the site in Photoshop (or maybe Fireworks)

I've been feeling more and more that it's really important to break away from the constraint that incremental CSS improvements impose on you. 

Step 3. Convert from photoshop to site

Auxiliary stuff: understand layout -- I read a really short book that talked about alignment and contrast, these are definitely important; understand typography -- I don't

# Examples

## Codeschool

Let's first take a look at the beautiful new Code School. 

Of course, one of the hard things about doing this analysis stuff is that you already have to know what to look for. Nevertheless, let's dive in.

Visceral reactions: Very cool design. No blue and white! It's fairly "flashy" in the use of a lot of images, textures, etc. but not gaudy (well unless you count all the zombie stuff) and very easy to use. The buttons and text really stand out. I feel like the strong theme and dark colors make it more immersive compared to something that's bright and blue, which looks professional but feels less like something I'm adventuring into, but, hey, Facebook/Google/etc are doing fine.

Course design: This is the home page. Of course, it is a bit of a different context from ours since they are trying to sell stuff. In full screen, the first 40% is mostly trite marketing stuff. Well, I guess that's better than 100% of the screen as we currently have it.. There are a wide variety of typographies, textures, shadings, borders that provide a slick look with strong contrasts. Each course gets a prominent box making up a 2x2 grid in total -- this makes sense as that's basically all the content they have. (See peepcode or lynda.com for an example of something with a wider selection. But I think the lesson for us is that we should not try to design for what might be (a huge range of diverse courses) but instead for what is happening right now -- either ONE course or a small selection of courses within a single niche.)

Video UX: Play the video like any other. The first Rails for Zombies episode is less than 6 minutes and broken in 7 chapters, displayed on the right. The one button outside of the video player is either "Start level" or "Resume level", which takes me to the code challenges whether I've just started, finished, or am rewatching the episode.
Design-wise: actually quite minimal: video, chapter listing, download links, and the one button.

Code challenges UX: Great idea here. After a lesson, you do some coding challenges to test your knowledge. Realistic command line feedback is excellent, but it doesn't actually evaluate things that don't work, so you can't check on intermediate progress (of course, everything has been a one-liner so far). After completing a challenge, a congratulations is displayed at the very top of the screen; it took me a while to notice this. If I can proceed to the next level without doing the challenges, I haven't been able to figure out how. Clear visual cue of which challenges have been completed. When everything is done, the standard congratulations links to the next episode with one big button.
Design-wise: The interface looks and feels like a terminal window, great! Except for things that take me to a different page, there is exactly one text box (the terminal) and one button ("Submit code"), so it is very friendly. The contrast between "Objective" "Resources" and the text box are very strong. It's interesting to look at without background images -- the layout and contrast are still very strong, but the images definitely add a nice flair. The tags by the Objective and Answer input are nice motifs; I actually have no idea how they are placed on the page.

Courses page: Again, despite looking nice and fancy, quite simple: a progress bar, a "Resume" button, some achievements listed. Actually, it'd be nice to be able to quickly look over all the stuff I've learned... 

There's more there, check it out for yourself and get inspired!

## OpenStudy

They also have a minimalistic design. When you enter a help room, you get a sharply divided two-column page. Questions are on the left (always), and the right begins as a blank canvas with the people currently logged in to study.

You can sort the question feed by all or unanswered (two simple options only). You can also ask a question in the text box at the top.

If you click on a question, it pops up in the RH sidebar:


Again, a clean feed, well defined edges and it's obvious what you're supposed to do.

I feel that's one thing the old version of learnstream was severely missing: a clear usage pattern on each page. It should be immediately obvious what you're supposed to click on every page.

# Random links


* http://mgeraci.github.com/Less-Boilerplate/
* [A Guide to Visual Design](http://www.visualmess.com/)
* [Smashing Magazine](http://www.smashingmagazine.com/)

