# RERE — EPISODE 002 ASSET MAPPING + GEMINI REFERENCE V01

**Status:** PRE-PRODUCTION READY  
**Episode:** `RERE-EP-002`  
**Rule:** canonical source → episode derivative → scene. Never scene → new canonical.

## 1. Required Reference Hierarchy

Attach only the minimum relevant authoritative references in this order:
1. `RERE-CHAR-01` canonical Rere character sheet.
2. Face/expression reference when close facial framing is used.
3. Canonical regular outfit reference.
4. `RERE-WORLD-PLAYROOM-01` canonical playroom.
5. Canonical Shapes Learning Sheet.
6. Approved learning-shape object references/derivatives.
7. Shot-specific storyboard specification.

## 2. Asset Inventory

| Asset | Status | Use | Source of truth |
|---|---|---|---|
| Rere character | Canonical | S01–S09 | Character Bible / canonical sheet |
| Rere face/expression | Canonical | S03–S05, S08 | Character system |
| Regular outfit | Canonical | S01–S09 | Character system |
| Playroom | Canonical | S01–S09 | World Bible |
| Learning Book | Canonical, optional | S02/S07 if used | Prop Bible |
| Crayon Kit | Canonical, optional | S02/S07 if used | Prop Bible |
| Shapes Learning Sheet | Canonical | S02–S08 | Learning asset system |
| Circle | Episode learning derivative | S02/S03/S06/S07/S08 | Shape spec below |
| Square | Episode learning derivative | S02/S04/S06/S07/S08 | Shape spec below |
| Triangle | Episode learning derivative | S02/S05/S06/S07/S08 | Shape spec below |

## 3. Learning Shape Specifications

### Circle
- closed, round silhouette
- no text, face or decorative pattern
- consistent thickness/material with other shapes
- large enough for preschool recognition
- no oval distortion

### Square
- four equal visual sides
- four clear corners
- front-facing/low-perspective presentation when teaching geometry
- no rotation that turns it into an ambiguous diamond
- no text

### Triangle
- three clear sides and three corners
- simple upright orientation during first teaching
- no rounded corners that obscure the concept
- no text

## 4. Generation Policy

If approved canonical learning-shape assets already exist, reuse them. Generate a new derivative only if the required asset is genuinely missing. Once approved, freeze its visual identity for all subsequent EP002 shots and Shorts.

## 5. Shot Reference Matrix

| Shot | Character | World | Learning refs | Props | Special constraint |
|---|---|---|---|---|---|
| S01 | Rere | Playroom | none | none | canonical opening |
| S02 | Rere | Playroom | circle/square/triangle | Book/Crayon optional | three shapes readable |
| S03 | Rere | Playroom | circle | optional learning surface | no answer-giving gesture during pause |
| S04 | Rere | Playroom | square | optional learning surface | true square geometry |
| S05 | Rere | Playroom | triangle | optional learning surface | true three-sided geometry |
| S06 | Rere | Playroom | 3 matched pairs | none | one-to-one matching only |
| S07 | Rere | Playroom | circle/square/triangle | Book/Crayon optional | simple creation |
| S08 | Rere | Playroom | circle/square/triangle | none | recall only |
| S09 | Rere | Playroom | none | none | canonical closing |

## 6. Universal Gemini Anchor

“Use the attached canonical Rere references as the authoritative source of identity. Preserve the exact face structure, brown eyes, curled eyelashes, distinctive nose and small smiling lip shape, single high fountain ponytail, canonical preschool proportions, and approved regular outfit. Use the attached canonical playroom and approved shape references as authoritative. Do not redesign recurring assets. Render soft pastel 3D CGI/kawaii, warm, rounded, clean, child-safe and naturally playful. Preserve continuity with adjacent shots.”

## 7. Universal Negative

No character redesign, face drift, hairstyle drift, outfit drift, adult proportions, extra fingers/limbs/eyes, malformed hands, uncanny face, photorealism, scary mood, random props, environment drift, prop geometry inconsistency, ambiguous shapes, extra shape types, text artifacts, watermark/logo, clutter, excessive bloom, rapid camera movement, overstimulation.

## 8. Asset QA Gate

Reject before scene generation if canonical Rere/world references are missing. Reject learning objects if their geometry cannot be identified immediately by a 2–4-year-old. Reject any derivative that changes between shots. Human approval is required before reuse.
