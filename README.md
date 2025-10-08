# Java Autoboxing, Serialization, File Handling, and Data Management Examples

## Overview
This repository contains Java programs demonstrating the use of **autoboxing/unboxing**, **serialization/deserialization**, and **file handling**. These examples showcase practical **data processing and management techniques** in Java for cleaner, more readable, and efficient code.

---

## Features

### 1. Sum of Integers Using Autoboxing and Unboxing (`SumOfIntegers.java`)
- Accept multiple integer inputs as strings.
- Convert string inputs to `Integer` objects using `Integer.parseInt()`.
- Demonstrates **autoboxing** (primitive to object) and **unboxing** (object to primitive).
- Calculate and display the total sum using enhanced for-loops.

---

### 2. Serialization and Deserialization of a Student Object (`StudentSerialization.java`)
- Create a `Student` class with fields: `studentID`, `name`, `grade`.
- Implement `Serializable` interface to persist objects.
- Serialize the `Student` object to a file using `ObjectOutputStream`.
- Deserialize it using `ObjectInputStream` and display the student’s data.

---

### 3. Menu-Based Employee Management System Using File Handling (`EmployeeManagement.java`)
- Menu-driven application with options:
  1. **Add an Employee**  
     - Input: name, ID, designation, salary  
     - Save to file in serialized or text format
  2. **Display All Employees**  
     - Read and display employee records from file
  3. **Exit the application**
- Demonstrates **File I/O** using `FileReader`, `FileWriter`, `BufferedReader`, `BufferedWriter`, or object streams.
- Implements repeated menu interaction using loops and `Scanner`.

---

## Project Structure

java-autoboxing-serialization-filehandling

├── SumOfIntegers.java # Autoboxing and unboxing example

├── StudentSerialization.java # Serialization and deserialization of Student object

├── EmployeeManagement.java # Menu-driven employee management using file handling

└── README.md # Project documentation

---

## Key Concepts Covered
- **Autoboxing and Unboxing**: Automatic conversion between primitive types and wrapper classes  
- **String Parsing**: Converting string input to integers using `Integer.parseInt()`  
- **Serialization/Deserialization**: Persisting objects to files and retrieving them  
- **File Handling**: Reading/writing text or serialized data using `FileReader`, `FileWriter`, `BufferedReader`, `BufferedWriter`, and object streams
- **Menu-Driven Applications**: Structuring repeated user interactions using loops and `Scanner`  
- **Efficient Data Management**: Persistent storage and retrieval of data for real-world applications

- **Menu-Driven Applications**: Structuring repeated user interactions using loops and `Scanner`  
- **Efficient Data Management**: Persistent storage and retrieval of data for real-world applications  
