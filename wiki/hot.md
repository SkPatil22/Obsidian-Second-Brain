---
type: meta
title: "Hot Cache"
updated: 2026-07-05T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-07-05. Nightly librarian pass — 12 wikilinks added across 10 files (bidirectional gaps Obsidian↔Memex and qmd↔Compounding Knowledge Artifact; Andrej Karpathy Facts list completed with Index and Log; Three-Layer Architecture now names Index and Log in the wiki layer; Compounding Knowledge Artifact gains Obsidian + Index and Log; Index and Log gains CKA back-link; Ingest Query Lint gains qmd for Query-at-scale; Second Brain Roadmap gains Wiki vs RAG + Memex in intro; portability cluster Thin Ribeye Recipes ↔ Seattle Trip); 1 flag updated (Seattle trip 16 days); 10 date fixes.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (`~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.**

## Recent Changes
- 2026-07-05: Librarian pass — LINK: `Obsidian` → `[[Memex]]` (bidirectional gap — Memex→Obsidian added 2026-07-04; added Obsidian paragraph on graph view as associative trails); `qmd` → `[[Compounding Knowledge Artifact]]` + `[[Wiki vs RAG]]` (qmd extends the CKA at scale; CKA→qmd existed but reverse absent); `Andrej Karpathy` → `[[Index and Log]]` (Facts list had 4 of 5 originated patterns; Index and Log was missing); `Three-Layer Architecture` → `[[Index and Log]]` (index+log live in wiki layer; never mentioned on the architecture page); `Compounding Knowledge Artifact` → `[[Obsidian]]` + `[[Index and Log]]` (how you read and navigate the artifact; both missing from the artifact's own page); `Index and Log` → `[[Compounding Knowledge Artifact]]` (the index is the map of the CKA); `Ingest Query Lint` → `[[qmd]]` (scale-out for the Query step); `Second Brain Roadmap` → `[[Wiki vs RAG]]` + `[[Memex]]` (roadmap intro now says what it's building — wiki-not-RAG Memex realization); `Seattle Trip 2026-07` → `[[Thin Ribeye Recipes]]` (meal prep for park days, 4-day shelf life); `Thin Ribeye Recipes` → `[[Seattle Trip 2026-07]]` (bidirectional). FLAG: Seattle trip updated to 16 days. 10 date fixes. See [[log]] and [[meta/maintenance/2026-07-05]].
- 2026-07-04: Librarian pass — LINK: `Karpathy - LLM Wiki` source body → `[[Andrej Karpathy]]` (3 bare name references now linked); `Wiki vs RAG` → `[[Memex]]`; `overview` → `[[Wiki vs RAG]]` + `[[Obsidian]]`; `Compounding Knowledge Artifact` → `[[qmd]]`; `Memex` → `[[Obsidian]]`. FLAG: Seattle trip updated to 17 days. 6 date fixes. See [[log]] and [[meta/maintenance/2026-07-04]].
- 2026-07-03: Librarian pass — LINK: `Ingest Query Lint` → `[[Andrej Karpathy]]` (2 places); `Andrej Karpathy` → `[[Ingest Query Lint]]`; `Pike Place Market` → `[[Running Shoes - Flat Feet]]`; `Obsidian` → `[[qmd]]`. FLAG: Seattle trip updated to 18 days. 5 date fixes. See [[log]] and [[meta/maintenance/2026-07-03]].
- See [[index]] for counts (1 source · 6 concepts · 7 entities · 6 domain pages).

## Active Threads
- **Thin ribeye recipe summary** — Telegram reminder was 2026-07-01 19:00 (4 days ago); check Telegram history if not acted on.
- **Shoe buying decision** — reminder was 2026-06-30 17:30 (5 days ago); likely acted on. See [[Running Shoes - Flat Feet]] for the breakdown. **FLAG:** if using Metcon 6 for Seattle trip, consider shorter Skyline route (~3.5 mi out-and-back) instead of the full 5.5 mi loop.
- **Seattle trip is 16 days away** (Jul 21–25). Critical path: book rental car + Port Angeles lodging NOW — late July books up fast. Restaurant reservations (Kashiba, Pink Door) also fill weeks out. See [[Seattle Trip 2026-07]].
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase, once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see `~/brain-infra/README.md` → `activate-sync.sh`.
