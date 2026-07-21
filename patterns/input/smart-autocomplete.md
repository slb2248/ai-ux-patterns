# Smart Autocomplete

**Category:** [Inputs](https://aiuxplayground.com/patterns/input)  
**Demo:** [aiuxplayground.com/pattern/smart-autocomplete](https://aiuxplayground.com/pattern/smart-autocomplete)

> Context-aware autocomplete beyond text

## Overview

Smart autocomplete is an AI UX pattern that predicts the next text, code, or field value from context and offers inline acceptance (Tab, ghost text, or suggestion chips) without opening a separate chat. It accelerates composition while leaving the user in control of the caret.

## Good for

Perfect for code editors, productivity tools, and applications where context-aware autocomplete accelerates input and improves accuracy.

## Skip it when

- Fields that must stay empty until a verified source fills them (legal attestations).
- Shared screens where ghost text would leak another user’s private predictions.
- Ultra-low latency UIs that cannot afford model round-trips on every keystroke.

## Easy to get wrong

- Suggestions that auto-commit without an explicit accept gesture.
- Ghost text with contrast too low to read or too high to ignore.
- Autocomplete that overwrites multi-cursor or selected ranges unexpectedly.
- No way to disable suggestions when they become noisy.

## In the wild

| Product | Implementation |
|---------|----------------|
| GitHub Copilot | Inline code ghost text accepted with Tab in the editor. |
| Gmail Smart Compose | Phrase completions in email that users tab-accept. |
| Tabnine | IDE completions tuned to team or local code context. |
| Editor IntelliSense + AI | Symbol completion layered with AI whole-line predictions. |

## On the site

[Smart Autocomplete demo](https://aiuxplayground.com/pattern/smart-autocomplete) · [more inputs](https://aiuxplayground.com/patterns/input)
