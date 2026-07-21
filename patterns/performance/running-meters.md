# Running Meters

**Category:** [Performance](https://aiuxplayground.com/patterns/performance)  
**Demo:** [aiuxplayground.com/pattern/running-meters](https://aiuxplayground.com/pattern/running-meters)

> Live token and cost counters during execution

## Overview

Running meters is an AI interface design pattern that displays live, ambient counters during agent execution for tokens consumed, dollars spent, and steps remaining, giving users ongoing visibility into scope and cost without demanding active attention. This UX pattern is the middle panel of the cost-awareness triad (forecast before, meter during, breakdown after), and it is the mechanism that catches divergence between prediction and reality early enough to intervene. The meter should be quiet when the run is on track and obvious when it is not, using typography and color the way a car dashboard uses a tachometer: unobtrusive at cruising speed, unmistakable in the red. Well-designed meters also expose the unit the user actually cares about (dollars, not just tokens, when a bill is attached) and update at a cadence that matches the speed of the underlying work.

## Good for

Essential for AI coding agents, research tools, and any long-running automation where users benefit from ambient visibility into token spend and progress while execution is in flight.

## Seen in

- Cursor token meter
- Claude Code usage panel
- OpenAI Playground meter
- Vercel usage dashboard

## On the site

[Running Meters demo](https://aiuxplayground.com/pattern/running-meters) · [more performance](https://aiuxplayground.com/patterns/performance)
