# Rate Limit Warnings

**Category:** [Performance](https://aiuxplayground.com/patterns/performance)  
**Demo:** [aiuxplayground.com/pattern/rate-limit-warnings](https://aiuxplayground.com/pattern/rate-limit-warnings)

> API limit alerts

## Overview

Rate limit warnings are an AI UX pattern that alerts users before they hit quota, RPM, or plan ceilings, and explains what happens next (wait, upgrade, switch model). Proactive limits prevent sudden dead ends mid-task.

## Good for

Essential for applications using AI APIs with rate limits, developer tools, and platforms where proactive limit management prevents service interruptions.

## Skip it when

- Truly unlimited internal deployments where limits never apply.
- Background batch jobs better served by queues than interactive warnings.
- When limits are so high that constant nags train users to ignore them.

## Easy to get wrong

- Failing only after submit with a cryptic HTTP 429 and no retry guidance.
- Warnings that push upgrade without showing remaining allowance.
- Inconsistent units between the warning and the billing page.
- Blocking the composer with no estimate of when capacity returns.

## In the wild

| Product | Implementation |
|---------|----------------|
| ChatGPT / Claude Pro | Usage and limit messaging when approaching plan caps. |
| Cursor | Premium model and agent usage warnings against plan quotas. |
| API consoles (OpenAI, Anthropic) | Rate limit headers and dashboard alerts for RPM/TPM. |
| Perplexity | Pro/feature gates when free limits are exhausted. |

## On the site

[Rate Limit Warnings demo](https://aiuxplayground.com/pattern/rate-limit-warnings) · [more performance](https://aiuxplayground.com/patterns/performance)
