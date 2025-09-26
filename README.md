## Student Record Management System (Java)

A console-based Student Record Management System implemented in Java, demonstrating OOP concepts such as inheritance, constructors, methods, collections, and conditional logic.

The system allows users to:

Add student records (Roll No, Name, Course, Marks).

Automatically calculate grades (A, B, C, D) based on marks.

Display all student records.

Exit the application.

## Features

OOP Design:

Person → parent class with name.

Student → child class with rollNo, course, marks, grade.

## Constructors: Default and parameterized.

## Methods:

inputDetails() → takes user input.

displayDetails() → prints student info.

calculateGrade() → assigns grade based on marks.

Menu-driven interface: Add Student, Display All Students, Exit.

## Grade Calculation
Marks	Grade
90 and above	A
75–89	B
50–74	C
Below 50	D
Sample Output
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 1
Enter Roll No: 101
Enter Name: Rahul
Enter Course: B.Tech
Enter Marks: 87.0

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 2

Roll No: 101
Name: Rahul
Course: B.Tech
Marks: 87.0
Grade: B

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 3
Exiting the application. Goodbye!

## How to Run

Save the code as StudentRecordSystem.java.

Open terminal/command prompt and navigate to the file location.

Compile:

javac StudentRecordSystem.java


Run:

java StudentRecordSystem
