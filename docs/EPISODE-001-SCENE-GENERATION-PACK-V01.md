# RERE EPISODE 001 — SCENE GENERATION PACK V01

**Episode ID:** `RERE-EP-001`  
**Status:** GATE 06 — GENERATION CONTROL PACK  
**Date:** 2026-09-12

## 1. Generation Objective

Generate scene candidates for the 12 locked storyboard shots without changing any canonical identity, world, or learning-prop design.

The goal is not to create 12 beautiful unrelated images. The goal is to create **one coherent visual sequence** in which the same Rere, same playroom, and same learning-object language remain stable.

## 2. Required Input References

Before generation, the operator must load the highest-quality available references for:

1. Canonical Rere character sheet.
2. Canonical playroom environment.
3. Episode 001 learning-prop derivative sheet.
4. Individual approved learning props when the model benefits from closer reference.
5. Canonical recurring props only when visible in the shot.

If any required canonical reference is missing, do not invent a replacement and do not promote the generated substitute to canonical.

## 3. Batch Strategy

Do not generate all 12 shots as one uncontrolled request.

### Batch A — Identity / Environment Test

Generate Shots **01, 02, 03** first.

Acceptance target:
- Rere identity stable.
- Playroom stable.
- Camera language stable.
- Outfit and hair stable.

### Batch B — Learning Discovery

Generate Shots **04, 05, 06, 07, 08**.

Acceptance target:
- learning objects read immediately.
- five target colors remain accurate.
- Rere identity remains stable.
- object scale and interaction remain natural.

### Batch C — Participation / Create

Generate Shots **09, 10, 11**.

Acceptance target:
- quiz choices readable.
- child participation space preserved.
- drawing activity looks child-created rather than adult-designed.

### Batch D — Closing

Generate Shot **12**.

Acceptance target:
- closing pose/gesture consistent.
- stable emotional tone.
- clean end-card safe area.

## 4. Generation Order Within Each Batch

For each shot:

**Reference Load → Universal Anchor → Shot Prompt → Negative Prompt → Generate → Compare → Reject/Approve → Save Version**

Do not use a successful image from one shot as a replacement for the canonical Rere reference. It can be used only as a scene-continuity reference when explicitly useful.

## 5. File Naming

Use:

`RERE-EP-001-S01-V01-C01`

Where:
- `S01` = storyboard shot.
- `V01` = scene prompt version.
- `C01` = candidate number.

Approved scene:

`RERE-EP-001-S01-V01-APPROVED`

Rejected candidate:

`RERE-EP-001-S01-V01-REJECTED-C01`

## 6. Candidate Evaluation Score

Score each candidate 0–2 for each category:

| Category | 0 | 1 | 2 |
|---|---|---|---|
| Rere identity | wrong | minor drift | canonical |
| Face | wrong | slight drift | match |
| Hair/outfit | wrong | slight drift | match |
| Environment | wrong | partial | match |
| Prop | wrong | partial | match |
| Learning clarity | unclear | acceptable | immediate |
| Composition | poor | usable | strong |
| Camera | wrong | acceptable | storyboard match |
| Lighting | wrong | acceptable | continuity match |
| Anatomy/hands | broken | minor issue | clean |
| Safety | unsafe | concern | clean |
| Style | wrong | partial | Rere universe |

**Approval threshold:** minimum **22/24**, with **no zero** in Identity, Face, Environment, Learning Clarity, Safety, or Anatomy/Hands.

## 7. Mandatory Rejection Conditions

Reject immediately if:

- Rere looks like a different child.
- Face structure changes.
- Hair/ponytail changes.
- Outfit changes without story reason.
- Playroom architecture materially changes.
- A canonical prop changes design.
- Target color is ambiguous.
- Child anatomy is visibly malformed.
- Hands/fingers are unusable for interaction.
- Multiple accidental characters appear.
- Generated text/logos/watermarks appear.
- Lighting creates unsafe flashing/strobe-like visual language.
- Scene becomes visually noisy or overstimulating.

## 8. Shot Acceptance Notes

### S01
Identity test. No learning object required.

### S02
Book and crayon kit must match canonical derivatives. Blank page should remain visually simple.

### S03
Face readability is more important than environment detail. Leave clean editorial safe area.

### S04
Apple must be unmistakably red. The red learning cue must dominate.

### S05
Banana must be unmistakably yellow. Avoid yellow-heavy background competition.

### S06
Ball must be unmistakably blue. The single gentle roll is the only significant action.

### S07
Plant leaves must read green immediately. Avoid dense foliage.

### S08
Flower must read pink immediately. Preserve Rere's signature heart gesture.

### S09
Three-object quiz layouts must be static enough for a 3–5 second response window.

### S10
Drawing should look like preschool mark-making. Do not create a polished adult illustration.

### S11
Completed drawing must visibly include all five target colors.

### S12
Rere's two-hand heart and goodbye wave must remain clean and recognizable.

## 9. Continuity Ledger

After every approved shot, record:

- Rere screen position.
- Rere facing direction.
- table/furniture relationship.
- visible recurring props.
- learning-object position.
- camera side.
- light direction.
- relative scale.

The next shot must be checked against this ledger before approval.

## 10. Human Review Passes

### Pass 1 — Identity
Only character/environment/prop consistency.

### Pass 2 — Learning
Only target-object clarity and child participation.

### Pass 3 — Cinematic / Technical
Camera, composition, lighting, anatomy, artifacts.

### Pass 4 — Child-Centered
Ask whether a 2–4-year-old can understand what to look at and what to do without adult explanation.

## 11. Gate 06 Exit Criteria

Gate 06 is complete only when:

- [ ] Batch A approved.
- [ ] Batch B approved.
- [ ] Batch C approved.
- [ ] Batch D approved.
- [ ] continuity ledger complete.
- [ ] all approved scene candidates archived with version IDs.
- [ ] rejected candidates remain identifiable.
- [ ] no generated candidate has been silently promoted to canonical.

## 12. Next Gate

After scene visuals are approved:

**Gate 07 — Voice Recording / Generation + Dialogue Timing**

Then:

**Gate 08 — Audio Assembly → Gate 09 — Edit → Gate 10 — QA → Gate 11 — Packaging → Gate 12 — Publish.**
