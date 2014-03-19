---
layout: post
title: Support That Doesn't Scale
category: posts
---

Oren Eini maintains a [fantastic blog](http://ayende.com/blog/) on the development of RavenDB - I love seeing someone so committed to transparently recording the ins and outs of building and selling software.  And when that software is a non-relational database?  Well that just sets my heart aflutter.

Recently he blogged about their [support triage process](http://ayende.com/blog/165761/support-triage) and it got me thinking about MongoDB's approach to the same.  You should read his post yourself (its less than 150 words), but I interpret it as this: a help ticket came in and the support team's first request was for the account ID.  They held off on the support process pending that information and the customer's account ID never came in, so the ticket was closed as "Gone Away".

Although I haven't sat in with the (stellar) MongoDB support team in a few months, my experience was that we handle things differently in one key way: the first request to come from a support engineer isn't "What is your order id?"  The first request is always "Tell me about the problem you're experiencing."

You can't find your subscription ID?  No worries, let's get you back on your feet and fill in the metadata afterwards.  You work on a project outside your company's subscription?  That's OK, we can talk about rolling you in after we fix the problem.  Your subscription expired 48 hours ago?  Not a problem...well you get the idea.

"That doesn't scale though!", right?  Of course it doesn't, but that doesn't matter, because you should [do things that don't scale](http://paulgraham.com/ds.html)!
