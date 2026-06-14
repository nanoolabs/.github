# Nanoo Labs .github organization repository [⌐■_■]

This repository is the **Control** for the **Nanoo Labs** organization. It contains global settings, community standards, and automation for all repositori in Nanoo Labs.

## Community Health Files

These files are global standard. If a repository in Nanoo Labs does not have its own version, GitHub will use these files:

- [CONTRIBUTING.md](./CONTRIBUTING.md) – Principles of "Performance-first, zero-bloat"
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) – Community behavior standards
- [SECURITY.md](./SECURITY.md) – How to report security problems.
- [.github/ISSUE_TEMPLATE/](./.github/ISSUE_TEMPLATE/) – Global templates for Bug Reports and Feature Requests
- [.github/PULL_REQUEST_TEMPLATE.md](./.github/PULL_REQUEST_TEMPLATE.md) – Global template for Pull Requests

## Profile Content

- [./profile/README.md](./profile/README.md) – Content for the main organization page at [github.com/nanoolabs](https://github.com/nanoolabs).

## Global Automation

- [.github/workflows/welcome.yml](./.github/workflows/welcome.yml) – Automatic welcome bot for every new contributor
- [.github/workflows/update-progress.yml](./.github/workflows/update-progress.yml) - Automatic roadmap update with **Auto-Status** logic.

### Auto-Status Logic

The status in the organization profile is calculate automatically base on the percentage in `progress.json`:

| Percent | Status Label |
| :--- | :--- |
| **0% - 10%** | `Planning` |
| **11% - 30%** | `Development` |
| **31% - 50%** | `Alpha` |
| **51% - 75%** | `Experimental` |
| **76% - 99%** | `Polishing` |
| **100%** | `Stable` |

Stay fast. Stay simple. [⌐■_■]

