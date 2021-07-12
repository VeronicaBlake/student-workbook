# Var, let and const

Afternoon Challenge: https://github.com/VeronicaBlake/js-tests-basics

## What is scope?

Scope is where the variable you declare is available for use. If it's globally scoped, or declared outside of a function (with 'var'), the variable is available for use in the whole window. Any variable declared with 'var' inside of a function is function scoped, or available for use in that function.

---

## What is hoisting?

Hoisting is when variables/function declarations are moved to the top of their scope before code execution. You have to be careful with hoisting because it can mess up variables and cause them to be read as undefined.

---

## In what cases might you use let vs const vs var?

Use let when you want to create a mutable variable, use const when you want an unchanging variable, and use var when you feel like indulging in the garbage fire of anarchy that is vanilla javascript.
