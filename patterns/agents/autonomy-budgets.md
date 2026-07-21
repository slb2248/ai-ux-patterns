# Autonomy Budgets

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/autonomy-budgets](https://aiuxplayground.com/pattern/autonomy-budgets)

> Time- or action-bounded unattended runs

## What it is

Autonomy budgets grant an agent unattended runtime with hard bounds on time or action count, then pause for review. They prevent runaway loops by forcing a checkpoint instead of a blank check on time, tokens, or side effects.

## When to use

Essential for long-running AI coding agents, research agents, and autonomous workflows where bounded unattended execution prevents runaway loops and keeps humans in the loop at natural checkpoints.

## When not to use

- Single-step assistants that never run unattended.
- Fully supervised flows where every step already requires approval.
- When you only need a soft warning; use hard budget ceilings for spend, not just a timer toast.

## Anti-patterns

- Unbounded agent loops with only a cancel buried in a menu.
- Budgets that expire silently and keep going.
- No visible remaining time or step count during the run.
- Extending the budget automatically without an explicit user gesture.

## How products use it

| Product | Implementation |
|---------|----------------|
| Cursor Agent | Max iterations / run bounds before the agent stops for review. |
| Claude Code | Session and tool-use caps that surface when limits approach. |
| Devin | Work units and scoped runs instead of open-ended autonomy. |
| GitHub Actions | Job timeouts as a hard ceiling on unattended execution. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Autonomy Budgets on AI UX Playground →](https://aiuxplayground.com/pattern/autonomy-budgets)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
