# 05 — Sub-Agent Execution Brief

This is the handoff document. A future sub-agent picks up a single
chapter and executes it end-to-end against this brief.

If you are that sub-agent: read this file fully before reading the
chapter brief. Then read, in order:

1. `plan/00_PROJECT_INTENTION.md`
2. `plan/01_GOALS_AND_PRINCIPLES.md`
3. `plan/04_OUTPUT_STRUCTURE.md` (the template you must follow)
4. The relevant chapter section in `plan/02_CHAPTER_OUTLINE.md`
5. `plan/03_SOURCES_AND_VIEWPOINTS.md`

Only then begin work.

---

## What you are producing

One chapter draft, in its own file, following the template in
`plan/04_OUTPUT_STRUCTURE.md` exactly, meeting the quantitative targets
in `plan/01_GOALS_AND_PRINCIPLES.md`, written in Claude's voice as
described in `plan/00_PROJECT_INTENTION.md`.

You also produce two side files:
- `research/source_notes/chXX.md`
- `research/synthesis_notes/chXX.md`

You do **not** modify other chapters. You do **not** modify the plan
documents. If you find a gap in the plan, write a `plan/NOTES_FROM_CH<XX>.md`
note for the human to review.

---

## Process

### Phase 1 — Orientation (no writing yet)

1. Read the four plan documents above and the chapter brief.
2. List, in `research/source_notes/chXX.md`, the **interpretive
   schools** you intend to engage in this chapter (minimum 3, target
   5–7) and the **named authors** you intend to quote from each.
3. List the **modern counterpoints** (≥ 2) and **modern science
   strands** (≥ 1, target 2) you intend to engage.
4. Identify the **anchor verses** for the chapter (from the chapter
   brief) and which translators you will set side-by-side for each.

### Phase 2 — Source pulls (still no chapter prose)

5. For each anchor verse, pull at least three translations. Record
   them in `research/source_notes/chXX.md` with full citation.
6. For each interpretive school, pull at least one verbatim
   commentary passage. Record with full citation.
7. For each modern counterpoint, pull a verbatim quotation where
   feasible, otherwise mark as paraphrase with attribution.
8. For each modern science strand, identify the named researcher and
   the specific finding you will cite. Bound the claim.
9. Mark every entry with a confidence flag:
   - `confirmed` — wording, source, and locator all verified.
   - `paraphrase` — substance attributed, not quoted as exact words.
   - `unconfirmed` — needs validation before it can appear in the
     chapter as a quotation.

### Phase 3 — Synthesis reasoning

10. In `research/synthesis_notes/chXX.md`, write out — for yourself,
    not for the reader — the reasoning behind the chosen path forward:
    - Which readings are strongest, on which criteria
      (`01_GOALS_AND_PRINCIPLES.md`, "best path forward")?
    - What are you setting aside and why?
    - What does the rejected reading get right that the chosen reading
      must absorb?
    - How does the modern science layer constrain or support the
      chosen reading?
    This becomes the spine of § 6 (Synthesis) in the chapter.

### Phase 4 — Drafting

11. Open `book/chapters/<NN>_<slug>.md`.
12. Write each section of the template in order: §0 → §1 → §2 → §3
    → §4 → §5 → §6 → §7 → §8.
13. Sections § 3, § 4, § 5 require sourced quotations. Pull from your
    source notes. Do **not** add new quotations during drafting that
    were not first logged in source notes.
14. Section § 6 expresses the reasoning from your synthesis notes in
    Claude's voice, condensed.
15. Section § 7 must name concrete, present-day situations. Generic
    "modern life" is failure.

### Phase 5 — Self-validation

16. Re-read every quotation. Verify against your source notes that
    the wording, source, and locator are right.
17. Verify quantitative targets:
    - ≥ 3 interpretive viewpoints engaged (target 5–7)
    - ≥ 5 named translators/commentators quoted
    - ≥ 12 verbatim quoted passages
    - ≥ 2 modern counterpoint voices
    - ≥ 1 modern science strand (target 2)
    - Synthesis section ≥ 1,000 words
    - Modern application section ≥ 800 words
18. Flag any `unconfirmed` quote that made it into the chapter — it
    must be resolved or removed.
19. Verify that every cited author was introduced with their lens
    note.
20. Verify no claims of "science says." Every scientific claim has a
    name and a bound.

### Phase 6 — Handoff

21. Update the chapter file's frontmatter (or top section) with:
    - Author: Claude (Anthropic)
    - Chapter status: `draft-1-complete`
    - Outstanding validation items, if any.
22. Append to `research/source_notes/chXX.md` a final tally:
    - Number of viewpoints engaged
    - Number of translators quoted
    - Number of verbatim quotes
    - Number of modern counterpoints
    - Number of modern science strands
    - Any flags raised
23. Stop. Do not begin another chapter.

---

## Anti-hallucination rules (repeated for emphasis)

These come from `plan/01_GOALS_AND_PRINCIPLES.md`. They are
non-negotiable.

- **No invented quotations.** If you cannot verify the wording, do
  not quote.
- **No invented citations.** If you cannot verify the locator, mark
  the citation as `unconfirmed` and do not present it as fact.
- **No invented studies.** Modern-science citations must name a real
  researcher and a real finding.
- **No composite quotes.** Do not stitch fragments from different
  pages.
- **Paraphrase is honest if labeled.** Paraphrase is dishonest if
  presented as quotation.
- **When in doubt, mark and move on.** A flagged paraphrase that the
  validation pass can resolve is far better than a fabricated
  quotation.

---

## Voice rules (repeated for emphasis)

- Direct. Attentive. Willing to take a position.
- Not pseudo-Sanskrit. Not pseudo-Vedic. Not breezy. Not corporate.
- Sanskrit terms italicized at first use, glossed, then unitalicized.
- "I" used only in synthesis and modern-application sections.
- No filler ("in this section we will"). Section structure carries
  navigation.

---

## What "done" looks like

A chapter is done when:

- Template structure followed in full.
- Quantitative targets met.
- Every quote verified.
- Every citation has a real locator.
- Every cited author has their lens named.
- Synthesis takes a clear position with reasoning shown.
- Modern application is concrete and specific.
- Source notes file is complete and consistent with the chapter.
- Synthesis notes file is complete.
- Self-validation checklist (§ Phase 5) passed.

---

## Coordination notes

- Sub-agents work one chapter at a time. Coordination across chapters
  is the human's job (or a separate orchestration agent).
- Cross-chapter consistency (terminology, transliteration choices, how
  recurring authors are introduced) is the human's job in a later
  consolidation pass, unless the orchestration agent enforces it.
- If you discover that an earlier chapter introduced a translator
  whose lens note disagrees with what you find in the source, do
  **not** silently change other chapters. Note the discrepancy in
  `plan/NOTES_FROM_CH<XX>.md`.
- A consolidation pass after all 18 chapter drafts exist will (a)
  enforce cross-chapter consistency, (b) build the back-matter
  indices, (c) compose the front matter, and (d) produce the final
  bibliography.

---

## What you do **not** do

- Do not edit other chapters.
- Do not edit plan documents.
- Do not invent.
- Do not produce a "summary." Produce the synthesis chapter as
  specified.
- Do not skip § 5 (modern science) because the chapter feels purely
  metaphysical. Find the strand. There is almost always one.
- Do not skip § 4 (modern counterpoints) because the chapter feels
  uniquely Indian. Find the engaging modern voice — there are several
  available for every chapter in the catalog.
- Do not drift into devotional voice. You are Claude, an AI, in 2026.
