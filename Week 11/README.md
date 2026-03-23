## Summary: Applying Object-Oriented Programming (OOP) in My Assignment

Object-Oriented Programming (OOP) is a programming approach that focuses on organizing code using **objects and classes** instead of just functions and procedures. Compared to procedure-oriented programming, OOP helps in managing complex programs by improving **modularity, reusability, and maintainability**.

### Understanding the Concept

From the lecture, I learned that earlier programming methods like **structured programming** and **procedure-oriented programming** focused on breaking problems into functions. However, as software became more complex, these approaches had limitations, especially in handling large-scale systems. OOP improves this by combining data and functions into a single unit called an **object**.

### How I Will Apply OOP

In my programming assignment, I will use OOP principles to design my application in a more organized and scalable way. Instead of writing everything in one main program with multiple functions, I will create **classes** that represent real-world entities in my project.

For example, if I am building an app (such as my community app or any interactive system), I can create:

- A `User` class to store user information (name, email, preferences)
- A `Content` or `Resource` class to manage different types of data
- A `Quiz` class to handle quiz logic, questions, and scoring

Each class will have:
- **Attributes (data)** → such as user name, score, or content type  
- **Methods (functions)** → such as login, display content, calculate score  

### Benefits in My Assignment

Using OOP will help me in several ways:

- **Code Reusability**: I can reuse classes in different parts of the program  
- **Better Organization**: Code will be divided into logical sections (classes)  
- **Easier Maintenance**: Changes in one class will not affect the whole program  
- **Scalability**: I can easily add new features without rewriting everything  

### Example

Instead of writing separate functions like:

```createUser()
calculateScore()
displayQuiz()

I will structure my code like:

class User {
createUser()
}

class Quiz {
calculateScore()
displayQuiz()
}
```

### Conclusion

Overall, I envision using OOP to make my assignment more structured, efficient, and easier to manage. By using classes and objects, I can model real-world scenarios more effectively and build a program that is both flexible and maintainable.


## Follow-Up Questions and Reflections

### Is My Chosen Programming Language OOP Capable?

Yes, my chosen programming language (JavaScript) is **Object-Oriented Programming (OOP) capable**. It supports OOP concepts such as objects, classes, inheritance, encapsulation, and polymorphism.

### To What Extent Does It Support OOP?

JavaScript supports OOP **partially to fully**, depending on how it is used:

- Modern JavaScript (ES6 and later) provides **full OOP-like features** using:
  - `class` syntax
  - `constructor` methods
  - `extends` for inheritance
- However, JavaScript is fundamentally **prototype-based**, not class-based like Java or C++

This means OOP is supported, but implemented differently compared to traditional OOP languages.

### Example in JavaScript

```javascript
class User {
  constructor(name) {
    this.name = name;
  }

  greet() {
    console.log("Hello " + this.name);
  }
}

const user1 = new User("Jay");
user1.greet();