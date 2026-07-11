---
type: meta
title: "Hot Cache"
updated: 2026-07-11T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-07-11. Nightly librarian pass — 1 wikilink added, 1 frontmatter fix applied. Gap closed: `overview` now links directly to `[[meta/conventions]]` (the front page described the vault's operation without ever pointing to the schema that governs it). Frontmatter fix: `Baking - Berries and Moisture` corrected from non-standard `type: technique` + vestigial `area: creative` (leftover from `learning/` era) to `type: recipe` (conventions covers "recipes and techniques" under this type). Seattle trip counter: 10 days.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (`~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.**

## Recent Changes
- 2026-07-11: Librarian pass — LINK: `overview` → `[[meta/conventions]]` (front page gap); STRUCTURE: `Baking - Berries and Moisture` frontmatter fix (`type: technique`→`recipe`, removed `area: creative`); FLAG: Seattle trip 11→10 days. See [[log]] and [[meta/maintenance/2026-07-11]].
- 2026-07-10: Librarian pass — LINK: `sources/_index` → `[[Ingest Query Lint]]`; `concepts/_index` → `[[Ingest Query Lint]]`; `entities/_index` → `[[Ingest Query Lint]]`; `Second Brain Roadmap` Phase 1 → `[[meta/conventions]]`. FLAG: Seattle trip 12→11 days. See [[log]] and [[meta/maintenance/2026-07-10]].
- 2026-07-09: Librarian pass — LINK: `meta/conventions` → `[[LLM Wiki Pattern]]` + `[[Three-Layer Architecture]]` + `[[Ingest Query Lint]]`; `travel/_index` gains Destination entities subsection; `Obsidian` ↔ `[[Index and Log]]`; `Wiki vs RAG` → `[[overview]]`; `overview` → `[[Index and Log]]`. See [[log]] and [[meta/maintenance/2026-07-09]].
- See [[index]] for counts (1 source · 6 concepts · 7 entities · 6 domain pages).

## Active Threads
- **[[Thin Ribeye Recipes|Thin ribeye recipe summary]]** — Telegram reminder was 2026-07-01 19:00 (10 days ago); check Telegram history if not acted on.
- **Shoe buying decision** — reminder was 2026-06-30 17:30 (11 days ago); likely acted on. See [[Running Shoes - Flat Feet]] for the breakdown. **FLAG:** if using Metcon 6 for Seattle trip, consider shorter Skyline route (~3.5 mi out-and-back) instead of the full 5.5 mi loop.
- **Seattle trip is 10 days away** (Jul 21–25). Critical path: book rental car + Port Angeles lodging NOW — late July books up fast. Restaurant reservations (Kashiba, Pink Door) also fill weeks out. See [[Seattle Trip 2026-07]].
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase, once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see `~/brain-infra/README.md` → `activate-sync.sh`.
