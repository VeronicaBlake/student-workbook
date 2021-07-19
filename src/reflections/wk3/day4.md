# The Observer Pattern

Afternoon Challenge: https://github.com/VeronicaBlake/fruitStand

## What problems does the Observer Pattern seek to solve?

## The observer pattern seeks to solve "one-to-many, one-way, and event-driven data binding". Or eliminating the push and pull between functions that requires them to update frequently after they've run once already.

## What are the three mechanisms of the observer pattern?

Subject - What is being watched
Observer - What does the watching and updating
Client - Honestly, I'm not totally sure what the client does. Will update with more information.

---

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

The bcw template awaits changes to the proxystate to update data. This way it doesn't have to be constantly refreshing, and can only make changes when the thing that it needs to change is updated. It's not running unless it needs to, which is efficient. And efficiency is time and time is money, baby. Ka-ching.
