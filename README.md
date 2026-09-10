# ASP.NET Core Product Sale Minimal API

A practice project demonstrating how to build a **Product and Sales Management API using ASP.NET Core Minimal API**, Entity Framework Core, and SQL Server.

## 📌 Project Overview

This project demonstrates the development of a RESTful API using the **Minimal API** approach in ASP.NET Core.

Instead of traditional API Controllers, Minimal APIs allow HTTP endpoints to be defined with less boilerplate code.

The project focuses on Product and Sales Management and demonstrates database integration using Entity Framework Core.

## 🚀 Features

* ASP.NET Core Minimal API
* RESTful API
* Product Management
* Sales Management
* CRUD Operations
* Entity Framework Core
* SQL Server
* JSON Request and Response
* HTTP GET, POST, PUT and DELETE
* Swagger / OpenAPI
* Database Integration

## 🏗️ Architecture

```text
Client
   │
   │ HTTP Request
   ▼
ASP.NET Core Minimal API
   │
   ├── API Endpoints
   │
   ├── Entity Framework Core
   │
   └── Data Models
           │
           ▼
      SQL Server
           │
           ▼
     JSON Response
           │
           ▼
         Client
```

## 🛠️ Technologies Used

* C#
* ASP.NET Core
* .NET 9
* ASP.NET Core Minimal API
* Entity Framework Core
* SQL Server
* REST API
* JSON
* Swagger / OpenAPI

## 📂 Project Structure

```text
ProductSaleMinimalApi
│
├── ProductSaleMinimalApi
│   ├── Models
│   ├── Data
│   ├── Migrations
│   ├── appsettings.json
│   └── Program.cs
│
└── ProductSaleMinimalApi.sln
```

## 🔹 Minimal API

The project uses ASP.NET Core Minimal API endpoints to handle HTTP requests.

Typical endpoint structure:

```csharp
app.MapGet("/api/products", ...);
app.MapPost("/api/products", ...);
app.MapPut("/api/products/{id}", ...);
app.MapDelete("/api/products/{id}", ...);
```

This approach provides a lightweight way to create HTTP APIs with minimal code.

## 🗄️ Database

The application uses **SQL Server** as the database and **Entity Framework Core** for data access.

Configure the database connection in:

```text
appsettings.json
```

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AspNetCoreProductSaleMinimalApi.git
```

### 2. Open the Project

Open the solution in Visual Studio:

```text
ProductSaleMinimalApi.sln
```

### 3. Configure SQL Server

Update the connection string in `appsettings.json` according to your local SQL Server configuration.

### 4. Apply Database Migration

If migrations are included, run:

```bash
dotnet ef database update
```

### 5. Run the Application

```bash
dotnet run
```

### 6. Test the API

Use Swagger, Postman, or another REST API client to test the endpoints.

## 🎯 Learning Objectives

This project was created to practice:

* ASP.NET Core Minimal API
* RESTful API development
* HTTP methods
* CRUD operations
* Entity Framework Core
* SQL Server integration
* Database migrations
* API endpoint mapping
* JSON data exchange
* Swagger API testing
* Minimal API vs Controller-based API concepts

## 🔄 HTTP Methods

| Method | Purpose              |
| ------ | -------------------- |
| GET    | Retrieve data        |
| POST   | Create new data      |
| PUT    | Update existing data |
| DELETE | Delete data          |


