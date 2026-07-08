---
title: Deliberate Git
type: book
author: Johan Abildskov
year: in progress (unpublished manuscript)
link: private repository (deliberate-git, manuscript/)
feeds: []          # no framework notes exist yet; see inbox/import-books-craft.md for candidates
added: 2026-07-08
---

# Deliberate Git

## What this source is (maturity note)

An early-stage, unpublished book manuscript by the author of this repository.
Only chapter 1 (the introduction, ~270 words) is substantive; chapters 2 and 3
are untouched Leanpub template boilerplate (Markdown syntax examples and
preview instructions) and carry no content. Treat this source as a *statement
of intent and thesis*, not a developed argument. Its value to the framework is
the stance it articulates, plus the pedagogy it commits to (kata-based
practice).

## Core argument

Git is the de-facto standard for version control, used by every developer
every day — yet most developers only know a narrow happy path and are helpless
off it. Organizations tolerate this because Git skill is boring and not
legibly connected to business value. The book's answer is *deliberateness*:
improve Git skills in a structured, practiced way (modeled on the open-source
Git Katas used at Eficode Praqma for training) so that when advanced usage is
needed — especially during a crisis — the tool can be wielded without effort.
Fluency is built ahead of need, through repeatable exercises, not acquired
reactively mid-incident.

## Chapter summaries

- **Chapter 1 — Introduction.** The full thesis: Git's ubiquity, the
  "one-trick pony" skill gap, why companies underinvest (boring, not obviously
  business-valuable), the daily-use argument for investment, fundamentals as
  crisis insurance, and the kata method — every technique paired with a
  repeatable exercise, usable both for continuous practice and as a rehearsal
  reference "before undertaking a risky manoeuvre." Closing intent: "make Git
  a lot less scary."
- **Chapters 2–3.** Leanpub template boilerplate; no book content.

## Extracted claims

Empirical (checkable):

- **E1.** Git is the de-facto standard of version control in software
  development; alternatives matter mainly for niches like large binary assets.
  (ch. 1) — near-certainly supported; easy to verify against developer surveys.
- **E2.** Many developers know only a narrow Git happy path and "are baffled
  when they veer away" from it. (ch. 1) — plausible, anecdotal as stated;
  would need survey/observational evidence.
- **E3.** Companies and managers accept this skill gap because getting better
  at Git is boring and not obviously linked to business value. (ch. 1) — a
  causal claim about organizational behavior; unverified as stated.

Definitional:

- **D1.** "Deliberate" Git use = structured, intentional, practiced-in-advance
  command of the tool, as opposed to reactive, copy-pasted, happy-path-only
  use. (Implied by title + ch. 1; the manuscript never defines it explicitly —
  a gap worth noting.)

Normative (author's stance):

- **N1.** Because every developer uses Git daily, investing in Git skill is
  worthwhile even if the payoff is not legible to the business — a
  frequency-of-use × marginal-improvement argument for where to spend
  practice effort. (ch. 1)
- **N2.** Skill at fundamentals pays off most in crisis: an incident is hard
  enough "without having to learn the tools and techniques that will help
  remediate issues" mid-crisis. Fluency should be banked in calm times. (ch. 1)
- **N3.** Skills should be built through repeatable exercises (katas):
  theory coupled with an exercise, repeated "until it sticks," and also used
  as rehearsal immediately before a risky operation. (ch. 1)

## How "deliberateness" could feed a systemic-software-engineering framework

- **Deliberateness as a stance, not a Git topic.** The generalizable claim is:
  systems reward practitioners who invest in fluency *ahead of need*. The Git
  content is one instance; the same stance covers debugging, incident tooling,
  shell fluency, and (via the companion book) public speaking. Candidate
  concept: *deliberate practice of engineering fundamentals*.
- **The legibility gap as a systemic failure mode.** E3 describes an incentive
  structure: high-leverage skills go unfunded because their value is not
  legible to management. That is a systemic claim about how organizations
  allocate learning investment — arguably more interesting to the framework
  than the Git advice itself.
- **Crisis as the test of the system.** N2 reframes skill as *latent capacity*
  that only becomes visible under stress — connects to resilience engineering
  ideas (capacity you build before you need it).
- **Katas as engineered feedback loops.** N3 is a design pattern for learning
  systems: pair every claim with a repeatable, low-stakes exercise. This also
  mirrors this repository's own method (pair every concept with sources,
  checks, and tensions).

## Agreements and disagreements

- Supports a practice-centric, systems view of skill: competence is built by
  designed loops, not accumulated by osmosis. Consonant with deliberate
  practice literature (Ericsson) — worth an /enrich pass if a framework note
  emerges.
- Potential pushback for the framework: the book optimizes *individual* tool
  mastery, while a systemic frame usually locates leverage in the system
  (process, tooling defaults, guardrails) rather than in individual heroics.
  Is "everyone drills Git katas" the systemic fix, or is it better UX/porcelain
  and safer defaults? This is a genuine tension candidate.

## Quotable

- "Many developers are one trick ponies when it comes to Git and are baffled
  when they veer away from the happy path." (ch. 1)
- "I hope this book will make Git a lot less scary." (ch. 1)
