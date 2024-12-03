# SpringBoot_Java_Project
This project is developed using the Spring Boot framework to build a Java application with various key Spring features such as MVC, CRUD operations, AOP, Security, and Spring Data JPA. Additionally, it includes functionality to generate Excel sheets and PDF files from the database.

 
## Features ##
 Spring Boot MVC: Implements the Model-View-Controller pattern for structuring web applications.
 
 Spring Boot CRUD: Supports Create, Read, Update, and Delete operations on entities in the application.
 
 Spring AOP (Aspect-Oriented Programming): Used for cross-cutting concerns like logging, transactions, etc.
 
 Spring Security: Secures the application by handling authentication and authorization.
 
 Spring Data JPA : Provides support for interacting with databases.
 
 Excel and PDF Generation: Retrieves data from the database and generates Excel sheets and PDF reports.
 

## Technologies Used
Java 17

Spring Boot 3.1.4


Spring MVC


Spring Data JPA 


Spring Security


Spring AOP


Thymeleaf (library for front-end)


MySQL for the database


Apache POI for Excel generation

 
openpdf for PDF generation(group id: com.github.librepdf)


Maven for dependency management


Git for version control

  
  
## Running the Application. 

First, create data in MySQL database for the testing (using SQL scripts provided)  
Once the application is running, you can perform the following:

Access the API:
Visit http://localhost:8080/ to access the application endpoints.

There will be Login page. Login using user credentials  
    user-name: priya, shilpa, max and  password: password123  These users have different access roles EMPLOYEE, MANAGER, and ADMIN respectively which is to demonstrate role based authorization in Spring security. Home page links are customized based on the user role. 
    

Click on the 'Employees Details' link page on home page to view all employees where you can add, update delete employees(CRUD operations). 
Additionally, you can generate Excel and PDF reports.    
   
    
