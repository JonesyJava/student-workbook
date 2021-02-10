# Day 6 - Week 2
## Intro to Javascript - Day 2
Today our class went over for loops, array methods, and functions again. I'm starting to get more comfortable with for loops and arrays. This afternoon we went over more practice situations with array methods, for loops, and functions. 

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
Function Declaration, Function Expression, Generator Function

Function Declaration defines a named function. The function definition is then hoisted, thus allowing the function to be used before it is defined.

Function Expressions defines a name ir anonomous function, which is a function that has no name. Function Expressions are not hoisted and cannot be used before they are defined. 

Generator Functions, also known as Arrow Function Expressions, is a shorter syntax for writing a function expression. They do not crate their own value. 

## What is the difference between Parameters and Arguments?
Parameters are used when defining a function. They are the names created in the function definition. Parameters are separated by commas in the ()

Arguments are the values the function receives from each parameter when the function is executed or invoked.

## What are higher order functions? Can you provide an example?
Higher order functions are functions that operate on other functions. They either take functions as arguments or provide a return on said function.

An example of a higher order function is as follows:

function greaterThan(y) {
  return x => x > y;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true

This function above creates another function within a function. 

## JS Day-2 Challenges
- [My Github](https://github.com/JonesyJava/js-tests-loops-and-arrays)