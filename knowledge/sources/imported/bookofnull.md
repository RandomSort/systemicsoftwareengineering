---
title: Book of Null (corpus overview)
type: experience / post collection
author: Johan Abildskov
year: 2026 (in progress; originated in a Halloween meetup talk)
link: https://github.com/RandomSort/bookofnull
feeds: []
added: 2026-07-08
---

# Book of Null — corpus overview

Private corpus imported 2026-07-08. This note is a distilled overview; the
source repo stays private. Individual notes for the most framework-relevant
pieces live in `knowledge/sources/imported/bookofnull/`.

## What the corpus is

*Book of Null* ("Mastering Undefined Behaviour") is the author's own
collection of ~40 very short, self-contained pieces about software
engineering: koans, litanies, structural jokes, and typographic experiments.
It is satire, not comedy — deadpan, precise, designed so the insight is
"absent from the piece, present in the reader". Nothing is explained; each
piece creates the conditions for an observation the reader already half-knew.
It began as verses "cited" from a fictional canonical text during an
incident-report-as-occult-ritual talk, and that framing persists: the pieces
present engineering folk wisdom as scripture.

For the framework, this corpus is valuable precisely because it is
compressed: each piece is a claim about software reality with the
argumentation stripped out. Distilling a piece means reconstructing the
argument the verse implies.

## Recurring themes

1. **Map vs. territory.** Source code, tickets, diagrams, and names are
   representations that get mistaken for the system itself (002, 025, 027,
   031–033, 042). Includes the Magritte homage: a pipe character captioned
   "Ceci n'est pas une pipe".
2. **Engineering epistemics.** What we actually know vs. what we believe:
   causal overconfidence (004), belief masquerading as knowledge (035),
   assumptions that survive their tests (038), hindsight bias around bugs
   (040), instrument-mediated blindness (003).
3. **Production reality and normalization of deviance.** Everything is
   broken and works anyway (008); broken production outlasts everyone's
   innocence (009); the retried-until-green build (019); eventual
   consistency as perpetual inconsistency accepted as good enough (028).
4. **Correctness is relational.** Right answers, features, and tools are
   only right relative to the humans using them (029, 007, 037).
5. **Language as an engineering surface.** Naming (005), branded
   methodology capitals (006), RFC 2119 keywords (013), bit/byte/word
   puns about units of data vs. units of meaning (031–033).
6. **Work about work.** Tickets, meetings, and status updates as proxies
   mistaken for work (042); the ambiguity of "slacking off" in thinking
   work (011); "So what?" as the move from complaint to action (010).
7. **Humans, computers, and AI.** The intent–instruction gap (036), the
   complementarity-and-shared-blind-spot of humans plus machines (017,
   001), and whether provenance changes quality (041).
8. **Self-reference and structural jokes.** Pieces that enact their own
   subject: a book revoking consent to be read (016), a disclaimer that
   confirms what it denies (024), the one piece that breaks the book's own
   layout rule about expectations (037), and empty files as pieces.

## Piece inventory

One line per file in `bookofnull/pieces/` (piece 026 is absent from the
numbering; three files are empty, plausibly as title-only jokes).

