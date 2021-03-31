# Encapsulation in JavaScript
https://codeworksacademy.com/fs-student-guide/resources/wk3/02-Encapsulation/

## What is the purpose of Encapsulation?

The purpose of encapsulation is to bundle data together, and hide it from the outside. The object stores its state privately, and can only be accessed through methods.

This process eliminates an environment where race conditions could form, and while I might not know much, I know that race conditions are probably bad for the loading and processing speed of your site. Also, chaos will ensue without order. This is a truth of nature, and a truth of programming. 

Finally, it allows you to make small changes to one item without having to rewrite your entire code. "A small change in requirements should necessitate a correspondingly small change in the software." --- N. D. Birrell, M. A. Ould,

---

## What were some of the problems with closures and the underscore prefix?

Breaking Changes: Not totally sure on this one, it seems like this is due to underscore naming conventions being something that newbies shouldn't mess with, and they can code breaking changes by messing with underscore prefixes in the names?

Leaked Implementation Details: The documentation does not have the capability to support other data types, and breaks. 

Expanded Attack Surface for Hackers: The API becomes larger than necessary, thus making it more vulnerable to cybersecurity attacks.

Self Documenting Code: This assumes your users know that they're not intended to use the function because of the underscore prefix. Some might know, some might not, and that's what the kids call "an issue". 


---

## How do we create private variables in a ES6 Class? Why would you do this?

This article is referenced in the journal: https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36

We create private variables in an ES6 class by using closures. 
Closures are an enclosed function that references its surrounding state. According to the article, "a closure gives you access to an outer function’s scope from an inner function."

Private variables are created to prevent anyone that shouldn't be messing with them from messing with them. 