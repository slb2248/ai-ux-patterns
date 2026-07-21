# Context Portability

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/context-portability](https://aiuxplayground.com/pattern/context-portability)

> Legible payloads across app boundaries

## What it is

Context portability is an AI interface design pattern that makes the payload an agent carries across app boundaries (credentials, conversation history, files, user preferences, prior tool outputs) legible and editable, so users and downstream systems can see and shape exactly what travels. This UX pattern addresses the boundary problem in cross-app agent workflows, where the richness of in-app context collapses into an opaque blob the moment the agent invokes a tool or hands off to another surface. By surfacing the handoff payload as a first-class object with structured fields, the pattern lets users inspect what the agent is about to share, redact sensitive details, and understand why a downstream app produced the result it did. It is the interoperability contract that makes composed, multi-tool agent products reviewable rather than black-boxed.

## When to use

Essential for cross-app agents, tool-calling assistants, and multi-step workflows where users benefit from inspecting and editing the context payload that travels across each boundary.

## Seen in

- Model Context Protocol
- ChatGPT Connectors
- Zapier data mapping
- Apple Shortcuts variables

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Context Portability on AI UX Playground →](https://aiuxplayground.com/pattern/context-portability)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
