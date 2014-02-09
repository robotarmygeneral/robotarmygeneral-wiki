(BTW I wrote this in the style of a blog post or similar format that I would post when the site was ready for public beta. So some of the statements are slightly presumptuous about how I'll end up using it. )

It's too easy to spend unstructured time in a way that's not only non-productive but not even entertaining. I think the reason is that we tend to do the easiest thing. Which, if you're like me, is sitting down at the computer and loading up Google Reader or Reddit or something like that. Whereas something with just a little further reach could be a lot more fun and/or beneficial.  

Timeboxing is a good solution to not let too many hours pass by unnoticed. But I have yet to develop the discipline to think about timeboxing every time I get to a point where I'm (usually unconsciously) scheduling time. 

Here is a very simple but effective solution. 

"Shuff" (http://smooth-galaxy-737.heroku.com/) is a web app where you simply supply different lists of URLs and then visit a link that redirects you to a random item on the list. It actually renders a page with the URL and then loads that URL into the browser, so it supports bookmarklet-style Javascript as well, which I usually use for popup alerts if I don't have a URL associated with the item (like cleaning the house---though for me that should probably link to a how-to site). 
  
I have a main "Doing stuff" list where each item is a branch into some activity that I may want to do (and could potentially then timebox). The advantages of visiting my "Doing stuff" link every time I'm ready to switch gears are that I don't have to worry about making a decision and everything I need to do is covered (with some probability---and only if I've realized I need to do it and added it to the list, of course). I also get that little element of randomness that adds some fun. 

What to shuffle

Ideally, you should shuffle everything you might want to do that isn't rigidly scheduled in your day. That means that both your productive stuff ("clean the house", "study for class") and your fun stuff ("browse random sites", "get new music") could all be sitting together in the same list. If you're the type of person who is strictly in either work mode or play mode for stretches of time, then you could have multiple scheduling lists, but I feel that less lists means less cognitive load, and you can always "roll again" if you really aren't in the mood.

On the other hand, if you have one main "Do stuff" list it can link to the random item in other lists. So instead of an alert to browse news sites, I just have a link to my list of news sites. (Or you can do both, just to let yourself know what's about to pop up.) 

Balancing

Being able to re-choose as much as you want means you don't have to make your list perfectly balanced. Also, you get to decide how long you spend with each activity.

However, there is some choice in terms of what to collect into one item. I like to group things by rough states of mind. So I wouldn't have "Sites of interest" but rather a "Mindless sites" list and a "Learn more about Starcraft" list. Each item should either link to another list or have some clear starting point. Finally, so I don't have to do a lot of maintenance, the items are typically things that are fairly permanent. So I use "Watch current Chinese show" (which I keep linked in my bookmarks bar) vs. "Watch particular show X".

Finally, there are always things that don't make sense to do at random times, like "Recipes to cook" or "Places to go on a date". These examples though I would consider "rigidly scheduled" so that they don't belong in the main list. But you can always create side lists that you can visit at those scheduled times.

Timeboxing

I want to experiment with opening or running some kind of timeboxing thing as well, so that I don't even have to think about that. Something like this works already:
javascript:window.open("http://mail.google.com/", "_newtab"); javascript:window.location.replace("http://e.ggtimer.com/10%20minutes");
But it'd be nice to have a checkbox or something on the site that will add something automatically.

Tracking

In addition to or instead of dictating the time to spend on each activity, one could imagine that this service can tie-in nicely with personal informatics. The advantage over other services (like RescueTime) is that it can potentially hold all types of activity you do (perhaps only as a javascript alert, but it is still represented), and that things are already categorized. 

Other example uses 

* The idea of random immersion that I mentioned briefly before: One of my "Doing stuff" links is a link to a random list of Chinese sites that seem to potentially have interesting stuff. If one resource is spent, I'll delete the link. Some of the links are to general search or portal sites, which gives me a chance to sustain the link population. Most importantly, it's giving me a chance to play around in a lot of sites with natural use of the language without having to plan out each time I want to get some Chinese exposure.
* I've been using it as the primary way to listen to music with a huge list of mostly YouTube links with a mix of favorite songs and songs I've heard about (as well as Pandora and some other ones that do continuous playing to provide a fallback while the list is still too short to have enough variety). Since I usually do this in parallel with other stuff, it's a link on my bookmarks bar rather than in "Doing stuff".  I do have a "Doing stuff" link that involves discovering new music to add (which links to a shuffle of review and social sites). 
* Restaurant chooser with links to Yelp or Google places. This is an example of how "many shallow lists" can be a good idea (and a way to avoid needing tags or other complexity for the site): Have a list for Italian, Chinese, expensive, fast, or however you want to break it down based on your mood. Then have another list for when you aren't picky that just links to each of the more specific lists. So you can have any level of hierarchy or even infinite loops if you see it fit. Overlap might happen, but it's usually not a huge deal that something is slightly more probable, especially if you've bothered to list it multiple places. (The sublists idea can also work well for music, I just realized -- I definitely want a party music list (even though I'm not in college anymore).)

Neal:

> Quite cool. Future feature: let people publish their lists. This could be really cool, eg, a list of restaurants or a list of music.
> 
> Something i've been thinking about on and off since last semester-- when reading articles/blog posts/etc., I often find myself opening up a shit ton of potentially-interesting links in new tabs. However, I often don't have the stamina or the time to actually read through them. But, imagine if there was an easy way to bookmark the link in a Shuff! list. Then, when I want to read more on topic X at some later date, I can easily get a random related link from my list.

Updates and tips:

* Toolbar when you shuffle a category, including its own timer! A few sites aren't happy with being iframes, but then you can just click the link on the toolbar. When you reshuffle, even when following to other categories, the timer is perserved. 
* The timer can be set from the category page (where it lists the links) before shuffling or from the toolbar.
* YouTube videos will be embedded directly and reshuffle when completed.
* Use 
#My text here
to display a note that says "My text here"
* Use
j:alert("hey! it's javascript");
or 
javascript:alert("hey! it's javascript");
to execute any javascript commands (multiple commands can be separated by semicolon). The advantage of the latter syntax is that you can click to re-execute in the toolbar.
* Use 
/shuffle/xx 
where xx is the category number to shuffle other categories. E.g. use it to shuffle subcategories of songs or actions within a task. Remember you can use the timer here, so if you don't want to manually type the timer every time, use
/shuffle/xx?timer=yy
where yy is the time in seconds. For example I might do /shuffle/22?timer=600#household to shuffle among household chores (e.g. "#Do the dishes") for 10 minutes. The #household has no effect other than to remind me what the link is.
* See what kind of crazy shit you can come up with. Implementing fancy features is nice, but it's even more satisfying when you realize you can already do it with some combination of javascript, wacky urls, and category-abuse!

A nice set of features would be adding or deleting the current iframe url from the current category (for my Chinese links, I usually use the shuff'd links to find new ones; alternately, you mind want to be able to quickly delete, say, a song that you have gotten sick of). Unfortunately, it seems that the url is actually quite difficult to access. Bleh, maybe I just need to make a browser extension...
