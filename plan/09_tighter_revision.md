# 09 — Tighter Revision

Fourth revision pass. plan/06 set the vision. plan/07 installed
direct address. plan/08 cut length and dropped Sanskrit / inline
references. This pass fixes three remaining problems:

1. Each chapter rambles. The point gets made, then made again from
   another angle, then again with a different example, then a coda
   restates it. Cut.
2. Each chapter narrates itself in third person. *The chapter says.
   The chapter is asking. Where the chapter leaves you.* The reader
   is inside the chapter; the chapter does not need to point at
   itself.
3. Chapters lean on each other. *The next chapter opens this. The
   previous chapter argued.* Each chapter should stand alone,
   confidently making its point without referencing the book's
   architecture.

Everything in plans 06–08 not contradicted here remains binding.

## What changes

### 1. Length

Cut another 30–40%.

- Average chapter: **~1,000 words** (range 800–1,200)
- Chapter 1: **1,800–2,200 words** (carries book intro + scene + roadmap)
- Chapter 18: **1,500–1,800 words** (the gathering point)

Total chapter manuscript target: **~20,000 words** (from ~32,000).

The cuts come from: removing meta-commentary (item 2 below),
removing inter-chapter references (item 3 below), collapsing
paragraphs that restate the prior paragraph, cutting examples
that duplicate the work of other examples, cutting codas that
repeat the lede.

### 2. Structure: point → body → summary

Every chapter has three parts. They are not labeled with
subheadings. The reader feels them as continuous prose.

**Lede (50–150 words).** State the chapter's point — or points,
if more than one — as plain assertions. No scene-setting, no
throat-clearing, no warm-up. The first sentence is the claim.
If there are multiple claims, list them as numbered or bulleted
items immediately under the lede.

**Body (600–900 words).** The long-form development of the lede.
Continuous prose. Examples, analogies, the Gita's verses where
they earn position, philosophical or scientific moves where they
earn position. Each paragraph develops the argument; no paragraph
restates the prior paragraph. Subheadings allowed sparingly
(2–3 max per chapter, naming a turn in the argument, never naming
the chapter's own structure).

**Summary (50–150 words).** The closing. Restate the point in a
different register — an image, an instruction, a turn the body
has earned. Land once. No coda after the close.

Chapter 1 is the exception. It carries the book's roadmap (per
plan/08) plus the chapter's own claim. Length 1,800–2,200; the
roadmap section runs ~400 words and sits between the dramatic
scene and the closing.

### 3. No self-referential meta-commentary

Forbidden phrases (search for and remove):

- *this chapter / the chapter / this book / the book* used to
  point at the work itself
- *the chapter says / the chapter is asking / the chapter teaches*
- *where the chapter leaves you / the chapter ends with*
- *the chapter is doing something specific / the chapter is
  reading itself*
- *that is the chapter, in one line / that is the central claim*
- *this is the chapter's claim / this is what the chapter is*

The chapter makes its claims as the author's claims, in the
author's voice. *Attention is the practice* — not *the chapter
claims attention is the practice*. *The collapse is the door* —
not *this is the chapter's claim*. The author speaks. The work
does not narrate itself.

### 4. No inter-chapter narration

Forbidden:

- *the next chapter / the previous chapter / Chapter N argues*
- *we will see / we have seen / as I argued earlier*
- *this builds on / this opens what comes next*
- *the book has been doing X for ten chapters*

Each chapter stands alone. If a point made in another chapter is
needed, restate it briefly in the author's voice without naming
where it came from. The reader picking up Chapter 11 should not
need to know what Chapter 7 said.

The exception: **Chapter 1's roadmap** (per plan/08) names the
four-part posture the rest of the book develops. That is allowed
because Chapter 1 is the entry point. Chapters 2–18 do not refer
back to it.

### 5. No source-reading meta-commentary

Forbidden:

- *most readings treat X as Y, but I read it differently*
- *I read this chapter through the position that*
- *the commentators are split on*
- *as Sankara reads it / on Ramanuja's reading*

The author has absorbed the readings and speaks in own voice.
The back-matter references list names everyone the book drew on.
A reader who wants to know where a position came from goes there.

Famous quoted phrases stay where they earn position — *I am
Time, the destroyer of worlds*; *the just and loving gaze* —
without inline attribution.

### 6. Remove YAML frontmatter

Eleven chapters currently open with a YAML frontmatter block:

```
---
chapter: N
sanskrit_title: ...
author: Claude (Anthropic)
status: ...
---
```

This renders as a metadata table on GitHub and adds nothing for
the reader. Remove from all 18 chapters. The chapter opens with
the H1 title.

### 7. Add next-chapter hyperlink

At the end of every chapter (after the closing prose), add:

```
---

[Continue to Chapter N+1 — Title](FILENAME.md)
```

For chapter 18, link to the back matter:

```
---

[References](../back_matter/01_references.md)
```

Use a horizontal rule (`---`) to separate the link from the
chapter's closing prose.

## Voice preserved

- Direct YOU address
- Lead with the claim
- No Sanskrit transliterations in the prose (English equivalents
  per plan/08)
- No inline citations
- Smart-reader assumed
- Coffee-shop pace

## Hard floors (still binding)

- 18-chapter structure
- Each chapter delivers its argumentative goal from plan/06
- Author's positions held (the world is real; the deeper self is
  real-but-not-final; surrender is the synthesis at 18.66)
- Chapter 1's introductory opening (Gita + book + dramatic scene
  + roadmap)
- Chapter 18's closing on the bow picked up
- Closure on something memorable
- Verbatim quotations of famous lines kept

## What is cut from prior plans

