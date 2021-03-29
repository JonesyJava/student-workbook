# Day 27 - Week 8
## Capstone Projects
## What are the three main types of testing we can accomplish in Vue? What does each method provide?
### Unit Testing -
Since unit testing advice is often framework-agnostic, here are some basic guidelines to keep in mind when evaluating which unit testing tool is best for your application.

First-class error reporting
When tests fail, it is critical that your unit testing framework provides useful errors. This is the job of the assertion library. An assertion with high-quality error messages helps minimize the amount of time it takes to debug the problem. In addition to simply telling you what test is failing, assertion libraries provide context for why a test fails, e.g., what is expected vs what was received.

Some unit testing frameworks, like Jest, include assertion libraries. Others, like Mocha, require you to install assertion libraries separately (usually Chai).

Active community and team
Since the majority of unit testing frameworks are open-source, having a community that is active can be critical to some teams that will be maintaining their tests for a long period of time and needs to ensure that a project will be actively maintained. In addition, having an active community has the benefit of providing more support whenever you run into issues.

### Component Testing -
The following section provides guidelines on things to keep in mind when evaluating which component testing framework is best for your application.

Optimal compatibility with the Vue ecosystem
It should be no surprise that one of the first criteria is that a component testing library should have is being as compatible with the Vue ecosystem as possible. While this may seem comprehensive, some key integration areas to keep in mind include single file components (SFCs), Vuex, Vue Router, and any other Vue specific plugins that your application relies on.

First-class error reporting
When tests fail, it is critical that your component testing framework provides useful error logs that help to minimize the amount of time it takes to debug the problem. In addition to simply telling you what test fails, they should also provides context for why a test fails, e.g., what is expected vs what was received.

### End-To-End (E2E) Testing -
While unit tests provide developers with some degree of confidence, unit and component tests are limited in their abilities to provide holistic coverage of an application when deployed to production. As a result, end-to-end (E2E) tests provide coverage on what is arguably the most important aspect of an application: what happens when users actually use your applications.

In other words, E2E tests validate all of the layers in your application. This not only includes your frontend code, but all associated backend services and infrastructure that are more representative of the environment that your users will be in. By testing how user actions impact your application, E2E tests are often the key to higher confidence in whether an application is functioning properly or not.

## What testing method do you think is the most useful? Why?
E2E in my opinion is the most valuable because these tests validate all of the layers in your application and not just one layer. This is also a great way to ensure your application is the best quality available and will not break or cause more severe issues down the road.

## What testing method do you think is the least useful? Why?
The least useful in my opnion is the Unit Testing because as you're coding you should be fixing these error messages as you go. While it is still very useful to Unit Test, it is also valuable to know what it is you are coding and how to use the frameworks you've decided to code within. 