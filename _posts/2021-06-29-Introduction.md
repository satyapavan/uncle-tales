---
layout: post
title: Introduction | పరిచయం 
author: SP
image: assets/images/0000.jpg
categories: []
tags: [intro]
featured: true
toc: true
hidden: true
---

#### TL;DR version
A tribute `by the` annoyed `to the` excited.

#### Objective
Are you one of those folks who skips reading the super long messages on messaging platforms?
Then this is a chance for you to redeem yourself by reading through these **super long WhatsApp forwards** 

#### Overview
To be on same page, i did not copy/paste these messages into this blog. **I automated it.**

When ever you send a super cute message in a group, in statistics terms, 50% of the audience are swelled and 
remaining 50% are annoyed. 

This blog is a tribute `by the` annoyed `to the` excited audience.

This blog is the quintessential WhatsApp Uncle coming into existence

#### Implementation
At a high level, this is how this site came into existence.

1. Export the WhatsApp chat by excluding the media
1. Load that data into a python program
1. Split the raw file into individual messages (some messages spawn into multiple lines, hence they need to be accounted for in the logic)
1. strip any confidential information out of these messages (you don't want to post the raging rant of a furious uncle into the internet)
1. start swimming through the sea of messages by ignoring the `Hi` `Hello` messages and pick the long forwards
1. identify the language - the biggest problem so far as we also make use of `Tenglish` and `Hinglish`
1. filter duplicate messages
1. post them into the blog

For an elaborate implementation please head over the github implementation.

#### Next steps
Sounds good, so what's next?

There are quite a few expansion plans,
1. Implement sentimental analysis over these posts to identify the jokes vs. serious posts vs. stories
2. Add auto voice over this text and push them as podcasts
3. Add a `Surprise Me` page that returns a new post with each visit.


#### Disclamer
Though I have taken the most gruelling step of scrutinizing through each post to avoid any controversial 
posts, there could be an odd post that might have slipped between my fingers.

So, if you see any such post, **please feel free to bring it up to my notice for take down**.

#### Jar of dirt

Do you have any **Copyright issues** or **general questions** or anything off your chest? 

Head over to [Github repository](https://github.com/satyapavan/unread-gems) and raise a bug report
