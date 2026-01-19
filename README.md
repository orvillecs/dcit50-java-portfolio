# DCIT 50 – Java Programming Laboratory Portfolio

This repository contains a compilation of all laboratory activities completed for the subject **DCIT 50**. The activities are designed to demonstrate fundamental Java programming concepts through practical, problem-based applications.

Each laboratory activity is organized in a **separate folder** and focuses on different aspects of Java development, including basic syntax, control structures, arrays, and object-oriented programming principles. The projects emphasize proper program logic, code organization, and user interaction using console-based applications.

This portfolio serves as a consolidated reference of my progress and learning throughout the course, showcasing how theoretical concepts were applied to solve real-world programming problems.

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
