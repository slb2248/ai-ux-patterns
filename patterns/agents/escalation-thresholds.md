# Escalation Thresholds

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/escalation-thresholds](https://aiuxplayground.com/pattern/escalation-thresholds)

> Auto-demote autonomy when risk crosses a line

## Overview

Escalation thresholds are an AI agent UX pattern that defines numeric or categorical lines (dollar amount, blast radius, unknown recipient, compliance flag) beyond which autonomy drops and a human must approve. Risk triggers demotion automatically instead of relying on vibes.

## Good for

Essential for agentic commerce, finance, admin automation, and enterprise agents where unattended execution is acceptable only within a bounded envelope of risk.

## Skip it when

- Products that always require approval and have no autonomy mode to demote from.
- When thresholds cannot be measured reliably and false triggers would freeze work.
- Fully manual tools with no agent autonomy.

## Easy to get wrong

- Invisible thresholds the user cannot see or configure.
- Escalating without showing which threshold fired.
- Thresholds so low that every action escalates and autonomy is fake.
- No way for admins to set different thresholds per environment (dev vs prod).

## In the wild

| Product | Implementation |
|---------|----------------|
| Enterprise agent platforms | Policy engines that require approval above spend or data-class tiers. |
| Banking / fintech AI | Hard dollar and fraud thresholds before execution. |
| Customer support agents | Auto-escalate to humans on toxicity, VIPs, or refund limits. |
| Cloud ops agents | Prod-write thresholds that demote to plan-only mode. |

## On the site

[Escalation Thresholds demo](https://aiuxplayground.com/pattern/escalation-thresholds) · [more agents](https://aiuxplayground.com/patterns/agents)
