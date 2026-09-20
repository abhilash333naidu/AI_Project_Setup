# AI Agent–Driven Development Setup Template

A minimal, opinionated starter template for vibe-coding and AI-agent-driven development. Use it to bootstrap new projects with a stable `docs/`-first workflow so your coding agent always has the right context.

## Who this is for

Solo developers who want to ship faster with AI coding agents, without losing track of scope, architecture, or past decisions.

## Why this exists

AI coding agents work best when they have a clear blueprint. This template separates **thinking and guardrails** from **source code**, so your agent reads intent first and stays aligned across sessions.

## What's inside

- `docs/` — the core docs layer:
  - `prd.md` — product requirements and scope
  - `architecture.md` — system architecture and tech stack
  - `rules.md` — coding rules and agent guardrails
  - `design.md` — UI/UX design tokens and decisions
  - `tasks.md` — executable task checklist
  - `memory.md` — lessons learned and session memory
- `.cursorrules` — forces your AI agent to read and update `docs/`
- `.gitignore` — sensible defaults for common stacks
- `LICENSE` — MIT license

## Quick start

1. Create a new repo from this template using the **Use this template** button.
2. Edit each file in `docs/` for your project.
3. Open the project in Cursor, Claude Code, or your preferred agent host.
4. Start coding — the agent will read `docs/` first and keep `tasks.md` and `memory.md` current.

## Download ZIP

If you prefer a local copy, grab the latest ZIP from the [Releases](https://github.com/abhilash333naidu/AI_Project_Setup/releases) section.

## Feedback

This is a public template and it will improve with your input. If you have suggestions for wording, structure, or missing guardrails, open an issue or reach out. I’m especially interested in:
- What was missing when you started using it
- Which docs file felt unclear
- What automation would actually help
