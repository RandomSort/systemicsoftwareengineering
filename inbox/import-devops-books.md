# Import: two DevOps book manuscripts (2020)

Captured 2026-07-08 from the author's two unfinished private manuscripts.
Source notes: `knowledge/sources/imported/devops-according-to.md` and
`knowledge/sources/imported/devops-revolution.md`.

Manuscript paths referenced below:
- DA = /workspace/devopsaccordingtojohanabildskov (repo: randomsort/devopsaccordingtojohanabildskov)
- DR = /workspace/devopsrevolution (repo: randomsort/devopsrevolution)

For /process-inbox: each candidate below is a potential seed concept in
`framework/`; the tension candidates belong in `knowledge/tensions/`; the
open questions in `knowledge/questions.md`.

---

## Candidate framework concepts

### Principles before practices
Practices adopted without their generating principles decay: the organization
drifts back, impact stays local or temporary, and imitation of "cool
companies" becomes cargo culting. But practices are not mere outputs — they
push back on principles and higher organizational layers, so the stack is
bidirectional. (DA `manuscript/1-the-challenge-of-defining-devops.md`)

### Whole-value-stream optimization
"Always consider the entire value stream" (DA Flow1): optimize globally,
decompose functional silos, never optimize a segment. Connects to DR's BAPO /
"structure eats strategy" — organize (and architect) around the business's
value streams. (DA `manuscript/2-meta-principles.md`; DR
`manuscript/chapter1.md` BAPO topic)

### The value stream is not homogeneous (fuzzy front end vs. delivery pipeline)
DA Flow7: the exploratory front end and the repeatable delivery pipeline have
separate properties and need different management/measurement regimes. This is
also the reconciliation point for "lean is not sufficient in product
development" (DR, via Reinertsen): flow metrics fit the pipeline, information-
buying economics fit the front end. (DA `manuscript/2-meta-principles.md`; DR
`manuscript/chapter1.md` product-development-flow topic)

### Make work visible, measure flow
DA Flow2–5 as one cluster: visualize work; measure WIP, queue size, cycle
time. Plus Flow6, "handoffs are not free" — handoffs are a real cost center
(knowledge loss, queues), not a neutral org-chart artifact. (DA
`manuscript/2-meta-principles.md`)

### Transformation as paradigm shift ("DevOps Revolution Model")
DR's namesake thesis: DevOps adoption follows Kuhn's structure — normal
science, anomalies, revolution, new normal that then evolves (Genesis →
Revolution → Evolution → Epitaph). Explicitly positioned as "a different
approach than the three ways". (DR `manuscript/chapter1.md`)

### Organizational zone of proximal development
Extrapolate Vygotsky's ZPD from individuals to organizations: an org can only
adopt what is adjacent to its current capability. Author flags this as his own
speculation ("I do believe this can be extrapolated"). Converges with the
alignment trap and infrastructure-as-precondition. (DR
`manuscript/chapter1.md` ZPD topic)

### The alignment trap
A named failure mode of traditional transformations: increasing alignment
while disregarding whether the technology organization can execute. Alignment
without execution capability makes outcomes worse, not better. (DR
`manuscript/chapter1.md` alignment-trap topic)

### Infrastructure is more than technical
Infrastructure includes mental infrastructure, organizational infrastructure
(hierarchies, incentives, communication structures), and cultural
infrastructure. Corollary: "empowered teams without the infrastructure is not
a win" — autonomy != anarchy; empowerment needs enabling structure. (DR
`manuscript/chapter1.md` Infrastructure and Drive topics)

### Transformation needs torch bearers and external tension
A transformation is a continuous disruption of the way of working and the
toolstack; sustaining it requires persistence, internal torch bearers who keep
re-introducing tension, and external inputs (consultants, conferences,
training, peer networks). (DA `possible-topics.md`)

### Names are load-bearing (Meta1)
"DevOps is a horrible name, but it is the best we have": a movement's label
constrains what people think it covers, yet shared vocabulary beats accurate
vocabulary — abandoning the banner costs more than the misreading. Generalizes
to any framework term. (DA `manuscript/2-meta-principles.md`)

