# Tasks

## Active
- [ ] Implement `store.js` read/write with atomic write and `.bak` backup
  - Accept: `node --test tests/store.test.js` passes
- [ ] Implement `tt add` and `tt list`
  - Accept: `node src/cli.js add "x" && node src/cli.js list` prints `1. [ ] x`

## Backlog
- [ ] `tt done <id>`
  - Accept: task shows `[x]` in `tt list`
- [ ] `tt rm <id>`
  - Accept: task absent from `tt list`; unknown id exits 1 with message
- [ ] README with install and usage

## Completed
- 2026-11-02: Docs scaffold filled in