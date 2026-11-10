# Student Management System

## Project Overview

The **Student Management System** is a simple, menu-driven Python application developed to manage student records using CSV file handling.

It allows users to add, search, and delete student information. All records are stored in a CSV file, providing permanent data storage.

## Features

- **Add Student:** Enter and store student name, marks, and roll number.
- **Search Student:** Find student records using their roll number.
- **Delete Student:** Remove student records using their roll number.
- **CSV Storage:** Store student information in a structured CSV file.
- **Permanent Storage:** Save changes automatically.
- **Automatic File Creation:** Create the CSV file if it does not already exist.

## Technologies Used

- Python 3
- CSV Module
- File Handling
- VS Code

## Project Structure

```text
Student-Management-System/
│
├── student_management.py
├── students.csv
└── README.md
```

## How to Run

**Step 1:** Clone the repository.

```bash
git clone YOUR_REPOSITORY_URL
```

**Step 2:** Navigate to the project folder.

```bash
cd Student-Management-System
```

**Step 3:** Run the Python program.

```bash
python3 student_management.py
```

**Step 4:** Select an option from the menu to manage student records.

## Sample Output

```text
1. Add Student
2. Search Student
3. Delete Student
4. Exit

Enter choice: 1

Enter name: Arun
Enter marks: 85
Enter roll number: 101

Student added successfully!
```

## CSV Data Format

Student records are stored in `students.csv`.

| Name | Marks | Roll Number |
|---|---|---|
| Arun | 85 | 101 |
| Priya | 90 | 102 |

## Concepts Learned

- Python file handling
- CSV file operations
- Reading and writing data
- Lists and dictionaries
- Conditional statements
- Loops
- CRUD operations
- Permanent data storage

## Learning Outcome

This project helped develop practical knowledge of Python programming, data storage, file input/output operations, and basic CRUD functionality.

It demonstrates how Python can be used to build simple data management applications.

## Future Improvements

- Add an update student feature.
- Display all student records.
- Implement input validation.
- Add a graphical user interface.
- Introduce student login and authentication.

Author: Sharan
