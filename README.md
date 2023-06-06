# P1 - Full-Stack Task managment Project

## Introduction

This is a Java-based full stack task-management application.A user can manage,track,create and label tasks using this application. The application will be primarily built using Spring boot and Angular frame works and will utilize a PostgreSQL database to store tasks and user information.

## User Stories

- **As a user**, I want to be able to register an account. 
- **As a user**, I want to be able to log in to my account. 
- **As a user**, I want to be able to create a new task. 
- **As a user**, I want to be able to view all my tasks. 
- **As a user**, I want to be able to edit an existing task. 
- **As a user**, I want to be able to delete a task. 
- **As a user**, I want to be able to assign a task to myself or another user. 
- **As a user**, I want to be able to set a due date for a task. 
- **As a user**, I want to be able to mark a task as complete. 
- **As a user**, I want to be able to search for tasks based on their title or description. 
- **As a user**, I want to be able to sort tasks by their due date or creation date. 



## MVP (Minimum Viable Product)

- User registration and login
- create a new task
- mark a task as complete
- edit an existing task
- assign a task  
- delete a task
- view all tasks
- search for tasks based on their title or description
- filter tasks based on their completion status
- Implementing Task Priority and Urgency level


## Stretch Goals

- Task Reminders and Notifications
- Generate Task Analytics and Reports

## Tech Stacks

- **Angular**: Frame work to build the user interface of the application.
- **SpringBoot**:Frame work to develop the backend of the application.
- **Java**: The main programming language used for building the application.
- **PostgreSQL**: Used as the database to store user, product, and order data.
- **Maven or Gradle**: Used for managing project dependencies.
- **JUnit**: A testing framework for Java applications, used to ensure our code works as expected.
- **Log4j**: A logging utility for debugging purposes.
- **JDBC (Java Database Connectivity)**: An API for connecting and executing queries on the database.
- **BCrypt**: A Java library for hashing and checking passwords for security.
- **JUnit, Mockito, and PowerMock**: Used for unit and integration testing.
- **Git and GitHub**: Used for version control.

## Requirements

- **Clean Codebase**: All code should be clean and well-documented. The repository should not include any unnecessary files or folders such as the `target/`, `.DS_Store`, etc. All files and directories should be appropriately named and organized.

- **Database Design**: The database should be designed following the principles of the 3rd Normal Form (3NF) to ensure data integrity and efficiency. An Entity Relationship Diagram (ERD) should be included in the documentation.

- **Secure**: All sensitive user data such as passwords must be securely hashed before storing it in the database. The application should not display any sensitive information in error messages.

- **Error Handling**: The application should handle potential errors gracefully and provide clear and helpful error messages to the users.

- **Testing**: The application should have a high test coverage. Unit tests and integration tests should be implemented using JUnit, Mockito, and PowerMock.

- **Version Control**: The application should be developed using a version control system, preferably Git, with regular commits denoting progress.

- **Documentation**: The repository should include a README file with clear instructions on how to run the application. Code should be well-commented to allow for easy understanding and maintenance.

- **Scalable**: The design of the application should be scalable, allowing for easy addition of new features or modifications in the future.

##ERD diagram
![image](https://github.com/052223-java-angular/Bethelhem_P1-Back_End/assets/98676637/f5be67cb-6b0b-4af6-befb-38a69cbf0b92)

