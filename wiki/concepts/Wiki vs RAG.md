---
type: concept
title: "Wiki vs RAG"
status: synthesized
sources: ["[[Karpathy - LLM Wiki]]"]
created: 2026-06-24
updated: 2026-07-02
tags: [concept, pkm, comparison]
---

# Wiki vs RAG

The core distinction that motivates the [[LLM Wiki Pattern]].

| | **RAG** (retrieve-at-query-time) | **LLM Wiki** (compile-once, maintain) |
|---|---|---|
| When work happens | Every query | Once, at ingest |
| Accumulation | None — rediscovered each time | Compounds with every source |
| Cross-references | Found ad hoc, per question | Already present in the pages |
| Contradictions | Re-encountered each query | Flagged once, recorded |
| Synthesis | Re-pieced every time | Reflects everything already read |
| Examples | NotebookLM, ChatGPT uploads, most RAG | This vault |

**The failure mode of RAG:** ask a subtle question that needs five documents synthesized, and the LLM must find and piece together the fragments *every single time*. Nothing is built up.

**The wiki answer:** the synthesis is a durable artifact — a [[Compounding Knowledge Artifact]]. You read it; the LLM writes it.

> Note: RAG isn't wrong, just different. [[Andrej Karpathy|Karpathy]] notes the [[Index and Log|index-file approach]] scales to ~100 sources before embedding-based retrieval becomes worth adding — at which point a search layer ([[qmd]]) can sit *on top of* the wiki, not replace it.

See [[Karpathy - LLM Wiki]].
