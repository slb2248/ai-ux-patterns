# Feedback

**Category:** [Outputs](https://aiuxplayground.com/patterns/output)  
**Interactive demo:** [https://aiuxplayground.com/pattern/feedback-loops](https://aiuxplayground.com/pattern/feedback-loops)

> Collect thumbs and comments to improve answers

## What it is

Feedback loops are an AI UX pattern that collect quick judgments on outputs (thumbs, ratings, flags, or “not helpful”) to improve future answers and surface quality issues. Visible, low-friction feedback is how products learn preference without a full survey.

## When to use

Essential for all AI applications where collecting user feedback enables continuous improvement and better alignment with user needs and preferences.

## When not to use

- Internal one-off tools with no model or ranking pipeline to consume the signal.
- High-stakes decisions where a thumb is too blunt and structured review is required.
- Every micro-token during streaming; wait until the answer settles.

## Anti-patterns

- Feedback that vanishes with no confirmation or effect the user can observe.
- Only thumbs down with no reason codes, leaving teams unable to triage.
- Forcing a rating modal after every message.
- Using feedback solely for marketing metrics while never feeding training or retrieval.

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT | Thumbs and optional free-text feedback on assistant messages. |
| Claude | Message-level feedback controls on responses. |
| Gemini | Positive/negative feedback and report flows on answers. |
| Perplexity | Feedback on answer quality and wrong-source issues. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Feedback on AI UX Playground →](https://aiuxplayground.com/pattern/feedback-loops)**

Or browse all [Outputs patterns](https://aiuxplayground.com/patterns/output).
