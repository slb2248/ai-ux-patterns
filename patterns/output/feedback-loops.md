# Feedback

**Category:** [Outputs](https://aiuxplayground.com/patterns/output)  
**Demo:** [aiuxplayground.com/pattern/feedback-loops](https://aiuxplayground.com/pattern/feedback-loops)

> Collect thumbs and comments to improve answers

## Overview

Feedback loops are an AI UX pattern that collect quick judgments on outputs (thumbs, ratings, flags, or “not helpful”) to improve future answers and surface quality issues. Visible, low-friction feedback is how products learn preference without a full survey.

## Good for

Essential for all AI applications where collecting user feedback enables continuous improvement and better alignment with user needs and preferences.

## Skip it when

- Internal one-off tools with no model or ranking pipeline to consume the signal.
- High-stakes decisions where a thumb is too blunt and structured review is required.
- Every micro-token during streaming; wait until the answer settles.

## Easy to get wrong

- Feedback that vanishes with no confirmation or effect the user can observe.
- Only thumbs down with no reason codes, leaving teams unable to triage.
- Forcing a rating modal after every message.
- Using feedback solely for marketing metrics while never feeding training or retrieval.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | Thumbs and optional free-text feedback on assistant messages. |
| Claude | Message-level feedback controls on responses. |
| Gemini | Positive/negative feedback and report flows on answers. |
| Perplexity | Feedback on answer quality and wrong-source issues. |

## On the site

[Feedback demo](https://aiuxplayground.com/pattern/feedback-loops) · [more outputs](https://aiuxplayground.com/patterns/output)
