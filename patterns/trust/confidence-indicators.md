# Confidence Indicators

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/confidence-indicators](https://aiuxplayground.com/pattern/confidence-indicators)

> Visual confidence levels for outputs

## What it is

Confidence indicators are AI UX cues (scores, meters, badges, or hedging copy) that show how certain the system is about an answer or claim. They help users decide whether to trust, verify, or escalate. Critical when wrong answers are costly.

## When to use

Critical for medical tools, financial analysis platforms, and decision-support systems where visual confidence indicators help users assess information reliability.

## When not to use

- Casual creative chat where numeric confidence adds anxiety without decision value.
- When the score is not calibrated and would systematically mislead.
- Every sentence in a long answer; prefer claim-level or answer-level cues for high-risk parts only.

## Anti-patterns

- Decorating every reply with 97% confidence that never changes.
- Green badges on unverifiable claims with no path to sources.
- Hiding uncertainty behind confident tone while the model is guessing.
- Scores without a legend for what high vs low means in this product.

## How products use it

| Product | Implementation |
|---------|----------------|
| Google Search | Featured answers and AI Overviews pair claims with sources more than raw percentages. |
| Perplexity | Evidence-first chips and source counts act as confidence proxies. |
| Medical AI tools | Often show explicit probability or risk tiers next to recommendations. |
| Watson-style decision support | Ranked hypotheses with confidence bars for clinician review. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Confidence Indicators on AI UX Playground →](https://aiuxplayground.com/pattern/confidence-indicators)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
