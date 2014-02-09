This is one of hopefully many ideas that will be sent to the group for discussion. Many existing ideas are recorded on the GosuAPM wiki: http://gosuapm.pbworks.com (ask me for access), and I will try move new ideas to there periodically if they seem pretty good. Ideas may range from asinine to half-baked to full-fledged, so interpret them as you wish. They aren't intended to disrupt our focus on Learnstream.

The background:

Testing suites are used in software development to ensure that all aspects of a system remain functional throughout development. I.e. a test would be added to ensure a new feature works as intended. After adding the feature, it should pass the test. In addition, when the entire project is built, it is tested with all tests. This can also be used to estimate compatibility of new features by running the test suite with a placeholder for that feature.

User interface (UI) design is an essential part of most software development. It requires users to test the usability, experience, and aesthetics of an interface, so testing is usually not automated but rather incremental. UI testing requires gathering users, training them, recording feedback, etc. 

The idea: 

Developers can write tests for UI features. For example: "the user should be able to log in from the main page within 3 clicks and 10 seconds". The test suite builds up a bunch of features like this. How do you test them though? Easy: mechanical turk! https://www.mturk.com/mturk/welcome It generates a URL and instructions to make testing that feature easily and then assigns one feature at a time for workers on mturk. 
