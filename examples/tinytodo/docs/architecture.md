# Architecture

Status: ready

## Overview
Single-binary Node.js CLI. Parses args, reads and writes one JSON file, prints results.

## Tech Stack
- Runtime: Node.js 20, ESM
- Language: JavaScript (no TypeScript in v1)
- Storage: `~/.tinytodo/tasks.json`
- Tests: built-in `node:test`
- Dependencies: none. Do not add any without approval.

## Project Structure
- `src/cli.js`: arg parsing and command dispatch
- `src/store.js`: read/write tasks.json (atomic write)
- `tests/`: one test file per module

## Data Flow
argv -> cli.js -> store.js -> tasks.json -> stdout

## External Dependencies
None. No network calls.

## Constraints
Must work offline. Startup under 100 ms. Corrupt JSON must not lose data: back up to `tasks.json.bak` before overwriting.