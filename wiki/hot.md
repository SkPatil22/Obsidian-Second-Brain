---
type: meta
title: "Hot Cache"
updated: 2026-07-17T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-07-17. Nightly librarian pass — 17 new wikilinks, 0 moves, 0 merges. Primary theme: **conventions.md promoted to navigation hub** — 7 links added to folder definitions and ingestion contract (all 3 knowledge-layer folder descriptions now link to `[[Ingest Query Lint|ingestion]]`; `travel/` and `learning/` folder backtick code spans converted to navigable `[[entities/_index|entities/]]` and `[[concepts/_index|concepts/]]`; step 3 of the ingest contract now links all 3 knowledge-layer folder types; "Travel started this way" → `[[travel/_index|Travel]]`). Four bare domain names in `overview.md` linked (recipes, projects, learning, ideas — completing the set after travel was linked 2026-07-16). Knowledge-layer triangle closed: `entities/_index` and `concepts/_index` both now point to `[[sources/_index|Sources]]`. `entities/_index` → `[[people/_index|People]]` (reverse of 2026-07-16 people→entities). `ideas/_index` → `[[areas/_index|Areas]]` (first-ever edit to ideas/_index since vault setup). `projects/_index` SBR description updated to include media parsing. Seattle trip counter: **4 days**.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28, see [[Second Brain Roadmap]]): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Media parsing ✅ live** — TikTok / Reddit / X / Instagram / YouTube links auto-extracted before filing.
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.**

## Recent Changes
- 2026-07-17: Librarian pass — LINK: `meta/conventions` folder defs → `[[Ingest Query Lint|ingestion]]` ×3 + `[[entities/_index]]` + `[[concepts/_index]]`; creating-categories example → `[[travel/_index|Travel]]`; ingest step 3 → `[[sources/_index]]` + `[[concepts/_index]]` + `[[entities/_index]]`; `overview` → `[[recipes/_index]]` + `[[projects/_index]]` + `[[learning/_index]]` + `[[ideas/_index]]`; `entities/_index` → `[[sources/_index]]` + `[[people/_index]]`; `concepts/_index` → `[[sources/_index]]`; `ideas/_index` → `[[areas/_index]]` (17 wikilinks). FLAG: Seattle trip 5→4 days. See [[log]] and [[meta/maintenance/2026-07-17]].
- 2026-07-16: Librarian pass — LINK: `meta/conventions` → `[[Index and Log]]`; `wiki/index` → `[[Index and Log]]`; `wiki/log` → `[[Index and Log]]`; `Running Shoes - Flat Feet` ↔ `[[Raspberry Chocolate Cake]]` (both directions); `overview` → `[[travel/_index|Travel]]`; `people/_index` → `[[entities/_index]]`; `learning/_index` → `[[resources/_index]]` (8 wikilinks). FLAG: Seattle trip 6→5 days. See [[log]] and [[meta/maintenance/2026-07-16]].
- 2026-07-15: Librarian pass — LINK: `Seattle Trip 2026-07` ↔ `[[Raspberry Chocolate Cake]]`; `resources/_index` → `[[learning/_index]]`; `areas/_index` → `[[learning/_index]]` (4 wikilinks). FLAG: Seattle trip 7→6 days. See [[log]] and [[meta/maintenance/2026-07-15]].
- See [[index]] for counts (1 source · 6 concepts · 7 entities · 6 domain pages).

## Active Threads
- **[[Thin Ribeye Recipes|Thin ribeye recipe summary]]** — Telegram reminder was 2026-07-01 19:00 (16 days ago); check Telegram history if not acted on.
- **Shoe buying decision** — reminder was 2026-06-30 17:30 (17 days ago); likely acted on. See [[Running Shoes - Flat Feet]] for the breakdown. **FLAG:** if using Metcon 6 for Seattle trip, consider shorter Skyline route (~3.5 mi out-and-back) instead of the full 5.5 mi loop.
- **Seattle trip is 4 days away** (Jul 21–25). Critical path: book rental car + Port Angeles lodging NOW — late July books up fast. Restaurant reservations (Kashiba, Pink Door) also fill weeks out. See [[Seattle Trip 2026-07]].
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase, once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see `~/brain-infra/README.md` → `activate-sync.sh`.
