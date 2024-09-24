
# OOPS Practice set 1
### Topic 1
 **Classes and Objects**
1. Define a class `Car` with attributes `brand`, `model`, and `year`. Create multiple instances of the `Car` class and print their details.
2. Write a `get_details()` method in the `Car` class to return a formatted string representing the car's details.
3. Create a class `Book` with attributes `title`, `author`, and `year_published`. Instantiate an object and display the book's information.
4. Why are objects considered the instances of a class? Explain with an example.
5. How is memory allocated for objects? Write a short note on how the class blueprint is used.

### Topic 2
**Encapsulation**
1. Create a class `BankAccount` with private attributes `_account_number`, `_balance`. Provide public methods `deposit()`, `withdraw()`, and `get_balance()` to manipulate the balance.
2. Modify the `BankAccount` class to include data validation when withdrawing money (ensure no overdraft).
3. Why is encapsulation considered important in OOP? Illustrate with a practical example.
4. Write a class `Person` that uses private attributes and provide getters and setters for those attributes.
5. Explain the difference between public, private, and protected access modifiers.

### Topic 3
**Inheritance**
1. Define a base class `Person` with attributes `name` and `age`. Create a derived class `Student` that inherits from `Person` and adds a new attribute `student_id`. Instantiate objects and display their details.
2. How is method overriding implemented in inheritance? Write an example where a child class method overrides a parent class method.
3. Write an example of multiple inheritance where class `Teacher` inherits from `Person` and a new class `Employee`.
4. What is the significance of the `super()` function in inheritance? Demonstrate with code.
5. Explain the difference between single, multiple, and multilevel inheritance with examples.

### Topic 4
**Polymorphism**
1. Create two classes, `Dog` and `Cat`, both having a method `speak()`. Write a function that takes an object and calls the `speak()` method on it, demonstrating polymorphism.
2. How does polymorphism benefit code reusability? Give a practical example of method overriding.
3. Create a base class `Shape` with a method `area()`, and then create two derived classes `Rectangle` and `Circle` that override the `area()` method.
4. Demonstrate operator overloading in Python by implementing a `__add__()` method to add two objects of the `Time` class.
5. What is method overloading? Provide an example in a language that supports it.

### Topic 5
**Abstraction**
1. Create an abstract class `Shape` with an abstract method `area()`. Implement derived classes `Rectangle` and `Circle` that provide concrete implementations of the `area()` method.
2. How does abstraction differ from encapsulation? Explain with examples.
3. Why are abstract methods useful in designing a class hierarchy? Provide an example.
4. Write an abstract class `Vehicle` with abstract methods `start_engine()` and `stop_engine()`. Implement these methods in subclasses `Car` and `Motorcycle`.
5. Can we instantiate an abstract class? Why or why not? Illustrate with code.

### Topic 6
**Interfaces (or Protocols)**
1. Create an interface `PaymentProcessor` with methods `pay()` and `refund()`. Implement this interface in classes `CreditCardPayment` and `PayPalPayment`.
2. How do interfaces help in decoupling code? Explain with a real-world scenario.
3. Write an interface `Notification` with a method `send_notification()`. Implement classes `EmailNotification` and `SMSNotification` that use this interface.
4. Can a class implement multiple interfaces? Write an example to demonstrate this.
5. What is the difference between an abstract class and an interface?

### Topic 7
 **Composition vs. Inheritance**
1. Create two classes, `Engine` and `Car`, where `Car` uses `Engine` via composition. Write methods in both classes that illustrate their relationship.
2. Why would you choose composition over inheritance in OOP design? Provide an example where composition is more appropriate.
3. Implement a class `Company` that uses the `Employee` class by composition.
4. Modify the previous `Person` and `Employee` classes to use composition instead of inheritance.
5. Compare the advantages and disadvantages of composition and inheritance.

### Topic 8
 **Constructors and Destructors**
1. Write a class `Employee` with a constructor that initializes `name`, `age`, and `salary`. Instantiate the object with different sets of data.
2. What is a destructor? Write a code example demonstrating the use of destructors.
3. Can a constructor be overloaded? Write a class `Product` that demonstrates overloaded constructors.
4. Write a class `Transaction` where a destructor is used to print a message when the object is deleted.
5. Explain the concept of constructor chaining with an example.

### Topic 9
 **Static Methods and Class Variables**
1. Write a class `Library` with a class variable `total_books`. Write methods to add books and track the total count of books using this class variable.
2. Define a static method `validate_isbn()` in a class `Book`. Call this static method without creating an instance of the class.
3. What is the difference between a static method and an instance method? Provide examples.
4. Write a program to demonstrate the use of static variables to share data among all instances of a class.
5. How are class variables shared across all instances? Write code to show this behavior.

### Topic 10
**Design Patterns (Optional Advanced Topic)**
1. Write code implementing the Singleton design pattern for a class `DatabaseConnection`.
2. Explain the Factory design pattern with an example of creating objects for different payment methods (`CreditCard`, `PayPal`, etc.).
3. Write code to implement the Observer pattern where multiple classes observe a `Stock` class for price changes.
4. What are the advantages of using the Strategy pattern? Provide an example related to login system authentication methods.
5. How does the Decorator pattern enhance or alter the behavior of objects? Write a code example demonstrating its use.