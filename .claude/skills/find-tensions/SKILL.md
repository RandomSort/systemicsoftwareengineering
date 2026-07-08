---
name: find-tensions
description: Sweep the framework for internal contradictions, definitional drift, and assumption clashes; file tension notes. Usage - /find-tensions [scope], defaults to the whole framework.
---

# Find tensions

1. Determine scope: the named notes, or all of `framework/` by default.
2. For a small scope (≤ ~8 notes), spawn one **contradiction-finder** agent
   (subagent_type: contradiction-finder) over the whole scope. For a larger
   framework, partition: spawn parallel contradiction-finders over clusters of
   related notes (use `related:` frontmatter to cluster), plus one pass over a
   random cross-cluster sample — contradictions hide between clusters, not
   within them.
3. Deduplicate findings against existing `knowledge/tensions/` before
   accepting new tension notes.
4. Verify conventions: both sides steelmanned, `tensions:` frontmatter updated
   on involved notes, nothing resolved, no note bodies edited.
5. Commit as `tensions: sweep found N new (scope)`.
6. Report findings by type with one-line summaries, ordered by how much of the
   framework each tension touches.