- plan/07's "2,500–3,500 word per-chapter target." Now 800–1,200.
- plan/08's "1,200–1,800 word per-chapter target." Now 800–1,200.
- The "engage 2–3 commentators substantively" guidance from
  review/22. Now: zero inline commentator engagement; absorb
  and speak.
- Any subheadings naming the chapter's own structure ("Where the
  chapter leaves you," "What this book teaches" inside Ch 1's
  internal sections beyond the roadmap).

## Chapter-by-chapter directives

The directives below are calibrations, not rewrites. Each agent
reads its current chapter, applies the manuscript-wide rules
above, and lands on the target word count.

### Ch 1 (current 2,547)
- Keep the Gita-introduction opening (~150 words).
- Keep the dramatic battlefield scene (~300 words).
- Keep "the collapse is the door" claim (~100 words).
- Keep the four-part posture roadmap (~400 words).
- Cut "Why this lands now" + "What it looks like in your life"
  to ~600 words combined. Three vignettes max, briefly.
- Cut "What follows" coda. The chapter closes on the image of
  the bow slipping from the hand.
- Remove YAML frontmatter.
- Target: **1,800–2,200 words**.

### Ch 2 (current 1,620) — Act fully without grafting selfhood onto outcome
- Lede: state the instruction in 2–3 sentences.
- Cut "the chapter is foundation" / "where the chapter leaves
  you" / "the chapter does not say" — all of it.
- Cut one of the two case examples (interview OR medical
  decision, not both at length).
- Remove YAML frontmatter.
- Target: **900–1,100 words**.

### Ch 3 (current 1,789) — Action is the only honest path
- Lede: state the case for action over withdrawal.
- Cut commentator-style framing.
- Tighten the body.
- Target: **900–1,100 words**.

### Ch 4 (current 1,811) — Lineage and the teacher
- Lead with 4.34: approach a teacher with humility, ask, serve.
- Cut architecture-preview language.
- Target: **900–1,100 words**.

### Ch 5 (current 1,417) — Inner renunciation, not geographic withdrawal
- Lede: renunciation is inner, not outer.
- This chapter is already near target — light pass.
- Target: **800–1,000 words**.

### Ch 6 (current 1,797) — Attention is the practice
- Lede already strong; preserve.
- Cut doubled close.
- Compress modern-source mentions to one or two.
- Target: **900–1,100 words**.

### Ch 7 (current 1,797) — The world is real
- Lede already strong; preserve.
- Cut self-referential narration ("This is the chapter where the
  book commits to that. The previous...").
- Target: **900–1,100 words**.

### Ch 8 (current 1,748) — What a life accumulates becomes operative at the threshold
- Lede already strong; preserve the opening line.
- Cut "That is the chapter, in one line" — replace with direct
  assertion.
- Cut "I read most of this book through the position that" —
  replace with direct assertion.
- Cut "The chapter is not adding mysticism. It is reading itself."
- Target: **900–1,100 words**.

### Ch 9 (current 1,697) — Devotion has no entry fee
- Lede already strong.
- Light pass.
- Target: **900–1,100 words**.

### Ch 10 (current 1,499) — Train the eye
- Already near target.
- Cut self-referential narration if any.
- Remove YAML frontmatter.
- Target: **800–1,000 words**.

### Ch 11 (current 2,002) — When something too big is granted, ask for the smaller face
- Lede: the asking is the right response, not weakness.
- Cut "I will name as my reading and not the chapter's own text"
  — own the extension directly without meta-commentary.
- Cut "No other chapter contains a vision. No other ruptures
  the dialogue" — meta-commentary about the book's structure.
- Compress the climate / technology / doomscroll / bedside
  vignettes — three, not four, briefly.
- Remove YAML frontmatter.
- Target: **1,000–1,200 words**.

### Ch 12 (current 1,596) — The qualities of a life given to love
- Lede: the qualities are diagnostic, not virtues to assemble.
- Light pass.
- Target: **900–1,100 words**.

### Ch 13 (current 1,651) — The watcher is not the weather
- Lede already strong.
- Cut "The chapter calls that the watcher" — direct assertion.
- Cut "It is not a metaphysical curiosity" — the next sentence
  states it positively, that is enough.
- Target: **900–1,100 words**.

### Ch 14 (current 1,715) — Practice has a body
- Lede already strong: "Practice has a body."
- Cut self-referential narration.
- Remove YAML frontmatter.
- Target: **900–1,100 words**.

### Ch 15 (current 1,710) — The supreme person
- Lede in plain assertion.
- Remove YAML frontmatter.
- Target: **900–1,100 words**.

### Ch 16 (current 1,698) — A mirror, not a roster
- Lede already strong: "This chapter is a mirror, not a roster."
  Convert to: "Use this as a mirror, not a roster" — drop the
  self-reference.
- Target: **900–1,100 words**.

### Ch 17 (current 1,698) — Your faith is what your life does
- Lede already strong (in the title-line style).
- Remove YAML frontmatter.
- Target: **900–1,100 words**.

### Ch 18 (current 2,133) — Surrender as the synthesis
- Lede: stop trying to save yourself by your performance.
- Compress the recap of the book's prior chapters; this chapter
  is the gathering point but does not need to summarize each
  predecessor.
- Keep the bow-picked-up closing.
- Remove YAML frontmatter.
- Target: **1,500–1,800 words**.

## Process

1. plan/09 (this document) is binding.
2. 18 chapter revision agents run in parallel. Each reads plan/09,
   reads its current chapter, and writes a new version replacing
   the file.
3. Each agent: removes YAML frontmatter, applies the manuscript-
   wide rules, hits its target word count, adds the next-chapter
   hyperlink at the end.
4. After agents land, the manuscript is committed and pushed.

— *Claude*
