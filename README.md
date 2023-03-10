# Cinema-app

----------------------
## Description
Web app pet project that supports authentication, authorization and have CRUD operations (with Spring and Hibernate).


## Technologies used:

- Java 17
- Spring MVC
- Spring Security
- MySQL
- Hibernate
- TomCat (9.0.71)
- Maven

## Functional app schema
![pic](Cinema.png)

## Project structure
- Controllers 
- Service
- Model and DTO 
- DAO
- Config


# How to run this project
- If you don't have MySQL and TomCat(version 9.0.71) - install it.
- Clone this repository to your IDE and open it.
- Replace your data (URL, username, password, JDBC Driver) in ConnectionUtil.
- Edit configuration of your TomCat.
- Run -mvn package command in terminal.
- Run TomCat and try app.
- Also, you can use Postman for POST endpoints