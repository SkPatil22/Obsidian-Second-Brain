---
type: meta
title: "Hot Cache"
updated: 2026-06-24T00:30:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-06-24. Vault bootstrapped on the Raspberry Pi and the first real source ingested: Karpathy's LLM Wiki essay — the blueprint for this whole vault.

## Key Recent Facts
- Canonical vault lives on the Pi at `~/claude-obsidian`. Transport: `filesystem` (no MCP/REST API needed). Plugin `claude-obsidian` v1.9.2 installed + enabled.
- Owner: Sachet. Purpose: personal second brain — work, finance, recipes, projects, learning, ideas.
- The vault implements the [[LLM Wiki Pattern]]: raw → distilled → compounding ([[Three-Layer Architecture]]). You curate; Claude does the bookkeeping.

## Recent Changes
- Ingested: [[Karpathy - LLM Wiki]] → 6 concepts + 4 entities (see [[index]]).
- Created: clean Personal-mode `wiki/` structure; [[meta/conventions]]; per-domain `_index` pages.
- Preserved: original plugin demo wiki in `.seed-demo/`.

## Active Threads
- **Phase 1 (vault + plugin) is done.** Next up: Phase 2 — always-on ingestion service on the Pi (a phone number / drop folder to text raw data to). Then scheduled routines (morning weather/news/finance brief) and a retrieval layer ([[qmd]]) once the wiki grows.
- Domains (`areas/`, `recipes/`, `people/`, etc.) are scaffolded but empty — ready for real content.
