---
type: project
title: "Second Brain Roadmap"
status: active
area: growth
priority: 1
created: 2026-06-24
updated: 2026-06-24
tags: [project, meta, infrastructure]
---

# Second Brain Roadmap

The staged build-out of this vault into an always-on personal knowledge + automation system. Implements the [[LLM Wiki Pattern]] as its foundation.

## Where we are
- **Phase 1 — Vault + plugin** ✅ done 2026-06-24. Clean Personal-mode vault on the Pi; `claude-obsidian` plugin installed; first ingest ([[Karpathy - LLM Wiki]]).
- **Phase 1.5 — Sync** 🟡 prepped, awaiting GitHub auth. `~/brain-infra/sync.sh` + cron push every 15 min; Windows/phone Obsidian become git-synced clients. Activate with `~/brain-infra/activate-sync.sh`.

## Next
- **Phase 2 — Always-on ingestion** 🟡 **built, needs Telegram token**. `~/brain-infra/brain_bot.py` + systemd service; activate via `activate-telegram.sh`. Design in `~/brain-infra/PHASE2-DESIGN.md`.
  - **Telegram bot → vault `.raw/` → auto-ingest** via headless **`claude -p`** (Pro plan, **no API spend**) → filed + synced. **No triage gate, no review** — everything that comes in gets distilled and sorted (the [[Ingest Query Lint|ingest]] loop).
  - **Big historical dumps** (camera roll, old files) get **on-demand multi-agent triage** that Sachet kicks off from Claude Desktop — infrequent, not always-on.
  - The **[[Second Brain Roadmap|/brain skill]]** is the manual front-door for the same loop (`~/.claude/skills/brain/`).
- **Phase 3 — Scheduled routines** — morning weather / news / finance brief.
- **Phase 4 — Retrieval** — [[qmd]] or similar once the wiki outgrows [[Index and Log|the index]].
- **Phase 5+ — Agents** — read-only → reversible actions → (last, gated) capital allocation.

## Constraints (standing)
- No metered API spend — Pro plan only. Prefer free/local components on the Pi.
- The Claude CLI is scaffolding; converge toward zero-friction messaging capture.
- Reliability first; autonomy earns trust in stages.
