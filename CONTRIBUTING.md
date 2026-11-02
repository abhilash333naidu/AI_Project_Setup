# Contributing

Thanks for helping improve AI Project Setup. This template is small on purpose, so changes should make it clearer or more useful without adding weight.

## Ways to contribute

- **Report a problem or suggest an improvement.** Open an issue using the feedback template in `.github/ISSUE_TEMPLATE/`. Useful details: what you were trying to do, which file was unclear, and what would have helped.
- **Improve the template.** Open a pull request (see below).
- **Share a real project.** If you adapted the template, a short note in an issue about what worked or failed is valuable.

## Before you open a pull request

1. Open an issue first for anything larger than a typo or a broken link, so the direction can be agreed.
2. Keep each pull request to one purpose.
3. Keep the template generic. Project-specific content belongs in `examples/`, not in the core `docs/`.
4. Do not commit secrets, API keys, credentials, or personal data, including in example files.

## Documentation conventions

- Core docs in `docs/` start with a `Status:` line. Keep the existing wording of the status comments unless you are changing the readiness rule itself.
- If you change a rule in `AGENTS.md`, check that `CLAUDE.md`, `.cursorrules`, `README.md`, and `docs/rules.md` still agree.
- Keep the README accurate about what the template enforces. It is written guidance for agents; it does not block them with tooling. Do not describe it otherwise.
- If you change the examples, keep them consistent with the rules in `docs/`.

## Pull request checklist

- [ ] The change has a clear purpose, described in the pull request.
- [ ] The README and any affected docs are updated.
- [ ] `CHANGELOG.md` has an entry under "Unreleased".
- [ ] You have checked the change by reading it through, and by rendering the README on GitHub if you changed Markdown layout or images.
- [ ] No secrets or personal data are included.

## Licence

By contributing, you agree that your contributions are licensed under the MIT License in `LICENSE`.
