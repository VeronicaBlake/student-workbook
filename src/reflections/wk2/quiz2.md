# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

```
var, let and const
```

**2.** What is the definition of a function?

```
Reusable, self contained modules of code that accomplish a specific task. They are objects, and always return something.

```

**3.** What are the `SOLID` principles?

```
Single Use - Methods and functions are only responsible for one thing

Open/close principal - “Software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.” - Bertrand Meyer

Liskov Substitution - objects of a superclass can be replaced with objects of its subclasses without breaking the application, so objects of your subclasses have to behave in the same way as the objects of your superclass.

Interface Segregation Principle -“Clients should not be forced to depend upon interfaces that they do not use.” - Robert C. Martin

Dependency Inversion - High-level modules should be easily reusable and unaffected by changes in low-level modules.
```

**4.** Given this array:

```js
let fruit = ["apple", "banana", "pineapple", "orange", "strawberry"];
```

What index is the pineapple's current position? How do you know?

```
Because of zero based indexing, pineapple is at position 2.

```

**5.** With these two objects:

```js
let you = { name: "You", hair: true, friends: [] };
let them = { name: "Them", hair: false, friends: [] };
```

how would you .push the `them` object into the `you` object's array of friends?

```
you.friends.push.(them)

```

**6.** Give an example of a JavaScript `Conditional`:

```
if -  if a condition is truthy, do the thing that 'if' specifies. (ex. if the dress is blue, print 'true')
else - if the if statement is falsey, do this instead. (ex. if the dress is blue, print true. else, print false.)
else if - if all of the other statements that have been specified are falsey, do this.
      (ex. if the dress is blue, print 'true'. else if dress is red, print 'red'.)

```

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "**\_\_**" space? What would you put here to increase `i` by one on every iteration?

```js
for ( let i = 0; i < arr.length; _______ ) {
```

```
This is the increment statement, and it's written as "i++"
```

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

```
Dom stands for Document Object Model. The file first accessed to render the DOM is the HTML file, and then the JavaScript file.

```

**9.** What are the `9` ECMAScript types as defined by MDN?

```
Data Types:
undefined
Boolean
Number
String
BigInt
Symbol

Structural Types:
Object
Function

Structural Root Primitive:
Null
```

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?

```
A parameter is a placeholder for the argument, at least that's how I think of it. The parameter is what will go into the function or method, and the argument is the specific instance of that thing.
```

**11.** What is the difference between a `primitive` value and a `reference` value?

```

Primitive variables store the actual values, where reference values store where to find the objects (addresses) they refer to.

```
