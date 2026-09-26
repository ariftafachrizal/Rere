# RERE — GEMINI CLEAN PRODUCTION SESSION EP001 V01

**Episode:** RERE-EP-001 — Petualangan Warna  
**Brand:** Rere dan Cipi  
**Status:** RESET 06 — CLEAN GEMINI SESSION CONTROL  
**Date:** 2026-09-26  
**Source of Truth:** GitHub repository `ariftafachrizal/Rere`

## 1. Purpose

This document is the initialization/control protocol for a completely fresh Gemini production session for EP001.

It exists to prevent legacy prompt carry-over, character drift, Cipi redesign, stale storyboard instructions, and accidental use of unapproved generated images as canonical references.

This document does **not** authorize scene generation by itself.

Production remains gated by the six EP001 learning assets and human QA.

## 2. Authority Order

When instructions conflict, follow this order:

1. **Current GitHub production-control master**
   - `docs/RERE-PRODUCTION-CONTROL-MASTER-V01.md`
2. **EP001 clean asset & Gemini reference map**
   - `docs/RERE-EP001-CLEAN-ASSET-GEMINI-REFERENCE-MAP-V01.md`
3. **EP001 storyboard production master**
   - `docs/EPISODE-001-STORYBOARD-PRODUCTION-MASTER-V03.md`
4. **EP001 script lock**
   - `docs/EPISODE-001-SCRIPT-LOCK-V01.md`
5. **Batch QA system**
   - `docs/BATCH-001-QA-SYSTEM-V01.md`
6. Episode Gemini execution/prompt documents, only where they do not conflict with the sources above.

The clean Reference Map is the attachment authority for EP001.

## 3. Legacy Isolation Rule

The fresh Gemini session must NOT rely on:

- previous Gemini conversations
- previous Gemini project memory
- legacy 18-shot EP001 prompts
- old Rere-only opening/closing instructions
- old wording such as “Rere dan Kelinci Pink”
- previous generated frames as identity references
- unapproved generated images
- Gemini's own interpretation of what Rere, Cipi, or the playroom should look like.

If a previous generated frame is needed for continuity, it may only be used **after approval** and only as a continuity/state reference. It never overrides a canonical reference.

## 4. Brand Lock

### Public brand

**Rere dan Cipi**

### Character

**Rere** remains the canonical Rere character.

### Companion

**Cipi — Kelinci Pintar**

Cipi is the existing canonical Pink Bunny.

**Cipi is a naming/brand update, NOT a visual redesign.**

Canonical Cipi reference:

`assets/props/rere-pink-bunny-canonical.png.png`

Do not generate a new bunny design.

### Core signature

**BELAJAR • BERMAIN • BERBAGI**

Supporting phrase:

**MAIN • COBA • TEMUKAN**

## 5. Locked Brand Opening / Closing

### Opening

> “Hai teman-teman! Aku Rere, dan ini Cipi! Yuk main dan belajar bersama kami!”

S01 must visibly establish Rere + Cipi.

### Closing

> “Hebat sekali hari ini!”

> “Terima kasih sudah belajar bersama Rere dan Cipi!”

> “Belajar... Bermain... Berbagi... Bersama Rere dan Cipi!”

> “Sampai jumpa, teman-teman! Dadah!”

S12 must visibly contain Rere + Cipi.

End-card typography is editorial/post-production. Gemini must not invent it inside the scene.

## 6. Canonical Reference Package

### Rere

Attach directly from GitHub:

- `assets/character/rere-character-sheet-canonical.png`
- `assets/character/rere-expression-sheet-canonical.png` when expression fidelity matters
- `assets/character/rere-turnaround-sheet-canonical.png` when pose/view fidelity matters
- `assets/character/rere-outfit-sheet-canonical.png` when wardrobe fidelity matters

### Cipi

Attach directly when Cipi appears:

- `assets/props/rere-pink-bunny-canonical.png.png`

### Playroom

Attach directly for EP001:

- `assets/props/rere-world-playroom-canonical.png`

### Recurring props

Attach only when required by the shot:

