<<<<<<< HEAD
# BoardGame
=======
# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  
![Screenshot (457)](https://github.com/user-attachments/assets/02f50f10-0af8-42b2-bc00-27acec15fe04)
![Screenshot (453)](https://github.com/user-attachments/assets/c84ebbd4-347c-4dec-baa0-27750a84dbe2)
![Screenshot (452)](https://github.com/user-attachments/assets/0dc18e0e-aec3-4bdb-a6bd-581defae99ea)
![Screenshot (448)](https://github.com/user-attachments/assets/c3e212ba-266f-49ea-aa99-4ecd0df52afe)
![Screenshot (455)](https://github.com/user-attachments/assets/6701cca9-6714-4249-8d8b-95ed3bb5c58f)
![Screenshot (454)](https://github.com/user-attachments/assets/34923e79-fb62-4d7d-afaf-08d43dd85a53)

![Screenshot (463)](https://github.com/user-attachments/assets/ad2b28a3-613d-4545-b8c4-e20173723dde)
![Screenshot (462)](https://github.com/user-attachments/assets/040db040-f1e4-40ab-898a-63bf568fd65f)
![Screenshot (461)](https://github.com/user-attachments/assets/c35dd250-7a0e-4592-bf42-794f4dab17a0)
![Screenshot (460)](https://github.com/user-attachments/assets/bc5e656f-56f0-4ef1-9637-86f467493609)
![Screenshot (459)](https://github.com/user-attachments/assets/ab310d51-8b70-41e3-af31-c0b995536c04)
![Screenshot (458)](https://github.com/user-attachments/assets/35774d71-5ac0-47a1-b3ed-fe606f748f9e)

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊


