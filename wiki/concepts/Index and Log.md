---
type: concept
title: "Index and Log"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-10-08
tags: [concept, pkm, navigation]
---

# Index and Log

Two special files that let the LLM (and you) navigate the [[LLM Wiki Pattern|wiki]] as it grows, living in the wiki layer of [[Three-Layer Architecture]]. They are the navigation layer of the [[Compounding Knowledge Artifact]] — the map to find your synthesis, not the synthesis itself. Different jobs.

## index.md — content-oriented
A catalog of everything: each page with a link, a one-line summary, optional metadata. Organized by category ([[entities/_index|entities]], [[concepts/_index|concepts]], [[sources/_index|sources]]…). Updated on every [[Ingest Query Lint|ingest]]. On a query, the LLM **reads the index first**, then drills in. Works well to ~100 sources / hundreds of pages — no [[Wiki vs RAG|embedding RAG]] needed at that scale. [[Obsidian]]'s Dataview can extend this with dynamic filtered views as the vault grows. → [[index]]

## log.md — chronological
Append-only record of what happened and when (ingests, queries, lints). Tip: consistent prefixes make it grep-able:

```
## [2026-04-02] ingest | Article Title
```
→ `grep "^## \[" log.md | tail -5` gives the last 5 operations. → [[log]]

Together they substitute for search infrastructure at small/medium scale; a dedicated engine ([[qmd]]) is added only when the wiki outgrows them. The vault they navigate is [[overview]]. See [[Karpathy - LLM Wiki]] by [[Andrej Karpathy]]. The rules governing how both files are updated on each ingest — format, required fields, commit message — live in [[meta/conventions]]. The daily running Lint record — the concrete implementation of the log.md concept across 70+ nightly passes — is archived in [[meta/maintenance/_index|Maintenance archive]].

Developing fluency with the Index and Log pattern — building clean indexes, maintaining grep-able log formats, extending with Dataview queries as the vault grows — is an active learnable skill; track that mastery in [[learning/_index|Learning]]. New navigation approaches and catalog variations (progressive disclosure, graph-backed index, filter layers) are idea-worthy sparks; file those in [[ideas/_index|Ideas]].

_← [[concepts/_index|Concepts]] · see [[projects/_index|Projects]] for the active implementation_
