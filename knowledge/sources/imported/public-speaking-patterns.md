---
title: Public Speaking Patterns
type: book
author: Johan Abildskov (with a co-author)
year: in progress (unpublished manuscript, dated 2026)
link: private repository (publicspeakingpatterns)
feeds: []          # no framework notes exist yet; see inbox/import-books-craft.md for candidates
added: 2026-07-08
---

# Public Speaking Patterns

## What this source is (maturity note)

An in-progress, co-authored book manuscript. The substantive material today is:
a finished ~450-word preface (which carries the whole thesis, in the intended
voice), a complete four-part chapter skeleton (27 chapter files, nearly all
title-only stubs), an older `manuscript/` outline with a few one-line seeds,
and a detailed `STYLEGUIDE.md` that is arguably the most developed artifact in
the repo. The glossary is empty. Treat the preface and style guide as
load-bearing; treat the chapter map as a table of intent.

## Core argument

Public speaking is one of the most common phobias, and engineers dodge it
twice over: the stage is out of the comfort zone, and the imagined preparation
(embarrassing coaching rituals) is too. But the skillset is high-ROI even for
people who never take a stage — presenting is just one manifestation; the same
skills decide whether excellent technical work excites anyone, and whether
meetings produce value. Most existing advice fails engineers because it does
not compile to actions ("slow down," "breathe"). The book's answer is
*patterns and heuristics*: concrete, immediately applicable techniques that
get you past the hygiene bar and make you *reliably good* (not spectacular),
applicable even before you understand why they work — with the judgment to
deviate arriving later, through practice. Goal, verbatim: "help you suffer
less during your next presentation."

## Part / chapter map

- **Preface** (written) — thesis, audience, method; see core argument.
- **Part I — Introduction** (placeholder text only).
- **Part II — Public Speaking** (the on-stage skill; all stubs)
  - *The Fear*: What is Public Speaking / Why It Matters / Managing Nerves
  - *Delivery*: Voice and Pace / Body Language / Eye Contact
  - *In the Moment*: Opening Strong / Handling Questions / Recovering From Mistakes
- **Part III — Making Your Content** (all stubs)
  - *Structure*: The One Idea / Narrative Arc / Opening and Closing
  - *Slides*: Less Is More / Visual Language / Code and Diagrams
  - *Preparing*: Know Your Material / Practice Methods / Getting Feedback
- **Part IV — Getting on Stage** (all stubs)
  - *Finding Opportunities*: Types of Venues / The CFP Process / Writing a Proposal
  - *Building Presence*: Your Speaker Profile / Community Involvement / Your Speaker Bio
  - *The Talk Lifecycle*: Preparing for the Event / On the Day / After the Talk
- **Appendix** — Glossary (empty).
- Older `manuscript/` outline (Speaking in Front of People / Creating
  Effective Presentations / Getting a Talk Accepted) — superseded by the parts
  above, but shows the dry voice: "Public speaking is about speaking in
  public, a side effect of this is that it tends to be in front of other
  people. It is horrible."

## Extracted claims

Empirical (checkable):

- **E1.** Public speaking is one of the most common phobias. (preface) —
  widely reported; fact-checkable against phobia-prevalence research.
- **E2.** Engineers avoid not only speaking but *preparing* for it, because
  the expected preparation (group coaching rituals) is itself outside the
  comfort zone. (preface) — anecdotal/experiential; grounded in the authors'
  workshop experience.
