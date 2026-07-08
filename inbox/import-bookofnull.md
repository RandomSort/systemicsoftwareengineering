# Import capture: Book of Null corpus

Captured 2026-07-08 from the private corpus (github.com/RandomSort/bookofnull).
Overview: `knowledge/sources/imported/bookofnull.md`; detailed notes in
`knowledge/sources/imported/bookofnull/`. Each item below is a candidate
framework concept for /process-inbox to route (seed concept, proposal, or
merge into an existing note). Source references use corpus paths for
traceability.

---

## Candidate concepts

### Map vs. territory in software
Source code, dashboards, tickets, names, and diagrams are representations
that engineers habitually mistake for the system itself; the running system
in production is the only territory. Candidate root concept — several other
candidates below are instances of it at different layers.
(`bookofnull/pieces/002-understanding-code.md`,
`bookofnull/pieces/025-youarehere.md`, `bookofnull/pieces/027.thisisnotapipe.md`,
`bookofnull/pieces/042-the-work.md`)

### Causal humility
We treat our cause-and-effect inferences as the strongest link in our
reasoning when they are the weakest — while reality runs on mechanism alone.
Systems thinking (delays, loops, non-linearity) is largely the discipline of
repairing weak causal models; incident "root causes" deserve hypothesis
status, not finding status.
(`bookofnull/pieces/004-cause-and-effect.md`,
`bookofnull/pieces/040-intelligence.md`)

### Feedback-signal integrity
Feedback loops only regulate a system when the signal is honest, and people
under pressure rationally corrupt signals that stand between them and done —
the flaky build retried until green being the canonical case. Goodhart's law
as a property of every gate whose outcome can be re-sampled.
(`bookofnull/pieces/019-pipeline-sonnet.md`,
`bookofnull/pieces/042-the-work.md`)

### Instrument-mediated perception (observability as sight)
Software has no perceivable surface; engineers "see with their hands" and
are otherwise blind. Every perception of a system goes through an instrument
someone chose to build, so an organization's thinking quality is bounded by
its instrumentation.
(`bookofnull/pieces/003-seeing.md`, `bookofnull/pieces/002-understanding-code.md`)

### Relational correctness (outcomes over outputs)
Right answers, features, and tools are right only relative to the humans
using them; an artifact can be locally correct and systemically wrong. Draws
the system boundary to include users — a framework that stops at the API
measures the wrong system.
(`bookofnull/pieces/029-is.md`, `bookofnull/pieces/007-customer-is-user.md`,
`bookofnull/pieces/037-expectations.md`)

### Everything is broken and works anyway
Partial brokenness is the steady state of complex systems; "working" means
functioning despite latent faults. Corollary: individual innocence is
orthogonal to system state — "production is broken" is about the system, not
about who touched it.
(`bookofnull/pieces/008-broken.md`, `bookofnull/pieces/009-production-is-broken.md`,
`bookofnull/pieces/028-eventual-consistency.md`)

### The intent-specification gap
Whether the machine did or didn't do exactly what you told it, the problem
is the same: the distance between what you said and what you meant. Persists
unchanged from assembly to LLM prompting; human-plus-machine composition
moves the crack rather than closing it ("neither applies common sense").
(`bookofnull/pieces/036-computers.md`, `bookofnull/pieces/017-agents.md`,
`bookofnull/pieces/001-claude.md`)

### Engineering as belief management
Day-to-day engineering vocabulary is belief vocabulary ("this should work");
even testing an assumption returns another assumption to interpret. The
craft is budgeting faith: converting belief to knowledge where verification
is cheap, and knowing where the residual faith lives. Resonates with this
repo's "confidence is data" directive.
(`bookofnull/pieces/035-on-faith.md`, `bookofnull/pieces/038-test-your-assumptions.md`)

### Complexity matching and relocation
Solution complexity vs. problem complexity forms a 2x2, and mismatch in
either direction is information: unexplained simplicity is as suspicious as
unexplained complexity. Tradeoffs as conservation-and-relocation of
complexity — ask where the displaced complexity went (users, operators,
future).
(`bookofnull/pieces/039-tradeoffs.md`, `bookofnull/pieces/028-eventual-consistency.md`)

### Work about work
Tickets, meetings, statuses, and prioritization are maps of work that
organizations drift toward optimizing instead of the work; meanwhile real
work (thinking, resting on a problem) photographs as idleness. Guard the
ratio; when the proxy becomes the deliverable, re-point at the work.
(`bookofnull/pieces/042-the-work.md`, `bookofnull/pieces/011-slacking-off.md`,
`bookofnull/pieces/010-sowhat.md`)

### Language as an engineering surface
Names, capitalized methodologies (agile vs. Agile), and normative keywords
(MUST/SHOULD) are load-bearing infrastructure that fails silently: renaming
a tradeoff ("eventual consistency") can hide it, and branding a practice can
replace it. Possibly a sub-facet of map-vs-territory rather than a concept
of its own.
(`bookofnull/pieces/005-names.md`, `bookofnull/pieces/006-versus.md`,
`bookofnull/pieces/013-RFC-2119.md`, `bookofnull/pieces/031-words-1.md`)

### Gradual failure and risk misperception
The failure idioms we reach for (final straw, boiling frog, elephant in the
room) reveal how badly we perceive slow, cumulative system change: the last
straw gets the fame, not the years of loading. A perception-of-drift concept
adjacent to normalization of deviance.
(`bookofnull/pieces/030-animals.md`, `bookofnull/pieces/040-intelligence.md`)

## Open questions

- Epistemic status of satire: the corpus makes claims via koans with the
  argument deliberately absent. When a framework note cites these pieces as
  sources, what confidence do they support — are they evidence, or only
  articulation? Suggest treating them as normative/definitional stance
  sources, with empirical grounding required separately.
- Is "everything is broken; it works anyway" an empirical claim about
  complex systems (cf. Cook, *How Complex Systems Fail*) or an accepted
  stance? Affects whether it is /fact-check-able.
- Map-vs-territory shows up at at least four layers (code/production,
  metrics/quality, tickets/work, names/things). One root concept with
  instances, or several sibling concepts? Route deliberately to avoid a
  grab-bag note.
- Candidate tension: "never break the users' expectations" (037) vs.
  relational correctness (029) — if users' expectations are wrong for them,
  which yields? Also vs. deprecation/change as a systemic necessity.
- Candidate tension: "the user is using it wrong means wrong feature" (029)
  vs. "the customer is always right" pricing/market frame (007) — same
  person, conflicting frames; where does the framework stand?
- The AI pieces (001, 017, 041) suggest a possible concept about provenance
  vs. quality (does knowing who/what made it change what it is worth?) —
  currently too thin; park or seed?
- Piece 026 is absent and three pieces are empty files (015-deprecated,
  018-telemetry, 020-pseudo-random) — likely intentional structural jokes;
  no action, noted for corpus fidelity.
