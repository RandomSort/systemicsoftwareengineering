# Systemic Software Engineering

Systemic Software Engineering is a framework condensing a mental model of how
software engineering — and by extension, how organized human work — functions.
It is primarily a thinking tool: writing it down forces crystallization. If it
is useful to others, that is a welcome side effect.

The framework is a *condensation* of a much larger corpus of knowledge,
experience, and thinking. This repository therefore holds two layers:

1. **The framework** (`framework/`) — the condensed, opinionated core: concepts,
   their relations, and the claims they rest on.
2. **The knowledge base** (`knowledge/`) — the supporting corpus: source notes,
   identified tensions and contradictions, and open questions that drive
   further thinking.

On top of these sits a **content pipeline** (`content/`) for deriving blog
posts, talks, and videos from the framework, and an **agentic toolchain**
(`.claude/`) for enriching, clarifying, fact-checking, and stress-testing the
knowledge with AI agents.

## Repository map

| Path | Purpose |
|---|---|
| `framework/` | The condensed framework: one note per concept |
| `knowledge/sources/` | Literature/source notes feeding the framework |
| `knowledge/tensions/` | Contradictions and unresolved tensions, tracked explicitly |
| `knowledge/questions.md` | Running list of open questions |
| `inbox/` | Raw captures — thoughts, links, fragments awaiting processing |
| `content/` | Briefs, drafts, and published derivatives (posts, scripts) |
| `docs/WORKFLOWS.md` | How to work: the improvement loop and the content pipeline |
| `.claude/agents/` | Agent role definitions (fact-checker, critic, …) |
| `.claude/skills/` | Slash commands orchestrating the agents |

## How to work with this repository

Read [`docs/WORKFLOWS.md`](docs/WORKFLOWS.md). The short version:

- Capture raw thinking into `inbox/`, then run `/process-inbox`.
- Improve the framework with `/enrich`, `/clarify`, `/fact-check`,
  `/find-tensions`, and `/review-framework`.
- Produce content with `/draft-post` and `/draft-video-script`.

Agents propose; the author disposes. Nothing in `framework/` changes meaning
without deliberate human judgment — agents surface evidence, tensions, and
drafts, but the framework remains one person's crystallized thinking.

## License

[CC BY-SA 4.0](LICENSE)
