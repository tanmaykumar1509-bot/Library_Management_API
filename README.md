# Library Management REST API

A lightweight, RESTful web service built with **Java 17** and **Spring Boot 3.3.5** for managing library book records. It provides full CRUD (Create, Read, Update, Delete) functionality backed by an in-memory data store and includes a pre-configured Postman collection for immediate API testing.

---

## Tech Stack

- **Language:** Java 17
- **Framework:** Spring Boot 3.3.5 (`spring-boot-starter-web`)
- **Build Tool:** Apache Maven
- **Data Storage:** In-memory `ArrayList` (pre-seeded on startup)
- **API Testing:** Postman Collection v2.1

---

## Project Structure

```text
LibraryManagementRESTAPI/
├── postman/
│   └── Library_Management_API.postman_collection.json
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── library/
│       │           ├── LibraryManagementApiApplication.java
│       │           ├── controller/
│       │           │   └── BookController.java
│       │           └── model/
│       │               └── Book.java
│       └── resources/
│           └── application.properties
└── pom.xml
