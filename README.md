# CodeAlpha_Student_Management_System

#Task

Develop a menu-driven C program to manage student records.

# Requirements

* Create a menu-driven C program.
* Implement the following features:

  * Add Student Record
  * Delete Student Record
  * Update Student Record
  * Search Student Record
  * Display Student Records
* Use **Structures** and **File Handling** to store data permanently.

Description:

This project is a Student Management System developed in C as part of the CodeAlpha C Programming Internship. The application uses structures and file handling to manage student records efficiently and store data permanently in a binary file.

The system allows users to add, display, search, update, and delete student records through a user-friendly menu-driven interface.

Features:

* Add Student Records
* Display All Student Records
* Search Student by Roll Number
* Update Student Information
* Delete Student Records
* Permanent Data Storage using File Handling
* Menu-Driven Interface

Technologies Used:

* C Programming Language
* GCC Compiler
* Visual Studio Code
* File Handling
* Structures

Program Workflow:

1. Display the main menu.
2. Select an operation:

   * Add Student
   * Display Students
   * Search Student
   * Update Student
   * Delete Student
   * Exit
3. Perform the selected operation.
4. Student records are stored permanently in `student.dat`.

Structure Used:

struct Student
{
    int rollNo;
    char name[50];
    float marks;
};

Functions Used:

1. addStudent():

Adds a new student record to the file.

2. displayStudents():

Displays all stored student records.

3. searchStudent()

Searches for a student using the roll number.

4. updateStudent()

Updates an existing student's information.

5. deleteStudent()

Deletes a student record from the file.

File Handling:

The project uses binary file handling:

* `student.dat` – Stores student records permanently.
* `temp.dat` – Temporary file used during record deletion.

Sample Menu:

===== STUDENT MANAGEMENT SYSTEM =====
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit

How to Compile and Run:

Compile:

gcc -o studentManagement.exe studentManagement.c

Run:

.\studentManagement.exe


Learning Outcomes:

* Understanding Structures in C
* Working with File Handling
* Binary File Operations
* Data Storage and Retrieval
* Record Management Systems
* Modular Programming using Functions

Author

Shreya Mangalaram

CodeAlpha Internship – C Programming
