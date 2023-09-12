---
tags: 🌱
date: 10--Aug--2022
---

# Composition

Unlike [[Inheritance]] which follows is-a relation. Composition follows **has-a relation**.

## Usage in [[Class]]
Class will contain [[Object reference]] from other classes as its variable -> pointer as variable to memory location of object. 

## Usage in [[Object]]
Include other objects as its data member -> **object composition**

Note that when using composition, no direct access to private data of embedded object is allowed. There must be proper use of the [[Object reference]] to call the [[Instance method]] needed to perform an action.

## Example
A car has an engine, [[Object oriented programming|OOP]] allows us to embed *engine* within *car* class.

---
Links: 