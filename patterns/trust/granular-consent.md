# Granular Consent

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/granular-consent](https://aiuxplayground.com/pattern/granular-consent)

> Per-capability toggles, not bundled grants

## What it is

Granular consent is an AI UX pattern that splits agent permissions into per-capability toggles (read vs send email, view vs book calendar) instead of one all-or-nothing grant. Users authorize least privilege and revoke pieces without resetting the whole integration.

## When to use

Essential for AI assistants, enterprise agents, and connector ecosystems where least-privilege permissions reduce risk and let users tailor scope to the specific task without losing the rest of the integration.

## When not to use

- Tiny prototypes with a single harmless capability where toggles add clutter.
- Environments that only support coarse OAuth scopes and cannot honor fine toggles.
- One-shot local tools with no persisted permissions.

## Anti-patterns

- A single “Allow all” default that collapses granularity.
- Toggles that look independent but still require re-auth of everything on change.
- No plain-language description of what each capability can do.
- Hiding previously granted scopes so users cannot audit them later.

## How products use it

| Product | Implementation |
|---------|----------------|
| GitHub Apps | Fine-grained repository and permission scopes at install time. |
| Google Workspace add-ons | Per-API scopes rather than blanket account access. |
| iOS / macOS privacy panes | Per-capability access to photos, mic, and screen recording. |
| ChatGPT / Claude connectors | Connector permissions broken into discrete actions where platforms allow. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Granular Consent on AI UX Playground →](https://aiuxplayground.com/pattern/granular-consent)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