- `assets/props/rere-learning-book-canonical.png`
- `assets/props/rere-crayon-kit-canonical.png`
- `assets/props/rere-pink-heart-motif-canonical.png`
- `assets/props/rere-backpack-canonical.png`

### EP001 learning assets

These are BUILD dependencies and must be approved before full scene generation:

- `RERE-EP001-ASSET-RED-APPLE-V01.png`
- `RERE-EP001-ASSET-YELLOW-BANANA-V01.png`
- `RERE-EP001-ASSET-BLUE-BALL-V01.png`
- `RERE-EP001-ASSET-GREEN-PLANT-V01.png`
- `RERE-EP001-ASSET-PINK-FLOWER-V01.png`
- `RERE-EP001-ASSET-QUIZ-SET-V01.png`

Reference map:

`docs/RERE-EP001-CLEAN-ASSET-GEMINI-REFERENCE-MAP-V01.md`

## 7. EP001 Scene Authority

EP001 uses **12 scenes: S01–S12**.

Do not recreate or reinterpret EP001 as the legacy 18-shot structure.

Learning order:

1. Merah — apple
2. Kuning — banana
3. Biru — ball
4. Hijau — plant/leaf
5. Pink — flower

Participation includes:

- five color-recognition pauses
- approximately 4 seconds each
- mini quiz: merah, kuning, pink
- approximately 4 seconds per response window
- no answer leakage.

S10 connects recognition to creation using all five target colors.

S11 must show the approved result/state from S10.

Target runtime is approximately **3:18–3:40**. Do not extend runtime merely to reach four minutes.

## 8. Cipi Presence Policy

### REQUIRED

- S01
- S12

### RECOMMENDED / OPTIONAL

- S02
- S03
- S10
- S11

### SECONDARY ONLY

- S04–S09

When Cipi appears in learning shots:

- never point to the answer
- never signal the answer
- never obscure the learning object
- never become a competing focal point
- never change canonical bunny geometry.

## 9. Generation Sequence

Follow this order:

### Gate A — Session initialization

1. Open a completely new Gemini session.
2. Do not import old conversation history.
3. Load this session-control document.
4. Load the clean Reference Map.
5. Load the active storyboard and QA rules.

### Gate B — Asset production

6. Generate only the six EP001 BUILD learning assets.
7. Human-review each asset.
8. Reject/regenerate failures.
9. Promote only approved assets to the approved EP001 reference set.

### Gate C — Scene keyframes

10. Generate controlled keyframes one shot at a time.
11. Attach canonical references directly on every request.
12. Use approved learning assets only.
13. Human-review each keyframe before using it downstream.

### Gate D — Motion

14. Convert approved keyframes into controlled video motion where required.
15. Keep motion limited to the storyboard action.
16. Human-review motion separately from image identity.

### Gate E — Episode assembly

17. Assemble S01–S12.
18. Perform continuity, learning, child-centered and parent-trust QA.
19. Only then proceed to packaging/publish gates.

## 10. One-Shot Rule

One Gemini request should have one clear production purpose.

Do not ask Gemini to invent:

- character identity
- world design
- learning-object design
- scene composition
- complex action
- camera language

all at once when the asset/keyframe workflow can control these separately.

Preferred pipeline:

**Canonical References → Approved Learning Asset → Keyframe → Video Motion → Human QA**

## 11. Standard Session Initialization Prompt

Paste the following as the first control message in a new Gemini session:

