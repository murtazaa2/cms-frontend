 # Contact Management System

A full-stack Contact Management System built using **Java Spring Boot**, **Spring Security**, **JWT Authentication**, **MySQL**, and **React.js**. The application allows users to securely manage their contacts through a modern web interface.

## Features

### Authentication & Security

* User Registration
* User Login
* JWT-Based Authentication
* Protected Routes
* Secure API Access

### Contact Management

* View All Contacts
* Add New Contacts
* Edit Existing Contacts
* Delete Contacts
* Contact Details Management

## Technology Stack

### Backend

* Java 17
* Spring Boot
* Spring Security
* JWT (JSON Web Token)
* Spring Data JPA
* Hibernate
* MySQL

### Frontend

* React.js
* React Router
* Axios
* Bootstrap

### Development Tools

* IntelliJ IDEA
* Visual Studio Code
* MySQL Workbench
* Postman
* Git & GitHub

## System Architecture

React Frontend
       │
       ▼
Spring Boot REST API
       │
       ▼
Service Layer
       │
       ▼
Repository Layer
       │
       ▼
MySQL Database

## Database Structure

### Users Table

| Column   | Type    |
| -------- | ------- |
| id       | BIGINT  |
| username | VARCHAR |
| password | VARCHAR |

### Contacts Table

| Column     | Type    |
| ---------- | ------- |
| id         | BIGINT  |
| first_name | VARCHAR |
| last_name  | VARCHAR |
| title      | VARCHAR |
| email      | VARCHAR |
| phone      | VARCHAR |

## API Endpoints

### Authentication

| Method | Endpoint           |
| ------ | ------------------ |
| POST   | /api/auth/register |
| POST   | /api/auth/login    |

### Contacts

| Method | Endpoint           |
| ------ | ------------------ |
| GET    | /api/contacts      |
| GET    | /api/contacts/{id} |
| POST   | /api/contacts      |
| PUT    | /api/contacts/{id} |
| DELETE | /api/contacts/{id} |

## Screenshots

### Registration Page

(Add Screenshot Here)

### Login Page

(Add Screenshot Here)

### Dashboard

(Add Screenshot Here)

### Contact List

(Add Screenshot Here)

### Add Contact

(Add Screenshot Here)

### Edit Contact

(Add Screenshot Here)

### Delete Contact

(Add Screenshot Here)

## Installation Guide

### Clone Repository

bash
git clone https://github.com/yourusername/contact-management-system.git


### Backend Setup

1. Open the Spring Boot project in IntelliJ IDEA.
2. Configure MySQL database in `application.properties`.

Example:

properties
spring.datasource.url=jdbc:mysql://localhost:3306/contactdb
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

3. Run the Spring Boot application.

Backend will start on:

http://localhost:8080

### Frontend Setup

Navigate to the frontend directory:

bash
cd frontend


Install dependencies:

bash
npm install

Start React application:

bash
npm run dev


Frontend will start on:

text
http://localhost:5173

## Authentication Flow

User Login
    │
    ▼
JWT Token Generated
    │
    ▼
Token Stored in Browser
    │
    ▼
Protected API Requests
    │
    ▼
Access Granted

## Testing

The project includes unit testing using:

* JUnit 5
* Mockito

Tested Components:

* ContactService
* CRUD Operations
* Repository Mocking

## Future Enhancements

* Contact Search Functionality
* Pagination
* Contact Categories
* Profile Picture Upload
* Email Notifications
* Contact Import/Export

## Learning Outcomes

This project demonstrates:

* Full Stack Development
* REST API Development
* Spring Security Implementation
* JWT Authentication
* React Frontend Development
* Database Integration with MySQL
* Unit Testing with JUnit and Mockito
* Git and GitHub Workflow

## Author

# Murtaza Moiz

Java Full Stack Developer (Learning Project)


This project is developed for educational and learning purposes.
