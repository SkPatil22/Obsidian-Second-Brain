---
type: entity
entity_type: concept-artifact
title: "Memex"
status: stub
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-10-31
tags: [entity, history, pkm]
---

# Memex

Vannevar Bush's 1945 vision (from "As We May Think") of a personal, curated knowledge store with **associative trails** between documents — where the connections between documents are as valuable as the documents themselves.

## Relevance
[[Andrej Karpathy]] (via [[Karpathy - LLM Wiki]]) frames the [[LLM Wiki Pattern]] as the spiritual successor to the Memex. Bush's vision was closer to a private, actively-curated wiki than to what the web became. The Memex is firmly on the *wiki* side of the [[Wiki vs RAG]] spectrum: compile once, maintain, grow — not re-derive from scratch on every query. **The part Bush couldn't solve: who does the maintenance.** The LLM is the missing piece — it maintains the trails via the [[Ingest Query Lint]] loop so they don't rot, producing a [[Compounding Knowledge Artifact]] that actually stays alive.

The modern implementation: [[Obsidian]] for the browsing layer, Claude for the maintenance, and [[qmd]] for retrieval at scale (Phase 4) — realizing Bush's vision with contemporary tooling, organized by the [[Three-Layer Architecture]] (raw sources → wiki layer → schema). The associative trails are navigated via [[Index and Log]] — the catalog and chronological record that make them findable as the wiki grows. See [[Second Brain Roadmap]] for how this vault builds out that realization, phase by phase, [[overview]] for where it stands today, and [[meta/maintenance/_index|Maintenance archive]] for the daily proof that the maintenance problem is solved — the LLM runs these passes so the trails don't rot.

Understanding Bush's original design goals — associative trails, the distinction from linear/hierarchical organization, and why the maintenance problem blocked the vision for 80 years — deepens your grasp of the modern implementation; track that background in [[learning/_index|Learning]]. The Memex concept also continues to spark ideas about knowledge architecture and navigation; file those in [[ideas/_index|Ideas]]. The source that introduced the Memex to this vault is archived in [[sources/_index|Sources]].

_← [[entities/_index|Entities]] · [[concepts/_index|Concepts]] · [[projects/_index|Projects]] — the vault building out Bush's vision is the main active project · [[resources/_index|Resources]] — Bush's "As We May Think" (1945) is a PKM reference to ingest when available · [[log]] — the daily record proving the maintenance problem is solved · [[hot]] — the most recent working context_

_Stub._
