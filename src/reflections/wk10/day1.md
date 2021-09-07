# C# Data Types

---

## What are the three categories of data types? How are they different?

The data types in C# differ in how they store value in their memory. 

Value type: holds a data value within its own memory space
    -bool -byte -char -decimal -double -enum -float -int -long
    -sbyte -short -struct -uint -ulong -ushort

Reference type: contains a pointer to another memory location that holds the data
    -String -Arrays -Class -Delegate

Pointer type: a data type that assigns a variable whose value is the direct address of the memory location.

---

## What are the Value-type data types? What differences do you notice from JavaScript?
 
  -bool -byte -char -decimal -double -enum -float -int -sbyte -short -struct -uint -ulong -ushort

These different from Javascript in a couple of ways, but I can say the one that sticks out to me the most is the variety of data types that are classified as Value types. Many of them can be lumped into larger JS data types; int, float, and decimal would all be under int in javascript, as an example. 


--- 

## In your own words how do Reference types get stored in memory? How does this differ from Value types?

Whereas value types create their own spaces to store infomation, reference types store the data in another space, and then create a quick reference to the space where the data is stored. If a value type was a treasure chest, a reference type is a treasure map, but the map makes a route to the treasure? That analogy needs some work. 
