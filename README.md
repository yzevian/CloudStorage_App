# Cloud Storage Application

This project is an exercise to acquaint the developer with 
[Spring](https://spring.io),
[Spring Boot](https://spring.io/projects/spring-boot),
[Thymeleaf](https://www.thymeleaf.org/) 
the [Spring Initializer](https://start.spring.io/), 
the [MyBatis](https://mybatis.org) ORM (Object-Relational Mapping) framework,
the [JUnit 5](https://junit.org/junit5/) testing framework,
the [Selenium](https://www.selenium.dev/) WebDriver for integration testing and 
the IntelliJ IDE.

## Table of contents
* [Project Requirements](#requirements)
* [Setup](#setup)
* [Resources](#resources)
* [Thanks](#thanks)
* [Deployment](#deployment)

## Framework
 
1. The back-end with Spring Boot
2. The front-end with Thymeleaf
3. Application tests with Selenium

The instructors provide the student developer with front-end 
html files, a hashing service class, an encryption service class and
a Spring Boot framework using Maven.

## Setup 
### Launch
The project requires IntelliJ IDE and has only tested in that development environment.
The Maven project file (pom.xml) provides all dependencies.
The main() method is found in:

`cloudstorage/src/main/java/com/udacity/jwdnd/course1/cloudstorage/CloudStorageApplication.java`

### JUnit Tests 
Integration tests on Chrome can be found here:

`
cloudstorage/src/test/java/com/udacity/jwdnd/course1/cloudstorage/CloudStorageApplicationTests.java
`

There are also JUnit tests for the model layer.  They can be found in the `
cloudstorage/src/test/java/com/udacity/jwdnd/course1/cloudstorage/model/` package.


## Deployment 
This project pushes commits to a Jenkins installation in the AWS Cloud which deploys the [application to a Docker container](https://cloudstorage.davidjdickinson.com).
