# Contributing to CMDS

Thanks for your interest in contributing. This guide applies to every repository in the [CMDS organization](https://github.com/cmds-app) unless an individual repo overrides it with its own `CONTRIBUTING.md`.

## Ways to contribute

- **Report a problem** — open a [Fix](../../issues/new?template=fix.yml) issue.
- **Propose a feature** — open a [Feature](../../issues/new?template=feature.yml) issue.
- **Suggest a refactor** — open a [Refactor](../../issues/new?template=refactor.yml) issue.
- **Track infrastructure work** — open a [Setup](../../issues/new?template=setup.yml) issue.
- **Submit code** — open a pull request following the steps below.

Before opening a new issue, search existing issues to avoid duplicates. If a related issue exists, comment there instead.

## Development workflow

1. **Fork and clone** the repository you want to change.
2. **Create a branch** from `main`. Use a short, descriptive name (e.g. `fix/login-redirect`, `feature/export-csv`).
3. **Make your changes.** Keep commits focused and write clear commit messages.
4. **Run the project's tests and linters** locally. Repo-specific commands live in the repo's `README.md`.
5. **Open a pull request** against `main` and fill out the [pull request template](./pull_request_template.md).

### Branch naming

| Prefix      | Use for                                  |
| :---------- | :--------------------------------------- |
| `fix/`      | Bug fixes                                |
| `feature/`  | New features or feature changes          |
| `refactor/` | Internal restructuring, no behavior change |
| `setup/`    | Infrastructure or tooling changes        |
| `docs/`     | Documentation-only updates               |

### Commit messages

- Write commits in the imperative mood ("Add export button", not "Added export button").
- Keep the subject line under 72 characters.
- Reference related issues in the body (e.g. `Closes #123`).

## Pull requests

- Link the PR to the issue it resolves.
- Keep PRs as small as practical — split large changes into reviewable chunks.
- Ensure CI passes before requesting review.
- Update documentation and tests alongside code changes.
- Mark the PR as a draft if it is not ready for review.

A maintainer will review your PR. Address feedback by pushing additional commits to the same branch; do not force-push after review has started unless asked.

## Code style

Each repository documents its own style and tooling in its `README.md`. In general:

- Match the conventions already present in the file you are editing.
- Run the repo's formatter and linter before committing.
- Add or update tests for any behavior change.

## Reporting security issues

Do **not** open a public issue for security vulnerabilities. Follow the disclosure process in [`SECURITY.md`](./SECURITY.md).

## Code of conduct

All contributors are expected to follow the [Code of Conduct](./CODE_OF_CONDUCT.md).

## Getting help

If you are stuck, see [`SUPPORT.md`](./SUPPORT.md) for the right channel to ask.
