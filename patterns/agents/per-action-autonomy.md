# Per-Action Autonomy

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/per-action-autonomy](https://aiuxplayground.com/pattern/per-action-autonomy)

> Autonomy scoped per capability, not per app

## What it is

Per-action autonomy is an AI agent UX pattern that sets independence per capability, not one global autopilot. Users might auto-draft email but require approval to send, or auto-commit to feature branches but never to main.

## When to use

Essential for AI coding agents, workflow automation, and productivity assistants where different actions carry different risk profiles and users need calibrated autonomy per capability, not per app.

## When not to use

- Single-capability agents where per-action settings duplicate a global toggle.
- Audiences who will never open advanced settings; offer sensible defaults first.
- When the platform cannot enforce different policies per tool call.

## Anti-patterns

- One “Autopilot” switch that silently enables irreversible actions.
- Per-action settings buried with no summary of current policy.
- Defaults that auto-approve send/delete on first connect.
- Policies that drift after model or connector updates without notice.

## How products use it

| Product | Implementation |
|---------|----------------|
| Email agents | Auto-draft known threads; approve send to new recipients. |
| Cursor / coding agents | Freer edits in working trees; gated pushes to protected branches. |
| ChatGPT agent mode | Differentiated confirms for browsing vs messaging vs purchases. |
| Enterprise IT bots | Auto-read; approve write to production systems. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Per-Action Autonomy on AI UX Playground →](https://aiuxplayground.com/pattern/per-action-autonomy)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
