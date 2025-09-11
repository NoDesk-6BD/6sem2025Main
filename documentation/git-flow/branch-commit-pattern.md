## Objective

This document aims to standardize development practices across all project repositories, promoting consistency, readability, and efficient collaboration among team members. The guidelines apply to all stakeholders, including the Frontend, Backend and ETL teams.

<br>

## Branch Pattern

A branch is a resource that allows the team to work on different versions of the code simultaneously, without interfering with what is already stable and working.

### Main Branches:

- `main`: Contains the stable, production-ready version of the project.
- `sprint-{number}`: Branch used as a basis for ongoing sprint tasks.

> Example: `sprint-1`, `sprint-2`, `sprint-3`

### Format:

```shell
{type}/{jira-card-code}-{brief-description}
```

### Allowed types:

- `feature` - Implementation of new functionality.
- `fix` - Bug fixes, both in development and production.
- `hotfix` - Urgent fixes of critical bugs in production.
- `chore` - Maintenance tasks or adjustments without direct impact on the source code.
- `doc` - Changes exclusively to the documentation (code comments, README, etc.).

### Example:

```shell
feature/ND-1-creation-initial-backend-structure
```

> Use lowercase letters and hyphens instead of spaces. The card code must come from the management tool (Jira).

<br>

## Commit Pattern

Standardizing commit messages is an important practice because, in addition to helping understand the commit history, it facilitates the creation of automated tools based on the specification.<br>
Learn more by clicking here: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Format:

```shell
{type} ({code-card-jira}): {short description}
```

### Allowed types:

- `feat` - Implementation of new functionality.
- `fix` - Fixing bugs or issues in the code.
- `doc` - Changes to the documentation.
- `style` - Formatting adjustments (without functional impact).
- `refactor` - Code refactoring.
- `test` - Adding or updating tests.
- `chore` - Task with no direct impact on source code, tools, or libraries.

### Example:

```shell
feat (ND-1): Creating the initial backend structure
```
