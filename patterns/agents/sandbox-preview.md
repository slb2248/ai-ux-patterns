# Sandbox Preview

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/sandbox-preview](https://aiuxplayground.com/pattern/sandbox-preview)

> Dry-run plan with explicit side effects before execute

## Overview

Sandbox preview is an AI agent UX pattern that dry-runs a plan (showing intended side effects, diffs, or receipts) before execution. Users inspect what would change in a safe staging context, then approve, edit, or cancel the real run.

## Good for

Essential for agentic automation, bulk admin tools, and cross-app workflows where users need to trust a manifest of effects before granting execution rights.

## Skip it when

- Read-only assistants with no side effects to preview.
- Trivial single-line edits where a full sandbox is slower than an inline diff.
- When the sandbox cannot faithfully mirror production permissions, false previews are worse than none.

## Easy to get wrong

- Previews that omit irreversible effects present in the real plan.
- Execute buttons that skip sandbox after the first approval forever.
- Sandboxes that mutate production data “just a little.”
- Walls of logs with no human-readable summary of blast radius.

## In the wild

| Product | Implementation |
|---------|----------------|
| Terraform plan | Infrastructure dry-run listing creates/updates/destroys before apply. |
| CI dry runs | Pipeline simulation or plan jobs before merging agent changes. |
| Email merge previews | Sample personalized messages before bulk send. |
| Agent plan-then-act modes | Visible plan and file diffs prior to apply in coding agents. |

## On the site

[Sandbox Preview demo](https://aiuxplayground.com/pattern/sandbox-preview) · [more agents](https://aiuxplayground.com/patterns/agents)
