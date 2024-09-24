# Theory OOPS

### Set 1: **Introduction to OOP Concepts**

1. What are the four pillars of Object-Oriented Programming (OOP)?
2. Explain the difference between a class and an object.
3. What is the significance of encapsulation in OOP?
4. How does abstraction improve code design?
5. Write a simple `User` class with attributes `username` and `password`.

### Set 2: **Inheritance and Constructors**

1. What is inheritance, and why is it important in OOP?
2. Write a class `AdminUser` that inherits from the `User` class. Add an extra attribute `admin_level`.
3. What is a constructor in a class, and how is it defined in Python (or any language of your choice)?
4. Explain the difference between single inheritance and multiple inheritance.
5. Can a constructor be overloaded? Provide an example to explain your answer.

### Set 3: **Encapsulation and Access Modifiers**

1. Explain the concept of encapsulation with an example.
2. How are access modifiers (like private, protected, public) implemented in your preferred programming language?
3. Why should passwords be encapsulated when building a login system?
4. Modify the `User` class to use encapsulation for `password` with getter and setter methods.
5. Write code to prevent unauthorized access to the `password` attribute.

### Set 4: **Polymorphism and Method Overriding**

1. What is polymorphism in OOP, and how is it achieved?
2. What is the difference between method overloading and method overriding?
3. Write a method `login()` in the `User` class and override it in the `AdminUser` class.
4. Can constructors be overridden? Justify your answer with an example.
5. Give an example of polymorphism in the context of a login system.

### Set 5: **Abstraction and Interfaces**

1. What is the difference between abstraction and encapsulation?
2. How do interfaces (or abstract classes) promote abstraction in OOP?
3. Design an interface `LoginInterface` with methods `login()` and `logout()`.
4. Implement this interface in the `User` and `AdminUser` classes.
5. What is the significance of abstract methods when designing a login system?

### Set 6: **Composition vs. Inheritance**

1. What is the difference between composition and inheritance?
2. Give an example where composition might be more appropriate than inheritance.
3. Modify the `User` class to use composition by introducing a `Profile` class.
4. What are the advantages and disadvantages of composition over inheritance?
5. Explain how composition can be used to handle multiple user roles in a login system.

### Set 7: **Exception Handling in OOP**

1. Why is exception handling important in OOP?
2. Write a `login()` method that raises an exception if the username or password is incorrect.
3. How can you handle multiple exceptions in OOP?
4. What is the use of the `finally` block in exception handling?
5. Explain the role of custom exceptions in a login system.

### Set 8:**File Handling and Persistence in Login Systems**

1. How can file handling be used to store user login data?
2. Write a code snippet to save user credentials to a file securely.
3. How can you read login information from a file and verify it?
4. What precautions should be taken when handling sensitive user data in files?
5. Explain how a database could be used instead of file handling for a more scalable solution.

### Set 9: **Static vs. Instance Methods and Variables**

1. What is the difference between a static method and an instance method in OOP?
2. Create a static method `validate_password()` in the `User` class that checks the strength of a password.
3. What is a class variable, and how is it different from an instance variable?
4. Write code to demonstrate the use of class variables in tracking the number of active users in the system.
5. Can static methods be overridden? Explain with an example.

### Set 10: **Design Patterns in OOP (Optional Advanced Topic)**

1. What are design patterns, and why are they important in OOP?
2. Explain the Singleton design pattern and its use case in building a login system.
3. Write code for a Singleton `LoginManager` class.
4. How can the Factory design pattern be applied in a login system for handling different user roles?
5. What are the benefits and drawbacks of using design patterns in OOP?