### Prescription vs. context-sensitivity
The DevOps culture is averse to prescriptive frameworks, producing vague
guidance ("Just be yourself, but DevOps!"); DA deliberately chooses to be
prescriptive while disclaiming one-true-way status. When is an opinionated
recipe a service and when is it cargo-cult fuel? (DA
`manuscript/1-the-challenge-of-defining-devops.md`)

### Developer-agency antipatterns
A diagnostic checklist of how orgs disempower developers: devs not present
where change is decided; change planned *to* dev rather than with them; devs
"protected" from meetings/planning; devs not owning their own time; leadership
deprioritizing onboarding; refusing to change organizational language;
treating "gatekeeper" as a taboo word. (DA `possible-topics.md`)

### The Peter-Principle trust tax
Subject-matter experts promoted into management micro-manage from dated
expertise; skilled people must first out-argue the manager before doing the
work, until trust is built — a structural drag on the team. The only fully
drafted passage in DR. (DR `manuscript/chapter1.md` Peter Principle topic)

### Anti-presentism about operations
Pushback on the "before DevOps, ops was clueless" narrative: it is not just
now that we figured out how to deliver value. Historical humility as a
framework hygiene rule. (DA `possible-topics.md`)

### Exploitation vs. exploration of value streams
"If we organize around existing value streams, how do we create new value
streams?" — value-stream orientation optimizes the existing business and may
foreclose emergent business. Connects BAPO, zone management (core vs.
context), Crossing the Chasm. (DR `manuscript/chapter1.md` BAPO and
zone-management topics)

---

## Where the manuscripts agree

- Shared canon: Westrum, CALMS, the Three Ways, Team Topologies/Conway
  territory appear in both.
- Both are principles-first and systems-level: DA attacks "practices without
  principles"; DR grounds everything in complex sociotechnical systems and
  mental models.
- Both are value-stream oriented (DA Flow1; DR BAPO/value-stream
  orientation).
- Both treat culture as typed and measurable (Westrum in both topic lists).
- Both resist hype: DA's anti-presentism about ops; DR's recorded skepticism
  of Tuckman and of fake agile (DoD papers).

## Where they disagree — tension candidates

### Tension candidate: recipe vs. revolution
DA endorses the Three Ways precisely because they "can be interpreted as a
recipe for how to approach DevOps transformations", and frames transformation
as *continuous* disruption. DR explicitly says "The DevOps Revolution Model™
is a different approach than the three ways" and frames adoption as a Kuhnian
*paradigm shift* — punctuated, not recipe-followable. Same author, two change
models: incremental/sequenced vs. revolutionary/discontinuous. (DA
`manuscript/1-the-challenge-of-defining-devops.md`; DR
`manuscript/chapter1.md`)

### Tension candidate: lean flow metrics vs. product-development economics
DA's Flow2–5 principles are classic lean flow management (visualize, WIP,
queues, cycle time). DR records Reinertsen's "Lean is not sufficient in
Product Development" — asymmetric payoffs and buying information beat waste
elimination in the front end. DA's own Flow7 (fuzzy front end has separate
properties) gestures at the resolution, but the two drafts pull in different
directions about how central flow metrics should be. (DA
`manuscript/2-meta-principles.md`; DR `manuscript/chapter1.md`)

### Tension candidate (intra-DA, worth filing anyway): prescriptive stance vs. anti-prescriptive culture
DA both criticizes the anti-prescriptive culture and concedes no one-true-way
exists. If practices-without-principles is the disease, is a prescriptive
book a cure or another vector? (DA
`manuscript/1-the-challenge-of-defining-devops.md`)

---

## Open questions

- What was Johan's own definition of DevOps going to be? The heading exists
  in DA ch. 1 but is empty — the framework may now be the answer.
- What tiers were planned beyond Meta and Flow in DA's principle scheme
  (Feedback? Learning?), mirroring the Three Ways?
- What exactly was "The DevOps Revolution Model™"? Only its Kuhnian skeleton
  and its opposition to the Three Ways survive in DR.
- Does organizational ZPD (DR) hold up empirically, and how does it relate to
  the alignment trap — are they the same constraint seen from learning vs.
  strategy angles?
- How do new value streams emerge in a value-stream-organized company? (DR's
  own recorded open problem.)
- DR's final self-questions: who is the audience, what are we missing, is
  psychological safety under-covered — do these still apply to this
  framework?
