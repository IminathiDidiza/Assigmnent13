# Student Attendance System

A comprehensive student attendance management system with CI/CD pipeline implementation.

## Features

- Student attendance tracking
- RESTful API endpoints
- Database integration
- CI/CD pipeline
- Basic authentication
- Email notifications
- Attendance statistics
- Bulk import/export

## Getting Started

### Prerequisites
- Java 17 or higher
- Maven 3.8 or higher
- Git
- IDE (IntelliJ IDEA, Eclipse, or VS Code recommended)
- Docker (optional)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-attendance-system.git
   ```

2. Navigate to project directory:
   ```bash
   cd student-attendance-system
   ```

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

## Features for Contribution

| Feature | Difficulty | Status | Description |
|---------|------------|--------|-------------|
| Email Notifications | Easy | Open | Send email alerts for absent students |
| Statistics Dashboard | Medium | Open | Create visual attendance analytics |
| Bulk Import/Export | Easy | Open | Add CSV import/export functionality |
| Role-based Access | Medium | Open | Implement user role management |
| QR Code Check-in | Medium | Open | Add QR code-based attendance |
| Mobile Interface | Hard | Open | Create responsive web design |
| Real-time Tracking | Hard | Open | Implement WebSocket for live updates |
| API Documentation | Easy | Open | Create OpenAPI/Swagger docs |

## Project Structure

```
.
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── attendance/
│   │   │           ├── model/
│   │   │           ├── repository/
│   │   │           ├── service/
│   │   │           └── controller/
│   │   └── resources/
│   └── test/
│       └── java/
│           └── com/
│               └── attendance/
├── .github/
│   └── workflows/
│       └── ci.yml
├── pom.xml
└── README.md
```

## Local Development

### Running Tests

```bash
# Run all tests
mvn test

# Run specific test class
mvn test -Dtest=TestClassName

# Run with coverage
mvn verify
```

## CI/CD Pipeline

Our project uses GitHub Actions for continuous integration and deployment. The pipeline:

1. Runs on every push and pull request
2. Executes all unit and integration tests
3. Generates a JAR artifact when merged to main
4. Enforces code quality through branch protection rules

### Pipeline Stages

1. **Build**: Compiles the code and runs tests
2. **Test**: Executes unit and integration tests
3. **Package**: Creates a JAR file
4. **Deploy**: Uploads the artifact to GitHub releases

## Contributing

We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Roadmap

Check out our [ROADMAP.md](ROADMAP.md) for planned features and improvements.

## Branch Protection Rules

The main branch is protected with the following rules:
- Requires pull request reviews (minimum 1 reviewer)
- Requires status checks to pass
- Prevents direct pushes to main

## Contributing Process

1. Create a new branch for your feature
2. Make your changes
3. Write/update tests
4. Create a pull request
5. Wait for review and approval

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Spring Boot team for the amazing framework
- All contributors who have helped shape this project
- The open-source community for inspiration and support 