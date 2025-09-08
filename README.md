# Movie Management API

## About

This project is a backend API built using Spring Boot to manage movies. It lets you add, update, view, and delete movies with details like title, director, release year, genre, and rating.

## Tech Used

- Java 21  
- Spring Boot  
- Spring Data JPA (Hibernate)  
- MySQL database  
- Maven for building the project  

## How To Run

1. First, clone the project:  
2. Update the database settings:  
- Open `src/main/resources/application.properties`  
- Change the MySQL username, password, and database name to match your setup.
3. Build and start the project:  
4. The API will start on `http://localhost:8080`.

## What You Can Do With This API

| Request Type | URL            | Action                  |
|--------------|----------------|-------------------------|
| GET          | `/movies`      | See all movies          |
| GET          | `/movies/{id}` | See details of one movie|
| POST         | `/movies`      | Add a new movie         |
| PUT          | `/movies/{id}` | Change details of a movie|
| DELETE       | `/movies/{id}` | Remove a movie          |

## Tests & Documentation

- There are no automated tests included yet.  
- Swagger API documentation is not added in this version.

## Notes

This is my first API project with multiple layers like Entity, DAO, Service, and Controller. I am still learning and plan to improve tests and documentation soon.
