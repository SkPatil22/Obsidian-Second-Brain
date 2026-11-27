---
type: meta
title: "Hot Cache"
updated: 2026-11-27T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-11-27. Nightly librarian pass #115 — **1 new link across 1 file.** Attribution close: `wiki/meta/maintenance/_index` intro named [[Andrej Karpathy]] personally ("coined by [[Andrej Karpathy]]") without citing the specific essay. The archive is the daily executor of the essay's Lint step — the page most tightly coupled to [[Karpathy - LLM Wiki]] — yet was the last LWP-attribution page in the vault not to cite both. Every other attribution page (conventions, log, overview, all 6 concept footers) cites essay + person. The reverse direction (essay → archive) has existed since pass #97. Added "([[Karpathy - LLM Wiki]])" to close the bidirectional. IaL 114+→**115+**. Bake: 125 days, still `untested`.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 of [[Second Brain Roadmap]] complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28, see [[Second Brain Roadmap]]): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Media parsing ✅ live** (see [[Second Brain Roadmap]]) — TikTok / Reddit / X / Instagram / YouTube links auto-extracted before filing.
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.** Current vault state: [[overview]].

## Recent Changes
- 2026-11-27: Librarian pass #115 — LINK: 1 new wikilink (maintenance archive intro → [[Karpathy - LLM Wiki]]; bidirectional close; essay→archive existed since pass #97; archive cited author but not essay; last LWP-attribution page without essay citation; 1 link, 1 file). FLAG: IaL 114+→115+; bake warning → 125 days. See [[log]] and [[meta/maintenance/2026-11-27]].
- 2026-11-26: Librarian pass #114 — LINK: 3 new wikilinks ([[Second Brain Roadmap]] footer → [[sources/_index|Sources]] + [[entities/_index|Entities]] + [[meta/conventions|Conventions]]; body-to-footer gap; Phase 1 bullet names all three; 3 links, 1 file). FLAG: IaL 113+→114+; bake warning → 124 days. See [[log]] and [[meta/maintenance/2026-11-26]].
- 2026-11-25: Librarian pass #113 — LINK: 9 new wikilinks (4 domain content pages → [[log]] + [[sources/_index|Sources]] (systematic gap: last content tier without both; 8 links, 4 files); [[Seattle Trip 2026-07]] footer → [[sources/_index|Sources]] (had log since #106; last domain content footer without sources; 1 link, 1 file)). FLAG: IaL 112+→113+; bake warning → 123 days. See [[log]] and [[meta/maintenance/2026-11-25]].
- See [[index]] for counts (1 [[sources/_index|source]] · 6 [[concepts/_index|concepts]] · 8 [[entities/_index|entities]] · 6 domain pages). Full maintenance history in [[meta/maintenance/_index|Maintenance archive]].

## Active Threads
- **✅ Seattle trip — complete** (Jul 21–25, 2026, returned Sat Jul 25). All 5 days done: [[Pike Place Market]] city day → Rainier (Paradise/Skyline) → Olympic (Hurricane Ridge + Lake Crescent + Sol Duc Falls + Port Angeles) → Olympic (Hoh Rainforest + Ruby Beach) → Seattle depart. See [[Seattle Trip 2026-07]] + [[Olympic National Park]] + [[Mount Rainier National Park]].
- **🍰 Post-trip bake — pending:** Fresh Washington raspberries sourced at [[Pike Place Market]] (Tue Jul 21). [[Raspberry Chocolate Cake]] status: `untested` as of 2026-11-27 (**125 days** post-return). Update the recipe page when done.
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase (see [[Second Brain Roadmap]]), once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see [[Second Brain Roadmap]] → `~/brain-infra/README.md` → `activate-sync.sh`.
