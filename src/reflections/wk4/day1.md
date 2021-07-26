# Callback Hell

Afternoon Project:https://github.com/VeronicaBlake/triviAPI

https://codeworksacademy.com/fs-student-guide/resources/wk4/01-Callbacks/

<!--Callbacks are "tasks that get dispatched, go off and do something in the background, and then complete successfully or abort due to failure."-->

## What are some of the signs and causes of Callback Hell?

One of the signs of callback hell is the pyramid of curly braces and commas at the bottom of a block of code, indicating functions nested in functions and so on. One of the causes of this is the expectation that code execution is carried out from top to bottom, which doesn't have to be the case in Javascript if you're writing asynchronous code. 

---

## What does the asynchronous mean and how are callbacks involved?

Asynchronous means to take place in the future. Callbacks are the name of a convention for using a javascript function, and act as a catalyst for 

---

## Summarize the 3 ways to avoid / fix Callback Hell

Keep your code shallow - Name your functions, move the functions to the top level of the program, trust hoisting to have your back

Modularize - To my understanding, it looks like this is breaking up blocks of functions into files and calling to the files in your main code.

Handle every single error - Make the first argument of your callback handle errors. Code linters can help with this as well.
