Étude: teaches mastery through precise and careful repetition. [I like this book already!] Do them with the whole team, in a place where you can break into small groups and use whiteboards. Debrief for a few minutes afterward.

Phases are week-by-week release cycles with planning, analysis, design & coding, testing, and deployment all going on in that cycle.

Product manager + 2 onsite customers per 3 programmers. One tester per 4 programmers.

First steps:

Include a vertical stripe of the application for the first iteration.

For the first story, work with the entire group together (one driver). 

Have coding standards discussion.

Root-cause analysis: Ask why 5 times.

Get verbal agreement at the beginning of an activity -- will motivate people to further participation.

Daily stand-up meeting <10 min, ~30 sec updates from each member; quickly negotiate pairs or advising for the day

Weekly Iteration demo: ~10 min. Don't simplify or exaggerate problems. Release a demo for customers.

## Roles
 
customer: define the software, do release planning, lead weekly iteration demo, provide requirement details upon request, review work in progress, create detailed customer tests (including product managers, domain experts, interaction designers, business analysts)
two customers per three programmers
 
programmers: coming design, tests, and coding into single activity; generalizing specialists
 
testers: exploratory testing, not looking for bugs
one tester per four programming
 
coaches: maintain disciple, responsible for reporting
 
smallest team: 4 programmers, 1 project manager
 
## XP Practices
Sit Together, Real Customer Involvement, Ubiquitous Language, Stand-Up Meetings, Coding Standards, Iteration Demo, Reporting
Releasing: Done Done, No Bugs, Version Control, Ten-Minute Build, Continuous Integration, Collective Code Ownership, Documentation
Planning: Vision, Release Planning, The Planning Game, Risk Management, Iteration Planning, Slack, Stories, Estimating
Developing: Incremental Requirements, Customer Tests, Test-Driven Development, Refactoring, Simple Design, Incremental Design and Architecture, Spike Solutions, Performance Optimization, Exploratory Testing
 
## XP concepts
Refactoring: changing structure of code without changing its behavior
Technical debt: total amount of less-than-perfect design and implementation
Timeboxing: especially for meetings, research, discussion
Last Responsible Moment: delay commitment to make better decisions
Stories: self-contained, individual elements of the project---one or two days of work---customer-centric
Iterations: full cycle of design-code-verify-release---preferably one week long
Velocity: consistent estimate of effort
Theory of constraints:  programmers set the constraint for throughput
Mindfulness: pay attention to process and practices of development
 
## Equipment
Pairing station
Dedicated build machine
Two big magnetic whiteboards and other whiteboards
Large plastic calendar
Plush toy as integration token (Ch 7)
Inspirational pieces
Unit-testing tool
Build tool
Index cards---5000 white, 2000 of each color
Pencils
Food
Flip charts and painters tape
Dry-erase markers, flip-chart markers
Magnets

## References
Domain-Driven Design
Patterns of Enterprise Application Architecture
Refactoring - Fowler
 
First iteration: one feature with several stories; vertical stripe (meaning go deep for one feature, I think)
10-20 stories in the first planning session and estimate
guess velocity
work on first few stories as a group; use projector
 
