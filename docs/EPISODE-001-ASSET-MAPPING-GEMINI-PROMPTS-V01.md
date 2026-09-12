# RERE EPISODE 001 — ASSET MAPPING & GEMINI SCENE PROMPTS V01

**Episode ID:** `RERE-EP-001`  
**Status:** GATE 04 — PRODUCTION PROMPTS READY  
**Date:** 2026-09-12  
**Target:** 2–4 tahun  
**Format:** 16:9 landscape  

## 1. Production Rule

This document is the bridge between the locked storyboard and scene generation.

**Canonical Master → Approved Derivative → Scene Prompt → Generation → Human Review**

Gemini must not redesign canonical character, recurring props, or canonical environments.

If an approved visual reference is unavailable to the generation tool, STOP and flag the missing asset rather than inventing a replacement.

## 2. Asset Status Legend

- **CANONICAL:** locked source of truth.
- **APPROVED:** design approved; binary reference may still need to be supplied to Gemini.
- **GENERATED:** scene-specific output; never promoted to canonical automatically.
- **OPTIONAL:** may be omitted without changing learning objective.

## 3. Shot-to-Asset Map

| Shot | Character | World | Primary Props | Secondary Props | Required Reference |
|---|---|---|---|---|---|
| 01 | RERE-CHAR-01 | PLAYROOM-01 | — | optional bunny | Rere master + playroom |
| 02 | RERE-CHAR-01 | PLAYROOM-01 | BOOK-01, CRAYON-KIT-01 | bunny, backpack | Rere + playroom + props |
| 03 | RERE-CHAR-01 | PLAYROOM-01 | — | — | Rere + playroom |
| 04 | RERE-CHAR-01 | PLAYROOM-01 | RED APPLE | BOOK-01 | Rere + playroom + apple |
| 05 | RERE-CHAR-01 | PLAYROOM-01 | YELLOW BANANA | — | Rere + playroom + banana |
| 06 | RERE-CHAR-01 | PLAYROOM-01 | BLUE BALL | — | Rere + playroom + ball |
| 07 | RERE-CHAR-01 | PLAYROOM-01 | GREEN PLANT/LEAF | — | Rere + playroom + plant |
| 08 | RERE-CHAR-01 | PLAYROOM-01 | PINK FLOWER | optional heart motif | Rere + playroom + flower |
| 09 | RERE-CHAR-01 | PLAYROOM-01 | QUIZ OBJECT SET | — | Rere + playroom + quiz set |
| 10 | RERE-CHAR-01 | PLAYROOM-01 | BOOK-01, CRAYON-KIT-01 | bunny | Rere + playroom + props |
| 11 | RERE-CHAR-01 | PLAYROOM-01 | finished drawing | — | Rere + playroom + drawing |
| 12 | RERE-CHAR-01 | PLAYROOM-01 | — | optional recurring props | Rere + playroom |

## 4. Universal Gemini Anchor

Paste this before every scene-specific prompt:

> Create a polished preschool 3D CGI scene in the established Rere universe. Rere is the same recurring canonical character across all episodes: cheerful preschool girl, warm friendly expression, brown eyes, curled eyelashes, distinctive small smiling lips, prominent but child-proportional nose, one high fountain ponytail, canonical pink bow, canonical proportions and canonical outfit. Use the supplied canonical Rere reference as the identity source of truth. Use the supplied canonical Rere playroom reference as the environment source of truth. Preserve architecture, furniture placement, scale, palette relationships, and lighting direction. Use supplied canonical prop references exactly when applicable. Soft pastel 3D kawaii aesthetic, rounded forms, tactile child-safe materials, warm diffused daylight, gentle shadows, clean composition, clear focal point, preschool scale, emotionally warm, non-scary, non-overstimulating. Camera should feel close to a child's perspective with natural perspective and gentle depth of field. No redesign of canonical assets.

## 5. Universal Negative Prompt

