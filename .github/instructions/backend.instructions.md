---
applyTo: "backend/**"
---

# Backend Instructions

## API Design

- Follow RESTful API design principles
- Use consistent URL naming: plural nouns for resources (e.g., `/users`, `/messages`)
- Return appropriate HTTP status codes (200, 201, 400, 401, 403, 404, 500)
- Version the API where appropriate (e.g., `/api/v1/`)
- Document all endpoints with request/response examples

## Data Validation

- Validate all incoming request data before processing
- Use a schema validation library (Zod, Joi, Pydantic) for input validation
- Return descriptive validation error messages

## Database

- Use parameterized queries or an ORM to prevent SQL injection
- Handle database connection errors gracefully
- Use transactions for operations that modify multiple records atomically
- Add proper indexes for frequently queried fields

## Authentication & Authorization

- Use JWT or session-based authentication
- Validate tokens on every protected endpoint
- Implement role-based access control where needed

## Logging

- Log all incoming requests (method, path, status, duration)
- Log errors with stack traces and request context
- Use structured logging (JSON format) for production environments
- Do not log sensitive information (passwords, tokens, personal data)
