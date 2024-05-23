# ProductOrderApi
A sample ASP.NET Core Web API project demonstrating CRUD operations for managing products and orders using a repository pattern, Entity Framework Core for database operations, and a Singleton design pattern for logging. The project also includes Swagger for API documentation and testing.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Logging](#logging)
- [License](#license)

## Features
- CRUD operations for Products and Orders
- Repository pattern for database access
- Singleton design pattern for logging
- Entity Framework Core integration
- Swagger for API documentation

## Technologies Used
- C#
- ASP.NET Core
- Entity Framework Core
- Swagger
- Singleton Design Pattern

## Getting Started

### Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (for database)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ProductOrderApi.git
   cd ProductOrderApi

### Logging
This project uses a Singleton design pattern for logging. The Log class implements the ILog interface and logs messages to both a file and the console
