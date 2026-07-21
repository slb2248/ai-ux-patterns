# Time-Delayed Execution

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/time-delayed-execution](https://aiuxplayground.com/pattern/time-delayed-execution)

> Cancelable countdown before high-impact actions

## Overview

Time-delayed execution is an AI interface design pattern that runs high-impact actions on a short, visible countdown (5 seconds, 30 seconds, or several minutes) during which a single click cancels the operation. This UX pattern trades a small amount of latency for a wide margin of user control, giving users a grace period to catch mistakes, reconsider decisions, or intercept agents that are about to do the wrong thing. Popularized by Gmail Undo Send and Slack scheduled-send delay, the pattern maps directly onto agentic workflows where irreversible actions like sending emails, committing code, or charging payments benefit from a cancelable window. It is often more trustworthy than confirmation modals because it preserves flow while still offering protection.

## Good for

Essential for email clients, payment flows, agent actions, and any interface where high-impact irreversible operations benefit from a short cancelable window.

## Seen in

- Gmail Undo Send
- Slack Scheduled Send
- Cursor Agent
- Stripe Payments

## On the site

[Time-Delayed Execution demo](https://aiuxplayground.com/pattern/time-delayed-execution) · [more agents](https://aiuxplayground.com/patterns/agents)
