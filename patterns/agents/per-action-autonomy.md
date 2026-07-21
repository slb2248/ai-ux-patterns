# Per-Action Autonomy

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/per-action-autonomy](https://aiuxplayground.com/pattern/per-action-autonomy)

> Autonomy scoped per capability, not per app

## Overview

Per-action autonomy is an AI agent UX pattern that sets independence per capability, not one global autopilot. Users might auto-draft email but require approval to send, or auto-commit to feature branches but never to main.

## Good for

Essential for AI coding agents, workflow automation, and productivity assistants where different actions carry different risk profiles and users need calibrated autonomy per capability, not per app.

## Skip it when

- Single-capability agents where per-action settings duplicate a global toggle.
- Audiences who will never open advanced settings; offer sensible defaults first.
- When the platform cannot enforce different policies per tool call.

## Easy to get wrong

- One “Autopilot” switch that silently enables irreversible actions.
- Per-action settings buried with no summary of current policy.
- Defaults that auto-approve send/delete on first connect.
- Policies that drift after model or connector updates without notice.

## In the wild

| Product | Implementation |
|---------|----------------|
| Email agents | Auto-draft known threads; approve send to new recipients. |
| Cursor / coding agents | Freer edits in working trees; gated pushes to protected branches. |
| ChatGPT agent mode | Differentiated confirms for browsing vs messaging vs purchases. |
| Enterprise IT bots | Auto-read; approve write to production systems. |

## On the site

[Per-Action Autonomy demo](https://aiuxplayground.com/pattern/per-action-autonomy) · [more agents](https://aiuxplayground.com/patterns/agents)
