---
layout: post
title:  "Wait, we didn't have to implement the API?"
--- 

This week in software engineering my project team is working on adding in a database to our project. We are using PostgreSQL with the help of the psycopg2 package to query our database of food, ingredients, and cuisines within the API calls. Since I am working on the API, I will take advantage of things like psycopg2.extras which will help return records using an interface similar to the Python dictionaries instead of harder to work with tuples. It will make the conversion over to using a database along with the API much easier. I think I am also going to work on achieving better and easier to understand JSON format with the API POST calls. I recently found [http://jsonapi.org/](http://jsonapi.org/) which claims to the "standard for building APIs in JSON." We followed a similar standard the first try, but I like this one more. 

We realized once looking at the second stage of the project's specs that we really didn't have to actually write the API routes and functions for the first stage of the project. I guess we thought "create a RESTful API using Apiary" meant to actually implement it in the Python code too. At least we won't have to do as much work this week! We also weren't in a rush to turn it in for the first deadline so it turned out fine; even though, we did more work than we had to.

On a side note, I really enjoyed this quote from Conrad Stoll's guest lecture related to open source: "Shared Problems Deserve Shared Solutions." This goes beyond just being an active participant in open source activities. I feel it says a lot about how as a community we can collaborate more on practically everything because there are a TON of the problems. 

> Tip of the Week: 
> If you don't want to do more work than you have to, you should ask more questions about the project secs. 