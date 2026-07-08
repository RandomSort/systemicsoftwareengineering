---
title: Test your Assumptions (Book of Null 038)
type: post
author: Johan Abildskov
year: 2026
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# Test your Assumptions

Source piece: `bookofnull/pieces/038-test-your-assumptions.md` (four-line
koan).

## Core argument

"I had an assumption / I wrote a test / The test failed / I have an
assumption." The tense shift (had → have) is the payload: testing an
assumption did not convert it to knowledge. A failing test presents a
choice between two assumptions — the one about the code and the one encoded
in the test — and until you interpret the failure, you have merely traded
one assumption for another (or discovered you hold two). Verification
produces evidence, not verdicts; knowledge is formed in the interpretation,
which is itself fallible.

## Extracted claims

- **Definitional:** a test is a consistency check between two encodings of
  belief (expected behavior in the test, actual behavior in the code); a
  failure localizes a disagreement, not the truth.
- **Empirical:** a nontrivial fraction of failing tests are wrong
  themselves (incorrect expectations, broken fixtures, environmental
  causes) — checkable against test-repair and flaky-test literature.
- **Normative:** treat green/red as evidence requiring interpretation;
  beware the comfort of "tested" as a terminal epistemic state.

## Framework relevance

The corrective sibling of *On Faith* (035): even the standard remedy for
faith — testing — returns you to belief-management, one level up. Feeds a
feedback-loops concept with an important nuance: a feedback signal is only
as good as the model that interprets it. Also pairs with *The Green Build*
(019): 038 shows the signal is ambiguous even when honest; 019 shows what
happens when it is also dishonest.

## Quotable

- "The test failed / I have an assumption"
