# RERE EP001 — SHOT QUEUE V01

**Episode:** RERE-EP-001 — Petualangan Warna  
**Storyboard authority:** docs/EPISODE-001-STORYBOARD-PRODUCTION-MASTER-V03.md at commit ebd822e4d82ded6d98f9fd9243318065e6f91d6f  
**Reference authority:** docs/RERE-EP001-CLEAN-ASSET-GEMINI-REFERENCE-MAP-V01.md  
**Session authority:** docs/RERE-GEMINI-CLEAN-PRODUCTION-SESSION-EP001-V01.md  
**Learning gate:** PASSED / LOCKED  
**Scene production:** UNLOCKED  
**Status:** READY FOR S01 KEYFRAME

## 1. Production Rule

Generate one shot at a time.

Pipeline:

Canonical References → Approved Learning Asset → Keyframe → Human QA → Motion → Human QA

Do not batch-generate S01–S12.

A rejected candidate is never overwritten; increment the version.

## 2. Global Reference Priority

1. Canonical Rere
2. Expression / turnaround / outfit reference when relevant
3. Canonical Cipi when present
4. Canonical playroom
5. Canonical recurring props
6. Locked EP001 learning asset
7. This shot queue
8. Approved previous shot/keyframe only for continuity/state, never identity

## 3. Shot Queue

| Shot | Function | Duration | Required references | Learning asset | Motion |
|---|---|---:|---|---|---|
| S01 | Signature Opening | 10–12s | Rere + expression + Cipi + playroom | — | 1–2 |
| S02 | Drawing Hook | 12s | Rere + playroom + Learning Book + Crayon Kit | — | 1–2 |
| S03 | Short CTA | 7s | Rere + playroom | — | 0–1 |
| S04 | Red / Apple | 17s | Rere + playroom + Red Apple | RERE-EP001-ASSET-RED-APPLE-V01.png | 1–2 |
| S05 | Yellow / Banana | 17s | Rere + playroom + Yellow Banana | RERE-EP001-ASSET-YELLOW-BANANA-V01.png | 1–2 |
| S06 | Blue / Ball | 17s | Rere + playroom + Blue Ball | RERE-EP001-ASSET-BLUE-BALL-V01.png | 2 |
| S07 | Green / Plant | 17s | Rere + playroom + Green Plant | RERE-EP001-ASSET-GREEN-PLANT-V01.png | 1 |
| S08 | Pink / Flower | 18s | Rere + playroom + Pink Flower | RERE-EP001-ASSET-PINK-FLOWER-V01.png | 1 |
| S09 | Mini Quiz | ~33s | Rere + playroom + Quiz Set | RERE-EP001-ASSET-QUIZ-SET-V01.png | 0–1 |
| S10 | Create / Drawing | ~35s | Rere + playroom + Learning Book + Crayon Kit | five locked color assets as visual references | 1–2 |
| S11 | Achievement / Review | 15s | Rere + playroom + approved S10 drawing state | — | 1 |
| S12 | Signature Closing | 20–25s | Rere + expression + Cipi + playroom | — | 1 |

## 4. Shot-Specific Controls

### S01 — Signature Opening
- Rere + Cipi clearly visible.
- Rere faces camera, smiles, waves, then opens hands invitingly.
- Cipi remains secondary.
- No learning objects.
- Camera: child-height, gentle.
- Keyframe: RERE-EP001-S01-KEYFRAME-V01.png

### S02 — Drawing Hook
- Same playroom geography as S01.
- Rere moves to child-scale learning table.
- Learning Book open; Crayon Kit visible.
- Cipi optional/secondary.
- No random stationery.
- Keyframe: RERE-EP001-S02-KEYFRAME-V01.png

### S03 — Short CTA
- Rere-led MCU.
- Leave safe negative space for editorial CTA.
- Never generate “subscribe” typography inside image.
- Keyframe: RERE-EP001-S03-KEYFRAME-V01.png

### S04 — Red / Apple
- One approved Red Apple only.
- Rere holds apple clearly at chest height.
- 4-second question pause.
- No answer-revealing pointing/highlight.
- Apple remains unmistakably red.
- Keyframe: RERE-EP001-S04-KEYFRAME-V01.png

