# Project Name: Clean Architecture .NET Core Web API

## Overview
This project is a robust .NET Core Web API designed with Clean Architecture principles. It employs industry best practices, including the repository pattern, Entity Framework Core migrations, services interfaces and classes, AutoMapper for object mapping, and comprehensive API features such as sorting, paging, exception handling, CORS support, and Swagger documentation. Furthermore, this API has been thoroughly tested using Postman to ensure reliability and functionality.

## Project Features
- **Clean Architecture**: The project follows the Clean Architecture pattern, which promotes separation of concerns and maintainability.

- **Entity Framework Core Migrations**: Entity Framework Core migrations are used to manage the database schema, ensuring easy database schema updates.

- **Services Interfaces and Classes**: The application is built with a clear separation of responsibilities, making use of services interfaces and classes to facilitate modularity and dependency injection.

- **AutoMapper**: AutoMapper simplifies the process of mapping between DTOs (Data Transfer Objects) and domain models, reducing code duplication.

- **Sorting and Paging**: The API provides robust sorting capabilities, allowing users to sort results based on various criteria, such as `ProductBrandType`, `ProductType`, and more. Additionally, it supports paging with options for `Skip`, `Take`, and enabling/disabling paging using `IsPagingEnabled`.

- **Exception Handling**: The project incorporates a comprehensive exception handling mechanism to return informative error responses to clients.

- **CORS (Cross-Origin Resource Sharing)**: CORS has been configured to control which domains can access the API, enhancing security and accessibility.

- **Swagger Documentation**: Swagger has been seamlessly integrated into the project, auto-generating API documentation. This simplifies API exploration and testing.

- **Postman Testing**: The API has been rigorously tested using Postman, covering various endpoints and scenarios to ensure its functionality and reliability.

## Getting Started
To begin using this project, follow these steps:

1. Clone the repository to your local machine.
2. Configure the database connection in the app settings.
3. Execute Entity Framework Core migrations to create and update the database schema.
4. Build and run the application.

## API Endpoints
- **GET /api/products**: Retrieve a list of products, with support for sorting and paging.
- **GET /api/products/{id}**: Fetch details for a specific product by ID.
- **POST /api/products**: Create a new product.
- **PUT /api/products/{id}**: Update an existing product by ID.
- **DELETE /api/products/{id}**: Remove a product by ID.

## Configuration
Customize the project's configuration in the `appsettings.json` file. Here, you can set the database connection string, configure CORS policies, and define other essential settings.

## Dependencies
This project relies on the following technologies and libraries:
- .NET Core
- Entity Framework Core
- AutoMapper
- Swagger
- CORS
- Postman (for testing)

