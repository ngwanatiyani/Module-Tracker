# CPUT Module Tracker 📚✨

Welcome to the CPUT Module Tracker project! This standalone Java application helps CPUT Application Development students track their module performance throughout their academic journey.

## Purpose

As students progress from their first to third year, managing multiple modules with unique assessment structures can be challenging. This application empowers students with features that support their academic success.

## Dependencies

<details>
<summary>Click to expand</summary>

### 1. Spring Web
**Purpose:**  
Supports building web applications with MVC architecture and RESTful services.

### 2. Spring Data JPA
**Purpose:**  
Simplifies data access with repository interfaces for easy CRUD operations.

### 3. H2 Database
**Purpose:**  
A lightweight, in-memory database ideal for development and testing.

### 4. Thymeleaf
**Purpose:**  
A server-side template engine for dynamic HTML rendering.

### 5. Spring Boot DevTools
**Purpose:**  
Enhances development with features like automatic restarts and live reload.

</details>

## File Descriptions

<details>
<summary>Click to expand</summary>

### 1. Config
- **Purpose:** Configuration settings for the application.
- **File(s):** `SecurityConfig.java`

### 2. Controller
- **Purpose:** Handles HTTP requests and returns responses.
- **File(s):** `StudentController.java`

### 3. Model
- **Purpose:** Represents data structure.
- **File(s):** `Student.java`

### 4. Repository
- **Purpose:** Interface for data access.
- **File(s):** `StudentRepository.java`

### 5. Service
- **Purpose:** Contains business logic and repository interactions.
- **File(s):** `StudentService.java`

### 6. Resource
- **Purpose:** Contains static resources and templates.
- **File(s):** Static resources in `src/main/resources/static/` and templates in `src/main/resources/templates/`.

### 7. Test
- **Purpose:** Testing the application.
- **File(s):** `StudentProgressApplicationTests.java`

</details>

## Summary

This structure and the contents of each file facilitate the effective building of the Student Progress Tracking Web Application, covering configuration, controllers, models, repositories, services, templates, and testing.

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Run the application using `mvn spring-boot:run`.
4. Access the application at `http://localhost:8080`.

## Key Features

- **User Registration & Authentication:** Secure access to the application.
- **Year of Study Selection:** Navigate through different academic levels.
- **Module Management:** Organize core and elective modules.
- **Assessment Tracking:** Monitor tests, assignments, quizzes, and exams.
- **Grade Calculation:** Automatically calculate grades based on assessments.
- **Progress Tracking:** Track progress after each completed task.
- **Projection Tools:** Predict future performance.
- **Intervention Features:** Support struggling students.
- **Local Data Storage:** Securely store user data.
