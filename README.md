<h6 align="center"><img height="200" src="https://media.gettyimages.com/vectors/taxi-car-vector-id1161667429?k=20&m=1161667429&s=612x612&w=0&h=wRxiIAMdxqggCCybbJYlPk-oSQPzXEWqHvGGk47hzJ0=" width="200"/></h6>

# Taxi service


### Description

---
This is the implementation of a primitive taxi service, its purpose - to show the ability to build a three-tier web application:
* level controllers - for communication with the user
* level service - the main logic of the program
* level DAO - to communicate the program with the database

### Technologies

---
* java 11
* MySQL
* JSP
* JSTL
* XML
* Tomcat

### To run the program

---
1. In your computer must be installed java 11, MySQL and Tomcat for run this app
2. Fork this project in your repo and clone it
3. Initialize your database using __init_db.sql__ file that located in resources
4. Add your info to __ConnectionUtil__ located in util to be able to connect to your database
 ```java
    public static final String URL = " URL ADDRESS DATABASE";
    public static final String USERNAME = "USERNAME";
    public static final String PASSWORD = "PASSWORD";
    public static final String JDBC_DRIVER = "JDBC_DRIVER";
```
5. Run this project using Tomcat's local server

If the program was launched successfully, you need to register or log in to the received web page to use all the features of the program
