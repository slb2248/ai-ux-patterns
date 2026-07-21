# Blast Radius Visualization

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/blast-radius-visualization](https://aiuxplayground.com/pattern/blast-radius-visualization)

> Preview scope before agent executes

## What it is

Blast radius visualization is an AI agent UX pattern that previews how many files, records, users, or systems an action will touch before approval. Concrete counts (“412 files across 37 folders”) beat vague progress bars that reveal scope too late.

## When to use

Essential for agentic tools, bulk automation platforms, and admin interfaces where fan-out actions need clear scope disclosure before execution to prevent accidental large-scale changes.

## When not to use

- Single-target actions where the radius is obviously one object.
- When accurate counts cannot be computed without already executing the mutation.
- Tiny hobby tools with no bulk operations.

## Anti-patterns

- Starting a bulk run with only a spinner and no pre-count.
- Underestimating counts that balloon mid-run with no re-confirmation.
- Showing technical IDs without human-readable scope maps.
- Allowing “select all matching” with no ceiling or sample preview.

## How products use it

| Product | Implementation |
|---------|----------------|
| Cursor / coding agents | Multi-file diff summaries before applying large changes. |
| CRM / support agents | Recipient or record counts before bulk message or update. |
| Cloud consoles | Resource-count previews before fleet-wide operations. |
| Design system migrate tools | Component instance counts before mass redesign apply. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Blast Radius Visualization on AI UX Playground →](https://aiuxplayground.com/pattern/blast-radius-visualization)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
