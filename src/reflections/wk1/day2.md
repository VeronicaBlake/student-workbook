# Day 2 - Review of HTML/CSS
Daily Challenge: https://github.com/VeronicaBlake/Coolsite

## What is a Pseudo-Class, and what are some of the most common ones you think you will use?
a pseudo-class is a style element that applies to an element when the element is in a particular state. Things like hovering, visited and unvisited links, and text boxes changing color when they're clicked. Coincidentally, I think those will be common ones that I will use a lot. 
---

## What is Specificity, and how might you use it to your benefit?
Specificity is the determining factor in code when multiple rules are targeting the same element, but assigning different vales to that element. (Essentially it's like the hierarchy of rules.)

Specificity can allow for some flexibility in code if you need one instance of an element to run differently than all other times the element is run, or if you'd like to apply another, previously written rule to the element. It can also be useful for knowing when something will deploy, or to know what will happen to a certain element when it's run.
---

## What problems do you think you could run into if you over-utilized the !important feature?

To paraphrase Syndrome from The Incredibles, "When everything is important, nothing will be." Specificity won't matter, code won't run the way you think it should (if someone misses the !important then some outcomes will make no sense), and it will change the outcome. I'm sure it has a time and a place to be used, but for the most part it seems like it would just complicate things and make code difficult to follow.