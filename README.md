# ASP.NET Core Web API Project

This is an ASP.NET Core Web API connected to a MySQL database. The API performs various CRUD operations, and Swagger is configured for easy API exploration and testing.

## Features:
- **MySQL Database Integration**: The API connects to a MySQL database.
- **Swagger UI**: Provides a visual interface to test and interact with the API endpoints.
- **CRUD Operations**: Full support for create, read, update, and delete operations.

## Prerequisites:
Before running the project, ensure you have the following installed:
- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [MySQL Server](https://dev.mysql.com/downloads/mysql/)
- [Visual Studio](https://visualstudio.microsoft.com/)
- [Git](https://git-scm.com/)

## Getting Started:

### Clone the Repository:

First, clone the repository from GitHub:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name 

###** Update `appsettings.json`**:
You need to configure your MySQL database connection string by updating the `appsettings.json` file in the root directory:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "server=localhost;database=YourDatabaseName;user=YourUsername;password=YourPassword;"
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft": "Warning",
      "Microsoft.Hosting.Lifetime": "Information"
    }
  },
  "AllowedHosts": "*"
}

## Replace the following:
  - **YourDatabaseName: with your MySQL database name.
  - **YourUsername: with your MySQL username.
  - **YourPassword: with your MySQL password.






            
