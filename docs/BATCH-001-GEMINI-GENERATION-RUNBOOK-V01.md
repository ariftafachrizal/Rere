# RERE — BATCH 001 GEMINI GENERATION RUNBOOK V01

**Purpose:** execution manual for generating EP001–EP006 visual/video assets with Gemini after canonical Character, World, Props, Camera and Lighting assets are locked.

**Status:** PRODUCTION RUNBOOK  
**Audience:** Rere production operator / editor  
**Rule:** Gemini is the renderer. Storyboard and canonical assets are the source of truth. Human review is the final authority.

---

## 1. DO NOT REGENERATE WHAT IS ALREADY CANONICAL

Before opening Gemini, understand the hierarchy:

`Canonical Asset → Production Storyboard → Gemini Render → Human QA → Approved Shot → Editing`

Already locked and reusable:

- Rere character identity
- Rere face/anatomy
- Regular outfit
- Muslimah outfit when explicitly required
- World/environment
- Recurring props
- Camera language
- Lighting/color language
- Voice/audio language
- Editing/motion language

Gemini must **not** redesign any of these.

If Gemini output changes Rere's face, hair, outfit, room architecture, recurring prop geometry or visual language, reject and regenerate using stronger references/instructions.

---

## 2. DOCUMENTS TO OPEN BEFORE PRODUCTION

Use these as the operator's source stack:

1. `docs/CANONICAL-ASSET-REGISTRY.md`
2. `docs/CHARACTER-BIBLE-RERE.md`
3. `docs/WORLD-ENVIRONMENT-BIBLE-RERE.md`
4. `docs/PROP-BIBLE-RERE.md`
5. `docs/CAMERA-CINEMATOGRAPHY-BIBLE.md`
6. `docs/LIGHTING-COLOR-GRADING-BIBLE.md`
7. `docs/VOICE-BIBLE-RERE.md`
8. `docs/BATCH-001-ASSET-MAPPING-GEMINI-V01.md`
9. `docs/BATCH-001-GEMINI-PROMPT-PACK-V01.md`
10. Episode Production Master Storyboard V02 for the episode being rendered.

Do not search the repository for basic instructions while rendering. This runbook plus the episode storyboard should be enough to execute the generation pass.

---

## 3. REFERENCE ATTACHMENT ORDER

For each shot attach only what is relevant, in this order:

### A. Character
- canonical Rere character sheet
- face/expression reference if the face is important
- outfit reference if outfit continuity matters

### B. World
- canonical location/environment sheet

### C. Props
- recurring prop references that are visible in the shot
- learning-object reference for the target object

### D. Story
- relevant storyboard shot specification

Minimum principle:

> Attach enough information to remove ambiguity, but not so much unrelated information that Gemini starts blending assets.

---

## 4. UNIVERSAL ANCHOR INSTRUCTION

Use this concept at the beginning of every generation prompt:

> Use the attached canonical Rere references as the authoritative source of identity. Preserve the exact face structure, brown eyes, curled eyelashes, distinctive nose and small smiling lip shape, single high fountain ponytail, canonical preschool proportions, and approved outfit. Use attached canonical environment and prop references as authoritative. Do not redesign, reinterpret, replace, recolor, age-up or stylize these canonical assets. Render only the requested shot action.

Then add the shot-specific instruction.

---

## 5. UNIVERSAL NEGATIVE PROMPT

Append the universal constraints to every visual generation request:

> No character redesign, no face drift, no hairstyle drift, no outfit drift, no adult proportions, no extra fingers, no extra limbs, no extra eyes, no malformed hands, no uncanny face, no photorealism, no scary mood, no random props, no environment redesign, no prop geometry inconsistency, no text artifacts, no watermark, no logo, no clutter, no excessive bloom, no extreme camera movement, no dutch angle, no handheld shake, no rapid zoom, no overstimulation.

Add episode-specific negatives after this block.

---

## 6. SHOT PROMPT STRUCTURE

Every shot prompt should contain these blocks:

1. **Identity** — canonical Rere reference.
2. **World** — canonical location.
3. **Props** — exact approved assets.
4. **Objective** — what the child should understand.
5. **Action** — exact physical sequence.
6. **Expression** — emotional state.
7. **Eye direction** — object/camera/other target.
8. **Composition** — what must dominate frame.
9. **Camera** — preset, framing, movement.
10. **Lighting** — canonical preset.
11. **Motion** — intensity 0–4.
12. **Continuity** — relation to previous/next shot.
13. **Negative** — universal + shot-specific.
14. **Acceptance criteria** — objective pass/fail checks.

Never prompt only with a vague sentence such as “make a cute Rere video about colors.”

---

## 7. IMAGE VS VIDEO DECISION

### Prefer image/still-first when:
- shot is primarily a talking pose;
- learning object must remain geometrically stable;
- exact composition is more important than movement;
- a pause/answer window needs a clean hold;
- Gemini video introduces identity drift.

### Prefer video generation when:
- physical action is educationally important;
- Rere must walk, pick up, place, roll or wave;
- object movement must be visibly continuous;
- the action cannot be communicated well by a still.

### Hybrid is allowed
Generate a stable still as the visual anchor, then animate only the required movement. This is preferred when it improves character consistency.

