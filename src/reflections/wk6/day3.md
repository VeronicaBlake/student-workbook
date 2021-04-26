# Understanding VueJs Lifecycle Hooks

Reading: https://codeworksacademy.com/fs-student-guide/resources/wk6/03-VueLifeCycleHooks/

Diagram: https://vuejs.org/v2/guide/instance#Lifecycle-Diagram

Project: Unable to push to github but I have it on local storage 

## What are lifecycle hooks? What are lifecycle hooks used for?

"Lifecycle hooks are a window into how the library you're using works behind-the-scenes." Lifecycle hooks are defined methods that get executed at specific stages in the lifespan of a Vue object. They start from creation and go to destroyed. 

---

## How have you utilized lifecycle hooks in your afternoon projects?

We've been using onMount frequently, and it seems that these lifecycle hooks happen to pretty much any object that is written into vue. I have a bunch of questions: Do they happen every time an object is re-rendered? It appears so. Also, how are they called? Is that just behind the scenes vue magic? That appears to be the case as well. If that is correct, then it would appear that vue hinges on these, so lifecycle hooks are an intrinsic part of vue. 

---

## What are mounting hooks? When might you use them?

Mounting hooks are the hooks that are most commonly used, they allow access to your component immediately before and after the first render. If you need access to the DOM of your component right before or after the initial render, this is a good one to use. 
