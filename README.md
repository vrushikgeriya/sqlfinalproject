Student Management System - SQL Project

Overview

This project is a basic Student Management System built using SQL. It manages students, courses, instructors, departments, and enrollments. The project also demonstrates various SQL operations like CRUD, joins, aggregation, subqueries, and window functions.

Database Setup
CREATE DATABASE final_project;
USE final_project;
Tables Created

1. Students

Stores student details.

StudentID (Primary Key)
FirstName
LastName
Email
BirthDate
EnrollmentDate

2. Courses

Stores course details.

CourseID (Primary Key)
CourseName
DepartmentID
Credits

3. Instructors

Stores instructor details.

InstructorID (Primary Key)
FirstName
LastName
Email
DepartmentID

4. Enrollments

Stores student-course relationships.

EnrollmentID (Primary Key)
StudentID
CourseID
EnrollmentDate
5. Departments

Stores department details.

DepartmentID (Primary Key)
DepartmentName
Sample Data

Initial records are inserted into all tables for testing queries.

SQL Operations Performed
1. CRUD Operations
Insert a new student
Read all students
Update student email
Delete a student

2. Filtering

SELECT * FROM Students
WHERE EnrollmentDate > '2022-12-31';

3. Join with Condition

Retrieve courses from Mathematics department.

4. Aggregation with HAVING

Count students in each course and filter results.

5. Students Enrolled in Multiple Courses

Find students enrolled in both SQL and Data Structures.

6. DISTINCT Usage

Retrieve unique students enrolled in selected courses.

7. Aggregate Function

SELECT AVG(Credits) FROM Courses;

9. Department-wise Student Count

Count total students in each department.

10. INNER JOIN

Retrieve students with their enrolled courses.

11. LEFT JOIN

Retrieve all students and their courses (if any).


13. Date Function

Extract year from enrollment date.

14. String Function

Concatenate instructor full name.

15. Window Function

Calculate running total of students per course.

16. CASE Statement

Label students as:

Senior (more than 4 years)
Junior (less than or equal to 4 years)

-> Key Concepts Covered
Database creation
Table relationships
CRUD operations
Joins (INNER, LEFT)
Aggregation (COUNT, AVG)
GROUP BY and HAVING
Subqueries
Window functions
Date functions
Conditional logic (CASE)

Conclusion:-

This project demonstrates core SQL concepts required for managing relational databases and performing data analysis on structured data.
