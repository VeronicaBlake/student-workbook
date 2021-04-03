# The Observer Pattern
https://codeworksacademy.com/fs-student-guide/resources/wk3/04-ObserverPattern/

Project: https://github.com/THUNDER-DANIEL/sportingGoods

## What problems does the Observer Pattern seek to solve?

The observer pattern really takes the single responsibility principle to the max. This way, there is a list of events (all listed in the designated list), that are being observed by a single observer. 

This allows a one way data flow, so there is predictability in what events will be launched when. This also means that code can be built to be as reusable as possible. 

---

## What are the three mechanisms of the observer pattern?

The Three mechanisms of the observer pattern are:

-Subscribe: Adds new events  
-Unsubscribe: Removes events
-Broadcast: Calls all events

---

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The BCW template uses get and set to create a proxy of the Appstate, which is then exported whenever the things in the Appstate are called. This allows us to use everything in the Appstate without changing the hard coded data in there, letting all of the good stuff that comes with MVC pattern and proxy objects. Is that kind of close? That's the closest I can come with my limited understanding. 
