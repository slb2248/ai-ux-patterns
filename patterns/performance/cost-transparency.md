# Cost Transparency

**Category:** [Performance](https://aiuxplayground.com/patterns/performance)  
**Interactive demo:** [https://aiuxplayground.com/pattern/cost-transparency](https://aiuxplayground.com/pattern/cost-transparency)

> Show operation costs

## What it is

Cost transparency is an AI UX pattern that shows the price of an operation (tokens, credits, dollars, or rate-limit units) before or as the user runs it. Visible cost helps users choose models, depth, and tools without surprise bills or silent quota burn.

## When to use

Ideal for applications with usage-based pricing, credit systems, and platforms where cost awareness helps users manage spending and optimize usage.

## When not to use

- Flat unlimited consumer plans where showing micro-costs adds anxiety with no decision value.
- Internal demos on company-paid keys where cost UI distracts from the task.
- When estimates are so wrong that displaying them destroys trust.

## Anti-patterns

- Hiding cost until after a large agent run finishes.
- Inconsistent units (credits vs dollars) across model picker and usage page.
- “Free” labeling for actions that still burn shared team quotas.
- No warning when a tool call will spend an order of magnitude more than a normal reply.

## How products use it

| Product | Implementation |
|---------|----------------|
| OpenAI / Anthropic consoles | Token and dollar usage visible per request and in billing dashboards. |
| Cursor | Surfaces premium model and agent usage against plan limits. |
| Perplexity / Claude Pro | Makes plan limits and upgraded modes legible at choice time. |
| Cloud LLM gateways | Per-team budgets and cost estimates before high-spend agent jobs. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Cost Transparency on AI UX Playground →](https://aiuxplayground.com/pattern/cost-transparency)**

Or browse all [Performance patterns](https://aiuxplayground.com/patterns/performance).
