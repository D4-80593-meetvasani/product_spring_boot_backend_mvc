# Product Spring Boot Backend (MVC)

## Overview

This Spring Boot project, serves as a robust backend for managing product data. It follows the Model-View-Controller (MVC) architecture and utilizes a JPA repository for efficient data persistence.

## Features

- **Controller:** The `ProductController` class manages HTTP requests, providing endpoints for CRUD operations such as adding products, retrieving details by ID or category, updating information, and deleting products.

- **Service:** The `ProductServiceImpl` class implements business logic, orchestrating interactions between the controller and the data access layer. It leverages the `ProductDao` interface, extending the JPA `CrudRepository` for streamlined database operations.

- **Entities:** The project defines a `Product` entity encapsulating product details and a `Category` enum for efficient categorization. Common properties like ID are abstracted into a `BaseEntity` class.

- **Data Access:** Spring Data JPA and Hibernate facilitate data access. The `ProductDao` interface extends `CrudRepository`, providing standard CRUD operations for the `Product` entity.

- **Testing with Swagger UI:** The project includes Swagger UI, enabling interactive API testing. Screenshots within the repository demonstrate how to use each endpoint, enhancing the testing experience.

## Technical Details

- **Technology Stack:**
  - Spring Boot
  - Spring Data JPA
  - Hibernate
  - Swagger UI for API testing

## Getting Started

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd product_spring_boot_backend_mvc`
3. Build and run the application: `./mvnw spring-boot:run`

## Testing with Swagger UI

Visit `http://localhost:8080/swagger-ui.html` after starting the application to access the Swagger UI. Explore and test the API endpoints interactively.

## Conclusion

This project provides a scalable and efficient backend solution for managing product data. Feel free to explore and integrate it with your frontend application.

## Swagger Screenshots

![Swagger 1](./Swagger (1).png)
![Swagger 2](./Swagger (2).png)
![Swagger 3](./Swagger (3).png)
![Swagger 4](./Swagger (4).png)


---

