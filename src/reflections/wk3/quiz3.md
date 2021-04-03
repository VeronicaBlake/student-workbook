# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- https://info.keylimeinteractive.com/the-four-pillars-of-object-oriented-programming#:~:text=Now%20that%20we%20have%20covered,Abstraction%2C%20Inheritance%2C%20and%20Polymorphism. -->
```

The pillars of OOP are: 

Encapsulation: A semi-permeable membrane situation with an object. Stuff can come out, but can't go in. 

Abstraction: Selecting the specific data you need from a pool of data, and being able to recall that specific data in other instances easily.

Inheritance: The ability of one object to acquire some or all of the properties of another object.

Polymorphism: Using a class in the same way as its parent. 

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

```
let property = staff.name 

```
**3.** What is Encapsulation?

```
Encapsulation is the method of making an object private to other objects. Or some parts of the object private, and selecting what is public. This limits what can mess with the object when. Nifty!

```
**4.** What does the S stand for in the `SOLID` principles?
```
Single Use 

```
**5.** What the difference between a `class` and an instance of a `class`?

```
A class is more of a blueprint, while an instance of class is an actual object. It's the metaphysical idea of a chair vs the chair that you're sitting in right now. 
```
**6.** What is a `Proxy` object?

```
A proxy object is a "copy" of the actual object that can be changed, and acts as a stand in for the hard data.
```

**7.** What is the purpose of the `MVC` pattern?
```
The MVC uses encapsulation to improve security and clarify code between developers.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?

```
The Controller brings and translates information from the View to the Service, much like a waiter takes an order from a customer to the kitchen. 
```

**9.** What is the job of the `Service` in `MVC`?

```
The service is where all the functions are stored and carried out. 

```
**10.** What is the job of the `Model` in `MVC`?

```
The Model houses objects in classes so that all of their information can be exported easily and stored in one place. A template can also be put here as well. 

```

