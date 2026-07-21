# Plan & Execute

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/plan-execute](https://aiuxplayground.com/pattern/plan-execute)

> Breaking goals into steps

## Overview

Plan & Execute is an AI agent UX pattern where the agent first breaks a complex goal into an explicit, ordered list of steps, then works through that plan sequentially while showing progress. Users can review, edit, or approve the plan before execution starts, which improves reliability and gives visibility into a multi-step task before any action runs.

## Good for

Ideal for autonomous AI agents, complex task automation, and workflow tools where planning before execution improves success rates and user confidence.

## Skip it when

- Single-step requests where a plan adds a review step with nothing to actually review.
- Latency-sensitive interactions where users want an immediate answer, not a proposal to approve first.
- Highly exploratory tasks where the right steps only emerge as the agent learns from early results.

## Easy to get wrong

- Showing a plan once and then silently deviating from it during execution with no updated view.
- Plans so granular they bury the real decision points under dozens of trivial sub-steps.
- No way to edit or reject individual steps, only accept-all or cancel-all.
- Re-planning from scratch on every minor failure instead of adjusting the remaining steps.

## In the wild

| Product | Implementation |
|---------|----------------|
| AutoGPT | Generates a task list from a goal and executes items sequentially with visible state. |
| CrewAI | Assigns planned sub-tasks across role-based agents with a defined execution order. |
| LangChain (plan-and-execute agents) | Separates a planner step from an executor loop that carries out each planned action. |
| Cursor Agent | Drafts a todo-style plan for multi-file tasks before making edits. |

## On the site

[Plan & Execute demo](https://aiuxplayground.com/pattern/plan-execute) · [more agents](https://aiuxplayground.com/patterns/agents)
