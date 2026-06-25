---
type: meta
title: "Conventions"
created: 2026-06-24
updated: 2026-06-24
tags: [meta, conventions]
---

# Conventions

The rules every note in this vault follows. Claude reads this before writing.

## Frontmatter (minimum)

Every note carries YAML frontmatter with at least:

```yaml
---
type:        # source | concept | entity | recipe | goal | area | project | person | idea | resource | meta
title: ""
created: YYYY-MM-DD
updated: YYYY-MM-DD
tags: []
---
```

Type-specific fields are added on top (e.g. recipes get `servings`, `time`, `source_url`; sources get `source_url`, `ingested`).

## Folders

- **areas/** — ongoing, no end state (health, finance, career, home). Review periodically.
- **projects/** — has an outcome and a finish line. Closes when done.
- **recipes/** — one cookable recipe per note, parsed from any source (incl. reel/TikTok links).
- **learning/** — concepts and skills *you* are mastering (distinct from `concepts/` which is extracted from sources).
- **people/** — relationships, shared context, birthdays, follow-ups.
- **ideas/** — sparks and half-thoughts (graphic design, product, writing).
- **resources/** — books, courses, tools worth referencing.
- **sources/** — one summary page per ingested raw source. Built by ingestion.
- **concepts/** — ideas, patterns, frameworks extracted from sources. Built by ingestion.
- **entities/** — people, orgs, products, repos, places. Built by ingestion.

## Linking

- Wikilinks are `[[Note Name]]` — filenames are unique, no paths needed.
- Link liberally. A link to a page that doesn't exist yet is a *todo*, not an error.
- When a source introduces a concept or entity, create/extend its page and link both ways.

## Ingestion contract

1. Read the source from `.raw/`. Never modify it.
2. Check `.raw/.manifest.json` — skip if the hash is unchanged (unless "force").
3. Write a `sources/` summary + any `concepts/`, `entities/`, and domain pages it touches (typically 8–15 pages for a rich source, fewer for a thin one).
4. Cross-reference everything. Flag contradictions in the relevant page and in [[log]].
5. Update [[index]] counts, append to [[log]], overwrite [[hot]], and record the source in `.raw/.manifest.json`.

## The filter

When uncertain whether something is worth keeping, **file it conservatively** (e.g. an `ideas/` stub or a flagged source) rather than discarding. Low-confidence or ambiguous items get a `status: needs-review` flag, never a silent drop.
