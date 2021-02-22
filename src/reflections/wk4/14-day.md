# Day 14 - Week 4
## Intro to Async Code and API's

## What are the three states of a Promise?
Three states of a promise are Pending, Resolve, and Rejected.
## How do promises seek to resolve the issues of "callback hell"?
Promises have three states that are all active in resolving issues of Callback Hell. The pending state allows for a success or fail, resolved completes the promise, and rejected is the failed promise. These three states allow you to create smaller functions, rather than nesting the function again and again. Promises are used by chaining, which attach callbacks rather than passing them, which is one of the benefits to promises in JavaScript.
## What is the difference between .then() and .catch()?
.then() method is called after the Promise is resolved. If the Promise fails then we utilize a .catch() method which during the failed promise, will then jump to the catch and display a different message in the console.
## Afternoon Challenge
- [My Github]()