- **E3.** Most public speaking advice is too vague to act on ("what does
  *slow down* and *breathe* mean in practice?"). (preface) — contestable but
  checkable against the genre.

Definitional:

- **D1.** Patterns = reusable solutions to recurring problems, not rules;
  heuristics = rules of thumb you apply until you know better; hygiene bar =
  the minimum acceptable standard — not everything needs to be exceptional.
  (STYLEGUIDE.md, "The Engineering Frame")

Normative (authors' stance):

- **N1.** "The stage is optional. The skills are not." Public speaking skill
  transfers to meetings, pitching, and making work legible; a technically
  excellent feature nobody is excited about is value left on the table.
  (preface)
- **N2.** Aim for *reliably good, not spectacular* — get past the hygiene bar
  with patterns; do not chase "the next TED speaker." (preface)
- **N3.** Apply patterns *before* you fully understand why they work;
  judgment about when to deviate is earned through practice and experience
  afterward. (preface) — a Shu-Ha-Ri-shaped competence model.
- **N4.** Advice must be operationalized to be useful: "Slow down means:
  pause after every third sentence," not "remember to slow down and breathe."
  (preface + STYLEGUIDE tone targets)
- **N5.** A talk carries one idea (The One Idea), is shaped as a narrative
  arc, and wins or loses at its opening and closing. (Part III structure —
  stub-level, but the commitment is explicit in the chapter map.)

## What this book should feed in `content/` (production loop)

This source informs `docs/WORKFLOWS.md` stage-by-stage, not just the
framework:

- **Brief stage (`content/briefs/_template.md`)** — *The One Idea* is the
  book's core structural pattern and maps directly onto the brief's "the one
  thing the reader should take away." Make it a hard gate: a brief with two
  ideas is two briefs.
- **Draft stage (`/draft-post`, `/draft-video-script`)** — *Narrative arc* and
  *Opening Strong / Opening and Closing* should shape draft structure: hook
  first (the video-script skill already demands a hook — the book supplies the
  patterns for it), problem named before solution, deliberate close, and the
  style guide's chapter arc as a default post skeleton: open with the problem
  → state the pattern early → brief why → concrete example/anti-pattern →
  close with scope. Also adopt: never open with a quote, never close by
  summarizing what was just said.
- **Slides/visuals (`/draft-video-script` b-roll and visual cues)** — *Less Is
  More*, *Visual Language*, *Code and Diagrams*: signal vs. noise as the test
  for every visual; one visual point per cue.
- **Edit stage** — *Getting Feedback* and *Practice Methods* mirror the
  author-edit stage; the style guide's "hedging audit" (count qualifiers; more
  than two per paragraph undermines authority) is a concrete, automatable
  editing check for drafts.
- **Publish/backlink + talks pipeline** — Part IV (*CFP process*, *Writing a
  Proposal*, *Talk Lifecycle*, *After the Talk*) is effectively a production
  loop for talks: proposals are briefs, "after the talk" is the
  publish-and-backlink stage. If talks become a first-class content type in
  `content/`, this part is the workflow source.

## STYLEGUIDE.md — writing-voice guidance to seed `content/VOICE.md`

The style guide is directly reusable; the main adaptation is person (book is
first-person-plural "we" for a two-author team; personal content should be
"I"). Distilled guidance:

- **Reader model**: a technically skilled professional who is skeptical of
  soft-skills content, suspicious of hype, short on time, high ROI bar, and
  "may be anxious ... but would not admit it easily." Write for the skeptic,
  not the enthusiast.
- **Voice**: direct — "say the thing," no throat-clearing ("it is important to
  note that..."); empathetic but not soft; dry humor, self-aware asides, and
  understatement welcome; exclamation points and motivational energy are not;
  authoritative but not preachy — strong opinions stated plainly, no
  moralizing, no repeating for emphasis.
- **Tone calibration by example**: "This will fail in front of an audience,"
  not "this might potentially not work as well as you hope"; "Meetings are
  objectively horrible," not "meetings can sometimes feel challenging."
- **The engineering frame as vocabulary**: patterns, heuristics, ROI, hygiene
  bar, signal vs. noise, "deviate when you know better." Banned:
  corporate/coach-speak (*leverage*, *synergy*, *impactful*, *circle back*,
  *take it to the next level*).
- **Sentence mechanics**: short sentences at key points; vary rhythm ("a short
  punch after a longer setup lands harder"); active voice by default; one
  qualifier per claim; **hedging audit** — more than two qualifiers per
  paragraph undermines authority; contractions fine.
- **Emphasis discipline**: italics to introduce terms; bold only for critical
  info or named patterns; never CAPS.
- **Structural rules**: open with the problem; state the pattern early;
  explain why briefly; show it concretely; close with scope. No opening
  quotes, no closing summaries.
- **Self-anchoring**: "not a motivation book — we are not here to inspire
  confidence, we are here to improve outcomes."
- **AI collaboration protocol** (highly consonant with this repo's
  agents-propose-author-disposes rule): AI preserves the dry voice, fixes
  mechanics, and *flags rather than fixes* voice drift, over-strong claims,
  and repetition. Includes reusable prompt templates for copy-edit, review,
  and new-passage tasks — a ready-made pattern for `content/` skill prompts.

## Agreements and disagreements

- Strongly supports the repo's production philosophy: one idea per artifact
  mirrors "one concept per file"; operationalized advice (N4) is a quality
  bar this framework's notes should also meet; the AI-collaboration section
  independently reinvents "agents propose, the author disposes."
- Pushback worth keeping: N3 (apply patterns before understanding) sits
  uneasily with a *systemic* framework whose whole point is understanding why
  things work. When is pattern-following without understanding good enough,
  and when is it cargo-culting? Tension candidate.

## Quotable

- "The stage is optional. The skills are not." (preface)
- "Meetings are objectively horrible, but the right subset of public speaking
  skills can turn them into high value activities." (preface)
- "What does *slow down* and *breathe* mean in practice?" (preface)
- "We hope this book will help you suffer less during your next
  presentation." (preface)
- "We are not here to inspire confidence, we are here to improve outcomes."
  (STYLEGUIDE.md)
