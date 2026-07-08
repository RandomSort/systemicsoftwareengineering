---
title: "The why, what and how of scaling Git repositories"
type: talk
author: Johan Abildskov
year: 2019
link: https://youtu.be/J_RekbDzWrE (source: /workspace/abildskov.io/content/talks/git-merge-2019.md)
feeds: []
added: 2026-07-08
---

# The why, what and how of scaling Git repositories

> **Evidence level:** talk page holds title, event (Git Merge 2019), and a
> YouTube recording link. The recording exists publicly, so inferred claims
> below are recoverable/verifiable by watching it; until then treat them as
> speculative.

## Core argument (inferred)

Repository scaling is presented in why/what/how order: first the forces that
make repositories grow or multiply (organization size, history, binaries,
monorepo-vs-polyrepo choices), then what "scaling" concretely means, then the
techniques. The ordering is the interesting part — it insists that scaling is
a *motivated sociotechnical decision*, not a tooling reflex. Repository
structure encodes team structure, ownership boundaries, and change-flow; Git
performance problems are usually organizational decisions surfacing as
technical pain.

## Extracted claims

- **[normative]** (inferred from structure) "Why" precedes "how": adopting
  scaling techniques without articulating the forcing problem is the failure
  mode the talk is built against.
- **[empirical]** (inferred, recoverable from recording) There is a real
  spectrum of scaling techniques (splitting, submodules/subtrees, LFS-style
  binary handling, monorepo tooling) with distinct trade-offs, none dominant.

## Agreements and disagreements

- Feeds a framework thread about *artifact structure mirroring organizational
  structure* (Conway-adjacent, but for repositories rather than architecture):
  the unit of version control is a socio-organizational boundary choice.
- Consistent with the corpus-wide why-before-how stance (DOPIER's
  "Deliberate", "beyond the buzzword").
- Verification path exists: the recording at youtu.be/J_RekbDzWrE should be
  watched before any claim here is cited as evidence.

## Quotable

- Title itself encodes the method: "The why, what and how of scaling Git
  repositories" — in that order.
