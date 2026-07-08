---
title: The Green Build (Book of Null 019)
type: post
author: Johan Abildskov
year: 2026
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# The Green Build

Source piece: `bookofnull/pieces/019-pipeline-sonnet.md` (a sonnet).

## Core argument

A love sonnet to the one green build among "most red and grey" peers,
achieved by patient retrying of flaky builds. The satire: the green build is
supposed to be a *measurement* of the change's quality, but the engineer has
turned it into a *target* and optimized the signal directly. A green
obtained by re-rolling the dice carries no information, yet it still confers
permission to merge and go home — the final line's "surely, I did not
introduce too much debt" is the self-deception said out loud. It is
Goodhart's law enacted at the level of a single developer and a single
afternoon.

## Extracted claims

- **Empirical:** flaky test suites induce retry-until-green behavior, which
  destroys the informational value of CI signals; test flakiness at scale is
  well documented (e.g., Google's flaky-test reports — /fact-check target).
- **Definitional:** a gate whose outcome can be re-sampled until it passes
  is not a gate; the effective quality bar is "passes at least once", not
  "passes".
- **Normative:** the integrity of a feedback signal matters more than its
  color; a trustworthy red is worth more than a negotiated green.

## Framework relevance

Concrete, recognizable anchor for feedback-signal integrity: feedback loops
only regulate a system when the signal is honest, and humans under delivery
pressure will rationally corrupt signals that stand between them and going
home. Connects to Goodhart's law, normalization of deviance, and *The work*
(042 — proxies mistaken for the thing). Strong candidate example for any
note on quality gates or CI/CD.

## Quotable

- "Retrying the builds, my change is sublime / The build is Green, though it was resistant"
