---
title: Teaching Git — fluency, fear, and opinionated defaults
type: experience
author: Johan Abildskov
year: 2017–2019
link: https://github.com/RandomSort/notes (git/allthingsgit.md, git/buildinganarmyofgitninjas.md, ideas/12signsyoureusinggitwrong.md, ideas/explaingit.md, ideas/opinionatedgit.md, ideas/blogposts.md)
feeds: []
added: 2026-07-08
---

# Teaching Git — fluency, fear, and opinionated defaults

## Core argument

A cluster of notes from years of teaching Git (trainings, the git-katas, an
"All Things Git" podcast appearance, talk "Building an Army of Git Ninjas").
The through-line: Git is where the industry's relationship to its tools is
most visible. Git has "effectively world domination," yet most users operate
it by ritual and fear. The real diagnostic of using Git wrong is not any
particular command — it is "you are not sure what the consequence of the
current action is" and "it feels like magic." Teaching tools is therefore
teaching a mental model (CLI + whiteboard, telling a story), and since Git
itself refuses to have an opinion ("there is not a 'right way' to do it in
Git"), someone has to supply one.

## Extracted claims

- Empirical (the "13 signs you're using Git wrong" list — each an observable
  fear-symptom): deleting and re-cloning; multiple local copies of the same
  repo; a file called `Header_old.js` in the repo; many branches "just in
  case"; it feels like magic; not knowing the consequence of the current
  action.
- Definitional: tool mastery = ability to predict consequences of actions;
  its absence shows as hoarding behaviors (copies, stale branches, _old
  files) — version control re-implemented on top of version control.
- Empirical/pedagogical: "we are not our own target audience" — tool experts
  systematically mis-design training and clients for actual users ("you are
  not a GUI developer").
- Normative: don't build more Git clients; give people tools to enforce
  *their workflow* (workflow > client).
- Normative: because there is no global "this is how you should use Git," an
  opinionated position (e.g. "rebase is better than merging"; CLI plus
  diff/mergetool, no extra tools) is a service to learners, not arrogance —
  the Opinionated Git project premise.
- Pedagogical: teach by structure and story ("structure your material,"
  "telling a story"); learning by teaching works; survey what learners found
  hard *before and after* to locate the real difficulty.
- Connects to the training-event fallacy (see thirteen-things note): "we know
  Git, we had a training two years ago."

## Agreements and disagreements

Generalizes cleanly from Git to any infrastructure tool: the framework
concept hiding here is *consequence-fluency* — safety to act comes from
predictable mental models, and its absence produces defensive waste that
looks like user stupidity but is actually tool/teaching failure. Tension
with "abused figures": opinionated simplifications are teaching gold and
mandate-abuse fuel at the same time.

## Quotable

- "We are not our own target audience."
- "It feels like magic" — as a bug report about the user's mental model, not
  praise.
