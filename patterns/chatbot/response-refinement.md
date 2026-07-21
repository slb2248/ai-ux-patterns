# Response Refinement

**Category:** [Chatbot](https://aiuxplayground.com/patterns/chatbot)  
**Interactive demo:** [https://aiuxplayground.com/pattern/response-refinement](https://aiuxplayground.com/pattern/response-refinement)

> Modify AI responses with contextual actions

## What it is

Response refinement is an AI UX pattern that lets users modify an existing answer with contextual actions (shorter, more formal, expand, fix tone, continue) without rewriting the whole prompt. It keeps iteration on the output rather than burying history in re-prompts.

## When to use

Critical for AI chat interfaces, content generation tools, and conversational assistants where iterative refinement improves output quality and user satisfaction.

## When not to use

- One-shot factual lookups where refinement chrome is unused clutter.
- Code patches where structured diff review is safer than vague “make it better.”
- When the product already supports natural-language edit-selection (magic edit) on the same surface.

## Anti-patterns

- Refinement actions that replace history with no undo or version carousel.
- Opaque “Improve” with no preview of what will change.
- Refining silently changes cited claims without updating sources.
- Too many micro-actions that bury Copy and Regenerate.

## How products use it

| Product | Implementation |
|---------|----------------|
| Gemini | Modify response actions for length, tone, and structure on answers. |
| ChatGPT | Regenerate and edit flows plus conversational refinement turns. |
| Claude | Rewrite and style adjustments via follow-ups and artifacts. |
| Notion AI | Inline improve/shorten/change-tone actions on generated text. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Response Refinement on AI UX Playground →](https://aiuxplayground.com/pattern/response-refinement)**

Or browse all [Chatbot patterns](https://aiuxplayground.com/patterns/chatbot).
