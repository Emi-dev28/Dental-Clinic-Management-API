# Dental Clinic Management System with NestJS

## Description

This project demonstrates my proficiency in developing backend applications using NestJS. It's a management system for a dental clinic, designed to showcase my capabilities in creating robust and scalable APIs.

## Key Features

- Modular architecture following Clean Architecture principles
- Implementation of design patterns such as Repository and Dependency Injection
- Use of TypeORM for database management
- End-to-end (e2e) tests to ensure code quality
- API documentation with Swagger
- DTO handling for data validation
- Implementation of entity relationships (OneToOne, OneToMany)

## Technologies Used

- NestJS
- TypeScript
- TypeORM
- MySQL
- Jest for testing
- Swagger for API documentation

## Project Structure

The project follows a modular structure, implementing hexagonal architecture (also known as ports and adapters). Each module (such as patients, dentists, appointments) implements its own domain, application, and infrastructure layers. This demonstrates my understanding and application of Hexagonal Architecture principles, which is a variant of Clean Architecture, focusing on separation of concerns and independence of business rules. The structure ensures that the core business logic remains isolated from external dependencies, promoting maintainability and testability.

## How to Run the Project

1. Clone the repository
2. Install dependencies with `npm install`
3. Configure environment variables in a `.env` file
4. Run the project in development mode with `npm run start:dev`
