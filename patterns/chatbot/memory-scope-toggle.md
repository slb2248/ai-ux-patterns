# Memory Scope Toggle

**Category:** [Chatbot](https://aiuxplayground.com/patterns/chatbot)  
**Demo:** [aiuxplayground.com/pattern/memory-scope-toggle](https://aiuxplayground.com/pattern/memory-scope-toggle)

> Set memory persistence per message

## Overview

Memory scope toggle is an AI UX pattern that lets users choose how far a message or fact may persist (this chat only, this project, or lasting account memory) before or as they send. It prevents accidental promotion of sensitive context into long-term memory.

## Good for

Essential for AI chat products with memory features, especially in enterprise and team contexts where retention policies vary by task and sensitivity.

## Skip it when

- Stateless products with no memory layer at all.
- Single-session throwaway chats where every option is “this chat only.”
- Enterprise modes where policy already forces chat-only and a toggle would lie.

## Easy to get wrong

- Defaulting sensitive pastes into long-term memory without a scope choice.
- Toggles that do not show what is already remembered after send.
- Silent promotion from project memory to org-wide memory.
- Scope labels users cannot distinguish (Saved vs Remembered vs Learned).

## In the wild

| Product | Implementation |
|---------|----------------|
| Claude Projects | Project-scoped knowledge separate from global chat memory. |
| ChatGPT Memory | Controls for what is remembered and ability to manage saved memories. |
| Notion AI workspaces | Workspace and page context boundaries for AI assistance. |
| Enterprise copilots | Tenant and channel scopes with admin-enforced retention. |

## On the site

[Memory Scope Toggle demo](https://aiuxplayground.com/pattern/memory-scope-toggle) · [more chatbot](https://aiuxplayground.com/patterns/chatbot)
