# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
vue-bind: or adding a ':' in front of the type of data you want to bind.
vue-model: which listens to any input events or updates on the view.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single 
Page 
Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
SPA allows you to use a single page and inject data into that page when requested. This means the page does not refresh upon request or recieving new information, and will keep the user on a single page.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is a hook that allows for data to be loaded onto the page immediately upon routing to a page. 
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model is used as a two-way data binding method which allows for two sets of data to be joined together. One of the ways you may see a v-model being used is within someones full name. If you have a data set of someones first name and another with their last name, you can data bind these two pieces using a v-model to give/display their full name using a more simplistic code. 
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
v-on can be used for a click action of a button or section of displayed data, or it can be used as a submit function for a form. It is essentially an event handler used to listen to an action and apply that action where requested and intended. 
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
A 'v-if' allows for conditionally rendered data/elements to the page. It works essentially like a traditional 'if' statement in JavaScript. A 'v-for' is also a conditional directive in Vue.js and works essentially like a 'map' function in JavaScript and allows you to rendered to the page iterating over each object in an array, or array of objects.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The purpose for the 'key' attribute within a 'v-for' is a special attribute that allows for children of the same common parent to be identiied and rendered in an orderly way. 'Key' is useful when you want to properly trigger a lifecycle hook of a component or trigger a transition. The following example displays how a 'key' is most often seen inside a 'v-if' 

Example: <li v-for="item in items" :key="item.id">...<li>
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
<slot> is used on content inserted into child components to indicate which named "slot" the content belongs to.

Example:
Vue.component('alert-box', {
  template: `
    <div class="demo-alert-box">
      <strong>Error!</strong>
      <slot></slot>
    </div>
  `
})
```