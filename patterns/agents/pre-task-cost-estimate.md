# Pre-Task Cost Estimate

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/pre-task-cost-estimate](https://aiuxplayground.com/pattern/pre-task-cost-estimate)

> Forecast tokens, dollars, and time before run

## Overview

Pre-task cost estimate is an AI interface design pattern that displays a forecast of the expected cost of an agent run (tokens, dollars, wall-clock minutes) before the user clicks to execute. This UX pattern makes spending legible in the same terms the user is about to commit to, replacing the single "Run" button that burns an unknown amount of budget in the background with a transparent scope and spend preview. Estimates are shown as ranges with the precision the system can honestly provide, updated if the plan changes mid-flight, and reconciled against actuals post-run so users calibrate future expectations. The pattern is foundational to cost-aware agent UX: agents are the first class of software where a loop can consume unbounded money without the user realizing, and forecasting is the first line of defense.

## Good for

Essential for AI coding agents, research agents, and long-running automation where forecasting cost and duration before execution prevents budget overruns and sets honest expectations.

## Seen in

- Cursor Agent
- Claude Code
- Devin
- OpenAI Assistants API

## On the site

[Pre-Task Cost Estimate demo](https://aiuxplayground.com/pattern/pre-task-cost-estimate) · [more agents](https://aiuxplayground.com/patterns/agents)
