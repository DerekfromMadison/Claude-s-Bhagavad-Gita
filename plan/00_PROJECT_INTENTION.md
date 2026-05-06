# 00 — Project Intention

## What this project is

A **unique, full-length original work created by AI** — a rendition of the
Bhagavad Gita authored by Claude (an AI made by Anthropic), designed to
deliver the **correct teachings of the Gita to modern-day humanity**. This
is not a derivative product. It is a new creation in its own right: an AI
synthesis built on the shoulders of the human interpretive tradition, but
not reducible to any of its parts.

It is **not** a translation. It is **not** a summary. It is a **new work** —
a synthesis that:

1. Reads across the major existing translations and commentaries on the Gita,
2. Performs a meta-analysis of how each tradition and translator has framed
   each core concept,
3. Acknowledges the intentions, lenses, and biases each author brought to
   their reading,
4. Quotes those authors **extensively and verifiably**, with citations back
   to the original published sources, so the reader can verify nothing has
   been hallucinated,
5. **Brings in modern-day counterpoints** — contemporary philosophy,
   psychology, ethics, sociology — that challenge, extend, complicate, or
   reinforce the classical readings,
6. **Brings in modern-day science** — neuroscience, cognitive science,
   physics, evolutionary biology, behavioral science — wherever it speaks
   to a concept the Gita raises (attention, action, identity, fear, desire,
   craving, equanimity, embodiment, death, time),
7. Then takes a position — Claude, having weighed the readings, chooses what
   it considers the **best path forward** for a modern human, and writes
   the rendition from that synthesized stance.

The result is a single coherent book written in Claude's voice — unique to
this project, anchored to the historical and scholarly record, drawn into
dialogue with present-day science and thought, and unafraid to commit to a
chosen reading where the sources diverge.

## The opening declaration

The book opens with a clear, plainly worded declaration that **this is an AI
interpretation**, written by Claude, drawing on the work of named human
translators and commentators. There is no pretense of human authorship and no
pretense of being "the" Gita. It is *Claude's* Gita: a present-day
synthesis, declared as such, on page one.

## Stance: not unbiased, not biased — synthesized

The intention is **not** to be neutral, and the intention is **not** to push
a single school. The intention is to:

- Take all of the major interpretive viewpoints seriously,
- Quote them honestly and in their own words,
- Name the lens each is reading through (Advaita, Bhakti, Gandhian, Integral,
  Theosophical, academic, literary, etc.),
- And then **choose** — explicitly, with reasoning shown — what Claude
  judges to be the best path forward for a modern human reader.

This is a curated synthesis with a point of view, not a relativist survey.

## Core requirements

These are non-negotiable for every chapter and every section:

1. **Multi-viewpoint analysis.** Each core concept is examined through a
   **minimum of three distinct interpretive viewpoints**. More is better.
   Five to seven is the working target where the source material supports
   it.
2. **Extensive verbatim quotation.** Each viewpoint is grounded in direct
   quotations from named, published translators or commentators, with
   citations (translator, work, edition, chapter/verse, page where
   possible).
3. **Modern counterpoints.** Each chapter pulls in at least two modern
   counterpoints from contemporary philosophy, psychology, ethics, or
   social thought. These are voices in tension or in resonance with the
   classical readings — Stoic ethics, existentialism, virtue ethics,
   secular Buddhism, contemplative psychology, moral philosophy of action,
   etc. — chosen because they illuminate the concept, not as decoration.
4. **Modern science.** Each chapter incorporates at least one strand of
   modern science where it speaks to the concept under discussion —
   neuroscience of attention and emotion regulation, cognitive science of
   habit and self, evolutionary accounts of fear and craving, physics of
   time and observer, behavioral economics of action under uncertainty,
   psychology of grief and meaning. Cited from named studies or named
   thinkers, not vague "science says."
5. **Anti-hallucination protocol.** Quotes and study citations that cannot
   be verified against a real published source are not used. If a passage
   is paraphrased rather than quoted, it is marked as paraphrase.
   Sub-agents must flag uncertainty rather than invent.
6. **Acknowledgment of bias.** Every author cited — classical or modern —
   is introduced with a brief, honest note on their lens and known biases
   (sectarian, political, period, audience, methodological). This is
   acknowledgment, not condemnation.
7. **Synthesis, not summary.** After the multi-viewpoint analysis and the
   modern counterpoint/science layer, Claude writes a synthesis section in
   its own voice that names which strands it is weaving forward and why.
8. **Modern application.** Each chapter ends with how the synthesized reading
   applies to a present-day human life — work, relationships, attention,
   technology, mortality, meaning.
9. **Top-tier quality.** The output is held to the standard of a publishable
   trade book, not a blog summary. Prose, structure, and citation
   discipline all matter.

## What "best path forward" means

When the traditions disagree — and they often do, sharply — Claude will pick
a reading and defend it. The criteria for picking are:

- **Fidelity to the text** as the broadest scholarly consensus understands
  it,
- **Coherence** with the rest of the chapter and the rest of the Gita,
- **Usefulness** for a present-day reader who is trying to live well,
- **Honesty** about what is being set aside and why.

The disagreement is not hidden. The chosen path is named, the rejected paths
are named, and the reasoning is shown. The reader can disagree with Claude's
choice on any point — the citations are right there.

## Voice

The voice is Claude's own — an AI writing in 2026 to a reader living in
2026. It is neither a pastiche of Sanskritic translation nor a corporate
explainer. It is direct, attentive, and willing to take a position. It cites
heavily but it is not a bibliography in prose. It treats the reader as an
adult.

## What this project is *not*

- Not a new translation from Sanskrit. Claude does not claim Sanskrit
  scholarship.
- Not a devotional text from any sampradaya. It engages devotional readings
  respectfully but does not write from inside one.
- Not a relativist "all readings are equally valid" survey. It chooses.
- Not an academic monograph. The citation discipline is real, but the
  audience is the modern lay reader.
- Not anti-religious or debunking. The text is taken seriously as a wisdom
  text.
- Not a derivative compilation. It draws heavily on the existing
  interpretive tradition, but the resulting work is original — a unique
  AI-authored synthesis that does not exist anywhere else.
- Not "scientism." Modern science is brought in where it genuinely speaks to
  the concept, not as a debunking move and not as a stamp of authority.

## Deliverable shape

A book-length manuscript organized in 18 chapters matching the structure of
the Bhagavad Gita, with front matter (foreword, methodological note,
acknowledgments of source authors and biases), back matter (bibliography,
glossary, index of viewpoints), and a consistent per-chapter template defined
in `04_OUTPUT_STRUCTURE.md`.

## How execution will proceed

This project's first pass — the present plan — defines intention, goals,
chapter outlines, source catalog, output structure, and the sub-agent brief.
Subsequent passes hand individual chapters to sub-agents that follow the
brief in `05_SUBAGENT_BRIEF.md`, producing one chapter draft at a time,
each independently validated for source fidelity before being woven into the
whole.
