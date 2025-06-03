# AuthECAPI (Flat Program.cs Version)

A minimal ASP.NET Web API for user authentication using JWT, where all service registrations, middleware configurations, and application logic are written directly in `Program.cs`. This version avoids using extension methods or extra abstraction layers for maximum transparency and simplicity.

## 🔐 Features

- ASP.NET Core Identity for user management
- JWT (JSON Web Token) for authentication
- All logic in a single `Program.cs` file
- Minimal API endpoints for login and registration
- Entity Framework Core for data persistence

## 🧰 Technologies Used

- ASP.NET Core 8
- ASP.NET Identity
- Entity Framework Core
- JWT Bearer Authentication
- SQLite / SQL Server (or your choice of DB)

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- Visual Studio or VS Code

### Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/AuthECAPI.git
   cd AuthECAPI

2. **Restore dependencies and run migrations:**
   ```
   dotnet restore
   dotnet ef database update

3. **Run the API:**
   ```
   dotnet run
   he API should be running on https://localhost:5001 or a similar port.![authECAPI](https://github.com/user-attachments/assets/65f937d5-1fa9-4b52-8460-a0efe26b5ac3)
   
![authECAPI](https://github.com/user-attachments/assets/2ba2ad0c-4f1d-48ce-948d-1b6f1131d9a1)
