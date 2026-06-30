---
type: meta
title: "Overview"
created: 2026-06-24
updated: 2026-06-30
tags: [meta, overview]
---

# Overview

**This vault is Sachet's personal second brain** — a persistent, compounding knowledge base across all life domains: work, finance, recipes, projects, learning, and ideas.

It follows [[Andrej Karpathy|Karpathy's]] *[[LLM Wiki Pattern|LLM Wiki]]* pattern: plain Markdown you own, where Claude reads sources, distills them, cross-links everything, and the knowledge compounds with every session. The wiki is the product; chat is just the interface.

## How it works

1. **Raw in.** Sources land in `.raw/` (articles, links, transcripts, screenshots, recipes). They are immutable — read, never edited.
2. **Distilled out.** Claude ingests a source and writes 1–N pages into `wiki/`: a source summary, plus any concepts, entities, and domain notes it touches. Everything is cross-linked with `[[wikilinks]]`.
3. **It compounds.** Each new source links into what's already here. Contradictions get flagged. The graph gets denser.

## The "do I give a fuck" filter

Not everything gets ingested. A random screenshot is noise; your insurance card is signal. When in doubt, a source is filed conservatively rather than discarded, and low-confidence items are flagged for review rather than silently dropped.

## Where things live

See [[index]] for the full map. Domains hold *your* curated notes; `sources/`, `concepts/`, and `entities/` are the knowledge layer the ingestion pipeline builds automatically.

## Status

Bootstrapped 2026-06-24 on the Raspberry Pi (canonical home). Transport: filesystem. See [[Second Brain Roadmap]] for the full build-out. Phase 2 (always-on Telegram ingestion) is live as of 2026-06-28. Scheduled routines and retrieval ([[qmd]]) come next.
