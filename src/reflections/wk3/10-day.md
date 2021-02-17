# Day 10 - Week 3
## Intro to Javascript and MVC - Day 6
Today we started off with a morning challenge where we wanted to create a function to find the longest word within the sentence "What is the longest word in this sentence?". We used a for loop to find the longest word and also found alternative solutions to this challenge using an array method and a .reduce method. We then went over Encapsulation during lecture. We went over what closures, export/imports, and why it is so much more efficient to utilize encapsulated code. 

## What is the purpose of Encapsulation?
Encapsulation is the idea of bundling data and methods that work on particular data within one unit. I also hides the internal representation, or state, of an object from outside manipulation. You can control the access to data with Get or Set.
## What were some of the problems with closures and the underscore prefix?
One of the problems with underscore prefix is that if you call a draw within a function, and then call draw again, nothing will work. A problem with the closures is breaking changes. Some internal properties and methods tend to change more frequently than public properties and methods, so this becomes an issue if the closures are deleted and are not considered when breaking changes. closures however enforce true encapsulation, while underscore prefixes do not.
## How do we create private variables in a ES6 Class? Why would you do this?
You can create private variables by using closure-based encapsulation over using classes and the new specification field. You would do this to keep your variables private so that an outdside user cannot manipulate the data set.


## JS Day-10 Vending Machine Challenge
- [My Github](https://github.com/JonesyJava/vending-machine.git)