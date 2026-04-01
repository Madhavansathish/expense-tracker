# Expense Tracker - Spring Boot REST API

## Overview

The Expense Tracker is a backend RESTful application built using Spring Boot. It enables users to manage and track their expenses through a set of well-defined APIs. The system supports core CRUD operations and demonstrates clean layered architecture with database integration.

---

## Features

* Create, read, update, and delete expenses
* RESTful API design following standard HTTP methods
* Layered architecture (Controller, Service, Repository)
* Persistent storage using MySQL
* Structured and maintainable codebase

---

## Tech Stack

* Backend: Java, Spring Boot
* Framework: Spring Web
* Database: MySQL
* ORM: Spring Data JPA (Hibernate)
* Build Tool: Maven

---

## Project Structure

src/
└── main/
├── java/com/example/demo/
│    ├── controller/
│    ├── service/
│    ├── repository/
│    ├── entity/
│    └── DemoApplication.java
└── resources/
└── application.properties

---

## How to Run the Project

1. Clone the repository:
   git clone https://github.com/Madhavansathish/Expense_tracker_springboot.git

2. Open the project in an IDE such as IntelliJ IDEA or Eclipse.

3. Configure the database in application.properties:
   spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
   spring.datasource.username=your_username
   spring.datasource.password=your_password

4. Run the application by executing:
   DemoApplication.java

5. Access the application at:
   http://localhost:8080

---

## API Endpoints

| Method | Endpoint       | Description            |
| ------ | -------------- | ---------------------- |
| POST   | /expenses      | Create a new expense   |
| GET    | /expenses      | Retrieve all expenses  |
| GET    | /expenses/{id} | Retrieve expense by ID |
| PUT    | /expenses/{id} | Update an expense      |
| DELETE | /expenses/{id} | Delete an expense      |

---

## Key Concepts Demonstrated

* RESTful API design
* Spring Boot auto-configuration
* Dependency Injection
* Layered architecture (Controller, Service, Repository)
* JPA/Hibernate ORM
* MySQL database integration

---

## Future Enhancements

* Add authentication and authorization (JWT)
* Implement pagination and filtering
* Add analytics and reporting features
* Integrate frontend client (React or Angular)

---

## Author

Madhavan

---

## Notes

This project is developed to demonstrate backend development capabilities using Spring Boot, focusing on clean architecture, API design, and database interaction.
