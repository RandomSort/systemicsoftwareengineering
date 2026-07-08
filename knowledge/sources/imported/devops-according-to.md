---
title: DevOps According to Johan Abildskov (unfinished manuscript)
type: book
author: Johan Abildskov
year: 2020
link: https://github.com/randomsort/devopsaccordingtojohanabildskov
feeds: []          # framework notes this source informs
added: 2026-07-08
---

# DevOps According to Johan Abildskov

Unfinished book draft (private repo, last touched mid-2020). Two manuscript
chapters plus a topics backlog. Despite its incompleteness it contains the
clearest early statement of the author's stance: DevOps must be taught
*principles-first*, and the author is willing to be prescriptive where the
wider DevOps culture refuses to be. The "meta-principles" chapter, though
skeletal, reads like a direct ancestor of a systemic-software-engineering
framework: named, numbered principles about flow and measurement.

## Core argument

DevOps has no official definition — it is a grassroots movement gone
mainstream, so every vendor and guru defines it to suit their purpose, which
leaves newcomers (individuals and organizations) lost. Jumping straight to the
concrete layer (automation, cloud, "the Jenkins person") yields *practices
without principles*: change that cannot anchor in the organization and whose
impact stays local or temporary. The book's answer is a deliberately
prescriptive, opinionated flavour of DevOps — not claimed as the one true
definition, but well-defined enough to actually follow — grounded in explicit
principles from which practices can be continuously re-derived.

## Chapter-by-chapter

### 1. The Challenge of Defining DevOps (`manuscript/1-the-challenge-of-defining-devops.md`)

- No official definition exists; the definitional vacuum has "widespread
  consequences": vendors define DevOps self-servingly, newcomers cannot
  navigate, and the anti-prescriptive culture produces vague guidance the
  author caricatures as "Just be yourself, but DevOps!".
- Tools-first DevOps (visible in r/devops questions and "DevOps Engineer" job
  ads) leads to practices without principles → organizational drift away from
  the new practices → local or temporary impact. Understanding *why* the
  practices exist lets you keep re-applying the principles and grow capability
  instead of cargo-culting "what the cool companies are doing". Tools and
  practices still matter: they "provide push back" to principles and to higher
  layers of the organization (feedback runs both ways in the stack).
- Surveys existing definitions to build shared language:
  - **The Three Ways** (Kim et al., *The Phoenix Project*): flow of value
    end-to-end with global optimization and de-siloing; amplified feedback
    loops; then — on that foundation — a culture of continuous
    experimentation. The author calls it one of his favorite brief
    explanations because it "can be interpreted as a recipe for how to
    approach DevOps transformations". Notably reads the three ways as
    *sequenced*: ways one and two are prerequisites for way three.
  - **CALMS** — section stubbed, listed but unwritten.
  - **Ken Mugrage**: "A culture where people, regardless of title or
    background, work together to imagine, develop, deploy and operate a
    system." (quoted approvingly)
  - **Johan Abildskov** — his own definition is an empty heading; the draft
    stops before committing to it.
- A stub section on certifications (SAFe DevOps, DevOps Institute) — the
  institutionalization of a movement that resists definition.

### 2. Meta-principles (`manuscript/2-meta-principles.md`)

Headings only — no prose — but the naming scheme and the titles themselves are
the payload. The scheme separates a **Meta** tier from a **Flow** tier,
implying planned further tiers (feedback? learning?) mirroring the Three Ways:

- **Meta1: DevOps is a horrible name, but it is the best we have.** The name
  wrongly suggests it is only about dev and ops; the movement's label
  undersells its scope, yet abandoning it would cost the shared banner.
- **Flow1: Always consider the entire value stream.**
- **Flow2: Visualize work.**
- **Flow3: Measure work in progress.**
- **Flow4: Measure queue size.**
- **Flow5: Measure cycle time.**
- **Flow6: Handoffs are not free.**
- **Flow7: The fuzzy front end and delivery pipeline have separate
  properties.** (The exploratory/ideation part of the value stream obeys
  different dynamics than the repeatable delivery part — one measurement and
  management regime does not fit both.)

Flow2–5 are pure Kanban/lean flow-management; Flow6–7 are the more original
moves: pricing handoffs as a real cost, and refusing to treat the value
stream as homogeneous.

### Topics backlog (`possible-topics.md`)

- **Agile without software**: the need for technical excellence; "why the
  agile industrial complex is bad" — process transformation divorced from
  engineering capability.
- **Westrum culture** (organizational culture typology).
- **Anti-presentism**: pushback against contemporary DevOps rhetoric that
  paints pre-DevOps ops as "clueless" — it is not "just now that we have
  figured out how to deliver value".
