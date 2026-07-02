---
type: concept
title: "Three-Layer Architecture"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-02
tags: [concept, pkm, architecture]
---

# Three-Layer Architecture

The structural backbone of the [[LLM Wiki Pattern]], as framed by [[Andrej Karpathy]]. Three layers, strict ownership.

| Layer | This vault | Who owns it | Rule |
|-------|-----------|-------------|------|
| **Raw sources** | `.raw/` | You (curated) | Immutable — LLM reads, never edits. Source of truth. |
| **The wiki** | `wiki/` | The LLM | LLM creates/updates pages, maintains cross-refs and consistency. You read it. |
| **The schema** | `CLAUDE.md` + [[meta/conventions]] | Co-evolved | Tells the LLM how the wiki is structured and what workflows to follow. |

The **schema is the key file** — it's what makes the LLM a disciplined wiki maintainer rather than a generic chatbot. You and the LLM refine it over time as you learn what works for your domains.

See [[Ingest Query Lint]] for the operations that move data between layers — each ingest adds to the [[Compounding Knowledge Artifact]] — and [[Karpathy - LLM Wiki]] for the original framing.

## In this vault
- **Front-end:** [[Obsidian]] on the Pi (or Windows/phone via sync) — graph view, search, Dataview queries
- **Optional search layer:** [[qmd]] — adds hybrid BM25+vector retrieval on top without changing the substrate, when the wiki outgrows the index
- **Implementation:** [[Second Brain Roadmap]] — the staged build-out of this vault, phase by phase
