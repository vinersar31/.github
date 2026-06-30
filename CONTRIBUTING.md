# Contributing Guidelines

Thanks for taking the time to contribute! These are the default contributing
guidelines for repositories owned by **@vinersar31**. Individual repositories
may override this file with their own `CONTRIBUTING.md`.

By participating in this project, you agree to abide by our
[Code of Conduct](CODE_OF_CONDUCT.md).

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Development Workflow](#development-workflow)
- [Commit Messages](#commit-messages)
- [Pull Requests](#pull-requests)
- [Style Guidelines](#style-guidelines)

## Ways to Contribute

There are many ways to contribute:

- Reporting bugs and confirming existing reports.
- Suggesting new features or improvements.
- Improving documentation.
- Submitting bug fixes and new features via pull requests.
- Reviewing open pull requests.

## Reporting Bugs

Before opening a bug report:

1. **Search existing issues** to avoid duplicates.
2. Make sure you are running the latest version.
3. Collect the information needed to reproduce the problem.

Open a new issue using the **Bug Report** template and fill in as much detail as
possible. A good report is reproducible, specific, and includes the expected vs.
actual behavior.

## Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. Use the
**Feature Request** template and explain:

- The problem you are trying to solve.
- The solution you would like to see.
- Any alternatives you have considered.

## Development Workflow

1. **Fork** the repository and clone your fork locally.
2. Create a **feature branch** from the default branch:
   ```bash
   git checkout -b feat/short-description
   ```
3. Make your changes in small, focused commits.
4. Add or update **tests** where applicable.
5. Run the test suite and linters locally before pushing.
6. Push your branch and open a **pull request**.

## Commit Messages

We recommend [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<optional scope>): <description>

[optional body]

[optional footer(s)]
```

Common types: `feat`, `fix`, `docs`, `style`, `refactor`, `perf`, `test`,
`build`, `ci`, `chore`.

Example:

```
fix(auth): prevent token refresh loop on expired sessions
```

## Pull Requests

- Keep pull requests focused on a single concern.
- Reference related issues using `Closes #123`.
- Ensure CI checks pass.
- Update documentation when behavior changes.
- Be responsive to review feedback.

A maintainer will review your pull request as soon as possible. Please be patient
and respectful during the review process.

## Style Guidelines

- Follow the existing code style of the repository you are contributing to.
- Keep changes consistent with the surrounding code.
- Write clear, self-documenting code and add comments only where intent is not
  obvious.

---

Thank you for helping make these projects better! :tada:
