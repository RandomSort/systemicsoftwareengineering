---
title: "Use 2019 to make your infrastructure DOPIER"
type: post
author: Johan Abildskov
year: 2019
link: https://abildskov.io/DOPIER-infrastructure/ (source: /workspace/abildskov.io/content/posts/2019-01-03-DOPIER-infrastructure/index.md)
feeds: []
added: 2026-07-08
---

# Use 2019 to make your infrastructure DOPIER

## Core argument

Infrastructure quality is not a tooling question but a set of systemic
properties. The DOPIER acronym names six: **Deliberate** (every element exists
because it was asked for, with a known rationale), **Operable** (the team can
actually do operations work at a level of abstraction it can afford —
"rightsourced"), **Plastic** (easy to change in sane ways, hard to break),
**Immutable** (the atomic units composing the plastic whole are uniquely
versioned and traceable), **Existing** (in version control and monitored —
otherwise it effectively doesn't exist), and **Reproduceable** (no one-offs;
provisioning is automated and scripted). Improvement starts with honest
enumeration of what you actually run.

## Extracted claims

- **[normative]** "Our infrastructure should be as it is, because we asked for
  it to be" — ad-hoc/arbitrary infrastructure is broken; uncertainty cannot be
  handled by ignoring it. (§Deliberate)
- **[normative]** "There is no one true level of abstraction. What matters is
  that the infrastructure capabilities are rightsourced so you can spend your
  effort on what provides value to your customers." (§Operable)
- **[empirical]** The low barrier to acquiring machines makes teams forget
  that operations work only *begins* at provisioning, and teams often lack the
  skill set to operate what they order. (§Operable)
- **[normative]** Infrastructure that is hard to change once deployed is an
  anti-pattern; the goal is "easy to change in sane ways but difficult to
  break." (§Plastic)
- **[definitional]** Plasticity and immutability operate at different levels:
  "Compose your plastic infrastructure from immutable atomic units!" — the
  whole adapts, the parts are versioned and traceable. (§Immutable)
- **[normative]** "If it is not under version control, it does not exist" —
  extended from source code to all infrastructure. (§Existing)
- **[normative]** "If it is not monitored, it is not in production." (§Existing)
- **[empirical]** "The same way tests capture knowledge about your software
  your monitoring configurations captures knowledge about your IT landscape."
  (§Existing)
- **[empirical]** Reproducible pre-production environments are key to the
  delivery process, and their value "is hard to fathom before having lived
  it." (§Reproduceable)
- **[normative]** The improvement method: "start figuring out the world and
  being painfully honest" — enumerate the services you run but don't really
  operate; the next steps will show themselves. (§Making your infrastructure
  DOPIER)

## Agreements and disagreements

- Strong proto-material for a systemic framework: the piece consistently
  describes *properties of the system* (deliberateness, plasticity,
  observability) rather than tools, and explicitly handles an apparent
  contradiction (plastic vs immutable) by separating system levels — a
  systemic move worth naming as a general pattern.
- "Rightsourcing" anticipates platform-engineering / cognitive-load arguments
  (Team Topologies, 2019) — potential convergent evidence, potential tension
  over whether the team or the organization chooses the abstraction level.
- Possible tension to watch: "deliberate" (everything has an asked-for
  rationale) can conflict with "plastic" (cheap change invites undeliberate
  drift). The post doesn't address who re-validates the rationale after change.

## Quotable

- "Compose your plastic infrastructure from immutable atomic units!"
- "If it is not under version control, it does not exist."
- "If it is not monitored, it is not in production."
- "There is no one true level of abstraction."
- "We can't handle our uncertainty by ignoring it."
