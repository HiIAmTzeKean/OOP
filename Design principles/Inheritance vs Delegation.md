---
tags: 🌱
date: 30--Sep--2022
---

# Inheritance vs Delegation

- [[Inheritance]] uses 'is-a' relation
    - Subclasses will inherit data from Superclass
        - Reusability
        - Overriding
    - Downside
        - Changes to [[Superclass]] means that [[Subclass]] must be recompiled
        - Changes to methods in Superclass might lead to changes in the methods in subclass
- Delegation uses 'has-a' relation
    - Advantage
        - Changes to object composited does not affect the class using it since it is encapsulated within the [[Class]]
        - No need for recompilation of other class for some change in the class that is composited

---
Links: 