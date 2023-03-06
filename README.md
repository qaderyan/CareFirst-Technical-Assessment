Employee Management System:

This Employee Management System is a Java-based application that utilizes Spring Boot and MongoDB. It provides REST API calls for managing employee data, along with exception handling and JUnit test cases. This project was developed by Rohin Qaderyan for the CareFirst FSD Interview Project Request.

Getting Started:

To get started with the Employee Management System, you will need to have Java, Maven, and MongoDB installed on your system. You can then clone this repository and run the application using the following command:

bash
Copy code
mvn spring-boot:run
The application will start up on port 8080. You can then access the REST API using your preferred HTTP client.

API Calls
The following REST API calls are available:

Method	Endpoint	Description:

GET	/employees	Get all employees
GET	/find	Get employee with particular name and designation (AND operator on Mongo)
DELETE	/delete/{id}	Get an employee by ID
POST	/createemployee	Add a new employee
PUT	/employees/{id}	Update an employee by ID
GET	/salary	Get total salary in a particular designation (Group By clause on Mongo)
Exception Handling
The Employee Management System includes exception handling for the following scenarios:

Employee not found:

Invalid request
Missing required fields
MongoDB is not responding
Unit Tests
The Employee Management System includes JUnit tests for the following scenarios:

Get all employees:

Get an employee by ID
Add a new employee
Update an employee by ID
Delete an employee by ID
Get employee with constraints

Database:

The Employee Management System uses MongoDB as its database. You can configure the database connection settings in the application.properties file. Here the implementation is done using MongoTemplate as it supports more complex queries.

Technologies Used:

The following technologies were used in the development of the Employee Management System:

Java 8
Spring Boot
MongoDB
Maven
JUnit

Contributing:

Contributions to the Employee Management System are welcome. To contribute, please fork this repository, make your changes, and submit a pull request.

License:

This project was inspired by the need for a simple and efficient employee management system. Special thanks to the Spring Boot, MongoDB, and JUnit communities for their contributions to open-source software.
