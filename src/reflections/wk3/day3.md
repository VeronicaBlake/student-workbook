# Intro to Javascript Proxy Objects

Afternoon Challenge: https://github.com/VeronicaBlake/gregslist-mvc

## What are the two common operations that we will set in the handler?

Get and Set are the two common operations set in the handler.

---

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

You have to give a Get two parameters, the object itself and the property being accessed in order for it to not return "undefined".

---

## What are some of the benefits of the proxy object that we are using in our structure for applications?

Proxy objects provide an interface to control the behavior of any target object using a handler, which is useful to us moving forward with aync code. It also allows manipulation of data that isn't the hard, 'pure' data, so you don't have to worry about deleting something that might need to be reverted or changed later.
