# Prompt Starters

**Category:** [Inputs](https://aiuxplayground.com/patterns/input)  
**Demo:** [aiuxplayground.com/pattern/empty-state](https://aiuxplayground.com/pattern/empty-state)

> Example prompts on an empty chat screen

## Overview

Prompt starters is an AI UX pattern that shows example prompts or suggested actions on an empty conversation screen, before the user has typed anything. Examples like "Write a professional email" or "Explain quantum computing" demonstrate capability and remove the blank-page problem, helping new users understand what to ask and how to phrase it.

## Good for

Essential for AI chat interfaces, writing tools, and applications where showing example prompts helps users discover capabilities and overcome the blank page problem.

## Skip it when

- Returning power users who already have a clear task; static starters become visual clutter after the first session.
- Highly specialized tools where generic starters cannot represent the narrow, expert-level queries the product expects.
- Interfaces where the input itself already has strong placeholder text doing the same job.

## Easy to get wrong

- The same four starters shown to every user regardless of their role or prior usage.
- Starters that showcase capabilities the product cannot actually deliver well yet.
- No way to dismiss or refresh starters, so they persist as noise once a user is experienced.
- Vague starters like "Ask me anything" that do not model good prompting behavior.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | Rotating example prompts appear on the empty new-chat screen. |
| Claude | Suggested prompts on first load model different task categories the assistant handles. |
| Notion AI | Empty-state suggestions demonstrate writing, summarizing, and brainstorming actions. |
| Google Gemini | Starter cards on the home screen surface varied use cases at first launch. |

## On the site

[Prompt Starters demo](https://aiuxplayground.com/pattern/empty-state) · [more inputs](https://aiuxplayground.com/patterns/input)
