# Student Information Dictionary

## Task 7 — AI & ML Internship - Veda Technology

A simple Python-based student information system that uses dictionaries to store, search, add, and update student records.

## Project Overview

This project demonstrates how Python dictionaries can be used to represent structured student information. Each student is identified using a unique Student ID, which is used to access and manage their details.

The project includes operations for:

* Adding new student records
* Searching for a student using their ID
* Updating existing student information
* Displaying the final student database

## Technologies Used

* Python
* Jupyter Notebook
* Python Dictionaries

## Student Information Stored

Each student record contains:

* Student ID
* Name
* Age
* Major

## Operations Performed

### 1. Add Student

The `add_student()` function adds a new student to the database. It also checks whether the Student ID already exists.

### 2. Search Student

The `search_student()` function searches for a student using their unique Student ID and displays the student's information if found.

### 3. Update Student

The `update_student()` function updates a specific field, such as Age or Major, in an existing student's record.

## Example Records

The project uses manually created student records such as:

* Alice Smith — Data Science
* Bob Jones — Artificial Intelligence

## Example Output

```text
--- Adding Records ---
Success: Student 'Alice Smith' added.
Success: Student 'Bob Jones' added.

--- Searching Records ---
Record Found for 'ID001'
Not Found: No student matches ID 'ID999'.

--- Updating Records ---
Success: Student 'ID001' updated Age to '21'.
Success: Student 'ID002' updated Major to 'Artificial Intelligence'.

--- Final Database State ---
ID001: {'Name': 'Alice Smith', 'Age': 21, 'Major': 'Data Science'}
ID002: {'Name': 'Bob Jones', 'Age': 22, 'Major': 'Artificial Intelligence'}
```

## Learning Outcome

Through this task, I practiced using dictionaries, nested dictionaries, functions, conditional statements, and loops to manage structured student information in Python.
