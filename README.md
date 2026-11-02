# AI Agent–Driven Development Setup Template

A minimal, opinionated starter template for vibe-coding and AI-agent-driven development. Use it to bootstrap new projects with a stable `docs/`-first workflow so your coding agent always has the right context.

## Who this is for

Solo developers who want to ship faster with AI coding agents, without losing track of scope, architecture, or past decisions.

## Why this exists

AI coding agents work best when they have a clear blueprint. This template separates **thinking and guardrails** from **source code**, so your agent reads intent first and stays aligned across sessions.

## What's inside

- `docs/`: the core docs layer
  - `prd.md`: product requirements and scope
  - `architecture.md`: system architecture and tech stack
  - `rules.md`: coding rules and agent guardrails
  - `design.md`: UI/UX design tokens and decisions
  - `tasks.md`: executable task checklist
  - `memory.md`: lessons learned and session memory
- `.cursorrules`: forces your AI agent to read and update `docs/`
- `.github/ISSUE_TEMPLATE`: standard feedback issue template
- `AI_Project_Setup_template.zip`: zip of the template
- `.gitignore`: sensible defaults for common stacks
- `LICENSE`: MIT license

## Quick start

1. Click **Use this template** on GitHub, or clone from the terminal:

```bash
git clone https://github.com/abhilash333naidu/AI_Project_Setup.git my-ai-project
cd my-ai-project
rm -rf .git && git init
```

The `rm -rf .git` step removes the template's git history so your project starts fresh.

2. Edit each file in `docs/` for your project.
3. Open the project in Cursor, Claude Code, or your preferred agent host.
4. Start coding. The agent reads `docs/` first and keeps `tasks.md` and `memory.md` current.

## Download ZIP

Grab the ZIP from the repo root (`AI_Project_Setup_template.zip`), or from [Releases](https://github.com/abhilash333naidu/AI_Project_Setup/releases) if a release exists.

## Contributing

Open an issue using the feedback template. Useful feedback includes:
- What was missing when you started using it
- Which docs file was unclear
- What automation would have helped

## License

MIT. See [LICENSE](LICENSE).
