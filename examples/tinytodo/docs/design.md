# Design

Status: ready

## Design System
Plain terminal output. Readable, no colour dependence.

## UI Tokens
- Task line: `<id>. [ ] text` or `<id>. [x] text`
- Exit code 0 on success, 1 on user error, 2 on unexpected error

## Component Rules
- `tt list` with no tasks prints `No tasks.`
- Unknown command prints usage and exits 1.

## Copy & Tone
Short, direct. Errors say what happened and what to do: `No task with id 7. Run "tt list" to see ids.`

## Reference
None.