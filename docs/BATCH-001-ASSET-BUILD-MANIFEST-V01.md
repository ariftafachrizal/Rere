# Rere — Batch 001 Asset Build Manifest

**Version:** v1.0  
**Date:** 2026-09-12  
**Status:** PRODUCTION CONTROL DOCUMENT  
**Purpose:** define every non-canonical learning/scene asset that must exist before Gemini scene generation begins.

---

## 1. Governing Rule

Batch 001 scene generation must never invent an educational object that should have been prepared as a reference asset.

Production chain:

**Canonical Reference → Learning Asset → Asset QA → Scene Generation → Scene QA**

The Canonical Asset Registry remains the source of truth for Rere, recurring props, and worlds. fileciteturn53file0L2-L2

A learning asset may be new, but it must visually belong to the Rere universe and must not redefine an existing canonical identity.

---

## 2. Shared References — Already Canonical

Use these when applicable; do not regenerate them independently:

- `assets/character/rere-character-sheet-canonical.png`
- `assets/character/rere-expression-sheet-canonical.png`
- `assets/character/rere-turnaround-sheet-canonical.png`
- `assets/props/signature/rere-pink-bunny-canonical.png`
- `assets/props/signature/rere-backpack-canonical.png`
- `assets/props/signature/rere-learning-book-canonical.png`
- `assets/props/signature/rere-pink-heart-motif-canonical.png`
- `assets/props/utility/rere-crayon-kit-canonical.png`
- `assets/props/utility/rere-water-bottle-canonical.png`
- `assets/props/utility/rere-pencil-case-canonical.png`
- `assets/props/utility/rere-learning-box-canonical.png`
- `assets/props/utility/rere-activity-apron-canonical.png`
- `assets/environment/rere-world-playroom-canonical.png`
- `assets/environment/rere-world-bedroom-canonical.png`
- `assets/environment/rere-world-kitchen-canonical.png`
- `assets/environment/rere-world-garden-canonical.png`
- `assets/environment/rere-world-classroom-canonical.png`

Learning libraries already approved:

- `rere-learning-colors-sheet-canonical.png`
- `rere-learning-shapes-sheet-canonical.png`
- `rere-learning-numeracy-sheet-canonical.png`
- `rere-learning-literacy-sheet-canonical.png`
- `rere-learning-science-nature-sheet-canonical.png`

---

## 3. Asset Status Vocabulary

- **READY:** reference exists and has passed design approval.
- **BUILD:** must be generated/assembled before scene generation.
- **QA:** generated; awaiting human approval.
- **LOCKED:** approved for downstream scene generation.
- **REJECT:** do not use; regenerate or revise.

---

# 4. EP001 — Petualangan Warna

Target learning colors: **merah, kuning, biru, hijau, pink**.

| Asset ID | Asset | Purpose | Status | Proposed output |
|---|---|---|---|---|
| `RERE-LEARN-EP001-APPLE-01` | Red Apple | Red recognition | BUILD | `RERE-EP001-ASSET-RED-APPLE-V01.png` |
| `RERE-LEARN-EP001-BANANA-01` | Yellow Banana | Yellow recognition | BUILD | `RERE-EP001-ASSET-YELLOW-BANANA-V01.png` |
| `RERE-LEARN-EP001-BALL-01` | Blue Ball | Blue recognition | BUILD | `RERE-EP001-ASSET-BLUE-BALL-V01.png` |
| `RERE-LEARN-EP001-PLANT-01` | Green Plant/Leaf | Green recognition | BUILD | `RERE-EP001-ASSET-GREEN-PLANT-V01.png` |
| `RERE-LEARN-EP001-FLOWER-01` | Pink Flower | Pink recognition | BUILD | `RERE-EP001-ASSET-PINK-FLOWER-V01.png` |
| `RERE-LEARN-EP001-QUIZ-SET-01` | Quiz object set | Final five-color review | BUILD | `RERE-EP001-ASSET-QUIZ-SET-V01.png` |

### EP001 asset rules

