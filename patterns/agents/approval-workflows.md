# Approval Workflows

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/approval-workflows](https://aiuxplayground.com/pattern/approval-workflows)

> Human approval gates

## Overview

Approval workflows are an AI agent UX pattern that routes consequential actions through human review gates (single or multi-step) before execution. They formalize human-in-the-loop as a process (who approves, what is shown, what happens on reject) rather than a one-off confirm button.

## Good for

Essential for enterprise applications, content management systems, and critical workflows where human approval ensures quality, compliance, and safety before execution.

## Skip it when

- Low-stakes drafts where constant approvals slow teams without reducing real risk.
- Fully reversible local edits better served by undo than a formal approval queue.
- Solo consumer tools with no reviewer role; use a simpler confirm card instead.

## Easy to get wrong

- Approvals that hide the payload (diff, email, amount) being authorized.
- Serial approvals that timeout with no escalation or cancel state.
- Auto-approve after N seconds without an explicit user preference.
- Reject with no feedback path, so the agent cannot learn what to change.

## In the wild

| Product | Implementation |
|---------|----------------|
| GitHub / Copilot Workspace | Human review of PRs or agent diffs before merge. |
| Enterprise IT / identity tools | Multi-step approval for access and agent permission grants. |
| ChatGPT / Gemini agents | Send and action gates before email or external side effects. |
| Zapier / workflow builders | Human approval steps mid-automation before continuing. |

## On the site

[Approval Workflows demo](https://aiuxplayground.com/pattern/approval-workflows) · [more agents](https://aiuxplayground.com/patterns/agents)
