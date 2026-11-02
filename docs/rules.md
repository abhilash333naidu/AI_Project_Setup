# Rules

Status: draft <!-- Change to 'ready' once filled in. Agents must not code while any doc is draft. -->

This file is the source of truth for how the AI agent should behave in this project. If this file changes, the agent should adapt immediately.

## AI Agent Rules
- Always read the files in `docs/` before writing any code.
- Follow the active architectural constraints, task list, and current memory state.
- Do not introduce packages or patterns not aligned with `docs/architecture.md` and `docs/design.md`.
- Keep changes scoped to the current task in `docs/tasks.md`.
- Update `docs/tasks.md` and `docs/memory.md` after completing work.
- Do not code while any of `prd.md`, `architecture.md`, `design.md`, `rules.md` is `Status: draft`.
- Verify before marking done: run the task's acceptance check and show the output. Never tick a task on assumption.
- Stop and ask before destructive operations, scope changes, or ambiguous requirements.
- Doc precedence on conflict: `rules.md` > `architecture.md` > `prd.md` > `design.md` > `tasks.md` > `memory.md`.
- Full agent instructions live in `AGENTS.md`.

## Code Standards
<!-- Example:
- Use TypeScript for new files.
- Prefer explicit types over `any`.
- Handle errors at the boundary; don't swallow exceptions.
-->
<!-- Linting, naming, error handling, testing expectations. -->

## Commit Standards
<!-- Example:
- Conventional Commits: feat:, fix:, docs:, chore:
- Branch names: feature/, fix/, chore/
- One logical change per commit
-->
<!-- Commit message format, branch naming, PR rules. -->

## Security & Privacy
<!-- Example:
- Never commit secrets or tokens.
- Validate all user input at the boundary.
- Avoid logging sensitive data.
-->
<!-- Secrets handling, input validation, auth rules. -->

## Performance Rules
<!-- Example:
- Keep bundle size under 200KB for core UI.
- Paginate large lists; avoid loading everything at once.
-->
<!-- Budgets, pagination, caching, observability requirements. -->
