# Contributing
Thank you for contributing. This guide outlines the process for proposing changes and submitting pull requests.

## Pull requests
Pull requests are the preferred way to propose changes to the codebase. We follow the [fork-and-pull workflow](https://github.com/susam/gitpr) and welcome contributions from the community.

1. Fork the repository to your own GitHub account.
2. Clone the project to your local machine.
3. Create a branch with a concise, descriptive name.
4. Make your changes and follow any repository-specific formatting or testing requirements.
5. Push the branch to your fork.
6. Open a pull request in the main repository.

## Guidelines

### Commit message guidelines
Use a commit format that includes a commit type and a clear summary, with an optional description when needed.

- Commit type: Use the appropriate conventional commit type as defined by [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
- Commit summary: Write the summary in the imperative mood, as if giving a command. Do not capitalize the first letter, and do not end it with a period.

```bash
Examples:
  docs: update readme file
  feat: add application dockerfile
```

### Pull request guidelines
Use a title in the format: [Commit Type] Short Summary

```bash
Examples:
  [feat] add input parsing for user data
  [fix] resolve VPC subnet configuration issue
```

### Coding guidelines
- Add comments only where they improve clarity.
- Follow the DRY principle and avoid unnecessary duplication.

## Linting and formatting
This repository contains configuration for the pre-commit tool, which automates checking linting and formatting during a commit.

## Reporting bugs
We use GitHub Issues to track bugs. Please open a new issue to report a problem or unexpected behavior.

## License
By contributing, you agree that your contributions will be licensed under the project's [MIT License](LICENSE.md).
