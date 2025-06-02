# IdentityService API

A minimal ASP.NET Web API for handling user authentication using JWT (JSON Web Token). This project includes basic login and registration functionality via ASP.NET Core Identity, along with two custom `POST` endpoints defined directly in the `Program.cs` file.

## Features

- User registration and login using ASP.NET Identity
- JWT-based authentication
- Minimal API structure using ASP.NET Core 8+
- Two additional custom endpoints in `Program.cs`

## Technologies Used

- ASP.NET Core 8
- ASP.NET Identity
- JWT Bearer Authentication
- Entity Framework Core
- SQLite / SQL Server (or your preferred DB)

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- Visual Studio or VS Code
- Optional: Docker (if containerizing)

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/IdentityService.git
   cd IdentityService

2. **Restore dependencies and run migrations:**
   ```
   dotnet restore
   dotnet ef database update

3. **Run the API:**
   ```
   dotnet run
   he API should be running on https://localhost:5001 or a similar port.![authECAPI](https://github.com/user-attachments/assets/65f937d5-1fa9-4b52-8460-a0efe26b5ac3)

   
