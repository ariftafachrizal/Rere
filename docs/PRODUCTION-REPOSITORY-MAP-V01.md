# RERE — PRODUCTION REPOSITORY MAP

**Version:** 1.0  
**Status:** Production Standard  
**Date:** 2026-09-12

## 1. Purpose

This document defines where production artifacts belong so that a growing episode library remains searchable and maintainable.

## 2. Repository Architecture

```text
Rere/
├── README.md
├── docs/
│   ├── brand/
│   ├── character/
│   ├── world/
│   ├── props/
│   ├── camera/
│   ├── lighting/
│   ├── voice/
│   ├── audio/
│   ├── editing/
│   ├── packaging/
│   ├── episodes/
│   ├── batches/
│   └── qa/
│
├── assets/
│   ├── character/
│   ├── outfits/
│   ├── expressions/
│   ├── gestures/
│   ├── environment/
│   ├── props/
│   │   ├── signature/
│   │   ├── utility/
│   │   ├── learning/
│   │   └── master/
│   ├── audio/
│   ├── graphics/
│   └── packaging/
│
└── production/
    ├── batch-001/
    │   ├── references/
    │   ├── episodes/
    │   ├── voice/
    │   ├── audio/
    │   ├── edit/
    │   ├── qa/
    │   └── packaging/
    └── batch-002/
```

## 3. Documentation vs Binary Assets

### `docs/`

Use for:

- Bibles
- decisions
- scripts
- storyboards
- asset maps
- prompt packs
- QA records
- production trackers
- batch plans

### `assets/`

Use for approved visual/audio source assets.

### `production/`

Use for working episode outputs, candidate generations, review exports, and temporary production material.

Do not treat a working candidate as canonical.

## 4. Canonical Asset Paths

Character:

`assets/character/`

World:

`assets/environment/`

Signature props:

`assets/props/signature/`

Utility props:

`assets/props/utility/`

Learning props:

`assets/props/learning/`

Master sheets:

`assets/props/master/`

## 5. Episode Documentation Naming

Use:

`docs/episodes/EPISODE-[###]-[DOCUMENT]-V##.md`

Examples:

- `EPISODE-001-OBJECTIVE-V01.md`
- `EPISODE-001-SCRIPT-V01.md`
- `EPISODE-001-STORYBOARD-V01.md`
- `EPISODE-001-ASSET-MAP-V01.md`
- `EPISODE-001-GEMINI-PROMPTS-V01.md`
- `EPISODE-001-QA-V01.md`
- `EPISODE-001-PACKAGING-V01.md`

Existing Episode 001 documents may remain at the current root `docs/` location until a deliberate repository reorganization is approved.

## 6. Batch Documentation Naming

Use:

`docs/batches/BATCH-[###]-[DOCUMENT]-V##.md`

Examples:

- `BATCH-001-SLATE-V01.md`
- `BATCH-001-ASSET-MATRIX-V01.md`
- `BATCH-001-TRACKER-V01.md`
- `BATCH-001-QA-V01.md`

## 7. Working Asset Naming

Scene candidate:

`RERE-EP001-S04-CANDIDATE-01`

Approved scene:

`RERE-EP001-S04-APPROVED-V01`

Review export:

`RERE-EP001-EDIT-REVIEW-V01`

Final master:

`RERE-EP001-FINAL-V01`

## 8. Never Mix These Categories

Do not place:

- raw candidates in canonical folders
- temporary edits in canonical folders
- screenshots as canonical assets
- scene renders as character masters
- episode-specific props in signature folders without approval

## 9. Archive Strategy

When an approved version is superseded:

- retain the old version where practical
- mark it DEPRECATED
- document the replacement
- update references
- do not silently delete the history

## 10. Repository Health Check

Before each batch freeze:

- [ ] canonical paths valid
- [ ] no duplicate canonical names
- [ ] no candidate in canonical folder
- [ ] all new assets have IDs
- [ ] all episode docs have versions
- [ ] asset registry updated
- [ ] production tracker updated

## 11. Binary Availability Rule

A documented filename is not sufficient evidence that the binary exists.

Before production, verify the actual file at its expected repository path.

If binary upload is unavailable through the connected GitHub workflow, keep the documentation accurate by marking the asset as pending binary ingestion rather than pretending it is hosted.
