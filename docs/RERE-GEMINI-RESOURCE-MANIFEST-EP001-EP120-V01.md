# RERE — GEMINI RESOURCE MANIFEST EP001–EP120 V01

**Status:** ACTIVE / CANONICAL EXECUTION MAP

## Universal copy/paste prompt

```text
RERE PROJECT — GEMINI EXECUTION PROMPT

EPISODE: [EP###]
SHOT: [S##]

CONTENT:
[content pack path]

STORYBOARD / PRE-PRODUCTION:
[canonical batch/storyboard path]

GEMINI PROMPT SOURCE:
[canonical prompt path]

CHARACTER:
docs/CHARACTER-BIBLE-RERE.md
assets/character/rere-character-sheet-canonical.png
assets/character/rere-expression-sheet-canonical.png
assets/character/rere-turnaround-sheet-canonical.png

PROPS / ASSETS:
docs/PROP-BIBLE-RERE.md
docs/CANONICAL-ASSET-REGISTRY.md
[attach only the required canonical prop / learning-object assets]

WORLD:
docs/WORLD-ENVIRONMENT-BIBLE-RERE.md
docs/CANONICAL-ASSET-REGISTRY.md
[attach required canonical environment asset]

OBJECTIVE:
[one locked learning promise]

ACTION:
[one primary action + supporting micro-actions]

INTERACTION:
[question/instruction → 3–5 sec PAUSE → child response → reinforcement]
Never leak the answer during PAUSE.

CAMERA / LIGHT / MOTION:
[exact shot directive from storyboard]

CONTINUITY:
[preserve Rere identity, world, props, object position and action continuity]

NEGATIVE:
no redesign, face drift, hairstyle drift, adult proportions, extra fingers/limbs/eyes,
malformed hands, scary/uncanny face, photorealism, random props, world drift,
text artifacts, watermark/logo, clutter, excessive bloom, overstimulation, answer leak.

ACCEPTANCE:
[exact acceptance criteria from storyboard/batch row + QA system]
```

## Mandatory resource order

**Character → Face/Anatomy → Outfit/Expression → World → Recurring Props → Learning Object → Storyboard Shot → Camera → Lighting → Motion → Scene → Negative → QA**

## Batch source map

| Episodes | Content metadata | Storyboard / pre-production | Gemini source |
|---|---|---|---|
| EP001 | `docs/RERE-CONTENT-PACK-EP001-V01.md` | `docs/EPISODE-001-STORYBOARD-PRODUCTION-MASTER-V02.md` | `docs/BATCH-001-SHOT-PROMPTS-V01.md` |
| EP002–EP006 | `docs/RERE-CONTENT-PACK-EP002-EP006-V01.md` | `docs/BATCH-EP002-EP006-PREPRODUCTION-MASTER-V01.md` | `docs/BATCH-001-SHOT-PROMPTS-V01.md` |
| EP007–EP036 | `docs/RERE-CONTENT-PACK-EP007-EP036-V01.md` | `docs/BATCH-EP007-EP036-AUTONOMOUS-PRODUCTION-PACK-V01.md` | same batch source / prompt directive |
| EP037–EP060 | `docs/RERE-CONTENT-PACK-EP037-EP060-V01.md` | `docs/BATCH-EP037-EP060-PREPRODUCTION-MASTER-V01.md` | same batch source / prompt directive |
| EP061–EP084 | `docs/RERE-CONTENT-PACK-EP061-EP084-V01.md` | `docs/BATCH-EP061-EP084-PREPRODUCTION-MASTER-V01.md` | same batch source / prompt directive |
| EP085–EP108 | `docs/RERE-CONTENT-PACK-EP085-EP108-V01.md` | `docs/BATCH-EP085-EP108-PREPRODUCTION-MASTER-V01.md` | same batch source / prompt directive |
| EP109–EP120 | `docs/RERE-CONTENT-PACK-EP109-EP120-V01.md` | `docs/BATCH-EP109-EP120-PREPRODUCTION-MASTER-V01.md` | same batch source / prompt directive |

## Canonical shared resources

- Character Bible: `docs/CHARACTER-BIBLE-RERE.md`
- Canonical Asset Registry: `docs/CANONICAL-ASSET-REGISTRY.md`
- Prop Bible: `docs/PROP-BIBLE-RERE.md`
- World Bible: `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md`
- Prompt Architecture: `docs/BATCH-001-PROMPT-ARCHITECTURE-V01.md`
- QA System: `docs/BATCH-001-QA-SYSTEM-V01.md`
- Shorts Master: `docs/BATCH-001-SHORTS-MASTER-V01.md`

## Gemini operating rule

Do not generate a recurring identity from text when a canonical visual reference exists. The prompt describes **what Rere is doing**, not **what Rere should look like**.

## QA rule

Generation is not approval. Inspect every output. P0/P1 failures block the episode.
