# Inbox: candidates from the two book imports (2026-07-08)

Captured during the digestion of two private book manuscripts into source
notes. Each item below is a routing candidate for /process-inbox. Sources:

- `knowledge/sources/imported/deliberate-git.md` (DG)
- `knowledge/sources/imported/public-speaking-patterns.md` (PSP)

---

## Candidate framework concepts (seed proposals)

1. **Deliberate fluency (practice ahead of need).** Both books share one
   stance: high-frequency skills (Git, speaking) deserve structured practice
   *before* they are needed, so they cost nothing under pressure. DG frames
   it as katas + crisis insurance; PSP as patterns past the hygiene bar.
   Possible note: `framework/deliberate-fluency.md`. [DG N1–N3; PSP N2]

2. **The legibility gap.** Organizations underinvest in high-leverage skills
   whose value is not legible to management ("getting better at Git is boring,
   and not obviously linked to business value"). Same mechanism plausibly
   explains underinvestment in speaking, docs, tooling. A systemic
   incentive-structure claim, probably more valuable to the framework than
   either book's object-level advice. [DG E3]

3. **Communication as a value multiplier.** "The feature you built might be
   technically excellent, but if you cannot excite anyone about it, you are
   leaving value on the table." Engineering value = technical quality ×
   legibility/adoption; the second factor is a skill, not a personality
   trait. Related to #2 (legibility applied to one's own work). [PSP N1]

4. **Operationalized advice as a quality bar.** Advice must compile to
   actions: "slow down" fails; "pause after every third sentence" passes.
   Candidate *meta-rule for this framework itself*: a concept note that
   cannot name what a practitioner does differently on Monday is not done.
   Could become a check inside /clarify. [PSP N4, STYLEGUIDE tone targets]

5. **Patterns before understanding (hygiene bar / reliably good).** A
   competence model: apply heuristics before you understand why they work;
   earn the judgment to deviate through practice (Shu-Ha-Ri-shaped). Useful
   for onboarding, runbooks, paved roads. [PSP N2–N3, D1]

6. **Crisis as the test of latent capacity.** Fundamentals fluency is
   capacity banked in calm times that only becomes visible under stress —
   bridges to resilience engineering if /enrich picks it up. [DG N2]

7. **Katas / rehearsal loops as designed learning systems.** Pair every
   claim with a repeatable low-stakes exercise; also rehearse immediately
   before risky operations. A feedback-loop design pattern, not a Git topic.
   [DG N3; PSP Part III "Practice Methods"]

## Open questions (candidates for knowledge/questions.md)

- Is "deliberateness" a first-class concept, or an instance of a more general
  feedback-loops / practice concept the framework will need anyway?
- Tension candidate: DG optimizes *individual* tool mastery, but a systemic
  frame usually locates leverage in the system (safer defaults, better
  porcelain, guardrails). Is "everyone drills katas" the systemic answer, or
  a workaround for bad tool UX? [DG source note, Agreements section]
- Tension candidate: PSP's "apply patterns before understanding" vs. a
  framework whose premise is that understanding the system is the point.
  Where is the line between hygiene-bar pattern-following and cargo-culting?
  [PSP source note, Agreements section]
- Do the two books plus this framework share one underlying thesis (deliberate,
  systematized craft) that deserves an umbrella note — or is that forced?
- Is E1 (Git de-facto standard) / PSP E1 (phobia prevalence) worth a
  /fact-check pass once any depending note exists, to seed the evidence trail?

## Content-pipeline actions (route to docs/WORKFLOWS.md / content/, not framework/)

- **Seed `content/VOICE.md` from PSP's STYLEGUIDE.md** — the distillation is
  in the PSP source note ("STYLEGUIDE.md — writing-voice guidance" section).
  Adaptations needed: first person singular ("I", not the book's "we");
  drop print-safety rules; keep reader model (skeptical engineer), dry/direct
  tone, engineering-frame vocabulary, banned corporate-speak list, hedging
  audit, emphasis discipline.
- **Harden the one-idea rule in `content/briefs/_template.md`** — one
  takeaway per brief as a gate; a brief with two ideas is two briefs. [PSP N5]
- **Adopt PSP's chapter arc as the default draft skeleton** in /draft-post:
  open with the problem → state the point early → brief why → concrete
  example/anti-pattern → close with scope. No opening quotes, no closing
  summaries. [PSP STYLEGUIDE "Chapter Structure"]
- **Hook patterns for /draft-video-script** from "Opening Strong" /
  "Opening and Closing" once those chapters get written; meanwhile the
  narrative-arc + one-idea commitments already apply.
- **Add a hedging audit to the edit stage** (count qualifiers per paragraph;
  >2 undermines authority) — mechanically checkable, could be an agent lint.
- **PSP's AI-collaboration protocol** (preserve voice / fix mechanics / flag
  drift, with prompt templates) overlaps heavily with CLAUDE.md's
  agents-propose-author-disposes; consider folding its prompt templates into
  the content skills.
- **Talks as a first-class content type?** PSP Part IV (CFP, proposal,
  talk lifecycle, after-the-talk) is a ready-made production loop for talks
  parallel to posts/videos; WORKFLOWS.md names talks but content/ has no
  talk pipeline.
