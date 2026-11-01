---
slug: stack-adoption
status: idea
---
# Stack adoption

## Outcome

Adopt the base stack for Google Workspace MCP.

## Approach

Add mise and Lefthook. Without this, Google Workspace MCP lacks the shared task and hook entry points that enforce stack drift checks and project verification.

## Acceptance

- `/stack check` reports 0 drift.
- `mise run check test` passes.

## Run

- 2026-11-01 — Captured from the [Stacks Plan](https://github.com/kickinrad/workflows/blob/main/plans/stacks_plan.md).

## Related

- [Stacks Plan](https://github.com/kickinrad/workflows/blob/main/plans/stacks_plan.md)
