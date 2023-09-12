---
tags: 🌱
alias: Class method
date: 19--Aug--2022
---

# Static method

It is a **class method** that is **common** across the objects of the class. They are stored in the [[Permanent Generation space]] of the heap as they are associated to the [[Class]] and not the [[Object]].

## Uses
- Code sharing across objects --> Reduce memory usage
- Allows calling of static variables via the class name without creating object.

## Access
- Static methods can only access [[Static variable]] and not any [[Dynamic variable]] nor [[Instance method]]
- Cannot use "this" keyword as there is no instance to refer to

---
Links: [[Static keyword]]