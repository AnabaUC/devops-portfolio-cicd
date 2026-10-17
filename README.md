# DevOps Portfolio CI/CD

A beginner-friendly DevOps portfolio project demonstrating Git,
GitHub Actions, automated testing, continuous integration,
continuous deployment, and GitHub Pages.

## Architecture

Developer
↓
GitHub
↓
Pull Request
↓
GitHub Actions
↓
Automated Tests
↓
Build
↓
GitHub Pages
↓
Live Website

## Technologies

- Git
- GitHub
- GitHub Actions
- Node.js
- Jest
- GitHub Pages
- HTML
- CSS
- JavaScript

## CI Pipeline

The CI pipeline automatically:

1. Checks out the code
2. Sets up Node.js
3. Installs dependencies
4. Runs automated tests
5. Builds the application
6. Verifies the build

## CD Pipeline

When changes are merged into `main`, the deployment workflow:

1. Checks out the code
2. Installs dependencies
3. Runs tests
4. Builds the application
5. Uploads the build artifact
6. Deploys the website

## Security

Sensitive values are stored using GitHub Actions Secrets
rather than being committed to the repository.

## Project Status

In active development as part of my DevOps learning portfolio.