- **DevOps transformations as continuous disruption** of the way of working
  and toolstack; sustaining one takes persistence, internal "torch bearers"
  who keep re-introducing tension, and external inputs (consultants,
  conferences, training, peer networks).
- **Antipatterns** (a diagnostic list, mostly about how organizations treat
  developers): devs not present where change is decided; leaders who
  deprioritize onboarding ("It's important that we get you started right,
  but my calendar unfortunately… we will talk tomorrow"); treating
  "gatekeeper" as a taboo word instead of a role to examine; "we plan change
  *to* Dev" (change done to teams, not with them); the belief that devs must
  be "protected" from meetings/planning; refusal to change organizational
  language; unexamined assumptions about devs; devs not owning their own
  time.

## Extracted claims

1. **[Definitional]** DevOps has no official definition; it is a label
   retroactively applied by many independent discoverers of similar
   principles. (ch. 1)
2. **[Empirical]** The definitional vacuum measurably harms newcomers and
   organizations trying to adopt DevOps, and is exploited by purpose-driven
   definitions from vendors/frameworks. (ch. 1 — checkable against adoption
   literature)
3. **[Empirical]** Adopting DevOps practices without their underlying
   principles produces change that decays: the organization drifts back, and
   impact stays local or temporary. (ch. 1)
4. **[Normative]** DevOps guidance *should* be prescriptive — an opinionated,
   well-defined flavour beats "just be yourself, but DevOps", even though the
   DevOps culture is averse to prescriptive frameworks. (ch. 1)
5. **[Definitional]** The Three Ways can be read as a *sequenced recipe*:
   flow enables feedback, and both are prerequisites for continuous
   experimentation. (ch. 1)
6. **[Normative]** Practices deserve respect as more than principle-output:
   they push back on principles and higher organizational layers. (ch. 1)
7. **[Normative/Definitional]** Meta1: the name "DevOps" is bad but worth
   keeping — shared vocabulary beats accurate vocabulary. (ch. 2)
8. **[Normative]** Flow1: optimize the entire value stream, never a local
   segment. (ch. 2)
9. **[Normative]** Flow2–5: work must be made visible and flow must be
   measured — WIP, queue size, cycle time. (ch. 2)
10. **[Empirical]** Flow6: handoffs carry real, non-zero cost (knowledge
    loss, queuing, motivation). (ch. 2)
11. **[Definitional]** Flow7: the fuzzy front end and the delivery pipeline
    are regime-distinct parts of the value stream with separate properties;
    they must not be managed by the same rules. (ch. 2)
12. **[Empirical]** Sustained transformation requires continuous
    re-introduction of tension by internal torch bearers plus external
    inputs; otherwise it stalls. (possible-topics.md)
13. **[Empirical]** Pre-DevOps operations was not clueless; the "before times
    were dark" narrative is historically wrong. (possible-topics.md)

## Feeds (framework relevance)

- Claims 3–4 → a *principles-before-practices* / anti-cargo-culting concept.
- Claims 8–11 (the Flow principles) → flow, work-visibility, and
  value-stream-segmentation concepts; Flow7 is a candidate seed on its own.
- Claim 7 → a concept about naming and shared vocabulary in movements.
- Claim 12 → transformation-sustainability / organizational-change concepts.
- The antipatterns list → diagnostic material for concepts about developer
  agency (devs owning their time, change done *with* not *to* teams).

## Agreements and disagreements

- Agrees with the sibling manuscript (*DevOps Revolution*) on Westrum, CALMS,
  the Three Ways as shared reference points, and on systems-level,
  principles-first framing.
- Internal tension worth keeping: the book praises the Three Ways *as a
  recipe* and aims to be prescriptive, while acknowledging DevOps culture is
  adverse to prescription — prescription vs. context-sensitivity is live.
- Diverges from *DevOps Revolution* on the change model: here transformation
  is a recipe / "continuous disruption"; there it is framed as a Kuhnian
  revolution explicitly different from the Three Ways. See
  `inbox/import-devops-books.md` for the candidate tension.

## Quotable

- "This leads to practices without principles." (ch. 1)
- Vague gurus saying "Just be yourself, but DevOps!" (ch. 1)
- "DevOps is a horrible name, but it is the best we have." (ch. 2, Meta1)
- "Handoffs are not free." (ch. 2, Flow6)
- Ken Mugrage (quoted in ch. 1): "A culture where people, regardless of title
  or background, work together to imagine, develop, deploy and operate a
  system."
