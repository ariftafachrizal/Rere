# RERE — PRODUCTION CONTROL MASTER V02

**Status:** ACTIVE / CANONICAL  
**Date:** 2026-09-14  
**Scope:** EP001–EP120

## 1. Operating model

**GitHub = Source of Truth.**  
**Todoist = Execution Queue.**

Todoist should contain only actionable execution cards. Detailed learning, storyboard, asset and prompt specifications remain in GitHub.

## 2. Mandatory execution order

1. `00 — START HERE`
2. `01 — EP001 PILOT`
3. `02 — EP002–EP006`
4. `03 — EP007–EP036`
5. `04 — EP037–EP060`
6. `05 — EP061–EP084`
7. `06 — EP085–EP108`
8. `07 — EP109–EP120`
9. `08 — QA & RELEASE`

Do not skip ahead merely because pre-production is ready.

## 3. Canonical resources

### Character
- `docs/CHARACTER-BIBLE-RERE.md`
- `assets/character/rere-character-sheet-canonical.png`
- `assets/character/rere-expression-sheet-canonical.png`
- `assets/character/rere-turnaround-sheet-canonical.png`

### Props / assets
- `docs/PROP-BIBLE-RERE.md`
- `docs/CANONICAL-ASSET-REGISTRY.md`
- `assets/props/...`

### World
- `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md`
- `assets/environment/...`

### Learning / content metadata
- `docs/RERE-EPISODE-CURRICULUM-EP001-EP120-V01.md`
- `docs/RERE-CONTENT-PACK-EP001-V01.md`
- `docs/RERE-CONTENT-PACK-EP002-EP006-V01.md`
- `docs/RERE-CONTENT-PACK-EP007-EP036-V01.md`
- `docs/RERE-CONTENT-PACK-EP037-EP060-V01.md`
- `docs/RERE-CONTENT-PACK-EP061-EP084-V01.md`
- `docs/RERE-CONTENT-PACK-EP085-EP108-V01.md`
- `docs/RERE-CONTENT-PACK-EP109-EP120-V01.md`

### Gemini
- `docs/BATCH-001-PROMPT-ARCHITECTURE-V01.md`
- `docs/BATCH-001-GEMINI-PROMPT-PACK-V01.md`
- `docs/BATCH-001-SHOT-PROMPTS-V01.md`
- `docs/RERE-GEMINI-RESOURCE-MANIFEST-EP001-EP120-V01.md`

### QA / Shorts
- `docs/BATCH-001-QA-SYSTEM-V01.md`
- `docs/BATCH-001-SHORTS-MASTER-V01.md`
- relevant episode Shorts pack

## 4. Production card contract

Every Todoist episode card must contain:

- YouTube title
- content description
- hashtags
- pillar
- learning promise
- content metadata path
- storyboard / pre-production path
- Gemini prompt source
- Gemini resource manifest
- canonical character path
- canonical prop/asset path
- canonical world path
- QA path
- Shorts path
- explicit completion gate

## 5. Gemini reference order

**Character → Face/Anatomy → Outfit/Expression → World → Recurring Props → Learning Object → Storyboard Shot → Camera → Lighting → Motion → Scene → Negative → QA**

The canonical prompt scaffold and all resource links live in:

`docs/RERE-GEMINI-RESOURCE-MANIFEST-EP001-EP120-V01.md`

## 6. Batch map

| Order | Episodes | Pre-production | Content metadata |
|---|---|---|---|
| 1 | EP001 | EP001 dedicated production docs | `docs/RERE-CONTENT-PACK-EP001-V01.md` |
| 2 | EP002–EP006 | `docs/BATCH-EP002-EP006-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP002-EP006-V01.md` |
| 3 | EP007–EP036 | `docs/BATCH-EP007-EP036-AUTONOMOUS-PRODUCTION-PACK-V01.md` | `docs/RERE-CONTENT-PACK-EP007-EP036-V01.md` |
| 4 | EP037–EP060 | `docs/BATCH-EP037-EP060-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP037-EP060-V01.md` |
| 5 | EP061–EP084 | `docs/BATCH-EP061-EP084-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP061-EP084-V01.md` |
| 6 | EP085–EP108 | `docs/BATCH-EP085-EP108-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP085-EP108-V01.md` |
| 7 | EP109–EP120 | `docs/BATCH-EP109-EP120-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP109-EP120-V01.md` |

## 7. EP001 pilot gate

EP001 validates the entire production loop before scale:
- canonical identity consistency
- Gemini reference workflow
- visual quality and QA
- Indonesian voice/audio
- editing template
- Shorts derivation
- packaging
- time/cost
- final release workflow

## 8. Completion semantics

- **PRE-PRODUCTION READY:** specification exists.
- **IN PRODUCTION:** actual work has started.
- **QA:** actual output exists and is being inspected.
- **COMPLETE:** output exists, is saved, and passes QA.
- **BLOCKED:** dependency or P0/P1 issue prevents completion.

Documentation existing is never enough to mark production complete.
