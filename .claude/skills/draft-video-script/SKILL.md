---
name: draft-video-script
description: Produce a video script (hook, spoken narration, visual cues, title/description options) from framework notes. Usage - /draft-video-script <concept-or-tension> [duration/audience hints]. Brief must be approved before drafting.
---

# Draft a video script

Same brief-first flow as /draft-post — read that skill's rules; everything
about traceability, voice, and the approval stop applies. Video-specific
differences:

## Brief additions
Target duration, platform (YouTube long-form? short?), hook concept, and the
visual opportunities the concept offers (diagrams of the system, before/after,
concrete scenario to dramatize).

## Script format
Write to `content/drafts/` as a two-column-style script:

```
## Section name (~M:SS)
NARRATION: spoken prose — write for the ear: short sentences, no
  parentheticals, numbers rounded, terms explained on first use.
VISUAL: what is on screen — talking head, diagram (describe it), screen text,
  b-roll suggestion.
```

Required sections: cold-open hook (first 20 seconds earns the rest), the
problem, the idea, a concrete worked example, boundaries ("when this doesn't
apply" — the framework tracks its tensions; use them, it builds trust), and a
close with one memorable restatement of the one thing.

## Deliverables
Script, plus 3 title options, a 2–3 sentence description, and a thumbnail
concept. Commit as `content: video script <title>`.