## Progress quiz
Do programmers critique all production code with at least one other programmer? (Yes-5)
Do all team members consistently, thoughtfully, and rigorously apply all the practices that the team has agreed to use? (Yes-75)
Are team members generally focused and engaged at work? (Yes-5)
Are nearly all team members aware of their progress toward meeting team goals? (Yes-4)
Do any problems recur more than one per quarter? (No-5)
Does the team improve its process in some way at least once per month? (Yes-5)
Do programmers ever make guesses rather than getting answers to questions? (No-75)
Are programmers usually able to start getting information (as opposed to sending a request and waiting for a response) as soon as they discover their need for it? (Yes-4)
Do team members generally communicate without confusion? (Yes-4)
Do nearly all team members trust each other? (Yes-4)
Do team members generally know what other team members are working on? (Yes-1)
Does the team demonstrate its progress to stakeholders at least once per month? (Yes-4)
Does the team provide a working installation of its software for stakeholders to try at least once per month? (Yes-1)
Do all important stakeholders currently trust the team's ability to deliver? (Yes-3)
Can any programmer on the team currently build and test the software, and get an unambiguous success/fail result, using a single command? (Yes-25)
Can any programmer on the team currently build a tested, deployable release using a single command? (Yes-5)
Do all team members use version control for all project-related artifacts that aren't automatically generated? (Yes-25)
Can any programmer build and test the software on any development workstation with nothing but a clean check-out from version control? (Yes-25)
When a programmer gets the latest code, is he nearly always confident that it will build successfully and pass al its tests? (Yes-5)
Do all programmers integrate their work with the main body of code at least once per day? (Yes-4)
Does the integration build currently complete in fewer than 10 minutes? (Yes-4)
Do nearly all programmers share a joint aesthetic for the code? (Yes-1)
Do programmers usually improve the code when they see opportunities, regardless of who originally wrote it? (Yes-4)
Are fewer than five bugs per month discovered in the team's finished work? (Yes-1)
Do nearly all team members understand what they are building, why they're building it, and what stakeholders consider success? (Yes-25)
Do all important stakeholders agree on what the team is building, why, and what the stakeholders jointly consider success? (Yes-25)
Does the team have a plan for achieving success? (Yes-4)
Does the team regularly seek out new information and use it to improve its plan for success? (Yes-2)
Does the team's plan incorporate the expertise of business people as well as programmers, and do nearly all involved agree the plan is achievable? (Yes-3)
Are nearly all the line items in the team's plan customer-centric, results-oriented, and order-independent? (Yes-4)
Does the team compare its progress to the plan at predefined, timeboxed intervals, no longer than one month apart, and revise its plan accordingly? (Yes-4)
Does the team make delivery commitments prior to each timeboxed interval, then nearly always deliver on those commitments? (Yes-4)
After a line item in the plan is marked "complete," do team members later perform unexpected additional work, such as bug fixes or release polish, to finish it? (No-25)
Does the team nearly always deliver on its release commitments? (Yes-3)
Are programmers nearly always confident that the code they've written recently does what they intended it to? (Yes-25)
Are all programmers comfortable making changes to the code (Yes-25)
Do programmers have more than one debug session per week that exceeds 10 minutes? (No-3)
Do all programmers agree that code is at least slightly better each week than it was the week before? (Yes-25)
Does the team deliver customer-valued stories every iteration? (Yes-3)
Do unexpected design changes require difficult or costly changes to existing code? (No-3)
Do programmers use working code to give them information about technical problems? (Yes-1)
Do any programmers optimize code without conducting performance tests first? (No-3)
Do programmers ever spend more than an hour optimizing code without customers' approval? (No-3)
Are on-site customers rarely surprised by the behavior of the software at the end of an iteration? (Yes-4)
Is there more than one bug per month in the business logic of completed stories? (No-3)
Are any team members unsure about the quality of the software the team is producing? (No-1)
 
## Ch 5. Thinking
 
Pair programming: give time for correcting little mistakes; laptop on hand for quick research; research together for longer time; sometimes split up; switch roles at least every half hour; encourage less experienced coders to research a particular topic beforehand; ping pong pairing: write a test, pass and write, and repeat; say you're tired is partner is cranky; switch when feeling stuck or frustrated
 
Energized work: go home on time; healthy food in workplace; eat lunch together; take a break when getting angry; revert code that doesn't pass at the end of the da; 
 
Informative workspace: buzz of activity is good cue; use whiteboards; big visible charts---iteration and release planning, team calendar; keep the chart updated; charts for improvement (amount of pairing, pair switching, build performance, support responsiveness, interruptions)
 
Root cause analysis: ask why five times
 
## Chapter 6. Collaborating
 
Sit together
 
Daily stand-up meetings: pre-set time; new information for the team; 30 seconds per person; suggestion: just before lunch; determine pairs
 
Coding standards: create some
 
Iteration demo: 10 minutes; invite stakeholders; introduction: list of stories with explanation and demonstration; ask "Is our work to date satisfactory?" and "May we continue?"; create usable deployment; write new ideas on cards; root cause analysis if nitpicking continues
 
Reporting: create and update vision statement; weekly demo serves as report; status email to supplement demo
 
## Chapter 7. Releasing
 
Releasing étude: consider all activities between an idea and a release to real customers; group into days; write down tasks (red card) along with shortest, longest, and average time to complete them; discuss and write down solutions to reduce the time (green card).
 
Story completion criteria: tested, coded, designed, integrated, builds, installs, migrates, reviewed, fixed, accepted
Make a little progress on every aspect every day. 
 
Only count "done done" stories towards velocity.
 
Test-driven development should reduce the number of bugs to begin with. Fix bugs right away. If a bug is too big to interrupt a task, add it as a story and announce it. Collectively decide whether there is enough slack to fix the bug. After finding a bug, do a root cause analysis. 
 
Use version control. Use version control to do "diff debugging": go backwards and forwards in check-ins until isolating the bug. Store the whole project, other than generated code, in one repository. Never check-in code that breaks the build.
 
By the end of an iteration, all stories are done done.  Add a tag for iterations and releases.
 
Integrate code every few hours, and keep release infrastructure up to date. Necessary: successful build. Sufficient: significant change, something others want. Throw away unintegrated code at the end of the day.
 
Use central integration machine. To update: ensure integration token is available, update from repository. To integrate: update, get token, check in code, run build on integration machine, replace token. 
 
Use collective code ownership.
 
Reduce documentation.
 
## Chapter 8 - Planning
 
Create a cohesive vision and document it in a vision statement: what, why, success criteria---use to prioritize stories.
 
Plan releases around minimum marketable features
 
Try to make each story individually releasable (vertical vs horizontal stripes)
 
Use timeboxed release plans (e.g. once per month)
 
Plan at the last responsible moment 
 
Planning game: customer knows value, programmer knows cost
1. create or select story
2. programmers estimate story
3. customers place story in order of relative priority
4. repeat until all stories estimated
 
