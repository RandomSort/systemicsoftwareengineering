# Workflows

Two loops run over this repository: an **improvement loop** that grows and
hardens the knowledge, and a **production loop** that derives content from it.
Both are agent-assisted but author-driven.

```
            ┌──────────────────────────────────────────────┐
            │                IMPROVEMENT LOOP              │
            │                                              │
 capture ──▶ inbox ──▶ crystallize ──▶ challenge ──▶ connect
            │            (framework)    (tensions,         │
            │                 ▲          fact-check)       │
            │                 └──── resolve ◀──────────────┘
            │
            └──▶ PRODUCTION LOOP: select ─▶ brief ─▶ draft ─▶ edit ─▶ publish ─▶ backlink
```

## 1. The improvement loop

### Capture
Dump raw material into `inbox/` — a thought, a link, a disagreement with a
book, a shower insight. Zero friction, no structure required. This is the only
stage with no quality bar.

### Crystallize — `/process-inbox`
Agents triage the inbox: each item is matched against the existing framework
and routed — merged into an existing concept as a proposal, drafted as a new
`seed` concept note, filed as a source note, or logged as an open question.
You review the routing; nothing lands in `framework/` as settled meaning
without your sign-off.

### Enrich — `/enrich <note>`
For a chosen concept: agents research supporting and opposing literature,
find concrete examples and counterexamples, and add source notes to
`knowledge/sources/`. Output arrives as proposals on the note, never as
silent rewrites.

### Clarify — `/clarify <note>`
A "naive reader" agent reads the note cold and reports where it is ambiguous,
circular, jargon-dependent, or assumes context that isn't written down. It
proposes sharper phrasings side-by-side with the original. This is how the
condensation gets denser without getting more obscure.

### Challenge — `/fact-check <note>` and `/find-tensions`
- **Fact-check**: extracts the empirical claims from a note, researches each,
  and records verdicts (`supported / contested / refuted / unverifiable`)
  with citations. Confidence frontmatter gets updated; refuted claims become
  tension notes, not deletions.
- **Find tensions**: sweeps the framework for internal contradictions —
  concept A assumes what concept B denies, a principle that its own examples
  violate, definitional drift between notes. Each finding becomes a note in
  `knowledge/tensions/`.

### Connect
Agents propose missing links between concepts (`related:` frontmatter) and
flag orphaned notes. A framework is a *system* of concepts; unlinked notes are
a smell.

### Resolve (author-only)
Work through open tensions. Resolution can mean: revise a concept, split it,
accept the tension explicitly (some tensions are real and load-bearing), or
demote a claim. This is the actual thinking work the whole apparatus exists to
provoke — agents can brief you on a tension (`/review-framework` includes a
tension digest) but should not resolve tensions themselves.

### Audit — `/review-framework`
A periodic (e.g., monthly) holistic pass: coverage gaps, stale notes
(`last-reviewed` aging), orphans, status distribution (all `seed`, nothing
`stable`?), unresolved tension backlog, and an overall coherence read. Output
is a review report in `docs/reviews/` you can work through.

## 2. The production loop (blog posts, videos, talks)

The framework is the single source of truth; content is a *projection* of it
for an audience. That gives you two properties worth protecting:

- **Traceability**: every piece of content cites the framework notes it
  projects. When the framework moves, you know which published content is
  stale.
- **Reusability**: one `stable` concept can be projected many times — post,
  video, talk section — without re-deriving the thinking.

### Stage 1 — Select
Pick from `content/ideas.md`, which agents keep fed: `/review-framework`
appends "content-ready" candidates (notes that reached `stable` with resolved
or explicitly-accepted tensions, or a tension interesting enough to think
through in public). Writing about a concept is also a legitimate way to
*develop* it — a `developing` note plus its open tension often makes a better
post than a settled one.

### Stage 2 — Brief
Run `/draft-post <concept>` (or `/draft-video-script <concept>`); it first
produces a brief from `content/briefs/_template.md`: audience, the one thing
the reader should take away, the angle (story? argument? teardown?), and the
framework notes in scope. **Approve the brief before drafting** — it is much
cheaper to steer a brief than a draft.

### Stage 3 — Draft
The drafting agent writes from the framework notes and their sources *only* —
no new unsourced claims — in your voice (see `content/VOICE.md`, which you
should seed with 2–3 posts you're proud of). Drafts land in
`content/drafts/`, frontmatter linking brief and source notes. For video, the
skill produces a script with a hook, spoken-prose narration, and b-roll/visual
cues, plus a description and title options.

### Stage 4 — Edit (author-only)
You rewrite. The draft is scaffolding for your voice, not a product. Editing
frequently exposes weak spots in the underlying concept — file those back as
inbox items or tensions. This backpressure from writing to thinking is the
most valuable byproduct of the pipeline.

### Stage 5 — Publish and backlink
Move to `content/published/` with the canonical URL in frontmatter, and add
the piece to the source concept's note. When a concept later changes
materially, `/review-framework` flags published content that projects it as
potentially stale.

## 3. Cadence that works in practice

| Rhythm | Activity |
|---|---|
| Continuous | Capture to `inbox/` |
| Weekly (~30 min) | `/process-inbox`, skim proposals, merge/reject |
| Per writing session | One `/enrich` or `/clarify` + one tension resolved |
| Monthly | `/review-framework`, prune ideas list, pick next content |
| Per content piece | brief → draft → edit → publish → backlink |

## 4. Division of labor

| Work | Who |
|---|---|
| Capturing, deciding meaning, resolving tensions, final voice | **Author** |
| Research, triage, claim extraction, verification, contradiction sweeps, first drafts, link hygiene, staleness tracking | **Agents** |

The test for whether an agent should do something: *does it require the
author's judgment about what the framework means?* If yes, the agent's job is
to prepare the decision, not make it.