> Do not change Rere's face, eye color, eye shape, eyelashes, nose, lips, hairstyle, ponytail position, hair color, body proportions, age appearance, outfit, bow, or skin tone. No alternate character. No extra child. No adult proportions. No realistic human photography. No anime redesign. No exaggerated facial features. No duplicate Rere. No extra fingers or malformed hands. No deformed limbs. No floating objects. No warped props. No inconsistent scale. No environment redesign. No pink-everything palette. No harsh shadows. No dramatic cinematic lighting. No flashing lights. No horror, danger, sadness, aggression, clutter, visual noise, excessive bloom, extreme wide-angle distortion, rapid-motion implication, text artifacts, logos, watermarks, random typography.

## 6. Scene Prompts

### SHOT 01 — Signature Opening

**Reference assets:** Rere canonical + Playroom canonical.

> Medium shot transitioning gently toward medium close-up. Rere stands/sits in the established playroom facing the camera, warm smile, gentle one-hand wave, relaxed shoulders, direct friendly eye contact. Leave clean visual space around her face. The playroom is recognizable but secondary. Soft warm daylight, gentle contact shadows, natural child-perspective camera, subtle depth of field. Visual emotion: welcoming and safe. No learning props need to dominate this shot.

**Motion:** gentle wave only.  
**Do not generate title text inside image.**

### SHOT 02 — Drawing Hook

**Reference assets:** Rere + Playroom + Learning Book + Crayon Kit.

> Medium-wide preschool playroom composition. Rere sits naturally at the canonical child-scale table with the canonical learning book open in front of her and canonical crayon kit nearby. Start with enough environment to establish the room, then attention naturally falls on the blank page and colorful crayons. Rere looks excited and curious, then looks toward the crayons. Keep bunny/backpack as subtle continuity anchors only if they do not clutter the frame. Warm daylight, clean focal hierarchy.

### SHOT 03 — Short CTA

**Reference assets:** Rere + Playroom.

> Medium close-up. Rere looks directly at the camera with a brief cheerful invitation, friendly smile, open body language, minimal gesture. Background playroom softly defocused. Keep face highly readable. Reserve lower safe area for editorial subscribe overlay; do not generate any text or UI inside the image.

### SHOT 04 — Red Apple

**Reference assets:** Rere + Playroom + approved red apple.

> Rere discovers a clearly visible red apple in the canonical playroom. Begin in medium shot with Rere noticing it, then use a clean close-up/reframe where the apple occupies a clear focal position while Rere remains readable. Rere gently picks up or points to the apple. The apple must be unmistakably red. During the question pause, hold the apple steady and visually isolated enough for a toddler to inspect. Friendly curiosity, warm daylight, no competing red objects near the focal area.

**Learning word:** MERAH.

### SHOT 05 — Yellow Banana

**Reference assets:** Rere + Playroom + approved yellow banana.

> Match the previous learning-shot geography and visual language. Rere discovers a single clearly visible yellow banana, points to or gently holds it, then looks toward camera as if asking the child a question. During PAUSE, banana remains stable, large and visually isolated. Yellow must read clearly against the playroom palette. Keep Rere expression curious and patient.

**Learning word:** KUNING.

### SHOT 06 — Blue Ball

**Reference assets:** Rere + Playroom + approved blue ball.

> Rere discovers a single clearly visible blue ball. Medium learning composition with Rere and ball, followed by a clean close-up/reframe of the ball. Rere gently rolls the ball once. During PAUSE, ball is stationary and clearly visible. Blue must be unmistakable. Motion remains gentle and preschool-safe. No other blue object competes for attention.

**Learning word:** BIRU.

### SHOT 07 — Green Plant

**Reference assets:** Rere + Playroom + approved green plant/leaf.

> Rere notices a small child-safe green plant in the canonical playroom and points gently toward a clearly visible green leaf. Keep the leaf large enough to read on a mobile screen. Rere looks from plant to camera, inviting participation. During PAUSE, hold the composition still. Green should contrast against the warm neutral playroom background.

**Learning word:** HIJAU.

### SHOT 08 — Pink Flower

**Reference assets:** Rere + Playroom + approved pink flower.

