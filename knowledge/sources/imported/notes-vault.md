---
title: Personal notes vault (RandomSort/notes)
type: experience
author: Johan Abildskov
year: 2017–2020
link: https://github.com/RandomSort/notes
feeds: []
added: 2026-07-08
---

# Personal notes vault (RandomSort/notes)

Overview source note for the private notes vault. The vault is mixed-content:
talk abstracts and theses, blog/product ideas, book notes, teaching material,
conference organizing notes, and private consulting-engagement notes. Only the
generalizable knowledge is imported here; client-engagement and personal
material is deliberately excluded (see "Excluded from import" below).

## What the vault contains (directory level)

- `ideas/` (32 files) — talk, blog, product, and tooling ideas. The densest
  knowledge layer: consultant ethics, documentation philosophy, code-as-city
  metaphors, team-health instruments, developer-behavior simulation.
- `praqma/talks/` — abstracts and skeletons for the author's own public
  conference talks (alignment trap, automation, DevOps figures, software
  quality, consultant temptations). Treated as first-class statements of the
  author's thinking.
- `git/`, `practical-git/` — notes on teaching Git (podcast prep, training
  design, a Git-internals demo script).
- `books/` — reading list plus one book note (*Our Iceberg Is Melting*).
- `devopsdojo/` — script for the author's own DevOpsDojo video series
  (episode 5: Site Reliability Engineering).
- `slidedecks/` — skeletons for decks (monorepos; a Danish talk on software
  process for non-engineers).
- `courses/`, `Manning/` — notes on courses taken/reviewed (Jira, creative
  writing, a Manning video course). Low framework relevance.
- `DevOpsDays/` — conference-organizing retrospective notes and a comedy
  standup script about DevOps culture.
- Top-level topic files — `oneliners.md` (collected aphorisms with
  attributions), `RANDOM.md` (fragments).
- Several directories and files of private consulting-engagement and personal
  material — excluded (below).

## Recurring themes

1. **Trust as the essence of software quality.** "I trust a rock to behave as
   expected; I cannot say the same for the average piece of software."
2. **Organizations repeat known-bad patterns.** Dysfunction gets normalized
   ("this is just how it is here"); the mistakes are neither unique nor
   unsolvable, yet recur everywhere.
3. **Skepticism about measurement and figures.** Charts and metrics used to
   mandate decisions rather than inform them; the search for the "SI unit of
   team performance"; behavioral nudging from repo data.
4. **Automation as hard engineering, not silver bullet.** Effort routinely
   spent on automation with low return; mindset over tooling.
5. **Teaching and learning tools.** Git pedagogy recurs constantly: fluency as
   safety, "we are not our own target audience", a training event is not
   knowledge.
6. **Consulting ethics.** Leave no legacy behind, don't be a white knight,
   build capability instead of solving the customer's problem for them.
7. **Explaining systems through story and metaphor.** Urban planning for
   codebases, choose-your-own-adventure pipelines, D&D parties, Christmas
   calendars, comics — a persistent instinct that systemic ideas need
   narrative carriers.
8. **The urge to test claims empirically.** Simulating developer teams to make
   CI/CD claims plausible instead of asserting them.

## Inventory of framework-relevant files

Vault paths are relative to the repo root of https://github.com/RandomSort/notes.
Items with a dedicated source note link into `notes/`.

