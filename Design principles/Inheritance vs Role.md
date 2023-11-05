---
tags:
  - 🌱
  - ComputerScience 
date: 30--Sep--2022
---

# Inheritance vs Role

- [[Inheritance]]
    - Requires some specialisation of the [[Subclass]]
    - Subclass must be distinct from [[Superclass]] by implementing some attribute and methods that differentiate one subclass from another
- Role
    - Application of inheritance on role might seem valid since the 'is-a' relation satisfy but the specialisation of the subclass might not
    - Take the example of father and mother class inheriting from person class, it is a valid 'is-a' relation but there is not specialisation
    - Role can be identified using enum relationship check → if it is possible to enum these classes, then these classes should be roles and not inheritance

---
Links: 