Installation
Prerequisites
Java 11 or later
Maven
H2 Database (used for development; you can configure another database if needed)
Steps to Run the Project Locally
Clone the repository:

bash
Copy code
git clone https://github.com/karunkarthickc/medical.git
Navigate to the project directory:

bash
Copy code
cd medical-api
Build the project:

bash
Copy code
mvn clean install
Run the application:

bash
Copy code
mvn spring-boot:run
The API will be accessible at http://localhost:8080.

Endpoint	Method	Description
/api/users/register	POST	Register a new user
/api/users/login	POST	Log in an existing user with email and password
/api/heartrate/all	GET	Get all heart rate records
/api/heartrate/user/{userId}	GET	Get heart rate records for a specific user by userId
/api/users/test	GET	Test the API to check if it's working

