---
type: source
title: "Karpathy — LLM Wiki"
author: "Andrej Karpathy"
source_url: "https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f"
raw: "[[.raw/karpathy-llm-wiki-2026-06-24.md]]"
ingested: 2026-06-24
updated: 2026-07-04
status: summarized
tags: [source, pkm, llm, foundational]
---

# Karpathy — LLM Wiki

> [!quote] The thesis
> "The wiki is a persistent, compounding artifact. The cross-references are already there. The contradictions have already been flagged. The synthesis already reflects everything you've read."

The foundational essay for **this vault**. [[Andrej Karpathy|Karpathy]] publishes it as an "idea file" meant to be pasted into an LLM agent (Claude Code, Codex, etc.) so the agent and user can instantiate their own version. This page is the source-of-record summary; the ideas are broken out into linked concept pages.

## What it argues

Most LLM-document workflows are [[Wiki vs RAG|RAG]]: upload files, retrieve chunks at query time, generate an answer. The LLM rediscovers knowledge from scratch every question — nothing accumulates. The [[LLM Wiki Pattern]] inverts this: the LLM *incrementally builds and maintains a persistent wiki* of interlinked Markdown that sits between you and the raw sources. Knowledge is **compiled once and kept current**, not re-derived per query — a [[Compounding Knowledge Artifact]].

The division of labor: **you** curate sources, explore, and ask good questions; **the LLM** does all the bookkeeping — summarizing, cross-referencing, filing. "Obsidian is the IDE; the LLM is the programmer; the wiki is the codebase."

## Structure it prescribes

- [[Three-Layer Architecture]] — raw sources (immutable) · the wiki (LLM-owned) · the schema (`CLAUDE.md`, co-evolved).
- [[Ingest Query Lint]] — the three core operations.
- [[Index and Log]] — `index.md` (content catalog) + `log.md` (chronological, grep-able).
- Optional tooling — a search engine over the pages as it grows ([[qmd]]); [[Obsidian]] graph view, Dataview, Marp.

## Why it works

Maintenance — not reading or thinking — is the tedious part of a knowledge base, and it's why humans abandon wikis. LLMs don't get bored and can touch 15 files in one pass, so maintenance cost approaches zero. Karpathy ties the idea to [[Memex]] (Vannevar Bush, 1945): a private, actively-curated store where the *connections* between documents are as valuable as the documents — Bush's unsolved problem was who does the maintenance. The LLM is the answer.

## Relevance to this vault

This is the blueprint Sachet's second brain is built on. Every convention in [[meta/conventions]] traces back here. Karpathy's own usage — ingest one source at a time, stay involved, read the summaries — is the recommended default workflow. See [[Second Brain Roadmap]] for how the implementation is staged across phases.

## Contradictions / open questions
- _None flagged yet (first source)._ Karpathy notes the index-file approach works to ~100 sources / hundreds of pages before embedding-based search becomes worthwhile — a future decision point for this vault.
