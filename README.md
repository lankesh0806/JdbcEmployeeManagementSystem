# JdbcEmployeeManagementSystem

## Description
A **console-based Employee Management System** developed using **Java and JDBC**, connected to a **PostgreSQL database**.  
This project demonstrates database connectivity, CRUD operations, search functionality, and bulk updates using JDBC.

## Database Details
- **Database Name:** company
- **Table Name:** employees
- **Columns:**
  - empid (Primary Key)
  - name
  - department
  - salary

## Features
- Add a new employee
- View all employees
- Display total employee count
- Search employee by ID
- Update employee details (name, department, salary)
- Delete employee with confirmation
- Search employees by department
- Display count of employees per department
- Bulk salary increment by department

## Operations Supported

### 1. Add New Employee
- Inputs: Employee ID, Name, Department, Salary
- Stores employee details in the database

### 2. View All Employees
- Displays all employee records
- Shows total number of employees

### 3. Search Employee by ID
- Displays employee details if found
- Shows “Employee Not Found” if not available

### 4. Update Employee Details
- Update name, department, and salary
- Based on employee name

### 5. Delete Employee
- Delete employee using Employee ID
- Confirmation prompt before deletion
- Displays success message after deletion

### 6. Search Employees by Department
- Displays all employees from a given department
- Shows total count of employees in that department

### 7. Bulk Salary Update (Bonus)
- Increase salary by bonus amount for a department
- Displays number of records updated

## Technologies Used
- Java (Core Java)
- JDBC
- PostgreSQL
- Maven
- pgAdmin 4 (Database Management)
- Eclipse / IntelliJ IDEA

## Project Structure
JdbcEmployeeManagementSystem/
├─ src/
│ └─ main/
│ └─ java/
│ └─ com/example/jdbc/
│ ├─ Employee.java
│ ├─ EmployeeDAO.java
│ ├─ DBConnection.java
│ └─ EmployeeApp.java
├─ pom.xml
├─ README.md
└─ .gitignore
