---
type: concept
title: "Ingest Query Lint"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-05
tags: [concept, pkm, workflow]
---

# Ingest · Query · Lint

The three core operations of the [[LLM Wiki Pattern]], as defined by [[Andrej Karpathy]].

## Ingest
Drop a source into `.raw/`, tell the LLM to process it. It reads, discusses takeaways, writes a summary page, updates the index, updates relevant entity/concept pages, and appends to the log. **A single source touches ~10–15 pages.** Default workflow (Karpathy's preference): one source at a time, stay involved, read the summaries. Batch ingest is possible with less supervision. Data moves from the raw layer upward through [[Three-Layer Architecture]], building the [[Compounding Knowledge Artifact]] with each pass.

## Query
Ask questions against the wiki. The LLM reads the index first, drills into relevant pages, and answers **with citations**. Key insight: **good answers get filed back** as new pages (a comparison, an analysis, a discovered connection) so explorations compound instead of vanishing into chat history.

## Lint
Periodic health check. Look for: contradictions between pages, stale claims newer sources superseded, orphan pages with no inbound links, important concepts lacking their own page, missing cross-references, and data gaps fillable with a web search. Keeps the wiki healthy as it grows.

Run lint every ~10–15 ingests. Operations are recorded in [[Index and Log]]. See [[Karpathy - LLM Wiki]] by [[Andrej Karpathy]].
