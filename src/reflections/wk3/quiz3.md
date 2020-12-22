# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Encapsulation, Abstraction, Inheritance, and Polymorphism
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
let property = `${this.name}`
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
It's bundling data and methods, which use that data, to prevent outside access or external change of those objects.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility, a class having only one SINGLE responsibility.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A "class" is essentially a blueprint of an object and what it can do. An "instance of a class" will always have the same properties but can hold different values of those properties.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A proxy object is an object that bundles around another object and changes the behaviors of that target object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
It allows for easier maintenance and parallel development of an application due to the way the information is separated.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The Controller's job is to pass information to the correct Model and return the responses back to the View/user.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
There isn't a Service in the MVC Pattern. However, in the MVCS Pattern, the Services job is to handle and manipulate data.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is responsible for managing the data, talking to the database and returning data to the controller.
```

