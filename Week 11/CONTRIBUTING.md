## OOP Concepts Guide for Contributors

This project follows Object-Oriented Programming (OOP) principles. Contributors are encouraged to understand and apply these concepts while working on the code.


### Encapsulation
Encapsulation restricts direct access to data and allows controlled access through methods.

```java
class BankAccount {
    private double balance;

    public void deposit(double amount) {
        if (amount > 0) {
            balance += amount;
        }
    }

    public double getBalance() {
        return balance;
    }
}
```
### Abstraction

Abstraction hides implementation details and exposes only essential functionality.

```java
abstract class Animal {
    abstract void makeSound();

    void sleep() {
        System.out.println("Sleeping...");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("Woof!");
    }
}
```

### Inheritance

Inheritance allows a class to reuse properties and methods of another class.

```java
class Vehicle {
    void start() {
        System.out.println("Vehicle starting...");
    }
}

class Car extends Vehicle {
    void showCar() {
        System.out.println("This is a car.");
    }
}
```

### Polymorphism

Polymorphism allows the same method to behave differently depending on the object.

```java
class Animal {
    void makeSound() {
        System.out.println("Generic sound");
    }
}

class Dog extends Animal {
    void makeSound() {
        System.out.println("Woof!");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal obj = new Dog();
        obj.makeSound(); // Calls Dog's version
    }
}