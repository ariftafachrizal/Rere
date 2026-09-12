# Rere Prop Reference Assets

This directory contains the visual reference registry for Rere props.

## Directory Structure

```text
assets/props/
├── master/
│   └── rere-prop-master-sheet-canonical.png
├── signature/
│   ├── rere-pink-bunny-canonical.png
│   ├── rere-backpack-canonical.png
│   ├── rere-learning-book-canonical.png
│   └── rere-pink-heart-motif-canonical.png
├── utility/
│   ├── rere-crayon-kit-canonical.png
│   ├── rere-water-bottle-canonical.png
│   ├── rere-pencil-case-canonical.png
│   ├── rere-learning-box-canonical.png
│   └── rere-activity-apron-canonical.png
├── learning/
│   ├── rere-learning-colors-sheet-canonical.png
│   ├── rere-learning-shapes-sheet-canonical.png
│   ├── rere-learning-numeracy-sheet-canonical.png
│   ├── rere-learning-literacy-sheet-canonical.png
│   └── rere-learning-science-nature-sheet-canonical.png
└── environment/
    ├── rere-playroom-anchor-props-canonical.png
    ├── rere-bedroom-anchor-props-canonical.png
    ├── rere-kitchen-anchor-props-canonical.png
    ├── rere-garden-anchor-props-canonical.png
    └── rere-classroom-anchor-props-canonical.png
```

## Canonical Rule

`canonical` means the image has been explicitly approved as a visual source of truth.

A master sheet is an overview. An individual prop reference is authoritative for that prop.

For example:

- `master/rere-prop-master-sheet-canonical.png` = overview/alignment sheet
- `signature/rere-pink-bunny-canonical.png` = authoritative Pink Bunny identity

If the two ever conflict, the **individual canonical prop asset wins**, and the master sheet must be corrected.

## Tier A — Brand Signature

- `rere-pink-bunny-canonical.png`
- `rere-backpack-canonical.png`
- `rere-learning-book-canonical.png`
- `rere-pink-heart-motif-canonical.png`

## Tier B — Character Utility

- `rere-crayon-kit-canonical.png`
- `rere-water-bottle-canonical.png`
- `rere-pencil-case-canonical.png`
- `rere-learning-box-canonical.png`
- `rere-activity-apron-canonical.png`

## Learning Libraries

- `rere-learning-colors-sheet-canonical.png`
- `rere-learning-shapes-sheet-canonical.png`
- `rere-learning-numeracy-sheet-canonical.png`
- `rere-learning-literacy-sheet-canonical.png`
- `rere-learning-science-nature-sheet-canonical.png`

## Location Anchor Libraries

- `rere-playroom-anchor-props-canonical.png`
- `rere-bedroom-anchor-props-canonical.png`
- `rere-kitchen-anchor-props-canonical.png`
- `rere-garden-anchor-props-canonical.png`
- `rere-classroom-anchor-props-canonical.png`

## Draft Naming

Drafts should use:

- `draft-v01`
- `draft-v02`
- etc.

Drafts must never silently replace a canonical asset.

## Required Canonical Sheet Content

For recurring props, the individual canonical reference should ideally show:

- front view
- 3/4 view
- side view when needed
- back view when needed
- scale relative to Rere
- color/material reference
- close-up of signature details
- usage/interaction reference when useful

## Consistency Hierarchy

**Character Identity → Face → Anatomy → Outfit → Gesture/Expression → World → Prop → Scene**

For a specific prop:

**Prop Identity → Silhouette → Major Details → Material → Color → Scale → Scene Placement → Decoration**

## Binary Asset Note

The GitHub repository connector can document and verify binary asset paths, but binary movement/upload may require the repository's normal Git workflow when the connector cannot write binary content directly.

A path is only considered repository-hosted canonical when the actual binary exists at that exact path.

See:

- `docs/PROP-BIBLE-RERE.md`
- `docs/CANONICAL-ASSET-REGISTRY.md`
