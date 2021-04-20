# Component Based Architecture


Project: https://github.com/VeronicaBlake/vue-playground

## What is Component based architecture?

"A method for encapsulating individual pieces of a larger user interface (components) into self-sustaining, independent micro-systems." This means that we take components (ie chat sections, friends lists, navbars, etc.) and write them within their own sections, as opposed to breaking them up into three different sections of controllers, models, and services.

---

## What are some benefits of Component based architecture?

Components make calls from the client side to the server side, and do so independently. This means that single components can refresh on a page without causing the entire page to reload. Components are reusable, so you get more bang for your buck. Also, all things pertaining to that component (html, functions, modules, etc.) are inside of the single component. This eliminates the need to go running around to servers and controllers to see what's doing what when.

---

## What are some drawbacks to Component based architecture?

Possible degraded readibility - views can become busy and cluttered with the amount of things going on in them. This is a potential drawback to vertical architecture, and you might have to dive deep into a view to see what's going on. (I would argue that it's a pain both ways, horizontally and vertically, so good documentation and ease of writing should be taken into consideration when sharing and writing code.)