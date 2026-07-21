# Semantic Search

**Category:** [Commerce](https://aiuxplayground.com/patterns/commerce)  
**Interactive demo:** [https://aiuxplayground.com/pattern/semantic-search](https://aiuxplayground.com/pattern/semantic-search)

> Retrieve items by meaning, not keywords

## What it is

Semantic search is an AI UX pattern that retrieves results by meaning (not only keyword match) so queries like “waterproof shell for rainy hikes” surface relevant items even without exact terms. Strong products still show why a result matched and let users tighten with filters.

## When to use

Essential for e-commerce platforms, content discovery applications, and knowledge bases where users search by intent and meaning rather than exact keywords.

## When not to use

- Tiny catalogs where keyword search already returns complete, exact sets.
- Legal or SKU lookup that must match exact identifiers, not “close enough.”
- Offline or privacy-hard clients that cannot embed or call a retrieval index.

## Anti-patterns

- Semantic results with no keyword fallback when users search an exact ID.
- Opaque ranking with no filters, sort, or “match explanation.”
- Quietly ignoring part of a natural-language query (size, budget, brand).
- Mixing ads into the semantic set without labeling sponsorship.

## How products use it

| Product | Implementation |
|---------|----------------|
| Algolia NeuralSearch-style UX | Meaning-aware retrieval with familiar facets and query understanding. |
| Amazon | Natural-language browse and Rufus-assisted discovery over catalog search. |
| Etsy | Intent-friendly product search across messy handmade titles. |
| Shopify storefront AI search | Store-scoped semantic product find with merchant filters. |

## Try it live

Interactive demo, screenshots, and full guidance on the site:

**[Open Semantic Search on AI UX Playground →](https://aiuxplayground.com/pattern/semantic-search)**

Or browse all [Commerce patterns](https://aiuxplayground.com/patterns/commerce).
