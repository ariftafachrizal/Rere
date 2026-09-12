# Rere — Canonical Asset Registry

**Status:** Production Standard — v1.1  
**Date:** 2026-09-12  
**Purpose:** single source-of-truth registry for character, prop, world, and scene assets.

## 1. Core Rule

> **A canonical asset is an identity source of truth, not merely an example image.**

Every recurring character, recurring prop, and recurring world location must have one explicit canonical reference. Episode images, screenshots, generated scene frames, and illustrative images inside Bibles are **not** canonical unless explicitly registered here.

The production chain is:

**Source Reference → Bible/Design Rules → Canonical Asset → Master Sheet → Individual Asset → Episode Scene**

Never reverse this chain by allowing a random episode generation to redefine canonical identity.

## 2. Consistency Hierarchy

When references conflict, use this priority:

**Identity → Face → Anatomy → Outfit → Gesture/Expression → World → Props → Scene Details**

For prop-specific conflicts:

**Prop Identity → Silhouette → Major Details → Material → Color → Scale → Scene Placement → Decoration**

For world-specific conflicts:

**World Identity → Architecture/Layout → Major Furniture → Anchor Props → Scale → Lighting → Decoration**

Scene prompts must not override a higher-level canonical reference.

## 3. Asset Status

### CANONICAL

Approved and locked as a visual source of truth. Production prompts should use this reference whenever the asset appears.

### DRAFT

Exploration only. May inform discussion but must not replace a canonical asset.

### DEPRECATED

Former canonical asset retained for history. Do not use for new production.

### ILLUSTRATIVE

Example artwork inside a document, storyboard, master sheet, or presentation. It does not automatically become canonical.

## 4. Batch 01 — Character Canonical Lock

**Character ID:** `RERE-CHARACTER-01`  
**Version:** `v1.0`  
**Status:** **CANONICAL / LOCKED**

### Canonical character references

- `assets/character/rere-character-sheet-canonical.png`
- `assets/character/rere-character-sheet-v02.png`
- `assets/character/rere-expression-sheet-canonical.png`
- `assets/character/rere-turnaround-sheet-canonical.png`

These references establish Rere's facial identity, anatomy/proportion, hair signature, expression language, and presentation modes. See `docs/CHARACTER-BIBLE-RERE.md`.

### Character identity lock

- female preschool character
- Rere — Si Pecinta Pink
- brown eyes
- curled eyelashes
- distinctive child facial identity
- dark hair
- Regular Rere: one high fountain ponytail
- Regular Rere: pink bow/hair accessory direction
- Muslimah Rere: canonical pink hijab + modest preschool styling
- child-appropriate proportions
- cheerful, friendly, curious personality

## 5. Prop Canonical Lock

Prop IDs are separate identity assets. A prop appearing in a character sheet does **not** automatically inherit canonical status.

### Tier A — Signature Props

| Prop ID | Asset | Status |
|---|---|---|
| `RERE-PROP-PINK-BUNNY-01` | `assets/props/signature/rere-pink-bunny-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-BACKPACK-01` | `assets/props/signature/rere-backpack-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-BOOK-01` | `assets/props/signature/rere-learning-book-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-HEART-01` | `assets/props/signature/rere-pink-heart-motif-canonical.png` | **CANONICAL / LOCKED** |

### Tier B — Character Utility

| Prop ID | Asset | Status |
|---|---|---|
| `RERE-PROP-CRAYON-KIT-01` | `assets/props/utility/rere-crayon-kit-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-WATER-BOTTLE-01` | `assets/props/utility/rere-water-bottle-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-PENCIL-CASE-01` | `assets/props/utility/rere-pencil-case-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-LEARNING-BOX-01` | `assets/props/utility/rere-learning-box-canonical.png` | **CANONICAL / LOCKED** |
| `RERE-PROP-ACTIVITY-APRON-01` | `assets/props/utility/rere-activity-apron-canonical.png` | **CANONICAL / LOCKED** |

### Learning Libraries

The following learning-object sheets are approved as current design references:

- `rere-learning-colors-sheet-canonical.png`
- `rere-learning-shapes-sheet-canonical.png`
- `rere-learning-numeracy-sheet-canonical.png`
- `rere-learning-literacy-sheet-canonical.png`
- `rere-learning-science-nature-sheet-canonical.png`

## 6. Master Sheet vs Individual Canonical Asset

A master sheet is an overview and alignment reference.

An individual canonical asset is the authoritative design for that specific object.

For example:

`rere-prop-master-sheet-canonical.png`

may show a Pink Bunny, but the authoritative Bunny identity is:

`rere-pink-bunny-canonical.png`

Once an individual asset is locked, future master sheets and scenes must derive from that individual reference.

## 7. Prop Master Sheet Status

Current intended master-sheet location:

`assets/props/master/rere-prop-master-sheet-canonical.png`

