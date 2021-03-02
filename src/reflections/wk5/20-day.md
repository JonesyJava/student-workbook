# Day 20 - Week 5
## Intro to Node.js

## What is a virtual property?
Virtuals are an additional field given for a model. Their values can be set manually or automatically with defined functionality. A common virtual property is the full name of a person, composed of first and last. Virtual properties do not persist within the database and are only existing logically, not written to the documents collection.
## When might you use a virtual property?
Virtual property allows the Entity Framework to create a proxy around the virtual property so that the property can support lazy loading and more efficient change tracking.
## How do you search by a virtual properties value?
A GET method can be used as a function to return the virtual value. With the GET function you can perform complex processing or just concatenate single document fields. After utilizing a GET function, we can then utilize a SET function, which will be useful in splitting strings or do other operations. 

## Afternoon Project
- [My Github]()