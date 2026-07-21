# Suggest / Confirm / Execute

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/suggest-confirm-execute](https://aiuxplayground.com/pattern/suggest-confirm-execute)

> Three autonomy modes for AI agents

## Overview

Suggest / confirm / execute is an AI agent UX pattern that offers three autonomy modes: the agent only proposes (suggest) asks before acting (confirm) or runs with permission already granted (execute). Users pick the mode that matches risk so control scales with stakes instead of a single autopilot switch.

## Good for

Essential for AI coding agents, workflow automation, and any interface where users need explicit control over how independently an AI acts on their behalf.

## Skip it when

- Single low-stakes draft tools where confirm always and execute never is enough.
- Fully attended interactive editors where every keystroke is already human-driven.
- Regulated flows that legally require confirm for every side effect, expose confirm only, not execute.

## Easy to get wrong

- A global Autopilot that silently includes irreversible execute actions.
- Mode labels without showing what will run (tools, targets, blast radius).
- Defaulting newcomers to execute on first session.
- Switching modes mid-run without pausing or re-disclosing side effects.

## In the wild

| Product | Implementation |
|---------|----------------|
| Cursor Agent | Plan and ask before apply vs freer edit modes with reviewable diffs. |
| GitHub Copilot Workspace | Proposal and plan stages before merging agent-authored changes. |
| Claude Code | Permission prompts for tool use vs trusted local edit sessions. |
| Devin | Staged plans and human gates before long autonomous coding runs. |

## On the site

[Suggest / Confirm / Execute demo](https://aiuxplayground.com/pattern/suggest-confirm-execute) · [more agents](https://aiuxplayground.com/patterns/agents)
