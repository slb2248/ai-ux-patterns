# Confidence Indicators

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/confidence-indicators](https://aiuxplayground.com/pattern/confidence-indicators)

> Visual confidence levels for outputs

## Overview

Confidence indicators are AI UX cues (scores, meters, badges, or hedging copy) that show how certain the system is about an answer or claim. They help users decide whether to trust, verify, or escalate. Critical when wrong answers are costly.

## Good for

Critical for medical tools, financial analysis platforms, and decision-support systems where visual confidence indicators help users assess information reliability.

## Skip it when

- Casual creative chat where numeric confidence adds anxiety without decision value.
- When the score is not calibrated and would systematically mislead.
- Every sentence in a long answer; prefer claim-level or answer-level cues for high-risk parts only.

## Easy to get wrong

- Decorating every reply with 97% confidence that never changes.
- Green badges on unverifiable claims with no path to sources.
- Hiding uncertainty behind confident tone while the model is guessing.
- Scores without a legend for what high vs low means in this product.

## In the wild

| Product | Implementation |
|---------|----------------|
| Google Search | Featured answers and AI Overviews pair claims with sources more than raw percentages. |
| Perplexity | Evidence-first chips and source counts act as confidence proxies. |
| Medical AI tools | Often show explicit probability or risk tiers next to recommendations. |
| Watson-style decision support | Ranked hypotheses with confidence bars for clinician review. |

## On the site

[Confidence Indicators demo](https://aiuxplayground.com/pattern/confidence-indicators) · [more trust](https://aiuxplayground.com/patterns/trust)
