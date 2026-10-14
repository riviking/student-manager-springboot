# Student Registration System

A Spring Boot CRUD web application for registering students, built for COSC 32133 / BECS 32263 Lab Sheet 04.

## Features
- Add students with form validation (name, email, phone, course, age)
- View all students in a table
- Edit and delete student records
- Data stored in an H2 in-memory database

## Tech Stack
Spring Boot, Spring Data JPA, Thymeleaf, H2 Database, Bean Validation

## How to Run
1. Run `./mvnw spring-boot:run` (or run `StudentmanagerApplication.java` from the IDE)
2. Open http://localhost:8080
3. H2 console: http://localhost:8080/h2-console (JDBC URL: `jdbc:h2:mem:studentdb`, user: `sa`, no password)