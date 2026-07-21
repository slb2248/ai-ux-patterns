# Conversation Summary

**Category:** [Outputs](https://aiuxplayground.com/patterns/output)  
**Demo:** [aiuxplayground.com/pattern/conversation-summary](https://aiuxplayground.com/pattern/conversation-summary)

> Auto-summarize long chats

## Overview

Conversation summary is an AI UX pattern that auto-generates a concise overview of a long thread (decisions, action items, and topics) so users can catch up without rereading. Good summaries are refreshable, editable, and clearly marked as model-written.

## Good for

Essential for applications with long conversation threads, team collaboration tools, and knowledge management platforms where users need to quickly understand conversation context and key points.

## Skip it when

- Short chats where a summary is longer than the thread.
- Sensitive threads where summarization would expand who can see content.
- Realtime voice turns where summary should wait until a natural pause.

## Easy to get wrong

- Summaries that invent decisions not present in the thread.
- No link back to the turns that allegedly support each bullet.
- Auto-replacing the transcript without preserving the full history.
- Stale pinned summaries after the conversation continues.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | Users ask for or receive condensed recaps of long threads. |
| Claude | Project and chat summarization for long-context handoff. |
| Notion AI | Summarize page or discussion content into action-oriented briefs. |
| Slack AI | Channel and thread summaries for catch-up in busy workspaces. |

## On the site

[Conversation Summary demo](https://aiuxplayground.com/pattern/conversation-summary) · [more outputs](https://aiuxplayground.com/patterns/output)
