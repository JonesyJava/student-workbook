# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
All npm packages contain a file, usually in the project root, called package. json - this file holds various metadata relevant to the project. This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
You need package.json at the beginning of your project to be able to handle your project's dependencies. Sometimes even your lambda expressions will need to have support from your package.json, as well as if you are coding and include Heroku.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
The command is 'npm i' and 'npm run build'
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.ENV files are used to provide your application with specific data based on it's environment.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view your logs on the web by logging into your Heroku dashboard. Navigate to the app you want to see for example https://dashboard.heroku.com/apps/<app-name> . Once on this page select “more” you should see a drop down menu: In this menu select “View logs”.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
1. Login to Heroku. Before you can login to Heroku, you need to install the heroku-cli interface: Heroku CLI. .
2. Open your project, initiate git repository. Our initial deployment was done using the Github 'Deploy to Heroku' button. ...
3. Add Heroku / Github repository as remote / origin. ...
4. Commit changes and push to Heroku.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is important so that you are not making changes on the master version of the application. This also allows for you to see if you code will merge with the master file without issues.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Sometimes the code review happens before the unit testing but usually only when the code reviewer is really swamped and that's the only time he or she can do it. Our standard is to do the code review before the product goes to QA.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging is the word used to define combining two branches of code. They are typically merged with the master file but need to make sure they are not conflicting with errors of code. 
```
