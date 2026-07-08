---
name: fact-check
description: Extract and verify the empirical claims of a framework note; record verdicts with citations and file tensions for refuted claims. Usage - /fact-check <concept-note-path-or-name>.
---

# Fact-check a concept

1. Resolve the argument to a note in `framework/`. Without an argument,
   suggest notes whose `confidence` exceeds their evidence (e.g. `working` or
   `validated` with empty `sources:`), or whose `last-reviewed` is oldest.
2. Spawn the **fact-checker** agent (subagent_type: fact-checker) on the note.
3. Verify conventions: verdict table in proposals, source notes created,
   tension notes for refuted/contested claims, no claim deleted or rewritten,
   `confidence:` changed only as a proposal.
4. Commit as `knowledge: fact-check <concept> (S supported / C contested / R refuted / U unverifiable)`.
5. Report the verdict summary and any tensions filed, and remind the user the
   confidence change (if proposed) awaits their decision.

For a sweep across many notes, spawn one fact-checker per note in parallel —
but cap at ~5 per run so the user can realistically review the output.
