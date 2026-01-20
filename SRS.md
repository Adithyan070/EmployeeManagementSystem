# Software Requirements Specification (SRS)
## Employee Management System

## 1. Introduction

### 1.1 Purpose
The purpose of this document is to describe the requirements of the Employee Management System.  
This system helps manage employee records efficiently using a web-based application.

### 1.2 Scope
The Employee Management System provides functionalities to add, update, delete, and view employee details.  
It is designed for small to medium organizations.

### 1.3 Definitions
- **Admin**: User who manages employee data
- **CRUD**: Create, Read, Update, Delete
- **EMS**: Employee Management System

## 2. Overall Description

### 2.1 Product Perspective
The system is a standalone Spring Boot application using REST APIs and a relational database.


### 2.2 User Classes and Characteristics
- Admin/User: Can manage employee records

### 2.3 Operating Environment
- Operating System: Windows / Linux
- Backend: Java, Spring Boot
- Database: MySQL
- IDE: Eclipse

## 3. Functional Requirements

### 3.1 Add Employee
- The system shall allow the user to add a new employee.
- Employee details include ID, Name, Email, Role, and Salary.

### 3.2 View Employee
- The system shall display a list of all employees.

### 3.3 Update Employee
- The system shall allow updating existing employee details.

### 3.4 Delete Employee
- The system shall allow deleting employee records.

## 4. Non-Functional Requirements

### 4.1 Performance
- The system should respond within 2 seconds.

### 4.2 Security
- Data should be stored securely in the database.

### 4.3 Reliability
- The system should be available during working hours.

## 5. Constraints
- Requires Java 17+
- Requires MySQL database
- Requires Maven

## 6. Future Enhancements
- User authentication and authorization
- Frontend UI using React or Angular
- Role-based access control

## 7. Conclusion
The Employee Management System simplifies employee data management and improves efficiency.
