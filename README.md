# Discussion Forum Built Using React.js

## Purpose
Build a discussion forum based on using a pre-existing well-documented open source library, and/or a “Node + Angular” stack that uses a MySQL database to store and retrieve information.

## TL;DR
Building from scratch using React.js triumphs existing discussion forums that have little flexibility using SQL DB configuration. This is my attempt to study the effectiveness of React.js. 

---

## Before React.js

#### Research Findings
===
Searching within the existing open source libraries on discussion forums, I found these three most viable options:

[NodeBB](https://github.com/NodeBB/NodeBB) - Popular and highly recommended Node.js discussion forum 
**Pros**
+ Open source
+ Uses Node.js
+ Due to popularity, continous updates and plug-ins are built
**Cons**
+ Default DB configuration is NoSQL (Redis, Mongo)
+ Running a secondary DB is said to be possible but experimental (Suggestion: MySQL NoSQL connector)

[Discourse](https://github.com/discourse/discourse) - Community discussion platform that features mailing list, discussion forum, and chatrooms
**Pros**
+ Free and open source
+ Front-end built with [Ember.js](http://emberjs.com/)
**Cons**
+ Back-end built with Ruby on Rails, not JS
+ Uses NoSQL (PostgreSQL, Redis)

[Ghost](https://github.com/TryGhost/Ghost/tree/master)
Multi-author blogging platform with quick and easy archive indexing
**Pros**
+ Free and open source
+ Compatible with Node.js
+ Supports MySQL DB by changing configuration
**Cons**
+ Default configuration is SQLite
+ Blogging platform, not a discussion forum	

#### Action Taken
===
NodeBB was the most recommended option due to its continuous updates and plug-ins provided by the wide user base; however, I encountered a problem installing MySQL as a secondary DB. I should've listened to NodeBB's warning:
> This option is experimental and should not be used on a production environment.

Node.js + SQL = rare combination in the booming world of MEAN stack.

---

## After React.js

I saw a FB event about React.js: "The Frontend Framework of the Future" but I saw no correlation to this project at first. I attended the talk out of curiosity.

#### After attending the talk by UW Hacker's very own [Grant Timmerman](http://grant.cm/), I realized that [React.js](https://facebook.github.io/react/) might just be able to have the potency that this project needed.

Although I would not be using a pre-existing open source library (thus, requiring more time-consuming to build), React.js is a JavaScript UI library that can combine with Node.js with SQL DB. Score!

This is my first project using React.js (The project may contain excessive commenting).
