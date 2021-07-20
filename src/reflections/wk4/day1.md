# Callback Hell

Afternoon Project:https://github.com/VeronicaBlake/triviAPI

https://codeworksacademy.com/fs-student-guide/resources/wk4/01-Callbacks/

<!--Callbacks are "tasks that get dispatched, go off and do something in the background, and then complete successfully or abort due to failure."-->

## What are some of the signs and causes of Callback Hell?

The Pyramid of curly braces at the bottom of a block of code can indicate callback hell. This is because people write the code with the expectation that execution is carried out in the code from top to bottom, which is not the case.

---

## What does the asynchronous mean and how are callbacks involved?

Asynchronous regarding functions means that the function will be executed in the future. Callbacks are just a convention for using functions in javascript. Asynchronism (?) with callbacks is a way to make sure that your code isn't hung up on function and stops loading/functioning as it waits for that callback. The page will load, and then the callback will run the function in it. Usually callbacks are utilized with downloads/reading/talking to databases. Nifty!

---

## Summarize the 3 ways to avoid / fix Callback Hell

Keep your code shallow - Name your functions, move the functions to the top level of the program, trust hoisting to have your back

Modularize - To my understanding, it looks like this is breaking up blocks of functions into files and calling to the files in your main code.

Handle every single error - Make the first argument of your callback handle errors. Code linters can help with this as well.
