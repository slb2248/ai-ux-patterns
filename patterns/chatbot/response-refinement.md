# Response Refinement

**Category:** [Chatbot](https://aiuxplayground.com/patterns/chatbot)  
**Demo:** [aiuxplayground.com/pattern/response-refinement](https://aiuxplayground.com/pattern/response-refinement)

> Modify AI responses with contextual actions

## Overview

Response refinement is an AI UX pattern that lets users modify an existing answer with contextual actions (shorter, more formal, expand, fix tone, continue) without rewriting the whole prompt. It keeps iteration on the output rather than burying history in re-prompts.

## Good for

Critical for AI chat interfaces, content generation tools, and conversational assistants where iterative refinement improves output quality and user satisfaction.

## Skip it when

- One-shot factual lookups where refinement chrome is unused clutter.
- Code patches where structured diff review is safer than vague “make it better.”
- When the product already supports natural-language edit-selection (magic edit) on the same surface.

## Easy to get wrong

- Refinement actions that replace history with no undo or version carousel.
- Opaque “Improve” with no preview of what will change.
- Refining silently changes cited claims without updating sources.
- Too many micro-actions that bury Copy and Regenerate.

## In the wild

| Product | Implementation |
|---------|----------------|
| Gemini | Modify response actions for length, tone, and structure on answers. |
| ChatGPT | Regenerate and edit flows plus conversational refinement turns. |
| Claude | Rewrite and style adjustments via follow-ups and artifacts. |
| Notion AI | Inline improve/shorten/change-tone actions on generated text. |

## On the site

[Response Refinement demo](https://aiuxplayground.com/pattern/response-refinement) · [more chatbot](https://aiuxplayground.com/patterns/chatbot)