The binary must physically exist at that exact repository path before it is treated as repository-hosted canonical. If the current binary is still under `assets/props/`, move it without changing its content/name.

The master sheet must be regenerated/revised if a Tier A prop is later canonically changed so that the visual overview matches the individual canonical assets.

## 8. Batch 02 — World / Environment Canonical Lock

**Batch:** `BATCH-02`  
**Version:** `v1.0`  
**Status:** **APPROVED / LOCKED DESIGN DIRECTION**

The ten canonical world locations have completed the visual design pass and are approved as the current environment identity references.

| # | World ID | Location | Canonical Reference | Status |
|---|---|---|---|---|
| 01 | `RERE-WORLD-PLAYROOM-01` | Playroom | `rere-world-playroom-canonical.png` | **APPROVED / LOCKED** |
| 02 | `RERE-WORLD-BEDROOM-01` | Bedroom | `rere-world-bedroom-canonical.png` | **APPROVED / LOCKED** |
| 03 | `RERE-WORLD-KITCHEN-01` | Kitchen | `rere-world-kitchen-canonical.png` | **APPROVED / LOCKED** |
| 04 | `RERE-WORLD-GARDEN-01` | Garden | `rere-world-garden-canonical.png` | **APPROVED / LOCKED** |
| 05 | `RERE-WORLD-CLASSROOM-01` | Classroom | `rere-world-classroom-canonical.png` | **APPROVED / LOCKED** |
| 06 | `RERE-WORLD-OUTDOOR-PLAY-01` | Outdoor Play / Playground | `rere-world-outdoor-play-canonical.png` | **APPROVED / LOCKED** |
| 07 | `RERE-WORLD-COMMUNITY-01` | Community / Street | `rere-world-community-canonical.png` | **APPROVED / LOCKED** |
| 08 | `RERE-WORLD-MARKET-01` | Market / Shop | `rere-world-market-canonical.png` | **APPROVED / LOCKED** |
| 09 | `RERE-WORLD-NATURE-01` | Nature | `rere-world-nature-canonical.png` | **APPROVED / LOCKED** |
| 10 | `RERE-WORLD-IMAGINATION-01` | Imagination World | `rere-world-imagination-canonical.png` | **APPROVED / LOCKED** |

### World identity rules

- Rere remains the primary character focal point.
- Pink is a signature accent, not a requirement for every surface.
- Supporting colors keep the world livable and educationally readable.
- Architecture and major furniture must remain stable when a location recurs.
- Anchor props must remain consistent with the corresponding Prop Bible.
- Child-scale design is mandatory.
- Lighting and mood may vary for story/time-of-day purposes without redefining the location.
- Imagination World may be more magical, but Rere's identity remains canonical.

See `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md` and `docs/WORLD-ENVIRONMENT-ASSET-STATUS.md`.

## 9. Generation Rule

When generating a scene:

1. Load canonical Rere reference.
2. Load canonical outfit reference when needed.
3. Load canonical prop references for recurring props.
4. Load canonical world reference.
5. Generate the scene around those references.
6. QA the output against the references.

**Do not ask the generation model to invent a recurring character, prop, or world from text alone when a canonical visual reference exists.**

## 10. No Silent Drift

The following are considered identity drift:

- changed face structure
- changed eye shape/color
- changed hairstyle signature
- changed canonical hijab styling
- changed prop silhouette
- changed major prop markings
- changed prop material without reason
- changed prop color identity
- changed relative scale dramatically
- replacing a recurring prop with a visually similar but different object
- changing recurring world architecture/layout without a documented version change
- moving major furniture randomly
- changing world palette relationships so strongly that the location becomes unrecognizable

Minor rendering differences caused by lighting, camera, pose, depth of field, animation, or story dressing are acceptable if identity remains recognizable.

## 11. Version Change Protocol

If a canonical asset genuinely needs redesign:

1. identify the current canonical asset
2. create a candidate version
3. compare against the current canonical
4. document the reason
5. explicitly approve the new version
6. update this registry and the relevant Bible
7. preserve the previous version as deprecated/archive where practical
8. update affected master sheets and future prompts

Never overwrite a canonical identity silently.

## 12. Production QA Gate

Before an asset enters an episode:

- [ ] correct canonical character
- [ ] correct canonical prop
- [ ] correct canonical world
- [ ] correct outfit mode
- [ ] correct scale
- [ ] recognizable silhouette
- [ ] no accidental redesign
- [ ] no generic replacement
- [ ] no irrelevant decorative clutter
- [ ] scene still prioritizes learning/story intention

## 13. Golden Rule

> **Generate new stories, not new identities.**

Rere may visit a new place, learn a new concept, wear an approved outfit variation, and interact with new objects—but Rere herself, every recurring canonical prop, and every recurring canonical world must remain recognizably the same.
