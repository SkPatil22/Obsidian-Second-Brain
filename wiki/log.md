---
type: meta
title: "Log"
created: 2026-06-24
updated: 2026-07-21
tags: [meta, log]
---

# Log — Operations Record

Chronological record of every operation against this vault. Newest first. The chronological half of the [[Index and Log]] navigation pattern — [[index]] is the catalog half.
Entries use a grep-able prefix: `grep "^## \[" log.md | tail -5` → recent ops.

## [2026-07-20] librarian | Nightly maintenance pass

- **LINK (4 files, 3 new wikilinks):** source→vault bidirectional closes — `Second Brain Roadmap` → `[[overview]]` (SBR is the build-out plan; overview is the current vault state; overview→SBR existed since 2026-07-06; SBR→overview was absent — now added to intro: "For the current state of the vault, see [[overview]]"; 1 link); `Karpathy - LLM Wiki` source → `[[overview]]` (source essay is the blueprint; overview is the living realization it produced; overview→source existed since initial ingest; source's "Relevance to this vault" section linked to SBR but not to the current vault state — now added inline: "and [[overview]] for the current state of the vault"; 1 link). Domain index reverse close — `travel/_index` → `[[projects/_index|Projects]]` (projects/_index already noted "(Trips live under [[travel/_index|Travel]])" since the travel carve-out; travel/_index footer linked to recipes and resources but not back to projects despite the lineage; added to footer note; 1 link).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed.
- **FLAG — CRITICAL:** Seattle trip warning updated 1→TOMORROW (today 2026-07-20, departure 2026-07-21). Updated `Seattle Trip 2026-07` warning callout to "1 day to departure (Jul 21 — TOMORROW)" with last-chance urgency. Rental car, Port Angeles lodging, Kashiba/Pink Door reservations remain open — **book tonight**.
- **DATE FIXES (5 files):** `projects/Second Brain Roadmap` 2026-07-13→2026-07-20; `sources/Karpathy - LLM Wiki` 2026-07-04→2026-07-20; `travel/_index` 2026-07-19→2026-07-20; `travel/Seattle Trip 2026-07` 2026-07-19→2026-07-20; `wiki/index.md` 2026-07-19→2026-07-20.
- **Report:** [[meta/maintenance/2026-07-20]]

## [2026-07-19] librarian | Nightly maintenance pass

- **LINK (6 files, 8 new wikilinks):** trip cluster last edges — `Mount Rainier National Park` → `[[Raspberry Chocolate Cake]]` (Rainier is visited Wed Jul 22; raspberries sourced at Pike Place the day before; post-trip bake on return — only park entity in the 8-node trip cluster not yet linked to the cake; 1 link); `Olympic National Park` → `[[Raspberry Chocolate Cake]]` (same logic — Olympic is Thu–Fri Jul 23–24, the later leg; post-trip bake timing follows the full trip including this; 1 link); `Raspberry Chocolate Cake` → `[[Mount Rainier National Park]]` + `[[Olympic National Park]]` (bidirectional close; cake page was missing direct nav to the park destinations of the trip during which raspberries are sourced — navigable via Seattle Trip but not directly; 2 links). Domain index cross-nav — `travel/_index` → `[[recipes/_index|Recipes]]` + `[[resources/_index|Resources]]` (travel index listed trip pages and entity destinations but had no pointer to the domain indexes where trip food prep and trip gear live; trip food prep = Thin Ribeye + Raspberry Cake in recipes; trip gear = Running Shoes in resources; 2 links); `recipes/_index` → `[[travel/_index|Travel]]` (closing the reverse — recipes listed learning but not the travel domain where trip-specific sourcing/prep lives; Pike Place sourcing is the explicit connection; 1 link); `resources/_index` → `[[travel/_index|Travel]]` (Running Shoes - Flat Feet is trip gear; resources index had no pointer to where that trip context lives; 1 link).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 3→2 days (today 2026-07-19, departure 2026-07-21 = 2 days). Rental car, Port Angeles lodging, Kashiba/Pink Door reservations — **book now, these are critical path items 2 days from departure**.
- **DATE FIXES (8 files):** `entities/Mount Rainier National Park` 2026-07-07→2026-07-19; `entities/Olympic National Park` 2026-07-07→2026-07-19; `recipes/Raspberry Chocolate Cake` 2026-07-16→2026-07-19; `travel/_index` 2026-07-09→2026-07-19; `recipes/_index` 2026-07-14→2026-07-19; `resources/_index` 2026-07-15→2026-07-19; `travel/Seattle Trip 2026-07` 2026-07-18→2026-07-19; `wiki/index.md` 2026-07-18→2026-07-19.
- **Report:** [[meta/maintenance/2026-07-19]]

## [2026-07-18] librarian | Nightly maintenance pass

- **LINK (10 files, 15 new wikilinks):** domain overview completeness — `overview.md` opening sentence listed "work, finance" as bare text and omitted three vault folders entirely; now all nine top-level domains linked: `[[areas/_index|areas]]` + `[[people/_index|people]]` + `[[resources/_index|resources]]` (3 links); knowledge-layer triangle bidirectional close — `sources/_index` → `[[concepts/_index|Concepts]]` + `[[entities/_index|Entities]]` (audit trail was one-directional; sources produce these; 2 links); `concepts/_index` ↔ `entities/_index` (co-produced in same ingest pass; neither linked the other; 2 links); Memex → `[[Index and Log]]` (Memex is about navigable associative trails; IaL is the vault's navigation implementation; missing from the "modern realization" paragraph; 1 link); domain cross-navigation — `learning/_index` → `[[areas/_index]]` + `[[ideas/_index]]` (skills serve life areas; ideas become learning; 2 links); `ideas/_index` → `[[learning/_index]]` (bidirectional; 1 link); `areas/_index` → `[[people/_index]]` + `[[resources/_index]]` (relationships and tools live inside life areas; 2 links); baking↔trip cluster last open edge — `Baking - Berries and Moisture` ↔ `Seattle Trip 2026-07` (Tue Jul 21 Pike Place is when fresh-vs-frozen decision is made; technique page governs that purchase; neither linked the other despite sharing the Pike Place moment; 2 links).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 4→3 days (today 2026-07-18, departure 2026-07-21 = 3 days). Rental car, Port Angeles lodging, Kashiba/Pink Door reservations remain open — **book now**.
- **DATE FIXES (11 files):** `wiki/overview.md` 2026-07-17→2026-07-18; `wiki/entities/Memex.md` 2026-07-12→2026-07-18; `wiki/sources/_index.md` 2026-07-10→2026-07-18; `wiki/concepts/_index.md` 2026-07-17→2026-07-18; `wiki/entities/_index.md` 2026-07-17→2026-07-18; `wiki/learning/_index.md` 2026-07-16→2026-07-18; `wiki/ideas/_index.md` 2026-07-17→2026-07-18; `wiki/areas/_index.md` 2026-07-15→2026-07-18; `wiki/recipes/Baking - Berries and Moisture.md` 2026-07-14→2026-07-18; `wiki/travel/Seattle Trip 2026-07.md` 2026-07-17→2026-07-18; `wiki/index.md` 2026-07-17→2026-07-18.
- **Report:** [[meta/maintenance/2026-07-18]]

## [2026-07-17] librarian | Nightly maintenance pass

- **LINK (9 files, 17 new wikilinks):** conventions schema-layer completeness — folder descriptions for `sources/`, `concepts/`, `entities/` all said "Built by ingestion" with bare "ingestion" text; now each links `[[Ingest Query Lint|ingestion]]` (3 links — these are the ingestion-layer folders whose very description names the concept without linking it); `travel/` folder description said "reusable `entities/` pages" with a backtick code span — now `[[entities/_index|entities/]]` (navigable from the canonical folder definition); `learning/` folder description said "distinct from `concepts/`" — now `[[concepts/_index|concepts/]]` (the distinction is only useful if both sides are navigable); Creating new categories example — "(Travel started this way.)" → "([[travel/_index|Travel]] started this way.)" (the paragraph introduces the folder-creation pattern; Travel is the living example — it should be navigable); ingestion contract step 3 — "`sources/` summary + any `concepts/`, `entities/`" → `[[sources/_index|sources/]]` + `[[concepts/_index|concepts/]]`, `[[entities/_index|entities/]]` (the Ingest step specification names all three knowledge-layer folder types with bare backtick spans — the most read part of conventions should link to what it names, 3 links); front-page domain navigation — `overview.md` opening sentence listed "recipes, projects, learning, and ideas" as bare domain names (after `travel` was linked 2026-07-16, the others remained bare) — now each links its `_index` (4 links: `[[recipes/_index|recipes]]`, `[[projects/_index|projects]]`, `[[learning/_index|learning]]`, `[[ideas/_index|ideas]]`); knowledge-layer cross-navigation — `entities/_index` and `concepts/_index` both had no pointer to `[[sources/_index|Sources]]` — entities and concepts are extracted FROM sources; the knowledge-layer triangle (sources→concepts/entities) was one-directional: now both indexes link to sources (2 links); `entities/_index` ↔ `people/_index` — entities/_index listed its pages without noting the curated-relationships distinction; `people/_index` added `[[entities/_index]]` 2026-07-16 but the reverse was absent; disambiguation now bidirectional (1 link); `ideas/_index` → `[[areas/_index|Areas]]` — ideas with no finish line that mature into ongoing domains belong in areas; the distinction between one-off sparks and ongoing life concerns wasn't navigable from ideas/_index (1 link); `projects/_index` — updated SBR description to add "media parsing" (Phase 3 live).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed. Empty domain folders retained.
- **FLAG — date counter:** Seattle Trip warning updated 5→4 days (today 2026-07-17, departure 2026-07-21 = 4 days). Rental car, Port Angeles lodging, and restaurant reservations (Kashiba, Pink Door) remain open.
- **DATE FIXES (9 files):** `wiki/overview.md` 2026-07-16→2026-07-17; `wiki/meta/conventions.md` 2026-07-16→2026-07-17; `wiki/entities/_index.md` 2026-07-10→2026-07-17; `wiki/concepts/_index.md` 2026-07-14→2026-07-17; `wiki/ideas/_index.md` 2026-06-24→2026-07-17; `wiki/travel/Seattle Trip 2026-07.md` 2026-07-16→2026-07-17; `wiki/projects/_index.md` 2026-06-30→2026-07-17; `wiki/index.md` 2026-07-16→2026-07-17; `wiki/log.md` 2026-07-16→2026-07-17.
- **Report:** [[meta/maintenance/2026-07-17]]

## [2026-07-16] librarian | Nightly maintenance pass

- **LINK (8 files, 8 new wikilinks):** concept-navigation gaps closed — `meta/conventions` → `[[Index and Log]]` (step 5 of the ingestion contract references `[[index]]` and `[[log]]` as files but never names the concept that defines the pattern; closes the schema ↔ navigation concept gap); `wiki/index.md` → `[[Index and Log]]` (the master index IS the catalog half of the Index and Log pattern — never linked to the concept explaining why it exists; now does); `wiki/log.md` → `[[Index and Log]]` (same gap for the chronological half — preamble now names the concept); trip-prep triangle completed — `Running Shoes - Flat Feet` → `[[Raspberry Chocolate Cake]]` + `Raspberry Chocolate Cake` → `[[Running Shoes - Flat Feet]]` (the trip-prep three-way triangle was missing this edge: Thin Ribeye ↔ Running Shoes ✅ 2026-07-12; Thin Ribeye ↔ Raspberry Cake ✅ already; Running Shoes ↔ Raspberry Cake was the sole remaining gap — both are Tue Jul 21 Pike Place day-1 logistics items for the same Seattle trip); front-page travel gap — `overview.md` → `[[travel/_index|Travel]]` (overview listed "recipes, projects, learning, and ideas" as life domains but omitted travel — currently the vault's most active domain); disambiguation close — `people/_index` → `[[entities/_index]]` (people/ = curated relationships; entities/ = ingestion-derived person facts; Andrej Karpathy is the standing example of the distinction — now navigable from people/); `learning/_index` → `[[resources/_index]]` (bidirectional close: `resources/_index` → `learning/_index` was added 2026-07-15; learning never reciprocated — now both point to each other).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed. Empty domain folders (areas, people, ideas, learning) retained — anti-sprawl.
- **FLAG — date counter:** Seattle Trip warning updated 6→5 days (today 2026-07-16, departure 2026-07-21 = 5 days). Action items (rental car, Port Angeles lodging, Kashiba/Pink Door reservations) remain open.
- **DATE FIXES (10 files):** `meta/conventions` 2026-07-13→2026-07-16; `wiki/index.md` 2026-07-15→2026-07-16; `wiki/overview.md` 2026-07-14→2026-07-16; `wiki/people/_index.md` 2026-06-24→2026-07-16; `wiki/learning/_index.md` 2026-06-24→2026-07-16; `Running Shoes - Flat Feet` 2026-07-12→2026-07-16; `Raspberry Chocolate Cake` 2026-07-15→2026-07-16; `Seattle Trip 2026-07` 2026-07-15→2026-07-16; `wiki/log.md` 2026-07-15→2026-07-16; `wiki/hot.md` 2026-07-15→2026-07-16.
- **Report:** [[meta/maintenance/2026-07-16]]

## [2026-07-15] librarian | Nightly maintenance pass

- **LINK (4 files, 4 new wikilinks):** trip↔recipe bidirectional close — `Seattle Trip 2026-07` → `[[Raspberry Chocolate Cake]]` (Logistics section: Tue Jul 21 city day at Pike Place is the natural window to source fresh Washington raspberries for the cake filling — closes the last missing edge between the trip cluster and the recipe cluster); `Raspberry Chocolate Cake` → `[[Seattle Trip 2026-07]]` (bidirectional close — the cake's Pike Place note already implied the trip context; making the trip directly navigable from the cake page). Disambiguation triad completed — `resources/_index` → `[[learning/_index]]` (reference material/gear vs. skills being mastered — the last domain-adjacent index that didn't point to learning; `concepts/_index` and `recipes/_index` already did); `areas/_index` → `[[learning/_index]]` (life domains vs. active skills mastery; areas already pointed to projects, now also to learning).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed. Empty domain folders retained.
- **FLAG — date counter:** Seattle Trip warning updated 7→6 days (2026-07-15 departure count, Jul 21).
- **DATE FIXES (7 files):** `Seattle Trip 2026-07` 2026-07-14→2026-07-15; `Raspberry Chocolate Cake` 2026-07-14→2026-07-15; `resources/_index` 2026-06-29→2026-07-15; `areas/_index` 2026-06-24→2026-07-15; `index` 2026-07-14→2026-07-15; `log` 2026-07-14→2026-07-15; `hot` 2026-07-14→2026-07-15.
- **Report:** [[meta/maintenance/2026-07-15]]

## [2026-07-14] librarian | Nightly maintenance pass

- **LINK (7 files, 8 new wikilinks):** Recipe ↔ travel cluster densified — `Raspberry Chocolate Cake` → `[[Pike Place Market]]` (Pike Place produce stalls are the natural source for fresh Washington raspberries — the cake filling calls for 12 oz fresh; closes the last unlinked pair between the recipe cluster and the travel cluster); `Pike Place Market` → `[[Raspberry Chocolate Cake]]` (bidirectional close); `Baking - Berries and Moisture` → `[[Pike Place Market]]` (the fresh-vs-frozen berry section maps directly to Pike Place produce sourcing — "fresh → fillings, décor: best appearance" aligns with market-stall raspberries); `Pike Place Market` → `[[Baking - Berries and Moisture]]` (bidirectional close — completes the recipe ↔ travel triangle for all three recipe pages). Front-page navigation — `overview` → `[[hot]]` + `[[log]]` (CLAUDE.md defines 4 entry-point files: overview, index, conventions, hot — overview linked to index and conventions but never to hot or log; now all 4 cross-referenced from the front page). Disambiguating cross-links — `recipes/_index` → `[[learning/_index]]` (cooking techniques live in recipes/, non-cooking skills live in learning/; learning said so but recipes never reciprocated — now bidirectional); `concepts/_index` → `[[learning/_index]]` (concepts are extracted automatically; learning is what you're actively mastering — important distinction; no prior pointer from concepts to learning).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed. Empty domain folders retained.
- **FLAG — date counter:** Seattle Trip warning updated 8→7 days (2026-07-14 departure count, Jul 21).
- **DATE FIXES (10 files):** `Raspberry Chocolate Cake` 2026-06-30→2026-07-14; `Baking - Berries and Moisture` 2026-07-11→2026-07-14; `Pike Place Market` 2026-07-08→2026-07-14; `overview` 2026-07-11→2026-07-14; `recipes/_index` 2026-06-30→2026-07-14; `concepts/_index` 2026-07-10→2026-07-14; `Seattle Trip 2026-07` 2026-07-13→2026-07-14; `index` 2026-07-13→2026-07-14; `log` 2026-07-13→2026-07-14; `hot` 2026-07-13→2026-07-14.
- **Report:** [[meta/maintenance/2026-07-14]]

## [2026-07-13] librarian | Nightly maintenance pass

- **LINK (2 files, 2 new wikilinks):** PKM source-link gaps closed — `meta/conventions` → `[[Karpathy - LLM Wiki]]` (conventions is the schema layer built from the source essay; Karpathy-LLM-Wiki already linked back to conventions, but conventions never linked to the source — last outbound gap from the schema file); `Second Brain Roadmap` → `[[Karpathy - LLM Wiki]]` (SBR is the staged implementation of the source essay; source already linked to SBR via "see [[Second Brain Roadmap]] for how the implementation is staged"; SBR linked to [[LLM Wiki Pattern]] and [[Andrej Karpathy]] but not the source document — last reverse link gap in the PKM cluster).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed. Empty domain folders retained.
- **FLAG — date counter:** Seattle Trip warning updated 9→8 days (2026-07-13 departure count, Jul 21).
- **DATE FIXES (6 files):** `meta/conventions` 2026-07-09→2026-07-13; `Second Brain Roadmap` 2026-07-10→2026-07-13; `Seattle Trip 2026-07` 2026-07-12→2026-07-13; `index` 2026-07-12→2026-07-13; `log` 2026-07-12→2026-07-13; `hot` 2026-07-12→2026-07-13.
- **Report:** [[meta/maintenance/2026-07-13]]

## [2026-07-12] librarian | Nightly maintenance pass

- **LINK (5 files, 5 new wikilinks):** PKM cluster last gaps — `Wiki vs RAG` → `[[Ingest Query Lint]]` (the "compile-once, at ingest" body text described the Ingest operation without naming it; IQL was the only core concept not linked from Wiki vs RAG — all 5 others now complete); `Obsidian` → `[[Ingest Query Lint]]` (Web Clipper feeds the ingest loop — the first step of Ingest is getting sources into `.raw/`; Obsidian's feature that does exactly that had no pointer to the concept); `Memex` → `[[Ingest Query Lint]]` (Bush's "who does the maintenance" open problem is answered specifically by the Ingest/Lint loops; the maintenance sentence now names the workflow). Travel cluster last gap — `Running Shoes - Flat Feet` → `[[Thin Ribeye Recipes]]` + `Thin Ribeye Recipes` → `[[Running Shoes - Flat Feet]]` (bidirectional close; every other pair in the 5-node travel cluster was already connected; Running Shoes ↔ Thin Ribeye was the sole remaining missing edge — both are primary logistics prep for the same Seattle trip park days).
- **ORPHANS:** none; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all correctly filed. Empty domain folders retained.
- **FLAG — date counter:** Seattle Trip warning updated 10→9 days (2026-07-12 departure count).
- **DATE FIXES (6 files):** `Wiki vs RAG` 2026-07-09→2026-07-12; `Obsidian` 2026-07-09→2026-07-12; `Memex` 2026-07-08→2026-07-12; `Running Shoes - Flat Feet` 2026-07-02→2026-07-12; `Thin Ribeye Recipes` 2026-07-08→2026-07-12; `Seattle Trip 2026-07` 2026-07-11→2026-07-12.
- **Report:** [[meta/maintenance/2026-07-12]]

## [2026-07-11] librarian | Nightly maintenance pass

- **LINK (1 file, 1 new wikilink):** front-page gap — `overview` → `[[meta/conventions]]` (the vault front page described how the vault works and pointed to `[[index]]` but never linked to the schema/rules document; `meta/conventions` is the operational contract every note follows — reachable from `index` in 1 hop but not from `overview` directly; now 1-hop from the front page).
- **STRUCTURE — frontmatter fix (1 file):** `Baking - Berries and Moisture` — `type: technique` → `type: recipe` (`technique` is not a valid type per [[meta/conventions]]); removed vestigial `area: creative` field (leftover from when the page lived in `learning/` before the 2026-06-28 move to `recipes/`); `tags: [learning, baking, technique]` → `tags: [recipe, baking, technique]`.
- **ORPHANS:** no orphans; all pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE (folders):** no moves; all correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 11→10 days (2026-07-11 departure count).
- **DATE FIXES (6 files):** `overview` 2026-07-09→2026-07-11; `Baking - Berries and Moisture` 2026-06-30→2026-07-11; `Seattle Trip 2026-07` 2026-07-10→2026-07-11; `index` 2026-07-10→2026-07-11; `hot` 2026-07-10→2026-07-11; `log` 2026-07-10→2026-07-11.
- **Report:** [[meta/maintenance/2026-07-11]]

## [2026-07-10] librarian | Nightly maintenance pass

- **LINK (4 files, 4 new wikilinks):** knowledge-layer ingest gaps — `sources/_index` → `[[Ingest Query Lint]]` (description said "built automatically by ingestion" without linking the concept that names the Ingest operation; the most direct gap remaining in the knowledge-layer folder descriptions); `concepts/_index` → `[[Ingest Query Lint]]` (same — "extracted from sources" is precisely the Ingest step; all 3 knowledge-layer folders now link to Ingest Query Lint); `entities/_index` → `[[Ingest Query Lint]]` (same — "accreting facts from every source via ingestion" completes the triangle); schema-link gap — `Second Brain Roadmap` Phase 1 bullet → `[[meta/conventions]]` (meta/conventions is the schema artifact created in Phase 1; already reachable via SBR→Three-Layer Architecture→meta/conventions but now 1 hop direct; Phase 1 "plugin installed" step produced conventions).
- **ORPHANS:** no orphans; all content pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed. Empty domain folders (areas, people, ideas, learning) retained — anti-sprawl.
- **FLAG — date counter:** Seattle Trip warning updated 12→11 days (2026-07-10 departure count).
- **DATE FIXES (6 files):** `sources/_index` 2026-06-24→2026-07-10 (stale since setup — first edit); `concepts/_index` 2026-06-28→2026-07-10; `entities/_index` 2026-06-28→2026-07-10; `projects/Second Brain Roadmap` 2026-07-05→2026-07-10; `travel/Seattle Trip 2026-07` 2026-07-09→2026-07-10; `index` 2026-07-08→2026-07-10.
- **Report:** [[meta/maintenance/2026-07-10]]

## [2026-07-09] librarian | Nightly maintenance pass

- **LINK (6 files, 8 new wikilinks):** schema-layer gap closed — `meta/conventions` → `[[LLM Wiki Pattern]]` + `[[Three-Layer Architecture]]` (preamble now identifies conventions as the schema layer that encodes these patterns; largest single gap in the vault — the schema file never linked to what it implements) + `[[Ingest Query Lint]]` (Ingestion contract heading now names the Ingest operation); travel hub gap — `travel/_index` → `[[Mount Rainier National Park]]` + `[[Olympic National Park]]` + `[[Pike Place Market]]` (travel index said "places become entity pages" but listed none; added Destination entities subsection); bidirectional gap closed — `Index and Log` → `[[Obsidian]]` (Dataview extends the index layer at scale; Obsidian→IaL added same pass); `Obsidian` → `[[Index and Log]]` (Dataview bullet now names the concept it extends); `Wiki vs RAG` → `[[overview]]` ("This vault" in examples column was bare text; now links to the vault front page); `overview` → `[[Index and Log]]` (added concept pointer alongside the [[index]] file link).
- **ORPHANS:** no orphans; all content pages maintain ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 13→12 days (2026-07-09 departure count).
- **DATE FIXES (7 files):** `meta/conventions` 2026-06-24→2026-07-09; `travel/_index` 2026-07-01→2026-07-09; `concepts/Index and Log` 2026-07-06→2026-07-09; `entities/Obsidian` 2026-07-05→2026-07-09; `concepts/Wiki vs RAG` 2026-07-07→2026-07-09; `overview` 2026-07-06→2026-07-09; `travel/Seattle Trip 2026-07` 2026-07-08→2026-07-09.
- **Report:** [[meta/maintenance/2026-07-09]]

## [2026-07-08] librarian | Nightly maintenance pass

- **LINK (4 files, 6 new wikilinks):** travel food-prep cluster completed — `Thin Ribeye Recipes` → `[[Mount Rainier National Park]]` + `[[Olympic National Park]]` (parks→Thin Ribeye was added 2026-07-07; reverse used only bare text "Rainier/Olympic" without wikilinks — bidirectional triangle now fully navigable); `Thin Ribeye Recipes` → `[[Pike Place Market]]` (day-1 food market as source of ingredients for park-day meal prep; closing the market→recipe→parks planning chain); `Pike Place Market` → `[[Thin Ribeye Recipes]]` (bidirectional close — day-1 market day is when you shop for the park-day bowls); PKM cluster tightened — `Ingest Query Lint` → `[[meta/conventions]]` (conventions file has the explicit Ingestion contract; concept page had no pointer to the vault-specific implementation); `Memex` → `[[Three-Layer Architecture]]` (the Three-Layer Architecture is the structural realization of Bush's vision; Memex linked to Obsidian and LLM Wiki Pattern without naming the organizing architecture).
- **ORPHANS:** no new orphans; all pages have ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 14→13 days (2026-07-08 departure count).
- **DATE FIXES (5 files):** `recipes/Thin Ribeye Recipes` 2026-07-05→2026-07-08; `entities/Pike Place Market` 2026-07-03→2026-07-08; `concepts/Ingest Query Lint` 2026-07-07→2026-07-08; `entities/Memex` 2026-07-07→2026-07-08; `travel/Seattle Trip 2026-07` 2026-07-07→2026-07-08.
- **Report:** [[meta/maintenance/2026-07-08]]

## [2026-07-07] librarian | Nightly maintenance pass

- **LINK (7 files, 7 new wikilinks):** bidirectional gap closed — `Memex` → `[[Second Brain Roadmap]]` (SBR already links to Memex as "modern realization"; Memex's closing sentence described the realization without linking to the roadmap); bidirectional gap closed — `qmd` → `[[Ingest Query Lint]]` (IQL→qmd existed for the Query-at-scale note; qmd never linked back to the specific operation it extends); PKM cluster tightened — `Ingest Query Lint` → `[[Wiki vs RAG]]` (Ingest = compile-once = the wiki-not-RAG operation; contrast was described but unlinked in the Ingest section); `Three-Layer Architecture` → `[[Wiki vs RAG]]` (architecture makes wiki-not-RAG structurally possible; unlinked in the opening description); `Wiki vs RAG` → `[[Three-Layer Architecture]]` (the wiki answer is "built by the Three-Layer Architecture"; CKA was named without its producing architecture); travel cluster — `Mount Rainier National Park` → `[[Thin Ribeye Recipes]]` (park days = meal prep days; Thin Ribeye→Seattle Trip→Rainier existed but Rainier→Thin Ribeye missing); `Olympic National Park` → `[[Thin Ribeye Recipes]]` (same; multi-day Olympic leg makes portable meal prep even more relevant).
- **ORPHANS:** no new orphans; all pages have ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 15→14 days (2026-07-07 departure count).
- **DATE FIXES (8 files):** `entities/Memex` 2026-07-04→2026-07-07; `entities/qmd` 2026-07-05→2026-07-07; `concepts/Ingest Query Lint` 2026-07-06→2026-07-07; `concepts/Three-Layer Architecture` 2026-07-05→2026-07-07; `concepts/Wiki vs RAG` 2026-07-04→2026-07-07; `entities/Mount Rainier` 2026-07-02→2026-07-07; `entities/Olympic` 2026-07-02→2026-07-07; `travel/Seattle Trip 2026-07` 2026-07-06→2026-07-07.
- **Report:** [[meta/maintenance/2026-07-07]]

## [2026-07-06] librarian | Nightly maintenance pass

- **LINK (4 files, 4 new wikilinks):** source-gap closed — `overview` → `[[Karpathy - LLM Wiki]]` (the vault front page linked to the concept and the author but never to the foundational source document itself; added inline at first mention of the pattern); system-nav gap — `index` → `[[Second Brain Roadmap]]` (System section listed Conventions/Log/Hot/Overview but not the build-out roadmap, which is equally foundational); concept-compounding gap — `Ingest Query Lint` → `[[Compounding Knowledge Artifact]]` in Query section (the Ingest section already linked it; the Query section says "explorations **compound**" without linking the concept that names that property); RAG contrast unlinked — `Index and Log` → `[[Wiki vs RAG]]` ("no embedding RAG needed at that scale" names the exact contrast the Wiki vs RAG concept documents; the word RAG was bare).
- **ORPHANS:** no new orphans; all 42 pages have ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 16→15 days (2026-07-06 departure count).
- **DATE FIXES (5 files):** `wiki/overview` 2026-07-04→2026-07-06; `wiki/index` 2026-07-05→2026-07-06; `concepts/Ingest Query Lint` 2026-07-05→2026-07-06; `concepts/Index and Log` 2026-07-05→2026-07-06; `travel/Seattle Trip 2026-07` 2026-07-05→2026-07-06.
- **Report:** [[meta/maintenance/2026-07-06]]

## [2026-07-05] librarian | Nightly maintenance pass

- **LINK (10 files, 12 new wikilinks):** bidirectional gap — `Obsidian` → `[[Memex]]` (Memex→Obsidian added 2026-07-04 but reverse absent; added paragraph connecting Obsidian graph view to Bush's "associative trails"); bidirectional gap — `qmd` → `[[Compounding Knowledge Artifact]]` (CKA→qmd added 2026-07-04 but reverse absent) + `[[Wiki vs RAG]]` (qmd keeps the system on the wiki side at scale); `Andrej Karpathy` → `[[Index and Log]]` (he originated all 5 core patterns; Facts list had only 4); `Three-Layer Architecture` → `[[Index and Log]]` (index+log live in the wiki layer; omitted from the layer description); `Compounding Knowledge Artifact` → `[[Obsidian]]` (how you read the artifact) + `[[Index and Log]]` (how you navigate it); `Index and Log` → `[[Compounding Knowledge Artifact]]` (the index is the navigation layer of the CKA); `Ingest Query Lint` → `[[qmd]]` (Query step at scale); `Second Brain Roadmap` → `[[Wiki vs RAG]]` + `[[Memex]]` (the roadmap *is* a wiki-not-RAG Memex realization — both missing from the intro); `Seattle Trip 2026-07` → `[[Thin Ribeye Recipes]]` (meal prep for national park days — 4-day shelf life, portable); `Thin Ribeye Recipes` → `[[Seattle Trip 2026-07]]` (bidirectional close for the portability cluster).
- **ORPHANS:** no new orphans; Thin Ribeye Recipes strengthened (already reachable via sibling recipes; now also from Seattle Trip).
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 17→16 days (2026-07-05 departure count).
- **DATE FIXES (10 files):** `entities/Andrej Karpathy` 2026-07-03→2026-07-05; `entities/Obsidian` 2026-07-03→2026-07-05; `entities/qmd` 2026-07-02→2026-07-05; `concepts/Three-Layer Architecture` 2026-07-02→2026-07-05; `concepts/Compounding Knowledge Artifact` 2026-07-04→2026-07-05; `concepts/Index and Log` 2026-07-02→2026-07-05; `concepts/Ingest Query Lint` 2026-07-03→2026-07-05; `projects/Second Brain Roadmap` 2026-07-02→2026-07-05; `travel/Seattle Trip 2026-07` 2026-07-04→2026-07-05; `recipes/Thin Ribeye Recipes` 2026-06-29→2026-07-05.
- **Report:** [[meta/maintenance/2026-07-05]]

## [2026-07-04] librarian | Nightly maintenance pass

- **LINK (5 files, 7 new wikilinks):** author-linking gap closed — `Karpathy - LLM Wiki` source body had 3 bare "Karpathy" references with no `[[Andrej Karpathy]]` link (intro, "Why it works," "Contradictions" section); bidirectional gap closed — `Wiki vs RAG` → `[[Memex]]` (Memex page already linked to Wiki vs RAG; reverse was absent since initial ingest); overview densified — `overview` → `[[Wiki vs RAG]]` (inline "unlike RAG" was unlinked) + `[[Obsidian]]` (browsing layer never named on the vault front page); scale-out gap — `Compounding Knowledge Artifact` → `[[qmd]]` (retrieval layer that extends the artifact was unmentioned on the concept page); modern-realization gap — `Memex` → `[[Obsidian]]` (concrete closing sentence naming the tool that realizes Bush's vision).
- **ORPHANS:** no new orphans; all 5 affected nodes were already reachable.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 18→17 days (2026-07-04 departure count).
- **DATE FIXES (6 files):** `sources/Karpathy - LLM Wiki` 2026-06-28→2026-07-04 (longest-stale source page, stuck since initial librarian pass); `concepts/Wiki vs RAG` 2026-07-02→2026-07-04; `wiki/overview` 2026-07-02→2026-07-04; `concepts/Compounding Knowledge Artifact` 2026-07-02→2026-07-04; `entities/Memex` 2026-07-02→2026-07-04; `travel/Seattle Trip 2026-07` 2026-07-03→2026-07-04.
- **Report:** [[meta/maintenance/2026-07-04]]

## [2026-07-03] librarian | Nightly maintenance pass

- **LINK (4 files, 5 new wikilinks):** attribution gap closed — `Ingest Query Lint` → `[[Andrej Karpathy]]` (2 places: intro + closing citation); `Andrej Karpathy` → `[[Ingest Query Lint]]` (Facts list now covers all 4 concepts he originated); bidirectional gaps restored — `Pike Place Market` → `[[Running Shoes - Flat Feet]]` (Running Shoes→Pike Place was added 2026-07-02 but reverse was absent); `Obsidian` → `[[qmd]]` (qmd→Obsidian existed since 2026-07-02 but Obsidian→qmd was absent).
- **ORPHANS:** no new orphans; all 4 affected nodes were already reachable.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 19→18 days (2026-07-03 departure count).
- **DATE FIXES (5 files):** `concepts/Ingest Query Lint` 2026-06-28→2026-07-03 (oldest stale file in the vault; untouched since initial ingest); `entities/Pike Place Market` 2026-07-01→2026-07-03; `entities/Obsidian` 2026-07-02→2026-07-03; `entities/Andrej Karpathy` 2026-07-02→2026-07-03; `travel/Seattle Trip 2026-07` 2026-07-02→2026-07-03.
- **Report:** [[meta/maintenance/2026-07-03]]

## [2026-07-02] librarian | Nightly maintenance pass

- **LINK (14 files, 19 new wikilinks):** PKM cluster — closed the last remaining gaps: `Three-Layer Architecture` → `[[Compounding Knowledge Artifact]]`; `Index and Log` → `[[LLM Wiki Pattern]]` + `[[Three-Layer Architecture]]`; `Compounding Knowledge Artifact` → `[[Ingest Query Lint]]`; `Wiki vs RAG` → `[[Index and Log]]`; `LLM Wiki Pattern` → `[[Second Brain Roadmap]]`; `Second Brain Roadmap` → `[[Three-Layer Architecture]]` + `[[Compounding Knowledge Artifact]]`; `overview` → `[[Compounding Knowledge Artifact]]`. Entity enrichment: `Andrej Karpathy` → `[[Three-Layer Architecture]]` + `[[Compounding Knowledge Artifact]]` + `[[Wiki vs RAG]]`; `Memex` → `[[Wiki vs RAG]]`; `qmd` → `[[Andrej Karpathy]]` + `[[Obsidian]]`; `Obsidian` → `[[Compounding Knowledge Artifact]]`. Travel+city triangulation: both national parks → `[[Pike Place Market]]`; `Running Shoes` → `[[Pike Place Market]]`.
- **ORPHANS:** no new orphans; `[[Pike Place Market]]` strengthened (was weakest node, only 1 inbound content link; now 4).
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; all folders correctly filed.
- **FLAG — date counter:** Seattle Trip warning updated 20→19 days (2026-07-02 departure count).
- **DATE FIXES (16 files):** all edited files stamped 2026-07-02; plus `index.md` and 5 concept entities carrying stale 2026-06-28 dates.
- **Report:** [[meta/maintenance/2026-07-02]]

## [2026-07-01] librarian | Nightly maintenance pass

- **LINK (8 files, 12 new wikilinks):** densified travel + fitness cluster — added `[[Running Shoes - Flat Feet]]` to both national park entities (and reverse); added `[[Olympic National Park]]` + `[[Mount Rainier National Park]]` to Pike Place Market See also; densified PKM cluster — `Three-Layer Architecture` → `[[Andrej Karpathy]]` + `[[Second Brain Roadmap]]`; `qmd` → `[[Second Brain Roadmap]]`; `overview` → `[[Three-Layer Architecture]]` + `[[Ingest Query Lint]]`; `Second Brain Roadmap` → `[[Obsidian]]`.
- **ORPHANS:** no new orphans — all content pages have ≥1 inbound content link.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves; fitness/Running Shoes stays in resources/ (anti-sprawl: single note).
- **FLAG — Skyline Trail footwear:** Skyline Trail at Rainier is ~5.5 mi (Metcon 6's stated upper limit). Added `[!warning]` callout in [[Running Shoes - Flat Feet]] Buying Decision section with specific route advice.
- **FLAG — Seattle trip urgency:** 20 days to Jul 21 departure. Added `[!warning]` callout to [[Seattle Trip 2026-07]] action items flagging rental car + Port Angeles as critical path.
- **DATE FIXES (10 files):** qmd, Mount Rainier, Olympic, Pike Place Market, Three-Layer Architecture, overview, Second Brain Roadmap, Running Shoes, Seattle Trip, travel/_index — all stamped 2026-07-01.
- **Report:** [[meta/maintenance/maintenance-2026-07-01]]

## [2026-06-30] librarian | Nightly maintenance pass

- **LINK (3 files, 5 new wikilinks):** triangulated the recipes cluster — added [[Thin Ribeye Recipes]] to `Raspberry Chocolate Cake` and `Baking - Berries and Moisture` See Also sections; added [[Andrej Karpathy]] to `concepts/Index and Log.md` (ghost link from 2026-06-28 pass).
- **ORPHANS:** [[Thin Ribeye Recipes]] had no content-page inbound links; now linked from both sibling recipe pages.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves. Anti-sprawl check: 4 empty domain folders retained (areas, people, ideas, learning) — no category warranted yet.
- **FLAG — stale claims corrected (2 files):** `overview.md` said "scheduled routines come next" but Phase 3 is live since 2026-06-28 — corrected to Phase 4 next; `projects/_index.md` description two phases behind reality — updated to reflect Phases 2+3 live.
- **DATE FIXES (3 files):** `concepts/Index and Log.md` 2026-06-24→2026-06-30; `concepts/_index.md` 2026-06-24→2026-06-28; `recipes/_index.md` 2026-06-24→2026-06-30.
- **GHOST LINK:** 2026-06-28 log claimed [[Andrej Karpathy]] added to Index and Log concept, but link was absent from file. Added now.
- Report: [[meta/maintenance/maintenance-2026-06-30]]

## [2026-06-29] telegram | Thin ribeye recipes — healthy & portable

- Source: `.raw/tg-20260629-161204-022142-note.md` (Telegram capture).
- Request: healthy thin ribeye recipes that pack well; summary requested for Tuesday 2026-07-01 at 7pm.
- Created: [[Thin Ribeye Recipes]] (recipes) — 4 recipes: Korean bulgogi bowl, chimichurri farro bowl, Thai steak salad bowl, steak stir-fry. Includes universal technique section (pat dry, cast iron, rest + slice against the grain) and "what not to pack" guide.
- Reminder scheduled: Tuesday 2026-07-01 at 7:00 PM.

## [2026-06-29] librarian | Nightly maintenance pass

- **DATE FIXES (17 files):** corrected stale `updated` frontmatter dates the 2026-06-28 pass edited but did not stamp. Files: concepts/ (LLM Wiki Pattern, Compounding Knowledge Artifact, Wiki vs RAG, Three-Layer Architecture, Ingest Query Lint), entities/ (Andrej Karpathy, Obsidian, qmd, Memex, Mount Rainier, Olympic, `_index`), sources/ (Karpathy - LLM Wiki — also added missing `updated:` field), projects/ (Second Brain Roadmap, `_index`), resources/ (`_index`), travel/ (Seattle Trip).
- **LINK (3 files):** [[Running Shoes - Flat Feet]] ↔ [[Seattle Trip 2026-07]] cross-linked (logistics/footwear); [[Second Brain Roadmap]] → [[Andrej Karpathy]] added to intro sentence.
- **ORPHANS:** Running Shoes was reachable only via meta pages; now linked from Seattle Trip content.
- **DEDUP:** no duplicates found.
- **STRUCTURE:** no moves needed.
- **FLAG — stale claim corrected:** hot.md had "Phase 3 — Scheduled routines is next" but [[Second Brain Roadmap]] shows Phase 3 ✅ live 2026-06-28. Corrected in hot.md rewrite; Phase 4 ([[qmd]] retrieval) is the actual next phase.
- Report: [[meta/maintenance/maintenance-2026-06-29]]

## [2026-06-29] telegram | Running shoes research — flat feet

- Source: `.raw/tg-20260629-024833-076953-note.md` (Telegram capture).
- Request: best running/training shoes for super flat feet, under $200, for jogging + boxing (stability priority).
- Created: [[Running Shoes - Flat Feet]] (resources) — top picks: Nike Free Metcon 6, Reebok Nano X5 Edge, NOBULL Outwork Edge; dedicated-runner picks: Brooks Adrenaline GTS 25, Saucony Arahi 7.
- Reminder scheduled: Tuesday 2026-06-30 at 5:30 PM — push summary to Sachet via Telegram.

## [2026-06-28] librarian | Nightly maintenance pass
- **LINK (15 files):** densified the graph — added [[Obsidian]] to LLM Wiki Pattern quote; [[Andrej Karpathy]] to Wiki vs RAG, Compounding Knowledge Artifact, Memex, Index and Log; [[Memex]]+[[Andrej Karpathy]] to Compounding Knowledge Artifact; [[Three-Layer Architecture]]+[[LLM Wiki Pattern]] to Obsidian, qmd; [[Obsidian]]+[[qmd]] to Three-Layer Architecture; [[Compounding Knowledge Artifact]]+[[Three-Layer Architecture]] to Ingest Query Lint; [[Second Brain Roadmap]] to overview, Andrej Karpathy, Karpathy source; [[qmd]] to LLM Wiki Pattern list; [[Olympic National Park]] ↔ [[Mount Rainier National Park]] (sister parks, both directions).
- **STRUCTURE:** no moves needed — reorg was done 2026-06-28 already.
- **DEDUP:** no duplicates found.
- **ORPHANS:** no true orphans (every page had at least one inbound link). Semantic density improved across PKM cluster.
- **FLAG — stale status:** [[Second Brain Roadmap]] Phase 2 was marked 🟡 "needs token"; updated to ✅ live (Telegram bot active per hot.md and log). [[overview]] status section updated to match. [[Obsidian]] entity had "Phase 2" for sync — corrected to "Phase 1.5".
- **FLAG — self-link bug:** `[[Second Brain Roadmap|/brain skill]]` in Roadmap page linked to itself; replaced with plain text reference.
- Report: [[meta/maintenance/maintenance-2026-06-28]]

## [2026-06-28] reorg | New `travel/` category + cooking consolidation
- Created top-level **`travel/`**; moved [[Seattle Trip 2026-07]] there (was `projects/`). Type → `trip`.
- Moved [[Baking - Berries and Moisture]] into **`recipes/`** (was `learning/`) — all cooking lives together. Type → `technique`.
- Encoded the policy in [[meta/conventions]] + the `/brain` skill: **new top-level categories are created on demand** for coherent recurring domains (with anti-sprawl judgment). So this kind of sorting happens automatically from now on.

## [2026-06-28] telegram | Baking tip — oil vs butter
- Source: `.raw/tg-20260628-201312-655215-note.md` (Telegram capture).
- Updated: [[Baking - Berries and Moisture]] — added the WHY behind oil-over-butter (milk solids + ~80% fat content → firmer crumb when cold).
- No new pages created.

## [2026-06-25] brain | Seattle trip Jul 21–25
- Source: [[.raw/seattle-trip-research-2026-06-25.md]] (web research, sha256 27ecf7f9…).
- Created: [[Seattle Trip 2026-07]] (project) + entities [[Mount Rainier National Park]], [[Olympic National Park]], [[Pike Place Market]].
- Key facts: Rainier no timed-entry in 2026; dates hit wildflower-peak start; Tue–Sat = weekday park parking.

## [2026-06-25] brain | Raspberry chocolate cake
- Source: [[.raw/raspberry-chocolate-cake-research-2026-06-25.md]] (web research, sha256 e53dd1bb…).
- Created: [[Raspberry Chocolate Cake]] (recipe) + [[Baking - Berries and Moisture]] (technique).
- First `/brain` skill runs — research → distilled → auto-filed, no review.

## [2026-06-24] ingest | Karpathy — LLM Wiki
- Source: [[Karpathy - LLM Wiki]] (`.raw/karpathy-llm-wiki-2026-06-24.md`, sha256 dc3efe98…).
- Created (11 pages): source summary; concepts [[LLM Wiki Pattern]], [[Wiki vs RAG]], [[Compounding Knowledge Artifact]], [[Three-Layer Architecture]], [[Ingest Query Lint]], [[Index and Log]]; entities [[Andrej Karpathy]], [[Obsidian]], [[qmd]], [[Memex]].
- Updated: [[index]] (counts 1/6/4), sources/concepts/entities `_index`, [[hot]], `.raw/.manifest.json`.
- Contradictions: none (first source).

## 2026-06-24 — setup

- **BOOTSTRAP** — Vault initialized on the Raspberry Pi (`~/claude-obsidian`) as the canonical home. Cloned `AgriciDaniel/claude-obsidian`, ran `setup-vault.sh`. Detached the upstream `origin` remote so this private vault never pushes to the public template.
- **RESTRUCTURE** — Original plugin demo wiki preserved to `.seed-demo/`. Built a clean Personal-mode structure: `areas/`, `projects/`, `recipes/`, `learning/`, `people/`, `ideas/`, `resources/` + the ingestion layer `sources/`, `concepts/`, `entities/`, `meta/`.
- **CONFIG** — Transport detected as `filesystem`. Methodology mode: generic. Created [[index]], [[overview]], [[hot]], [[meta/conventions]], and per-domain `_index.md` pages.
