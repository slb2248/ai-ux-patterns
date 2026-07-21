# Data Ownership & Control

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/data-ownership](https://aiuxplayground.com/pattern/data-ownership)

> User control over AI data usage

## Overview

Data ownership and control is an AI UX pattern that gives users clear rights over what the product stores, trains on, shares, or remembers, export, delete, retention, and opt-outs in plain language. Trust depends on controls that are findable and actually enforceable, not buried legal copy.

## Good for

Essential for all AI applications where user trust depends on transparency and control over personal data, ensuring compliance with privacy regulations and building user confidence.

## Skip it when

- Ephemeral tools that store nothing durable and only need a clear “we don’t keep this” line.
- Enterprise admin-only consoles where end users correctly have no deletion rights.
- When legal cannot honor a control you show, never advertise deletion you cannot complete.

## Easy to get wrong

- Settings that claim “don’t train on my data” with no confirmation of scope or lag.
- Delete chat that still leaves embeddings or admin logs undisclosed.
- Dark-pattern retention defaults that require digging to turn off memory or sharing.
- Export that omits the formats users need to leave the product.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT | Data Controls for training opt-out, history, and memory management. |
| Claude | Privacy and training settings with project/workspace data boundaries. |
| Google Account | Activity and AI feature controls tied to account-wide data settings. |
| Apple Privacy Dashboard-style patterns | Permission and data-use summaries users can audit over time. |

## On the site

[Data Ownership & Control demo](https://aiuxplayground.com/pattern/data-ownership) · [more trust](https://aiuxplayground.com/patterns/trust)
