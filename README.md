# User_management

This is a User Management project which is built using Java and Spring Boot.
It includes RESTful service endpoints to create, list, update and delete Users. It also Includes a login endpoint to validate email and password against existing Users.
Each user contains attributes such as name, email, password and last login time. H2 in-memory database is used to store and fetch the data.


#Building the project

Java  version Used: `Java 11`

Maven version Used:` >3.8.0`

Run `mvn clean install ` from parent directory to build the project.

#Running the Application

Run `mvn spring-boot:run` to run the application from command line

once your application is running you can access the endpoints from any API testing tools by importing the below json file.

[User management.postman_collection.json](User management.postman_collection.json)