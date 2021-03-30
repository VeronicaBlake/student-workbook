# ES6 modules

https://codeworksacademy.com/fs-student-guide/resources/wk3/01-Modules/#what-exactly-is-a-module

Project: https://veronicablake.github.io/zoo/

## What problem does using exports solve?

Exports allow you to include/reference one JavaScript file in another, as opposed to having to write things out multiple times, or referencing multiple HTML Script files, which effects performance. 

---

## How does export differ from export default?

There can only be a single export default module per instance of class. Default export is the "main" export because it will be the easiest to reference, and to my understanding named (non-default) exports can still be made and referenced in other JS files.

---

## What is a benefit of using the Module System?

There are many benefits to using the module system. The main one seems to be organization. Naming conflicts usually resolve (as multiple functions can be named the same thing in reference to their individual JS files, but still referenced), files can communicate with each other individually and with only the pieces of information they need, and the self-containment makes denugging easier. Yay modules!