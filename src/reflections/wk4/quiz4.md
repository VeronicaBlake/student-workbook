# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?

```
Asynchronous code waits on a promise from another part of the code to fire, synchronous just kind of does its own thing. Async is conditional, synchronous is not.

```

**2.** What is an event listener?

```
An event listener is added to an object to fire when a change is made to that object. It waits and listens for the object to change, and then makes the changes. Like our 'proxystate.on'.

```

**3.** What does the `O` represent in the `SOLID` principles?

```
O: Open-closed principle. Objects should be open for extension, but closed for modification. It's like improv, they can "yes and", not change the entire situation.

```

**4.** What is a callback / higher order function?

```
A callback function is a function that is passed as an argument to another function, and is "called back" when triggered by a listener. A function that accepts other functions as arguments is called a higher-order function. Higher-order functions accept callback functions as arguments.

```

**5.** What is a `promise`? How do you capture an error from a `promise`?

```
A promise is an object that will return something in the future. Errors are caught using the "then" and "catch" pattern.

```

**6.** Name three processes used to make requests over `HTTP`?

```
Get, Post, Put

```

**7.** What does the `API` acronym stand for?

```
Application Programing Interface

```

**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?

```
The Controller makes calls to the APIs

```

**9.** What is the purpose of encapsulation in programming?

```
Encapsulation prevents unauthorized parties from accessing data. That can be as benign as another part of your code you don't want doing the heavy lifting, or a hacker trying to get all your secrets.

```

**10.** What is `HTTP` response code for a successful request?

```
Anything starting with a 2 (200-299)

```

**11.** What is a 500 error?

```
Something has gone wrong on the internal server, but the server can't be more specific about what. In short, It's not *my* problem, it's the server's.

```
