# Swift Shipping System - README

## Introduction

The Swift Shipping System is a comprehensive solution designed to streamline the management of shipping operations. It aims to facilitate efficient order processing, delivery management, and user administration through a robust and scalable architecture.

## Table of Contents

1. [Project Objective](#project-objective)
2. [Features](#features)
3. [Architecture](#architecture)
4. [Technology Stack](#technology-stack)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Future Work](#future-work)
8. [Contributors](#contributors)

## Project Objective

The objective of the Swift Shipping System is to enhance the efficiency and accuracy of shipping operations. This system supports various user roles, such as administrators, sellers, and delivery personnel, and provides tools for managing orders, regions, branches, and settings.

## Features

### User Management
- **Admin**: Manage system settings and user roles.
- **Sellers**: Manage store information and customer orders.
- **Delivery Personnel**: Track and update delivery status.
- **Customers**: Place and track orders.

### Order Management
- **Order Creation**: Sellers can create and manage new orders.
- **Order Tracking**: Delivery personnel can update order status in real-time.
- **Reporting**: Generate detailed reports on order statuses and delivery times.

### Regional Management
- **Regions**: Define and manage different delivery regions.
- **Branches**: Manage branches within each region.

### Settings Management
- **Weight Settings**: Configure shipping weight-related settings.
- **Role Permissions**: Define and manage user role permissions.

### Security Features
- **Authentication**: Secure login with role-based access control.
- **Data Encryption**: Protect sensitive user information.

## Architecture

The Swift Shipping System follows an N-Tier Architecture to separate concerns and ensure scalability and maintainability. The architecture is divided into the following layers:

### Presentation Layer
- **Technologies**: Angular Framework
- **Responsibilities**: Handles the user interface and user interactions.

### Business Logic Layer
- **Technologies**: ASP.NET Core Web API
- **Responsibilities**: Processes business rules and logic, handles validation and authorization.

### Data Access Layer
- **Technologies**: Entity Framework
- **Responsibilities**: Manages data retrieval and storage, communicates with the database.

### Database Layer
- **Technologies**: MSSQL Server
- **Responsibilities**: Stores and manages data persistently.

## Technology Stack

- **Backend**: ASP.NET Core Web API, AutoMapper, MS Identity, JWT (JSON Web Token)
- **Frontend**: Angular Framework
- **Database**: MSSQL Server

## Installation

### Prerequisites
- Node.js
- Angular CLI
- .NET Core SDK
- MSSQL Server

### Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-repository-url.git
    ```

2. **Backend Setup**
    - Navigate to the backend directory:
      ```bash
      cd backend
      ```
    - Restore packages and build the project:
      ```bash
      dotnet restore
      dotnet build
      ```
    - Run the project:
      ```bash
      dotnet run
      ```

3. **Frontend Setup**
    - Navigate to the frontend directory:
      ```bash
      cd frontend
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Start the Angular development server:
      ```bash
      ng serve
      ```

## Usage

### Running the Application
- **Backend**: Ensure the backend server is running on the designated port.
- **Frontend**: Access the frontend application through the Angular development server URL (typically `http://localhost:4200`).

### Accessing the Application
- **Admin Dashboard**: Manage users, roles, and system settings.
- **Seller Dashboard**: Create and manage orders.
- **Delivery Dashboard**: Track and update delivery statuses.
- **Customer Interface**: Place and track orders.

## Future Work

- **Mobile Application**: Develop a mobile app for order management on-the-go.
- **Real-Time Tracking**: Implement real-time delivery tracking.
- **Payment Gateway Integration**: Integrate with popular payment gateways.
- **Enhanced Reporting**: Add more detailed and customizable reporting features.

## Contributors

- **Mostafa Ali**
- **Ahmed Mohamed**
- **Fatma Sorour**
- **Aya Nassar**
- **Ola Nazmy**
