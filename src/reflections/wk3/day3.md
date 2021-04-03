# Intro to Javascript Proxy Objects
https://codeworksacademy.com/fs-student-guide/resources/wk3/03-Proxies/

## What are the two common operations that we will set in the handler?

Project: https://github.com/VeronicaBlake/spring21-gregslist

The two common operations that we will set in the handler are: 

1. Get - this is a trap for setting a property value 
2. Set - MDN says that set should return a boolean value.


---

## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

To insure that values don't become undefined, they need to be strings. Otherwise the handler gets confused and returns undefined, and that's not good for anyone. 

---

## What are some of the benefits of the proxy object that we are using in our structure for applications?

The proxy object allows us to make 'modifications' to certain objects without changing the source material. It's also useful in asynchronous functions (not sure exactly what that means yet but I have an idea percolating).