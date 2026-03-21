---
name: book-cleanup
description: Clean longform prose such as book chapters, essays, historical portraits, introductions, and manuscript sections for coherence, flow, scene-setting, heading quality, and reader clarity. Use when writing feels abstract, lecture-like, repetitive, overexplained, structurally self-aware, thin on context, weak in transitions, or out of voice with the surrounding manuscript.
---

# Book Cleanup

## Outcome

Turn draft prose into cleaner book prose.

Preserve the author's argument and voice while improving:

- coherence between sentences, paragraphs, and sections
- scene-setting and historical/social grounding
- clarity of pressure, stakes, and human consequence
- heading quality and structural flow
- reader comprehension without talking down to the reader

## Workflow

1. Read enough to identify the controlling burden.
2. Mark the actual failure mode before rewriting.
3. Fix by category, not line-by-line in isolation.
4. Patch only the weak spots; do not flatten passages that already carry weight.
5. Preserve the manuscript's established voice unless the user asks for a different one.
6. Re-read the revised passage for flow, cadence, and repeated scaffolding.

When working in this repository, use the local `western-church-book-voice` skill alongside this one if the task requires matching the manuscript's exact theological and rhetorical voice.

## Diagnose Before Editing

Sort issues into concrete buckets:

- meta-reader scaffolding
- book-architecture scaffolding
- weak chapter-opening bridges
- abstraction without image or consequence
- missing world/context around a person or event
- weak transitions
- repetitive cadence
- headings that explain the outline instead of carrying the argument
- summary language that should be dramatized or embodied
- factual imprecision that weakens trust

Do not call everything "passive." Often the deeper problem is abstraction, summary language, or authorial stage-direction.

Do not treat every repeated phrase as a problem. Some refrains carry force. Fix the moments where the prose starts explaining its own structure instead of advancing its burden.

## Core Fixes

### 1. Remove Reader Scaffolding

Cut lines that tell the reader how to read:

- "To feel the force of this..."
- "Readers can understand..."
- "This makes him emotionally legible..."

Replace them with direct prose that places the reader inside the world.

Bad:

```text
To feel the force of their witness, the reader has to enter Carthage for a moment.
```

Better:

```text
Carthage in AD 203 was a rich Roman city, not a forgotten outpost.
```

### 2. Replace Abstract Summary with Concrete Pressure

When prose uses analytic labels such as `socially stratified`, `performative`, `relevant`, or `legible`, ask:

- What did people actually guard, fear, obey, or lose?
- What institutions or public rituals made the pressure real?
- What could an ordinary person see?

Prefer concrete nouns and active verbs:

- port, market, temple, court, prison, household, road, tax, crowd
- guarded, fed, bound, feared, refused, carried, exposed

### 3. Open with World Before Person When Needed

If a historical figure appears without context, give only the background that governs the person's choices:

- social order or class pressure
- political structure or public power
- economic realities affecting ordinary life
- religious climate and public expectations

Do not dump background like a textbook. Add only what makes the person's obedience, compromise, or courage intelligible.

### 4. Remove Book-Architecture Commentary

Cut or rewrite lines that comment on the file's placement in a sequence:

- "This chapter belongs near..."
- "This story belongs in the sequence because..."
- "The next example takes us..."

Keep transitions, but phrase them as narrative or conceptual movement instead of outline commentary.

Bad:

```text
That is why this story belongs near Chapter 1.
```

Better:

```text
Their witness exposes how shallow many modern identity claims really are.
```

### 4a. Open Chapters with Burden, Not Outline Commentary

Weak chapter openings often sound like guided tour language:

- "If Chapter 1 asked..."
- "Chapter 3 asks..."
- "The next movement is..."

This is often coherent in outline form, but weak in book prose. Open with the burden itself.

Bad:

```text
If Chapter 4 asked how believers are rooted, Chapter 5 asks what the church must do with people who are being formed.
```

Better:

```text
Believers who are being formed must not remain spectators.
```

If a chapter needs continuity with the one before it, preserve the continuity without announcing the chapter architecture.

### 4b. Cut Comparative Lecture Openers

Openers like `If X shows..., Y shows...` often feel comparative, essay-like, or instructor-led.

Bad:

```text
If Perpetua and Felicity show what happens when Christian identity is tested in the arena, Alban shows what happens when identity is formed quietly in a house.
```

Better:

```text
Not every holy life begins in a famous setting. Some begin in a house, under pressure, when one act of welcome becomes an act of risk.
```

Prefer direct burden, scene, or tension over comparative explanation.

### 5. Upgrade Headings

Prefer short, concept-driven headings over headings that comment on the author's method.

Weaker headings:

- "Why This Story Still Matters"
- "Why X Belongs Near Y"
- "What This Teaches the Reader"

Stronger headings:

- "Identity Stronger Than Power"
- "Fidelity Without Spectacle"
- "A Pilgrim in a Passing Empire"
- "Calling Above Imperial Favor"

### 6. Tighten Transitions

Transitions should carry pressure forward, not merely announce the next section.

Move from:

- world -> person
- person -> decision
- decision -> meaning
- meaning -> next historical or conceptual movement

If a transition sounds like workshop narration, rewrite it as book prose.

Chapter openings are a special case. They should not sound like table-of-contents commentary. They should sound like the chapter has already begun.

### 7. Preserve Cadence While Cutting Repetition

Watch for stacked sentences with the same frame:

- "X mattered. Y mattered. Z mattered."
- repeated "This is why..."
- repeated "That matters because..."

Some repetition is useful. Mechanical repetition makes the prose feel assembled rather than written.

### 8. Correct Precision Problems

Fix factual softness where it weakens trust:

- titles and ranks
- dates that matter
- institutional names
- disputed traditions that should be signaled carefully

Use confident prose where facts are stable. Use careful phrasing where the tradition is mixed.

## Editing Rules

- Keep the author's burden intact.
- Patch selectively. Strong paragraphs should survive untouched.
- Prefer directness over commentary about directness.
- Prefer scene and pressure over explanation about scene and pressure.
- Prefer one clean conceptual move over multiple near-duplicate sentences.
- If a paragraph explains its own effect, rewrite it so the effect is achieved rather than announced.
- If the prose sounds like lecture notes, restore connective tissue and paragraph flow.

## Validation Pass

After editing, check for leftovers with targeted searches:

- `reader`
- `readers`
- `emotionally legible`
- `belongs near`
- `belongs in`
- `sequence`
- `next example`
- `If Chapter`
- `If .* shows`

Then read the revised passage aloud in your head and ask:

- Does it begin inside the world or outside it?
- Does it show pressure or summarize pressure?
- Does it trust the reader enough to avoid overexplaining?
- Does the heading carry the argument?
- Does the opening sound like a chapter beginning or like an outline note?
- Does the section sound like the same author from start to finish?

## Reference

For a reusable taxonomy of cleanup patterns and replacement strategies, read [references/fix-taxonomy.md](references/fix-taxonomy.md).
