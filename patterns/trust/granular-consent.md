# Granular Consent

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/granular-consent](https://aiuxplayground.com/pattern/granular-consent)

> Per-capability toggles, not bundled grants

## Overview

Granular consent is an AI UX pattern that splits agent permissions into per-capability toggles (read vs send email, view vs book calendar) instead of one all-or-nothing grant. Users authorize least privilege and revoke pieces without resetting the whole integration.

## Good for

Essential for AI assistants, enterprise agents, and connector ecosystems where least-privilege permissions reduce risk and let users tailor scope to the specific task without losing the rest of the integration.

## Skip it when

- Tiny prototypes with a single harmless capability where toggles add clutter.
- Environments that only support coarse OAuth scopes and cannot honor fine toggles.
- One-shot local tools with no persisted permissions.

## Easy to get wrong

- A single “Allow all” default that collapses granularity.
- Toggles that look independent but still require re-auth of everything on change.
- No plain-language description of what each capability can do.
- Hiding previously granted scopes so users cannot audit them later.

## In the wild

| Product | Implementation |
|---------|----------------|
| GitHub Apps | Fine-grained repository and permission scopes at install time. |
| Google Workspace add-ons | Per-API scopes rather than blanket account access. |
| iOS / macOS privacy panes | Per-capability access to photos, mic, and screen recording. |
| ChatGPT / Claude connectors | Connector permissions broken into discrete actions where platforms allow. |

## On the site

[Granular Consent demo](https://aiuxplayground.com/pattern/granular-consent) · [more trust](https://aiuxplayground.com/patterns/trust)
