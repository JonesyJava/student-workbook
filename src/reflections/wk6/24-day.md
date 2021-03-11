# Day 24 - Week 6
## Intro to Vue.js
Today we started our day with WhiteBoard Challenges. Every Thursday we are going to be practicing whiteboard challenges in front of the class to practice for interviews. We then began learning how to utilize Auth0 within our Vue Applications. During this introduction, we created an application similar to Instagram, called "InstaHam". We went over Nested Routers and using these to create posts within a user profile. We also learned how to create a voting method within each post create by other user profiles. During the afternoon, we were challenged to recreate our previous project, "Pokedex", utilizing the new information presenting during lecture.
## What is a nested route?
A nested route is when a route to one page has another route to a page, or multiple pages, within the route itself. Think in terms of a user profile. This user profile may have posts, which in this case, posts will be a potential route nested within the user's profile route.
## When might you use a nested route? (other than the provided example)
A great example to have a nested route would be within an online library. Say we want to look at an author, which has multiple topics or genres in which they compose. We could use the author as a main route, then have genres as the nested route, and continue nested from there if necessary or desired for better categorization. 
## Can you pass parameters through nested routes? When might you use them?
Yes, parameters can absolutely be passed through a route and nested route. For example within a user profile; this user profile may have an ID to present differentiation within data. This ID can then be passed through the route to specify what the route's output should return. Example: User {{ $route.params.id }}
## Afternoon Project
- [My Github]()