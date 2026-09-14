# RERE — PRODUCTION CONTROL MASTER V01

**Status:** ACTIVE — canonical execution-control document  
**Scope:** EP001–EP120  
**Last control revision:** 2026-09-14  
**Purpose:** bridge the GitHub production system and Todoist so that Todoist remains an execution checklist while GitHub remains the source of truth.

## 1. Operating principle

**GitHub = Source of Truth.**  
**Todoist = Execution Queue.**

Todoist must never become a second, conflicting production specification. Every actionable Todoist task points to the relevant GitHub document.

The execution order is:

1. START HERE / CONTROL
2. EP001 PILOT — full production
3. EP002–EP006 — Batch 001 scale
4. EP007–EP036 — Foundation expansion
5. EP037–EP060 — Language / social-emotional / daily-life
6. EP061–EP084 — Nature / science / early reasoning
7. EP085–EP108 — Literacy / creativity / problem solving
8. EP109–EP120 — Integration / review
9. Cross-batch QA, packaging, publishing and learning review

Do not jump ahead simply because pre-production exists. Pre-production readiness means an episode is specified; production completion still requires actual outputs and QA.

## 2. Canonical resource hierarchy

### Character
- `docs/CHARACTER-BIBLE-RERE.md`
- `assets/character/rere-character-sheet-canonical.png`
- `assets/character/rere-expression-sheet-canonical.png`
- `assets/character/rere-turnaround-sheet-canonical.png`

### Props / assets
- `docs/PROP-BIBLE-RERE.md`
- `docs/CANONICAL-ASSET-REGISTRY.md`
- `assets/props/...`
- approved learning-object sheets under the registered asset paths

### World
- `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md`
- `docs/CANONICAL-ASSET-REGISTRY.md`
- `assets/environment/...`

### Learning / curriculum
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
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP001-V01.md`
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP002-EP006-V01.md`
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP007-EP036-V01.md`
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP037-EP060-V01.md`
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP061-EP084-V01.md`
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP085-EP108-V01.md`
- `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP109-EP120-V01.md`

### QA / Shorts
- `docs/BATCH-001-QA-SYSTEM-V01.md`
- `docs/BATCH-001-SHORTS-MASTER-V01.md`
- episode-specific Shorts packs where present

## 3. What a production task must contain

Every production-control task must answer:

**WHAT**
- exact episode/phase
- exact deliverable
- exact acceptance gate

**WHERE**
- content metadata path
- storyboard path
- Gemini prompt path
- character reference path
- prop/asset path
- world path
- QA path

**DONE WHEN**
- explicit output exists
- output is saved with agreed naming
- QA is passed
- next dependency is unblocked

For content/publishing tasks, the task description must also expose:
- YouTube title
- content description
- hashtags
- learning promise
- content pack path
- Gemini manifest path
- storyboard source
- canonical character
- props
- world
- QA
- Shorts source

## 4. EP001 pilot gate

EP001 is the production pilot.

Do not scale aggressively until these are validated:
- Rere identity consistency
- canonical props/world consistency
- Gemini reference workflow
- shot generation quality
- Indonesian voice identity
- pause timing
- editing template
- Shorts derivation
- thumbnail/title packaging
- production time and cost
- final QA workflow

## 5. Episode execution contract

### A. Content
Use the appropriate `RERE-CONTENT-PACK-*.md`.

### B. Pre-production verification
Verify:
- one learning promise
- locked script/sequence
- storyboard beats
- canonical asset references
- Gemini resource map
- QA acceptance criteria
- Shorts concepts

### C. Gemini
Use the corresponding `RERE-GEMINI-EXECUTION-MANIFEST-*.md`.
Attach canonical visual references in this order:

**Rere → expression/outfit → world → recurring props → learning object → storyboard shot spec**

Never generate a recurring identity from text alone when a canonical visual reference exists.

### D. Visual QA
Use `docs/BATCH-001-QA-SYSTEM-V01.md`.  
P0/P1 failures block completion.

### E. Audio
Use the batch voice/audio standards and preserve:
- exact canonical opening
- interaction pause
- answer reveal
- canonical closing
- music ducking
- child-friendly loudness

### F. Editing
Assemble 16:9 long-form first. Shorts are derivatives unless crop/reframe fails QA.

### G. Packaging
Create:
- title
- description
- hashtags
- thumbnail
- filename
- final metadata

### H. Release
Only release after final episode QA passes.

### I. Learning review
Record performance and learning observations before using them to revise future batches.

## 6. Batch map

| Execution order | Batch | Episodes | Canonical pre-production source | Content metadata | Gemini manifest |
|---|---|---|---|---|---|
| 1 | Pilot | EP001 | EP001 dedicated production docs | `docs/RERE-CONTENT-PACK-EP001-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP001-V01.md` |
| 2 | Batch 001 | EP002–EP006 | `docs/BATCH-EP002-EP006-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP002-EP006-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP002-EP006-V01.md` |
| 3 | Foundation | EP007–EP036 | `docs/BATCH-EP007-EP036-AUTONOMOUS-PRODUCTION-PACK-V01.md` | `docs/RERE-CONTENT-PACK-EP007-EP036-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP007-EP036-V01.md` |
| 4 | Language / FEEL / Life | EP037–EP060 | `docs/BATCH-EP037-EP060-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP037-EP060-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP037-EP060-V01.md` |
| 5 | Nature / Science | EP061–EP084 | `docs/BATCH-EP061-EP084-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP061-EP084-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP061-EP084-V01.md` |
| 6 | Literacy / Creativity | EP085–EP108 | `docs/BATCH-EP085-EP108-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP085-EP108-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP085-EP108-V01.md` |
| 7 | Integration | EP109–EP120 | `docs/BATCH-EP109-EP120-PREPRODUCTION-MASTER-V01.md` | `docs/RERE-CONTENT-PACK-EP109-EP120-V01.md` | `docs/RERE-GEMINI-EXECUTION-MANIFEST-EP109-EP120-V01.md` |

## 7. Todoist naming convention

Use only these section names in the production-control project:

1. `00 — START HERE`
2. `01 — EP001 PILOT`
3. `02 — EP002–EP006`
4. `03 — EP007–EP036`
5. `04 — EP037–EP060`
6. `05 — EP061–EP084`
7. `06 — EP085–EP108`
8. `07 — EP109–EP120`
9. `08 — QA & RELEASE`

Avoid generic names such as `PHASE 17`, `PHASE 18`, `PHASE 19`. The section name must tell the user what range is being executed.

## 8. Completion semantics

- **PRE-PRODUCTION READY:** specification exists and can be executed.
- **IN PRODUCTION:** actual work is underway.
- **QA:** actual output exists and is being inspected.
- **COMPLETE:** required output + QA + saved deliverable exists.
- **BLOCKED:** a dependency or P0/P1 issue prevents completion.

Never mark a task complete merely because its documentation exists.
