---
tags: 🌱
date: 10--Aug--2022
---

# Object creation

When a new [[Object]] is created, memory is allocated to store the [[Object]]. A pointer is also created which reference to the memory location of the object.

## Steps of creation

1. Declaration of variable to hold the pointer to object
2. Allocate memory for the object to be created with keyword *new*

Without the keyword *new*, there will be no object created.

## Example

```java
className var = new constructorCall();
Rectangle r1 = new Rectangle();
r2=r1;
```

In this case, *r2* and *r1* will point to the same memory location and only 1 rectangle exist in memory. This situation is known as [[Object reference]].

---
Links: [[Constructor method]]