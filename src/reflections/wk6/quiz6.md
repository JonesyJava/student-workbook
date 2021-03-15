# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
We start our projects using the following methods within our terminal or CMDLine:
    - vue create (name application)
    - make sure you have Standard Config & Lint on Save active
    - cd into the file created and 'code .' to enter project
    - 'npm i' ... then 'npm run serve' to start server on host
```
**2.** Where can you find the scripts to startup your project on localhost?
<!-- enter you answer in the space below -->
```
package.JSON is where you can find the scripts to startup your project on the localhost.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
Components can be reused over and over throughout your projects. 
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
Template, Script, and Style are the elements that make up a component.
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
'L' in SOLID stands for Liskov Substitution Principle. Defined - Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
Vue-Router is used with a router-link. The router-link injects the component data within a section for you to mount the information without haveing to reload a new page. 
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
State - Data only used within the compenent or temporary data
  Vs
AppState - Data potentially needed/used within the entire application
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services is used for the business logic within any Vue project. 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
App.Vue contains the main or root element of your Vue project. This is the part of Vue that is critical to the overall application. 
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
<style> is used to alter styling within your application. Adding 'scoped' to your style element will aloow you to keep the styling local to your component. 
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
V-For is the method to watching objects in the State and AppState. 
```