# Failure Disclosure

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/failure-disclosure](https://aiuxplayground.com/pattern/failure-disclosure)

> Honest signaling of AI limitations

## Overview

Failure disclosure is an AI UX pattern that clearly signals when the system could not answer, a tool failed, confidence is too low, or results are empty, instead of writing confident prose over a miss. Distinct error states help users recover and calibrate long-term trust.

## Good for

Essential for AI search, agents, research tools, and any system where honest signaling of limitations, failed tool calls, and low-confidence outputs builds long-term user trust.

## Skip it when

- Transient loading moments better served by skeletons than failure chrome.
- Soft hedges on every answer when the system did succeed; reserve failure UI for real blocks.
- Internal-only tooling where structured logs matter more than end-user failure copy.

## Easy to get wrong

- Cheerful hallucination that invents sources or “completed” tool results.
- Generic “Something went wrong” with no cause or next step.
- Same visual style as a normal answer, so users miss the failure.
- Retry that loops forever without escalating or changing strategy.

## In the wild

| Product | Implementation |
|---------|----------------|
| Perplexity | States when search coverage is weak and leans on sources rather than invented claims. |
| Claude | Can decline or state uncertainty instead of fabricating when evidence is missing. |
| Cursor Agent | Surfaces blocked tool calls and failed steps in the agent trace. |
| ChatGPT | Shows clear tool or browsing failures rather than pretending the action succeeded. |

## On the site

[Failure Disclosure demo](https://aiuxplayground.com/pattern/failure-disclosure) · [more trust](https://aiuxplayground.com/patterns/trust)
