# SEDO Retake Exam 2 - Homies Application

This is a .NET application for managing events and participants.

## Features

- Event management
- Participant registration
- User authentication
- Responsive web interface

## Technology Stack

- .NET 6
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- Bootstrap

## Getting Started

1. Clone the repository
2. Restore dependencies: `dotnet restore`
3. Build the solution: `dotnet build`
4. Run tests: `dotnet test`
5. Run the application: `dotnet run`

## CI/CD

This project includes GitHub Actions workflow for continuous integration:
- Runs on push to `develop` and `feature` branches
- Restores dependencies
- Builds the project
- Runs unit and integration tests

## Project Structure

- `Homies/` - Main application
- `Homies.Data/` - Data layer
- `Homies.Tests/` - Unit tests
- `Homies.IntegrationTests/` - Integration tests
