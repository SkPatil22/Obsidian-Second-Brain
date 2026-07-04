---
type: meta
title: "Hot Cache"
updated: 2026-07-04T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-07-04. Nightly librarian pass — 7 wikilinks added across 5 files (author-link gap in Karpathy source; Memex ↔ Wiki vs RAG bidirectional; overview → Wiki vs RAG + Obsidian; Compounding Artifact → qmd; Memex → Obsidian); 1 flag updated (Seattle trip 17 days); 6 date fixes.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Works as `/brain <topic>` or natural language.
- **Telegram bot is live** (`brain-bot.service` running) — notes via Telegram → `.raw/` → auto-ingested. Phase 2 complete.
- **Phase 3 — Scheduled routines is live** (✅ 2026-06-28): morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. Reminders via the bot (5-min cron). Email → action items built (needs Gmail app password to activate).
- **Phase 1.5 (sync)** still needs Sachet's GitHub steps (`~/brain-infra/README.md` → `activate-sync.sh`).
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`. Standing rule: **full automation, never review, never touch Obsidian manually.**

## Recent Changes
- 2026-07-04: Librarian pass — LINK: `Karpathy - LLM Wiki` source body → `[[Andrej Karpathy]]` (3 bare name references now linked); `Wiki vs RAG` → `[[Memex]]` (bidirectional gap; Memex→Wiki vs RAG existed but reverse absent); `overview` → `[[Wiki vs RAG]]` + `[[Obsidian]]` (vault front page had neither); `Compounding Knowledge Artifact` → `[[qmd]]` (retrieval layer never mentioned on the concept page); `Memex` → `[[Obsidian]]` (modern realization sentence added). FLAG: Seattle trip updated to 17 days. 6 date fixes. See [[log]] and [[meta/maintenance/2026-07-04]].
- 2026-07-03: Librarian pass — LINK: `Ingest Query Lint` → `[[Andrej Karpathy]]` (attribution gap closed, 2 places); `Andrej Karpathy` → `[[Ingest Query Lint]]` (Facts list); `Pike Place Market` → `[[Running Shoes - Flat Feet]]` (bidirectional gap from 2026-07-02 pass); `Obsidian` → `[[qmd]]` (bidirectional gap — qmd→Obsidian existed but not reverse). FLAG: Seattle trip updated to 18 days. 5 date fixes. See [[log]] and [[meta/maintenance/2026-07-03]].
- 2026-07-02: Librarian pass — PKM cluster fully closed (all 6 concepts mutually reachable); Andrej Karpathy entity fully attributed; travel+city cluster fully triangulated (Pike Place linked from both national parks and Running Shoes); 16 date fixes. See [[log]] and [[meta/maintenance/2026-07-02]].
- 2026-07-01: Librarian pass — travel+fitness cluster triangulated (Running Shoes ↔ Rainier/Olympic, Pike Place Market → parks); PKM cluster densified; 2 urgency flags added. 10 date fixes. See [[log]] and [[meta/maintenance/maintenance-2026-07-01]].
- See [[index]] for counts (1 source · 6 concepts · 7 entities · 6 domain pages).

## Active Threads
- **Thin ribeye recipe summary** — Telegram reminder was 2026-07-01 19:00 (3 days ago); should have been delivered. Check history if needed.
- **Shoe buying decision** — reminder was 2026-06-30 17:30 (4 days ago); likely acted on. See [[Running Shoes - Flat Feet]] for the breakdown. **FLAG:** if using Metcon 6 for Seattle trip, consider shorter Skyline route (~3.5 mi out-and-back) instead of the full 5.5 mi loop.
- **Seattle trip is 17 days away** (Jul 21–25). Critical path: book rental car + Port Angeles lodging NOW — late July books up fast. See [[Seattle Trip 2026-07]].
- **Phase 4 — Retrieval** ([[qmd]]) is the next infrastructure phase, once the wiki outgrows the index (~100 sources).
- **Phase 1.5 — Sync** (GitHub auth) is still pending; see `~/brain-infra/README.md` → `activate-sync.sh`.
