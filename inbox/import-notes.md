# Import: notes vault (RandomSort/notes) — candidate concepts and open questions

Captured 2026-07-08 by the notes-vault import. Source notes live in
`knowledge/sources/imported/notes/`; vault paths below are relative to
https://github.com/RandomSort/notes. Each item is a candidate for routing by
`/process-inbox` (seed concept, question, or tension).

## Candidate framework concepts

### Normalized dysfunction
"This is just how it is here" as the terminal state of organizational
pathology: dysfunction that has stopped being noticed, detectable through
jokes ("we're an incubator for our competitors"). The joke is the diagnostic;
the required response is alarm, not acceptance. Vault:
`praqma/talks/13thingsallcompaniesdowrong.md` → source note
`thirteen-things-all-companies-do-wrong.md`.

### The alignment trap
Sequencing claim: improving business–IT alignment before engineering
effectiveness makes things worse; alignment amplifies existing capability,
including dysfunction. Explains agile-transformation dread as rational.
Vault: `praqma/talks/alignment-trap.md` → source note `alignment-trap.md`.
Needs fact-check against Shpilberg et al. (MIT Sloan, 2007).

### Quality as warranted trust
Define software quality as warranted trust that the artifact behaves as
expected (the property a rock has and average software lacks), rather than as
an intrinsic attribute or a bag of practices. Separates practices adopted
from trust produced. Vault: `praqma/talks/thisstoneisbetterthanyoursoftware.md`
→ source note `this-stone-is-better-than-your-software.md`.

### The training-event fallacy
Organizations treat a past training event as durable capability ("we know
Git, we had a training two years ago" / "I know karate, I took a class two
years ago"). Capability is a practice with decay, not an acquisition. Also:
"if I need training I need training now" — capability demand is not
schedulable. Vault: `praqma/talks/13thingsallcompaniesdowrong.md`,
`oneliners.md`.

### Epistemic artifacts vs. authority artifacts
The same figure/model/metric changes function with the power relation it is
used in: informing (offered for shared reasoning) vs. mandating (wielded as
authority). Goodhart-adjacent but about models, not metrics. Vault:
`praqma/talks/abusedfiguresofdevops.md` → source note
`abused-figures-of-devops.md`.

### Consequence-fluency
Tool mastery defined as the ability to predict the consequence of the current
action; its absence produces defensive waste (re-cloning, `_old` files,
hoard-branches) that looks like user error but is a tool/teaching failure.
Generalizes beyond Git. Vault: `ideas/12signsyoureusinggitwrong.md`,
`git/allthingsgit.md` → source note `teaching-git.md`.

### Codebase as city (investment geography)
Codebase health as geography governed by investment policy: neglected
districts, avoidance-accelerated decay, refactoring as roadwork, deliberate
urban planning vs. accidental ghettos. Vault: `ideas/softwareghetto.md` →
source note `software-urban-planning.md`.

### Documentation demand as friction signal
Documentation consumption is a proxy for product friction ("consulting the
manual is the first step towards a support request"); drive it down by fixing
the product. Candidate tension with the Consultant's Oath's README bar —
docs as capability floor vs. docs as symptom. Vault: `ideas/nodocs.md` →
source note `nodocs-documentation-as-failure.md`.

### Structure precedes practice
SRE mechanisms (toil caps, ability to say no, shared on-call) all bottom out
in organizational preconditions — funding model, management enforcement.
Practices cannot be adopted inside structures that cannot honor them; "likely
impossible in a project-funded organization." Vault:
`devopsdojo/sitereliabilityengineering.md` → source note
`site-reliability-engineering-devopsdojo.md`. Related one-liner: "change the
process → you must change the organization."

### Directed automation
Automation ROI depends on which systemic constraint it relieves, not on the
amount automated; undirected automation is where effort goes to die. Toil
(SRE) is one definition of "directed." Precondition: organizations that treat
employee time as free cannot evaluate automation ROI at all. Vault:
`praqma/talks/automationishard.md`, `praqma/talks/13thingsallcompaniesdowrong.md`.

### Consultant polarities / capability-building roles
External-expert failure modes as paired temptations (show-off/impostor,
become-the-team/disconnect, curling/laissez-faire, solve-their-problem/
ivory-tower); the product is client capability. Generalizes to platform
teams, staff engineers, enablement. Vault: talks + ideas → source note
`five-temptations-of-a-consultant.md`.

### The measurement problem of team performance
There is no SI unit of team performance; every metric is an indicator plus an
argued assumption; "outcome per time" fails because outcome (value) is
undefined. Goal → focus area → measurable metric → action as the honest
decomposition. Vault: `ideas/lifeofdev.md` → source note
`simulating-development-teams.md`; also `praqma/measuringdevops.md`,
`ideas/codenudging.md`.

### Simulation as organizational epistemics
Claims about practices (CI frequency, batch size, review blocking, ceremony
overhead) should be made plausible ("not prove — make plausible") via crude,
explicit-assumption simulations — a middle ground between anecdote and
impossible controlled experiments. Vault: `ideas/lifeofdev.md` → source note
`simulating-development-teams.md`.

### Existence-by-system
An organization's effective reality is what its automated systems can see:
not in version control → doesn't exist; not monitored → not in production;
not automated → not remembered. Vault: `oneliners.md` → source note
`oneliners.md`.

### Management traceability asymmetry
Organizations demand rigorous traceability from technical work while
management decisions have none visible from below; engineering discipline is
applied selectively, downward. Vault:
`praqma/talks/13thingsallcompaniesdowrong.md`.

## Open questions

- Does the alignment-trap result (effectiveness before alignment) replicate
  beyond the original 2007 study, and does it transfer from IT-spend
  effectiveness to agile transformations? (`praqma/talks/alignment-trap.md`)
- Is "adopting tests/CD/DevOps has not made average software more
  trustworthy" defensible empirically, or rhetorical?
  (`praqma/talks/thisstoneisbetterthanyoursoftware.md`)
- Do the 13 pathologies reduce to fewer root causes (invisible inventory,
  normalized dysfunction, asymmetric accountability)?
  (`praqma/talks/13thingsallcompaniesdowrong.md`)
- Does avoided code actually deteriorate faster (broken-windows for code) —
  and does the urban-planning metaphor import contested urban theory?
  (`ideas/softwareghetto.md`)
- State of DevOps 2019 reading notes claim big-bang transformations and
  Centers of Excellence don't work, and large enterprises (>5000) are lower
  performers — worth extracting as sourced claims? How does the CoE finding
  square with SAFe-style rollouts? (`praqma/devopsverticals/stateofdevops2019.md`)
- "What gets measured gets managed" vs. the abused-figures skepticism — file
  as a tension once both ends exist as framework notes. (`oneliners.md`,
  `praqma/talks/abusedfiguresofdevops.md`)
- Fast feedback vs. instant gratification: if instant gratification erodes
  the ability to work hard over time, what does that imply for fast-feedback
  engineering culture? (`RANDOM.md`)
- Is there a place in the framework for narrative carriers (comics, D&D,
  choose-your-own-adventure pipelines, Christmas calendars) as a
  *communication requirement* of systemic ideas, or is that content-pipeline
  territory? (`ideas/chooseyourowncd.md`, `ideas/dndcode.md`,
  `ideas/thetwelvedaysofcd.md`, `praqma/DevOpsComic.md`)
- Team-health questionnaire (`ideas/questionairefivedysfunctions.md`): are
  its items (voice, confidence in changes, trust in colleagues/software,
  "actions are taken") a usable operationalization of team health for the
  framework?
