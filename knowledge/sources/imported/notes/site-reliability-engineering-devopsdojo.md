---
title: Site Reliability Engineering (DevOpsDojo episode 5 script)
type: talk
author: Johan Abildskov
year: ~2020
link: https://github.com/RandomSort/notes (devopsdojo/sitereliabilityengineering.md)
feeds: []
added: 2026-07-08
---

# Site Reliability Engineering (DevOpsDojo #5)

## Core argument

Script for the author's own DevOpsDojo video episode. SRE looks like an
oxymoron — "planet-scale operations with autonomous DevOps teams" reads like
traditional siloed Ops in disguise — but it is a *functioning DevOps
organizational structure*. Quoting Benjamin Treynor Sloss: "Site Reliability
Engineering is what happens when you ask a software engineer to design an
operations team." The author distills SRE to three core tenets: **minimizing
toil, shared ownership, and the ability to say no** — and argues each is a
structural commitment, not a practice a team can adopt alone.

## Extracted claims

- Definitional: toil is work that does not add long-run value or does not
  require engineering (manual deploys, following complex processes); toil is
  the opposite of engineering.
- Empirical (reported from Google): SRE teams operate at 30–50% toil, with
  50% as a hard cap; on violation the team *sheds responsibilities or gets
  resources added*.
- Structural claim (the author's sharpest addition): enforcing a toil cap
  "requires a hard buy-in from management... This will likely be impossible
  in a project-funded organization" — i.e., the funding model, not the team,
  determines whether SRE is possible.
- Definitional: shared ownership is operationalized, not aspirational — SREs
  feed production metrics back to product teams, and if a service is too
  unstable, *developers join the on-call rotation* until it is restored to
  operable quality.
- Empirical: SRE's purpose is dual scaling — services to world-class
  availability, and the engineering organization so productivity scales
  superlinearly with headcount.
- Structural: production-readiness reviews and SRE requirements only work
  with management commitment to enforce them — otherwise the org "reverts
  back to throwing applications over the wall of confusion."
- (Listed, undeveloped in the note: error budgets, blameless postmortems.)

## Agreements and disagreements

The recurring systemic move: every SRE mechanism bottoms out in an
organizational precondition (funding model, management enforcement,
negotiable responsibility). This supports a framework claim that practices
are downstream of structure — you cannot adopt SRE practices inside a
structure that cannot honor "no." Tension with automation-is-hard: toil
elimination prescribes aggressive automation; that talk warns undirected
automation is low-ROI. Synthesis: toil is the definition of *directed*.

## Quotable

- "Site Reliability Engineering is what happens when you ask a software
  engineer to design an operations team." — Benjamin Treynor Sloss (quoted)
