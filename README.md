# Employee Management System

A **Spring Boot REST API** project to manage employee data with full CRUD operations.

---

##  Tech Stack

* Java 
* Spring Boot
* Spring Data JPA
* MySQL
* Maven
* Postman (API Testing)

---

##  Features

*  Create Employee
*  Get All Employees
*  Get Employee by ID
*  Update Employee
*  Delete Employee

---

##  Project Structure

com.example.employeemanagement
├── controller
├── service
├── repository
└── entity

---

##  API Endpoints

###  Get All Employees

GET /api/employees

###  Get Employee By ID

GET /api/employees/{id}

###  Create Employee

POST /api/employees

###  Update Employee

PUT /api/employees/{id}

###  Delete Employee

DELETE /api/employees/{id}

---

##  Sample JSON

{
"name": "Prashant",
"email": "[prashant@gmail.com](mailto:prashant@gmail.com)",
"department": "IT",
"salary": 50000
}

---

##  Run Locally

1. Clone the repository
2. Open in IDE
3. Configure MySQL in application.properties
4. Run the project


##  API Testing

Tested using Postman

