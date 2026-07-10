---
type: meta
title: "Hot Cache"
updated: 2026-07-10T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-07-10. Nightly librarian pass — 4 wikilinks added across 4 files. Largest gap closed: all three knowledge-layer _index pages (sources, concepts, entities) lacked links to `[[Ingest Query Lint]]` even though their descriptions explicitly describe the ingest operation — fixed. `Second Brain Roadmap` Phase 1 now directly links to `[[meta/conventions]]` (the schema artifact created in Phase 1). Flag: Seattle trip 12→11 days.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (`~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.**

## Recent Changes
- 2026-07-10: Librarian pass — LINK: `sources/_index` → `[[Ingest Query Lint]]` (description said "built automatically by ingestion" without linking the concept); `concepts/_index` → `[[Ingest Query Lint]]` (same — "extracted from sources" via ingest); `entities/_index` → `[[Ingest Query Lint]]` (same — "accreting facts via ingestion"; all 3 knowledge-layer _index pages now link to Ingest Query Lint); `Second Brain Roadmap` Phase 1 → `[[meta/conventions]]` (schema created in Phase 1 now directly linked). FLAG: Seattle trip 12→11 days. See [[log]] and [[meta/maintenance/2026-07-10]].
- 2026-07-09: Librarian pass — LINK: `meta/conventions` → `[[LLM Wiki Pattern]]` + `[[Three-Layer Architecture]]` + `[[Ingest Query Lint]]`; `travel/_index` gains "Destination entities" subsection with all 3 Seattle places; `Obsidian` ↔ `[[Index and Log]]` bidirectional closed; `Wiki vs RAG` → `[[overview]]`; `overview` → `[[Index and Log]]`. See [[log]] and [[meta/maintenance/2026-07-09]].
- See [[index]] for counts (1 source · 6 concepts · 7 entities · 6 domain pages).

## Active Threads
- **[[Thin Ribeye Recipes|Thin ribeye recipe summary]]** — Telegram reminder was 2026-07-01 19:00 (9 days ago); check Telegram history if not acted on.
- **Shoe buying decision** — reminder was 2026-06-30 17:30 (10 days ago); likely acted on. See [[Running Shoes - Flat Feet]] for the breakdown. **FLAG:** if using Metcon 6 for Seattle trip, consider shorter Skyline route (~3.5 mi out-and-back) instead of the full 5.5 mi loop.
- **Seattle trip is 11 days away** (Jul 21–25). Critical path: book rental car + Port Angeles lodging NOW — late July books up fast. Restaurant reservations (Kashiba, Pink Door) also fill weeks out. See [[Seattle Trip 2026-07]].
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase, once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see `~/brain-infra/README.md` → `activate-sync.sh`.
