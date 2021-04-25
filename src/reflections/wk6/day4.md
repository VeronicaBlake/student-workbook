# Using Nested Routes in Vue.js

Reading: https://codeworksacademy.com/fs-student-guide/resources/wk6/04-ChildRoutes/


Project: 

## What is a nested route?

A nested route is a series of components nested inside of each other. It allows for more complex SPAs by giving certain routes children that can be accessed off of a child of the homepage. 

---

## When might you use a nested route? (other than the provided example)

You can use nested routes for so many things. Want to view a specific post on a specific profile? Nested route. Want to go down a wikipedia rabbit hole? Nested route (maybe, I'm not sure how wikipedia does their stuff. But it could work in theory.) Want to view a song in an album from an artist's homepage? BOOM. Nested route. The possibilities are endless. 

---

## Can you pass parameters through nested routes? When might you use them?

Yes, you most definitely can pass parameters through routes. This is useful when you'd like to view one instance of a specific type of data, like a picture or a post. You can set the path to be "path: location/id" to get a specific child element.