# CPUT Module Tracker 📚✨

Welcome to the CPUT Module Tracker project! This standalone Java application is designed for CPUT Application Development students to track their module performance throughout their academic journey.

## Purpose

As students progress from their first to third year, managing multiple modules with unique assessment structures can be challenging. This application empowers students with features that support their academic success.

## Dependencies used:

### 1. Spring Web
**Purpose:**  
Spring Web provides support for building web applications. It implements the MVC architecture and facilitates the creation of RESTful services. This dependency helps in handling HTTP requests, managing sessions, and serving web pages or JSON responses.

### 2. Spring Data JPA
**Purpose:**  
Spring Data JPA simplifies data access by providing an abstraction over JPA. It allows for easy data management through repository interfaces, reducing boilerplate code. This dependency enables CRUD operations and query methods to interact with the database effortlessly.

### 3. H2 Database
**Purpose:**  
H2 is a lightweight, in-memory database, ideal for development and testing. It allows for quick prototyping without the need for a full database setup. This dependency is useful for storing student records temporarily during development.

### 4. Thymeleaf
**Purpose:**  
Thymeleaf is a server-side Java template engine that integrates seamlessly with Spring. It allows for dynamic HTML rendering and supports features like conditional rendering and iteration. This dependency is used for creating the application's user interface.

### 5. Spring Boot DevTools
**Purpose:**  
Spring Boot DevTools enhances the development experience by providing features like automatic restarts and live reload. This dependency streamlines the development workflow, allowing for rapid iterations without the need for manual server restarts.

## File Descriptions

### 1. Config
- **Purpose:** Configuration settings for the application.
- **File(s):**
  - `SecurityConfig.java`: Configures security settings, allowing access control for different routes.

### 2. Controller
- **Purpose:** Handles incoming HTTP requests and returns responses.
- **File(s):**
  - `StudentController.java`: Manages student-related requests, including listing and adding students.

### 3. Model
- **Purpose:** Represents the data structure.
- **File(s):**
  - `Student.java`: Defines the `Student` entity with attributes like name, email, and marks.

### 4. Repository
- **Purpose:** Interface for data access.
- **File(s):**
  - `StudentRepository.java`: Provides methods for accessing and manipulating `Student` records in the database.

### 5. Service
- **Purpose:** Contains business logic and interactions with the repository.
- **File(s):**
  - `StudentService.java`: Implements methods for retrieving and saving student data.

### 6. Resource
- **Purpose:** Contains static resources and templates.
- **File(s):**
  - Static resources (e.g., CSS, JS) are located in `src/main/resources/static/`.
  - Thymeleaf templates (e.g., `students.html`) are located in `src/main/resources/templates/`.

### 7. Test
- **Purpose:** Testing your application.
- **File(s):**
  - `StudentProgressApplicationTests.java`: Contains tests for ensuring the application context loads correctly.

## Summary
This structure and the contents of each file will are used to build Student Progress Tracking Web Application effectively. It covers configuration, controllers, models, repositories, services, templates, and testing.

## How to Run
1. Clone the repository.
2. Navigate to the project directory.
3. Run the application using `mvn spring-boot:run`.
4. Access the application at `http://localhost:8080`.

## Web-APP Key Features

- **User Registration & Authentication**: Secure access to the application.
- **Year of Study Selection**: Navigate through different academic levels.
- **Module Management**: Organize core and elective modules.
- **Assessment Tracking**: Monitor tests, assignments, quizzes, and exams with varying weightings.
- **Grade Calculation**: Automatically calculate grades based on assessments.
- **Progress Tracking**: Track progress after each completed task.
- **Projection Tools**: Predict future performance.
- **Intervention Features**: Support struggling students.
- **Local Data Storage**: Securely store user data.
