I knew there was something more to this TDD thing, and I now I think I have something with a bit of metaphorical value (or I may be going crazy).

Actually I kind of read something along the same lines (same title too!) here: http://blog.toolshed.com/2008/10/test-driven-lea.html but he doesn't elaborate very much, so it took me a while to get it.

So what we're doing with LSAtomic is test-first learning. We are specifying tests of tiny components of knowledge that we want the students to learn: student.should be_able_to(integrate a_constant). They run those tests by interacting with the software, and then "program" themselves by actually learning the material that is needed. 

When do we run the tests? Unfortunately, a student can't run hundreds of tests in a few seconds. That's where spaced-repetition comes in---making these tests occur at the optimal intervals. 

How do we run the tests? Like in TDD, an appropriate amount of background needs to be established before the test can actually occur. A rule of thumb is that we set up exactly what we need and test only one thing at a time. 

How do we help the students program themselves? We learn best by example. But there are definitely a huge number of design decisions that can go here, so that's part of our challenge.

Extending the analogy further, where does refactoring come in? Refactoring is even more important because, as mentioned, testing is slower, and we don't want to waste students' time. For example, student.should be_able_to(integrate a_polynomial) eliminates the need for our previous test. But, like in TDD, we can't necessarily just start with this test because the student is limited in his/her cognitive abilities to program. 
