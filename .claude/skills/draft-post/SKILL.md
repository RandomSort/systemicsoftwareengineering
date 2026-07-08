---
name: draft-post
description: Produce a blog post from framework notes via brief-first flow. Usage - /draft-post <concept-or-tension> [audience/angle hints]. Brief must be approved before drafting.
---

# Draft a blog post

The framework is the source of truth; the post is a projection of it. Two
stages, with a hard stop between them.

## Stage 1 — Brief

1. Resolve the argument to framework note(s) or a tension note. Read them and
   their `sources:`.
2. Create a brief in `content/briefs/` from `_template.md`: audience, the one
   thing, angle, in/out of scope, format notes. Where the user gave hints,
   honor them; where not, propose your best call and say why.
3. **Stop and present the brief for approval.** Do not draft until the user
   approves (they may edit the brief first — re-read it before Stage 2).

## Stage 2 — Draft

4. Read `content/VOICE.md` if present and imitate it; if absent, tell the
   user drafts will be generic until they seed it.
5. Write the draft to `content/drafts/`, frontmatter linking the brief and
   `projects:` notes. Rules:
   - Every substantive claim must trace to a framework note or source note —
     no new unsourced claims. If the post needs a claim the framework lacks,
     flag it as a gap instead of inventing it.
   - Open with the reader's problem, not the framework's vocabulary.
     Introduce framework terms only after earning them.
   - Mark the brief `status: drafted`.
6. Commit as `content: draft <title>` and remind the user: the edit pass is
   theirs, and weaknesses found while editing should go back to `inbox/` or
   `knowledge/tensions/`.
