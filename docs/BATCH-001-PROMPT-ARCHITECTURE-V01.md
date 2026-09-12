# RERE BATCH 001 — PROMPT ARCHITECTURE V01

**Status:** Production Standard  
**Purpose:** reusable AI-generation prompt system for EP001–EP006  
**Date:** 2026-09-12

## 1. Principle

Gemini is a controlled downstream renderer. It does not define Rere's identity.

Prompt hierarchy:

**SYSTEM → CHARACTER → WORLD → PROP → OBJECTIVE → ACTION → CAMERA → LIGHT → MOTION → SCENE → NEGATIVE → QA**

## 2. Prompt Modules

### MODULE 01 — SYSTEM

> Produce content for the established Rere preschool universe. Follow all supplied canonical references and project Bibles. Preserve identity across shots and episodes. Prioritize clarity, warmth, child safety, educational readability, and continuity over spectacle.

### MODULE 02 — CHARACTER

> Use the supplied canonical Rere reference as the sole identity source. Preserve face, eyes, eyelashes, nose, lips, hair, ponytail/hijab mode, anatomy, proportions, outfit, age perception, and skin tone. Do not reinterpret the character.

### MODULE 03 — WORLD

> Use the supplied canonical world reference. Preserve architecture, layout, major furniture, scale, palette relationships, and anchor props. Story dressing may change only when it does not redefine the location.

### MODULE 04 — PROP

> Use supplied canonical/approved prop references exactly. Preserve silhouette, markings, material, color identity, scale, and interaction points.

### MODULE 05 — OBJECTIVE

State exactly one learning intention per scene.

Example:

> The child should recognize the red color on the apple.

### MODULE 06 — ACTION

Describe one primary action and supporting micro-actions.

Example:

> Rere notices the apple, points to it, gently picks it up, and looks toward the camera during the question.

### MODULE 07 — CAMERA

Use named project camera presets. Specify shot size, camera height, movement, focal point, composition, and PAUSE stability.

### MODULE 08 — LIGHTING

Use named project lighting presets. Specify time-of-day, softness, exposure intent, skin-tone protection, and learning-color protection.

### MODULE 09 — MOTION

Specify motion intensity from 0–4. Keep motion purposeful and age-appropriate.

### MODULE 10 — SCENE

Combine location, action, props, camera, lighting, mood, and continuity into the shot-specific instruction.

### MODULE 11 — NEGATIVE

Always append the project's identity-drift, anatomy, text-artifact, safety, and overstimulation negatives.

### MODULE 12 — QA

Tell the generation/review process what must be visually obvious and what would cause rejection.

## 3. Reusable Prompt Template

```text
[PROJECT SYSTEM]
[CANONICAL CHARACTER]
[CANONICAL WORLD]
[CANONICAL PROPS]
[LEARNING OBJECTIVE]
[PRIMARY ACTION]
[CAMERA PRESET]
[LIGHTING PRESET]
[MOTION LEVEL]
[SCENE-SPECIFIC DETAILS]
[CONTINUITY REQUIREMENTS]
[NEGATIVE PROMPT]
[ACCEPTANCE CRITERIA]
```

## 4. Batch Prompt Strategy

Generate prompts from structured data rather than copying prose manually.

Required fields per shot:

- episode_id
- shot_id
- objective
- character_reference
- world_reference
- prop_references
- action
- dialogue_context
- camera_preset
- lighting_preset
- motion_level
- audio_intent
- continuity_constraints
- negative_prompt
- acceptance_criteria

## 5. Cross-Episode Consistency

The same module should remain unchanged across episodes unless a Bible version changes.

Only these should normally vary:

- objective
- props
- action
- world when story requires it
- camera preset when shot requires it
- lighting mood when story requires it
- dialogue context

## 6. Prompt Versioning

`RERE-PROMPT-SYSTEM-V01`  
`RERE-PROMPT-CHARACTER-V01`  
`RERE-PROMPT-WORLD-V01`  
`RERE-PROMPT-PROP-V01`  
`RERE-PROMPT-EP001-V01`

## 7. Forbidden Prompt Behavior

Never instruct the model to:

- invent a new Rere design
- “make Rere similar to” a different character
- redesign canonical props
- redesign recurring locations
- add random decorative objects that compete with learning
- use extreme cinematic effects
- generate text when text will be composited editorially

## 8. Golden Rule

> **Prompt the story around the identity, never the identity around the prompt.**
