# Approval Workflows

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/approval-workflows](https://aiuxplayground.com/pattern/approval-workflows)

> Human approval gates

## What it is

Approval workflows are an AI agent UX pattern that routes consequential actions through human review gates (single or multi-step) before execution. They formalize human-in-the-loop as a process (who approves, what is shown, what happens on reject) rather than a one-off confirm button.

## When to use

Essential for enterprise applications, content management systems, and critical workflows where human approval ensures quality, compliance, and safety before execution.

## When not to use

- Low-stakes drafts where constant approvals slow teams without reducing real risk.
- Fully reversible local edits better served by undo than a formal approval queue.
- Solo consumer tools with no reviewer role; use a simpler confirm card instead.

## Anti-patterns

- Approvals that hide the payload (diff, email, amount) being authorized.
- Serial approvals that timeout with no escalation or cancel state.
- Auto-approve after N seconds without an explicit user preference.
- Reject with no feedback path, so the agent cannot learn what to change.

## How products use it

| Product | Implementation |
|---------|----------------|
| GitHub / Copilot Workspace | Human review of PRs or agent diffs before merge. |
| Enterprise IT / identity tools | Multi-step approval for access and agent permission grants. |
| ChatGPT / Gemini agents | Send and action gates before email or external side effects. |
| Zapier / workflow builders | Human approval steps mid-automation before continuing. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Approval Workflows on AI UX Playground →](https://aiuxplayground.com/pattern/approval-workflows)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
