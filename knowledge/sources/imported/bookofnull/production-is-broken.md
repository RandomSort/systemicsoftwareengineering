---
title: Production (Book of Null 009)
type: post
author: Johan Abildskov
year: 2026
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# Production

Source piece: `bookofnull/pieces/009-production-is-broken.md` (six-line
litany). Companion piece: `bookofnull/pieces/008-broken.md` ("Everything is
broken. / It works anyway.").

## Core argument

A litany that opens and closes with "Production is broken", bracketing four
declarations of personal non-involvement (didn't deploy, didn't approve,
didn't test, didn't write). The structure makes the point: the speaker's
complete innocence changes nothing about the system state. Brokenness is a
property of the system, not of any actor, and the instinctive first move in
an incident — establishing that it wasn't me — is causally and operationally
irrelevant. The companion piece (008) adds the wider stance: everything is
always somewhat broken, and working-anyway is the normal condition.

## Extracted claims

- **Empirical:** incident response commonly begins with responsibility
  positioning (was it my change?) before system repair; blame-oriented
  cultures amplify this. (Checkable against incident-management and
  blameless-postmortem literature.)
- **Definitional:** "production is broken" is a statement about system
  state; individual innocence and system brokenness are orthogonal.
- **Definitional (008):** partial brokenness is the steady state of
  complex systems; "working" means functioning despite latent faults, not
  absence of faults.
- **Normative:** ownership should attach to outcomes (the system works),
  not to actions (I didn't touch it).

## Framework relevance

Feeds concepts around production reality, blamelessness, and
system-over-individual attribution: in a systemic view, asking "whose
change?" is a category error before asking "what is the system doing?".
Resonates with Richard Cook's *How Complex Systems Fail* (systems run in
degraded mode; every incident has multiple contributors) — a good /enrich
target. Possible tension: accountability practices that require identifying
individual causes.

## Quotable

- "Production is broken / I did not deploy the change / ... / Production is broken"
- "Everything is broken. / It works anyway." (008)
