# Nanoo Labs · Org Control [⌐■_■]

**The control repository for the Nanoo Labs organization** - global settings, community standards, and automation inherited by every Nanoo Labs repo.

## Community Health Files [ ▨_▨ ]

These files are global standard. If a repository in Nanoo Labs does not have its own version, GitHub will use these files:

- [CONTRIBUTING](./CONTRIBUTING.md) – How to contribute, commit style, and standards
- [CODE OF CONDUCT](./CODE_OF_CONDUCT.md) – Community behavior standards
- [SECURITY](./SECURITY.md) – How to report security problems
- [LICENSE](./LICENSE) - MIT License
- [ISSUE TEMPLATES](./.github/ISSUE_TEMPLATE/) – Global templates for Bug Reports and Feature Requests
- [PR TEMPLATE](./.github/PULL_REQUEST_TEMPLATE.md) – Global template for Pull Requests

## Profile Content [⌐■_■]

- [PROFILE](./profile/README.md) – Content for the main organization page at [github.com/nanoolabs](https://github.com/nanoolabs)

## Global Automation [ ▣_▣ ]

- [WELCOME](./.github/workflows/welcome.yml) – Automatic welcome bot for every new contributor
- [UPDATE PROGRESS](./.github/workflows/update-progress.yml) – Automatic roadmap update with **Auto-Status** logic.

### Auto-Status Logic

The status in the organization profile is calculated automatically based on the percentage in `progress.json`:

| Percent       | Status Label   |
| :------------ | :------------- |
| **0% - 10%**  | `Planning`     |
| **11% - 30%** | `Development`  |
| **31% - 50%** | `Alpha`        |
| **51% - 75%** | `Experimental` |
| **76% - 99%** | `Polishing`    |
| **100%**      | `Stable`       |

Stay fast. Stay simple. [⌐■_■]
