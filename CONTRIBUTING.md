# Contributing to Flam Assignment

## Welcome!

Thank you for your interest in contributing to this project. This document provides guidelines for contributing.

## Development Setup

### Prerequisites
- Android Studio (latest version)
- Android NDK
- Node.js 14+
- Git

### Getting Started

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/flam-assignment.git
   ```
3. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Code Style

### Kotlin
- Follow official Kotlin coding conventions
- Use meaningful variable names
- Add KDoc comments for public APIs

### C++
- Follow Google C++ Style Guide
- Use smart pointers where appropriate
- Document complex algorithms

### TypeScript
- Strict mode enabled
- Use interfaces for type definitions
- Document public methods with JSDoc

## Commit Messages

Follow conventional commits format:

```
type(scope): subject

body

footer
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation only
- `style`: Code style changes
- `refactor`: Code refactoring
- `test`: Adding tests
- `chore`: Maintenance tasks

## Pull Request Process

1. Update documentation for any changes
2. Add tests if applicable
3. Ensure all tests pass
4. Update README if needed
5. Request review from maintainers

## Testing

### Android
```bash
./gradlew test
./gradlew connectedAndroidTest
```

### Web
```bash
cd web
npm test
```

## Questions?

Feel free to open an issue for any questions or concerns.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
