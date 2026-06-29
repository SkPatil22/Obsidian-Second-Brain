---
type: entity
entity_type: tool
title: "qmd"
status: stub
source_url: "https://github.com/tobi/qmd"
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-06-28
tags: [entity, tool, search]
---

# qmd

A local search engine for Markdown files — hybrid **BM25 + vector search with LLM re-ranking**, all on-device. By Tobi (tobi/qmd).

## Why it matters here
[[Karpathy - LLM Wiki]] names it as the obvious tool to add **once the wiki outgrows [[Index and Log|the index file]]** (~100+ sources). It exposes both a **CLI** (the LLM can shell out to it) and an **MCP server** (native tool use) — so it slots on top of [[Three-Layer Architecture]] without changing the substrate. It's the scale-out retrieval layer of the [[LLM Wiki Pattern]].

## Status for this vault
**Not needed yet.** The index-first approach covers small/medium scale. Revisit when search latency or recall degrades. A simpler home-grown search script is also a valid first step.

_Stub — candidate for the future retrieval layer (Stage 4 of the larger plan)._
