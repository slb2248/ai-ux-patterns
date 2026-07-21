# Source Quality Scores

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/source-quality-scores](https://aiuxplayground.com/pattern/source-quality-scores)

> Rate source reliability

## What it is

Source quality scores are an AI UX pattern that rates reliability or quality of sources used in an answer (tier labels, scores, or badges) so users can weight provenance, not only titles. Useful when corpora mix primary docs, blogs, and unverified pages.

## When to use

Ideal for research tools, information platforms, and applications where displaying source quality scores helps users assess information credibility.

## When not to use

- Closed corpora of equally trusted internal docs where scores add noise.
- When the scoring model is opaque and frequently contradicts user judgment.
- Creative generation with no real sources.

## Anti-patterns

- Green “trusted” badges with no criteria explained.
- Scoring the domain only while citing a low-quality page on that domain.
- Hiding low-quality sources instead of showing them with a clear weak score.
- Using scores as a substitute for excerpts and links.

## How products use it

| Product | Implementation |
|---------|----------------|
| Academic / research AI (Elicit, Consensus) | Signals paper quality, citation counts, or study type beside claims. |
| Enterprise search | Ranks internal sources by freshness, ACL, and owner authority. |
| Perplexity | Source lists emphasize reputable publishers alongside raw URLs. |
| News AI products | Publisher credibility labels next to grounded summaries. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Source Quality Scores on AI UX Playground →](https://aiuxplayground.com/pattern/source-quality-scores)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
