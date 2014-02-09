http://www.andestutor.org/ Apparently there is a web-based verison, but it seems like I can't access it without a course key. So rather than actually use it, I read a paper about it: http://www.andestutor.org/Pages/AndesLessonsLearnedForWeb.pdf The paper is actually quite interesting. Someone else should probably take a look and make sure I didn't miss any good insights.

The goal of Andes is to be a minimally invasive replacement to pen and paper for homework submission. It also add some "tutoring" features that help students understand and correctly complete the problems. They decided on a variety of constraints in terms of what the student can input based on technical and/or pedagogical reasons. The two main instructional objectives are 

1. Students must master all major and minor principles, so Andes explicitly teaches all of them. These include a) major physics principles (e.g. Newton's second law), b) unnamed principles that appear widely in textbooks (e.g. v2^2 = v1^2 + 2*a*d), c) special cases of more general laws d) rules of mathematics, and e) common sense entailments of a proper understanding of physics concepts.
2. Andes encourages students to think about problems in terms of their major principles. 

Check out the attached image to understand the interface: 

* The problem is presented in the top left.
* Students must draw vectors and coordinate systems for the problem when necessarily. 
* Students make definitions for all variables used in the top right. I think they also choose the type of variable (e.g. "instantaneous velocity").
* Then, students enter statements (equations of scalar constants and variables) below that.
* Presumably, the final answer is entered in the text field labelled Answer.
* Help is presented in the bottom left.
* The "x=?" button presents an equation solver.
* The lightbulb presents Next Step Help, and the "x?" (I think..) presents What's Wrong Help (described next)

Andes offers help in the following ways:

* If a student does something that is probably careless, like leaving a field blank, unsolicited help appears.
* If the student enters a definition that is not part of the solution or is incorrect, it is colored red. 
* If the student enters a statement that is not algebraically correct, it is colored red. The statement may not be part of a straightforward solution, but this allows students to do some searching to get to the right answer.
* For definitions or statements that are colored red, students can get "What's Wrong Help". This presents hints in a sequence of three, starting with pointing out where the problem is, and ending with telling the student exactly what to do (which subtracts from their score).
* Andes also colors major principles red when they are not first written in their primitive form and gives appropriate hints via What's Wrong Help. This promotes the 2nd instructional objective.
* An example of the "Next Step Help" can be seen in the screenshot. If the student hasn't made any progress, Andes has the student identify the type of quantity needed for the answer from a dropdown menu then choose the first major physics principle needed from a "cheat sheet". Otherwise if the student has made some progress, it tries to get them to the next step. 

Other constraints:

* Students must define all variables they use.
* Students have to be specific, e.g. enter degrees explicitly.
* Students must use scalar components of vectors in equations rather than vector equations.
* To encourage using variables instead of plugging in values at the beginning, Andes requires high precision. 

Other insights and results:

* Short training videos for how to use the system were the only method that got positive feedback.
* Students were motivated by their Andes scores. 
* The significance of allowing equations that are algebraically correct but not in a "good" solution is that students shouldn't have to cope with being lost and having to search for the solution for the first time when taking a traditional exam.
* By providing an equation solver and immediate feedback on correctness of statements, students aren't able to blame their algebra mistakes (sign error) for what is actually lack of understanding of physics principles.
* Compared to other tutor systems, Andes should transfer readily to pen and paper. 
* The "colored red" method allows self-repair. The Andes hint system is better for this then, say, learning from a textbook because students will often repair in a shallow way like copying from a similar example.
* Students learning from physics text often repair 
* A slight majority said they would not use Andes if they didn't have to.
* Andes led to one standard deviation improvement on exam scores.

Next up I'll check out something that claims to improve learning on Andes by replacing the hints with video tutorials! http://www.learnlab.org/research/wiki/index.php/Ringenberg_Examples-as-Help

Review of the Ringenberg paper: http://etd.library.pitt.edu/ETD/available/etd-08092006-163545/unrestricted/RingenbergMichaelA-10Aug2006.pdf

* Help from hints can be abused.
* Examples can also be abused by only using "surface features" to figure out how to proceed in the problem. 
* Making students use self-explanations for the steps in the example is one way to avoid the problem. 
* By providing annotated steps (i.e. "completely justified example"), it helps the student realize what good explanations are.
* An experiment compared showing hints from the original Andes against showing completely justified examples. (I don't think it was actually videos.)
* Learning effectiveness was not significantly different but efficiency increased compared to the original Andes.

A lot more to look at! http://www.learnlab.org/research/wiki/index.php/Physics

Some reflections at the end of our project/before I throw away the paper. 

* An interesting comparison: for mechanics and E&M it covers 356 problems and 550 "components" ("a knowledge base of 550 physics rules")
* I tried to follow these guidelines for components, as I posted earlier: "a) major physics principles (e.g. Newton's second law), b) unnamed principles that appear widely in textbooks (e.g. v2^2 = v1^2 + 2*a*d), c) special cases of more general laws d) rules of mathematics, and e) common sense entailments of a proper understanding of physics concepts." e) is a case that we haven't touched that much.
* So, we basically abandoned the whole thing of helping out a student throughout a problem, which is one of the main motivations behind Andes. It may be possible to get improvements by offering a hints system, but we also need to assess how effective our "video-scaffolded" problems are. It might be interested to do some scaffolded problems with the embedded quizzes too. (Should we try to get that to show up in review instead of lessons??)
* Interesting quote: "If students are going to solve problems, then they must master all principles, both major and minor. . . Experts and competent students clearly have some other knowledge than principles, and they use this knowledge to constrain their reasoning so that they produce just the principle applications required for solving the problem." I'm definitely in agreement and trying to follow the first part. The second is something that I've been thinking about a little bit, especially as I've been making components for the integration problems, and I plan to talk about it more soon. But I like how this quote is describing the "extra knowledge" as something as simple as "restraining yourself from vomiting millions of equations" rather than some kind of mystical intuition. I.e. it may be possible to capture, define, and teach this extra knowledge without too much work on top of the core knowledge base. (On the other hand, if you take chess as an example, learning the rules is infinitesimal compared to the ability to do well without having to enumerate every possible move from a certain board arrangement.)
* It goes on to talk about the ability to identify major components from a problem as something common to physics experts. However, since this observation doesn't identify any particular "extra knowledge", Andes doesn't teach any, but it does take "encouraging students to think about problem solutions in terms of their major principles" as a second instructional objective. Something we could think more about.
* A few different approaches to teaching major principles are described. The one Andes uses is to force the principle to be written in its primitive form in one of the steps. (Recall that Andes makes students write out each solution step as an equation.)

