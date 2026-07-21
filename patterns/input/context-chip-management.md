# Context Chip Management

**Category:** [Inputs](https://aiuxplayground.com/patterns/input)  
**Demo:** [aiuxplayground.com/pattern/context-chip-management](https://aiuxplayground.com/pattern/context-chip-management)

> Adding context sources via menu with removable chips

## Overview

Context chip management is an AI UX pattern that adds files, photos, code, or docs from a unified menu and shows each source as a removable chip in the composer. Users see and edit the exact context bundle before send instead of guessing what the model will receive.

## Good for

Perfect for AI coding assistants, knowledge management tools, and platforms where users compose queries using multiple context sources and need visibility into context composition.

## Skip it when

- Single-file upload tools where a chip list is heavier than one attachment row.
- Products that inject hidden RAG context users cannot remove.
- Voice-first surfaces with no visual chip area, use spoken confirmation instead.

## Easy to get wrong

- Chips with no remove (X) or overflow that hides active context.
- Duplicate menus (+, slash, drag-drop) that add the same source twice silently.
- Chips that rename files so users cannot verify identity.
- Sending before chips finish uploading with no disabled send state.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | + menu for files and tools; removable chips above the input. |
| Cursor | @ and attach flows that surface files/context as editable references. |
| Claude | Attach and project files represented before the turn is sent. |
| Notion AI | Page and database context selectable for a generation request. |

## On the site

[Context Chip Management demo](https://aiuxplayground.com/pattern/context-chip-management) · [more inputs](https://aiuxplayground.com/patterns/input)