Good XP teams achieve a stable velocity
 
Iteration timebox doesn't prevent problems but reveals them
 
Use iteration demo at the end of an iteration
 
30min - demonstration previous iteration
1hr - retrospective on previous iteration
30min-4hr - plan iteration
5min - commit to delivering stories
develop stories
prepare release
 
velocity of previous iteration: sum of estimates of "done done" stories
 
iteration planning: brainstorm then estimate tasks in terms of ideal person-hours. for tasks over six hours, break into smaller tasks. combine small tasks less than an hour. make sure everyone agrees with the plan -- verbal "yes".
 
at end of iteration, delete code for partially completed stories
 
batman - programmer who takes care of emergency situations; should be a rotated position
 
decrease number of stories if velocity is unstable; increase if it is rock solis less than an hour. make sure everyone agrees with the plan -- verbal "yes".
 
at end of iteration, delete code for partially completed stories
 
batman - programmer who takes care of emergency situations; should be a rotated position
 
decrease number of stories if velocity is unstable; increase if it is rock solid. ~10% of iteration on technical debt. dedicated research time: half a day per week, create small demonstrations of what you've learned. 
 
story - placeholder for a detaile discussion about requirements. represent customer value and written in customer terminology; objective completion criteria. use index cards during iteration planning. 4 to 10 stories per iteration. create documentation stories if needed. 
 
## Ch9 - Developing
 
developing étude: analyze a section of the code in pairs (15min), discuss in large group (15min)
 
use business logic rather than user interface actions to describe tests
 
key to TDD: small increments
 
(skipped a lot of the coding practices stuff)
 
be careful when refactoring tests -- you may want to break the test again to make sure you aren't writing a tautology
 
principles of simplicity: don't add what you don't need (according to stories), don't repeat yourself, self-documenting code, isolate third-party components, limit published interfaces
 
start with the simplest possible design that solves only one specific problem. incrementally generalize.
 
use spike solutions to experiment when new information is needed.
 
performance stories, if necessary, need a concrete, customer-valued goal.
 
skipped exploratory testing
 
Part III is pretty philosophical, so skipped the notes.

# Summary for summer project

##  Vision & roles
Loosely, we have three programmers and one product manager, Neal, who is playing the customer. In other words, Neal is trying to get an excellent product developed on behalf of HMC, and the rest of us are doing our best to deliver value through designing and developing that product (Ok, it's not really that distinct). The product vision is something I wanted everyone to work on together, so we can talk about it on, perhaps, Monday evening. These are some of my thoughts in one format: http://gosuapm.pbworks.com/w/page/39577731/LS-Atomic AoAD offers a different format that we can also adapt it for. But anyway, the vision is important! It is the purpose of the next eight weeks, and all of our decisions go towards that vision. 

##  Weekly iteration
We do major planning and product demos every week.

* Demo: Every Thursday at 1PM, we will meet with Joseph Vaughan (and possibly others such as physics faculty) to discuss and showcase our progress. This includes only totally complete ("done done") features.
* Iteration planning. After the demo, we spend about an hour planning the next week. This consists of creating stories---features/feature groups of a certain size written in terms of adding value to the product--- (on index cards!) and then collectively prioritize them and estimate the time required. Using the Pivotal Tracker tool, we enter the stories and eventually develop a velocity, which helps us estimate the amount of stuff we can get done.

##  Daily schedule

We work 9am to 6pm with an hour lunch break, Monday through Friday. Occasionally we may do a weekend day. Each day around 11:30, we meet for a very brief standup meeting to discuss what's been accomplish and plan pairing for the rest of the day. Of course, we are working in very close proximity, but it'll be good to have a bit of dedicated time to share thoughts.

##  Agile/extreme programming practices.

* Pair programming: we work in pairs with one person (mostly) coding and the other person (mostly) thinking ahead about the next steps. Except when Neal starts doing physics stuff, and then we'll be forced to have someone solo, switching off every couple hours probably.
* Test-driven development: The rails tutorial should have introduced you to this, but it doesn't talk about the strategy much. I've ordered TDD By Example for you to learn it better. It will be a steep learning curve, but I do think it's worthwhile. 
* Collective code ownership & version control: The first basically means that we all work on all parts of the code to add stuff, fix bugs as soon as they are found, and refactor to make it more clean. The repository stuff will be taken care of with Git. I don't think we need a dedicated build machine/integration token like in the book unless it becomes a problem.
* Minimal commenting/documentation! Seriously, just look at the code; it's self-documenting, especially when pairing the tests and implementation. So let's not waste time. However, we will add stories for any reports that we may have to do for HMC as well as stuff like user manuals.

##  Tools and standards 

* I drank the vim kool-aid. With pairing, it will be better for everyone to use the same thing, so I recommend it. Didn't take long at all to learn to use adequately. 
* Ruby. Rails. JQuery. Git. Rspec. Others to be decided. (Capybara? Jasmine? ERB vs Haml?) I don't really have a style within these, and I'm guessing no one else does, so that'll have to be developed on the go.
