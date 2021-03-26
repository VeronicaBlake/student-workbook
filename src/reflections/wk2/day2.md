# Javascript Functions

https://github.com/VeronicaBlake/js-tests-loops-and-arrays

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
Function Deceleration - 
    function name(parameter){
        The function definition is hoisted, allowing the function to be used before it is defined. This would be a good way to write a function if you're writing a framework for something that requires multiple functions to run at the same time or on each other's heels. 
    }

Function Expressions - 
    let name = function(parameter){
        These functions are not hoisted, so they cannot be used until they are defined. They also don't need to be named, so they can be used when you're not feeling like naming a function? I'm not sure when you would really use these to be honest. I've never seen one written like this.
    }

Arrow Function Expression -
    let name (parameters) => {
        These functions are useful due to their shorter syntax. 
    }

---

## What is the difference between Parameters and Arguments?
Parameters are the names that are used when creating the function definition, so they're a placeholder. They hold the place for arguments, which are the specific values that are placed in the function when the function is invoked.

So if we have this function: 

function evenOrOdd(num){
    if (num % 2 == 0)
    console.log ('even')
    else console.log ('odd')
}
function evenOrOdd(7)

num on line 14 is the parameter. 7 on line 19 is the argument.
---

## What are higher order functions? Can you provide an example?
There are many high order functions, such as:
-.map,
-.filter, 
-.push. 
There are a lot but those were the ones I could think of off the top of my head. Wen a function accepts another function as a parameter or returns a function, it is a higher order function. They're kind of like they're functions that pull double duty.
