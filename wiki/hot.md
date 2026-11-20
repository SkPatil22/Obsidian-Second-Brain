---
type: meta
title: "Hot Cache"
updated: 2026-11-20T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-11-20. Nightly librarian pass #108 — **11 new links across 5 files.** Two clusters: (1) systematic entity-layer gap — 4 PKM entity pages (Karpathy, Bush, qmd, Memex) each gain `[[areas/_index|Areas]]` in body + footer; mirrors pass #106's concept-layer sweep (all 6 concepts → areas); Obsidian entity and all three place entities already had it; these 4 were the last entity cluster without it; (2) body-to-footer gap in [[Karpathy - LLM Wiki]] source page — footer gains `[[projects/_index|Projects]]` + `[[meta/conventions|Conventions]]` + `[[meta/maintenance/_index|Maintenance archive]]`, all three already in the body. IaL 107+→**108+** (pass #108). Bake: 118 days, still `untested`.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 of [[Second Brain Roadmap]] complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28, see [[Second Brain Roadmap]]): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Media parsing ✅ live** (see [[Second Brain Roadmap]]) — TikTok / Reddit / X / Instagram / YouTube links auto-extracted before filing.
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.** Current vault state: [[overview]].

## Recent Changes
- 2026-11-20: Librarian pass #108 — LINK: 11 new wikilinks (4 PKM entities body+footer → [[areas/_index|Areas]]; Karpathy source footer → [[projects/_index|Projects]] + [[meta/conventions|Conventions]] + [[meta/maintenance/_index|Maintenance archive]]). FLAG: IaL 107+→108+; bake warning → 118 days. See [[log]] and [[meta/maintenance/2026-11-20]].
- 2026-11-19: Librarian pass #107 — LINK: 4 new wikilinks (Memex footer → [[sources/_index|Sources]]; Bush → [[meta/conventions|Conventions]] body+footer; maintenance archive → [[LLM Wiki Pattern]]). FLAG: IaL 106+→107+; bake warning → 117 days. See [[log]] and [[meta/maintenance/2026-11-19]].
- 2026-11-13: Librarian pass #106 — LINK: 6 new wikilinks (all 6 concept pages → [[areas/_index|Areas]]; systematic gap closed: learning/ideas/resources downstream pointer trio now complete with areas). FLAG: stale frontmatter corrected (conventions.md + index.md); IaL 105+→106+; bake warning → 111 days. See [[log]] and [[meta/maintenance/2026-11-13]].
- See [[index]] for counts (1 [[sources/_index|source]] · 6 [[concepts/_index|concepts]] · 8 [[entities/_index|entities]] · 6 domain pages). Full maintenance history in [[meta/maintenance/_index|Maintenance archive]].

## Active Threads
- **✅ Seattle trip — complete** (Jul 21–25, 2026, returned Sat Jul 25). All 5 days done: [[Pike Place Market]] city day → Rainier (Paradise/Skyline) → Olympic (Hurricane Ridge + Lake Crescent + Sol Duc Falls + Port Angeles) → Olympic (Hoh Rainforest + Ruby Beach) → Seattle depart. See [[Seattle Trip 2026-07]] + [[Olympic National Park]] + [[Mount Rainier National Park]].
- **🍰 Post-trip bake — pending:** Fresh Washington raspberries sourced at [[Pike Place Market]] (Tue Jul 21). [[Raspberry Chocolate Cake]] status: `untested` as of 2026-11-20 (**118 days** post-return). Update the recipe page when done.
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase (see [[Second Brain Roadmap]]), once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`.
