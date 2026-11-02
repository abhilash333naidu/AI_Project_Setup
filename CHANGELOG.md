# Changelog

All notable changes to this template are recorded here. Releases are also listed on the [GitHub releases page](https://github.com/abhilash333naidu/AI_Project_Setup/releases).

## [Unreleased]

### Added
- Logo (`assets/brand-mark.svg`), hero banner (`assets/hero-banner.png`), and architecture diagram (`assets/architecture.svg`) in the README.
- Social preview image (`assets/social-preview.png`) for repository sharing.
- `CONTRIBUTING.md`, `SECURITY.md`, and this changelog.

### Changed
- README title is now "AI Project Setup", matching the repository name.
- README and `examples/README.md` state which docs carry `Status:` (`prd.md`, `architecture.md`, `design.md`, `rules.md`) and that the readiness rule is written guidance, not enforced by tooling.

### Removed
- `assets/workflow.svg`, which was not referenced anywhere.

## [1.1.0] - 2026-11-02

- `AGENTS.md` added as the canonical agent rules; `CLAUDE.md` and `.cursorrules` point to it.
- Verify-before-done and stop-and-ask gates added to agent instructions.
- `Status: draft` gate on docs.
- Filled `examples/tinytodo` docs set.
- `.gitignore` no longer ignores lockfiles.
- `.gitattributes` enforces LF line endings.
- Cross-platform quick start via `degit`.

## [1.0.0] - 2026-09-20

- Initial template release: docs-first AI agent setup scaffold.
