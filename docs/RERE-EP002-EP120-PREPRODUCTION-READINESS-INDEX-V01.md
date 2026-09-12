# RERE — EP002–EP120 PRE-PRODUCTION READINESS INDEX V01

**Purpose:** single execution map proving where the episode-specific pre-production contract lives.
**Status:** PRE-PRODUCTION READY for EP002–EP120.

## Container rule
A batch pre-production master is a canonical container, not a generic checklist. Each episode row contains the locked learning objective, script sequence, shot-by-shot storyboard beats, asset/world mapping, executable prompt assembly directive, production handoff, five Shorts concepts, and QA constraints. A dedicated per-episode file may later supersede a row without changing the learning objective.

## Canonical locations
| Episodes | Canonical pre-production container |
|---|---|
| EP002–EP006 | `docs/BATCH-EP002-EP006-PREPRODUCTION-MASTER-V01.md` |
| EP007–EP036 | `docs/BATCH-EP007-EP036-AUTONOMOUS-PRODUCTION-PACK-V01.md` (V02 content; filename retained for continuity) |
| EP037–EP060 | `docs/BATCH-EP037-EP060-PREPRODUCTION-MASTER-V01.md` |
| EP061–EP084 | `docs/BATCH-EP061-EP084-PREPRODUCTION-MASTER-V01.md` |
| EP085–EP108 | `docs/BATCH-EP085-EP108-PREPRODUCTION-MASTER-V01.md` |
| EP109–EP120 | `docs/BATCH-EP109-EP120-PREPRODUCTION-MASTER-V01.md` |

## Per-episode readiness gate
Each episode is considered **PRE-PRODUCTION READY** when its container row has:
- one locked learning promise from the curriculum;
- a fixed 9-shot long-form structure;
- concrete S04–S06 teaching beats;
- S07 question/instruction with 3–5 second PAUSE and no answer leak;
- canonical Rere/world/prop references;
- prompt assembly directive using the canonical hierarchy;
- production handoff sequence;
- five Shorts mapped to the long-form learning moments;
- episode-specific safety/QA constraints;
- no unresolved P0/P1 planning blocker.

## Execution boundary
PRE-PRODUCTION READY means Gemini can be executed from the repository instructions. It does **not** mean visuals, audio, edited masters, Shorts, or publication have already been produced. Those remain production tasks and require actual deliverables plus QA before Todoist completion.

## EP001 comparison
EP001 retains its dedicated production master and script lock as the highest-detail reference implementation. EP002–EP120 use the batch-container architecture above to achieve the same execution contract without duplicating identical boilerplate across hundreds of files.
