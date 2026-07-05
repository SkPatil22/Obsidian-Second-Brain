---
type: project
title: "Second Brain Roadmap"
status: active
area: growth
priority: 1
created: 2026-06-24
updated: 2026-07-05
tags: [project, meta, infrastructure]
---

# Second Brain Roadmap

The staged build-out of this vault into an always-on personal knowledge + automation system. Implements the [[LLM Wiki Pattern]] (coined by [[Andrej Karpathy]]) as its foundation, following the [[Three-Layer Architecture]] to build a true [[Compounding Knowledge Artifact]].

## Where we are
- **Phase 1 — Vault + plugin** ✅ done 2026-06-24. Clean Personal-mode vault on the Pi; `claude-obsidian` plugin installed; first ingest ([[Karpathy - LLM Wiki]]).
- **Phase 1.5 — Sync** 🟡 prepped, awaiting GitHub auth. `~/brain-infra/sync.sh` + cron push every 15 min; Windows/phone [[Obsidian]] become git-synced clients. Activate with `~/brain-infra/activate-sync.sh`.

## Next
- **Phase 2 — Always-on ingestion** ✅ **live as of 2026-06-28**. `~/brain-infra/brain_bot.py` + systemd `brain-bot.service` running; Telegram token active.
  - **Telegram bot → vault `.raw/` → auto-ingest** via headless **`claude -p`** (Pro plan, **no API spend**) → filed + synced. **No triage gate, no review** — everything that comes in gets distilled and sorted (the [[Ingest Query Lint|ingest]] loop).
  - **Big historical dumps** (camera roll, old files) get **on-demand multi-agent triage** that Sachet kicks off from Claude Desktop — infrequent, not always-on.
  - The `/brain` skill is the manual front-door for the same loop (`~/.claude/skills/brain/`).
- **Phase 3 — Scheduled routines** ✅ **live 2026-06-28**. Morning brief (Raleigh weather + markets + sports for all six teams + politics) at 7am → daily note + Telegram. **Reminders** ("remind me to X tomorrow at 3pm") via the bot, fired by a 5-min cron, reflected into the calendar. **Email → action items** built (needs a Gmail app password to switch on).
- **Media parsing** ✅ **live** — TikTok / Reddit / X / Instagram / YouTube links you send get auto-extracted to text (`~/brain-infra/routines/fetch_media.py`) before filing. Reddit via RSS, others via yt-dlp + captions.
- **Phase 4 — Retrieval** — [[qmd]] or similar once the wiki outgrows [[Index and Log|the index]].
- **Phase 5+ — Agents** — read-only → reversible actions → (last, gated) capital allocation.

## Constraints (standing)
- No metered API spend — Pro plan only. Prefer free/local components on the Pi.
- The Claude CLI is scaffolding; converge toward zero-friction messaging capture.
- Reliability first; autonomy earns trust in stages.
