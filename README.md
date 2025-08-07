# http-LibraryManagementSystem
# Library Management System in Java

## Overview

This is a simple Java console-based Library Management System. It allows a user to perform the following operations:

- View available books
- View all books (including borrowed ones)
- Borrow a book
- Return a book

This project demonstrates basic object-oriented programming in Java, including the use of classes, objects, methods, encapsulation, and array lists.

## Classes

1. Book  
   Represents a book with a title, author, and availability status.

2. User  
   Represents a user with a name.

3. Library  
   Manages a list of books. Provides methods to add, issue, return, and display books.

## How to Run

### Prerequisites

- Java Development Kit (JDK) installed on your system
- Any code editor or IDE (like IntelliJ IDEA, Eclipse, or VS Code)

### Steps

1. Copy the code into a file named `LibraryManagementSystem.java`

2. Open terminal or command prompt in the same directory

3. Compile the code using the following command:

   javac LibraryManagementSystem.java

4. Run the program:

   java LibraryManagementSystem

## Sample Interaction

Enter your name: Ajay

1. Show Available Books  
2. Show All Books  
3. Borrow Book  
4. Return Book  
5. Exit  
Choose an option: 1

Available Books:  
Java Basics by John Doe (Available)  
OOP Concepts by Jane Smith (Available)  
Data Structures by Alan Turing (Available)

Choose an option: 3  
Enter book title to borrow: Java Basics  
Ajay borrowed: Java Basics

Choose an option: 1  
Available Books:  
OOP Concepts by Jane Smith (Available)  
Data Structures by Alan Turing (Available)

Choose an option: 4  
Enter book title to return: Java Basics  
Ajay returned: Java Basics

Choose an option: 5  
Thank you for using the Library System

## Features

- Console-based menu-driven interface
- Tracks book availability
- Allows borrowing and returning of books
- Shows both available and all books

## Future Improvements

- Add user login and registration
- Track which user borrowed which book
- Save book and user data to a file or database
- Add graphical user interface using JavaFX or Swing

## Author

Your Name  
Java Developer or Student  
