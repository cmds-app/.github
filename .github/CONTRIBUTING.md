# Contributing to CMDS

Thanks for your interest in contributing. This guide applies to every repository in the [CMDS organization](https://github.com/cmds-app) unless an individual repo overrides it with its own `CONTRIBUTING.md`.

## Ways to contribute

- **Report a problem.** Open a [Fix](../../issues/new?template=fix.yml) issue.
- **Propose a feature.** Open a [Feature](../../issues/new?template=feat.yml) issue.
- **Suggest a refactor.** Open a [Refactor](../../issues/new?template=refactor.yml) issue.
- **Report a slow path.** Open a [Performance](../../issues/new?template=perf.yml) issue.
- **Fix or add documentation.** Open a [Docs](../../issues/new?template=docs.yml) issue.
- **Add or improve tests.** Open a [Test](../../issues/new?template=test.yml) issue.
- **Track maintenance or infrastructure work.** Open a [Chore](../../issues/new?template=chore.yml) issue.
- **Submit code.** Open a pull request following the steps below.

Before opening a new issue, search existing issues to avoid duplicates. If a related issue exists, comment there instead.

## Development workflow

1. **Fork and clone** the repository you want to change.
2. **Create a branch** from `main`. Use a short, descriptive name (e.g. `fix/login-redirect`, `feat/export-csv`).
3. **Make your changes.** Keep commits focused and write clear commit messages.
4. **Run the project's tests and linters** locally. Repo-specific commands live in the repo's `README.md`.
5. **Open a pull request** against `main` and fill out the [pull request template](./pull_request_template.md).

### Branch naming

| Prefix      | Use for                                  |
| :---------- | :--------------------------------------- |
| `fix/`      | Bug fixes                                |
| `feat/`     | New features or feature changes          |
| `refactor/` | Internal restructuring, no behavior change |
| `perf/`     | Performance improvements                 |
| `docs/`     | Documentation-only updates               |
| `test/`     | Test additions or improvements           |
| `chore/`    | Maintenance, tooling, or infrastructure  |

### Commit messages

Commits follow [Conventional Commits](https://www.conventionalcommits.org/).

- **Format.** `<type>(<scope>): <description>` with an optional body and footer. The scope is optional; the parentheses go away with it.
- **Type.** Lowercase, from: `fix`, `feat`, `refactor`, `perf`, `docs`, `test`, `chore`, `build`, `ci`, `style`, `revert`. The first seven match the branch-prefix and issue-template taxonomy above; the last four (`build`, `ci`, `style`, `revert`) are commit-only types with no matching branch prefix.
- **Description.** Lowercase, imperative mood ("add export button", not "added export button"), no trailing period. Keep it under 72 characters.
- **Body.** Optional. Wrap at 72 characters. Explain *why*, not *what*. Skip when the subject is self-explanatory.
- **Breaking change.** Append `!` after the type or scope (`feat!:` or `feat(api)!:`) and add a `BREAKING CHANGE:` footer describing the migration.
- **Issue references.** Add `Closes #123` (or `Refs #123`) to the footer.
- **Atomic commits.** One logical change per commit. If you can't pick a single type, split it.

## Pull requests

- Link the PR to the issue it resolves.
- Keep PRs as small as practical - split large changes into reviewable chunks.
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
