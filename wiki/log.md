---
type: meta
title: "Log"
created: 2026-06-24
updated: 2026-06-24
tags: [meta, log]
---

# Log — Operations Record

Chronological record of every operation against this vault. Newest first.
Entries use a grep-able prefix: `grep "^## \[" log.md | tail -5` → recent ops.

## [2026-06-28] reorg | New `travel/` category + cooking consolidation
- Created top-level **`travel/`**; moved [[Seattle Trip 2026-07]] there (was `projects/`). Type → `trip`.
- Moved [[Baking - Berries and Moisture]] into **`recipes/`** (was `learning/`) — all cooking lives together. Type → `technique`.
- Encoded the policy in [[meta/conventions]] + the `/brain` skill: **new top-level categories are created on demand** for coherent recurring domains (with anti-sprawl judgment). So this kind of sorting happens automatically from now on.

## [2026-06-28] telegram | Baking tip — oil vs butter
- Source: `.raw/tg-20260628-201312-655215-note.md` (Telegram capture).
- Updated: [[Baking - Berries and Moisture]] — added the WHY behind oil-over-butter (milk solids + ~80% fat content → firmer crumb when cold).
- No new pages created.

## [2026-06-25] brain | Seattle trip Jul 21–25
- Source: [[.raw/seattle-trip-research-2026-06-25.md]] (web research, sha256 27ecf7f9…).
- Created: [[Seattle Trip 2026-07]] (project) + entities [[Mount Rainier National Park]], [[Olympic National Park]], [[Pike Place Market]].
- Key facts: Rainier no timed-entry in 2026; dates hit wildflower-peak start; Tue–Sat = weekday park parking.

## [2026-06-25] brain | Raspberry chocolate cake
- Source: [[.raw/raspberry-chocolate-cake-research-2026-06-25.md]] (web research, sha256 e53dd1bb…).
- Created: [[Raspberry Chocolate Cake]] (recipe) + [[Baking - Berries and Moisture]] (technique).
- First `/brain` skill runs — research → distilled → auto-filed, no review.

## [2026-06-24] ingest | Karpathy — LLM Wiki
- Source: [[Karpathy - LLM Wiki]] (`.raw/karpathy-llm-wiki-2026-06-24.md`, sha256 dc3efe98…).
- Created (11 pages): source summary; concepts [[LLM Wiki Pattern]], [[Wiki vs RAG]], [[Compounding Knowledge Artifact]], [[Three-Layer Architecture]], [[Ingest Query Lint]], [[Index and Log]]; entities [[Andrej Karpathy]], [[Obsidian]], [[qmd]], [[Memex]].
- Updated: [[index]] (counts 1/6/4), sources/concepts/entities `_index`, [[hot]], `.raw/.manifest.json`.
- Contradictions: none (first source).

## 2026-06-24 — setup

- **BOOTSTRAP** — Vault initialized on the Raspberry Pi (`~/claude-obsidian`) as the canonical home. Cloned `AgriciDaniel/claude-obsidian`, ran `setup-vault.sh`. Detached the upstream `origin` remote so this private vault never pushes to the public template.
- **RESTRUCTURE** — Original plugin demo wiki preserved to `.seed-demo/`. Built a clean Personal-mode structure: `areas/`, `projects/`, `recipes/`, `learning/`, `people/`, `ideas/`, `resources/` + the ingestion layer `sources/`, `concepts/`, `entities/`, `meta/`.
- **CONFIG** — Transport detected as `filesystem`. Methodology mode: generic. Created [[index]], [[overview]], [[hot]], [[meta/conventions]], and per-domain `_index.md` pages.
