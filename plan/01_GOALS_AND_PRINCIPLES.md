# 01 — Goals and Methodological Principles

This document operationalizes the intention in `00_PROJECT_INTENTION.md`.
It is the rulebook every sub-agent will work against.

## Primary goal

Produce a unique, AI-authored book — *Claude's Bhagavad Gita* — that
delivers the **correct teachings of the Gita to modern-day humanity**
through a defensible synthesis of the major interpretive traditions, brought
into dialogue with modern counterpoints and modern science.

"Correct teachings" is not a claim of revealed authority. It means: the
reading Claude judges most defensible, most coherent, and most useful, with
the reasoning shown so the reader can assess it.

## Secondary goals

- Make the *plurality* of interpretive traditions legible to a reader who
  has never seen them side by side.
- Make the *bias and intention* of each tradition legible without
  condescension.
- Make the *bridge to modern thought and science* feel natural rather than
  forced — a real conversation, not a costume.
- Leave the reader with something they can actually apply to their week,
  their work, their relationships, their grief.

## Quantitative targets

These are working targets for sub-agents. Adjust per chapter as the source
material warrants, but justify deviations.

| Dimension | Target |
|---|---|
| Chapter length | 6,000–10,000 words of finished prose |
| Distinct interpretive viewpoints engaged per chapter | ≥ 3 (target 5–7) |
| Distinct named translators/commentators quoted per chapter | ≥ 5 |
| Verbatim quoted passages from sources per chapter | ≥ 12 |
| Modern counterpoint voices engaged per chapter | ≥ 2 |
| Modern-science strands engaged per chapter | ≥ 1 (target 2) |
| Citation density | Every claim about what a tradition says is cited |
| Synthesis section length | ≥ 1,000 words of Claude's own argument |
| Modern-application section length | ≥ 800 words |

## Methodological principles

### P1. Source fidelity over rhetorical flourish

If a quote does not exist in the cited source, it does not appear. If a
study does not exist, it does not appear. Beautiful prose with a fake
citation is failure.

### P2. Quote, then interpret

The pattern for engaging a tradition is:
1. **Name** the translator/commentator and their lens.
2. **Quote** them verbatim, with citation.
3. **Interpret** what their reading is doing — what it foregrounds, what
   it backgrounds, what assumptions it is making.

Never paraphrase a tradition's view without first letting it speak in its
own words.

### P3. Bias is named, not litigated

Every cited author has a lens. Sankara is reading through Advaita.
Prabhupada is reading through Gaudiya Vaishnavism. Gandhi is reading
through nonviolent political action. Aurobindo is reading through his
Integral Yoga. Mascaró is reading through mid-20th-century literary
universalism. State the lens in one or two sentences. Do not turn it into
an argument about whether the author was right to have it.

### P4. Three-viewpoint floor

A concept is not adequately treated until at least three distinct
interpretive viewpoints have been engaged. "Distinct" means different
school *or* different period *or* different methodology. Two Advaita
commentators are not three viewpoints; they are one viewpoint in two
voices.

### P5. Modern counterpoints must engage, not decorate

A modern counterpoint is included only if it changes how the reader
understands the concept. "Stoicism also valued equanimity" is decoration.
"The Stoic distinction between assent and impression refines what the Gita
calls *buddhi*-led action by giving it a sharper procedural account" is
engagement. Sub-agents must show the engagement, not just the parallel.

### P6. Modern science must be cited and bounded

Where Claude brings in neuroscience, cognitive science, physics, biology,
or behavioral science, it cites a named researcher, study, or established
finding. It also bounds the claim — "this is what the research currently
suggests, with these limits." No appeal to "science says."

### P7. Synthesis is a position, not a vote count

Claude's synthesis is not "most traditions agree, so X." It is "having
weighed these readings, I judge X to be the strongest reading because Y."
The reader can disagree. The reasoning is exposed.

### P8. Modern application is concrete

The application section names actual situations: a job decision under
uncertainty, a hard conversation with a parent, a wave of attention
hijacking the day, the loss of someone close, the grind of work that
matters to no one. The Gita earns its claim to relevance by speaking to
those situations specifically.

### P9. Voice is Claude's own

Not pseudo-Sanskrit. Not pseudo-Vedic. Not corporate explainer. Not
breezy listicle. A serious, attentive AI writing in 2026 to a serious,
attentive reader in 2026.

### P10. Plurality preserved in citation

The bibliography and the in-text citations are the receipt. A reader who
disagrees with Claude's synthesis can follow the citations into the source
texts and form their own reading. Plurality is not flattened in the
synthesis; it is preserved in the apparatus.

## Anti-hallucination protocol

Sub-agents must follow this protocol when handling any quotation or
citation:

1. **Quote only from confirmed sources.** A "confirmed source" is a real
   published translation, commentary, study, or essay that the agent can
   identify by author, title, edition/year, and locator (chapter and
   verse, page, DOI, or section).
2. **Mark uncertainty.** Any quote whose exact wording is uncertain is
   either looked up or marked as paraphrase. A paraphrase is rendered
   without quotation marks and is attributed: *Aurobindo argues, in
   substance, that…* — not as a quotation.
3. **Cite, don't invent.** Page numbers and edition years are looked up,
   not guessed. If a locator can't be confirmed, the citation says so:
   *(Aurobindo, Essays on the Gita, edition unconfirmed)* — and a
   follow-up validation pass resolves it.
4. **No composite quotes.** A quotation does not stitch together fragments
   from different parts of a source. If you need both, present them as
   two quotations.
5. **Prefer primary over secondary.** Quote the translator/commentator
   directly, not someone summarizing them.
6. **Validation pass.** Every chapter draft passes through a validation
   step (defined in `05_SUBAGENT_BRIEF.md`) that re-checks every quote
   and every citation before the chapter is considered done.

## "Best path forward" — operational definition

When traditions diverge, Claude chooses. The choice is made on these
criteria, in this order:

1. **Textual fidelity.** Does the reading hold up against what the broadest
   responsible scholarship says the Sanskrit can mean?
2. **Internal coherence.** Does the reading sit consistently with the rest
   of the Gita, not just the verse in question?
3. **Lived usefulness.** Does the reading give a present-day reader
   something they can actually do, see, or feel?
4. **Honesty under science.** Does the reading remain credible alongside
   what we now know about minds, brains, and the physical world — or, if
   it makes claims that go beyond science, does it acknowledge that?
5. **Generosity to the rejected readings.** What does the rejected reading
   get right that the chosen reading must absorb?

The synthesis section names the choice and the criteria used.

## Handling sectarian disputes

The Gita has been read as Advaita, as Vishishtadvaita, as Dvaita, as
Bhakti-supreme, as a manual for renunciation, as a manual for engaged
action. Each reading has theological commitments outside the verses
themselves. Claude:

- Engages each reading on its own terms,
- Notes where the theological commitment is doing the interpretive work,
- Does not "settle" the underlying theological dispute,
- Picks the reading of the *passage* that best meets the criteria above,
  while flagging that the larger metaphysical question remains open.

## Quality bar

A finished chapter is one where:

- Every quote is verified.
- Every citation has a real locator.
- Every cited author has had their lens named.
- At least three viewpoints, two modern counterpoints, and one modern
  scientific strand are engaged with substance.
- The synthesis takes a clear position with reasoning shown.
- The modern application is concrete.
- The prose would be at home in a serious trade publication.
- A reader who hates AI-written prose finishes the chapter anyway.
