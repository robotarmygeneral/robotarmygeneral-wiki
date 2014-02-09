Our goal is to create a compelling online community for math competition enthusiasts, focusing primarily on the high school level. We intend to increase community interaction by implementing several features that enhance user exposure and allow greater interaction. Some such features include:

* Feature-rich user profiles including competition results and mathematics-related interests and activities.
* Directory of traditional mathematics competitions and events across the United States (and possible worldwide in the future) including general information edited by the community in the spirit of wiki applications, a list of community users attending the event, and discussion and user ratings/evaluations.
* Hosted online competitions, both team and individual based, with pre- and post-game discussion as well as listed results and possibly prizes.
* Freely-creatable, customizable group pages (such as for school teams, temporary competition teams, or math circles) with announcements, discussion, problem columns, and competition information and results. This could become a standard for math tournaments hosted by schools and new school math clubs.

## Integration with Existing Communities

This project does not intend to compete with any existing communities; rather, we want to improve the options for math student by increasing of the quality of community interaction and making it easier to gain information online.

Art of Problem Solving (http://www.artofproblemsolving.com) is by far the largest online math competition community.

* AoPS hosts a number of user blogs. However, there are limited options for sorting, filtering, or aggregating the data. Some of the entries, with user permission, could be aggregated through features of our site.
* The AoPS Wiki contains a wealth of community-authored information on mathematics competition and problem solving concepts. Ideally, we would like to reuse as much information as possible. AoPS Wiki currently has no official documentation license1.

[The iTest](http://www.theitest.com) is a “free online mathematics competition for high school students throughout the United States and abroad.” While the iTest continues to gain momentum, it has not achieved a vibrant math community largely because it does not offer a sufficient amount of user exposure and interaction. We would like to form a partnership with iTest by offering a social network to host their competition, which has already established a strong user base and problem writing.

## Technology Overview

Our goal is to keep in tune with current but well-established trends in web development.

To allow our community to interactive with broader social networks and other web services, we will attempt to create as open an architecture as possible in hopes that integration with other websites will exist or can be created in the future. Just a taste of the many ways we would like to see interactions with other web applications:

* Importing profile data from other communities
* Exporting data such as competition results to other profile, for example as a Facebook app.
* Exporting information to productivity apps, such as competition dates to Google Calendar.
* Syndicating problem columns and problem solving discussion with RSS.

The best available option for creating a social application API is the newly released OpenSocial API from Google, which is being adapted by major social network sites across the board. The OpenSocial API also always the use of Google Gadgets to make content available offline.

The community could be implemented in any language and web platform such Ruby on Rails, PHP with CakePHP, or Python with Django.
