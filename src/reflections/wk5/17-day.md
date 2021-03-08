# Day 16 - Week 5
## Intro to Async Code and API's
This morning we started learning Node.js. We are diviing into servers a little bit as well and seeing what each aspect might mean when setting up and/or using a server ourselves. This afternoon we created our own API and started attempting to understand what APIs are and how they are created. 
## What is the purpose of a Query String?
A querystring is a set of characters input to a computer or Web browser and sent to a query program to recover specific information from a database .
## What is the format of a query parameter? How does it start? How do you distinguish between one parameter and the next?
the format for a query parameter is Key=Value. The query itself starts with a '?' followed by the query. To differentiate between two queries is to use an '&'. 
## When do you think Query parameters would be helpful when writing your server?
It can help if you want information to be parsed into an object. An example that can explain this is using square[] brackets in your query string. ?horse[color]=black will then be parsed into an object {horse {color: black}} and store within your server so you dont have to create this object later. 
## Afternoon Project
- [My Github](https://github.com/JonesyJava/node-intro.git)