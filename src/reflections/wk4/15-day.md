# Day 15 - Week 4
## Intro to Async Code and API's
Today we started with the Morning Challenge, which was based on a fractorialize a number function. We then began to learn how to use multiple API's within the Async MVC Pattern. We created a DnD Spellbook page that would allow us to scroll through Spells (from one API) and Store those spells within another section (a second API which held ID's for each spell). During the afternoon we created a Pokedex with a PokeAPI, which gave us practice connecting API's within our code. 
## What is the purpose of Async/Await?
While Promises were introduced as a solution to Callback Hell, Async/Await were introduced as a solution for the complexity of syntax provided by Promises. 
## What must you do in order to await a promise inside of a function?
When you want to call the function you have to prepend the await, which will call the code and won't stop until the Promise is resolved or rejected. You also have to prepend the async keyword within the function so the function will return a promise.
## What are some of the primary benefits of Async/Await?
Async/Await makes debugging your code a lot easier because the debugger will not step over asynchronous code.
## Afternoon Challenge - Pokedex
- [My Github](https://github.com/JonesyJava/pokedex.git)