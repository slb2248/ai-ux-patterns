# Cross-Session Budget

**Category:** [Performance](https://aiuxplayground.com/patterns/performance)  
**Demo:** [aiuxplayground.com/pattern/cross-session-budget](https://aiuxplayground.com/pattern/cross-session-budget)

> Spending caps that persist across chats and devices

## Overview

Cross-session budget is an AI interface design pattern that persists spending limits across chats, sessions, users, and devices, so opening a new conversation or switching machines does not silently reset a cap the user or organization cared about. This UX pattern closes the most common leak in per-task cost controls: a ceiling that applies only to the current session and resets the moment the user starts over, which in practice means the agent can spend the cap many times over in a single day. Cross-session budgets live at the account or organization layer, aggregate usage from every surface the user operates, and persist reliably across devices. The pattern is the difference between a toy budget that only disciplines the current chat and a real one that disciplines the user's actual monthly bill.

## Good for

Essential for AI platforms, enterprise agent deployments, and consumer products where user spend accumulates across many sessions and devices, and session-scoped caps fail to reflect the real budget.

## Seen in

- OpenAI monthly caps
- Anthropic org budgets
- GitHub Copilot seat limits
- AWS organization budgets

## On the site

[Cross-Session Budget demo](https://aiuxplayground.com/pattern/cross-session-budget) · [more performance](https://aiuxplayground.com/patterns/performance)
