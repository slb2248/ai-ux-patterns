# Reversibility Marking

**Category:** [Agents](https://aiuxplayground.com/patterns/agents)  
**Demo:** [aiuxplayground.com/pattern/reversibility-marking](https://aiuxplayground.com/pattern/reversibility-marking)

> Label actions by how easily undone

## Overview

Reversibility marking is an AI agent UX pattern that tags each proposed action as fully reversible, partially reversible, or irreversible so users scrutinize risk before approve. It stops treating a draft edit and a charged payment with the same visual weight.

## Good for

Essential for agent interfaces, workflow automation, and any system that performs actions on behalf of users where surfacing reversibility helps calibrate approval attention to real risk.

## Skip it when

- Flows with only reversible local edits where every tag would say the same thing.
- When you cannot honestly classify reversibility and labels would mislead.
- Emergency break-glass tools where speed beats taxonomy.

## Easy to get wrong

- Uniform primary buttons for send, delete, and tweak draft.
- Calling something reversible when undo windows are tiny or unreliable.
- Hiding irreversibility in tooltip copy only.
- Marking irreversible actions lightly because they are “rare.”

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT / Gemini agents | Stronger confirmation chrome for send and external actions vs drafts. |
| Cursor Agent | Diff review emphasizes file-mutating steps before apply. |
| Banking / payments AI | Irreversible transfer confirmations distinct from simulation steps. |
| Email agents | Draft vs send clearly separated with send as irreversible. |

## On the site

[Reversibility Marking demo](https://aiuxplayground.com/pattern/reversibility-marking) · [more agents](https://aiuxplayground.com/patterns/agents)
