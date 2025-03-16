# Mega Man Robots API

<p align="center">
  <img src="./_docs/assets/icon.png" alt="Mega Man Robots API" width="150" />
</p>

<p align="center">
  <strong>MEGA-MAN-ROBOTS</strong>
</p>

<p align="center">
  <a href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml">
    <img src="https://github.com/felipeAguiarCode/MegaApiDotnetCore/actions/workflows/build.yml/badge.svg" alt="Build Status" />
  </a>
  <a href="https://github.com/felipeAguiarCode/MegaApiDotnetCore/releases/latest">
    <img src="https://img.shields.io/github/v/release/felipeAguiarCode/MegaApiDotnetCore" alt="Latest Release" />
  </a>
</p>

## 📖 About

Mega Man Robots API is a .NET Core 3.1 backend service that provides JSON-formatted data about the bosses from the Mega Man series. Built with Entity Framework Core and modern .NET technologies, this API aims to deliver a robust system for accessing Mega Man robot data.

<p align="center">
  <img src="./_docs/assets/carbon.png" alt="Code Preview" />
</p>

## 🚀 API Endpoints

| Method | Endpoint            | Description                           |
|--------|--------------------|-----------------------------------|
| GET    | `/api/v1/robots`   | Returns a list of all robots     |
| GET    | `/api/v1/robots/{id}` | Returns details of a specific robot by ID |
| POST   | `/api/v1/robots`   | Creates a new robot entry       |

## 🛠️ Technologies Used

- **Entity Framework Core**: ORM for data management.
- **RESTful API Design**: Ensures clear and effective communication.
- **Dependency Injection**: Promotes loose coupling and enhanced testability.

## 📦 Dependencies

| Package | Version | Link |
|---------|---------|------|
| `Microsoft.EntityFrameworkCore` | 3.1.8 | [NuGet](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8) |
| `Microsoft.EntityFrameworkCore.Design` | 3.1.8 | [NuGet](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8) |
| `Microsoft.EntityFrameworkCore.SqlServer` | 3.1.8 | [NuGet](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8) |
| `Newtonsoft.Json` | 12.0.2 | [NuGet](https://www.nuget.org/packages/Newtonsoft.Json/12.0.2) |

## 🏗️ Project Structure

```
📂 src
├── 📂 Controllers      # Routes for endpoints
├── 📂 Models           # Database models
├── 📂 Services         # Business rules
├── 📂 Middlewares      # Middleware logic
├── 📂 Database         # Database-related structures
│   ├── 📂 DTOs             # Data Transfer Objects
│   ├── 📂 EntityFramework  # ORM Entity Framework files
│   │     ├── 📂 Context     # Entity context settings
│   │     ├── 📂 Migrations  # Database migrations
│   ├── 📂 Repositories     # Repository pattern
```

## 📜 License

This software is licensed under the terms of the [MIT License](LICENSE).

---

Developed by [Felipe Aguiar](https://github.com/felipeAguiarCode) 🚀
