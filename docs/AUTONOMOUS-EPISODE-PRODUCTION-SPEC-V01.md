# RERE — AUTONOMOUS EPISODE PRODUCTION SPEC V01

**Scope:** EP007–EP120, and reusable for all episodes  
**Purpose:** eliminate routine ChatGPT dependency after an episode's curriculum row is approved and canonical systems are locked.

## Source order

1. `docs/RERE-EPISODE-CURRICULUM-EP001-EP120-V01.md`
2. episode-specific CONTENT LOCK
3. canonical character / world / prop bibles
4. episode SCRIPT LOCK
5. episode STORYBOARD PRODUCTION MASTER
6. episode ASSET MAPPING
7. episode SHOT PROMPTS
8. batch QA / voice / editing / packaging systems

Never reverse this hierarchy.

## Autonomous execution loop

`Todoist task → open required GitHub resources → verify readiness → attach canonical references → Gemini generation/reuse → inspect → save → shot QA → episode QA → voice/audio → edit → package → publish → learning review`

## Content generation contract

When an episode row is selected, the production operator must not invent a new learning objective. Use the curriculum row as the single learning promise. Build a short 3–4 minute preschool experience using:

`HOOK → NOTICE/EXPERIENCE → QUESTION/INVITATION → PAUSE → ANSWER/ACTION → REPEAT → CREATE/TRANSFER → RECALL → CANONICAL CLOSING`

Keep spoken Indonesian simple and natural. Do not add English vocabulary unless the episode's locked content explicitly requires it.

## Visual generation contract

Every Gemini request must attach only the minimum relevant canonical references, in this order:

1. Rere canonical character
2. face/expression when needed
3. canonical outfit
4. canonical world/location
5. recurring prop(s)
6. approved learning-object reference(s)
7. shot-specific storyboard/prompt

Use the batch universal anchor and negative prompt. Never ask Gemini to redesign a canonical asset.

## QA contract

Reject immediately for P0/P1 issues. Typical P1 blockers include identity drift, wrong learning object, ambiguous learning answer, geometry drift, broken continuity, unsafe anatomy, or misleading educational action.

For learning scenes verify:

- only the intended concept is visually dominant
- the child can infer the answer from the scene
- PAUSE is visually stable
- answer is not leaked before the pause
- Rere's gaze/gesture supports the intended target
- object count/geometry is exact where relevant
- action is physically believable

## Shorts contract

Create 5 Shorts per episode by default. Reuse approved long-form footage first and crop/reframe to 9:16. Only use dedicated Gemini vertical generation when the approved long-form source fails vertical QA.

Shorts pattern:

`HOOK → QUESTION/CHALLENGE → PAUSE → ANSWER/ACTION → REINFORCEMENT → MICRO-CLOSE`

## Completion contract

A Todoist task may be marked complete only when the described artifact/action actually exists. Planning, prompt creation or intention is not production completion.

An episode is production-ready only when all required repository resources exist, references are internally consistent, and the corresponding Todoist execution tasks are actionable.

An episode is production-complete only after actual visual/audio/editing deliverables and QA exist.

## No-confirmation rule

Routine production decisions already established in canonical documents do not require owner confirmation. Escalate only when a decision would change a locked brand rule, learning objective, safety rule, storyboard, canonical asset, or production baseline.
