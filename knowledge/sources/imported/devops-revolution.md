---
title: DevOps Revolution (unfinished manuscript)
type: book
author: Johan Abildskov
year: 2020
link: https://github.com/randomsort/devopsrevolution
feeds: []          # framework notes this source informs
added: 2026-07-08
---

# DevOps Revolution

Very early book draft (private repo, last touched late 2020). Only
`manuscript/chapter1.md` carries content — and it is not a chapter but the
book's *outline plus topics backlog*; `chapter2.md` and `chapter3.md` are
untouched Leanpub boilerplate. What survives is nonetheless valuable: a map of
the intellectual territory the author considered load-bearing for DevOps, and
the germ of an original thesis — "The DevOps Revolution Model™" — that frames
DevOps adoption as a Kuhnian paradigm shift rather than a continuous
improvement recipe.

## Core argument (reconstructed from the outline)

DevOps adoption is better understood as a *revolution* — a paradigm shift in
the sense of Kuhn's *Structure of Scientific Revolutions* — than as an
incremental transformation. The planned arc (Introduction → DevOps Genesis →
DevOps Revolution → DevOps Evolution → Epitaph) mirrors Kuhn: a prior normal
science, accumulating anomalies, revolution, then a new normal that itself
evolves. The supporting topics show the intended substance: organizations are
complex sociotechnical systems (systems thinking, Cynefin, mental models)
whose structure dominates strategy (BAPO, Conway's Law, Team Topologies), and
whose change capacity is bounded (zone of proximal development, alignment
trap, infrastructure in the broad sense).

## Chapter-by-chapter

### chapter1.md — Outline and topics (`manuscript/chapter1.md`)

**Planned sections:** (1) Introduction — DevOps, its merits and the business
case; (2) DevOps Genesis; (3) DevOps Revolution; (4) DevOps Evolution;
(5) Epitaph. No section prose was written.

**Topics backlog**, the real content — each entry a candidate chapter with the
author's angle where he recorded one:

- **BAPO** (Jan Bosch, "structure eats strategy"): connects BAPO, value
  stream orientation, and zone management. Key open problem stated: "if we
  organize around existing value streams, how do we create new value
  streams?" — organizing around today's business architecture may foreclose
  emergent business.
- **Product development flow** (Reinertsen): buy information; "asymmetry is
  not necessarily bad" (asymmetric payoffs justify bets); the margin; and
  the pointed claim "Lean is not sufficient in Product Development".
- **Zone management**: core vs. context (Moore).
- **Alignment trap**: a stated reason traditional transformations fail —
  "the agile transformation tends to increase alignment, disregarding
  whether the technology organization is able to execute". Alignment without
  execution capability makes things worse.
- **Westrum** culture typology.
- **Kuhn, Structure of Scientific Revolutions** — the book's namesake lens.
- **Zone of Proximal Development**: "I do believe this can be extrapolated
  from individuals to organizations" — organizations can only learn what is
  adjacent to their current capability.
- **Mental models**: "we work with the mental models, both individual and
  shared" (references itsonlyamodel.com).
- **Systems thinking**: "we build complex sociotechnical systems, where
  cause and effect might not be obvious."
- **Cynefin** (flagged as needing more study), **Conway's Law**,
  **Team Topologies**, **the ladder of inference** (as a team, org, and
  individual practice), **Five Dysfunctions of a Team** (the trust model),
  **Tuckman** (noted with skepticism: "there seem to be some literature
  suggesting that this is not a very good model?"), **Crossing the Chasm**.
- **Three Ways of DevOps**: "I think The DevOps Revolution Model™ is a
  different approach than the three ways. Might be something interesting
  there." — the author positions his model *against* the canonical one.
- **CALMS** ("probably need to be covered"), **The Five Ideals**,
  **Theory of Constraints**, **Shifting Left**, **Lean software wastes**,
  **Drive** (Pink) with the gloss "Autonomy != anarchy", and several US DoD
  papers on detecting fake agile.
- **Infrastructure**: "Infrastructure is not just technical. It also refers
  to the mental infrastructure — the organizational infrastructure
  (hierarchies, incentives, communication structures) — the cultural
  infrastructure and so on. Empowered teams without the infrastructure is
  not a win."
- **Crosslead / Team of Teams**; **sphere of influence** (control /
  influence / context).
- **Peter Principle** — the only fully drafted passage: promoted-to-
  incompetence subject-matter experts drive micromanagement; the experts who
  should do the work "start behind because they have to spend much effort
  convincing you that their approach is better, until trust has been built";
  some managers never set aside dated expertise, keeping teams less
  productive "due to their own personal interests".
- **Open questions** the author left himself: who is the target audience and
  what are we trying to say; what are we missing; do we miss points on
  psychological safety?

### chapter2.md, chapter3.md

Leanpub template boilerplate (Markdown syntax examples, preview
instructions). No authorial content.

## Extracted claims

1. **[Definitional]** DevOps adoption is a paradigm shift in Kuhn's sense —
   revolution followed by evolution — and this "DevOps Revolution Model" is
   a *different approach* than the Three Ways. (outline structure + Three
   Ways topic note)
2. **[Empirical]** Organizational structure dominates strategy ("structure
   eats strategy", via Jan Bosch/BAPO). (topics)
3. **[Definitional/Open]** Organizing around existing value streams leaves
   unanswered how new value streams emerge. (topics — filed as an open
   question, not a settled claim)
4. **[Empirical]** Lean is not sufficient in product development; product
   development economics (buying information, asymmetric payoffs) require
   more than waste elimination. (topics, via Reinertsen)
5. **[Empirical]** The alignment trap: transformations that increase
   alignment without increasing execution capability fail — a named failure
   mode of traditional agile transformations. (topics)
6. **[Empirical — flagged speculative by the author]** The zone of proximal
   development extrapolates from individuals to organizations: an
   organization can only adopt what is adjacent to its current capability.
   (topics)
7. **[Definitional]** The systems we build and change are complex
   sociotechnical systems where cause and effect are not obvious; mental
   models (individual and shared) are the working material. (topics)
8. **[Definitional]** Infrastructure includes mental, organizational
   (hierarchies, incentives, communication structures), and cultural
   infrastructure — not just technical. (topics)
9. **[Empirical]** Empowering teams without providing that broad
   infrastructure "is not a win". (topics)
10. **[Normative]** Autonomy != anarchy: autonomy requires enabling
    structure. (topics, via Drive)
11. **[Empirical]** Peter-Principled subject-matter-expert managers create a
    trust tax: skilled people must first out-argue their manager's dated
    expertise before doing the work. (topics — the drafted passage)
12. **[Empirical — author's own doubt recorded]** Tuckman's
    forming/storming/norming/performing may not be a well-supported model.
    (topics)

## Feeds (framework relevance)

- Claim 1 → a change-model concept: revolution/paradigm-shift vs. recipe.
- Claims 2–3 → organization-design concepts (structure eats strategy;
  exploitation-vs-exploration of value streams).
- Claims 5–6, 9–10 → transformation-capacity concepts: alignment trap,
  organizational ZPD, infrastructure-as-precondition-for-autonomy. These
  three converge on one idea: *change is bounded by present capability and
  enabling structure*.
- Claims 7–8 → the sociotechnical-systems foundation of the framework
  itself; claim 8's broad-infrastructure definition is close to a framework
  primitive.
- Claim 11 → management/trust dynamics concepts.

## Agreements and disagreements

- Agrees with *DevOps According to Johan Abildskov* on the canon (Westrum,
  CALMS, Three Ways as reference points) and on the systems-level framing.
- Disagrees on the change model: this manuscript explicitly positions its
  revolution model as "a different approach than the three ways", while the
  sibling manuscript endorses the Three Ways as a transformation recipe.
- Its Reinertsen-derived "Lean is not sufficient in product development" sits
  in tension with the sibling's lean-flavored Flow principles (measure WIP,
  queue size, cycle time) — though the sibling's Flow7 (fuzzy front end vs.
  delivery pipeline) points toward the same reconciliation.
- Details in `inbox/import-devops-books.md`.

## Quotable

- "Structure eats strategy." (topics, attributed to Jan Bosch / BAPO)
- "If we organize around existing value streams, how do we create new value
  streams?" (topics)
- "We build complex sociotechnical systems, where cause and effect might not
  be obvious." (topics)
- "Empowered teams without the infrastructure is not a win." (topics)
- "Autonomy != anarchy." (topics)
