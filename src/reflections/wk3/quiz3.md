# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Ecapsulation, Inheritence, and Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
return staff.property
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the idea of bundling data and methods that work on particular data within one unit. I also hides the internal representation, or state, of an object from outside manipulation. You can control the access to data with Get or Set.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
'S' stands for Single Responsibility
```
**5.** What's the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class and instance of a class have different behaviors. Class variables are shared between a class and all subclasses, however, an instance of a class can only belong to one specific class.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is not accessible to the client and is situated in the State. It limits the manipulation of the object or data. 
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC organizes your programs files and data. 
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
A controller is how the user interacts with the MVC pattern. This is how data is overall commuinicated to the DOM as well.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Service is a layer that communicates and/or intermediates information between the controller and the data repository.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Model is a layer that contains business logic and contains the public data properties. 
```