- `001-claude.md` — one sentence of praise for AI-assisted work, re-stressed eight ways; emphasis alone changes what is being doubted.
- `002-understanding-code.md` — syllogism: I understand the code; the code is not production; I do not understand the code.
- `003-seeing.md` — engineers "see with their hands" and are otherwise blind to the systems they fix.
- `004-cause-and-effect.md` — causal links: believed the strongest, actually the weakest in our minds, the only thing in reality.
- `005-names.md` — Shakespeare applied to `AbstractBillingValidationServiceInstanceFactoryImpl`; the name does not change the function.
- `006-versus.md` — being vs. branded doing: agile vs. Agile, safe vs. Certified SAFe.
- `007-customer-is-user.md` — the user always does it wrong; the customer is always right; they are the same person.
- `008-broken.md` — everything is broken; it works anyway; everything is broken.
- `009-production-is-broken.md` — a litany of personal non-involvement that leaves production exactly as broken.
- `010-sowhat.md` — "So what?" as the challenge that turns complaints, frustrations, and excuses into actions.
- `011-slacking-off.md` — a litany of "I'm not slacking off" that blurs compiling, agents, resting, thinking, and Slack.
- `012-worklife.md` — permutations of work/life until the compound stops meaning anything.
- `013-RFC-2119.md` — MUST, SHOULD, and COULD turned on the specs that define them.
- `014-random-prep.md` — DIY entropy verse: hand-made randomness that is "just about good enough".
- `015-deprecated.md` — empty file (the piece is deprecated).
- `016-donot-readme.md` — a book revoking consent to be read; README inverted.
- `017-agents.md` — humans and computers are better together, but "neither applies common sense".
- `018-telemetry.md` — empty file (the telemetry is collected where you cannot see it).
- `019-pipeline-sonnet.md` — a sonnet to the one green build among flaky red ones, achieved by retrying.
- `020-pseudo-random.md` — empty file.
- `021-blame.md` — `git blame` wordplay; the blamed name turns out to be one's own.
- `022-byot.md` — Web 3.0 as fill-in-the-blanks: user-generated content where the reader supplies the content.
- `023-incentivise-docs.md` — a git commit log: an empty `AGENTS.md` created to "increase likelihood engineers will write documentation".
- `024-fiction.md` — a work-of-fiction disclaimer that confirms the production-database incident it denies.
- `025-youarehere.md` — a single dot: "You are here".
- `027.thisisnotapipe.md` — a pipe character captioned "Ceci n'est pas une pipe".
- `028-eventual-consistency.md` — eventually consistent means perpetually inconsistent, consistently good enough for now.
- `029-is.md` — four koans on whether right answers, questions, features, and tools are right when humans use them wrong.
- `030-animals.md` — the failure-idiom zoo: ignored elephants, famous final straws, and the misjudged risk of boiling frogs.
- `031-words-1.md` — a bit of data should be more than a byte; units of data vs. units of meaning.
- `032-words-2.md` — taking a byte from ever-larger words still yields only a byte.
- `033-words-3.md` — nibbles, little ends and big ends, and staying hungry on half a byte.
- `034-reading.md` — yelling at a blog: "I shouldn't care, but they are doing it wrong".
- `035-on-faith.md` — every inflection of "I can't believe this works", resolving into faith.
- `036-computers.md` — it {did, didn't} do exactly what I told it; that's the problem.
- `037-expectations.md` — "Never break the users' expectations" — deliberately the book's only rule-breaking left-hand page.
- `038-test-your-assumptions.md` — assumption, test, failing test — and still an assumption.
- `039-tradeoffs.md` — a simple solution to a complex problem; a complex solution to a simple problem.
- `040-intelligence.md` — feeling smart and stupid about the same bug, both "obvious now".
- `041-perceptron.md` — the poem's quality was fixed before you learned whether a human or an AI wrote it.
- `042-the-work.md` — the ticket, the meeting, the status update, and prioritizing are not the work; the work is the work.

## Individual source notes

Detailed notes (core argument, claims, framework relevance) exist for the
twelve most framework-relevant pieces:

- [understanding-code](bookofnull/understanding-code.md) (002)
- [seeing](bookofnull/seeing.md) (003)
- [cause-and-effect](bookofnull/cause-and-effect.md) (004)
- [production-is-broken](bookofnull/production-is-broken.md) (009)
- [the-green-build](bookofnull/the-green-build.md) (019)
- [eventual-consistency](bookofnull/eventual-consistency.md) (028)
- [right-and-wrong](bookofnull/right-and-wrong.md) (029)
- [on-faith](bookofnull/on-faith.md) (035)
- [computers](bookofnull/computers.md) (036)
- [test-your-assumptions](bookofnull/test-your-assumptions.md) (038)
- [tradeoffs](bookofnull/tradeoffs.md) (039)
- [the-work](bookofnull/the-work.md) (042)

## Quotable

Kept deliberately short; the source is a private repo pending publication.

- "Everything is broken. / It works anyway." — *Acceptance* (008)
- "The work is the work" — *The work* (042)
