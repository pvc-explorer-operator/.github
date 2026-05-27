# Contributing to PVC Explorer Operator Projects

Thank you for taking the time to contribute! Every bug report, feature idea, and code improvement makes this project better for everyone.

## Table of contents

- [Code of Conduct](#code-of-conduct)
- [Getting started](#getting-started)
- [How to report a bug](#how-to-report-a-bug)
- [How to suggest a feature](#how-to-suggest-a-feature)
- [How to submit a pull request](#how-to-submit-a-pull-request)
- [Development setup](#development-setup)
- [Commit style](#commit-style)

---

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating you agree to abide by its terms. Please report unacceptable behaviour to the maintainers via a private GitHub message.

---

## Getting started

Not sure where to start? Look for issues labelled **`good first issue`** — these are intentionally scoped to be approachable without deep knowledge of the codebase.

For larger changes, **open an issue first** to discuss the idea before writing code. This avoids wasted effort if the direction doesn't fit the project's scope.

---

## How to report a bug

Use the **Bug report** issue template. Please include:

- What you did
- What you expected to happen
- What actually happened
- Your Kubernetes version, controller/agent version, and how you deployed (kind / in-cluster)

Security vulnerabilities should **not** be reported as public issues — see [SECURITY.md](SECURITY.md).

---

## How to suggest a feature

Use the **Feature request** issue template. Explain the problem you're trying to solve, not just the solution you have in mind. That helps us understand whether it fits the project's scope and discuss alternatives.

---

## How to submit a pull request

1. Fork the repo and create a branch from `main`.
2. Make your changes. If you're fixing a bug, add a test that would have caught it.
3. Run the full test suite locally (see repo README for details).
4. Run the linter (see repo README for details).
5. If you changed API or manifests, run the relevant generation commands.
6. Open a pull request against `main`. Fill in the PR template.

A maintainer will review within a reasonable time. If you haven't heard back in a week, feel free to ping the thread.
