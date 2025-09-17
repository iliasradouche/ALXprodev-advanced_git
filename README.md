# ALXprodev Advanced Git

This repository demonstrates the implementation of GitFlow workflow for advanced Git practices.

## GitFlow Setup

This project uses GitFlow branching model with the following configuration:

- **Production branch**: `main` - Contains production-ready code
- **Development branch**: `develop` - Integration branch for ongoing development
- **Feature branches**: `feature/*` - New features in development
- **Release branches**: `release/*` - Preparation for production releases
- **Hotfix branches**: `hotfix/*` - Critical bug fixes for production
- **Bugfix branches**: `bugfix/*` - Bug fixes during development
- **Support branches**: `support/*` - Support and maintenance

## Common GitFlow Commands

```bash
# Initialize GitFlow (already done)
git flow init -d

# Start a new feature
git flow feature start <feature-name>

# Finish a feature
git flow feature finish <feature-name>

# Start a release
git flow release start <version>

# Finish a release
git flow release finish <version>

# Start a hotfix
git flow hotfix start <version>

# Finish a hotfix
git flow hotfix finish <version>
```

## Project Structure

This repository follows GitFlow best practices for collaborative development and maintains clean separation between development and production code.

## Getting Started

1. Clone the repository
2. Ensure git-flow is installed
3. The repository is already initialized with GitFlow
4. Start developing using feature branches

## Contributing

Please follow the GitFlow workflow when contributing to this project:

1. Create feature branches from `develop`
2. Use pull requests for code review
3. Merge completed features back to `develop`
4. Use release branches for production deployments