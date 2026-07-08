---
title: "Getting Old(er)"
type: post
author: Johan Abildskov
year: 2018
link: https://abildskov.io/hashtag-getting-old/ (source: /workspace/abildskov.io/content/posts/2015-05-01-hello-world/index.md)
feeds: []
added: 2026-07-08
---

# Getting Old(er)

## Core argument

A confession-shaped argument about proportionality: the author ran a rented
VPC plus a Kubernetes cluster on Hetzner VMs to serve three WordPress sites
and two static sites, recognized the setup as some mix of over-engineering,
gold-plating, and yak shaving, and replaced it with S3. The generalizable
insight is the distinction between **tool discovery** and **solving the task
at hand** — and that even while writing this very post, the author caught
himself picking a new static site generator (Gatsby) because he'd been reading
about React, not because the task demanded it.

## Extracted claims

- **[empirical]** (self-observed) Engineers systematically conflate tool
  discovery with task-solving: "I should learn to distinguish between tool
  discovery and solving a task at hand. I'm trying to get better, but I still
  managed to use a new static site generation tool for setting up this site."
- **[normative]** Infrastructure should be proportional to the services it
  carries; a Kubernetes cluster for five small sites is "stupid" regardless of
  which named failure mode (over-engineering, gold-plating, yak shaving) it
  falls under.
- **[empirical]** (weak, anecdotal) Moving to a managed/high-abstraction
  target (static publishing to S3) removed the maintenance burden without
  loss: "Publishing static sites to S3, is my new favorite thing, it is just
  so easy."

## Agreements and disagreements

- Lived example of DOPIER's "rightsourcing" principle applied to oneself —
  feeds the same candidate concept from the practitioner side rather than the
  advisory side.
- Tension worth keeping: tool discovery is also how practitioners build the
  judgment the framework depends on. The post treats it purely as a failure
  mode; a systemic framework probably needs to say when exploration is the
  *right* mode (slack, deliberate practice) versus contamination of delivery
  work.

## Quotable

- "I should learn to distinguish between tool discovery and solving a task at
  hand."
- "I don't know if this is over-engineering, gold-plating or Yak shaving, but
  the right answer is probably at least two of the aforementioned."