| Vault path | One-line summary | Source note |
|---|---|---|
| `praqma/talks/13thingsallcompaniesdowrong.md` | Catalog of recurring organizational pathologies companies repeat "against common sense" | [notes/thirteen-things-all-companies-do-wrong.md](notes/thirteen-things-all-companies-do-wrong.md) |
| `praqma/talks/abusedfiguresofdevops.md` | Agile/DevOps visualizations misused to mandate decisions instead of inform them | [notes/abused-figures-of-devops.md](notes/abused-figures-of-devops.md) |
| `praqma/talks/alignment-trap.md` | Why agile transformations fail: intuition about alignment is wrong | [notes/alignment-trap.md](notes/alignment-trap.md) |
| `praqma/talks/automationishard.md` | Automation efforts routinely yield low ROI; strategy and mindset over tools | [notes/automation-is-hard.md](notes/automation-is-hard.md) |
| `praqma/talks/thisstoneisbetterthanyoursoftware.md` | Software quality reframed as warranted trust, benchmarked against a rock | [notes/this-stone-is-better-than-your-software.md](notes/this-stone-is-better-than-your-software.md) |
| `praqma/talks/the-five-temptations-of-a-consultant.md`, `ideas/thefivetemptationsofaconsultant.md` | Consultant failure modes as paired temptations/polarities | [notes/five-temptations-of-a-consultant.md](notes/five-temptations-of-a-consultant.md) |
| `ideas/howtoavoidlegacycode.md`, `ideas/blogposts.md` (Consultants Oath sections) | Leave no legacy code behind: treat everything as open source, leave a pipeline | folded into [notes/five-temptations-of-a-consultant.md](notes/five-temptations-of-a-consultant.md) |
| `ideas/softwareghetto.md` | Urban planning as a systemic metaphor for codebase health and maintenance | [notes/software-urban-planning.md](notes/software-urban-planning.md) |
| `ideas/nodocs.md` | Documentation need as a failure signal; principles for user-centered tooling | [notes/nodocs-documentation-as-failure.md](notes/nodocs-documentation-as-failure.md) |
| `ideas/lifeofdev.md` | Simulating developer teams to make claims about CI/CD practices testable | [notes/simulating-development-teams.md](notes/simulating-development-teams.md) |
| `git/allthingsgit.md`, `git/buildinganarmyofgitninjas.md`, `ideas/12signsyoureusinggitwrong.md`, `ideas/explaingit.md`, `ideas/opinionatedgit.md` | Git pedagogy: fluency as safety, opinionated defaults, teaching by story | [notes/teaching-git.md](notes/teaching-git.md) |
| `devopsdojo/sitereliabilityengineering.md` | SRE as functioning DevOps org structure: toil budgets, shared ownership, the ability to say no | [notes/site-reliability-engineering-devopsdojo.md](notes/site-reliability-engineering-devopsdojo.md) |
| `oneliners.md` | Collected aphorisms: compressed heuristics about software organizations | [notes/oneliners.md](notes/oneliners.md) |
| `praqma/talks/practicalCDin30minutesorless.md` | Talk: a complete CD pipeline from scratch with open tools is a 30-minute job | — |
| `ideas/benefitsofplatformdevelopment.md` | Why platform development: fix bugs once, lead time, domain experts need only domain knowledge | — |
| `ideas/codenudging.md` | Behavioral feedback to developers from commit data ("your branches live too long") | — |
| `ideas/questionairefivedysfunctions.md` | Belbin-style questionnaire to gauge team health (voice, confidence, trust in software) | — |
| `ideas/consultantfeedback.md` | Recurring customer-feedback instrument for consultants | — |
| `ideas/devopslympics.md` | CTF-style DevOps competition as learning/teambuilding format | — |
| `ideas/chooseyourowncd.md`, `ideas/dndcode.md`, `ideas/thetwelvedaysofcd.md` | Narrative formats for CD education (adventure, D&D, Christmas calendar) | — |
| `ideas/blogposts.md` | Blog idea backlog: wolf/giraffe language for consultants, Orwell's rules for CD, meetings hygiene, teaching Git | — |
| `ideas/gitlint.md`, `ideas/repoanalyser.md` | Tooling ideas: lint/scan repositories for bad practices and metrics | — |
| `ideas/taskdag.md` | Dependency-graph view of tasks so breakage consequences are visible system-wide | — |
| `slidedecks/monorepo.md` | Deck skeleton: "repositories for the rest of us" — monorepo pragmatics for normal orgs | — |
| `slidedecks/kv2017.md` | Danish talk: explaining modern software process (agile, technical debt, craft respect) to non-engineers | — |
| `books/our-iceberg-is-melting.md` | Book note: change management via fable; reduce complacency, increase urgency | — |
| `books/README.md` | Reading list (Mythical Man Month, Cathedral & Bazaar, Five Dysfunctions, Leading Change) | — |
| `praqma/measuringdevops.md` | Sketch of DevOps dashboards/alerts: provisioning lead time, platform adoption, autonomous releases | — |
| `praqma/devopsverticals/stateofdevops2019.md` | Reading notes on State of DevOps 2019: big-bang transformations and Centers of Excellence don't work | — |
| `praqma/notesonremotetraining.md` | General lessons on running full-day remote technical training well | — |
| `praqma/devooopsspeakerguide.md` | Speaker guide for a failure-stories meetup: how to tell an incident story | — |
| `praqma/cc2gitcaveats.md` | VCS-migration caveats: deliver all the time, do not reuse branches | — |
| `praqma/DevOpsComic.md` | Satirical comics on DevOps-in-name-only ("you are our Jira admin now") | — |
| `praqma/delegate.md` | Training outline: DevOps three ways; culture, tools, skills as foundations | — |
| `DevOpsDays/standup.md` | Comedy standup script — culture critique via jokes ("done" vs "done-done") | — |
| `DevOpsDays/DevOpsDaysCPH.md` | Conference-organizing retrospective (open spaces, ignite formats) | — |
| `practical-git/internals.sh` | Live-demo script for teaching Git internals | — |
| `RANDOM.md` | Fragments: fast feedback vs instant gratification; agile roguelike | — |

## Excluded from import (privacy)

Excluded wholesale, per privacy rules for this public repository: all
consulting-engagement directories and files (several directories named after
client companies, plus engagement notes inside `praqma/` and `notes/`),
internal-company material (retrospectives, 1:1 notes, feedback to named
colleagues, role pitches, meeting minutes), and personal material (wishlist,
party planning). Where an engagement note contained a genuinely general
lesson, it was extracted fully generalized; no client names, engagement
details, or private individuals' names appear in the imported notes.

## Quotable

- "I know karate, I took a class two years ago." — on training events as
  proxies for knowledge (`praqma/talks/13thingsallcompaniesdowrong.md`)
- "Consulting the manual is the first step towards making a support request."
  (`ideas/nodocs.md`)
