# Discussion Forum Built Using React.js

### Purpose
Build a discussion forum based on using a pre-existing well-documented open source library, and/or a “Node + Angular” stack that uses a MySQL database to store and retrieve information.

### Summary - TL;DR
Building from scratch using React.js triumphs existing discussion forums that have little flexibility using SQL DB configuration. This is my attempt to study the effectiveness of React.js. 

### Before React.js

##### Research Findings from April 2015
I started by researching the open source libraries. I found three most viable options:

Solutions
	| Features
	| Pros
	| Cons
--- | --- | ---
[NodeBB](https://github.com/NodeBB/NodeBB)
	| Popular and highly recommended Node.js discussion forum 
	| + Open source
	  + Uses Node.js
	  + Due to popularity, continous updates and plug-ins are built
	| + Default DB configuration is NoSQL (Redis, Mongo)
	  ..+ Running a secondary DB is said to be possible but experimental 
	  ..+ Possible solution: MySQL NoSQL connector
[Discourse](https://github.com/discourse/discourse)
	| Platform for community discussion that features mailing list, discussion forum, and chatrooms
	| + Free and open source
	  + Front-end built with [Ember.js](http://emberjs.com/)
	| + Back-end built with Ruby on Rails, not JS
	  + Uses NoSQL (PostgreSQL, Redis)
[Ghost](https://github.com/TryGhost/Ghost/tree/master)
	| Multi-author blogging platform with quick and easy archive indexing
	| + Free and open source
	  + Compatible with Node.js
	  + Supports MySQL DB by changing configuration
	| + Default configuration is SQLite
	  + Blogging platform, not a discussion forum	

##### Action Taken
NodeBB was the most recommended option due to its continuous updates and plug-ins provided by the wide user base; however, I encountered a problem installing MySQL as a secondary DB. I should've listened to NodeBB's warning:
> This option is experimental and should not be used on a production environment.

Node.js + SQL = rare combination in the booming world of MEAN stack.

### After React.js

##### After attending the React.js talk by UW Hacker's very own [Grant Timmerman](http://grant.cm/), I concluded that [React.js](https://facebook.github.io/react/) is the most progressive answer.

Although I would not be using a pre-existing open source library (thus, more time-consuming to build), **React.js was a JavaScript UI library that is compatible with Node.js _and_ SQL DB.** Score!

This is my first project using React.js (The project may contain excessive commenting).
