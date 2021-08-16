# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?

```
v-model: bind variables inside of an HTML attribute

double curly bois: binds a variable from the relative component 

```

**2.** The `SPA` acronym stands for what?

```
Single Page Application

```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?

```
A SPA will load more quickly than a traditional web application, as it only has to keep loading the router link instead of the entire page over and over. It's also got to be easier to write from a code standpoint, as you can make use of the components/pages to reuse structures and code.


```
**4.** What does the `onMounted` method in Vue do?

```
onMounted is a function that runs when a page is first initialized. So anything in it runs when the page is initialized.

```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?

```

The v-model attribute creates two way binding between the user input and the vuejs component. This will automatically pick up changes and store this value in the data properties of the component. This will be commonly used on a form input to record the user input.



```
**6.** The `v:on` (`@`) directive can be used for what?

```
v:on can be used to dynamically bind one or more attributes to an element.

```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?

```

v-if, v-else-if, v-else

```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?

```
The key attribute tells Vue how your data relates to the HTML elements it's rendering to the screen.

```
**9.** What is the `<slot>` element and what is it used for?

```
The <slot> element is used to inject data into another element.

```