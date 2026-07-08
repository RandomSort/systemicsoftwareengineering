# CLAUDE.md — conventions for agents working in this repository

This repository is a personal knowledge framework, not a codebase. The product
is *thinking made explicit*. Treat every edit as an edit to someone's mental
model.

## Prime directives

1. **Agents propose; the author disposes.** Never silently change the meaning,
   stance, or claims of a note in `framework/`. Mechanical fixes (typos,
   formatting, broken links) are fine to apply directly. Anything that shifts
   meaning goes into a clearly marked proposal section (see below) or into
   `knowledge/tensions/`.
2. **Preserve the author's voice.** The framework is deliberately opinionated
   and personal. Do not sand it down into neutral encyclopedia prose. Clarify
   without flattening.
3. **Confidence is data.** Every substantive claim carries a confidence level.
   Fact-checking updates confidence and evidence; it does not delete claims.
   A refuted claim becomes a tension, not a deletion.
4. **Contradictions are fuel, not bugs.** When two notes disagree, file a
   tension note in `knowledge/tensions/` rather than "fixing" either side.
   Resolving tensions is the author's core thinking work.

## Note conventions

All knowledge notes are Markdown with YAML frontmatter:

```yaml
---
title: Concept name
status: seed | developing | stable        # lifecycle maturity
confidence: speculative | working | validated
last-reviewed: YYYY-MM-DD
sources: []        # paths into knowledge/sources/ or external references
related: []        # paths to related framework notes
tensions: []       # paths to open tension notes involving this concept
---
```

- One concept per file in `framework/`, kebab-case filenames.
- Wiki-style relative links between notes; keep `related:` frontmatter in sync.
- Agent-proposed changes that alter meaning go under a trailing
  `## Proposals (agent)` section in the note, each proposal dated and
  attributed to the skill that produced it. The author merges or rejects them.

## Directory rules

- `inbox/` — append-only for capture; `/process-inbox` drains it. Never edit
  framework notes directly from inbox content without routing through the
  proposal convention.
- `knowledge/sources/` — one note per source (book, paper, post, talk).
  Summaries and extracted claims, with citation info. Never paste large
  copyrighted excerpts.
- `knowledge/tensions/` — one note per tension, using the template. Tensions
  have a lifecycle: `open → exploring → resolved | accepted-as-tension`.
- `content/` — derivatives only. Content drafts cite the framework notes they
  are built from, so posts can be regenerated/updated when the framework moves.

## Fact-checking rules

- Distinguish claim types: empirical (checkable against evidence), definitional
  (internal consistency), normative (author's stance — not fact-checkable, only
  challengeable via tensions).
- Cite sources for verdicts; prefer primary sources. Record verdicts as
  `supported / contested / refuted / unverifiable` with a one-line rationale.
- Web research is allowed and encouraged for empirical claims.

## Git conventions

- Commit messages: `area: what changed` (e.g., `framework: clarify feedback-loops note`,
  `tensions: file conway-vs-team-topologies`).
- Agents commit their own work on the branch they were asked to use; small,
  reviewable commits per skill run.
