---
type: entity
entity_type: tool
title: "qmd"
status: stub
source_url: "https://github.com/tobi/qmd"
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-07
tags: [entity, tool, search]
---

# qmd

A local search engine for Markdown files — hybrid **BM25 + vector search with LLM re-ranking**, all on-device. By Tobi (tobi/qmd).

## Why it matters here
[[Andrej Karpathy]] (via [[Karpathy - LLM Wiki]]) names it as the obvious tool to add **once the wiki outgrows [[Index and Log|the index file]]** (~100+ sources). It exposes both a **CLI** (the LLM can shell out to it) and an **MCP server** (native tool use) — so it slots on top of [[Three-Layer Architecture]] alongside [[Obsidian]] (the browsing layer) without changing the substrate. It's the scale-out retrieval layer of the [[LLM Wiki Pattern]] — specifically the Query step of [[Ingest Query Lint]] at scale.

Crucially, qmd sits *on top of* the [[Compounding Knowledge Artifact]], not instead of it — the synthesis stays; you just navigate it faster. This is what keeps qmd firmly on the wiki side of the [[Wiki vs RAG]] spectrum: nothing is re-derived from raw sources at query time.

## Status for this vault
**Not needed yet.** The index-first approach covers small/medium scale. Revisit when search latency or recall degrades. A simpler home-grown search script is also a valid first step. Tracked as Phase 4 in [[Second Brain Roadmap]].

_Stub — candidate for the future retrieval layer (Stage 4 of the larger plan)._
