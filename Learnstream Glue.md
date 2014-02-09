# Discussion

## Initial proposition 

Learnstream Glue is about using personalized learning pages.

It's similar to [Fruit](Learnstream Fruit) (or some of our recent discussion of [Atomic](Learnstream Atomic)) but with a focus on these PLPs. These involve both the community build-up of a course as well as the personalized content, exercises, and community discussion. You'll see how!

Again, we introduce an ordering on components in the course. Each component will have its own PLP. For a new course, we can even have a initial bank of questions that could help generate new components as the topic is explored (so it may work as a collaborative research tool as well). The pages work a little like a wiki, where you can also add resources such as video clips and exercises and have group discussions. Perhaps you can try to import initial content from Wikipedia, StackExchange sites, etc.

When you've just enrolled in a course, you'll be able to browse the PLPs in sequence, viewing all of the publicly available resources. You can also customize the pages by adding content (publicly or privately) and choosing which resources to include or hide. Figuring out how to store a combination of private and public edits seemed like a hassle, but that was before I knew about gitit. The obvious solution now seems that each user has a branch, and they can choose push to or merge with the public branches. Just need some kind of web interface on top of that... (and allowing git for power users would be great)

Of course, we'll offer some sort of SRS tool for going over the exercises that you've chosen to include that link back to respective PLPs. Pages without any exercises can have a default "remind me about this page" option.

Bring home message here is: You get the resources of a wiki without the bloat. Combine that with SRS and you've turned the data of the web into a lean, mean learning machine just for you.

Open questions:

* Thinking back to [LSSoup](Learnstream Soup), how will we alert people when there is new discussion or resources available for their pages?
* Are components the best way to break up pages?
* Will users be okay with the "sequence of pages" interaction, or do we need a more fluid way to handle viewing lessons (whatever those are) as well? 
* How will users perceive the cost and benefits of customizing their own pages? Of course, not all users are created equal. Some that may be more inclined include teachers who want to create a custom course from a standard curriculum (basically the definition of a teacher, so if they find our tool easy to use, it could be a winner) or an active researcher in a field, who learns from the existing pages, publishes a couple new ones, and earns a PhD!

## Neal's response

First impression: I really like this. In my mind, it also has more potential to be the "learning platform of choice" than any of the previous implementations of learnstream... if we can hit the user interaction model and make it super easy to deploy, it could be a killer app in almost any classroom setting.

Some questions I have:

* What if a user wants to push some edits but not all to the public branch?
* How do we gracefully manage merging for those not accustomed to git?

However, i think it has some very distinct advantages over previous ideas:

* Students are invested in their own learning. By having "personal learning pages", a student can own the content in a way not currently available.
* We could push the lofty open education ideals, and make students feel like they are contributing to the public knowledge base by contributing. (which they would be!)
* The lofty open-education ideals may be a yet-unexploited point of entry for social learning. We've talked a lot about sharing with your friends and/or classmates, asking for help, etc. But, the wikipedia social model could be very compelling in this arena. And with git, it'll be easy to track everyone's contribution (which could be tied into some gaming/badge/"impact score" features).

Thoughts on Ryan's open questions:

* Notifying users: one idea-- when someone merges into the public branch, they tag it as "major" or "minor" (and add some helpful commit messages!!). Then, everyone else can see when they log in if there are major/minor changes to their pages, and either approve or reject them for their local branch. They could also select (or opt out) to get emails for "major" revisions, which would be things like new substantive content, etc. (instead of fixes to typos, etc.)
* Components as delimiter: I think they are decent, but not necessarily the only way. I feel the guiding principle should be "is this a small enough concept to understand in one sitting, but large enough to be interesting?" We don't necessarily have to keep ourselves locked into the component model if that doesn't seem to be working.
* Ordered sequence?: I think having an order is good, but make it easy to navigate anywhere in the sequence. In terms of exercises, I think a user should select to add the exercises at the end of a page, so they can skim without necessarily committing to study. ANOTHER IDEA: let users define their own "course" through the course! That is, users could specify alternative orderings, and share those with the community. Or fork and completely revise.
* Cost/benefit of customization: Users can always go with the public branch and not make changes/modifications. But, if personal notes are encouraged in the interface, they'll likely have _something_ to add! In a classroom setting, teachers might make customizations a requirement (ie, the students are supposed to collectively build up the "class knowledge stream" as the course progresses...) Having a good way to import material will make this easier. 
