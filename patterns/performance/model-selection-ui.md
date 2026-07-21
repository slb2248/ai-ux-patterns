# Model Selection UI

**Category:** [Performance](https://aiuxplayground.com/patterns/performance)  
**Interactive demo:** [https://aiuxplayground.com/pattern/model-selection-ui](https://aiuxplayground.com/pattern/model-selection-ui)

> Let users choose AI model (speed vs quality)

## What it is

Model selection UI lets users choose which model or tier runs a task (balancing speed, quality, cost, and tools) via a picker in the composer or settings. Clear labels beat raw model codenames so people can match the model to the job.

## When to use

Perfect for AI platforms, developer tools, and applications where letting users choose models improves performance, cost efficiency, and user satisfaction.

## When not to use

- Single-model products with no meaningful quality or cost tradeoff.
- Audiences who should never see model names; prefer automatic routing with outcome labels only.
- Every nested dialog; one composer-level control is usually enough.

## Anti-patterns

- Raw internal model IDs with no speed/quality/cost explanation.
- Hidden downgrades on free tiers without locks or honest gating.
- Changing the model mid-thread without a visible indicator.
- Equating “Pro” with quality when it only means higher rate limits.

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT | Model and mode choices with outcome-oriented labels in menus. |
| Claude | Model and effort on the composer for spend and quality before send. |
| Perplexity | Model picker on the bar; free tiers show locks on premium models. |
| Gemini | Flash nickname on the bar; picker uses plain-language thinking copy. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Model Selection UI on AI UX Playground →](https://aiuxplayground.com/pattern/model-selection-ui)**

Or browse all [Performance patterns](https://aiuxplayground.com/patterns/performance).
