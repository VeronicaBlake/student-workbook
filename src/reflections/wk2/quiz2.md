# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?

```
var, let and const
```

**2.** What is the definition of a function?

```

```

**3.** What are the `SOLID` principles?

```
Single Use - everything has one job, and it does that job.
Open/close principal - open for extension, but closed for modification.
Liskov Substitution - every subclass or derived class should be substitutable for their base or parent class.
Interface Segregation Principle - Clients should be able to work your product with the interface they have
Dependency Inversion - decoupling but more complex.
```

**4.** Given this array:

```js
let fruit = ["apple", "banana", "pineapple", "orange", "strawberry"];
```

What index is the pineapple's current position? How do you know?

```
Pineapple is in position 2. It is this way because of the zero based indexing, which means that the first object in the array is at position 0.

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
if -  is used to specity a block of code to executed, if a condition is 'truthy'
    if the dress is blue, print 'true'.
else - used to specify a block of code to executed, if the same condition of a proceeding if statement is 'falsy'
      if the dress is blue, print true. else, print false.
else if - is used to specify a new condition to test if the first condition is false
      if the dress is blue, print 'true'. else if dress is red, print 'red'.

```

**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "**\_\_**" space? What would you put here to increase `i` by one on every iteration?

```js
for ( let i = 0; i < arr.length; _______ ) {
```

```
To increase the iteration of i every rotation, you would put "i++". The name of this element is the Increment Statement.
```

**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?

```
Dom stands for Document Object Model. The file first accessed to render the DOM is HTML and then JavaScript.

```

**9.** What are the `9` ECMAScript types as defined by MDN?

```
Data Types: that are primitives
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
null
```

**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?

```
A parameter is essentially a placeholder argument. The parameter can show what will be given to the function, but the argument is what is passed in the specific instance.
```

**11.** What is the difference between a `primitive` value and a `reference` value?

```
Values that are primitive store actual values, and reference values store the addresses of the objects they reference.
```
