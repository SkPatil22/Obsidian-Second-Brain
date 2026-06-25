---
type: concept
title: "LLM Wiki Pattern"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-06-24
tags: [concept, pkm, foundational]
---

# LLM Wiki Pattern

A pattern for personal knowledge bases where an **LLM incrementally builds and maintains a persistent wiki** of interlinked Markdown that sits between you and your raw sources. Coined/popularized by [[Andrej Karpathy]] (see [[Karpathy - LLM Wiki]]). It is the operating model of this entire vault.

## The mechanism

When a new source arrives, the LLM doesn't just index it for later ([[Wiki vs RAG|unlike RAG]]). It **reads, extracts, and integrates** — updating entity pages, revising topic summaries, flagging contradictions, strengthening the evolving synthesis. The result is a [[Compounding Knowledge Artifact]]: knowledge compiled once and kept current, not re-derived on every query.

## Division of labor

| Human | LLM |
|-------|-----|
| Curate sources | Summarize |
| Explore, ask good questions | Cross-reference & file |
| Direct the analysis | Maintain consistency, update links |
| Decide what it means | All the bookkeeping |

> "Obsidian is the IDE; the LLM is the programmer; the wiki is the codebase."

## Implemented here via

- [[Three-Layer Architecture]] — raw / wiki / schema
- [[Ingest Query Lint]] — the operations
- [[Index and Log]] — navigation as it scales
- Conventions in [[meta/conventions]]

## Lineage
Spiritual successor to the [[Memex]] (Vannevar Bush, 1945) — the LLM solves Bush's open problem of *who does the maintenance*.
