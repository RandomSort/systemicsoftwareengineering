---
name: review-framework
description: Holistic periodic audit of the framework - coverage gaps, staleness, orphans, tension backlog, coherence, content-ready candidates. Produces a report in docs/reviews/.
---

# Review the framework

A monthly-ish audit. Output is a report the author works through, not changes
to the framework itself.

1. **Inventory** (do inline, no agents needed): every `framework/` note with
   status, confidence, last-reviewed, source count, tension count; orphans
   (no `related:` in either direction); `knowledge/tensions/` by state and
   age; `knowledge/questions.md` backlog size.
2. **Coherence + critique**: spawn the **critic** agent
   (subagent_type: critic) over the framework as a whole — does it hang
   together as a system? What is the lens hiding?
3. **Staleness**: notes not reviewed in >90 days; published content in
   `content/published/` whose `projects:` notes changed since publication
   (compare git history).
4. Write the report to `docs/reviews/YYYY-MM-review.md` with sections:
   - Health dashboard (the inventory, as a table)
   - Tension digest — open tensions ordered by blast radius, each with a
     one-paragraph brief so the author can pick one to resolve
   - Critic's top objections
   - Stale content alerts
   - **Recommended next actions** — max 5, concrete (e.g. "resolve tension X",
     "/fact-check note Y", "note Z is content-ready")
5. Append content-ready candidates to `content/ideas.md`: notes at `stable`
   with tensions resolved/accepted, plus any open tension interesting enough
   to think through in public.
6. Commit as `docs: framework review YYYY-MM` and give the user the report's
   recommended actions inline.
