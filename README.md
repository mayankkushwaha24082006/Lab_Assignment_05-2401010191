# 📘 Student Record Management System (Assignment-5)
A Java console-based application to manage student records using OOP, interfaces, inheritance, custom exceptions, multithreading, file handling, and collections. This project is built according to the requirements provided in the assignment (exception handling, threading, file I/O, sorting, searching, updating, deleting, and load/save operations).

## 🚀 Features
### ✔ Add Student
Collects roll number, name, email, course, and marks, then calculates grade automatically.

### ✔ Search Student
Search by roll number using custom exception StudentNotFoundException.

### ✔ Update Student
Updates full details of a student entry.

### ✔ Delete Student
Deletes a student record by roll number using safe exception handling.

### ✔ View All Students
Displays all records using an Iterator.

### ✔ Sort by Marks
Sorts all students by marks (high → low) using a Comparator.

### ✔ File Handling
➤Loads records from students.txt automatically at startup

➤Saves all records back to the file before exit

➤Uses:

◦BufferedReader
◦BufferedWriter
◦File
◦Proper text-based persistence

### ✔ Multithreading
A loader animation is shown while adding and updating records.

### ✔ Custom Exception
StudentNotFoundException ensures safe error handling during search, delete, and update operations.

## 🧰 Technologies Used
➤Java OOP
➤Abstract class (Person)
➤Inheritance (Student extends Person)
➤Interface (RecordActions)
➤Collections (HashMap, Iterator, List)
➤Custom Exception
➤Multithreading (Thread, Runnable)
➤File Handling (Buffered I/O)
➤Sorting using Comparator
➤Data validation + try/catch

## 📂 Project Structure (Single File)

StudentRecordSystem.java
students.txt  (auto-created)

The single Java file includes:

➤Person (abstract class)
➤Student class
➤Loader thread class
➤StudentNotFoundException (custom exception)
➤RecordActions (interface)
➤StudentManager (complete CRUD + file handling)
➤Main menu driver

## ▶️ How to Run

1.Save the code as:

StudentRecordSystem.java

2.Compile:

javac StudentRecordSystem.java

3.Run:

java StudentRecordSystem

4.The file students.txt will be created automatically to store data.

## 📝 Sample Menu
===== Menu =====
1. Add Student
2. View All
3. Search
4. Delete
5. Update
6. Sort by Marks
7. Save & Exit
Enter choice:

## 🎯 Learning Outcomes
By completing this system, you learn:

➤How to use abstract classes & interfaces
➤Exception handling with custom exceptions
➤File handling in Java (BufferedReader/Writer)
➤Multithreading with Thread and Runnable
➤Using collections (HashMap, ArrayList, Iterator)
➤Designing a menu-driven CRUD system
➤Storing and loading persistent data
➤Sorting using Comparators
➤Clean OOP design and modular programming

