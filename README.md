# SEDO Retake Exam 2 - Homies Application

This is a comprehensive .NET application for managing events and participants, built with modern web technologies and DevOps practices.

## 🚀 Features

- **Event Management**: Create, edit, and manage events
- **Participant Registration**: Users can join and leave events
- **User Authentication**: Secure user registration and login
- **Responsive Web Interface**: Modern, mobile-friendly design
- **Real-time Updates**: Dynamic content updates
- **Search & Filter**: Find events by type and criteria

## 🛠️ Technology Stack

- **Backend**: .NET 6, ASP.NET Core MVC
- **Database**: Entity Framework Core with SQL Server
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Testing**: xUnit for unit tests, integration tests
- **DevOps**: GitHub Actions for CI/CD

## 📋 Prerequisites

- .NET 6 SDK
- SQL Server (LocalDB or full instance)
- Visual Studio 2022 or VS Code
- Git

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Momchil-Ivanov/SEDO-Retake-Exam-2.git
   cd SEDO-Retake-Exam-2
   ```

2. **Restore dependencies**
   ```bash
   dotnet restore
   ```

3. **Build the solution**
   ```bash
   dotnet build
   ```

4. **Run tests**
   ```bash
   dotnet test
   ```

5. **Run the application**
   ```bash
   dotnet run --project Homies
   ```

6. **Open your browser** and navigate to `https://localhost:5001`

## 🔄 CI/CD Pipeline

This project includes a robust GitHub Actions workflow for continuous integration:

- **Triggers**: Runs on push to `develop` and `feature/*` branches
- **Environment**: Ubuntu latest with .NET 6
- **Steps**:
  - ✅ Checkout repository
  - ✅ Setup .NET 6 environment
  - ✅ Restore NuGet packages
  - ✅ Build entire solution
  - ✅ Run unit and integration tests
  - ✅ Generate test reports

## 📁 Project Structure

```
SEDO-Retake-Exam-2/
├── .github/workflows/     # GitHub Actions CI/CD
├── Homies/               # Main ASP.NET Core application
├── Homies.Data/          # Data layer with Entity Framework
├── Homies.Tests/         # Unit tests (xUnit)
├── Homies.IntegrationTests/ # Integration tests
└── Homies.sln           # Solution file
```

## 🧪 Testing

The project includes comprehensive testing:

- **Unit Tests**: Test individual components and business logic
- **Integration Tests**: Test database interactions and API endpoints
- **Test Coverage**: Aiming for high code coverage

Run tests locally:
```bash
dotnet test --verbosity normal
```

## 📝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is part of the SEDO (Software Engineering and DevOps) retake exam.

## 👥 Authors

- **Momchil Ivanov** - Initial work and DevOps implementation

---

**Note**: This application demonstrates modern DevOps practices including CI/CD pipelines, automated testing, and proper project structure.
