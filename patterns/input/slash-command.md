# Slash Commands

**Category:** [Inputs](https://aiuxplayground.com/patterns/input)  
**Demo:** [aiuxplayground.com/pattern/slash-command](https://aiuxplayground.com/pattern/slash-command)

> Quick actions via /

## Overview

Slash commands are an AI UX pattern where typing "/" in the composer opens a menu of quick actions, templates, or model switches. They give power users keyboard-first access to capabilities without leaving the input field or navigating menus, and are common in chat, coding, and productivity tools.

## Good for

Perfect for IDEs, productivity tools, and developer environments where power users need quick keyboard-first access to AI models, templates, and actions.

## Skip it when

- Consumer surfaces where most users never learn command syntax and would never discover the feature.
- Products with very few actions, where a visible button is faster to find than a hidden command.
- Mobile-first composers where a slash menu competes with the on-screen keyboard for space.

## Easy to get wrong

- No visible hint that "/" does anything, leaving the feature undiscoverable.
- Commands with cryptic names and no description or preview of what they do.
- Slash menu and a separate "+" menu offering overlapping actions with no shared mental model.
- Breaking normal typing when a message legitimately starts with a "/" character.

## In the wild

| Product | Implementation |
|---------|----------------|
| Slack | Slash commands trigger integrations and actions like /remind or /poll from the message box. |
| Notion | Typing "/" opens a block-type and AI-action menu inline in the document. |
| Discord | Slash commands expose bot and app actions with argument autocomplete. |
| Midjourney | Slash commands like /imagine and /blend are the primary way to invoke generation. |

## On the site

[Slash Commands demo](https://aiuxplayground.com/pattern/slash-command) · [more inputs](https://aiuxplayground.com/patterns/input)
