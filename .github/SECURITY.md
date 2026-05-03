# Security Policy

The CMDS organization takes the security of its software seriously. This policy applies to every repository in the [CMDS organization](https://github.com/cmds-app) unless an individual repo overrides it with its own `SECURITY.md`.

## Reporting a vulnerability

**Do not open a public issue, discussion, or pull request for security vulnerabilities.** Public disclosure before a fix is available puts users at risk.

Report vulnerabilities through one of the following private channels:

- **GitHub private vulnerability reporting** — preferred. Open a report from the affected repository's **Security** tab → **Report a vulnerability**.
- **Email** — send details to [security@cmds-app.com](mailto:security@cmds-app.com).

When reporting, please include:

- The affected repository, version, or commit.
- A description of the vulnerability and its impact.
- Steps to reproduce, or a proof-of-concept if available.
- Any suggested mitigation or fix.
- Whether you intend to disclose publicly, and on what timeline.

You may encrypt sensitive reports; request our PGP key by email if needed.

## What to expect

| Stage              | Target response time          |
| :----------------- | :---------------------------- |
| Initial acknowledgement | Within 3 business days   |
| Triage and severity assessment | Within 7 business days |
| Status updates     | At least every 14 days while the report is open |
| Fix and disclosure | Coordinated with the reporter, typically within 90 days of triage |

We will:

1. Confirm receipt of your report.
2. Investigate and reproduce the issue.
3. Determine severity and affected versions.
4. Develop and test a fix.
5. Release a patch and publish a security advisory.
6. Credit the reporter in the advisory, unless you prefer to remain anonymous.

## Supported versions

Unless a repository's `README.md` states otherwise, only the latest release of each project receives security updates. Repository-specific support windows take precedence over this default.

## Scope

In scope:

- Source code and release artifacts published under the [cmds-app](https://github.com/cmds-app) organization.
- Official deployments and services operated by CMDS.

Out of scope:

- Third-party dependencies (report those upstream; we will track and update once a patch is available).
- Forks or modified distributions not maintained by CMDS.
- Issues requiring physical access, social engineering, or already-compromised user accounts.
- Denial-of-service attacks, automated scanner output without a working proof-of-concept, and theoretical issues with no demonstrable impact.

## Safe harbor

We will not pursue legal action against researchers who:

- Make a good-faith effort to comply with this policy.
- Avoid privacy violations, data destruction, and service disruption.
- Give us a reasonable opportunity to remediate before public disclosure.
- Do not exploit a vulnerability beyond what is necessary to demonstrate it.

## Public disclosure

Once a fix is released, we publish a [GitHub Security Advisory](https://docs.github.com/en/code-security/security-advisories) on the affected repository describing the issue, affected versions, and remediation steps. Reporters are credited unless they request otherwise.
