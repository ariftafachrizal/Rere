# Rere — Prop Asset Status

**Status:** Production Visual Library — v1.0  
**Date:** 2026-09-12

This document records the visual prop assets approved during the canonical prop pass.

## Canonical consistency rule

Every recurring character and recurring prop has one identity. A master sheet, scene render, or illustrative image must not redefine that identity.

**Source Reference → Bible/Design Rules → Canonical Asset → Master Sheet → Individual Asset → Episode Scene**

## 1. Signature / Utility Props — Approved Visual Designs

The following individual prop designs have been reviewed and approved by the project owner:

| # | Prop ID | Asset | Approval |
|---|---|---|---|
| 1 | `RERE-PROP-PINK-BUNNY-01` | `assets/props/signature/rere-pink-bunny-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 2 | `RERE-PROP-BACKPACK-01` | `assets/props/signature/rere-backpack-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 3 | `RERE-PROP-BOOK-01` | `assets/props/signature/rere-learning-book-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 4 | `RERE-PROP-HEART-01` | `assets/props/signature/rere-pink-heart-motif-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 5 | `RERE-PROP-CRAYON-KIT-01` | `assets/props/utility/rere-crayon-kit-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 6 | `RERE-PROP-WATER-BOTTLE-01` | `assets/props/utility/rere-water-bottle-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 7 | `RERE-PROP-PENCIL-CASE-01` | `assets/props/utility/rere-pencil-case-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 8 | `RERE-PROP-LEARNING-BOX-01` | `assets/props/utility/rere-learning-box-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 9 | `RERE-PROP-ACTIVITY-APRON-01` | `assets/props/utility/rere-activity-apron-canonical.png` | **APPROVED / CANONICAL DESIGN** |

## 2. Learning Visual Libraries — Approved

| # | Asset | Approval |
|---|---|---|
| 1 | `assets/props/learning/rere-learning-colors-sheet-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 2 | `assets/props/learning/rere-learning-shapes-sheet-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 3 | `assets/props/learning/rere-learning-numeracy-sheet-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 4 | `assets/props/learning/rere-learning-literacy-sheet-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 5 | `assets/props/learning/rere-learning-science-nature-sheet-canonical.png` | **APPROVED / CANONICAL DESIGN** |

These sheets define the visual direction of the learning-object libraries. Individual teaching objects may vary by lesson, but must follow the Rere Prop DNA and must not be mistaken for recurring signature identities unless separately registered.

## 3. Location Anchor Prop Sheets — Approved

| # | Asset | Approval |
|---|---|---|
| 1 | `assets/props/environment/rere-playroom-anchor-props-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 2 | `assets/props/environment/rere-bedroom-anchor-props-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 3 | `assets/props/environment/rere-kitchen-anchor-props-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 4 | `assets/props/environment/rere-garden-anchor-props-canonical.png` | **APPROVED / CANONICAL DESIGN** |
| 5 | `assets/props/environment/rere-classroom-anchor-props-canonical.png` | **APPROVED / CANONICAL DESIGN** |

These sheets are environment-anchor references. They establish recurring set dressing and object language for each location; the complete environment itself remains governed by `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md` and its canonical environment assets.

## 4. Master Prop Sheet

Target location:

`assets/props/master/rere-prop-master-sheet-canonical.png`

The master sheet is an overview/reference alignment asset. It does **not** override the individual canonical prop assets above.

If an individual canonical prop is changed in the future, the master sheet must be regenerated or revised to match it.

## 5. Binary Repository Note

The GitHub text connector can maintain the documentation and registry, but binary PNG files generated or uploaded during the visual workflow may still need to be physically committed through the user's local Git workflow.

Therefore:

- **Approved / canonical design** = visual design has been reviewed and locked for production identity.
- **Repository-hosted canonical asset** = the exact binary PNG physically exists at the registered repository path.

Do not claim a PNG is repository-hosted until the binary is actually present at its path.

## 6. Golden Rule

> **Generate new stories, not new prop identities.**

Once a recurring prop is approved, future scenes must reference that identity rather than asking the generation model to invent a visually similar replacement.
