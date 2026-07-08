---
title: Tradeoffs (Book of Null 039)
type: post
author: Johan Abildskov
year: 2026
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# Tradeoffs

Source piece: `bookofnull/pieces/039-tradeoffs.md` (two couplets).

## Core argument

Two mirrored fragments — "A simple solution / to a complex problem" and "A
complex solution / to a simple problem" — offered without comment. The
reader supplies the judgment, and the trap is that the judgment is not
symmetric or obvious: a simple solution to a complex problem is either
mastery (the right abstraction found) or denial (essential complexity
ignored, pushed onto users or operators); a complex solution to a simple
problem is either waste or evidence that the problem was never actually
simple. Complexity mismatch in either direction is a signal demanding
investigation, and the title reframes the whole thing: choosing where the
complexity lives is the tradeoff.

## Extracted claims

- **Definitional:** solution complexity and problem complexity are distinct
  quantities; design is the act of matching them, and mismatch is
  measurable information about the design or about your model of the
  problem.
- **Definitional:** essential complexity can be moved but not removed
  (echoes Brooks; a "simple solution" to a complex problem has relocated
  complexity somewhere — find where).
- **Normative:** neither mismatch is automatically wrong, but both must be
  explained; an unexplained simplicity is as suspicious as an unexplained
  complexity.

## Framework relevance

A candidate spine for the framework's tradeoffs concept: tradeoffs as
conservation-and-relocation of complexity rather than as menu choices.
Connects to *Eventual Consistency* (028, a named tradeoff hiding as
vocabulary) and to systems thinking's insistence on asking where displaced
effects went. Good /enrich target: Brooks (essential/accidental), Tesler's
law of conservation of complexity, Ousterhout.

## Quotable

- "A simple solution / to a complex problem // A complex solution / to a simple problem"
