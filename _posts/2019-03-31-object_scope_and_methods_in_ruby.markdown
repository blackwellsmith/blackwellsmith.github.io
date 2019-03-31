---
layout: post
title:      "Object scope and methods in Ruby"
date:       2019-03-31 08:50:49 -0400
permalink:  object_scope_and_methods_in_ruby
---


Initially the blog was supposed to be about class variables, instance variables and the scope of those objects. My project had a non-DRY moment. I had a class variable @@all being populated in multiple ways. Calling the class method save at the bottom of the code was making it hard to return anything else but that. We changed the the method being called to the all method, declared the class variable outside of any method. That dried up my code and aloud me to put up the febreze! I think the bigger picture here is object orientation, relationships and mapping the sql tables. This has come to the fore front of the ORM models we are reviewing. Object orientation and scope are the cheese in my ORM grilled cheese. SQL is my  bread, the butter and my hot pan are the mapping methods. I keep getting burned! I understand the concepts. I keep getting lost in the syntax and what kind of data I am working with. Is it an array, nested array of strings or hashes, ? or "?".   It may not be completely clear how I write these codes today or maybe ever when things get more complicated. I will know how to approach it. 

