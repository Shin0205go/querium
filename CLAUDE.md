# CLAUDE.md - AI Assistant Guidelines for Querium

## Project Overview

**Querium** (query + arium) is a "greenhouse for queries" - a project designed to nurture and cultivate questions and inquiries. The name combines the English "query" (問い) with the Latin suffix "-arium" (生息地/habitat), suggesting a nurturing environment for questions and knowledge exploration.

## Repository Structure

```
querium/
├── README.md          # Project overview and documentation
├── CLAUDE.md          # AI assistant guidelines (this file)
└── (project files to be added)
```

As the project grows, expect the following structure to emerge:

```
querium/
├── src/               # Source code
│   ├── components/    # UI components (if applicable)
│   ├── services/      # Business logic and services
│   ├── utils/         # Utility functions
│   └── types/         # Type definitions
├── tests/             # Test files
├── docs/              # Documentation
├── scripts/           # Build and utility scripts
└── config/            # Configuration files
```

## Development Workflow

### Getting Started

1. Clone the repository
2. Install dependencies (when package manager is configured)
3. Follow the setup instructions in README.md

### Branch Naming Convention

- `main` or `master` - Production-ready code
- `develop` - Integration branch for features
- `feature/<name>` - New features
- `fix/<name>` - Bug fixes
- `claude/<description>-<session-id>` - AI-assisted development branches

### Commit Message Guidelines

Use clear, descriptive commit messages:

- `feat: <description>` - New features
- `fix: <description>` - Bug fixes
- `docs: <description>` - Documentation changes
- `refactor: <description>` - Code refactoring
- `test: <description>` - Test additions/changes
- `chore: <description>` - Maintenance tasks

## Conventions for AI Assistants

### General Principles

1. **Read before writing** - Always read existing files before making modifications
2. **Minimal changes** - Make only the changes necessary to complete the task
3. **No over-engineering** - Keep solutions simple and focused
4. **Preserve existing patterns** - Follow conventions already established in the codebase
5. **Japanese context** - Be aware this project may include Japanese language elements

### Code Style

- Use consistent indentation (spaces preferred, typically 2 or 4 spaces)
- Follow the existing code style in the project
- Add comments only when logic isn't self-evident
- Keep functions small and focused

### Documentation

- Update README.md when adding significant features
- Document public APIs and complex logic
- Use JSDoc/TSDoc style comments for function documentation when appropriate

### Testing

- Write tests for new functionality when a test framework is established
- Ensure existing tests pass before committing
- Test edge cases and error conditions

### File Operations

- Create new files only when necessary
- Prefer editing existing files over creating new ones
- Use appropriate file extensions based on content type

## Language & Internationalization

Given the project name's Japanese etymology:
- Support for Japanese text should be considered in UI/UX decisions
- Use UTF-8 encoding for all text files
- Comments and documentation may include both English and Japanese

## Security Considerations

- Never commit sensitive data (API keys, passwords, credentials)
- Use environment variables for configuration secrets
- Validate user input at system boundaries
- Follow OWASP security guidelines

## Current Project Status

**Status: Initial Development**

This is a newly created repository. As the project evolves:
- This CLAUDE.md file should be updated to reflect new conventions
- Technology stack decisions will be documented here
- Build and deployment instructions will be added

## Contact & Contribution

For contributing to this project:
1. Create a feature branch from the main development branch
2. Make changes following the conventions above
3. Submit a pull request with a clear description

---

*Last updated: 2025-12-31*
