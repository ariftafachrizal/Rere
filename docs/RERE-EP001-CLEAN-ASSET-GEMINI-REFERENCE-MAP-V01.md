# RERE EP001 — CLEAN ASSET & GEMINI REFERENCE MAP V01

**Episode:** RERE-EP-001  
**Brand:** Rere dan Cipi  
**Status:** RESET 05 — PRODUCTION REFERENCE MAP  
**Date:** 2026-09-26  
**Source of Truth:** GitHub repository `ariftafachrizal/Rere`

## 1. Purpose

This document is the authoritative attachment/reference map for EP001 Gemini production.

It answers one question for every shot:

> **Exactly which approved references may be attached, which assets are still BUILD dependencies, and which references must never be invented by Gemini?**

Gemini must not use its own memory, a previous generated frame, or an unapproved scene output as an identity source.

Production chain:

**Canonical Reference → Approved Learning Asset → Keyframe/Scene Generation → Human QA → Video Motion → Human QA**

---

## 2. Reference Priority

For every EP001 request, use this priority order:

1. **Canonical Rere character**
2. **Canonical Rere expression/turnaround reference when relevant**
3. **Canonical regular outfit reference when relevant**
4. **Canonical Cipi / Pink Bunny reference**
5. **Canonical playroom**
6. **Canonical recurring props actually used by the shot**
7. **Approved EP001 learning-object reference**
8. **Shot-specific storyboard specification**
9. **Previous approved state/keyframe only for continuity, never for identity**

A previous generated image is never allowed to override a canonical reference.

---

## 3. READY — Canonical References

### Character

- `assets/character/rere-character-sheet-canonical.png`
- `assets/character/rere-expression-sheet-canonical.png`
- `assets/character/rere-turnaround-sheet-canonical.png`
- `assets/character/rere-outfit-sheet-canonical.png`

### Cipi

Public identity:

- **Name:** Cipi
- **Descriptor:** Cipi — Kelinci Pintar
- **Visual identity:** existing canonical Pink Bunny
- **Canonical reference:** `assets/props/rere-pink-bunny-canonical.png.png`

**Important:** Cipi is a naming/brand update, not a visual redesign.

### Playroom

- `assets/props/rere-world-playroom-canonical.png`

### Recurring EP001 props

- Learning Book: `assets/props/rere-learning-book-canonical.png`
- Crayon Kit: `assets/props/rere-crayon-kit-canonical.png`
- Pink Heart Motif: `assets/props/rere-pink-heart-motif-canonical.png`
- Backpack: `assets/props/rere-backpack-canonical.png`

Use only when the storyboard requires the prop.

---

## 4. BUILD — EP001 Learning Assets

These are required before full EP001 scene generation.

| Asset ID | Required asset | Output filename | Status |
|---|---|---|---|
| `RERE-LEARN-EP001-APPLE-01` | Red Apple | `RERE-EP001-ASSET-RED-APPLE-V01.png` | BUILD |
| `RERE-LEARN-EP001-BANANA-01` | Yellow Banana | `RERE-EP001-ASSET-YELLOW-BANANA-V01.png` | BUILD |
| `RERE-LEARN-EP001-BALL-01` | Blue Ball | `RERE-EP001-ASSET-BLUE-BALL-V01.png` | BUILD |
| `RERE-LEARN-EP001-PLANT-01` | Green Plant/Leaf | `RERE-EP001-ASSET-GREEN-PLANT-V01.png` | BUILD |
| `RERE-LEARN-EP001-FLOWER-01` | Pink Flower | `RERE-EP001-ASSET-PINK-FLOWER-V01.png` | BUILD |
| `RERE-LEARN-EP001-QUIZ-SET-01` | Controlled Quiz Object Set | `RERE-EP001-ASSET-QUIZ-SET-V01.png` | BUILD |

**Gate:** Do not generate the full EP001 scene set while any required learning asset remains BUILD/unapproved.

The approved color learning library may be used as a style/design reference:

