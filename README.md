# Student Management System in Python ( Tkinter Frontend & MySQL Backend )

A desktop-based **Student Management System** built using **Python**, **Tkinter**, and **MySQL**.  
This application provides an easy-to-use GUI for managing student records, marks, and report cards.

## Frontend
Tkinter-based graphical user interface.

## Database
MySQL is used as the backend database to store student details, marks, and user login data.

---

## Features

### Student Management
- Add a Student: Add new student records with personal and academic details.
- Delete a Student: Remove student records using roll number.
- Update Student Data: Modify student information as required.
- View All Students: Display all students stored in the database.
- Search Student: Search students by roll number, name, or course.

### Marks Management
- Enter Marks: Insert subject-wise marks for students.
- Edit Marks: Update previously entered marks.
- Delete Marks: Remove marks entry of a student.
- View Marks: Display marks of all students.
- Automatic Grade Calculation: Grades are generated based on percentage.

### Report Card
- Generate student report cards with:
  - Subject-wise marks
  - Total marks
  - Percentage
  - Grade

### Authentication
- Login system for users
- Change password functionality

---

## Screenshots
Screenshots of the application UI are available in the `screenshots/` folder.

---

## Setup

### 1. Fork this repository
Click the **Fork** button on GitHub.

### 2. Clone the repository
```bash
git clone https://github.com/pranay-surya/Student-Management-System.git
```
## Configure Database
 ```python
DB_HOST = "localhost"
DB_USER = "root"
DB_PASSWORD = "YOUR_DATABASE_PASSWORD"
DB_NAME = "college"
```


### Install requirements
```bash
 pip install -r requirements.txt
```
## Run main.py
```bash
 python main.py
```



