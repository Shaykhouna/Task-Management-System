# Task Management System with Analytics

A full-stack application for task management with analytics dashboards.
This project showcases both frontend and backend skills while being practical enough to complete as a junior developer.

## Features

- User registration and authentication with JWT
- Task creation, management, and categorization
- Analytics dashboard with performance metrics
- Mobile-responsive design
- RESTful API with Spring Boot

## Tech Stack

- **Frontend**: Angular with Angular Material
- **Backend**: Java Spring Boot
- **Database**: PostgreSQL
- **Authentication**: JWT
- **CI/CD**: GitHub Actions
- **Deployment**: Render

## DevSecOps Practices

- Automated CI/CD pipeline
- Code quality checks with SonarQube
- SAST with CodeQL
- Dependency vulnerability scanning
- Automated testing with coverage reporting
- Containerization with Docker

## Getting Started

### Prerequisites

- Java 17+
- Node.js 18+
- PostgreSQL
- Docker (optional)

### Backend Setup

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

## Development Workflow

1. Create a feature branch from `develop`
2. Implement changes with tests
3. Create a pull request to `develop`
4. After PR is approved and merged, changes will be automatically deployed to the staging environment
5. Releases are created by merging `develop` to `main`

## Security Features

- JWT authentication with proper token management
- Password encryption
- Role-based access control
- Input validation and sanitization
- HTTPS enforcement
- CORS configuration
- Content Security Policy

## License

This project is licensed under the MIT License - see the LICENSE file for details.
