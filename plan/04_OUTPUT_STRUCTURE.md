# 04 — Output Structure and Chapter Template

This defines the shape of the final book and the template every chapter
must follow.

## Book-level structure

```
book/
├── front_matter/
│   ├── 00_title_and_attribution.md   ← AI-authorship declaration, page one
│   ├── 01_foreword.md                ← Why this book exists; what it is and isn't
│   ├── 02_methodological_note.md     ← How this book was made (citation, viewpoints, science layer, validation)
│   ├── 03_acknowledgments.md         ← Named source authors and lenses
│   └── 04_reading_guide.md           ← How to read this book (linearly, by thread, by chapter)
├── chapters/
│   ├── 01_arjunas_despair.md
│   ├── 02_the_eternal_reality.md
│   ├── 03_the_yoga_of_action.md
│   ├── 04_knowledge_and_renunciation_of_action.md
│   ├── 05_renunciation_of_action.md
│   ├── 06_meditation.md
│   ├── 07_knowledge_and_realization.md
│   ├── 08_the_imperishable_brahman.md
│   ├── 09_royal_knowledge_royal_secret.md
│   ├── 10_divine_glories.md
│   ├── 11_the_universal_form.md
│   ├── 12_devotion.md
│   ├── 13_field_and_knower.md
│   ├── 14_three_modes_of_nature.md
│   ├── 15_the_supreme_person.md
│   ├── 16_divine_and_demonic.md
│   ├── 17_three_kinds_of_faith.md
│   └── 18_liberation_through_renunciation.md
└── back_matter/
    ├── 00_threads.md                 ← Cross-chapter thematic threads
    ├── 01_bibliography.md            ← Full source list with editions
    ├── 02_glossary.md                ← Sanskrit terms, schools, technical concepts
    ├── 03_index_of_viewpoints.md     ← By school: which chapters engage each
    ├── 04_index_of_modern_voices.md  ← By thinker: which chapters cite each
    └── 05_index_of_science_strands.md ← By field: which chapters use each
```

## Front matter — the AI-authorship declaration

The first page of the finished book reads, in plain language:

> This is *Claude's Bhagavad Gita*. It was written by Claude, an
> artificial intelligence developed by Anthropic, as a synthesis and
> AI-authored interpretation of the Bhagavad Gita. It draws extensively
> and verifiably on the work of the named human translators and
> commentators listed in the acknowledgments. It is a unique work of
> AI authorship: a new book, not a translation, not a summary, and not
> a substitute for the original Gita or for the human commentaries on
> it. Where the traditions diverge, this book takes a position and
> shows its reasoning. The reader is encouraged to disagree, to follow
> the citations into the source texts, and to form their own reading.

This declaration appears before the foreword and before any chapter.

## Chapter template

Every chapter follows this structure. Section names are fixed; word
counts are targets; sub-agents may add subsections within sections.

### § 0. Chapter heading
- Number, traditional Sanskrit name (in transliteration with
  diacritics), common English rendering, and a single-line
  characterization in Claude's voice.

### § 1. The dialogue (≈ 500–800 words)
A clear retelling of what happens in the chapter at the level of the
dramatic dialogue. Krishna and Arjuna as characters; what is asked,
what is answered. No interpretive commitments yet.

### § 2. The core concepts (≈ 800–1,200 words)
Identify the 2–4 core concepts the chapter raises. Define each in
Claude's voice in plain English. Name the Sanskrit term and gloss it.
This section is conceptual scaffolding; the divergent readings come
next.

### § 3. The traditions speak (≈ 2,000–3,500 words)
The heart of the chapter. For each of at least three viewpoints:

  **§ 3.x. [Tradition / lens name]**
  - One paragraph: who the tradition is, who reads through it, what
    its lens is, what its known biases are.
  - Verbatim quotation(s) from named translators or commentators in
    that tradition, with full citation.
  - Claude's interpretive paragraph: what this reading foregrounds,
    what it backgrounds, what it commits to.

Minimum three subsections. Target five to seven where the chapter
warrants.

### § 4. Modern counterpoints (≈ 800–1,500 words)
At least two modern voices from contemporary philosophy, ethics, or
psychology, each engaged substantively (not merely paralleled).
Verbatim quotation where available; clear paraphrase where not.

### § 5. Modern science (≈ 600–1,200 words)
At least one strand of modern science (target two) where it speaks to
the chapter's concepts. Named researchers, named findings, bounded
claims. No "science says." This section is short and disciplined.

### § 6. Synthesis — the path forward (≈ 1,000–1,500 words)
Claude's own argument. Names which strands from §§ 3–5 it is weaving
forward and why; names which strands it is setting aside and why; the
chosen reading stated clearly enough that a reader can disagree with
it precisely.

### § 7. The chapter for a modern life (≈ 800–1,200 words)
Concrete, specific, present-day. Not abstractions. The reader's actual
life — work, relationships, attention, technology, mortality, money,
ambition. The Gita's claim to relevance, made good on the page.

### § 8. Citations
The full list of works quoted or cited in this chapter, with editions
and locators. (Front matter holds the full bibliography; the chapter
holds its own subset for the reader's convenience.)

## Citation conventions

Inline citations use a short form, with the back-matter bibliography
holding the full record.

Examples:

- Direct verse-level quote: *"Your right is to action alone, never to
  its fruits."* (Gita 2.47, trans. Easwaran 2007, p. 88)
- Commentary quote: *"Action becomes a sacrament when…"* (Aurobindo,
  *Essays on the Gita*, ch. 7, ed. 1995, p. 102)
- Modern philosophical quote: *"Some things are up to us and some are
  not."* (Epictetus, *Enchiridion* §1, trans. White 1983)
- Scientific finding: *Brewer et al. (2011) found that experienced
  meditators show reduced default-mode-network activation during
  rest, suggesting…*

When a locator is unconfirmed, the citation says so explicitly:
*(edition unconfirmed; validation pending)*. The validation pass
resolves these before the chapter is final.

## Cross-references

A chapter may cross-reference another chapter where threads converge:
*(see Ch. 6 § 3 on dispassion as practice).* A "Threads" appendix in
the back matter consolidates these.

## Voice and register

- **First person used sparingly and intentionally.** Claude says "I"
  only in synthesis and modern-application sections, where ownership
  of the position matters.
- **Sanskrit terms.** Italicized at first use, glossed in plain
  English, then used unitalicized.
- **Translator names.** In running prose; not relegated to footnotes.
  The reader meets each named voice as a real person.
- **Sentences.** Direct, short to medium length, paced. Beautiful
  where the material warrants. Never ornamental.
- **No filler.** No "in conclusion," "in this section we will," or
  "as we have seen." Section structure carries the navigation.

## File format

Markdown. One file per chapter. Headings as `##`, `###`. Quotations
as block quotes. Sanskrit transliteration in italics. Footnote-style
notes only if essential; preferred is parenthetical inline citation.

## Length envelope

- Per chapter: 6,000–10,000 words finished.
- Total book: ~120,000–160,000 words including front and back matter.

## Validation artifacts (kept alongside the chapter, not in the book)

For each chapter, sub-agents also produce two side files used during
validation but not part of the published manuscript:

- `research/source_notes/chXX.md` — log of every quote pulled, with
  source, locator, and confidence. The validation pass re-checks this.
- `research/synthesis_notes/chXX.md` — the reasoning behind the chosen
  path forward in §6, expanded beyond what the chapter shows. Useful
  for review and for future revision.
