# How to use Props in Vue

Project: https://github.com/VeronicaBlake/vue-pokemon

## What are props?

Props are like arguments in functions. They allow us to pass variables/other information around between different components.

Props are only passed from parents to children, not vice versa
Props are read-only and cannot be modified

---

## What are props used for?

Props are used to pass variables and other information between components. 
They are especially handy if you want to bind javascript snippets to something, or call a javascript snippet from another area of your code.


---

## Where can props be used or accessed?
Props are used or accessed in our component definition. This is a good place to specify the data type that the specific prop is too. This is also where we specify if a prop is required or not.

They can be used in templates, but also methods, pretty much anywhere else in the component definition. 