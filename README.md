# cmds-app/.github

This repository holds organization-level configuration and default community health files for the CMDS organization.

## How GitHub uses this repo

GitHub looks in `.github` for default community health files that apply across every repo in the organization. When a specific CMDS repository does not define its own version of one of these files, GitHub falls back to the version stored here.

Full behavior is documented in [creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Typical contents

| File or folder              | Purpose |
| :-------------------------- | :------ |
| `CODE_OF_CONDUCT.md`        | Expected behavior for contributors and maintainers |
| `CONTRIBUTING.md`           | How to propose changes, file issues, and submit pull requests |
| `SECURITY.md`               | How to report security vulnerabilities |
| `SUPPORT.md`                | Where to get help |
| `ISSUE_TEMPLATE/`           | Default issue templates |
| `PULL_REQUEST_TEMPLATE.md`  | Default pull request template |
| `workflows/`                | Reusable GitHub Actions workflows available to any repo in the org |
| `profile/README.md`         | Content rendered on the organization's public profile page at `github.com/cmds-app` |
