# User_management

This is a User Management project which is built using Java and Spring Boot.
It includes RESTful service endpoints to create, list, update and delete Users. It also Includes a login endpoint to validate email and password against existing Users.
Each user contains attributes such as name, email, password and last login time. H2 in-memory database is used to store and fetch the data.


# Building the project

Java  version Used: `Java 11`

Maven version Used:` >3.8.0`

Run `mvn clean install ` from parent directory to build the project.

# Running the Application

Run `mvn spring-boot:run` to run the application from command line

once your application is running you can access the endpoints from any API testing tool by importing User management.postman_collection.json that is present in the parent directory.


## Sample Outputs

Creating User

<img width="1409" alt="Screenshot 2024-07-11 at 6 04 32 PM" src="https://github.com/sumanthreddy111/User_management/assets/60144092/20a457d2-54c2-4dac-8d9d-97b06b42ebb3">

List User

<img width="1409" alt="Screenshot 2024-07-11 at 6 04 59 PM" src="https://github.com/sumanthreddy111/User_management/assets/60144092/a66ecd68-ba61-4821-be2a-bcf6fbd66a75">

Update User

<img width="1409" alt="Screenshot 2024-07-11 at 6 05 20 PM" src="https://github.com/sumanthreddy111/User_management/assets/60144092/727430e2-5326-430f-bc30-ebda28b3ff4a">

Delete User

<img width="1409" alt="Screenshot 2024-07-11 at 6 05 48 PM" src="https://github.com/sumanthreddy111/User_management/assets/60144092/ca43322c-5e6b-4de7-b84c-8cd992364aaf">

Successful User login

<img width="1409" alt="Screenshot 2024-07-11 at 6 05 34 PM" src="https://github.com/sumanthreddy111/User_management/assets/60144092/5b2076f3-99fd-4eee-aacf-36d372b7d90f">

resource not found

<img width="1409" alt="Screenshot 2024-07-11 at 6 05 57 PM" src="https://github.com/sumanthreddy111/User_management/assets/60144092/abead6dc-8f35-49ad-9621-fd4db45cb5b0">




