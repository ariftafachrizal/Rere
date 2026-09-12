# RERE — BATCH PRODUCTION ASSET MATRIX

**Version:** 1.0  
**Status:** Production Planning Standard  
**Date:** 2026-09-12  
**Batch:** `RERE-BATCH-001`

## 1. Purpose

This matrix prevents duplicated generation and identifies what must exist before a multi-episode batch enters scene production.

## 2. Asset Classes

| Class | Examples | Lifecycle |
|---|---|---|
| Identity | Rere character sheets | canonical |
| Outfit | Regular / Muslimah | canonical variants |
| Expression | smile, curious, happy, thinking | approved derivative |
| Gesture | wave, point, heart, hold | approved derivative |
| World | Playroom, bedroom, etc. | canonical |
| Signature prop | Bunny, backpack, book, heart | canonical |
| Utility prop | crayons, bottle, pencil case | canonical |
| Learning prop | apple, banana, shapes, numbers | batch/episode derivative |
| Activity asset | drawing, matching set | episode derivative |
| Camera | shot presets | production standard |
| Lighting | mood/time presets | production standard |
| Voice | Rere voice identity | canonical production standard |
| Audio | music/SFX/ambience | canonical + derivatives |
| Graphics | subtitles, title cards | production standard |
| Packaging | thumbnail/title templates | production standard |

## 3. Existing Shared Assets

### Character

- `RERE-CHARACTER-01`
- character canonical sheets
- expression sheet
- turnaround sheet

### World

- `RERE-WORLD-PLAYROOM-01`
- 9 additional canonical locations

### Signature Props

- Pink Bunny
- Backpack
- Learning Book
- Pink Heart

### Utility Props

- Crayon Kit
- Water Bottle
- Pencil Case
- Learning Box
- Activity Apron

### Learning Libraries

- colors
- shapes
- numeracy
- literacy
- science/nature

## 4. Batch 001 Required Assets

| Asset | EP001 | EP002 | EP003 | EP004 | EP005 | EP006 | Build Strategy |
|---|:---:|:---:|:---:|:---:|:---:|:---:|---|
| Rere canonical | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | reuse |
| Playroom | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | reuse |
| Learning Book | ✓ | optional | optional | optional | — | optional | reuse |
| Crayon Kit | ✓ | optional | ✓ | optional | — | — | reuse |
| Pink Bunny | optional | optional | optional | optional | optional | ✓ | reuse |
| Apple | ✓ | — | — | optional | — | — | learning derivative |
| Banana | ✓ | — | — | optional | — | — | learning derivative |
| Blue Ball | ✓ | — | ✓ | optional | — | — | learning derivative |
| Green Plant | ✓ | — | — | — | — | — | learning derivative |
| Pink Flower | ✓ | — | — | — | — | — | learning derivative |
| Shape set | — | ✓ | — | ✓ | — | — | batch derivative |
| Number 1–5 set | — | — | ✓ | optional | — | — | batch derivative |
| Matching set | — | — | — | ✓ | — | — | batch derivative |
| Body-part cards | — | — | — | — | optional | — | optional derivative |
| Storage/sorting set | — | — | — | — | — | ✓ | derivative if needed |

## 5. Shared Asset Rule

If an asset appears in two or more episodes and is visually recognizable, prefer one canonical/batch-approved design.

Example:

If a blue ball appears in EP-001 and EP-003, do not generate two unrelated blue balls.

## 6. Learning Prop Derivative Rule

A learning prop derivative must have:

- clear silhouette
- simple material
- accurate target color/shape/quantity
- preschool scale
- no distracting decoration
- front/side/top reference where useful
- clean background reference
- consistent style with Rere universe

## 7. Asset Approval States

`REQUESTED`
→ `PROMPTED`
→ `GENERATED`
→ `REVIEW`
→ `REVISION`
→ `APPROVED`
→ `BATCH-LOCKED`

Only `APPROVED` or `BATCH-LOCKED` assets may enter final scene generation.

## 8. Asset Naming

Canonical:

`RERE-PROP-[NAME]-01`

Batch derivative:

`RERE-B001-LEARNING-[NAME]-01`

Episode-specific:

`RERE-EP001-ASSET-[NAME]-01`

Scene output:

`RERE-EP001-S04-V01`

## 9. Reference Package Structure

Recommended local production structure:

```text
production/
  batch-001/
    references/
      character/
      world/
      props/
      camera/
      lighting/
    episodes/
      ep-001/
      ep-002/
      ep-003/
      ep-004/
      ep-005/
      ep-006/
    voice/
    audio/
    edit/
    qa/
    packaging/
```

## 10. Pre-Generation Checklist

Before generating a scene:

- [ ] canonical Rere loaded
- [ ] correct outfit loaded
- [ ] expression/gesture reference loaded
- [ ] canonical world loaded
- [ ] all recurring props loaded
- [ ] learning prop approved
- [ ] camera preset selected
- [ ] lighting preset selected
- [ ] storyboard shot identified
- [ ] negative prompt loaded
- [ ] output naming defined

## 11. Batch-Level Asset QA

At the end of every asset batch:

- compare same prop across episodes
- compare Rere face across scenes
- compare playroom geometry
- compare scale relationships
- compare lighting
- compare palette

Do not judge assets only in isolation.

## 12. Asset Freeze

When a shared batch asset is approved:

> **FREEZE IT.**

Do not modify it because one episode happens to need a different pose, angle, or lighting.

Create a derivative scene use instead.

## 13. Binary Repository Rule

Documentation can be created through GitHub text APIs, but binary image availability must be verified separately.

A filename mentioned in a Bible is not proof that the binary file exists in the repository.

Never mark an image as repository-hosted canonical until its binary path has been verified.
