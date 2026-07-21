# Responsibility Attribution

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/responsibility-attribution](https://aiuxplayground.com/pattern/responsibility-attribution)

> Trace which agent or human caused each action

## Overview

Responsibility attribution is an AI interface design pattern that records, for every action an agent takes, which agent and which human initiated it, under which permissions, and through which delegation path, so downstream humans can answer the who-did-this question without forensic guesswork. This UX pattern turns multi-agent systems, where one agent delegates to another and on to a tool, from an attribution void into a legible chain of responsibility. Attribution lives alongside the artifact the agent produces (a commit message, a ticket comment, a system event) so that downstream reviewers, audits, and incident responders see the lineage inline rather than having to reconstruct it. The pattern is a non-negotiable building block for any agent product that acts in shared environments: without it, accountability collapses and teams cannot safely scale automation.

## Good for

Essential for multi-agent systems, enterprise automation, and shared collaborative environments where clear accountability across agents and humans is required for audits, incidents, and trust.

## Seen in

- Git Co-authored-by
- GitHub commit trailers
- Stripe Radar event logs
- Kubernetes audit logs

## On the site

[Responsibility Attribution demo](https://aiuxplayground.com/pattern/responsibility-attribution) · [more trust](https://aiuxplayground.com/patterns/trust)
