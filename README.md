# CRUD-Application-Spring-Boot-Mysql

This is a **Spring Boot CRUD Application** built using IntelliJ IDEA, MySQL, JPA, Hibernate, Thymeleaf, and Bootstrap. It demonstrates the implementation of basic CRUD (Create, Read, Update, Delete) operations on a MySQL database, utilizing Java and the Spring Boot framework.

## Features
- Basic CRUD operations with MySQL.
- MVC architecture using Spring Boot and Thymeleaf.
- JPA and Hibernate for database interaction.
- Responsive frontend with Bootstrap.

## Technologies Used
- **Java**
- **Spring Boot**
- **JPA & Hibernate**
- **MySQL**
- **Thymeleaf**
- **Bootstrap**

## Requirements
To run this project, you need:
- Java 17 or later
- Maven 3.6+ (optional)
- MySQL Server
- IntelliJ IDEA (or any preferred IDE)

## Application Structure
- Controller: Handles HTTP requests.
- Model: Represents the entities mapped to the database.
- Repository: Interfaces for JPA queries.
- Service: Contains the business logic.

## Endpoints
- GET /users: Displays all records.
- POST //users/new: Displays a form to add a new user.
- GET /users/edit/{id}: Displays the edit form for a specific user by their ID.
- POST //users/save: Saves a new user or updates an existing user.
- GET /users/delete/{id}: Deletes a specific user by their ID.

## Project Setup

### 1. Clone the Repository

### 2. Configure database

### 3. Update application.properties
    Modify the database configuration in src/main/resources/application.properties
    
### 4.Build and Run the Project

### 5.Access the Application
    http://localhost:8080


