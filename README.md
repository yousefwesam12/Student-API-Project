# Student Management REST API

A simple RESTful Web API built with **ASP.NET Core** for managing student records and practicing the fundamentals of backend API development.

## Tech Stack

* **C#**
* **ASP.NET Core Web API**
* **LINQ**
* **RESTful API**
* **Swagger / OpenAPI**

## Features

* Get all students
* Get a student by ID
* Get passed students
* Calculate average grades
* Add a new student
* Update student information
* Delete a student
* Input validation
* HTTP status code handling
* Swagger API documentation

## API Endpoints

| Method   | Endpoint                     | Description         |
| -------- | ---------------------------- | ------------------- |
| `GET`    | `/api/Students/All`          | Get all students    |
| `GET`    | `/api/Students/Passed`       | Get passed students |
| `GET`    | `/api/Students/AverageGrade` | Get average grade   |
| `GET`    | `/api/Students/{id}`         | Get student by ID   |
| `POST`   | `/api/Students`              | Add a student       |
| `PUT`    | `/api/Students/{id}`         | Update a student    |
| `DELETE` | `/api/Students/{id}`         | Delete a student    |

## Swagger

The API endpoints are documented and tested using **Swagger/OpenAPI**, providing an interactive interface for sending requests and viewing responses.

## Data Storage

The project currently uses an **in-memory collection** to simulate student data, so no external database is required.

## Project Structure

```text
StudentApi/
├── Controllers/
│   └── StudentsController.cs
├── Models/
│   └── Student.cs
├── DataSimulation/
│   └── StudentDataSimulation.cs
└── Program.cs
```

## Purpose

This project was built to practice **ASP.NET Core Web API**, RESTful API design, CRUD operations, LINQ, input validation, HTTP status codes, and Swagger documentation.
