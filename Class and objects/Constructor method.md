---
tags:
  - 🌱
  - ComputerScience 
date: 10--Aug--2022
---

# Constructor method

Constructors are used to initialise object data. Set of **special method**.

## Default constructor

If no constructors are written, compiler will declare an empty constructor. The default constructor **does nothing**.

```java
class Person {
    public Person() {}
    // Variables
    //methods
}
```

## [[Overloading]] constructors

To create object with different initial values, multiple constructors can be created with different argument list.

## Example

```java
public Person (String name, int age){
    this.name = name;
    this.age = age;
}
```

[[this keyword]] tells the complier the attribute being referred to is the object and not the argument list.

---
Links: 