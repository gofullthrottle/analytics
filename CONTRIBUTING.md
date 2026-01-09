# Contributing

Thank you for considering contributing to this project!

## Development Setup

```bash
# Clone the repository
git clone git@github.com:gofullthrottle/analytics.git
cd analytics

# Install dependencies
# (project-specific instructions to be added)
```

## Git Workflow

This project uses a **standard tier** branching strategy:

- `master` - Production branch (protected)
- `dev` - Development branch

### Creating Features

1. Create a feature branch from `dev`:
   ```bash
   git checkout dev
   git pull origin dev
   git checkout -b feature/your-feature-name
   ```

2. Make your changes with conventional commits:
   ```bash
   git commit -m "feat: add new feature"
   git commit -m "fix: correct bug"
   ```

3. Push and create a pull request:
   ```bash
   git push -u origin feature/your-feature-name
   ```

## Commit Convention

This project uses [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation changes
- `refactor:` - Code refactoring
- `test:` - Test additions or changes
- `chore:` - Maintenance tasks

## Code Quality

### Pre-commit Hooks

Pre-commit hooks run automatically on commit:

```bash
# Manual run
pre-commit run --all-files
```

### SonarQube

Code quality is monitored via SonarQube at:
- Production: https://sonarqube.jfcreations.com/dashboard?id=analytics
- Development: https://sonarqube.jfcreations.com/dashboard?id=analytics-dev

## Pull Request Process

1. Ensure all tests pass
2. Update documentation if needed
3. Request review from maintainers
4. Merge after approval
