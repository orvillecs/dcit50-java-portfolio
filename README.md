# DCIT 50 – Java Programming Portfolio

This repository contains a compilation of all laboratory activities and the final project completed for the subject **DCIT 50 – Java Programming**. The purpose of this portfolio is to demonstrate mastery of fundamental and advanced Java programming concepts through practical, problem-based applications.

Each laboratory activity is organized in a **separate folder** and showcases different aspects of Java development, including:

- Basic syntax and control structures  
- Object-oriented programming principles (classes, objects, inheritance, polymorphism, abstraction, and encapsulation)  
- Data handling with arrays and collections  
- GUI development using Java Swing  
- Real-world problem-solving and modular program design  

This portfolio serves as a consolidated reference of my learning journey throughout the course, illustrating how theoretical concepts were applied to create functional, well-structured Java programs. It highlights both **console-based applications** and **interactive graphical applications**, showing progression from foundational skills to more complex projects.


## Laboratory Activity 1: Library Book Management System

**Description:**  
This activity involves creating a basic Java console application that simulates a simple library book management system for tracking book borrowing activities.

**Key Features:**  
- Menu-driven system for user interaction  
- Uses arrays to store book titles and availability status  
- Allows adding books with a maximum limit of five  
- Updates book status between *Available* and *Borrowed*  
- Displays all registered books  
- Generates a summary report of total, available, and borrowed books  
- Handles invalid inputs and exits the program gracefully  

**Java Concepts Used:**  
- Arrays  
- Loops (`for`, `do-while`)  
- Conditional statements (`if-else`, `switch-case`)  
- Methods and basic program structure

## Laboratory Activity 2: Working with Java Classes and Objects

**Description:**  
This activity focuses on applying object-oriented programming concepts by creating and using Java classes and objects to represent books and their attributes.

**Key Features:**  
- Defines a `Book` class with properties such as title, author, year published, and current page  
- Uses a constructor to initialize object data  
- Creates multiple `Book` objects in the main program  
- Calls class methods to display details and update object values  
- Modifies object attributes such as current page and author  
- Stores `Book` objects in an array and filters books based on publication year  

**Java Concepts Used:**  
- Classes and objects  
- Encapsulation using private fields  
- Constructors  
- Methods and object manipulation  
- Arrays of objects  
- Loops and conditional statements

## Laboratory Activities 3 & 4: Coffee Shop Rewards System

**Description:**  
These activities involve creating a Java program that simulates a customer rewards system for a coffee shop. Customers earn points for purchases, redeem rewards, and the program keeps track of total registered customers.

**Key Features:**  
- Defines a `Customer` class with instance variables for name and points, and static variables for total customers  
- Implements default and parameterized constructors  
- Uses `this` keyword to access instance variables  
- Adds points for purchases and allows redemption of free drinks based on points  
- Displays customer information and total number of registered customers using static methods  
- Stores multiple `Customer` objects and calculates allowed reward redemptions  

**Java Concepts Used:**  
- Classes and objects  
- Constructors (default and parameterized)  
- Static variables and static methods  
- Instance methods and `this` keyword  
- Arrays of objects  
- Loops and conditional statements

## Laboratory Activity 5: Modeling a School Management System

**Description:**  
This activity involves creating a Java program to model a simple school management system. It uses **inheritance** to represent people in the school and **aggregation** to associate teachers with the courses they handle.

**Key Features:**  
- Defines a `Person` superclass with common attributes for all people  
- Implements `Student` and `Teacher` classes using inheritance  
- Aggregates `Course` objects within the `Teacher` class  
- Displays student information, teacher details, and the courses they teach  
- Demonstrates the use of constructors, the `super` keyword, and arrays of objects  

**Java Concepts Used:**  
- Inheritance (`extends`)  
- Aggregation (Teacher has Courses)  
- Constructors and the `super` keyword  
- Arrays of objects  
- Loops and methods for displaying information

## Laboratory Activity 6: Smart Home Control System

**Description:**  
This activity involves creating a Java program that models a simplified smart home system. Different devices such as air conditioners, lamps, televisions, and microwaves are represented using classes, and their behaviors are controlled through object-oriented programming principles.

**Key Features:**  
- Defines a parent `Device` class with common behaviors (turn on/off, show status)  
- Implements subclasses for `AirConditioner`, `LampShade`, `Television`, and `Microwave`  
- Demonstrates **method overriding** to show different device behaviors  
- Uses **polymorphic references** and arrays of parent type to manage multiple devices  
- Encapsulates device attributes with setters that display updated status  
- Provides static methods to power on/off all devices and count devices currently on  

**Java Concepts Used:**  
- Inheritance and method overriding  
- Polymorphism (parent type → child objects)  
- Encapsulation (private fields with setters)  
- Static methods for device management  
- Arrays of objects and loops  
- Dynamic behavior via runtime polymorphism

## Laboratory Activity 7: Abstraction and Encapsulation in Java

**Description:**  
This activity involves creating a simple Order Management System that emphasizes **abstraction, encapsulation, and safe data handling**. Orders are represented using abstract classes, interfaces, and enums, while collections are managed securely.

**Key Features:**  
- Defines an `Order` abstract class with private fields and an abstract `processOrder()` method  
- Implements `Payable` interface to define payment behavior  
- Uses enums (`OrderStatus`) to represent order states safely  
- Creates `OnlineOrder` class that extends `Order` and implements `Payable`  
- Encapsulates order data with private fields, getters, and validated setters  
- Stores multiple orders in an `ArrayList` and traverses them using an `Iterator`  
- Supports adding, processing, paying, and safely removing orders  

**Java Concepts Used:**  
- Abstraction (abstract classes and interfaces)  
- Encapsulation (private fields, getters/setters, controlled access)  
- Enums for fixed states  
- Collections (`ArrayList`) and iterators  
- Object-oriented design and modular class organization

## Laboratory Final Exam: Java Swing To-Do List Application

**Description:**  
This final project involves creating a Java Swing To-Do List application to help students manage tasks efficiently. The application uses **object-oriented programming principles** to ensure a well-structured and maintainable system.

**Key Features:**  
- Defines an abstract parent class `AbstractTask` with attributes `taskId`, `taskName`, and `taskDescription`  
- Implements subclasses `Task` and `TimedTask` with additional attributes (`status`, `estimatedMinutes`) and proper encapsulation  
- Uses `TaskManager` class to handle creating, updating, removing, and viewing tasks  
- Implements a main application window with a `JTable` to display all tasks  
- Provides a task input form window for adding new tasks, ensuring only one instance of the form can be open at a time  
- Validates all user input before saving tasks  
- Updates the main table automatically after adding tasks  

**Java Concepts Used:**  
- Object-Oriented Programming: inheritance, abstraction, encapsulation  
- Abstract classes and method overriding  
- Swing GUI components (`JTable`, forms, buttons, combo boxes)  
- Controller design pattern (`TaskManager`)  
- Data validation and event-driven programming  
- Dynamic UI updates and single-instance form management

