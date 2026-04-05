# Functional Programming (FP) – Summary

Functional Programming (FP) is a programming paradigm that focuses on writing clean, predictable, and reusable code using functions.

## Core Principles of FP

FP is built on 7 key principles:
- **Pure Functions**
- **Determinism**
- **No Side Effects**
- **Immutability**
- **Declarative Style**
- **Composition**
- **Recursion**

## Pure Functions
Pure functions always produce the same output for the same input and do not modify any external state.
- Easy to test
- Predictable behavior
- No hidden changes

## Immutability
Data is never modified after it is created.
- Prevents bugs caused by shared mutable state
- Makes code safer and easier to debug

## Referential Transparency
A function call can be replaced with its result without changing the program behavior.
- Improves readability
- Enables easier reasoning about code

## First-Class & Higher-Order Functions
Functions can be:
- Passed as arguments
- Returned from other functions

This enables powerful operations like:
- `map()`
- `filter()`
- `reduce()`

## Common Functional Methods

- **map()** → transforms each element in a collection  
- **filter()** → selects elements based on a condition  
- **reduce()** → combines elements into a single value  

## Chaining
Functions can be combined in pipelines:
- Improves readability
- Eliminates intermediate variables
- Creates concise and expressive code

## Functional Programming in Languages

Many modern languages support FP concepts:
- **Python**: `map()`, `filter()`, `functools.reduce()`, list comprehensions  
- **Java**: Streams API  
- **Kotlin**: Collections API  
- **JavaScript / Swift**: Array methods  

## FP vs Imperative Style

- **Imperative** → uses loops and step-by-step instructions  
- **Functional** → focuses on *what to do*, not *how to do it*  

FP is preferred because it:
- Produces cleaner and shorter code  
- Improves readability  
- Reduces bugs  

## Conclusion

Functional programming is widely used in modern development, especially in web and mobile applications. By using functional-style methods like `map`, `filter`, and `reduce`, developers can write code that is more concise, maintainable, and elegant.