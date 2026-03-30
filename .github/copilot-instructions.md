# GitHub Copilot Instructions

This repository is a common template for projects with a frontend and backend structure.

## Project Structure

- `frontend/` - Frontend application
- `backend/` - Backend application
- `.github/workflows/` - CI/CD pipeline definitions
- `.github/templates/` - Configuration templates
- `.github/instructions/` - Additional Copilot instructions

## General Guidelines

- Follow the existing code style and conventions in each folder
- Write clear, concise commit messages
- Ensure all new code is covered by tests
- Use environment variables for secrets and configuration; never hardcode credentials
- Follow the principle of least privilege for permissions

## Frontend

- Use modern JavaScript/TypeScript best practices
- Keep components small and focused
- Write unit tests for utility functions and components

## Backend

- Follow RESTful API design principles
- Validate all input data
- Handle errors gracefully and return meaningful error messages
- Document API endpoints

## CI/CD

- All pull requests must pass CI checks before merging
- Docker images are built and pushed to the container registry on merge to `main`
- Use the provided workflow templates as a starting point
