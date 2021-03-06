# Taxi service

# Description

This is a simple project made to show my skills in Java, JDBC, WEB, OOP.
The goal of this project is to create a taxi service. 

The project implements driver authentication with different functionality. 
To use all features you need to create new driver and log in, after that you can:

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
- MySQL
- JDBC
- Servlet Api
- JSP
- JSTL
- TomCat

# Setup
1. Fork this project.
2. Install MySQL and MySQL Workbench.
3. Initialize the MySQL database using the init.sql file.
4. Configure Apache Tomcat.
5. Then in MySQL Workbench create and open new connection with your credentials or use the existing one.
6. In the /util/ConnectionUtil.java class change the username and password  properties to the ones you specified when installing MySQL.
7. After starting the project, click on "Create a new Driver" to add the first driver.