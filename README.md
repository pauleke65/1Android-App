
# Glovo: Food Delivery and More

Server code for Glovo, a food delivery and logistics app

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Milestones](#milestones)
- [Application Modules](#application-modules)
- [Middlewares](#middlewares)
- [Database Models](#database-models)
- [External Services](#external-services)
- [Utilities and Helpers](#utilities-and-helpers)
- [Architecture](#architecture)
- [Documentation](#documentation)
- [API Documentation](#api-documentation)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

Provide instructions on how to set up and run your Node.js project. Include details about prerequisites and installation.

### Prerequisites

List any software, tools, or dependencies that need to be installed before running the project.

### Installation

A step-by-step guide on how to install and set up your project. You can use code blocks for commands.

```bash
npm install
```

## Usage

Explain how to use your project, including code examples and demonstrations.

## Milestones


### Milestone 1: Authentication Module
Develop the authentication module to handle user authentication and authorization

Tasks:

- Task 1: Implement user registration functionality
Create the logic for user registration including validating input data and saving user details to the database

- Task 2: Implement user login functionality
Create the logic for user login including validating credentials, generating JWT tokens, and returning them to the user

- Task 3: Implement authorization middleware
Create middleware to verify JWT tokens and restrict access to authenticated users

### Milestone 2: Order Management Module
Develop the order management module to process and track orders

Tasks:

- Task 4: Implement order creation functionality
Create the logic for creating new orders including validating the order details, assigning a delivery driver, and saving the order to the database

- Task 5: Implement order tracking functionality
Create the logic for tracking the status of orders including updating the order status and notifying users of order updates

### Milestone 3: User Management Module
Develop the user management module to handle user profile updates and other user-related operations

Tasks:

- Task 6: Implement user profile update functionality
Create the logic for updating user profiles including validating the updated data and saving the changes to the database

- Task 7: Implement password reset functionality
Create the logic for resetting user passwords including verifying the user's identity and updating the password in the database

### Milestone 4: Middleware and Routing Module
Create middlewares and define API endpoints for error handling, request validation, and routing

Tasks:

- Task 8: Implement error handling middleware
Create middleware to handle error responses and log error messages

- Task 9: Implement request validation middleware
Create middleware to validate incoming request data based on predefined rules

- Task 10: Define API endpoints and route handlers
Create the router module to define API endpoints and map them to appropriate route handlers

### Milestone 5: Database Models Module
Develop database models for user, order, and address entities

Tasks:

- Task 11: Create user model
Define the database model for the user entity including the necessary fields and relationships

- Task 12: Create order model
Define the database model for the order entity including the necessary fields and relationships

- Task 13: Create address model
Define the database model for the address entity including the necessary fields and relationships

### Milestone 6: External Services Integration Module
Integrate external services such as payment gateway, geocoding service, and push notification service

Tasks:

- Task 14: Integrate payment gateway
Implement the integration with the payment gateway to process payments for orders

- Task 15: Integrate geocoding service
Implement the integration with the geocoding service to lookup addresses and convert them to coordinates

- Task 16: Integrate push notification service
Implement the integration with the push notification service to send notifications to users

### Milestone 7: Utilities and Helpers Module
Develop utility functions and helpers for image processing, email service, and JWT token handling

Tasks:

- Task 17: Implement image processing utility functions
Create utility functions for image processing including resizing, cropping, and compressing images

- Task 18: Implement email service utility
Create a utility for sending emails to users including functionalities like composing, sending, and tracking emails

- Task 19: Implement JWT token utility functions
Create utility functions for handling JWT tokens including generating, verifying, and decoding tokens


## Application Modules

Modules handling core application functionalities


### Authentication
Handles user authentication and authorization

### OrderManagement
Manages the processing and tracking of orders

### UserManagement
Handles user registration, profile updates, and other user-related operations

## Middlewares

Middleware components are used for processing requests, error handling, and input validation. Routing modules define API endpoints and route handlers.


### ErrorHandling
Handles error responses and logging

### RequestValidation
Validates incoming request data

### Router
Defines API endpoints and route handlers

## Database Models

This group includes database models representing the various entities in the app. It also covers database queries for data retrieval and manipulation.


### User
Database model representing user entity

### Order
Database model representing order entity

### Address
Database model representing address entity

## External Services

Modules for integrating external services such as payment gateways, geocoding services, push notification services, etc.


### PaymentGateway
Integration with payment gateway for processing payments

### GeocodingService
Integration with geocoding service for address lookup

### PushNotificationService
Integration with push notification service for sending notifications to users

## Utilities and Helpers

Modules containing utility functions and third-party libraries used for specific functionality.


### ImageProcessing
Utility functions for image processing

### EmailService
Utility for sending emails to users

### JwtUtils
Utility functions for JWT token handling

## Architecture

This module group is responsible for creating and maintaining documentation for the application's API, making it easier for developers to understand how to use the API endpoints.

```mermaid

```



## API Documentation

If your project includes an API, provide a link to the API documentation or explain how to access it.

## Configuration

Explain how to configure your project, including any environment variables or configuration files.

## Contributing

Provide guidelines for contributors, including how to report issues, submit pull requests, and code formatting conventions.

## License

This project is licensed under the [License Name](LICENSE) - see the [LICENSE](LICENSE) file for details.
