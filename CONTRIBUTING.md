# Contributing to `setup-cli`

Thank you for your interest in contributing to setup-cli. This guide will help you get started with the contribution process.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](/CODE_OF_CONDUCT.md) By participating, you are expected to uphold this code.

## Types of Contributions

### Report Bugs

Report bugs at https://github.com/wriftai/setup-cli/issues

If you are reporting a bug, please include:

- Your operating system name and version.
- Any details about your local setup that might be helpful in troubleshooting.
- Detailed steps to reproduce the bug.

### Fix Bugs

Look through the GitHub issues for bugs.
Anything tagged with "bug" and "help wanted" is open to whoever wants to implement a fix for it.

### Implement Features

Look through the GitHub issues for features.
Anything tagged with "enhancement" and "help wanted" is open to whoever wants to implement it.

### Submit Feedback

The best way to send feedback is to file an issue at https://github.com/wriftai/setup-cli/issues.

If you are proposing a new feature:

- Explain in detail how it would work.
- Keep the scope as narrow as possible, to make it easier to implement.

## Getting Started

1. Fork the `setup-cli` repo on GitHub.

2. Clone your fork locally:

```bash
git clone git@github.com:wriftai/setup-cli.git
cd setup-cli
```

## Development Workflow

1. Create a new branch for your changes:
   ```bash
   git checkout -b type/description
   # Example: git checkout -b feat/add_workflow
   ```
2. Add tests for your changes

3. Commit your changes with a descriptive message following this format:

   ```
   fix: fix incorrect prediction polling

   Issue: <issue url>
   ```

   Commit messages should be well formatted, and to make that "standardized", use Conventional Commits. You can follow the documentation on [their website](https://www.conventionalcommits.org).

4. Push your branch to your fork
5. Open a pull request. In your PR description:
   - Clearly describe what changes you made and why
   - Include any relevant context or background
   - List any breaking changes or deprecations
   - Reference related issues or discussions