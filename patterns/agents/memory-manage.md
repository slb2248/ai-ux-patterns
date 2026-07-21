# Memory Management

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/memory-manage](https://aiuxplayground.com/pattern/memory-manage)

> Viewing what AI remembers

## What it is

Memory management is an AI UX pattern that lets users see, edit, prioritize, and delete what the assistant remembers across sessions. It turns inferred continuity into an inspectable list with clear off-ramps, so personalization does not feel like surveillance.

## When to use

Perfect for personal AI assistants, long-term agent relationships, and applications where the AI needs to remember user context across sessions.

## When not to use

- Stateless tools where remembering prior chats adds risk without value.
- Regulated contexts that forbid durable personal memory without enterprise controls.
- Products that only need short thread context, not cross-session profile memory.

## Anti-patterns

- Invisible memory that changes answers with no settings entry.
- No way to delete or export individual memories.
- Mixing declared preferences with inferred facts in one unlabeled blob.
- Turning memory off without explaining pause vs wipe.

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT | Saved memories list with search, prioritize/delete, and version restore. |
| Claude | Opt-in memory under Capabilities with import and pause-vs-reset. |
| Perplexity | Search-history memory toggle with Max-tier Brain upsell. |
| Gemini | Activity and personalization controls tied to Google account settings. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Memory Management on AI UX Playground →](https://aiuxplayground.com/pattern/memory-manage)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
