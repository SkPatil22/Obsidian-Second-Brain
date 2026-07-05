---
type: concept
title: "Compounding Knowledge Artifact"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-05
tags: [concept, pkm]
---

# Compounding Knowledge Artifact

The defining property of the [[LLM Wiki Pattern]]: the wiki is **persistent and compounding**, like interest. Each new source links into everything already there, so value grows super-linearly with size rather than staying flat (as in [[Wiki vs RAG|RAG]]).

## What "compounding" buys you
- Cross-references are **already there** when you arrive.
- Contradictions have **already been flagged**.
- The synthesis **already reflects** everything read.
- A good query answer can be **filed back** as a new page, so exploration compounds too — not just ingestion.

## What makes it possible
The bookkeeping cost is near zero because the LLM does it via the [[Ingest Query Lint]] loop (see [[concepts/LLM Wiki Pattern|division of labor]]). Humans abandon wikis when maintenance grows faster than value; here it doesn't.

Substrate: plain Markdown in a git repo → free version history. See [[Three-Layer Architecture]] and [[Karpathy - LLM Wiki]]. You read the artifact in [[Obsidian]] — graph view shows its topology; you follow wikilinks as associative trails. Navigate it via [[Index and Log]] as it grows.

When the wiki scales past ~100 sources, [[qmd]] adds a retrieval layer on top — without breaking the compounding nature of the artifact. Search becomes fast; the synthesis is still there.

The concept echoes [[Memex]] (Vannevar Bush, 1945) — a private store where connections between documents are as valuable as the documents themselves. Bush's unsolved problem was who does the maintenance. [[Andrej Karpathy]] frames the LLM as the answer: the compounding artifact is the Memex, finally realizable.
