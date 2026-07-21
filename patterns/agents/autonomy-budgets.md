# Autonomy Budgets

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/autonomy-budgets](https://aiuxplayground.com/pattern/autonomy-budgets)

> Time- or action-bounded unattended runs

## Overview

Autonomy budgets grant an agent unattended runtime with hard bounds on time or action count, then pause for review. They prevent runaway loops by forcing a checkpoint instead of a blank check on time, tokens, or side effects.

## Good for

Essential for long-running AI coding agents, research agents, and autonomous workflows where bounded unattended execution prevents runaway loops and keeps humans in the loop at natural checkpoints.

## Skip it when

- Single-step assistants that never run unattended.
- Fully supervised flows where every step already requires approval.
- When you only need a soft warning; use hard budget ceilings for spend, not just a timer toast.

## Easy to get wrong

- Unbounded agent loops with only a cancel buried in a menu.
- Budgets that expire silently and keep going.
- No visible remaining time or step count during the run.
- Extending the budget automatically without an explicit user gesture.

## In the wild

| Product | Implementation |
|---------|----------------|
| Cursor Agent | Max iterations / run bounds before the agent stops for review. |
| Claude Code | Session and tool-use caps that surface when limits approach. |
| Devin | Work units and scoped runs instead of open-ended autonomy. |
| GitHub Actions | Job timeouts as a hard ceiling on unattended execution. |

## On the site

[Autonomy Budgets demo](https://aiuxplayground.com/pattern/autonomy-budgets) · [more agents](https://aiuxplayground.com/patterns/agents)
