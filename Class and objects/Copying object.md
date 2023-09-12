---
tags: 🌱
date: 12--Aug--2022
---

# Copying object

Types of copying
1. Copying [[Object reference]]
2. Copying entire object

## Copying object reference

```java
Person p1 = new Person();
Person p2 = p1;
```

In this case, both *p1* and *p2* will point to the same object in memory. Modification of data using variable *p1* will affect *p2*.

## Copying object

```java
public class Person {
    // variables and other methods here
    public Person copyObject(){
    // Note the return type is the class of the current object
    Person p = new Person(argList);
    return p;
    }
}

Person p1 = new Person();
Person p2 = p1.copyObject();
```

Now there are 2 objects in memory, and *p1* and *p2* will reference to different objects.

---
Links: [[Object]]