# Generative UI

**Category:** [Outputs](https://aiuxplayground.com/patterns/output)  
**Interactive demo:** [https://aiuxplayground.com/pattern/gen-ui](https://aiuxplayground.com/pattern/gen-ui)

> Render interactive UI components in the answer

## What it is

Generative UI (GenUI) is an AI UX pattern where the model produces interactive interface elements (cards, forms, tables, charts, or controls) instead of (or in addition to) plain text. Users act on structured output in place, closing the gap between answer and next step.

## When to use

Perfect for rapid prototyping tools, design systems, dashboard builders, and low-code platforms where speed from concept to UI is critical.

## When not to use

- Simple Q&A where text is enough and generated widgets add noise.
- Strict design-system products that cannot safely render arbitrary generated components.
- High-security forms where model-authored fields would be unpredictable or unsafe.

## Anti-patterns

- Generating non-interactive mock UI that looks clickable but does nothing.
- Inconsistent components that break layout or accessibility every turn.
- No way to fall back to text or copy structured results out of the widget.
- Regenerating the whole UI on every keystroke with no stable state.

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT | Can render interactive canvases, tables, and app-like blocks inside chat. |
| Gemini | Produces structured maps, tables, and actionable layouts for research and planning. |
| Vercel / AI SDK demos | Streams generative UI components tied to tool results. |
| Cursor | Surfaces interactive diffs, plans, and structured agent artifacts beyond plain chat. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Generative UI on AI UX Playground →](https://aiuxplayground.com/pattern/gen-ui)**

Or browse all [Outputs patterns](https://aiuxplayground.com/patterns/output).
