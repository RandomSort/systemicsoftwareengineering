---
title: Simulating the life of a developer (making practice claims testable)
type: conversation
author: Johan Abildskov
year: ~2018
link: https://github.com/RandomSort/notes (ideas/lifeofdev.md)
feeds: []
added: 2026-07-08
---

# Simulating the life of a developer

## Core argument

Most claims about development practices — CI beats no-CI, small batches beat
large, reviews cost context switches — are asserted, not demonstrated. The
idea: simulate a development team as agents with skill levels and error
rates producing commits, and *make plausible* (explicitly "not prove —
sandsynliggør") the consequences of changing one variable: integration
frequency, unit tests catching errors locally vs. centrally, CI system
delays, blocked branch owners, reviewer context switching, time spent on
planning ceremonies. Run it against real repositories and real CI engines and
it doubles as a benchmark. The note (a brainstorm with a colleague, in
Danish) then falls into the deeper hole: to score the simulation you need a
measure — "what is the SI unit of team performance?" Outcome per time unit —
but what is outcome? "Value... that one is hard."

## Extracted claims

- Normative/methodological: claims about practices should be probed by
  simulation with explicit, crude assumptions — "the model will be trivially
  'bad,' but assumptions rough enough to show something interesting" beat no
  model.
- Definitional: candidate variables that a team-performance model must
  include: error rates, integration frequency, feedback delay (local vs.
  central test failure), review blocking, context-switch cost, and overhead
  time (planning, standups) modeled as an effectiveness factor that also
  consumes effective time.
- Definitional (the hard core): team performance has no agreed unit; every
  metric (commit frequency, failed-build percentage) is an *indicator*
  resting on an argued assumption, not a measure of value.
- Normative (from the same conversation): goals decompose as
  goal → focus area → measurable metric → action (e.g. reduce cost → automate
  environments → % builds failing → fix flaky tests); a supporting team is
  doing well "as long as the sum of its goals' values moves the right way."
- Empirical (aside in the conversation): "if your employees understand your
  vision, you don't need to manage them."

## Agreements and disagreements

Two framework threads: (1) simulation as epistemics — an honest middle ground
between anecdote and impossible controlled experiments for organizational
claims; (2) the measurement problem — the conversation independently
rediscovers why proxy metrics drift (every metric is an indicator plus an
argument), which grounds the framework's measurement skepticism (see
abused-figures-of-devops). Personal names from the source conversation are
omitted; it was a brainstorm with a colleague.

## Quotable

- "What is the SI unit of team performance?" (translated)
- "Not prove — make plausible." (translated)
