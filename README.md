# Taxi service

# Description

This is a project to show my skills in working with Java, JDBC, Web and OOP
The goal of this project is to create a simple taxi service

User (driver) authentication is implemented in the project.
After logging in to the user authentication system, the following functionality is available to him:

- Add car, driver or manufacturer
- Display car, driver or manufacturer
- Delete car, driver or manufacturer
- Add driver to car
- Display all drivers for current car

# Implementation details
Project based on 3-layer architecture:

- Presentation layer (controllers)
- Application layer (services)
- Data access layer (DAO)

# Technologies
- Java 11
- MySQL 8.0.29
- JDBC
- Servlet Api
- JSP
- JSTL
- TomCat 9.0.64

# Setup
1. Fork this project.
2. Install MySQL.
3. Initialize the MySQL database using the init.sql file.
4. Install Tomcat version 9.0.*
5. Configure Apache Tomcat.
6. Then in MySQL create and open new connection with your credentials or use the existing one.
7. In the /util/ConnectionUtil.java class change the username and password  properties to the ones you specified when installing MySQL.
8. After starting the project, click on "Create a new Driver" to add the first driver.