---
tags:
  - 🌱
  - ComputerScience 
date: 12--Aug--2022
---

# Null Pointer Exception Error

When a variable is created but not yet referenced to a valid object and we try to send a message.

## Example

```java
// Valid code
Person human = new Person();
human.eat();

// Not valid
Person human;
human.eat();
```

The variable in the second case points to a *NULL* location since the *Person* object has yet to be created.

---
Links: 