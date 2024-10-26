# Contributing to Signeo

Thank you for considering contributing to Signeo! Here’s how you can help and the guidelines we follow.

## Coding Standards
- **Style**: Use CamelCase for variables and functions. Follow Prettier for consistent code formatting.
- **Linting**: Follow Prettier for consistent code formatting.
- **Best Practices**:
  - Use **camelCase** for variables and functions.
  - Use descriptive variable names and document functions/classes as needed.
  - Avoid deeply nested code for clarity.
  - Limit functions to **20 lines** and **80 characters** wide for readability.

## Branch Naming
- **Main Branch**: `main`
- **Feature Branches**: `feature/short-description` (e.g., `feature/SubtitleSupport`)
- **Bugfix Branches**: `bugfix/short-description` (e.g., `bugfix/AudioDelayFix`)
- **Hotfixes**: `hotfix/short-description` (e.g., `hotfix/CriticalErrorFix`)
- **Release Branches**: `release/version-number` (e.g., `release/1.0.0`)

### Commit Messages
- Use the following format: `[Type] [#IssueId] Short description`
  - **Types**:
    - `[feat]`: New feature or addition
    - `[fix]`: Bug fix
    - `[refactor]`: Code improvements without changing functionality
    - `[test]`: Adding or updating tests
    - `[docs]`: Documentation changes
    - `[chore]`: Routine updates like dependency updates or small tweaks

  - **Example**:
    ```
    [feat] [#123] added live subtitle support for mobile
    [fix] [#45] [#67] resolved audio delay and subtitle lag
    [refactor] [#78] optimized subtitle processing for speed
    [chore] updated dependencies to latest versions
    ```

  - **Linking Multiple Issues**:
    - If a commit addresses multiple issues, include each issue number in brackets (e.g., `[fix] [#45] [#67] description`).

## Issue Management Guidelines

1. **Issue Labels**: Use labels to categorize issues:
   - **Core Labels**:
     - **bug**: Something isn’t working as expected.
     - **enhancement**: New feature or feature improvement.
     - **question**: Further information or clarification is requested.
     - **documentation**: Improvements or additions to documentation.

   - **Optional Labels**:
     - **help wanted**: Issues needing extra attention or support.
     - **duplicate**: Issue or pull request already exists.
     - **invalid**: Issue or pull request that doesn’t meet guidelines or is incorrect.
     - **wontfix**: Issue that won’t be addressed.

2. **Assigning Issues**: Assign issues to yourself before starting work to avoid duplication.

## Pull Requests
- Create a new branch for each feature or fix.
- Run all tests locally before creating a PR.
- In the PR description, use `Closes #issue_number` for each issue to automatically close it upon merging.
- **Tagging**: Apply relevant labels to your PR (e.g., `bug`, `enhancement`, `documentation`) for easy categorization.
- Ensure that your PR description includes:
  - **Summary of changes**
  - **Related issues**
  - **Checklist** (from the PR template)

Thank you for helping to make Signeo a great project!
