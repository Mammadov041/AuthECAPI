# AuthEC API Updated

A clean and minimal ASP.NET Web API for handling user authentication using JWT (JSON Web Token). This project uses ASP.NET Core Identity for user management and follows modern best practices including separation of concerns, extension methods for setup, and `IOptions<T>` for configuration.

## ✨ Features

- User registration and login via ASP.NET Core Identity
- JWT-based authentication
- Clean architecture with zero logic in `Program.cs`
- All setup logic moved to `IServiceCollection` and `WebApplication` extension methods
- Application settings managed via strongly-typed `IOptions<T>` injection
- Minimal API structure using ASP.NET Core 8+

## 🛠️ Technologies

- ASP.NET Core 8
- ASP.NET Core Identity
- JWT Bearer Authentication
- Entity Framework Core
- SQLite / SQL Server (or your preferred DB)
- Dependency Injection with `IOptions<T>`
- Clean architecture principles

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- Visual Studio 2022+ or VS Code
- Optional: Docker (for containerized deployment)

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/AuthECAPIUpdated.git
   cd AuthECAPIUpdated

2. **Restore dependencies and run migrations:**
   ```
   dotnet restore
   dotnet ef database update

3. **Run the API:**
   ```
   dotnet run
   he API should be running on https://localhost:5001 or a similar port.![authECAPI](https://github.com/user-attachments/assets/65f937d5-1fa9-4b52-8460-a0efe26b5ac3)
   
![authECAPI](https://github.com/user-attachments/assets/2ba2ad0c-4f1d-48ce-948d-1b6f1131d9a1)
