---
tags: 🌱
date: 30--Sep--2022
---

# OOP design goals

- [[Encapsulation]]
- Loose [[Couple|Coupling]]
    - Interaction via interface promotes loose coupling
- High [[Cohesion]]
    - Class only needs to focus on itself and does not need to manage the operation of other [[Class]]
    - An example can be Customer class not needing to implement validation for Login class

Some examples that contradict OOP goals
- When classes have bi-directional relationship
    - Both classes must know what the other is doing
    - Leads to low cohesion and tight coupling
    - Bad encapsulation as well since more methods must be made public

---
Links: 