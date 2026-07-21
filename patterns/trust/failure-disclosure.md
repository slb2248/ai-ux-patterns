# Failure Disclosure

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/failure-disclosure](https://aiuxplayground.com/pattern/failure-disclosure)

> Honest signaling of AI limitations

## What it is

Failure disclosure is an AI UX pattern that clearly signals when the system could not answer, a tool failed, confidence is too low, or results are empty, instead of writing confident prose over a miss. Distinct error states help users recover and calibrate long-term trust.

## When to use

Essential for AI search, agents, research tools, and any system where honest signaling of limitations, failed tool calls, and low-confidence outputs builds long-term user trust.

## When not to use

- Transient loading moments better served by skeletons than failure chrome.
- Soft hedges on every answer when the system did succeed; reserve failure UI for real blocks.
- Internal-only tooling where structured logs matter more than end-user failure copy.

## Anti-patterns

- Cheerful hallucination that invents sources or “completed” tool results.
- Generic “Something went wrong” with no cause or next step.
- Same visual style as a normal answer, so users miss the failure.
- Retry that loops forever without escalating or changing strategy.

## How products use it

| Product | Implementation |
|---------|----------------|
| Perplexity | States when search coverage is weak and leans on sources rather than invented claims. |
| Claude | Can decline or state uncertainty instead of fabricating when evidence is missing. |
| Cursor Agent | Surfaces blocked tool calls and failed steps in the agent trace. |
| ChatGPT | Shows clear tool or browsing failures rather than pretending the action succeeded. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Failure Disclosure on AI UX Playground →](https://aiuxplayground.com/pattern/failure-disclosure)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
