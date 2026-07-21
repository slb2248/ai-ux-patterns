# Confidence Score

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/confidence-score](https://aiuxplayground.com/pattern/confidence-score)

> Show how sure the model is about a claim

## Overview

Confidence score is an AI UX pattern that displays the model’s estimated certainty as a percentage, bar, or labeled level next to an answer. It helps users decide when to trust, verify, or escalate, and is especially useful in high-stakes domains where silent certainty is risky.

## Good for

Critical for medical, legal, financial, and other high-stakes applications where users need to assess the reliability of AI-generated information.

## Skip it when

- Creative or open-ended generation where numeric confidence is poorly calibrated and can fake precision.
- Consumer chat where users ignore scores and the UI cost outweighs the rare useful signal.
- Surfaces that already use richer uncertainty patterns (ranges, alternatives, ask-to-confirm) that a single percentage would oversimplify.

## Easy to get wrong

- Showing 90%+ on almost every answer, training users to ignore the score.
- A score with no guidance on what low confidence should trigger (verify, ask, or human review).
- Confusing model-internal logits with human-interpretable reliability.
- Using confidence as a substitute for citations or source links when claims need provenance.

## In the wild

| Product | Implementation |
|---------|----------------|
| Watson / clinical decision support | Surfaces confidence or evidence strength next to diagnostic or research suggestions. |
| Google Search (featured / AI answers) | Uses softer certainty framing and source backing rather than a raw probability alone. |
| Legal research tools | Pairs ranked relevance or confidence with links into primary documents. |
| Enterprise RAG copilots | Shows low-confidence states when retrieval coverage is thin so users escalate. |


## On the site

[Confidence Score demo](https://aiuxplayground.com/pattern/confidence-score) · [more trust](https://aiuxplayground.com/patterns/trust)
