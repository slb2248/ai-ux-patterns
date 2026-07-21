# Fact-Checking Indicators

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Demo:** [aiuxplayground.com/pattern/fact-checking-indicators](https://aiuxplayground.com/pattern/fact-checking-indicators)

> Real-time fact-checking status

## Overview

Fact-checking indicators are an AI UX pattern that surfaces verification status on claims (checking, supported, disputed, or unverified) while or after an answer streams. They help users calibrate trust beyond raw confidence scores by tying status to evidence workflows.

## Good for

Essential for information platforms, research tools, and applications where real-time fact-checking helps users assess the reliability of AI-generated claims.

## Skip it when

- Creative writing where factual verification is not the job.
- Offline models with no retrieval or checker backends.
- Dense UIs where per-claim badges destroy readability, prefer a single review pass.

## Easy to get wrong

- Green checkmarks without links to evidence.
- Indicators that finish before retrieval does (fake certainty).
- Only flagging false claims while leaving unverifiable ones unmarked.
- Mixing sponsored or SEO junk sources into “verified” states.

## In the wild

| Product | Implementation |
|---------|----------------|
| Perplexity | Answer with source-backed claims and clear research-in-progress states. |
| Google Search / AI features | Overview claims paired with supporting result evidence. |
| Dedicated fact-checking tools | Claim lists with supported/disputed labels and source diffs. |
| Research assistants | Per-sentence verification passes after draft generation. |

## On the site

[Fact-Checking Indicators demo](https://aiuxplayground.com/pattern/fact-checking-indicators) · [more trust](https://aiuxplayground.com/patterns/trust)
