# Generic question templates for Learnstream.
 
For LaTeX, use the traditional dollar/double dollar signs! 

$x^2 = 5$ is irrational!
 
TODO: This isn't working for me, I think it may be a Chrome thing but i'm too lazy to start up firefox on this machine.

Questions to answer in general:

* Does it check step-by-step work of the student?
* Does it show hints or show examples?
* Does it require justification input for steps?
* Do students input freely or from a dialogue menu? 
 
## Faded Example
 
### Description

Student sees a problem with a worked solution, where some steps are faded out (which they have to fill in). More details from Google Docs:

* if a concept or rule C is in the current learning focus and if the mastery of C is at least medium, then fade one or several parts which require C as a prerequisite
* if low-ability student, then prefer fading steps backwardly in the solution or fading conditions
* if low-ability student, then prefer fading parts inside a problem solving step rather than parts between steps
* if the learning-level goal is knowledge, then fade parts of problem statement, sub-goals, known assumptions or used facts
* if the learning-level goal is comprehension, then fade reference, justification for a step, explanations, or auxiliary information
* if the learning-level goal is application, then fade a step, a condition of a step, or a sub-solution, (sub)goal statements
* if the learning-level goal is meta-cognition, then fade links to other instructional items, meta-cognitive structure (headlines), or meta-cognitive heuristics
* start with smaller gaps and enlarge them gradually towards the end of exercising (i.e., depending on the learning history)
 
 
### Pros 

Demonstrated effective in several studies. Faded examples are a good way to learn -- they invoke active recall but are compatible with cognitive load, they also take advantage of our ability to mimic what others do (how do we use analogy to apply these examples to related, but not identical, problems?)
 
### Cons

Collaborations draw out long-term memories and also allows misconceptions to be observed and (hopefully) corrected (by what processes do we draw up these memories?). Direct problem solving (without aid/prompts from site) is what is ultimately tested, but studies seem to show faded examples still work.

Can we combine collaboration and faded example effectively?
 
 
## This question is like....
 
### Description
After seeing a faded example, the student is asked a question such as, “which of the following problems is mathematically (physically?) equivalent to the problem you just did." The possible answers could be pulled from problems they've already done, or new ones. They might further be asked to identify which aspects are equivalent, or what the similarities are (ie, conservation of momentum, etc.).
 
### Pros
Hopefully this will help show connections between different problems. Also, it will promote thinking in terms of the big conceptual ideas, as these will be repeatedly emphasized. It will also help them identify patterns in particular types of problems, which should help them pick out the key features which suggest a particular approach. When seeing a new problem, they will be able to identify what concepts are at play and hence have a good lead on how to approach the problem.
 
### Cons
 
 
 
 
## Spaced Recall of conceptual steps
 
### Description
After seeing a faded example of some problem, the student is asked to identify the major conceptual steps in solving the problem (ie, apply momentum conservation, then work-energy theorem, etc.). This should be done immediately following a faded example (the first repetition), and then repeated later based on SRS algorithm.
 
### Pros
Advantages of SRS, while avoiding the busy algebra. Promotes thinking in terms of big concepts (modeling good thought processes when approaching a problem).
 
### Cons
???
 
## Khan Academy-style
 
Only check the answer. Allow student to draw on the problem area. Present sequential hints when requested. Link to related video.
 
# Example problems

Question:

A 2000-kg car in neutral at the top of a 20.0 deg inclined driveway 20.0 m long slips its parking brake and rolls down.

If we ignore friction and drag, what would the magnitude of the velocity of the car be when it hits the garage door?

Solution 1 (kinematics):

1. vf^2 = vi^2 + 2ad 
2. vi = 0
3. a = g sin(20)
4. d = 20
5. vf = sqrt(2*g*20*sin(20))

Justifications:
1. minor principle 2. given ("car in neutral") 3. force component (minor principle?) 4. given 5. algebra

Solution 2 (energy conservation):

1. Potential energy is m*g*h. 
2. Final energy is 1/2 m*vf^2. 
3. m*g*h = 1/2 m*vf^2
4. vf = sqrt(2*g*h) = sqrt(2*g*20*sin(20))

Justifications: 
1. major principle 2. major principle 3. major principle 4. algebra

## Faded example


Suppose the user is trying to review the idea that kinetic energy = 1/2 mv^2.

User sees:

A 2000-kg car in neutral at the top of a 20.0 deg inclined driveway 20.0 m long slips its parking brake and rolls down.
If we ignore friction and drag, what would the magnitude of the velocity of the car be when it hits the garage door?

1. E_init = m*g*h. 
2. [                             ]
2. E_init = E_final
3. m*g*h = 1/2 m*vf^2
4. vf = sqrt(2*g*h) 
5. vf = sqrt(2*9.81 m/s^2*20.0 m*sin(20.0 deg))
6. vf = 11.6 m/s

Some options for what the user might do:

* Type in E_final = 1/2 m*vf^2
* Choose parts of the equations from a drop down or other type of interaction
* Fill in one part within the equation
* Not fill in anything, just click to reveal the part and then self-rate

In addition to that, justifying the step:

"The potential energy of the car has been converted entirely to kinetic energy. Kinetic energy is given by 1/2*m*v^2"

Does the user enter this? Is it somehow verified? When is the correct answer shown?

Do we then link to a video of a similar problem? Provide links to explanation of kinetic energy (which may then contain video)? Always or only if the student gets it wrong? Is the student "forced" to read or watch something if they miss it? 

Of course, only fading the one step is kind of silly because the user can easily "game" it by following the other equations backwards.

Maybe we should just show

1. E_init = m*g*h. 
2. E_final = ?

Then when the user fills in E_final, it will reveal the rest of the problem. If the user can't get that step, it reviews kinetic energy without finishing the problem.

When the system determines that the user has all of the required knowledge, then it will just show the problem from the beginning. That will ensure the user gets some practice with full problems.

# Thoughts

One thing to keep in mind is that students should understand the derivation of vf^2 = vi^2 + 2*a*d, but it is probably useful to memorize. 

I'm thinking that we should have a list and entries for all our major and minor principles. So of course the entry for this could show its derivation. But maybe something more intelligent where the student can choose to expand the steps showing the derivation? 

Doing full problems also raises some questions. If a user gets stuck on the problem, what do we show them? Assuming we have a spaced-repetition backend, are we going to count a miss for any of the components? If they get it right, do we rate a non-miss for every component? What if there are multiple solutions to the problem? 

By the way, I'm thinking that doing hints on the level of Andes is out of the scope for this summer.

