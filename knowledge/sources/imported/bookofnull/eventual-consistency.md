---
title: Eventual Consistency (Book of Null 028)
type: post
author: Johan Abildskov
year: 2026
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# Eventual Consistency

Source piece: `bookofnull/pieces/028-eventual-consistency.md` (five-line
verse).

## Core argument

A reframing by pure logic: a system that is *eventually* consistent is, at
any moment you actually observe it, *perpetually* inconsistent — and the
engineering stance is that this is "consistently... for now, good enough,
eventually". The piece exposes that "eventual consistency" is a euphemism
that names the desirable limit rather than the lived state, and that the
real design decision is the conscious acceptance of permanent, bounded
wrongness in exchange for availability.

## Extracted claims

- **Definitional:** eventual consistency guarantees convergence in the
  absence of updates, which in a continuously written system means the
  observable state is inconsistent essentially always. This is technically
  accurate, not just rhetorical.
- **Normative:** "good enough" is a legitimate — often correct —
  engineering position, but only when held explicitly; renaming
  inconsistency does not make the tradeoff, deciding does.
- **Empirical:** teams frequently adopt eventually consistent designs
  without articulating the staleness bounds users will actually experience.
  (Author's experience; checkable against distributed-systems practice
  literature.)

## Framework relevance

A crisp instance for a tradeoffs concept: consistency vs. availability is
the canonical engineering tradeoff (CAP), and the piece shows how vocabulary
can hide a tradeoff instead of making it. Also feeds map-vs-territory via
naming: the term describes the map's limit, the territory holds the
inconsistency. Pairs with *Acceptance* (008 — broken and works anyway).

## Quotable

- "That which is eventually consistent / Is perpetually inconsistent"
