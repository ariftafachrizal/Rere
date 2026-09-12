# RERE — BATCH 001 ASSET MAPPING & GEMINI SOURCE MATRIX V01

**Scope:** EP001–EP006  
**Audience:** ages 2–4  
**Status:** Production planning  
**Date:** 2026-09-12

## 1. SOURCE-OF-TRUTH RULE

Generation hierarchy:

**Identity → Face → Anatomy → Outfit → Gesture/Expression → World → Props → Camera → Lighting → Scene**

A generated scene is never a new canonical source by default. A generated asset becomes reusable only after human approval and registry/status update.

## 2. REQUIRED GEMINI REFERENCE ORDER

Use only the minimum relevant references for each generation:

1. Rere canonical character sheet — mandatory whenever Rere appears.
2. Face/expression sheet — mandatory for face close-ups or expression-sensitive shots.
3. Canonical outfit — mandatory when wardrobe visibility matters.
4. Canonical world/location sheet — mandatory for environment continuity.
5. Canonical recurring prop — mandatory when a recurring prop appears.
6. Approved learning-object reference — mandatory for learning objects.
7. Storyboard shot specification — prompt text, not necessarily an uploaded image.

Never attach unrelated reference variants merely to provide more examples.

## 3. SHARED REFERENCE PACKAGE

### Character
- `RERE-CHARACTER-CANONICAL`
- `RERE-FACE-EXPRESSION-CANONICAL`
- `RERE-OUTFIT-REGULAR-CANONICAL`

### World
- `RERE-WORLD-PLAYROOM-01`
- Other locations only when an episode explicitly requires them.

### Recurring props
- `RERE-PROP-PINK-BUNNY-01`
- `RERE-PROP-BACKPACK-01`
- `RERE-PROP-BOOK-01`
- `RERE-PROP-CRAYON-KIT-01`
- `RERE-PROP-LEARNING-BOX-01`

### Learning libraries
- Color sheet
- Shape sheet
- Numeracy sheet
- Matching sheet
- Body vocabulary sheet
- Routine/sorting sheet

## 4. EP001 — WARNA

**Canonical sources:** character + face + regular outfit + playroom.  
**New/required learning assets:** red apple, yellow banana, blue ball, green plant/leaf, pink flower, quiz object set.

| Shot | Main source set | Gemini output | Acceptance |
|---|---|---|---|
| S01 | Character + outfit + playroom | opening scene | identity/world locked |
| S02 | Character + playroom + crayon kit | drawing hook | hand/prop interaction clear |
| S03 | Character + playroom + red apple | red learning scene | apple unmistakably red |
| S04 | Character + playroom + banana | yellow learning scene | banana unmistakably yellow |
| S05 | Character + playroom + ball | blue learning scene | ball unmistakably blue |
| S06 | Character + playroom + plant | green learning scene | leaf/plant unmistakably green |
| S07 | Character + playroom + flower | pink learning scene | flower unmistakably pink |
| S08 | Character + five learning objects | quiz | only intended answer is plausible |
| S09 | Character + crayon kit + learning book | drawing/review | five-color continuity |
| S10–S12 | character + playroom + recurring props | achievement/closing | canonical identity |

## 5. EP002 — BENTUK

**Canonical sources:** character + face + outfit + playroom + shape learning sheet.

Required derivatives: clean circle, square, triangle learning objects/cards; one familiar contextual object per shape if needed.

| Shot | Source set | Output |
|---|---|---|
| S01–S02 | Character + playroom | mission/setup |
| S03 | Character + circle reference | circle teaching shot |
| S04 | Character + square reference | square teaching shot |
| S05 | Character + triangle reference | triangle teaching shot |
| S06 | Character + three shape references | matching shot |
| S07 | Character + shape set + crayons/book | create shot |
| S08–S09 | Character + playroom | review/closing |

## 6. EP003 — ANGKA 1–5

**Canonical sources:** character + face + outfit + playroom + numeracy sheet.

Required derivatives: five identical child-scale countable toys and optional number cards 1–5.

Critical invariant: each shot's object count must be exact and auditable. Do not let background props become countable distractors.

## 7. EP004 — COCOKKAN

**Canonical sources:** character + face + outfit + playroom + matching sheet.

Required derivatives: three unmistakable identical pairs. Keep distractors visually distinct. One matching rule per shot.

Critical invariant: only one answer should be visually defensible for a preschool child.

## 8. EP005 — BAGIAN TUBUH

**Canonical sources:** character + face/expression + outfit + safe mirror environment.

Required derivatives: body vocabulary visual reference if needed. No medical/clinical imagery.

Critical invariant: eyes, nose, mouth, hands and feet must remain anatomically correct and easy to point to.

## 9. EP006 — MERAPIKAN MAINAN

**Canonical sources:** character + face + outfit + playroom + recurring props + routine/sorting sheet.

Required derivatives: two stable storage destinations, small ball set, small block set.

Critical invariant: object-to-destination mapping stays unchanged throughout the episode and the room becomes visibly organized through actual actions.

## 10. UNIVERSAL GEMINI NEGATIVE PROMPT

> Do not redesign the canonical character, face, anatomy, hairstyle, outfit, recurring props, or environment. No adult proportions. No character age change. No extra fingers, limbs, eyes, facial features, or malformed hands. No photorealism. No scary or uncanny expression. No random logos, watermarks, text artifacts, or typography unless explicitly requested. No random props. No environment layout drift. No inconsistent object geometry. No excessive clutter. No overstimulating visual effects. No dramatic cinematic action. Preserve preschool scale, soft rounded 3D CGI/kawaii visual language, warm child-safe mood, clear learning focal point, and canonical continuity.

## 11. HUMAN APPROVAL GATE

For every generated asset/scene:

1. Identity match.
2. Face/anatomy match.
3. Outfit match.
4. World continuity.
5. Prop continuity.
6. Learning-object correctness.
7. Camera clarity.
8. Lighting/color continuity.
9. Child action clarity.
10. No unintended ambiguity.

If any critical criterion fails: **REJECT → return to canonical source → regenerate.**

## 12. OUTPUT NAMING

`RERE-EP###-S##-[ASSET|SCENE]-[NAME]-V##`

Examples:
- `RERE-EP002-S03-ASSET-SHAPE-CIRCLE-V01`
- `RERE-EP002-S03-SCENE-V01`
- `RERE-EP006-S05-SCENE-V02`

Approved reusable derivatives must be registered before being reused in another episode.
