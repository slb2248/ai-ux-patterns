# Semantic Search

**Category:** [Commerce](https://aiuxplayground.com/patterns/commerce)  
**Demo:** [aiuxplayground.com/pattern/semantic-search](https://aiuxplayground.com/pattern/semantic-search)

> Retrieve items by meaning, not keywords

## Overview

Semantic search is an AI UX pattern that retrieves results by meaning (not only keyword match) so queries like “waterproof shell for rainy hikes” surface relevant items even without exact terms. Strong products still show why a result matched and let users tighten with filters.

## Good for

Essential for e-commerce platforms, content discovery applications, and knowledge bases where users search by intent and meaning rather than exact keywords.

## Skip it when

- Tiny catalogs where keyword search already returns complete, exact sets.
- Legal or SKU lookup that must match exact identifiers, not “close enough.”
- Offline or privacy-hard clients that cannot embed or call a retrieval index.

## Easy to get wrong

- Semantic results with no keyword fallback when users search an exact ID.
- Opaque ranking with no filters, sort, or “match explanation.”
- Quietly ignoring part of a natural-language query (size, budget, brand).
- Mixing ads into the semantic set without labeling sponsorship.

## In the wild

| Product | Implementation |
|---------|----------------|
| Algolia NeuralSearch-style UX | Meaning-aware retrieval with familiar facets and query understanding. |
| Amazon | Natural-language browse and Rufus-assisted discovery over catalog search. |
| Etsy | Intent-friendly product search across messy handmade titles. |
| Shopify storefront AI search | Store-scoped semantic product find with merchant filters. |

## On the site

[Semantic Search demo](https://aiuxplayground.com/pattern/semantic-search) · [more commerce](https://aiuxplayground.com/patterns/commerce)
