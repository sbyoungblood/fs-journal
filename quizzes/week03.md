# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, inheritence, and polymorphism
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
let property = staff.name
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
The grouping of like concerns. I also serves as a way to restrict the direct access to some components of an object, so users cannot access state values for all of the variables of a particular object.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the model for what something will look like, such as an object, when it exists. An instance is when that model is made real, following the guidelines of the original model.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object allows you to create an object that can be used in place of the original object, but which may redefine fundamental Object operations like getting, setting, and defining properties.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The MVC separates the model from the controller, in addition to other separations (service, app state)
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
A controller is in charge of controlling the way a user interacts with an MVC application.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service manipulates data on an object.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The model holds the guidelines for how objects of a certain class will be build when they are instantiated.
```
