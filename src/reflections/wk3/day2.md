# Encapsulation in JavaScript

Afternoon Project: https://github.com/VeronicaBlake/vendingMachine

## What is the purpose of Encapsulation?

The purpose of encapsulation is so that an object stores its state privately, and only the object's methods have access to change it. It's self containment and organization.

---

## What were some of the problems with closures and the underscore prefix?

Breaking changes: People ignore the convention of the underscore, and wind up breaking the code.

Leaked implementation details: direct access to the underlying implementation details also allow code to break when used differently than intended.

Expanded Attack Surface for Hackers: If the intent is for internal use, it shouldn't be exposed externally as that allows more surface area for hackers to attack.

Self Documenting Code: Users can't know that this function isn't supposed to be used by them unless they already know about the underscore convention, so it's useless without additional documentation. And if that's the case, why not just write the function normally and put some documentation on it?

---

## How do we create private variables in a ES6 Class? Why would you do this?

You create an actual private variable in ES6 Classes by using a privileged method, written like:

const privilegedMethod = () => { function here }

this has access to the private data, and is encapsulated (?) so that things can't go messing it willy-nilly.
