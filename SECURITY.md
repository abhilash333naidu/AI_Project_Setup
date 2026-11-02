# Security Policy

## Supported versions

Only the latest release receives security fixes. Current release: v1.1.0.

| Version | Supported |
|---|---|
| 1.1.x (latest) | Yes |
| 1.0.x | No. Upgrade to the latest release |

## Scope

This repository is a set of Markdown files and agent instructions. It contains no executable application code. Security-relevant areas include:

- Instructions that could cause an AI agent to disclose secrets, follow untrusted content, or take actions beyond the project's intent.
- Guidance that could lead users to store credentials or personal data in `docs/`, `memory.md`, or other project files.
- Anything in the `examples/` directory that models an unsafe practice.

Security issues in the tools that agents run (your editor, your coding agent, or your own project code) should be reported to those projects.

## Reporting a vulnerability

Please do not open a public issue for a security problem.

- Use GitHub's private vulnerability reporting on this repository (Security tab, "Report a vulnerability"), if it is available.
- Otherwise, contact the maintainer privately through their GitHub profile, [@abhilash333naidu](https://github.com/abhilash333naidu).

Include: a description of the problem, the file or instruction involved, steps to reproduce, and the potential impact.

## What to expect

This is a small, maintainer-run template. Reports are read and acknowledged as soon as practical. The maintainer will confirm whether the report is in scope, fix it where appropriate, and credit the reporter if they wish.

## Handling secrets

Do not place API keys, tokens, passwords, or personal data in any file in this repository, including `docs/memory.md` and example files. If you have committed a secret by accident, revoke it first, then remove it from the history.