- `assets/props/rere-learning-colors-sheet-canonical.png`

The learning library does **not** automatically replace the six episode-specific approved derivatives above.

---

# 5. SHOT-BY-SHOT ATTACHMENT MAP

## S01 — SIGNATURE OPENING

**Required attachments**
- Canonical Rere character
- Rere expression reference
- Canonical Cipi/Pink Bunny
- Canonical playroom

**Optional**
- Regular outfit sheet if outfit fidelity needs reinforcement

**Learning asset:** none

**Cipi policy:** REQUIRED and clearly visible.

**Production purpose:** establish Rere + Cipi brand identity.

**Do not attach:** unrelated learning objects, old Pink Bunny variants, legacy episode frames.

---

## S02 — DRAWING HOOK

**Required**
- Canonical Rere character
- Canonical playroom
- Learning Book
- Crayon Kit

**Recommended**
- Canonical Cipi/Pink Bunny

**Learning asset:** none

**Cipi policy:** OPTIONAL background/companion presence; must not compete with the drawing discovery.

**Continuity**
- same playroom as S01
- same Rere outfit
- same canonical Book and Crayon Kit

---

## S03 — SHORT CTA

**Required**
- Canonical Rere character
- Canonical playroom

**Recommended**
- Canonical Cipi/Pink Bunny if visible in composition

**Learning asset:** none

**Cipi policy:** OPTIONAL. Keep CTA primarily Rere-led.

**Editorial**
- CTA graphic is added later
- never ask Gemini to generate “subscribe”, logos, or typography

---

## S04 — MERAH / APPLE

**Required**
- Canonical Rere character
- Canonical playroom
- Approved Red Apple derivative

**Optional**
- Expression reference
- Cipi only if naturally present and visually secondary

**Learning asset dependency:** `RERE-LEARN-EP001-APPLE-01`

**Cipi policy:** OPTIONAL; do not let Cipi create a second focal point.

**Critical**
- one apple only
- unmistakably red
- no strong competing red object
- no answer leakage during 4-second pause

---

## S05 — KUNING / BANANA

**Required**
- Canonical Rere character
- Canonical playroom
- Approved Yellow Banana derivative

**Optional**
- Expression reference
- prior approved S04 state/keyframe for continuity
- Cipi only if secondary

**Dependency:** `RERE-LEARN-EP001-BANANA-01`

**Critical**
- one banana only
- unmistakably yellow
- no answer-revealing gesture during pause
- preserve S04 room geography

---

## S06 — BIRU / BALL

**Required**
- Canonical Rere character
- Canonical playroom
- Approved Blue Ball derivative

**Optional**
- Expression reference
- Cipi only as secondary background companion

**Dependency:** `RERE-LEARN-EP001-BALL-01`

**Critical**
- one ball only
- blue must dominate
- one gentle roll only
- ball must be still during pause
- believable hand/ball and floor physics

---

## S07 — HIJAU / PLANT

**Required**
- Canonical Rere character
- Canonical playroom
- Approved Green Plant/Leaf derivative

**Optional**
- Expression reference
- Cipi only if secondary

**Dependency:** `RERE-LEARN-EP001-PLANT-01`

**Critical**
- one clear learning plant/leaf
- green must be unmistakable
- avoid dense foliage
- no competing green target
- no answer leakage during pause

---

## S08 — PINK / FLOWER

**Required**
- Canonical Rere character
- Canonical playroom
- Approved Pink Flower derivative

**Optional**
- Expression reference
- Cipi only if secondary

**Dependency:** `RERE-LEARN-EP001-FLOWER-01`

**Critical**
- one flower only
- unmistakably pink
- no purple/red ambiguity
- no anthropomorphic face
- preserve Rere two-hand-heart performance

---

## S09 — MINI QUIZ / CHILD TURN

**Required**
- Canonical Rere character
- Canonical playroom
- Approved Quiz Object Set

**Optional**
- Approved individual color derivatives when a specific quiz composition needs them
- Cipi only if the storyboard composition remains clear

