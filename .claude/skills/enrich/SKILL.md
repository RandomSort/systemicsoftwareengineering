---
name: enrich
description: Enrich a framework concept with researched sources, examples, and counterexamples. Usage - /enrich <concept-note-path-or-name>. Spawns the researcher agent.
---

# Enrich a concept

1. Resolve the argument to a note in `framework/` (fuzzy-match the name; if
   ambiguous, ask). Without an argument, suggest the 3 notes with the fewest
   `sources:` whose status is past `seed`.
2. Spawn the **researcher** agent (subagent_type: researcher) with the note
   path and a directive to find both the strongest support AND the strongest
   opposition for its claims.
3. When it returns, verify its output followed conventions (source notes use
   the template; the note body above `## Proposals (agent)` is untouched
   except `sources:` frontmatter).
4. Commit as `knowledge: enrich <concept> (+N sources)`.
5. Report to the user: sources added, strongest support, strongest
   opposition, and proposals awaiting their review in the note.

For enriching several notes at once, spawn one researcher agent per note in
parallel.
