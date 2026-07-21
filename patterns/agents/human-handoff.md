# Human Handoff

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/human-handoff](https://aiuxplayground.com/pattern/human-handoff)

> Escalating to humans

## Overview

Human handoff is an AI UX pattern that enables a graceful escalation from an AI agent to a human when the agent is uncertain, blocked, or reaches a situation requiring human judgment. It preserves conversation context across the transition so users are not forced to repeat themselves, maintaining trust by guaranteeing a path to resolution.

## Good for

Essential for customer support systems, enterprise AI applications, and critical workflows where human oversight ensures reliable outcomes.

## Skip it when

- Fully deterministic tasks where the agent either succeeds or fails cleanly with no gray area needing judgment.
- Products with no human support layer available; promising a handoff that leads nowhere is worse than none.
- Low-stakes interactions where a "try again" or "rephrase" prompt resolves the issue faster than an escalation.

## Easy to get wrong

- Dropping the user into a fresh support queue that has no memory of the AI conversation.
- No visible signal that a handoff happened, leaving users unsure whether they are still talking to the bot.
- Escalating too late, only after several failed AI attempts have already frustrated the user.
- Handoff triggers so broad that trivial questions get routed to a human unnecessarily.

## In the wild

| Product | Implementation |
|---------|----------------|
| Intercom | AI agent escalates to a human teammate with full conversation history attached. |
| Zendesk | Bot-to-agent handoff preserves ticket context and prior AI-suggested resolutions. |
| Drift | Conversational routing rules hand off qualified conversations to sales reps. |
| LivePerson | Confidence-based escalation shifts conversations from bot to human agents. |

## On the site

[Human Handoff demo](https://aiuxplayground.com/pattern/human-handoff) · [more agents](https://aiuxplayground.com/patterns/agents)
