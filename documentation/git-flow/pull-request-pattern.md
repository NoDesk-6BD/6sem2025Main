## Objective

This document aims to standardize development practices across all project repositories, promoting consistency, readability, and efficient collaboration among team members. The guidelines apply to all stakeholders, including the Frontend, Backend and ETL teams.

<br>

## Pull Request Pattern

A Pull Request (PR) is a resource that allows the team to collaboratively review and integrate code changes, ensuring quality and avoiding negative impacts on the already stable code.

### Format:

```shell
{type} ({code-card-jira}): {Brief description}
```

### Allowed types:

- `Feature` – Implementation of new functionality.
- `Fix` – Bug fixes in development or production.
- `Hotfix` – Urgent fixes of critical bugs in production.
- `Docs` – Documentation changes or additions.
- `Refactor` – Code changes that do not modify functionality.
- `Chore` – Maintenance tasks or adjustments without direct impact on the source code.

### Example:

```shell
Feature (ND-1): Creating the initial backend structure
```

> Always capitalize types (Feature, Fix, etc.) for consistency.

<br>

## Guidelines for opening a PR:

- Each new feature or fix must be submitted via Pull Request.
- Tag at least one reviewer from the team.
- Add the task link in Jira.
- Clearly describe what was changed.
- Make sure your branch is up to date with the sprint branch before submitting.

<br>

## Code Review

- Each PR must be reviewed by at least **one team member**.

#### The reviewer must check:

- Code clarity and readability.
- Test coverage (if applicable).
- Impact on other parts of the system. - Adherence to the best practices and standards defined in this repository.

> No PR should be merged without approval and success in the CI workflow.

<br>

## Definition of Done (DoD) for PRs

A PR will only be considered completed (Done) if it meets the following criteria:

- The code has been reviewed by at least one team member.
- All existing tests have passed successfully.
- New tests have been created (when applicable).
- Documentation has been updated (if necessary).
- There are no conflicts with the main branch of the sprint.
- The CI/CD workflow has run successfully.
- The PR contains a clear description and a link to the card in Jira.
- The task acceptance criteria (from Jira) have been met.
