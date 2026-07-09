---
type: concept
title: "Index and Log"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-09
tags: [concept, pkm, navigation]
---

# Index and Log

Two special files that let the LLM (and you) navigate the [[LLM Wiki Pattern|wiki]] as it grows, living in the wiki layer of [[Three-Layer Architecture]]. They are the navigation layer of the [[Compounding Knowledge Artifact]] — the map to find your synthesis, not the synthesis itself. Different jobs.

## index.md — content-oriented
A catalog of everything: each page with a link, a one-line summary, optional metadata. Organized by category (entities, concepts, sources…). Updated on every [[Ingest Query Lint|ingest]]. On a query, the LLM **reads the index first**, then drills in. Works well to ~100 sources / hundreds of pages — no [[Wiki vs RAG|embedding RAG]] needed at that scale. [[Obsidian]]'s Dataview can extend this with dynamic filtered views as the vault grows. → [[index]]

## log.md — chronological
Append-only record of what happened and when (ingests, queries, lints). Tip: consistent prefixes make it grep-able:

```
## [2026-04-02] ingest | Article Title
```
→ `grep "^## \[" log.md | tail -5` gives the last 5 operations. → [[log]]

Together they substitute for search infrastructure at small/medium scale; a dedicated engine ([[qmd]]) is added only when the wiki outgrows them. See [[Karpathy - LLM Wiki]] by [[Andrej Karpathy]].
