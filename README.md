# USER REGISTRATION AND FETCHING DATA - BACKEND PROJECT
Implementing a user register and user details fetch endpoints for a RESTful API using Spring Boot

**REQUIERMENTS**

-JAVA 17.0 or latest version

-Maven

-curl or poestman

-spring boot

-IDE(like eclipse)

**Implementation process of User registeration**

-> setup the project using spring boot initializer and add appropriate dependencies

-> unzip the folder and open the folder in java IDE

-> create class file to create application

- model
- service
- exception
- controller

-> After code compilation of class files , Run Application file in IDE or terminal

-> In cmd terminal , set the root path of the project - C:\path\root\project

-> Run mvn(Maven) by using command

 - mvn spring-boot:run(in cmd)

 -> After execution , use the API to connect to thew local host 8080

 -> API ENDPOINT - https://localhost:8080//api/users/register [POST]
 
 using this url access the application for user registration in curl or in POSTMAN application

 -> finally you will get the port to register the username , name, emailid, password in database

 **Implementation process of User Fetch**

 ->-> setup the project using spring boot initializer and add appropriate dependencies

-> unzip the folder and open the folder in java IDE

-> create class file to create application

- model
- service
- exception
- controller
- Repository

-> After code compilation of class files , Run Application file in IDE or terminal

-> In cmd terminal , set the root path of the project - C:\path\root\project

-> Run mvn(Maven) by using command

 - mvn spring-boot:run(in cmd)

 -> After execution , use the API to connect to thew local host 8080

 -> API ENDPOINT - https://localhost:8080//api/users/fetch [GET]
 
 using this url access the application for user registration in curl or in POSTMAN application

 -> finally you will get the port to FETCH the registered username , name, emailid from database.


 *Hence the project is performed executed and successfully.* 


 
