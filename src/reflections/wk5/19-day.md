# Day 16 - Week 5
## Intro to MongoDB, API's, and Relationships
Today we started the day with a morning challenge. The morning challenge we were to create a function that determines who will win in a battle for Middle Earth. We were given an array of values for both sides and set to create the solution via JavaScript. During the afternoon we were tasked with creating a Planet DB using MongoDB but had to have an example of One-to-Many & Many-to-Many (link below). 
## In simple terms what is a sub-document?
Sub-Documents are documents that are nested in other documents. You can spot a sub-document when a schema is nested within another schema.
## When might you use a sub-document?
The example given in the course reading uses a video game character and his Move Schema and then attaches a Special Move Schema within the character later on. However, you can also use sub-documents for a multitude of intentions. One example that came to mind, while reading this resource document in our course reading, was using this within a library data or even sports teams data. With every update, you are able to utilize the sub-documentation and input your new information.
## How do you add to a collection of sub-documents? What about editing them?
You can pass the entire object within the constructed data or you can add the data at a later time. The first method is fairly self-explanatory, however, the second method here needs a bit more explanation. Within the second method of adding sub-documents, you have to create a new Class. Then you can edit this class and add the sub-documentation required. When you are satified with the edit, run save. 

Editing sub-documents is a bit more involved still. When editing, you will need to remember to use the findOne() method to find the document. Get the array of your choosing, change the array after locating, and then ultimately save. 

## Afternoon Project
- [My Github](https://github.com/JonesyJava/galaxy-mongodb.git)