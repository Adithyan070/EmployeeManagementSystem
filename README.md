# Employee Management System

The Employee Management System is a Spring Boot–based web application used to manage employee details in an organization.  
It allows users to perform basic CRUD operations (Create, Read, Update, Delete) on employee records.

## Features
- Add new employee details
- View list of employees
- Update employee information
- Delete employee records
- RESTful APIs for employee management

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- Maven
- MySQL
- REST API
- Eclipse IDE

##  Project Structure
employee-management
│── src/main/java
│── src/main/resources
│── src/test/java
│── pom.xml
│── README.md

1.Clone the respository
2. Open the project in **Eclipse**
3. Configure MySQL database in `application.properties`
4. Run the application as **Spring Boot App**
5. Access APIs using Postman or browser

##  API Endpoints (Sample)
- `GET /api/employees`
- `POST /api/employees`
- `PUT /api/employees/{id}`
- `DELETE /api/employees/{id}`
