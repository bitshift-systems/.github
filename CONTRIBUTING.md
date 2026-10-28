# Contributing to Bitshift Systems

First off, thanks for taking the time to contribute! 💜

At **Bitshift Systems**, we build software with an emphasis on simplicity,
maintainability, and doing things properly. Whether you're fixing a typo,
reporting a bug, improving documentation, or contributing code, we appreciate
your help.

This document outlines our general contribution guidelines. Individual
repositories may have additional instructions that take precedence over this
document.

## Getting Started

Before contributing, we recommend:

1. Reading the repository's `README.md` to understand what the project does.
2. Checking for existing issues or pull requests related to what you want to
   work on.
3. Reviewing any project-specific development instructions.
4. Opening an issue or discussion before starting particularly large changes.

For smaller fixes, feel free to jump straight into a pull request.

## Reporting Issues

Found a bug or have an idea? We'd love to hear about it.

Before opening an issue, please check whether something similar has already been
reported.

When reporting a bug, try to include:

- A clear description of the problem.
- Steps to reproduce it, where applicable.
- What you expected to happen, and what actually happened.
- Relevant logs, screenshots, or error messages.
- Information about your environment, if relevant.

For feature requests, explain the problem you're trying to solve rather than
focusing solely on a particular implementation.

Please avoid including credentials, personal information, or other sensitive
data in issues.

## Making Changes

### Keep Changes Focused

Prefer small, focused contributions over large, unrelated changes.

A pull request should ideally address one issue or introduce one cohesive
improvement. This makes changes easier to review, test, and maintain.

If you're planning a substantial refactor or architectural change, consider
opening an issue or discussion first.

### Follow Existing Conventions

Different projects have different needs. Follow the existing conventions of the
repository you're contributing to.

In general:

- Prefer straightforward, readable code over clever solutions.
- Keep abstractions purposeful and avoid unnecessary complexity.
- Follow the project's established formatting and naming conventions.
- Add or update tests when changing behaviour.
- Update documentation when introducing or changing functionality.
- Avoid introducing new dependencies without a good reason.
- Consider backwards compatibility when changing public interfaces.

We value maintainability over perfection. Code doesn't need to be fancy to be
good.

### Testing

Before submitting your changes, run any relevant tests, linters, and formatters
provided by the repository.

If you can't run a particular check, mention it in your pull request.

Where practical, new functionality should include tests, and bug fixes should
include regression coverage.

## Pull Requests

When you're ready, open a pull request against the appropriate branch.

A good pull request should:

- Explain **what** changed and **why**.
- Reference any related issues (e.g. `Closes #123`).
- Describe how the changes were tested.
- Highlight any breaking changes, migrations, or important considerations.
- Include screenshots or examples for user-facing changes, where useful.

Draft pull requests are welcome for work in progress or when you'd like early
feedback.

### Reviews

Code review is a collaborative process, not an exam.

We aim to keep feedback constructive, specific, and focused on the code rather
than the person writing it.

As a contributor, please be open to suggestions and questions. As a reviewer,
explain the reasoning behind requested changes where possible.

Not every suggestion needs to be implemented, but discussions should be resolved
before merging.

Maintainers may request changes, close pull requests, or decline contributions
that don't align with a project's goals or direction.

## Commits

Write commit messages that explain what changed in a way that will make sense
to someone reading the history later.

We recommend using [Conventional Commits](https://www.conventionalcommits.org/)
where practical:

- `feat: add support for custom configuration`
- `fix: handle missing environment variables`
- `docs: clarify installation instructions`
- `refactor: simplify request validation`
- `chore: update dependencies`

Individual repositories may enforce specific commit message formats or use
automated release tooling.

There's no requirement to maintain a perfectly clean commit history while
working. Commits will be squashed before merging.

## Security

**Please don't report security vulnerabilities through public GitHub issues.**

If a repository has private vulnerability reporting enabled, use GitHub's
**Report a vulnerability** feature under its Security tab.

Otherwise, refer to the repository's `SECURITY.md` for disclosure instructions.

Avoid publishing exploit details or sensitive information before maintainers
have had an opportunity to investigate.

## Community & Conduct

We want Bitshift Systems projects to be welcoming spaces for people of all
backgrounds and experience levels.

Please:

- Treat others with respect and assume good intentions.
- Be constructive when giving or receiving feedback.
- Welcome questions and contributions from people who are learning.
- Disagree with ideas without attacking people.
- Respect others' time, boundaries, and contributions.

Harassment, discrimination, and deliberately hostile behaviour are not welcome.

Where a repository includes a `CODE_OF_CONDUCT.md`, that document provides
additional guidance.

## Licensing

By submitting a contribution, you agree that it may be distributed under the
repository's existing licence.

Make sure you have the right to submit any code, documentation, or other
materials included in your contribution.

If you're unsure about licensing or third-party content, please ask before
submitting.

## Finally

Not every contribution needs to be code.

Bug reports, documentation improvements, design discussions, testing, and
thoughtful feedback all help make projects better.

Thanks for helping build things with us.

**The Bitshift Systems maintainers** 💜
