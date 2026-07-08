---
title: "abildskov.io blog and talks corpus (2017–2019)"
type: post collection
author: Johan Abildskov
year: 2017–2019
link: https://abildskov.io (Hugo/Gatsby source at /workspace/abildskov.io; predecessor Jekyll blog at /workspace/randomsort.github.io)
feeds: []
added: 2026-07-08
---

# abildskov.io blog and talks corpus (2017–2019)

Corpus overview note. The author's own published writing and speaking record
from 2017–2019: two substantive blog posts, one stub post from the predecessor
Jekyll blog, and sixteen talk/appearance pages. The talk pages are inventory
records (title, event, link) rather than full abstracts — the titles and
delivery pattern carry the signal, not the page bodies.

## Themes across the corpus

1. **Infrastructure as a designed system, not an accident.** The DOPIER post
   argues infrastructure should be *deliberate* ("as it is, because we asked
   for it to be"), operable at the right level of abstraction, changeable as a
   whole but immutable in its parts, captured in version control, observed in
   production, and reproducible. This is proto–systemic thinking: properties of
   the whole system, not tool advocacy.
2. **Rightsourcing and levels of abstraction.** Recurring stance that there is
   "no one true level of abstraction" — teams should own exactly the layers
   where they add value and outsource the rest. Appears in DOPIER and is lived
   out in "Getting Old(er)" (killing a personal Kubernetes cluster for S3).
3. **Git as the gateway to engineering competence.** Half the talk record is
   Git: teaching it, demystifying it ("Jedi Mindtricks"), democratizing it
   ("for the rest of us", "I'm just a developer, why should I learn Git?"),
   and scaling it. The underlying claim: mastering the version control model
   changes how developers relate to their whole system of work.
4. **DevOps beyond hype.** Two 2019 talks titled "DevOps beyond the Buzzword"
   and one on "Used and abused figures of DevOps" — a skeptical, evidence-minded
   stance toward the movement the author is simultaneously an organizer in
   (Aarhus DevOps meetup, DevOpsDays CPH, CoDe-Conf hosting).
5. **Learning from production/manufacturing.** The lost Jekyll post "Extreme
   Lean in Sweden" points at Poppendieck-style Lean ("Lean Software
   Development: An Agile Toolkit") — software learning from real production.
6. **Self-aware practitioner honesty.** "Getting Old(er)" names the failure
   mode of confusing tool discovery with solving the task at hand; DOPIER's
   improvement method starts with "figuring out the world and being painfully
   honest."

## Inventory

### Blog posts

| Piece | Year | One-line summary | Path |
|---|---|---|---|
| Use 2019 to make your infrastructure DOPIER | 2019 | Six principles (Deliberate, Operable, Plastic, Immutable, Existing, Reproduceable) for sane infrastructure design; the corpus's most substantive piece | `/workspace/abildskov.io/content/posts/2019-01-03-DOPIER-infrastructure/index.md` |
| Getting Old(er) | 2018 | Retires a personal VPS + Kubernetes zoo for S3; names the tool-discovery-vs-task-at-hand failure mode | `/workspace/abildskov.io/content/posts/2015-05-01-hello-world/index.md` (dir name misleading; front-matter date 2018-12-10) |
| Extreme Lean in Sweden | 2017 | Stub only — heading references Poppendiecks' *Lean Software Development: An Agile Toolkit*; body was never committed or was lost | `/workspace/randomsort.github.io/_posts/2017-02-23-extreme-swedish-lean.markdown` |

### Talks and appearances

| Talk | Event, year | One-line summary | Path |
|---|---|---|---|
| Git Jedi Mindtricks | Git Merge 2017 | Advanced Git techniques demystified for a community audience (video: youtube M75aENmuzmo) | `/workspace/abildskov.io/content/talks/git-merge-2017.md` |
| I'm just a developer, why should I learn Git? | Embedded Seminar Jutland 2017 | Case for Git fluency to developers who see it as someone else's job | `/workspace/abildskov.io/content/talks/embedded-day-jut-2017.md` |
| I'm just a developer, why should I learn Git? | Embedded Day Oslo 2017 | Second delivery of the above to embedded practitioners | `/workspace/abildskov.io/content/talks/embedded-day-osl-2017.md` |
| Jedi Mind Tricks in Git | Aarhus DevOps Meetup 2017 | Local-meetup delivery of the Git demystification material | `/workspace/abildskov.io/content/talks/aarhus-devops-june-2017.md` |
| Hosting CoDe-Conf | CoDe-Conf 2017 | Conference host/organizer role (Continuous Delivery community) | `/workspace/abildskov.io/content/talks/code-conf-2017.md` |
| A Simulated Git Workflow | Git Merge 2018 | Simulating/teaching Git workflows rather than prescribing them | `/workspace/abildskov.io/content/talks/git-merge-2018.md` |
| Teaching Git (podcast) | All Things Git 2018 | Interview on how to teach Git — pedagogy of developer tooling | `/workspace/abildskov.io/content/talks/allthingsgit.md` |
| The DevOpsDays Song | DevOpsDays Copenhagen 2018 | Community/culture performance piece (video: youtube YPUKLfcuq9Y) | `/workspace/abildskov.io/content/talks/devopsdays-cph-2018.md` |
| Git Repositories for the rest of us | Aarhus DevOps Meetup 2018 | Repository practices democratized beyond experts | `/workspace/abildskov.io/content/talks/aarhus-devops-august-2018.md` |
| Hosting CoDe-Conf | CoDe-Conf 2018 | Conference host/organizer role, second year | `/workspace/abildskov.io/content/talks/code-conf-2018.md` |
| 25 things all companies do wrong | Aarhus DevOps Meetup 2018 | Catalogue of recurring organizational failure patterns | `/workspace/abildskov.io/content/talks/aarhus-devops-november-2019.md` (file name says 2019; front-matter date 2018-11-29) |
| DevOps: Beyond the Buzzword | Computerworld DevOps Seminar 2019 | What DevOps substantively is once hype is stripped away | `/workspace/abildskov.io/content/talks/computerworld-2019.md` |
| The why, what and how of scaling Git repositories | Git Merge 2019 | Scaling repositories as a sociotechnical problem: motivation, options, execution (video: youtu.be/J_RekbDzWrE) | `/workspace/abildskov.io/content/talks/git-merge-2019.md` |
| DevOps beyond the Buzzword | DevOps For Web Aarhus 2019 | Second delivery of the beyond-the-buzzword material | `/workspace/abildskov.io/content/talks/devops-for-web-aarhus.md` |
| Used and abused figures of DevOps | DevOpsDays Zurich 2019 | Critique of how DevOps metrics/figures get misused | `/workspace/abildskov.io/content/talks/devopsdays-zurich-2019.md` |
| Hosting DevOpsDays CPH | DevOpsDays Copenhagen 2019 | Conference host/organizer role | `/workspace/abildskov.io/content/talks/devopsdays-cph-2019.md` |

## Individual source notes

Deep notes for the pieces most relevant to the framework live in
`knowledge/sources/imported/blog/`:

- `dopier-infrastructure.md`
- `getting-older.md`
- `extreme-swedish-lean.md`
- `devops-beyond-the-buzzword.md`
- `used-and-abused-figures-of-devops.md`
- `25-things-all-companies-do-wrong.md`
- `scaling-git-repositories.md`
- `teaching-git.md`

## Caveats

- The talk pages contain no abstracts; individual talk notes flag which claims
  are inferred from title + delivery context rather than extracted from text.
- The corpus predates the framework by 7+ years. Treat it as evidence of the
  author's long-running themes, not as current positions.
