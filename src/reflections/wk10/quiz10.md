# C# Fundamentals


**1.** What is the purpose of a `namespace`?

```
A namespace keeps one set of names separate from another namespace. 


```
**2.** What is the difference between a `class` and a `struct`?

```

Structs are value type, classes are reference type

```
**3.** What is the method that returns an instance of a class, yet it has no return type?

```

The Method Declaration

```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?

```
'public; on line 30

```
**6.** In the example what is `string` an indication of?

```

the return type of Start()

```
**7.** In the example what is `abstract` preventing?

```

it prevents the string returned by Start() from inheriting the attributes of the class Car.

```
**8.** In the example what is the purpose of `virtual`?

```
virtual allows 'abstract' to be applied to the string returned by Start().

```
**9.** Name four access modifiers:

```
private, public, protected, internal

```
**10.** If you set a class or method to private, what can access it?

```
Only the functions inside the class/method can access what's inside a private class/method/

```