**Dependency:** `RERE-LEARN-EP001-QUIZ-SET-01`

**Quiz rule**
- one question at a time
- one plausible answer
- previously learned colors only
- red, yellow and pink
- 4-second response window each
- no pre-answer highlight or pointing

**Cipi policy:** OPTIONAL and secondary. Do not let Cipi signal the answer.

---

## S10 — CREATE / DRAWING

**Required**
- Canonical Rere character
- Canonical playroom
- Learning Book
- Crayon Kit
- Approved color learning derivatives

**Recommended**
- Canonical Cipi/Pink Bunny if present in the established room geography

**Dependencies**
- Red Apple derivative
- Yellow Banana derivative
- Blue Ball derivative
- Green Plant/Leaf derivative
- Pink Flower derivative

These objects do not all need to appear physically in S10; their approved visual language is used to ensure the five target colors remain consistent.

**Critical**
- physical crayon-to-paper interaction
- all five target colors visibly used
- no random text/letters
- finished drawing must remain stable for S11

---

## S11 — ACHIEVEMENT / REVIEW

**Required**
- Canonical Rere character
- Canonical playroom
- Approved finished five-color drawing state from S10

**Recommended**
- Canonical Cipi/Pink Bunny as a secondary companion

**Learning asset:** no new asset

**Continuity**
- the drawing shown must be the actual approved S10 result/state
- no new room
- no new learning concept

---

## S12 — SIGNATURE CLOSING

**Required**
- Canonical Rere character
- Rere expression reference
- Canonical Cipi/Pink Bunny
- Canonical playroom

**Optional**
- canonical Pink Heart Motif if required by visual treatment

**Learning asset:** none

**Cipi policy:** REQUIRED and clearly present.

**Exact brand function**
- Rere leads the closing
- Cipi is visibly present as her canonical companion
- both remain stable through the final frame

**Editorial**
- end-card typography is added in post
- Gemini must not invent end-card text

---

# 6. CIPI PRESENCE POLICY

Cipi is not a redesign target and not a mandatory focal character in every learning shot.

### Required
- S01 Opening
- S12 Closing

### Recommended / optional
- S02 Hook
- S03 CTA
- S10 Create
- S11 Achievement

### Secondary-only
- S04–S09 learning/quiz shots

When Cipi is present during learning:
- Cipi must not point to the answer.
- Cipi must not introduce a competing learning target.
- Cipi must not obscure the object.
- Cipi must use the same canonical Pink Bunny geometry every time.

---

# 7. GEMINI REFERENCE RULES

### Always
- Attach canonical Rere reference directly.
- Attach canonical Cipi reference directly whenever Cipi appears.
- Attach canonical playroom directly.
- Attach approved learning derivative directly for learning shots.
- Use the storyboard shot specification as the action authority.
- Use QA rules as rejection authority.

### Never
- Ask Gemini to “remember Rere”.
- Use a previous generated image as the sole identity reference.
- Use legacy 18-shot prompts.
- Use old brand wording “Rere dan Kelinci Pink”.
- Generate a new Pink Bunny design for Cipi.
- Let Gemini invent a learning object that is already defined as a BUILD asset.
- Use an unapproved output as a canonical reference.

---

# 8. PRODUCTION GATE

RESET 05 is considered **REFERENCE-MAP COMPLETE** when:

- [x] Canonical Rere source paths identified
- [x] Canonical Cipi/Pink Bunny source identified
- [x] Canonical playroom source identified
- [x] Recurring EP001 prop paths identified
- [x] Six EP001 learning dependencies identified
- [x] S01–S12 attachment map defined
- [x] Cipi presence policy defined
- [x] Legacy prompt excluded
- [ ] Six EP001 learning assets generated
- [ ] Six EP001 learning assets human-QA approved
- [ ] Gemini scene generation unlocked

The final three items are downstream production gates, not part of the reference-map document itself.

**RESET 05 output:** clean reference map only.  
**Next reset:** RESET 06 — Reset Gemini production session.
