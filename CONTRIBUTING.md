# Contributing to Student Attendance System


## Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Coding Standards](#coding-standards)
- [Testing](#testing)
- [Pull Request Process](#pull-request-process)

## Prerequisites

- Java 17 or higher
- Maven 3.8 or higher
- Git
- IDE (IntelliJ IDEA, Eclipse, or VS Code recommended)
- Docker (optional, for containerized development)

## Getting Started

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/student-attendance-system.git
   ```
3. Add upstream remote:
   ```bash
   git remote add upstream https://github.com/ORIGINAL-OWNER/student-attendance-system.git
   ```
4. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Development Workflow

1. Keep your fork up to date:
   ```bash
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```

2. Create a new branch for each feature/fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit:
   ```bash
   git add .
   git commit -m "feat: add new feature"
   ```

4. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

## Coding Standards

- Follow Java Code Conventions
- Use meaningful variable and method names
- Write comments for complex logic
- Keep methods small and focused
- Use proper indentation (4 spaces)
- Maximum line length: 120 characters

## Testing

1. Write unit tests for new features
2. Ensure all tests pass:
   ```bash
   mvn test
   ```
3. Maintain or improve code coverage
4. Include integration tests for API endpoints

## Pull Request Process

1. Update the README.md with details of changes if needed
2. Update the documentation if you're changing functionality
3. The PR will be merged once you have:
   - At least one approval
   - All CI checks passing
   - No merge conflicts

## Issue Labels

- `good-first-issue`: Perfect for first-time contributors
- `bug`: Something isn't working
- `enhancement`: New feature or improvement
- `documentation`: Documentation improvements
- `help-wanted`: Extra attention needed

## Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

## License

By contributing, you agree that your contributions will be licensed under the project's MIT License. 