# Inbox: blog/talks corpus import (2026-07-08)

Captured from digesting the author's own published writing 2017–2019.
Corpus overview: `knowledge/sources/imported/blog-abildskov-io.md`.
Deep notes: `knowledge/sources/imported/blog/*.md`.
For /process-inbox routing.

---

## Candidate framework concepts

1. **Rightsourcing / no one true level of abstraction** — teams should own
   exactly the layers where they add customer value and deliberately source
   out the rest; the correct abstraction level is contingent, not universal.
   Source: `knowledge/sources/imported/blog/dopier-infrastructure.md`
   (§Operable), lived example in `blog/getting-older.md`. Anticipates
   platform-engineering / cognitive-load arguments — enrich against Team
   Topologies. Strong seed candidate.

2. **Plastic wholes from immutable parts** — systems should be easy to change
   at the composition level while their atomic units stay versioned,
   traceable, unchangeable. Resolving an apparent contradiction by separating
   system levels is itself a reusable systemic move worth naming.
   Source: `blog/dopier-infrastructure.md` (§Plastic, §Immutable). Seed
   candidate; likely generalizes far beyond infrastructure (teams? APIs?
   framework notes?).

3. **Systemic existence = captured + observed** — "If it is not under version
   control, it does not exist; if it is not monitored, it is not in
   production." An artifact participates in the engineering system only when
   its definition is versioned and its behavior is observed; monitoring
   configuration is knowledge capture, like tests.
   Source: `blog/dopier-infrastructure.md` (§Existing). Seed candidate.

4. **Tool discovery vs the task at hand** — a distinct engineer failure mode:
   satisfying curiosity/novelty inside delivery work while believing one is
   solving the task. Needs a boundary: when is exploration the right mode
   (slack, deliberate practice) vs contamination?
   Source: `blog/getting-older.md`. Seed candidate + built-in open question.

5. **Convergent organizational failure** — independent companies exhibit the
   same recurring dysfunctions ("25 things ALL companies do wrong"), implying
   causes in shared structures/incentives rather than local incompetence. A
   framework must explain the convergence, not just list the failures.
   Source: `blog/25-things-all-companies-do-wrong.md`. Seed candidate —
   blocked on recovering the actual list from the author.

6. **Figures used and abused** — measurement claims detach from their studies
   and become rhetoric; practitioners owe provenance and limits when citing
   numbers (Goodhart-adjacent, DORA cargo-culting).
   Source: `blog/used-and-abused-figures-of-devops.md`. Seed candidate;
   dovetails with this repo's own fact-checking rules.

7. **Mental models as the unit of tool competence** — ritual operation vs
   model-based understanding; workflows should be simulated/understood before
   adopted. Source: `blog/teaching-git.md`. Seed candidate.

8. **Why-before-how ordering** — recurring corpus stance (Deliberate, "why,
   what and how", beyond-the-buzzword): interventions require an articulated
   forcing problem first. Possibly a principle rather than a concept.
   Sources: `blog/dopier-infrastructure.md`, `blog/scaling-git-repositories.md`,
   `blog/devops-beyond-the-buzzword.md`.

## Open questions

- Where is the line between rightsourced abstraction (healthy ignorance of a
  layer) and ritual ignorance (unhealthy operation-without-model)? Concepts 1
  and 7 pull in opposite directions. Candidate tension note once both concepts
  exist. (`blog/teaching-git.md` §Agreements)
- Does "deliberate" survive "plastic"? If change is cheap, who re-validates
  the asked-for rationale after each change? (`blog/dopier-infrastructure.md`)
- What were the actual 25 things? Elicit from author / old slides — the list
  is the payload. (`blog/25-things-all-companies-do-wrong.md`)
- Which DevOps figures were the abused ones in 2019, and has 2019–2026
  evidence (DORA, SPACE, developer-productivity discourse) changed the list?
  (`blog/used-and-abused-figures-of-devops.md`)
- What was the penny that dropped in "Extreme Lean in Sweden"? Body is lost;
  only the author can recover it. (`blog/extreme-swedish-lean.md`)
- What was the 2019 "beyond the buzzword" definition of DevOps, and does the
  framework now supersede it? (`blog/devops-beyond-the-buzzword.md`)
- Verification task: watch the Git Merge 2019 recording
  (youtu.be/J_RekbDzWrE) before citing `blog/scaling-git-repositories.md`
  claims as evidence.

## Reprojection candidates (content ideas — already-published material to refresh through the pipeline)

- **DOPIER, seven years on** — revisit the six principles in the platform
  engineering / IaC-mature / AI-ops era: which held, which the framework now
  states better. From `blog/dopier-infrastructure.md`. Strongest candidate:
  the original is a real published post with a sticky acronym.
- **Tool discovery vs the task at hand** — extract the buried insight of
  "Getting Old(er)" into a standalone essay; the 2026 version writes itself
  (swap Gatsby-because-React for framework-because-LLM). From
  `blog/getting-older.md`.
- **Extreme Lean in Sweden, recovered** — the post that never shipped; rewrite
  from memory as "what software actually learned from manufacturing", with the
  framework's systemic vocabulary. From `blog/extreme-swedish-lean.md`.
- **Used and abused figures, 2026 edition** — same critique, current targets
  (DORA percentile abuse, developer-productivity metrics, AI-coding stats).
  From `blog/used-and-abused-figures-of-devops.md`.
- **25 things all companies do wrong → N mechanisms behind them** — reproject
  the listicle as a systemic explanation of why the failures converge; strong
  series/video potential. From `blog/25-things-all-companies-do-wrong.md`.
- **"I'm just a developer, why should I learn X?"** — generalize the 2017 Git
  talk's framing to today's X (CI internals, infra, LLM tooling); the
  objection-first title format is reusable. From `blog/teaching-git.md`.
- **Repository structure is org structure** — reproject the Git Merge 2019
  scaling talk as a Conway-for-repositories post once the recording is
  reviewed. From `blog/scaling-git-repositories.md`.
