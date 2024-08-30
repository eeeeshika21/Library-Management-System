# Library Management System

The Library Management System is a simple and efficient application designed to manage a library's book inventory. Built using Spring Boot, this project demonstrates key features of Spring Boot, including RESTful web services, data access using Spring Data JPA, and basic frontend integration with HTML.

## Features

### Book Management:
- **CRUD Operations**: Create, read, update, and delete books in the library's inventory.
- **RESTful API Endpoints**: Expose RESTful endpoints for managing books.

### Web Interface:
- **Home Page**: A simple home page (`index.html`) served as a static resource.

## Project Structure

librarymanagement ├── src │ ├── main │ │ ├── java │ │ │ └── com.example.librarymanagement │ │ │ ├── LibrarymanagementApplication.java │ │ │ ├── controller │ │ │ │ ├── BookController.java │ │ │ │ └── HomeController.java │ │ │ ├── model │ │ │ │ └── Book.java │ │ │ └── repository │ │ │ └── BookRepository.java │ ├── resources │ │ ├── static │ │ │ └── index.html │ │ └── templates │ │ └── application.properties ├── target │ ├── generated-sources/annotations │ ├── generated-test-sources/test-annotations ├── .mvn ├── .vscode ├── .gitignore ├── HELP.md ├── mvnw ├── mvnw.cmd └── pom.xml

## Technologies Used
- **Spring Boot**
- **Spring Data JPA**
- **Java 17**
- **Maven**

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   cd library-management-system
Open the project in Visual Studio Code.

2.**Run the project**:

Use the built-in Spring Boot features to run the application directly from the IDE.

3.**Access the application**:

The REST API will be available at http://localhost:8080/.
The home page can be accessed at http://localhost:8080/index.html.
