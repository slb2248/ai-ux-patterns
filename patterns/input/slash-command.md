# Slash Commands

**Category:** [Inputs](https://aiuxplayground.com/patterns/input)  
**Interactive demo:** [https://aiuxplayground.com/pattern/slash-command](https://aiuxplayground.com/pattern/slash-command)

> Quick actions via /

## What it is

Slash commands are an AI UX pattern where typing "/" in the composer opens a menu of quick actions, templates, or model switches. They give power users keyboard-first access to capabilities without leaving the input field or navigating menus, and are common in chat, coding, and productivity tools.

## When to use

Perfect for IDEs, productivity tools, and developer environments where power users need quick keyboard-first access to AI models, templates, and actions.

## When not to use

- Consumer surfaces where most users never learn command syntax and would never discover the feature.
- Products with very few actions, where a visible button is faster to find than a hidden command.
- Mobile-first composers where a slash menu competes with the on-screen keyboard for space.

## Anti-patterns

- No visible hint that "/" does anything, leaving the feature undiscoverable.
- Commands with cryptic names and no description or preview of what they do.
- Slash menu and a separate "+" menu offering overlapping actions with no shared mental model.
- Breaking normal typing when a message legitimately starts with a "/" character.

## How products use it

| Product | Implementation |
|---------|----------------|
| Slack | Slash commands trigger integrations and actions like /remind or /poll from the message box. |
| Notion | Typing "/" opens a block-type and AI-action menu inline in the document. |
| Discord | Slash commands expose bot and app actions with argument autocomplete. |
| Midjourney | Slash commands like /imagine and /blend are the primary way to invoke generation. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Slash Commands on AI UX Playground →](https://aiuxplayground.com/pattern/slash-command)**

Or browse all [Inputs patterns](https://aiuxplayground.com/patterns/input).
