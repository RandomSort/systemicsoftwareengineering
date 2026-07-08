---
title: Seeing (Book of Null 003)
type: post
author: Johan Abildskov
year: 2026
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# Seeing

Source piece: `bookofnull/pieces/003-seeing.md` (four-line koan).

## Core argument

Engineers solving problems "see with their hands": we perceive software only
through what we can poke — editing, running, logging, clicking — because
software has no directly perceivable surface. But hands cannot actually see;
manipulation is not perception. The working engineer is functionally blind,
navigating a system by touch and inference, and rarely notices this because
the tooling makes the blindness comfortable.

## Extracted claims

- **Definitional:** software systems are not directly observable; every
  perception of a system is mediated by an instrument (logs, metrics,
  debuggers, tests, dashboards) that someone chose to build.
- **Empirical:** a large share of practical debugging proceeds by
  perturbation — change something and watch what happens — rather than by
  inspection of state. (Checkable against studies of debugging behavior.)
- **Normative:** treat observability as prosthetic sight: an investment
  that converts touch into vision, not an optional operational extra.

## Framework relevance

Foundation for a feedback/observability concept: if all perception of a
system is instrument-mediated, then the quality of an engineering
organization's thinking is bounded by the quality of its instruments.
Pairs with *Understanding* (002): reading code is another form of seeing
with the hands. Also relevant to cause-and-effect: blind probing produces
weak causal models (004).

## Quotable

- "I see with my hands / My hands can't see the code"