```text
RERE EP001 — CLEAN PRODUCTION SESSION

This is a fresh production session.

Project source of truth:
GitHub repository ariftafachrizal/Rere

Episode:
RERE-EP-001 — Petualangan Warna

Brand:
Rere dan Cipi

Canonical companion:
Cipi — Kelinci Pintar
Cipi uses the existing canonical Pink Bunny visual exactly as supplied.
Do not redesign Cipi.

AUTHORITATIVE CONTROL DOCUMENTS:
1. docs/RERE-PRODUCTION-CONTROL-MASTER-V01.md
2. docs/RERE-EP001-CLEAN-ASSET-GEMINI-REFERENCE-MAP-V01.md
3. docs/EPISODE-001-STORYBOARD-PRODUCTION-MASTER-V02.md
4. docs/EPISODE-001-SCRIPT-LOCK-V01.md
5. docs/BATCH-001-QA-SYSTEM-V01.md

LEGACY ISOLATION:
Ignore all previous Gemini conversations, previous generated Rere images, legacy 18-shot prompts, old brand wording, and old Rere-only opening/closing instructions.

REFERENCE RULE:
Canonical references are attached directly to each request.
Do not rely on memory for Rere, Cipi, the playroom, recurring props, or learning assets.
Previous generated images may only be used as approved continuity/state references and never as identity authority.

PRODUCTION GATE:
Do not generate full EP001 scenes yet.
The six EP001 learning assets must first be generated and human-QA approved.

LEARNING ORDER:
red/apple → yellow/banana → blue/ball → green/plant → pink/flower

SCENE STRUCTURE:
S01–S12 only.

CIPI:
Required in S01 and S12.
Optional/secondary according to the Reference Map in other scenes.
Cipi must never leak a quiz answer or compete with the learning target.

QUALITY PRIORITY:
1. Canonical identity
2. Educational clarity
3. Continuity
4. Child-safe, calm visual language
5. Motion quality
6. Novelty

If any instruction conflicts with the authoritative control documents, stop and follow the higher-priority source.

Confirm session initialization only.
Do not generate an image or video yet.
```

## 12. Universal Negative

Apply the active QA/negative rules from the Gemini prompt pack and storyboard.

At minimum:

- no Rere redesign
- no face/eye/eyelash/nose/lip drift
- no hairstyle or outfit drift
- no adult proportions
- no malformed anatomy
- no duplicated objects
- no random props
- no playroom layout drift
- no text/watermark/logo artifacts
- no photorealistic/scary/uncanny styling
- no excessive camera movement
- no answer leakage
- no ambiguous learning target
- no overstimulation.

## 13. Session Output Naming

Use versioned filenames.

Learning assets:

`RERE-EP001-ASSET-[TARGET]-V01.png`

Scene/keyframe candidates:

`RERE-EP001-S[##]-KEYFRAME-V01.png`

Video candidates:

`RERE-EP001-S[##]-VIDEO-V01.mp4`

If rejected, do not overwrite the rejected output. Increment the version.

Example:

`RERE-EP001-S04-KEYFRAME-V01.png` → rejected  
`RERE-EP001-S04-KEYFRAME-V02.png` → next candidate

## 14. Human QA Boundary

Gemini generation is not approval.

Human QA remains the final authority.

Reject immediately for P0/P1 defects, including:

- wrong character identity
- unsafe or unusable anatomy
- misleading learning content
- canonical prop/world drift
- wrong learning target
- broken continuity
- answer leakage.

For approved outputs, record:

- episode
- shot/asset ID
- version
- result
- reviewer
- date
- notes/defects if applicable.

## 15. RESET 06 Definition of Done

RESET 06 is complete when:

- [x] Fresh-session protocol is documented
- [x] Authority order is explicit
- [x] Legacy isolation is explicit
- [x] Rere canonical references are explicit
- [x] Cipi identity and presence policy are explicit
- [x] EP001 12-scene structure is explicit
- [x] Learning-asset gate is explicit
- [x] One-shot generation rule is explicit
- [x] Standard Gemini initialization prompt is ready
- [x] QA boundary is explicit
- [ ] Six EP001 learning assets generated
- [ ] Six EP001 learning assets human-QA approved
- [ ] RESET 07 rebuild Todoist execution tree
- [ ] RESET 08 gate unlock

The unchecked items are downstream gates and are intentionally outside RESET 06 completion.

## 16. Final Rule

**Do not let Gemini decide what Rere production is.**

GitHub defines the production system.  
The Reference Map defines the attachments.  
The Storyboard defines the scene.  
Gemini renders the instructed result.  
Human QA decides whether the result is accepted.
