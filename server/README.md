# Spring Boot CRUD API Backend

This project is a simple CRUD (Create, Read, Update, Delete) API backend built using Spring Boot. It provides endpoints to manage data for a specific domain, such as "Student," in a MySQL database.

## Table of Contents

- [Technologies](#technologies)
- [Features](#features)
- [Getting Started](#getting-started)
- [Endpoints](#endpoints)
- [Setup](#setup)
- [License](#license)

## Technologies

- Java 17
- Spring Boot 3.1.1
- MySQL Database

## Features

- Create a new record for a Student.
- Retrieve a specific student record by ID.
- Retrieve all student records.
- Update an existing student record.
- Delete a student record by ID.

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. Ensure you have Java 11 or higher installed on your machine.
2. Set up a MySQL database. Update the `application.yml` file with your database credentials.
3. Clone this repository to your local machine.
4. Open the project in your preferred Integrated Development Environment (IDE).
5. Build the project using the build tool of your choice (e.g., Maven, Gradle).
6. Run the application using your IDE or the command-line interface.

## Endpoints

| Method | Endpoint                   | Description                      |
| ------ | -------------------------- | -------------------------------- |
| POST   | /api/students             | Create a new student record.    |
| GET    | /api/students             | Retrieve all student records.   |
| GET    | /api/student/{id}        | Retrieve a specific student.    |
| PUT    | /api/students//update/{id}        | Update an existing student.     |
| DELETE | /api/students/delete/{id}        | Delete a student record.        |

## Setup

To set up the project locally, you need to have Java 11 or higher and a MySQL database installed. Here's how you can set it up:

1. Clone the repository: https://github.com/pradeep8577/Spring-Boot-CRUD/

2. Open the project in your IDE.

3. Update the `application.yml` file with your MySQL database credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/YourDatabaseName
spring.datasource.username=your-username
spring.datasource.password=your-password
```
4. build the project using Maven or Gradle:

  - For Maven:
``` mvn clean install ```

  - For Gradle:
``` ./gradlew clean build ```

## License
This project is licensed under the MIT License.