---
type: meta
title: "Hot Cache"
updated: 2026-06-25T00:00:00
tags: [meta, hot-cache]
---

# Recent Context

## Last Updated
2026-06-25. First two `/brain` runs landed: a raspberry chocolate cake and a Seattle trip plan — both researched, distilled, and auto-filed with no review.

## Key Recent Facts
- The **`/brain` skill** exists (`~/.claude/skills/brain/`): "research X and file it into the second brain, auto-sorted, cross-linked, no review." Loads next session; works as `/brain <topic>` or natural language.
- Vault on the Pi at `~/claude-obsidian`, transport `filesystem`, plugin enabled. Sync prepped (awaiting GitHub auth).
- Owner: Sachet. Standing rule: **full automation, never review, never touch Obsidian manually.**

## Recent Changes
- Created: [[Seattle Trip 2026-07]] + [[Mount Rainier National Park]], [[Olympic National Park]], [[Pike Place Market]].
- Created: [[Raspberry Chocolate Cake]] + [[Baking - Berries and Moisture]].
- See [[index]] for counts (1 source · 6 concepts · 7 entities · 4 domain pages).

## Active Threads
- **Phase 2 bot BUILT** (`~/brain-infra/brain_bot.py`, systemd `brain-bot.service`): Telegram → vault `.raw/` → auto-ingest via `claude -p` (no triage, no review). **Needs only a @BotFather token** — run `~/brain-infra/activate-telegram.sh`. Big historical dumps still get on-demand multi-agent triage from Claude Desktop.
- **Sync** still needs Sachet's GitHub steps (`~/brain-infra/README.md`).
- Seattle trip has open action items (rental car, Port Angeles lodging, restaurant bookings) in the project note.
