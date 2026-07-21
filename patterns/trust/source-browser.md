# Source Browser

**Category:** [Trust](https://aiuxplayground.com/patterns/trust)  
**Interactive demo:** [https://aiuxplayground.com/pattern/source-browser](https://aiuxplayground.com/pattern/source-browser)

> Inspect source documents beside the answer

## What it is

Source browser is an AI UX pattern that shows the original documents or passages beside (or linked from) the generated answer so users can verify claims in context. Highlights map answer spans back to source excerpts, making RAG and research outputs auditable instead of black-box.

## When to use

Perfect for legal research tools, document analysis applications, and platforms where side-by-side source verification builds trust and enables fact-checking.

## When not to use

- Pure chat with no retrieval corpus, where a browser pane would be empty theater.
- Mobile chat where a persistent dual pane destroys reading space; prefer a slide-over Sources view instead.
- Creative generation tasks where “sources” would invent provenance.

## Anti-patterns

- Listing file names without showing the excerpt that grounded the claim.
- Highlights that do not match the cited sentence, training users to distrust the panel.
- Auto-opening a full-width browser that pushes the answer off-screen on every query.
- No jump-to-passage link from an inline citation chip into the browser.

## How products use it

| Product | Implementation |
|---------|----------------|
| ChatPDF / document Q&A tools | Keeps the PDF open beside answers and scrolls to cited pages. |
| Perplexity | Sources panel and previews support claim-level inspection beyond chat text. |
| Notion AI / enterprise RAG | Opens linked workspace pages or snippets that the answer drew from. |
| Legal research platforms | Dual-pane reading of opinions or filings next to AI summaries. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Source Browser on AI UX Playground →](https://aiuxplayground.com/pattern/source-browser)**

Or browse all [Trust patterns](https://aiuxplayground.com/patterns/trust).
