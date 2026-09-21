---
type: meta
title: "Hot Cache"
updated: 2026-09-21T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-09-21. Nightly librarian pass — **11 new links across 8 files**: today's focus was closing four structural gaps — (1) **people↔resources bidirectional**: `people/_index` → `resources/_index` and `resources/_index` → `people/_index` (mentors/relationships surface worthwhile resources; resources often come from personal recommendations; both directions absent). (2) **IQL output-layer triangle**: `Ingest Query Lint` → `concepts/_index` + `entities/_index` (Ingest step named "entity/concept pages" as outputs but only linked `sources/_index`; all three output catalogs now linked from the description). (3) **Obsidian→Wiki vs RAG**: `Wiki vs RAG` named Obsidian as the wiki-side browser; reverse never closed. (4) **sources/_index↔Three-Layer Architecture** + wiki-layer catalogs in 3LA prose: `sources/_index` now names itself "the raw layer of the [[Three-Layer Architecture]]"; `Three-Layer Architecture` gains sentence naming all three wiki-layer catalogs (`sources/_index`, `concepts/_index`, `entities/_index`). Plus (5) `Raspberry Chocolate Cake` and `Thin Ribeye Recipes` both gain `people/_index` (cooking/meal-prep is social; both trip-cluster pages had linked every domain except people). **Bake-pending counter** climbs to 58 days.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 of [[Second Brain Roadmap]] complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28, see [[Second Brain Roadmap]]): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Media parsing ✅ live** (see [[Second Brain Roadmap]]) — TikTok / Reddit / X / Instagram / YouTube links auto-extracted before filing.
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.** Current vault state: [[overview]].

## Recent Changes
- 2026-09-21: Librarian pass — LINK: 11 new wikilinks across 8 files (people↔resources bidirectional; IQL → concepts/_index+entities/_index; Obsidian→Wiki vs RAG; sources/_index↔Three-Layer Architecture + wiki-layer catalogs in 3LA; Raspberry Cake+Thin Ribeye → people). FLAG: bake warning → 58 days. See [[log]] and [[meta/maintenance/2026-09-21]].
- 2026-09-20: Librarian pass — LINK: 6 new wikilinks across 6 files (concepts/_index+entities/_index+sources/_index → conventions; recipes/_index → people; Karpathy entity → sources/_index; maintenance archive → hot). FLAG: bake warning → 57 days; callout headers corrected. See [[log]] and [[meta/maintenance/2026-09-20]].
- 2026-09-19: Librarian pass — LINK: 7 new wikilinks across 5 files (index Counts→catalogs; areas/_index↔sources/_index bidirectional close; Rainier+Olympic+Pike Place→areas). FLAG: bake warning → 56 days. See [[log]] and [[meta/maintenance/2026-09-19]].
- See [[index]] for counts (1 [[sources/_index|source]] · 6 [[concepts/_index|concepts]] · 7 [[entities/_index|entities]] · 6 domain pages). Full maintenance history in [[meta/maintenance/_index|Maintenance archive]].

## Active Threads
- **✅ Seattle trip — complete** (Jul 21–25, 2026, returned Sat Jul 25). All 5 days done: [[Pike Place Market]] city day → Rainier (Paradise/Skyline) → Olympic (Hurricane Ridge + Lake Crescent + Sol Duc Falls + Port Angeles) → Olympic (Hoh Rainforest + Ruby Beach) → Seattle depart. See [[Seattle Trip 2026-07]] + [[Olympic National Park]] + [[Mount Rainier National Park]].
- **🍰 Post-trip bake — pending:** Fresh Washington raspberries sourced at [[Pike Place Market]] (Jul 21). [[Raspberry Chocolate Cake]] status: `untested` as of 2026-09-21 (58 days post-return). Update the recipe page when done.
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase (see [[Second Brain Roadmap]]), once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`.
