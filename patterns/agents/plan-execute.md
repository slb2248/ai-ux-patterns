# Plan & Execute

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/plan-execute](https://aiuxplayground.com/pattern/plan-execute)

> Breaking goals into steps

## What it is

Plan & Execute is an AI agent UX pattern where the agent first breaks a complex goal into an explicit, ordered list of steps, then works through that plan sequentially while showing progress. Users can review, edit, or approve the plan before execution starts, which improves reliability and gives visibility into a multi-step task before any action runs.

## When to use

Ideal for autonomous AI agents, complex task automation, and workflow tools where planning before execution improves success rates and user confidence.

## When not to use

- Single-step requests where a plan adds a review step with nothing to actually review.
- Latency-sensitive interactions where users want an immediate answer, not a proposal to approve first.
- Highly exploratory tasks where the right steps only emerge as the agent learns from early results.

## Anti-patterns

- Showing a plan once and then silently deviating from it during execution with no updated view.
- Plans so granular they bury the real decision points under dozens of trivial sub-steps.
- No way to edit or reject individual steps, only accept-all or cancel-all.
- Re-planning from scratch on every minor failure instead of adjusting the remaining steps.

## How products use it

| Product | Implementation |
|---------|----------------|
| AutoGPT | Generates a task list from a goal and executes items sequentially with visible state. |
| CrewAI | Assigns planned sub-tasks across role-based agents with a defined execution order. |
| LangChain (plan-and-execute agents) | Separates a planner step from an executor loop that carries out each planned action. |
| Cursor Agent | Drafts a todo-style plan for multi-file tasks before making edits. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Plan & Execute on AI UX Playground →](https://aiuxplayground.com/pattern/plan-execute)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
