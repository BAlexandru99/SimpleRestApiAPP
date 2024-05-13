# **Student REST API**

This repository contains a simple RESTful API for managing student data. It's built using Spring Boot framework in Java.
https://www.udemy.com/course/spring-hibernate-tutorial/?couponCode=LETSLEARNNOW

## Features

- **Get All Students**: Retrieve a list of all students.
- **Get Student by ID**: Retrieve a specific student by their ID.
- **Exception Handling**: Handles exceptions such as StudentNotFoundException and provides appropriate error responses.

## Usage

To use this API, you can follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using Git.

```bash
git clone https://github.com/your_username/student-rest-api.git

2. **Run the Application**: Navigate to the project directory and run the application using Maven or your preferred IDE.
bash
Copy code
mvn spring-boot:run

3. **Access the API**: Once the application is running, you can access the API endpoints using a tool like Postman or by making HTTP requests from your application.

Base URL: http://localhost:8080/api
GET /students: Retrieve all students.
GET /students/{studentId}: Retrieve a specific student by ID.
Dependencies
This project requires the following dependencies:

Spring Boot
Spring Web
Jakarta EE (Java Enterprise Edition)
Maven
