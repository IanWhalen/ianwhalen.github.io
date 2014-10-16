---
layout: post
title: Intern Projects @ MongoDB
category: posts
---

A while back, just as I began writing again, one of my first topics was [MongoDB's internship program](/posts/internships-at-mongodb), and I ended on a promise to follow up with examples of a few interesting projects from Summer 2013.  Then life got in the way.  So here, after a long delay, are four projects (out of ~17) that represent what MongoDB interns worked on in 2013:

## Rust and F# Drivers
In my mind the [Rust driver](https://github.com/mongodbinc-interns/mongo-rust-driver-prototype) and [F# driver](https://github.com/mongodbinc-interns/mongo-fsharp-driver-prototype) were each fantastic project ideas and archetypal of what we aimed for in the past:

* Free and open source software
* Greenfield projects
* In-demand from the community

Rather than digging into a simple web-app, both of these involved learning how to build a real library based on the template of our existing MongoDB drivers.

In both cases the interns were able to start from scratch and, working with MongoDB engineers as well as language experts from both the Rust and F# worlds, to release solid alpha/prototype versions of the software.  Not bad for ~10 weeks of work.

## Web-based Shell Emulator
The shell emulator at http://try.mongodb.org has been around for a little while.  Well, more than just a little while - the first mention of it in the Wayback Machine is from [February of 2010](https://web.archive.org/web/20100227223927/http://try.mongodb.org/).  So an update was overdue, and two students brought it into the modern world with better support for Javascript syntax and more recently introduced MongoDB features.  Also it's much prettier.

-> ![MongoDB web shell emulator](/images/mongodb-web-shell.png =338x262)

More than just a simple pass at code cleanup though, they took the opportunity to write their own Javascript evaluator, [suspend.js](https://github.com/FuegoFro/suspend.js), that allows the shell to run commands in the expected blocking manner without freezing the entire browser until execution has completed.

This shell emulator has now gone beyond its use as a simple tutorial and is the basis for the testing functionality in [MongoDB University](university.mongodb.com).

## Mongoose

Lastly, we had one of our interns in California pick up working on the [Mongoose ODM](http://mongoosejs.com/).  So rather than working on a brand new codebase he jumped straight into an existing open-source project - taking on bug fixes, feature development and community management all while being supervised by the library's original author.

This was a bit different than most of our other projects in Summer 2013, but it went extremely well and led us to make some changes in time for 2014, the nature of which I'll pick up in a final blog post to be published soon...