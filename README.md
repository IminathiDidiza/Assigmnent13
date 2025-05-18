# Student Attendance System

A comprehensive student attendance management system with CI/CD pipeline implementation.

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

### Prerequisites
- Java 17 or higher
- Maven 3.8 or higher
- Git

### Running Tests Locally

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

## Branch Protection Rules

The main branch is protected with the following rules:
- Requires pull request reviews (minimum 1 reviewer)
- Requires status checks to pass
- Prevents direct pushes to main

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Write/update tests
4. Create a pull request
5. Wait for review and approval

## License

MIT License 