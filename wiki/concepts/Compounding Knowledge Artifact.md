---
type: concept
title: "Compounding Knowledge Artifact"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-10-07
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

The concept echoes [[Memex]] (Vannevar Bush, 1945) — a private store where connections between documents are as valuable as the documents themselves. Bush's unsolved problem was who does the maintenance. [[Andrej Karpathy]] frames the LLM as the answer: the compounding artifact is the Memex, finally realizable — and [[overview|this vault]] is that artifact, growing session by session. The staged build-out is in [[Second Brain Roadmap]]; the daily health ledger in [[meta/maintenance/_index|Maintenance archive]]. The raw material that feeds the artifact — every source that has been ingested — is cataloged in [[sources/_index|Sources]]; the extracted people, tools, and places each ingest produces are in [[entities/_index|Entities]].

Understanding and maximizing the compounding dynamics — when to file a query answer back as a page, how to amplify cross-linking, how synthesis builds with each ingest — is active skill-building; track that mastery in [[learning/_index|Learning]]. New approaches to compounding knowledge (filing strategies, synthesis-first ingestion, automated cross-referencing) are worth exploring as sparks in [[ideas/_index|Ideas]].

_← [[concepts/_index|Concepts]]_
