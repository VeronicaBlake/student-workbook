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
 -bool -byte -char -decimal -double -enum -float -int -long
-sbyte -short -struct -uint -ulong -ushort

These different from Javascript in a couple of ways, but I can say the one that sticks out to me the most is that there are many more, because a lot of them are sub-types of the JS data types. Like int, float, and decimal would all be under int in javascript. 

--- 

## In your own words how do Reference types get stored in memory? How does this differ from Value types?

Whereas value types create their own spaces to store infomation, reference types store the data in another space, and then create a quick reference to the space where the data is stored. If a value type was a treasure chest, a reference type is instead a treasure map. 