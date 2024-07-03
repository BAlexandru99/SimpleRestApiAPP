# **Student REST API**

This repository hosts a straightforward RESTful API designed for managing student information, developed using the Spring Boot framework in Java. 

## Features

- **Get All Students**: Retrieve a comprehensive list of all registered students.
- **Get Student by ID**: Fetch detailed information about a specific student by their unique identifier.
- **Exception Handling**: Efficiently manages exceptions like StudentNotFoundException and ensures appropriate error responses are provided.

## Usage

To utilize this API, follow these simple steps:

1. **Clone the Repository**: Clone this repository to your local machine using Git.

    ```bash
    git clone https://github.com/your_username/student-rest-api.git
    ```

2. **Run the Application**: Navigate to the project directory and execute the application using Maven or your preferred IDE.

    ```bash
    mvn spring-boot:run
    ```

3. **Access the API**: Once the application is up and running, access the API endpoints using tools like Postman or integrate HTTP requests directly into your application.

    - Base URL: `http://localhost:8080/api`
    - **GET /students**: Retrieve a list of all students.
    - **GET /students/{studentId}**: Retrieve detailed information about a specific student by their ID.

## Dependencies

This project relies on the following dependencies:

- Spring Boot
- Spring Web
- Jakarta EE (Java Enterprise Edition)
- Maven