- Objects must be immediately recognizable by a 2–4-year-old.
- Color must be visually dominant and unambiguous.
- Avoid gradients that make the teaching color unclear.
- Avoid extra objects that could become alternative answers.
- Quiz set must contain exactly one clear representative for each target color.
- Keep object style consistent across all five learning objects.

---

# 5. EP002 — Petualangan Bentuk

Target shapes: **lingkaran, persegi, segitiga**.

| Asset ID | Asset | Purpose | Status | Proposed output |
|---|---|---|---|---|
| `RERE-LEARN-EP002-CIRCLE-01` | Circle learning object/card | Shape recognition | BUILD | `RERE-EP002-ASSET-CIRCLE-V01.png` |
| `RERE-LEARN-EP002-SQUARE-01` | Square learning object/card | Shape recognition | BUILD | `RERE-EP002-ASSET-SQUARE-V01.png` |
| `RERE-LEARN-EP002-TRIANGLE-01` | Triangle learning object/card | Shape recognition | BUILD | `RERE-EP002-ASSET-TRIANGLE-V01.png` |
| `RERE-LEARN-EP002-MATCH-SET-01` | Three-shape matching set | Matching activity | BUILD | `RERE-EP002-ASSET-MATCH-SET-V01.png` |

### EP002 asset rules

- Silhouettes must be geometrically obvious.
- Circle must not become an oval.
- Square must have four equal sides.
- Triangle must have three clear sides/corners.
- Matching set must not introduce a fourth target shape.

---

# 6. EP003 — Angka 1–5

Target: recognize and count **1–5** using one-to-one correspondence.

| Asset ID | Asset | Purpose | Status | Proposed output |
|---|---|---|---|---|
| `RERE-LEARN-EP003-COUNTABLE-SET-01` | Canonical countable toy | Counting | BUILD | `RERE-EP003-ASSET-COUNTABLE-TOY-V01.png` |
| `RERE-LEARN-EP003-NUMBER-CARDS-01` | Number cards 1–5 | Number recognition | BUILD | `RERE-EP003-ASSET-NUMBER-CARDS-1-5-V01.png` |
| `RERE-LEARN-EP003-COUNT-SET-01` | Countable instances 1–5 | Exact-count scene reference | BUILD | `RERE-EP003-ASSET-COUNT-SETS-1-5-V01.png` |

### EP003 critical invariant

**The visible number of objects must exactly equal the spoken/visual target number.**

No missing objects, duplicates hidden behind one another, ambiguous overlaps, or extra decorative copies.

---

# 7. EP004 — Bermain Cocokkan

Target: visual matching by one criterion at a time.

| Asset ID | Asset | Purpose | Status | Proposed output |
|---|---|---|---|---|
| `RERE-LEARN-EP004-PAIR-01` | Matching pair A | Match | BUILD | `RERE-EP004-ASSET-PAIR-A-V01.png` |
| `RERE-LEARN-EP004-PAIR-02` | Matching pair B | Match | BUILD | `RERE-EP004-ASSET-PAIR-B-V01.png` |
| `RERE-LEARN-EP004-PAIR-03` | Matching pair C | Match | BUILD | `RERE-EP004-ASSET-PAIR-C-V01.png` |
| `RERE-LEARN-EP004-MATCH-BOARD-01` | Three-pair activity board | Matching activity | BUILD | `RERE-EP004-ASSET-MATCH-BOARD-V01.png` |

### EP004 asset rules

- Each pair must be genuinely identical in the selected matching criterion.
- Distractors must not create a second plausible answer.
- One matching criterion is presented at a time: same color, same shape, or same object identity.
- Do not mix multiple hidden rules in one activity.

---

# 8. EP005 — Bagian Tubuh

Target vocabulary: **mata, hidung, mulut, tangan, kaki**.

