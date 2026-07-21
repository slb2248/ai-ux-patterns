# Interrupt and Resume

**Category:** [Chatbot](https://aiuxplayground.com/patterns/chatbot)  
**Demo:** [aiuxplayground.com/pattern/interrupt-and-resume](https://aiuxplayground.com/pattern/interrupt-and-resume)

> Stop mid-response and continue with context

## Overview

Interrupt and resume is an AI UX pattern that lets users stop generation or speech mid-turn and continue later with preserved context, what was said, what was cancelled, and where to pick up. It keeps conversations recoverable instead of forcing a full restart.

## Good for

Critical for voice assistants, long-form chat responses, and agentic chats where users need to redirect the model quickly without resetting the entire thread.

## Skip it when

- Atomic transactions that cannot partially complete (prefer full cancel + undo).
- Tiny answers that finish before an interrupt control is usable.
- Batch jobs better served by pause/checkpoint than conversational interrupt.

## Easy to get wrong

- Stop that discards the partial answer with no way to keep or edit it.
- Resume that invents continuity the model no longer has in context.
- No visible interrupted state. UI looks idle while a job still runs.
- Voice interrupt that leaves the mic hot without a clear listening indicator.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | Stop generating; edit or regenerate; voice mode barge-in. |
| Claude | Interrupt streaming replies and retry or continue the thread. |
| Voice assistants (Siri / Google / Alexa) | Barge-in to halt speech and issue a new or continued request. |
| Coding agents | Cancel a run and resume from a checkpoint or revised instruction. |

## On the site

[Interrupt and Resume demo](https://aiuxplayground.com/pattern/interrupt-and-resume) · [more chatbot](https://aiuxplayground.com/patterns/chatbot)
