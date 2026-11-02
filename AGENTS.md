# Agent Rules

Canonical instructions for any coding agent (Claude Code, Cursor, OpenCode, Codex, Kilo, etc.).
`CLAUDE.md` and `.cursorrules` point here. Edit this file only.

## Before coding
1. Read every file in `docs/`: `prd.md`, `architecture.md`, `rules.md`, `design.md`, `tasks.md`, `memory.md`.
2. If any of `prd.md`, `architecture.md`, `design.md`, `rules.md` still has `Status: draft`, stop. Tell the user which file is unfilled. Do not write code.
3. On conflict between docs, precedence is: `rules.md` > `architecture.md` > `prd.md` > `design.md` > `tasks.md` > `memory.md`. Flag the conflict to the user.

## While coding
- Work on one task from `docs/tasks.md` at a time. Stay inside its scope.
- Do not invent features, add dependencies, or change stack decisions outside `docs/` without explicit user approval.
- Stop and ask before: destructive operations (deleting files, force-push, dropping data), scope changes, ambiguous requirements, or anything touching secrets.

## Before marking done
- Run the task's acceptance check (build, tests, or the command listed in `docs/tasks.md`). Show the actual output.
- Never tick a task on assumption. If it cannot be verified, leave it unchecked and say why.

## After each task
- Update `docs/tasks.md`: check the item, move it to Completed with the date.
- Update `docs/memory.md`: current state, lessons learned, anything that broke.
- Keep `docs/memory.md` under ~150 lines. Roll older Session Notes into one short dated summary line.
