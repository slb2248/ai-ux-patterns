# Scope Disclosure

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/scope-disclosure](https://aiuxplayground.com/pattern/scope-disclosure)

> Plain-language agent permissions

## Overview

Scope disclosure is an AI UX pattern that states in plain language which accounts, files, tools, and actions an agent can reach, at connect time, on demand, and when scope changes. It turns permissions into a readable contract instead of a buried OAuth dump.

## Good for

Essential for AI agents, OAuth-based assistants, and any system that acts on behalf of users, where plain-language scope disclosure builds trust and reduces post-hoc security risk.

## Skip it when

- Local toys with no external permissions to disclose.
- When legal requires full policy text but you never provide a short summary (always give both).
- One-time scripts with no retained agent identity.

## Easy to get wrong

- Allow-all modals with no capability list.
- Disclosing scope once at install and never again after expansion.
- Jargon-only scopes (“access user.info.email.write”) with no human translation.
- No place in settings to re-read current scope.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT connectors | Permission summaries when linking apps and mail. |
| Claude connectors / computer use | Capability boundaries explained around tools and browsing. |
| GitHub Apps / OAuth | Scope lists at install with account-level review. |
| Enterprise AI gateways | Admin-visible agent capability contracts per team. |

## On the site

[Scope Disclosure demo](https://aiuxplayground.com/pattern/scope-disclosure) · [more trust](https://aiuxplayground.com/patterns/trust)
