# Day 22 - Week 6
## Intro to Vue.js
Today we started off with a Morning Challenge regarding repeatable data. We then began how to learn how to register and use API's with Vue.js. During the afternoon we were tasked with using a NASA API with Vue.js, where we could choose any of the API's we wanted and pass the information to the existing webpage.
## What are props?
In Vue, props (or properties), are the way that we pass data from a parent component down to it's child components. When we build our applications out of components, we end up building a data structure called a tree.
## What are props used for?
Props can be used in a number of ways within a type of specific value desired - 
  title: String, 
  likes: Number, 
  isPublished: Boolean,
  commentIds: Array,
  author: Object,
  callback: Function,
  contactsPromise: Promise // or any other constructor
## Where can props be used or accessed?
Props are used within Vue's one-way data flow, meaning that data can only flow from the parent to the child and not the other way around. The parent "owns" the value it passes down, which means the child cannot modify this value. The way we access a prop is by creating <template></template> element to hold and utilize the data values. JavaScript expressions are how we jell Vue to bind this data and output or intended result for reusability.
## Afternoon Project
- [My Github](https://github.com/JonesyJava/vue-nasa.git)