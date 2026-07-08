---
name: clarify
description: Cold-read a framework note for ambiguity, circularity, and undefined jargon; propose sharper phrasings. Usage - /clarify <concept-note-path-or-name>. Spawns the naive-reader agent.
---

# Clarify a concept

1. Resolve the argument to a note in `framework/` (fuzzy-match; ask if
   ambiguous).
2. Spawn the **naive-reader** agent (subagent_type: naive-reader) on the note.
3. Verify conventions were followed (proposals appended, body untouched).
4. Commit as `framework: clarity review of <concept>`.
5. Report the top clarity issues and where the proposals live.

Note: the naive-reader must NOT be given conversational context about what
the author "really means" — the value is the cold read. Pass only the note
path.
