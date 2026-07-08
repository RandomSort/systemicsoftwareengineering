---
name: process-inbox
description: Drain inbox/ — triage each captured item and route it into the framework (as a proposal), a source note, an open question, or a new seed concept. Use when the user wants to process captured thoughts.
---

# Process inbox

Follow CLAUDE.md conventions throughout.

1. List everything in `inbox/` (except README.md). If empty, say so and stop.
2. Read all of `framework/` note titles + definitions (frontmatter and
   `## Definition` sections are enough) to build a routing map.
3. For each inbox item, decide its routing:
   - **Extends an existing concept** → append a dated proposal to that note's
     `## Proposals (agent)` section, marked `(/process-inbox)`.
   - **A new concept** → create a `framework/` note from `_template.md` with
     `status: seed`, filling only what the capture supports.
   - **A source** (link, book reference, quote) → create a
     `knowledge/sources/` note from its template.
   - **A question** → append to `knowledge/questions.md` with date and origin.
   - **Content idea** → append to `content/ideas.md`.
   - **Unclear** → leave in inbox, flag in your summary.
4. Present the full routing plan to the user BEFORE deleting anything from
   `inbox/`. On confirmation, apply it and remove processed items.
5. Commit as `inbox: process N items` and summarize the routing.

Judgment calls belong to the author: when an item could merge into an
existing concept OR seed a new one, prefer the proposal route and note the
alternative.
