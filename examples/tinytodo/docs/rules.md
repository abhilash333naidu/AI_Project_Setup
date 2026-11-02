# Rules

Status: ready

## AI Agent Rules
- Always read the files in `docs/` before writing any code.
- Follow the active architectural constraints, task list, and current memory state.
- Do not introduce packages or patterns not aligned with `docs/architecture.md` and `docs/design.md`.
- Keep changes scoped to the current task in `docs/tasks.md`.
- Update `docs/tasks.md` and `docs/memory.md` after completing work.
- Do not code while any of `prd.md`, `architecture.md`, `design.md`, `rules.md` is `Status: draft`.
- Verify before marking done: run the task's acceptance check and show the output.
- Stop and ask before destructive operations, scope changes, or ambiguous requirements.

## Code Standards
- ES modules, `const` by default, no `any`-style shortcuts.
- Functions under 40 lines. Errors thrown with a clear message, caught once in `cli.js`.
- Every exported function has a test.

## Commit Standards
- Conventional Commits: `feat:`, `fix:`, `docs:`, `chore:`.
- One logical change per commit.

## Security & Privacy
- Never read or write outside `~/.tinytodo/`.
- No telemetry.

## Performance Rules
- No synchronous work beyond a single file read and write per command.