# Introduction to Programming: Language Types & Memory Management

## **1.Types of Programming Languages**

* **Procedural Languages:**

    * Focus on a series of well-structured steps, commands, and functions.
Code is executed in a specific order to complete a task.

* **Functional Languages:**

    * Built around pure functions; emphasis on avoiding modification of original data.
Features "first-class functions," allowing them to be assigned to variables.

* **Object-Oriented Languages:**

    * Organizes code into objects (combining code and data).
Uses classes as templates to define custom data types.
Improves maintainability, debugging, and code reuse.

## 2.Static vs. Dynamic Typing:

* **Static Typing (e.g., Java, C++):**

    * Type checking occurs at compile-time.
Data types must be declared explicitly before use.
Advantages: Higher control, fewer runtime errors.

* **Dynamic Typing (e.g., Python):**

    * Type checking occurs at runtime.
No need to declare data types beforehand.
Advantages: Faster to write code; however, errors may appear during execution.

## 3.Memory Management:

* Stack Memory: Stores reference variables.

* Heap Memory: Stores the actual objects (data values).

* Key Concepts:
    * A variable acts as a reference pointing to an object's location in the heap.
    * Multiple reference variables can point to the same object.

## 4.Garbage Collection:

* An automatic process that deletes objects from memory when they no longer have any reference variables pointing to them