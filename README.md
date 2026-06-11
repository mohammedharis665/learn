# CI/CD Demo Project

A comprehensive example of continuous integration and continuous deployment using:
- **GitHub Actions** for automated testing on push and schedule
- **Jenkins** for advanced pipeline orchestration and scheduling

## Project Structure
- `.github/workflows/` - GitHub Actions workflows
- `Jenkinsfile` - Jenkins Declarative Pipeline
- `src/` - Source code
- `tests/` - Test files

## Scheduled Builds
- Daily build at 2:00 AM UTC
- Weekly comprehensive tests on Mondays
- Every 6 hours automated check

## Quick Start
1. Clone the repository
2. Install dependencies
3. Run tests
4. Deploy to staging/production
