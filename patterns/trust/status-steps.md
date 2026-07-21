# Progress Steps

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/status-steps](https://aiuxplayground.com/pattern/status-steps)

> Collapsible thinking and tool traces

## Overview

Progress steps is an AI UX pattern that surfaces an agent's intermediate work, thinking, tool calls, search steps, as a collapsible trace. Collapsed by default to keep the interface calm, it expands on demand so users who want provenance or debugging detail can inspect what happened without leaving the conversation thread.

## Good for

Use when the system performs visible intermediate work (search, tools, multi-step reasoning) and you need both a calm default UI and optional transparency for verification, learning, or troubleshooting.

## Skip it when

- Single-step answers with no intermediate tool use or reasoning worth surfacing.
- Latency-critical UIs where rendering a step-by-step trace adds visual overhead to a near-instant response.
- Audiences who only care about the final answer and never want to see the underlying process.

## Easy to get wrong

- Expanding the full trace by default, burying the actual answer under process detail.
- Steps with no timestamps or duration, making it impossible to tell what took long.
- Generic step labels like "Processing" that give no real insight into what happened.
- Traces that disappear once the response finishes, preventing later review.

## In the wild

| Product | Implementation |
|---------|----------------|
| Perplexity | Collapsible "Steps" trace shows search queries and sources visited during research. |
| ChatGPT | Reasoning and tool-call summaries collapse under a "Thought for Ns" toggle. |
| Claude | Extended thinking renders as a collapsible block above the final response. |
| Cursor Agent | Tool calls and file reads appear as an expandable timeline during agent runs. |

## On the site

[Progress Steps demo](https://aiuxplayground.com/pattern/status-steps) · [more trust](https://aiuxplayground.com/patterns/trust)
