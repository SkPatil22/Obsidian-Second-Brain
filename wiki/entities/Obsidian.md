---
type: entity
entity_type: product
title: "Obsidian"
status: stub
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-23
tags: [entity, tool]
---

# Obsidian

A local-first Markdown knowledge app. Files are plain `.md` on disk, so the vault stays yours (and is a git repo — free version history).

## Role in this vault
The **front-end** for this second brain — "the IDE" in [[Andrej Karpathy|Karpathy's]] analogy (see [[Karpathy - LLM Wiki]]). Sits at the top of the [[Three-Layer Architecture]] as the browsing layer; the [[LLM Wiki Pattern]] defines what the LLM writes into it. Claude writes the `wiki/`; you browse it in Obsidian — following `[[wikilinks]]`, reading updated pages, and using the **graph view** to see the shape of the [[Compounding Knowledge Artifact]] as it grows.

## Useful features (per the source)
- **Graph view** — best way to see the shape of the wiki.
- **Web Clipper** — browser extension to convert articles to Markdown into `.raw/`, feeding the [[Ingest Query Lint|ingest]] loop.
- **Dataview** — queries over YAML frontmatter → dynamic tables; extends the [[Index and Log]] navigation layer at scale.
- **Marp** — Markdown slide decks generated from wiki content.

## In *this* setup
The canonical vault lives on the Raspberry Pi; see [[overview]] for the current vault state. Obsidian on Windows/phone will be a git-synced client (Phase 1.5 — sync, see [[Second Brain Roadmap]]). This Pi also has a desktop, so Obsidian can open the vault locally too.

When the wiki scales past ~100 sources, [[qmd]] adds hybrid BM25+vector search on top — Obsidian for browsing, qmd for retrieval. The two are complementary, not competing.

Obsidian's graph view and wikilink trails are the modern realization of what the [[Memex]] called "associative trails" — the connective tissue between documents that Bush argued was as valuable as the documents themselves.

_Stub._
