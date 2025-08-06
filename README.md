# Spring Security JWT Authentication

This project demonstrates how to secure a Spring Boot REST API using **Spring Security** and **JWT (JSON Web Tokens)**.

## Features

- Form-based login & Basic authentication
- Custom security filter
- Stateless JWT authentication
- Role-based access control
- Password hashing using BCrypt
- In-memory & database-based authentication
- JWT token generation and validation
- Integration with H2 database

## Technologies

- Java 17+
- Spring Boot
- Spring Security
- JWT
- H2 Database
- Maven

## Endpoints

| Method | Endpoint         | Description                    |
|--------|------------------|--------------------------------|
| POST   | `/api/auth/signin` | Authenticate and get JWT token |
| GET    | `/api/test/user` | Access for authenticated users |
| GET    | `/api/test/admin`| Access restricted to ADMIN role |

## Run the Project

```bash
./mvnw spring-boot:run
