# Seattle Football Seahawks Member Cards Repository

Welcome to the Seattle Football Seahawks Member Cards repository. This project serves as the backend system for managing member data, with a focus on providing a seamless interface for the Seattle Seahawks football team's member management.

## Backend

The backend is built using Spring Framework, which offers a robust and scalable platform to handle our RESTful API services. Spring's dependency injection and transaction management capabilities enable us to write clean and maintainable code.

## Database

For data persistence, we utilize PostgreSQL. It's a powerful, open-source object-relational database system that provides a strong foundation for storing member information and handling complex queries with high performance.

## Frontend

The frontend is developed with React, a popular JavaScript library for building user interfaces. React's component-based architecture allows us to create a dynamic and responsive experience for the team members and fans interacting with the platform.

## Getting Started

To get started with this project, clone the repository to your local machine and follow the setup instructions below.

### Prerequisites

- JDK 21.0.1 or later
- Maven 3.9.6
- PostgreSQL 16 or later

### Configuration

Create an `application.yml` file under the `src/main/resources` directory. This file should contain all the necessary configurations for the application, including database connection details. Below is a template to get you started:

```yml
spring:
  datasource:
    url: jdbc:postgresql://localhost:5432/your-database
    username: your-username
    password: your-password
  jpa:
    hibernate:
      ddl-auto: update
    show-sql: true
```

### Installation
Clone the repository:
```java
git clone https://github.com/your-github-username/seattle.seahawks.git
```
Navigate to the project directory:
```java
cd seahawks/src/main/java/Seattle/seahawks
```
Build the project using Maven:
```java
mvn clean install
```
Run the application:
```java
mvn spring-boot:run
```
The server should start, and the application will be available on http://localhost:8080.