---

## 8. PRODUCTION ORDER

Render in this exact order unless a technical issue requires a temporary exception:

1. EP001 S01–S12
2. EP002 S01–S09
3. EP003 S01–S09
4. EP004 S01–S09
5. EP005 S01–S09
6. EP006 S01–S09

Within each episode:

`S01 → S02 → S03 → ... → final shot`

Do not render the entire episode blindly before checking early shots. Use the first approved shots to validate consistency before continuing.

---

## 9. GENERATION LOOP FOR EVERY SHOT

### Step 1 — Read the storyboard
Know the learning objective, action, dialogue context, camera, pause and continuity.

### Step 2 — Attach references
Use the exact canonical assets mapped to the shot.

### Step 3 — Paste the shot prompt
Use the episode prompt sheet / prompt pack.

### Step 4 — Generate
Do not add creative improvisation unless a technical correction is required.

### Step 5 — Inspect immediately
Check character, environment, props, action, composition and learning clarity.

### Step 6 — Save with version
`RERE-EP###-S##-[ASSET|SCENE]-[NAME]-V##`

Example:
`RERE-EP001-S04-SCENE-RED-APPLE-V01`

### Step 7 — QA
Use P0–P3 QA from `docs/BATCH-001-QA-SYSTEM-V01.md`.

### Step 8 — Decide
- APPROVED → continue.
- P2/P3 → revise if meaningful.
- P1 → regenerate.
- P0 → stop and correct before continuing.

### Step 9 — Record approved version
The editor must know exactly which version is approved.

---

## 10. REGENERATION RULE

Do not endlessly tweak a bad generation with tiny prompt changes.

If the problem is identity/world/prop drift:

1. strengthen canonical reference attachment;
2. shorten unrelated prompt content;
3. explicitly state the asset is authoritative;
4. describe only the requested action;
5. regenerate a clean version.

If the problem is learning clarity:

1. simplify composition;
2. reduce distractors;
3. enlarge the learning object if necessary;
4. clarify gaze/hand position;
5. preserve PAUSE visibility.

---

## 11. EPISODE-SPECIFIC HARD RULES

### EP001 — Colors
- Target colors: red, yellow, blue, green, pink.
- During question/pause, do not visually reveal the answer too aggressively.
- One primary learning object at a time.

### EP002 — Shapes
- Circle, square, triangle only.
- Geometry must remain stable.
- Matching must be one-to-one.
- Do not introduce extra shapes.

### EP003 — Numbers 1–5
- Exact count is non-negotiable.
- One object = one count word.
- No hidden/duplicate objects.
- No visual arrangement that makes counting ambiguous.

### EP004 — Matching
- One clear matching criterion at a time.
- Exactly one plausible answer.
- Identical pairs must remain visually identical.

### EP005 — Body Parts
- Eyes, nose, mouth, hands, feet.
- Child-safe, non-clinical visual language.
- Mirror reflection must be physically coherent.
- Anatomy errors are immediate rejection.

### EP006 — Clean-up
- Action chain: take → carry → put away.
- Storage destinations stay fixed.
- No disappearing/reappearing toys.
- Physical contact and movement must make sense.

---

## 12. FILE / FOLDER CONTROL

Recommended production structure:

```text
production/
  batch-001/
    EP001/
      references/
      prompts/
      renders/
        v01/
        v02/
      approved/
      qa/
    EP002/
    EP003/
    EP004/
    EP005/
    EP006/
```

If the actual storage platform differs, preserve the same logical structure.

---

## 13. HUMAN QA CHECKLIST

Before marking a shot approved:

- [ ] Rere identity matches canonical.
- [ ] Face matches canonical.
- [ ] Hair/ponytail matches canonical.
- [ ] Outfit matches canonical.
- [ ] World architecture matches canonical.
- [ ] Recurring props match canonical.
- [ ] Learning object is correct.
- [ ] Learning object is readable.
- [ ] Action is physically believable.
- [ ] Hands/fingers/anatomy are clean.
- [ ] Camera follows child-height language.
- [ ] Lighting/color remains canonical.
- [ ] No answer leakage during PAUSE.
- [ ] No accidental extra objects.
- [ ] No text/watermark/logo artifact.
- [ ] Shot connects logically to previous/next shot.
- [ ] Child can understand what to look at/do.

---

## 14. STOP CONDITIONS

Stop the batch and resolve the issue before generating more shots if:

- canonical Rere identity repeatedly drifts;
- the same environment keeps changing;
- a recurring prop has multiple incompatible designs;
- a learning concept becomes visually ambiguous;
- generated videos repeatedly create anatomy/physics failures;
- the production operator is unsure which asset is canonical.

Do not solve a source-of-truth problem by generating more variants.

---

## 15. DEFINITION OF DONE

A shot is DONE only when:

`Generated → Saved → QA Passed → Version Locked → Approved`

An episode is DONE only when:

`All shots approved → Voice/audio synced → Editing assembled → Full-watch QA passed → Packaging approved → Publish gate passed`

Batch 001 is DONE only when:

`EP001–EP006 published or explicitly held with documented reason → release log complete → learning review scheduled/completed`

---

## FINAL PRINCIPLE

> **Prompt the story around the identity, never the identity around the prompt.**
