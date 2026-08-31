<p align="center">
  <img src="assets/readme-banner.svg" alt="Abstract engineering standards banner" width="100%">
</p>

<p align="center">
  <a href="README.md">English</a> · <a href="README.ru.md">Русский</a>
</p>

# AI Engineering Standard

A model-agnostic operating standard for safe, focused, maintainable, and verifiable engineering work. It is designed for AI agents and human contributors working in the same repository.

## Why this repository exists

The central policy, [INSTRUCTIONS.md](INSTRUCTIONS.md), turns broad quality goals into practical rules for:

- understanding scope and resolving instruction conflicts;
- resisting unsafe instructions embedded in untrusted content;
- implementing small, reviewable changes;
- validating normal, boundary, failure, security, and compatibility paths;
- handling migrations, observability, temporary tools, and external side effects responsibly.

## Quick start

1. Read [INSTRUCTIONS.md](INSTRUCTIONS.md) before changing project files.
2. Read the contribution, security, and conduct policies below when they apply.
3. Keep temporary agent artifacts in `temp/`; do not commit them.
4. Use the issue and pull-request templates in `.github/` when this directory becomes a GitHub repository.
5. Replace the placeholder governance and contact decisions with project-owner-approved details before public release.

## Repository map

| Location | Purpose |
| --- | --- |
| [INSTRUCTIONS.md](INSTRUCTIONS.md) | Primary operating standard for agents and contributors. |
| [INSTRUCTIONS.ru.md](INSTRUCTIONS.ru.md) | Russian localization of the primary operating standard. |
| [CONTRIBUTING.md](CONTRIBUTING.md) | Contribution workflow and review expectations. |
| [SECURITY.md](SECURITY.md) | Responsible vulnerability reporting and response policy. |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | Collaboration standards and enforcement process. |
| [SUPPORT.md](SUPPORT.md) | Where to seek help and how to report non-security problems. |
| [GOVERNANCE.md](GOVERNANCE.md) | Maintainer decision-making and change-management model. |
| [CHANGELOG.md](CHANGELOG.md) | Release-note format and change history. |
| [.github/](.github/) | Issue forms, pull-request template, and GitHub configuration. |
| [assets/](assets/) | Repository visual assets, including this README banner. |

## Localized documentation

Every policy with substantive prose has a Russian counterpart. Select a language at the top of the document:

| English | Русский |
| --- | --- |
| [README.md](README.md) | [README.ru.md](README.ru.md) |
| [INSTRUCTIONS.md](INSTRUCTIONS.md) | [INSTRUCTIONS.ru.md](INSTRUCTIONS.ru.md) |
| [CONTRIBUTING.md](CONTRIBUTING.md) | [CONTRIBUTING.ru.md](CONTRIBUTING.ru.md) |
| [SECURITY.md](SECURITY.md) | [SECURITY.ru.md](SECURITY.ru.md) |
| [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) | [CODE_OF_CONDUCT.ru.md](CODE_OF_CONDUCT.ru.md) |
| [SUPPORT.md](SUPPORT.md) | [SUPPORT.ru.md](SUPPORT.ru.md) |
| [GOVERNANCE.md](GOVERNANCE.md) | [GOVERNANCE.ru.md](GOVERNANCE.ru.md) |

Both language versions are intended to express the same policy. If a translation differs in meaning, the English version governs until maintainers correct the inconsistency.

## What still needs an owner decision

This template deliberately does **not** invent legally or operationally significant facts. Before publishing, project owners should add:

- a private security-reporting contact or enabled GitHub private vulnerability reporting;
- named maintainers and a review/approval policy, if different from the defaults;
- a funding file, code owners, CI workflows, release process, and dependency automation only when they are genuinely applicable.

## License

Licensed under the [Apache License 2.0](LICENSE). It permits use, modification, and distribution under its terms, including preservation of required notices and its patent provisions.