| Asset ID | Asset | Purpose | Status | Proposed output |
|---|---|---|---|---|
| `RERE-LEARN-EP005-BODY-VISUAL-01` | Child-safe body vocabulary visual | Vocabulary reference | BUILD | `RERE-EP005-ASSET-BODY-VOCAB-V01.png` |
| `RERE-LEARN-EP005-MIRROR-01` | Child-safe mirror activity reference | Imitation | BUILD | `RERE-EP005-ASSET-MIRROR-ACTIVITY-V01.png` |

### EP005 asset rules

- Keep anatomy simple, friendly, and preschool-appropriate.
- No medical, clinical, anatomical dissection, or body-horror imagery.
- Hands and feet must remain anatomically coherent.
- Mirror reflection must preserve Rere's canonical identity.

---

# 9. EP006 — Merapikan Mainan

Target routine: **ambil → kelompokkan → simpan → ulangi**.

| Asset ID | Asset | Purpose | Status | Proposed output |
|---|---|---|---|---|
| `RERE-LEARN-EP006-BALL-SET-01` | Ball toy set | Sort/store | BUILD | `RERE-EP006-ASSET-BALL-SET-V01.png` |
| `RERE-LEARN-EP006-BLOCK-SET-01` | Block toy set | Sort/store | BUILD | `RERE-EP006-ASSET-BLOCK-SET-V01.png` |
| `RERE-LEARN-EP006-STORAGE-01` | Canonical storage destination | Put-away action | BUILD | `RERE-EP006-ASSET-STORAGE-V01.png` |
| `RERE-LEARN-EP006-SORTING-SET-01` | Two-category sorting arrangement | Demonstrate routine | BUILD | `RERE-EP006-ASSET-SORTING-SET-V01.png` |

### EP006 asset rules

- Toys must remain physically present during the action chain.
- Storage destinations must be visually stable.
- The same toy cannot silently teleport or disappear between shots.
- Sorting must be visually obvious.

---

# 10. Batch Generation Order

Build assets in this order:

1. EP001 colors — establishes first production learning-object style.
2. EP002 shapes — reuse the same visual language.
3. EP003 numeracy — lock exact-count behavior.
4. EP004 matching — lock pair/distractor logic.
5. EP005 body vocabulary + mirror.
6. EP006 toys + storage.
7. Human QA and lock all approved outputs.
8. Only then execute scene generation for the corresponding episodes.

---

# 11. Gemini Asset Prompt Standard

Every asset generation prompt must include:

1. Rere visual universe/style reference.
2. Relevant canonical learning-library reference.
3. Exact educational purpose.
4. Required silhouette/color/count/matching constraint.
5. Clean isolated presentation suitable as a downstream reference.
6. No text unless the asset is explicitly a number/label card.
7. Universal negative prompt from `docs/BATCH-001-GEMINI-PROMPT-PACK-V01.md`.

### Generic asset instruction

> Create a new educational learning asset for the Rere preschool universe. Use the attached canonical Rere visual references and approved learning-library references as authoritative style sources. Preserve the soft pastel 3D CGI/kawaii visual language, rounded child-safe forms, clean composition, warm friendly presentation, and restrained pink signature accent. Do not redesign Rere, recurring props, or recurring environments. The asset must be immediately understandable to a 2–4-year-old and must satisfy the exact learning constraint specified for this asset. Produce a clean reference-ready asset with no watermark, no random text, no unnecessary decoration, and no ambiguous alternative answer.

---

# 12. Human QA Gate

An asset becomes **LOCKED** only when a human reviewer confirms:

- [ ] educational target is immediately obvious
- [ ] visual identity fits Rere universe
- [ ] no canonical identity drift
- [ ] correct color/shape/count/matching criterion
- [ ] clean silhouette
- [ ] no accidental distractor
- [ ] no malformed geometry
- [ ] no text artifacts
- [ ] no watermark/logo
- [ ] suitable for reuse across multiple shots
- [ ] filename and Asset ID match

If any critical item fails: **REJECT**.

---

## 13. Definition of Done

Batch 001 is asset-ready when every BUILD item above has an approved visual file, a stable Asset ID, a versioned filename, and a documented human QA decision.

**Do not start full scene generation while required BUILD items remain unapproved.**
