# CLAUDE.md

This file defines how AI coding agents should work in this repository.

## Required Reading Before Any Task

Before starting any task, read:

1. `CLAUDE.md`
2. `docs/PRD.md`
3. `docs/ARCHITECTURE.md`
4. `docs/TASKS.md`
5. `docs/AI_CHANGELOG.md`

## Working Rules

- Do not work directly on `main`.
- Use one branch per task.
- Use one Task ID per branch.
- Before editing code, output a Plan and wait for confirmation.
- Do not expand scope beyond the confirmed Task.
- Do not introduce new architecture decisions without approval.
- Do not modify production configs, secrets, auth, permissions, database migrations, or core integrations without explicit approval.

## Execution Modes

- Explore Mode: read-only.
- Plan Mode: write plan only.
- Build Mode: implement only after confirmation.
- Review Mode: review diff only.

## Completion Checklist

- Run `git status`.
- Review `git diff`.
- Run relevant tests / build / typecheck.
- Update `docs/AI_CHANGELOG.md`.
- Summarize changed files and risks.
- Do not merge automatically.
