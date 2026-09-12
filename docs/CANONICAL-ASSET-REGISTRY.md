# Rere — Canonical Asset Registry

**Status:** Production Standard — v1.0  
**Date:** 2026-09-12  
**Purpose:** single source-of-truth registry for character, prop, world, and scene assets.

## 1. Core Rule

> **A canonical asset is an identity source of truth, not merely an example image.**

Every recurring character and recurring prop must have one explicit canonical reference. Episode images, screenshots, generated scene frames, and illustrative images inside Bibles are **not** canonical unless explicitly registered here.

The production chain is:

**Source Reference → Bible/Design Rules → Canonical Asset → Master Sheet → Individual Asset → Episode Scene**

Never reverse this chain by allowing a random episode generation to redefine the canonical identity.

## 2. Consistency Hierarchy

When references conflict, use this priority:

**Identity → Face → Anatomy → Outfit → Gesture/Expression → World → Props → Scene Details**

For prop-specific conflicts:

**Prop Identity → Silhouette → Major Details → Material → Color → Scale → Scene Placement → Decoration**

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

## 5. Prop Canonical Lock Status

Prop IDs are separate identity assets. A prop appearing in a character sheet does **not** automatically inherit canonical status.

### Tier A

| Prop ID | Asset | Status |
|---|---|---|
| `RERE-PROP-PINK-BUNNY-01` | `assets/props/signature/rere-pink-bunny-canonical.png` | Pending individual lock |
| `RERE-PROP-BACKPACK-01` | `assets/props/signature/rere-backpack-canonical.png` | Pending individual lock |
| `RERE-PROP-BOOK-01` | `assets/props/signature/rere-learning-book-canonical.png` | Pending individual lock |
| `RERE-PROP-HEART-01` | `assets/props/signature/rere-pink-heart-motif-canonical.png` | Pending individual lock |

### Tier B

| Prop ID | Asset | Status |
|---|---|---|
| `RERE-PROP-CRAYON-KIT-01` | `assets/props/utility/rere-crayon-kit-canonical.png` | Pending individual lock |
| `RERE-PROP-WATER-BOTTLE-01` | `assets/props/utility/rere-water-bottle-canonical.png` | Pending individual lock |
| `RERE-PROP-PENCIL-CASE-01` | `assets/props/utility/rere-pencil-case-canonical.png` | Pending individual lock |
| `RERE-PROP-LEARNING-BOX-01` | `assets/props/utility/rere-learning-box-canonical.png` | Pending individual lock |
| `RERE-PROP-ACTIVITY-APRON-01` | `assets/props/utility/rere-activity-apron-canonical.png` | Pending individual lock |

## 6. Master Sheet vs Individual Canonical Asset

A master sheet is an overview and alignment reference.

An individual canonical asset is the authoritative design for that specific object.

For example:

`rere-prop-master-sheet-canonical.png`

may show a Pink Bunny, but the authoritative Bunny identity is:

`rere-pink-bunny-canonical.png`

Once the individual Bunny is locked, future master sheets and scenes must derive from that individual reference.

## 7. Master Sheet Status

Current uploaded prop master sheet:

`assets/props/master/rere-prop-master-sheet-canonical.png`

**Important:** this path is the intended canonical location. The binary file must physically exist at that exact repository path before it is treated as repository-hosted canonical. If the current binary is still under `assets/props/`, move it without changing the file content/name.

The master sheet must be regenerated/revised if any Tier A prop is later canonically changed so that the visual overview matches the individual canonical assets.

## 8. Generation Rule

When generating a scene:

1. Load canonical Rere reference.
2. Load canonical outfit reference when needed.
3. Load canonical prop references for recurring props.
4. Load canonical world reference.
5. Generate the scene around those references.
6. QA the output against the references.

Do **not** ask the generation model to invent the recurring prop from text alone when a canonical visual reference exists.

## 9. No Silent Drift

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

Minor rendering differences caused by lighting, camera, pose, depth of field, or animation are acceptable if identity remains recognizable.

## 10. Version Change Protocol

If a canonical asset genuinely needs redesign:

1. mark the current asset as current canonical
2. create a candidate version
3. compare against the current canonical
4. document the reason
5. explicitly approve the new version
6. update this registry and the relevant Bible
7. preserve the previous version as deprecated/archive where practical
8. update affected master sheets and future prompts

Never overwrite a canonical identity silently.

## 11. Production QA Gate

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

## 12. Golden Rule

> **Generate new stories, not new identities.**

Rere may visit a new place, learn a new concept, wear an approved outfit variation, and interact with new objects—but Rere herself and every recurring canonical prop must remain recognizably the same.
