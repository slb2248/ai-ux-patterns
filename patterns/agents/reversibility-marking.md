# Reversibility Marking

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Interactive demo:** [https://aiuxplayground.com/pattern/reversibility-marking](https://aiuxplayground.com/pattern/reversibility-marking)

> Label actions by how easily undone

## What it is

Reversibility marking is an AI agent UX pattern that tags each proposed action as fully reversible, partially reversible, or irreversible so users scrutinize risk before approve. It stops treating a draft edit and a charged payment with the same visual weight.

## When to use

Essential for agent interfaces, workflow automation, and any system that performs actions on behalf of users where surfacing reversibility helps calibrate approval attention to real risk.

## When not to use

- Flows with only reversible local edits where every tag would say the same thing.
- When you cannot honestly classify reversibility and labels would mislead.
- Emergency break-glass tools where speed beats taxonomy.

## Anti-patterns

- Uniform primary buttons for send, delete, and tweak draft.
- Calling something reversible when undo windows are tiny or unreliable.
- Hiding irreversibility in tooltip copy only.
- Marking irreversible actions lightly because they are “rare.”

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatGPT / Gemini agents | Stronger confirmation chrome for send and external actions vs drafts. |
| Cursor Agent | Diff review emphasizes file-mutating steps before apply. |
| Banking / payments AI | Irreversible transfer confirmations distinct from simulation steps. |
| Email agents | Draft vs send clearly separated with send as irreversible. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Reversibility Marking on AI UX Playground →](https://aiuxplayground.com/pattern/reversibility-marking)**

Or browse all [Agents patterns](https://aiuxplayground.com/patterns/agents).
