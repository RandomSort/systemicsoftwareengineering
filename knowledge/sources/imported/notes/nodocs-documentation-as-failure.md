---
title: "#NoDocs — documentation need as a failure signal"
type: post
author: Johan Abildskov
year: ~2018
link: https://github.com/RandomSort/notes (ideas/nodocs.md)
feeds: []
added: 2026-07-08
---

# #NoDocs — documentation need as a failure signal

## Core argument

When a user has to consult documentation — the thirteen-page install
document, the fourth StackOverflow tab, the obscure error code — that is a
failure on the part of the developer. The mission is value for the user; when
software breaks or is complex, it is the builder's duty to make the road back
to value frictionless. The provocation "aim to make your documentation
obsolete" does not mean write none — it means build software so obvious,
error-resilient, and self-explaining that the docs are rarely needed:
"consulting the manual is the first step towards making a support request."

## Extracted claims

- Normative (the thesis): documentation demand is a proxy metric for product
  friction; drive it down by fixing the product, not by writing more docs.
- Normative: do not blame the user for your assumptions — a script that
  crashes on a missing directory *knows* the circumstance, problem, and
  resolution; failing without saying so (or without offering to fix it) is an
  abdication. "It should not be an *exceptional* situation."
- Empirical (self-observation elevated to design rule): "If I have to do a
  manual task, sooner or later I will fuck it up" — so script what you can,
  and have the software offer to do setup for the user.
- Normative: contain yourself — information that doesn't immediately help the
  user fix the issue is hindering, not helping (debug data ≠ user help).
- Normative: name things for the user's reasoning, not cleverly —
  `RetryAfterTimeout` over `TimeoutRetry`; obviousness gives the user
  *context* to predict behavior.
- Normative: walk a mile in their boots — "the terminal is king" is the
  builder's context, not necessarily the user's; meet users in *their*
  context (write the plugin, build the IDE integration).
- Empirical (cited as positive example): Git's `git status` output usually
  leaves you in no doubt about the next action — evidence that self-guiding
  CLI software is achievable.

## Agreements and disagreements

This is a systems view of documentation: docs, error messages, support
tickets, and product friction form one feedback loop, and docs are the
pressure-relief valve that hides the signal. Tension candidate: the same
vault treats good READMEs as a core obligation (Consultant's Oath: newcomer
must succeed "with only the information in the README") — resolve as
layers: docs as capability floor vs. docs as friction symptom.

## Quotable

- "Consulting the manual is the first step towards making a support request."
- "If I have to do a manual task, sooner or later I will fuck it up."
