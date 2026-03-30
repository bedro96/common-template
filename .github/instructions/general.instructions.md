---
applyTo: "**"
---

# General Instructions

## Code Style

- Use consistent indentation (2 spaces for JS/TS, 4 spaces for Python)
- Use single quotes for strings in JavaScript/TypeScript
- Use double quotes for strings in Python
- Add trailing commas in multi-line objects and arrays (JS/TS)
- Keep line length under 120 characters

## Naming Conventions

- Use `camelCase` for JavaScript/TypeScript variables and functions
- Use `PascalCase` for classes and React components
- Use `UPPER_SNAKE_CASE` for constants and environment variable names
- Use `snake_case` for Python variables and functions
- Use descriptive names that clearly communicate intent

## Comments

- Write self-documenting code; add comments only when necessary to explain complex logic
- Keep comments up to date when code changes
- Use JSDoc/TSDoc for public APIs and functions in JavaScript/TypeScript
- Use Google-style docstrings for Python functions

## Error Handling

- Always handle errors explicitly; never silently swallow exceptions
- Return meaningful error messages to callers
- Log errors with sufficient context for debugging

## Security

- Never commit secrets, API keys, or passwords to source control
- Use environment variables for all configuration values
- Validate and sanitize all user input
- Follow the principle of least privilege