### S05 — Yellow / Banana
- Preserve S04 room geography.
- One approved Yellow Banana only.
- Resolve apple state before banana becomes focal.
- 4-second pause; no answer leakage.
- Keyframe: RERE-EP001-S05-KEYFRAME-V01.png

### S06 — Blue / Ball
- One approved Blue Ball only.
- One gentle roll, then ball becomes completely still.
- 4-second pause.
- No competing blue target.
- Keyframe: RERE-EP001-S06-KEYFRAME-V01.png

### S07 — Green / Plant
- Approved Green Plant only.
- One prominent green leaf as focal point.
- No dense foliage or competing green targets.
- 4-second pause.
- Keyframe: RERE-EP001-S07-KEYFRAME-V01.png

### S08 — Pink / Flower
- One approved Pink Flower only.
- Pink clearly dominant; stem/leaves secondary.
- 4-second pause.
- After reveal, Rere may perform canonical two-hand heart.
- Keyframe: RERE-EP001-S08-KEYFRAME-V01.png

### S09 — Mini Quiz
- Use approved Quiz Set as visual continuity authority.
- Present one question at a time.
- Quiz targets: red, yellow, pink.
- Each response window: 4 seconds.
- One plausible answer per question.
- Rere must not block choices or signal answer.
- No pre-answer highlight/glow/checkmark/pointer.
- Keyframe: RERE-EP001-S09-KEYFRAME-V01.png

### S10 — Create / Drawing
- Canonical Learning Book + Crayon Kit.
- Physical crayon-to-paper interaction must be believable.
- All five target colors visibly used.
- No random text/letters.
- Finished drawing becomes the locked S11 continuity state.
- Keyframe: RERE-EP001-S10-KEYFRAME-V01.png

### S11 — Achievement / Review
- Use the actual approved S10 finished drawing state.
- Rere presents drawing without covering important color areas.
- Warm, proud, calm expression.
- No new learning object or environment.
- Keyframe: RERE-EP001-S11-KEYFRAME-V01.png

### S12 — Signature Closing
- Rere + Cipi required.
- Rere leads; Cipi secondary.
- Two-hand heart → relaxed hold → gentle wave.
- Leave clean space for editorial end card.
- Never generate end-card typography.
- Keyframe: RERE-EP001-S12-KEYFRAME-V01.png

## 5. S01 Production Package

First shot to generate: S01.

Attach directly:
1. assets/character/rere-character-sheet-canonical.png
2. assets/character/rere-expression-sheet-canonical.png
3. assets/props/rere-pink-bunny-canonical.png.png
4. assets/props/rere-world-playroom-canonical.png

Optional only if needed:
- assets/character/rere-outfit-sheet-canonical.png

Do not attach:
- learning assets
- previous unapproved frames
- legacy 18-shot prompts
- old Pink Bunny variants

## 6. S01 Keyframe Acceptance

PASS only if:
- Rere identity is canonical.
- Cipi is the canonical Pink Bunny.
- Rere + Cipi are both clearly visible.
- Playroom architecture is consistent.
- Rere faces camera.
- Rere has a warm, natural smile.
- Wave/invitation pose is anatomically clean.
- Cipi remains secondary.
- No extra characters.
- No malformed hands/limbs.
- No text, logo, watermark or generated typography.
- Composition is child-height and uncluttered.
- Visual is suitable as the starting state for S01 motion.

If any P0/P1 defect appears: REJECT and generate V02.

## 7. Motion Gate

Do not generate S01 video until S01 keyframe passes Human QA.

After keyframe PASS:
RERE-EP001-S01-VIDEO-V01.mp4

Motion must be limited to:
- subtle settle
- gentle wave
- small invitation gesture
- natural facial micro-movement

No dramatic camera movement.

## 8. Downstream Order

S01 → S02 → S03 → S04 → S05 → S06 → S07 → S08 → S09 → S10 → S11 → S12

Each shot must pass Human QA before becoming a continuity reference for the next shot.

**Scene generation is now operationally unlocked, but production proceeds sequentially, one shot at a time.**
