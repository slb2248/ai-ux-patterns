# Dynamic Follow-ups

**Category:** [Inputs](https://aiuxplayground.com/patterns/input)  
**Interactive demo:** [https://aiuxplayground.com/pattern/follow-up](https://aiuxplayground.com/pattern/follow-up)

> Suggested questions

## What it is

Dynamic follow-ups is an AI UX pattern that surfaces contextually relevant next questions as clickable chips after a response. Instead of requiring users to think of what to ask next, the AI suggests 2-4 logical continuations based on the current answer, reducing cognitive load and guiding deeper exploration of a topic.

## When to use

Ideal for search engines, conversational AI tools, and discovery applications where suggesting follow-up questions guides user exploration and improves engagement.

## When not to use

- Transactional exchanges where the task is complete and further prompting would feel like padding.
- Highly personal or creative threads where generic suggested questions break the user's own train of thought.
- Answers already ending in an explicit question or call to action that a chip would duplicate.

## Anti-patterns

- Suggestions that just rephrase the previous question instead of extending it.
- The same generic chips regardless of what the answer actually covered.
- So many chips that they crowd out the actual response or next input field.
- Chips that silently send a different query than their visible label implies.

## How products use it

| Product | Implementation |
|---------|----------------|
| Perplexity | Related questions appear below each answer, generated from the answer's content. |
| Bing Copilot | Suggested follow-up prompts sit under the response as tappable chips. |
| Google AI Overviews | "People also ask"-style follow-ups extend the search session contextually. |
| ChatGPT | Contextual suggested replies occasionally appear after certain response types. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Dynamic Follow-ups on AI UX Playground →](https://aiuxplayground.com/pattern/follow-up)**

Or browse all [Inputs patterns](https://aiuxplayground.com/patterns/input).
