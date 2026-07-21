# Permission Drift Indicator

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/permission-drift-indicator](https://aiuxplayground.com/pattern/permission-drift-indicator)

> Surface accumulated agent permissions

## What it is

Permission drift indicator is an AI interface design pattern that proactively reminds users which permissions their AI agents currently hold, when those permissions were granted, and when they were last reviewed. This UX pattern combats the slow, invisible accumulation of scope that happens across months of OAuth grants, connector installs, and "just this once" approvals: the failure mode where users wake up to discover an assistant has read access to three email accounts, write access to two drives, and billing access to an account they barely remember authorizing. The indicator surfaces drift on a visible cadence (weekly digest, inline nudge, settings badge), makes each granted capability auditable, and provides one-click revoke. It is the audit-log pattern for the agent era: transparency as preventative security.

## When to use

Essential for AI agents, OAuth-based assistants, and connector ecosystems where long-lived permissions accumulate silently and users benefit from proactive visibility and review.

## Seen in

- Google Account Security
- 1Password Watchtower
- GitHub Connected Apps
- Apple Privacy Report


## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Permission Drift Indicator on AI UX Playground →](https://aiuxplayground.com/pattern/permission-drift-indicator)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
