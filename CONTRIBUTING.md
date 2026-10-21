**English** | [Русский](CONTRIBUTING.ru.md)

# Contributing

Thanks for helping with Vazie. Each repository has its own `CONTRIBUTING.md` with build steps and project rules;
this page covers what is common to all of them.

## Ground rules

1. **Never commit or post real secrets**: passwords, databases, keys, configurations, subscription links, tokens or
   personal data — not in code, tests, logs, screenshots or issues.
2. **No telemetry, analytics or new network access** without a discussion first.
3. **Justify new dependencies** in the pull request description. Prefer the platform's standard library.
4. **Keep it small.** One change per pull request; a fix does not need a refactor next to it.

## Before you start

- Found a bug? Search the issues, then open one with the form for that repository.
- Want a feature? Open an issue and describe the problem first. A short discussion saves a rejected pull request.
- Security problem? Do not open an issue: see [SECURITY.md](SECURITY.md).

## Pull requests

- Branch from `main`.
- Use [Conventional Commits](https://www.conventionalcommits.org): `feat(core): …`, `fix(android): …`, `docs: …`.
- Run the project's checks before you push; the repository's own guide names the command.
- Explain what changed and how you checked it. Screenshots help for anything visible.

By contributing you agree that your work is released under the licence of the repository you contribute to.
Please follow the [Code of Conduct](CODE_OF_CONDUCT.md).
