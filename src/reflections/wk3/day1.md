# ES6 modules

Afternoon Project: https://github.com/VeronicaBlake/zookeeper

## What problem does using exports solve?

Exports expose only those parts of the code that should be accessed by other parts of your code, and make it safer and harder to "hack".

---

## How does export differ from export default?

Export - multiple things can be exported from the file
Imports look like: import {firstThing, secondThing } from “../Services/ThingsService.js”
vs
Export Default - only export you get for the entire file
You can’t import the secondThing from the example above

---

## What is a benefit of using the Module System?

There are a lot of benefits of using the module system, but the one that seems to be touched on a lot in the article and from what I've heard is efficiency and standardization between programmers.