> Rere discovers a single beautiful but simple pink flower. Start with Rere's curious reaction, then clearly reveal the flower. Rere smiles warmly and forms the canonical two-hand heart gesture after revealing the answer. The flower is unmistakably pink but does not turn the whole environment pink. Soft sparkle-like visual feeling may be suggested through lighting, not excessive effects. Warm, affectionate, calm.

**Learning word:** PINK.

### SHOT 09 — Mini Quiz

**Reference assets:** Rere + Playroom + approved quiz object set.

> Create a toddler-friendly choice composition with exactly three large, clearly separated objects. Rere is visible as a guide but does not block the choices. For each quiz variant, one target-color object is clearly present while the other two are visually distinct. Use simple spatial separation and consistent object scale. Camera remains mostly static during the PAUSE. No arrows, text, checkmarks, or generated UI; editorial graphics are added later.

**Variants:** red target, yellow target, pink target.

### SHOT 10 — Create / Drawing

**Reference assets:** Rere + Playroom + Learning Book + Crayon Kit.

> Over-the-shoulder view shows Rere drawing on the canonical learning book. Then transition to a medium shot where Rere is visibly engaged in drawing. The page gradually contains simple childlike marks using red, yellow, blue, green and pink. Keep the five target colors clearly distinguishable. Avoid detailed adult artwork. Rere's hands must interact naturally with the crayons and page. Warm, calm, creative atmosphere.

### SHOT 11 — Achievement

**Reference assets:** Rere + Playroom + finished drawing.

> Medium close-up of Rere proudly presenting the completed simple colorful drawing toward camera. Rere smiles with quiet pride and warmth, not exaggerated excitement. The drawing clearly contains red, yellow, blue, green and pink. Keep Rere's canonical face and proportions unchanged. Background playroom remains continuous with previous shots.

### SHOT 12 — Signature Closing

**Reference assets:** Rere + Playroom.

> Medium shot transitioning gently to medium close-up. Rere faces camera with a warm smile, delivers the canonical closing, forms the two-hand heart gesture, then gives a gentle goodbye wave. Keep the composition stable and emotionally warm. Leave clean space for the editorial end card; do not generate text inside the image. Soft canonical closing lighting and restrained background activity.

## 7. Generation Protocol

For each shot:

1. Load canonical Rere reference.
2. Load canonical playroom reference.
3. Load only the required approved props.
4. Paste Universal Gemini Anchor.
5. Paste shot-specific prompt.
6. Paste Universal Negative Prompt.
7. Generate candidate(s).
8. Compare candidate against canonical identity and storyboard.
9. Reject any candidate with identity drift, prop drift, environment drift, or learning ambiguity.
10. Only approved candidates become scene assets.

## 8. Human Review Checklist

### Identity
- [ ] Rere face matches canonical.
- [ ] Hair/ponytail matches canonical.
- [ ] Outfit matches canonical.
- [ ] Body proportions match canonical.
- [ ] No duplicate or extra Rere.

### Environment
- [ ] Playroom architecture matches.
- [ ] Major furniture positions remain consistent.
- [ ] Lighting direction matches.
- [ ] Color palette remains Rere universe.

### Learning
- [ ] Target object is immediately readable.
- [ ] Target color is accurate.
- [ ] No competing focal object.
- [ ] Quiz choices are clearly separated.

### Safety / Quality
- [ ] Child-safe.
- [ ] No frightening imagery.
- [ ] No overstimulation.
- [ ] No malformed anatomy.
- [ ] No text artifacts.
- [ ] No watermark/logo generated by model.

## 9. Important Asset Gap

The following learning props were specified in the episode but must be supplied as approved visual references before scene generation:

- Red Apple
- Yellow Banana
- Blue Ball
- Green Plant/Leaf
- Pink Flower
- Quiz Object Set

These should be generated/approved as **learning-prop derivatives** using the Prop Bible visual language, not improvised separately inside each scene.

## 10. Gate 04 Status

**READY FOR CONTROLLED GENERATION**, conditional on supplying the missing learning-prop references listed above.

Next gate:

**Gate 05 — Learning Prop Derivatives + Scene Generation.**
