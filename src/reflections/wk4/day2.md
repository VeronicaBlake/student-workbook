# JavaScript Promises


Project: https://github.com/VeronicaBlake/gregslist-take2

## What are the three states of a Promise?

Pending: Initial State, before the Promise succeeds or fails - promise is waiting for its time to come (data is requested )

Resolved: Completed Promise - information is received from the server, promise completed

Rejected: Failed Promise -  information is not received, error message sent and promise failed 

---

## How do promises seek to resolve the issues of "callback hell"?

Promises can utilize chaining, which allows multiple callbacks to be attached to a single promise. This saves us from callback hell (callbacks on callbacks on callbacks), and makes the code cleaner to read and run. 


---

## What is the difference between .then() and .catch()?

.then() - called after the promise is resolved, and only runs if the promise is resolved.
.catch() - is called after the promise fails, and only runs if the promise fails. It is written after .then().