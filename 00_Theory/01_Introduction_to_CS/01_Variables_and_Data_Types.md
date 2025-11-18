# Variables and Data Types

## What Are Variables?

Variables are named storage locations that hold data used by a program.

Think of a variable as a container or label for a value. They allow programs to store, retrieve, and manipulate data dynamically.

### Key Ideas:

- Each variable has a **name** (identifier).
- It stores a **value** (data).
- The data belongs to a **data type** (defines what kind of value it is).
- The value stored in a variable can **change** during program execution.

### 📦 Analogy:

A variable is like a labeled jar. The jar (variable name) can hold different things (data), and you can replace what’s inside at any time.

---

### Why Variables Matter in Computer Science

- They make programs dynamic instead of static.
- Allow memory management and data manipulation.
- Enable abstraction — we can reason about “x” or “count” instead of literal values.

---

## What Are Data Types?

A data type defines the kind of value a variable can hold and what operations can be performed on it.

Every programming language, including Python, defines multiple types to handle different kinds of information.

### Common Categories:

1. **Numeric Types:** Integers, floating-point numbers, complex numbers
2. **Text Types:** Strings (sequence of characters)
3. **Boolean Types:** True or False values
4. **Structured Types:** Arrays, lists, tuples, sets, dictionaries
5. **Abstract Types:** Classes, objects, user-defined data models

---

### Data Representation in Computers

All data in a computer is represented using binary (0s and 1s) and **Data types** define how those bits are interpreted:

> - Integers → binary numbers
> - Text → character encoding (like ASCII or Unicode)
> - Images → pixel color values

**💡 Example:**
The number `65` and the character `'A'` are stored differently, even though both exist as binary data.

---

### Dynamic vs Static Typing

- **Static typing:** The data type of a variable is defined before program execution (e.g., C, Java).
- **Dynamic typing:** The data type is determined at runtime (e.g., Python, JavaScript).

| Typing Type | Example      | Description                            |
| ----------- | ------------ | -------------------------------------- |
| Static      | `int x = 5;` | Type must be declared explicitly       |
| Dynamic     | `x = 5`      | Type inferred automatically at runtime |

---

### Type Conversion and Compatibility

Even without going deep into syntax:

- Computers often convert between types (like integers to floats).
- Implicit conversion (coercion): Done automatically.
- Explicit conversion (casting): Done manually by the programmer.

> _We'll discuss about type conversion later for now just know they exist._

---

## Summary

- Variables store and label data in a program.
- Data types define what kind of data is being stored and what can be done with it.

Understanding both is essential before diving into any programming language. These concepts bridge the gap between abstract logic (CS) and concrete syntax (Python).
