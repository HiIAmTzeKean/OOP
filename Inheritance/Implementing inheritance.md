---
tags: 🌱
date: 28--Aug--2022
---

# Implementing [[Inheritance]]

## Parent class
```java
public SuperClass {
    private int arg1;
    public SuperClass () {
        arg1 =  0;
    }
    public SuperClass (arg1) {
        this.arg1 =  atg1;
    }
}
```

## Child class
```java
public class SubClass extends SuperClass {
    // define additional attributes
    public SubClass () {
        super();
        // other attributes
    }
    public SubClass (arg1) {
        super(arg1);
    }
}
```

>[!important]
>super() keyword must be at the start of the constructor to prevent compile error

We use *super()* in the subclass to initialise the superclass. Concept is similar to [[this keyword]] where we use *this* to refer to the [[Object]], *super()* is to refer to the superclass.

Note that subclass cannot directly modify the variables in superclass, and we must use the superclass methods to modify the **private variables**. The [[Subclass]] can however, call any public methods from the [[Superclass]] that it has inherited.

---
Links: [[Super keyword]]