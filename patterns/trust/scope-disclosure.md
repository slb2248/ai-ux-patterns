# Scope Disclosure

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/scope-disclosure](https://aiuxplayground.com/pattern/scope-disclosure)

> Plain-language agent permissions

## What it is

Scope disclosure is an AI UX pattern that states in plain language which accounts, files, tools, and actions an agent can reach, at connect time, on demand, and when scope changes. It turns permissions into a readable contract instead of a buried OAuth dump.

## When to use

Essential for AI agents, OAuth-based assistants, and any system that acts on behalf of users, where plain-language scope disclosure builds trust and reduces post-hoc security risk.

## When not to use

- Local toys with no external permissions to disclose.
- When legal requires full policy text but you never provide a short summary (always give both).
- One-time scripts with no retained agent identity.

## Anti-patterns

- Allow-all modals with no capability list.
- Disclosing scope once at install and never again after expansion.
- Jargon-only scopes (“access user.info.email.write”) with no human translation.
- No place in settings to re-read current scope.

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT connectors | Permission summaries when linking apps and mail. |
| Claude connectors / computer use | Capability boundaries explained around tools and browsing. |
| GitHub Apps / OAuth | Scope lists at install with account-level review. |
| Enterprise AI gateways | Admin-visible agent capability contracts per team. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Scope Disclosure on AI UX Playground →](https://aiuxplayground.com/pattern/scope-disclosure)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
