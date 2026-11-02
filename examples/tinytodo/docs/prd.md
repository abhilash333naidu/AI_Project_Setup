# Product Requirements

Status: ready

## Problem
Developers keep todo lists in browser tabs and chat apps. Lists drift, duplicate, and get lost. They want a list that lives next to the code and works offline.

## Target User
Solo developer working in a terminal.

## Key Features
- [ ] `tt add "text"`: add a task
- [ ] `tt list`: show open tasks with numeric ids
- [ ] `tt done <id>`: complete a task
- [ ] `tt rm <id>`: delete a task
- [ ] Data stored in one local JSON file

## Success Criteria
- Add, list, complete and remove a task in under 10 seconds from a fresh install.
- All commands work with no network.
- `npm test` passes.

## Out of Scope
Sync, accounts, due dates, tags, GUI, multi-user. Not in v1.