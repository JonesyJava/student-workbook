# Day 16 - Week 4
## Intro to MongoBD and creating Servers
Today we started learning about MongoDB and continued learning how to create Servers. We created out own MongoDB clusters and were challenged with creating a Greg's List API and including this within our vanilla application of Greg's List.
## What are the three types of relationships?
There are three types of relationships; One-to-One, One-to-Many, Many-to-Many.
## What are the benefits of the traditional linking of relationships instead of Embedding
One of the benefits to traditional linking is in the One-to-Many relationship. The advantage is that linking a relationship will make it less likely that an application will run in the maximum document size of its threshhold. It also makes it much easier to to return paginated comments as the application can slice and dice the comments more easily.
## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
In trying to manage many-to-many relationships we need to consider what kind of creation we are attempting to utilize - or what exactly we are required to complete and create, and most importantly, for what purpose. The example in the reading talks about books. We can categorize them based on multitudes of data points - authors, type, title, etc. However, this challenge can direct you in a decision to either make an embedding choice: One-way or Two-way, depending on the data involvement. 
## Afternoon Project
- [My Github]()