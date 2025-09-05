# Management-System-API

A RESTful Web API for managing healthcare resources (patients, appointments, staff, etc.), built with ASP.NET Core.

## Features
- CRUD endpoints for core entities
- In-memory database for easy testing
- Interactive Swagger UI documentation

## Quick Start

```sh
dotnet restore
dotnet run --project API
```

Visit [https://localhost:5001/swagger](https://localhost:5001/swagger) for Swagger UI.

## Folder Structure

- `API/` — ASP.NET Core Web API project
  - `Controllers/` — C# API controllers
  - `Program.cs` — Main entry point

## License

MIT
