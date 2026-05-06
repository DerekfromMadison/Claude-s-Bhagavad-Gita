# Claude's Bhagavad Gita

A unique, AI-authored synthesis rendition of the Bhagavad Gita, written
by Claude (an AI made by Anthropic), drawing extensively and verifiably
on the major human translations and commentaries on the Gita and
bringing them into dialogue with modern philosophy, ethics, psychology,
and science.

This is **not** a translation. It is **not** a summary. It is a new
work — declared as AI-authored on page one — that takes the plurality
of the Gita's interpretive traditions, names each lens honestly, quotes
each tradition in its own words with citation, and then chooses a path
forward for a present-day reader, with the reasoning shown.

## Status

Phase: **Plan complete.** Chapter drafting has not yet begun.

## How this repository is organized

```
.
├── plan/
│   ├── 00_PROJECT_INTENTION.md     The vision and scope of the project
│   ├── 01_GOALS_AND_PRINCIPLES.md  Goals, methodology, anti-hallucination protocol
│   ├── 02_CHAPTER_OUTLINE.md       Brief for each of the 18 chapters
│   ├── 03_SOURCES_AND_VIEWPOINTS.md Source corpus and interpretive schools
│   ├── 04_OUTPUT_STRUCTURE.md      Final book layout and chapter template
│   └── 05_SUBAGENT_BRIEF.md        Handoff brief for chapter-drafting agents
├── book/
│   ├── front_matter/               (To be drafted)
│   ├── chapters/                   (To be drafted, one file per chapter)
│   └── back_matter/                (To be drafted: bibliography, glossary, indices)
├── research/
│   ├── source_notes/               Per-chapter source-pull logs (validation artifact)
│   └── synthesis_notes/            Per-chapter reasoning behind chosen path forward
└── README.md                       This file
```

## Next step

A sub-agent picks up a single chapter, reads the plan documents in the
order specified in `plan/05_SUBAGENT_BRIEF.md`, executes the chapter
end-to-end against the template in `plan/04_OUTPUT_STRUCTURE.md`, and
produces:

- `book/chapters/<NN>_<slug>.md` — the chapter draft.
- `research/source_notes/ch<NN>.md` — the source-pull log.
- `research/synthesis_notes/ch<NN>.md` — the reasoning behind the
  chosen path forward.

Sub-agents work one chapter at a time. Cross-chapter consistency and
the front/back matter are produced in a final consolidation pass after
all 18 chapter drafts exist.

## What this project requires of every chapter

- ≥ 3 interpretive viewpoints engaged (target 5–7).
- ≥ 5 named translators or commentators quoted, with citation.
- ≥ 12 verbatim quoted passages, all sourced.
- ≥ 2 modern counterpoint voices from contemporary philosophy,
  ethics, or psychology.
- ≥ 1 modern science strand, citing named researchers and bounded
  findings.
- A synthesis section in Claude's voice that names which strands are
  woven forward and why.
- A modern-application section grounded in concrete present-day
  situations.

The full requirements are in `plan/01_GOALS_AND_PRINCIPLES.md`.

## Anti-hallucination commitment

Quotations and citations that cannot be verified against real published
sources do not appear. Paraphrase is permitted when labeled as such.
Every chapter passes a validation pass that re-checks every quote and
every locator before it is considered done. Details in
`plan/01_GOALS_AND_PRINCIPLES.md` and `plan/05_SUBAGENT_BRIEF.md`.

## On AI authorship

The book opens with a plain declaration that it was written by Claude
as an AI interpretation, drawing on named human translators and
commentators. There is no claim to revealed authority. There is no
pretense of human authorship. There is no pretense of being "the" Gita.
It is a present-day AI synthesis, declared as such, and inviting the
reader to follow the citations and form their own reading.
