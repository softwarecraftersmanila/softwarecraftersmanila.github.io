---
layout: post
title: October 2019 Meetup
tags: [meetup]
image: '/images/posts/2019-11-05/group.jpg'
---

Software Crafters Manila had our October meetup last October 24th. **PageUp People** hosted at our [office at Emapta](https://emapta.com/) in Ortigas CBD, Pasig.

![Welcome!](/images/posts/2019-11-05/logo.jpg)

We tackled an unusual topic this time: Refactoring Legacy Code. It's what a lot of developers deal with. And even if you've only worked on greenfield projects, it's very likely that you've written code that became hard to maintain legacy code at some point.

In order to explore this, we used the [Gilded Rose Refactoring Kata](http://iamnotmyself.com/2011/02/14/refactor-this-the-gilded-rose-kata/), and used [this version from Emily Bache](https://github.com/emilybache/GildedRose-Refactoring-Kata) as a starting point.

![photo1](/images/posts/2019-11-05/image9.jpg)

![photo1](/images/posts/2019-11-05/image5.jpg)

![photo1](/images/posts/2019-11-05/image7.jpg)

![photo1](/images/posts/2019-11-05/image3.jpg)

![photo1](/images/posts/2019-11-05/image13.jpg)

![photo1](/images/posts/2019-11-05/image4.jpg)

Approaching the problem, we started with the limitations the problem placed on us, like assuming that the customer was already happily using the code in production. If there is a mismatch between the stated requirements and the code, that may be behavior the client wants to keep.

We spent most the evening coming up with a sort of test harness to get us ready for the refactoring. This helped us understand how the code already behaved. Interestingly, the tests we wrote served to reveal some inconsistencies between the stated requirements and what the program actually did. This served as a jump off point to a discussion on the value of each undocumented feature we discovered. We marked these tests as behavior we're unsure of, and if we did have a client, one we needed to discuss the future of. The tests also helped us to understand the system better as a whole.

We would've liked to have finished it, but we didn't have enough time left in the evening to. We, instead, closed with a discussion on the different approaches we could make to the codebase and what would be a responsible approach in a real world project. Do you spend time in a rewrite of the whole code? Do you minimize the risk by attempting to only refactor a small portion that's only relevant to the feature being added? Give the kata a try yourself if you've got the chance and tell us what you think about the approach you took to solving it.

If you're interested in contributing through any means, or you might be interested in hosting, or just have suggestions on our format or topics that interest you, please reach out through our [Facebook Group](https://www.facebook.com/groups/softwarecraftersmanila/). Sign up for the next meetup through our [Meetup page](https://www.meetup.com/Software-Crafters-Manila/). 

See you there!