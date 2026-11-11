# Student Course Enrollment Academic Performance
A Python-based student management system built using SQLite and Tkinter/Jupyter widgets. It manages student records, and academic grade through a simple interactive dashboard.The project includes data validation, CRUD operations, relational database management, cascading deletion, and a master transcript view to simplify academic record management.


## 1. Project Overview
The Student Course Enrollment & Academic Performance Dashboard is a Python-based application designed to manage university student records, course enrollments, and academic grades.

It uses an SQLite database to store information and provides an interactive interface for inserting, deleting, viewing, and managing academic records.

## 2. Objectives
- To maintain student information in a structured database.
- To manage student course enrollments.
- To record and monitor assignment scores.
- To display student academic performance.
- To maintain data accuracy using validation and database relationships.

## 3. Technologies Used
- **Python:** Main programming language.
- **SQLite:** Relational database management.
- **Tkinter:** Desktop graphical user interface.
- **Jupyter Notebook:** Interactive notebook implementation.
- **Pandas:** Displaying and managing database records.
- **ipywidgets:** Interactive notebook controls.

## 4. Database Design
The project uses three relational database tables:

**Students Table**
- Student ID
- Student Name
- Major

**Enrollments Table**
- Enrollment ID
- Student ID
- Course Code
- Semester

**Grades Table**
- Grade ID
- Enrollment ID
- Assignment Name
- Score

Primary keys and foreign keys maintain relationships between the tables. Cascading deletion helps maintain database consistency.

## 5. Key Features
- Add new student records.
- Enroll students in courses.
- Enter assignment scores.
- Delete student records.
- Cancel individual course enrollments.
- View a combined student academic transcript.
- View individual database tables.
- Validate required fields and scores between 0 and 100.
- Automatically refresh dashboard information after changes.

## 6. How to Run the Project

### Python Desktop Application
1. Install Python on your computer.
2. Download the `registrar_dashboard.py` file.
3. Open the file using Python IDLE or VS Code.
4. Run the program.

### Jupyter Notebook
1. Install Jupyter Notebook.
2. Open `registrar_dashboard_jupyter.ipynb`.
3. Install the required packages:
   `pandas` and `ipywidgets`.
4. Run all notebook cells in order.

## 7. Expected Outcome
The application provides a simple and organized way to manage student information, course enrollments, and academic grades. It reduces manual record management and makes academic information easier to access.

## 8. Conclusion
This project demonstrates the practical use of Python programming and relational database management. It provides an efficient way to organize university academic records through an interactive dashboard.
