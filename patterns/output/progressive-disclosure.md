# Progressive Disclosure

**Category:** [Outputs](https://aiuxplayground.com/patterns/output)  
**Demo:** [aiuxplayground.com/pattern/progressive-disclosure](https://aiuxplayground.com/pattern/progressive-disclosure)

> Gradually reveal complex information

## Overview

Progressive disclosure is an AI UX pattern that reveals complexity in stages, basic answer first, then sources, steps, tools, or advanced controls on demand. It keeps the default view calm while power users can open depth without drowning newcomers in settings and panels.

## Good for

Perfect for long-form content, research reports, and complex AI outputs where users need both high-level summaries and detailed information on demand.

## Skip it when

- Safety-critical details that must be visible before consent or execute (do not hide risk).
- Expert-only consoles where collapsing essentials adds clicks without helping novices.
- Tiny answers where “show more” is pure chrome with no extra content.

## Easy to get wrong

- Hiding irreversible side effects behind Show more or Advanced.
- Endless nested accordions that bury the primary answer.
- Different disclosure rules on mobile vs desktop with no shared hierarchy.
- Default-collapsed citations or errors that users need to trust the claim.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | Compact replies with expandable reasoning, sources, or tool details. |
| Claude | Artifacts and extended thinking open from the thread when needed. |
| Perplexity | Answer first; research steps and Links available as deeper layers. |
| Gemini | Overview-style answers with expandable related content and tools. |

## On the site

[Progressive Disclosure demo](https://aiuxplayground.com/pattern/progressive-disclosure) · [more outputs](https://aiuxplayground.com/patterns/output)
