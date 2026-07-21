# Tool Use

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/tool-use](https://aiuxplayground.com/pattern/tool-use)

> Visualizing AI using external tools

## What it is

Tool use is an AI UX pattern that visualizes when the model calls external tools (search, code execution, browsers, APIs, or connectors) and what those tools returned. Users see capability in action rather than a silent black box between prompt and answer.

## When to use

Perfect for AI agent platforms, plugin systems, and tools where transparency about external tool usage enhances user trust and understanding.

## When not to use

- Single-tool products where the only verb is already obvious and chrome would clutter chat.
- Latency-critical mobile replies where each tool badge delays perceived completion.
- Background jobs users should not micro-manage; prefer a summary after completion.

## Anti-patterns

- Silent tool calls that change data with no indicator in the thread.
- Fake “Searching…” states when no tool actually ran.
- Dumping raw JSON tool payloads into the user-facing answer.
- No link from a tool step to the artifact it produced (file, citation, diff).

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT | Shows browsing, code, or connector tool activity during agentic runs. |
| Claude | Surfaces tool use (computer, search, skills) in the activity trail. |
| Cursor | Displays terminal, file, and browser tool steps while the agent works. |
| Perplexity | Makes search/research steps visible as the answer is grounded. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Tool Use on AI UX Playground →](https://aiuxplayground.com/pattern/tool-use)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
