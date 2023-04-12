# Library Management System

This project was bootstrapped with [Spring Initializer](https://start.spring.io/).

## Synopsis
This project focuses on the development of a centralized library management system aimed at streamlining library operations, improving inventory management, and enhancing the user experience. The proposed system will automate the cataloging, lending, and user management processes, addressing the issues faced by libraries with multiple branches in managing their collections, tracking lending, and providing efficient services to users. By leveraging a scalable, cloud-based architecture, the Library Management System (LMS) will be designed to adapt to the growing needs of libraries and support various functionalities, such as book cataloging, inventory management, user management, and search capabilities.

## Tools
IDE: 
> IntelliJ Ultimate 

Platforms Supported: 
> MacOS v12.6.4 and above, and Windows 10 and above

Language: 
> SQL, Java


Package Managers: Maven
Java Version: 
> OpenJDK version "17.0.2" 2022-01-18 <br/>
> OpenJDK Runtime Environment (build 17.0.2+8-86) <br/>
> OpenJDK 64-Bit Server VM (build 17.0.2+8-86, mixed mode, sharing)

Maven Version: 
> 3.8.2

## Build Steps
### Step 0 
Install appropriate versions of Java, Maven, and MariaDB
### Step 1: 
After installing MariaDB you’ll want to set the password for the root user<br/>
```GRANT ALL PRIVILEGES on *.* to 'root'@'localhost' IDENTIFIED BY 'password';```<br/><br/>
Or if you have a user and password already set you can go into `lms-core/src/main/resources/application.properties` and change the `spring.datasource.username` and `spring.datasource.password` to your desired username and password

### Step 2: 
run `mvn clean install` on the root folder of the library management system

### Step 3: This project works best when using an ide, but you can also run it from the command line.
#### For the Backend
Change directory to lms-core
`cd lms-core` <br/>
Run springboot application using maven
	`mvn spring-boot:run`


## Learn More
### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.0.2/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.0.2/maven-plugin/reference/html/#build-image)

"# Lms" 
"# Lms" 
