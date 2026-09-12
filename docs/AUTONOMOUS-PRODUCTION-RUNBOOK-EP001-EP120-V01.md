# RERE — AUTONOMOUS PRODUCTION RUNBOOK EP001–EP120 V01

## Purpose

This document defines the operating contract for producing Rere episodes from EP001 through EP120 without requiring routine return to ChatGPT.

## Source of truth

**GitHub repository:** `ariftafachrizal/Rere`  
**Task control:** Todoist project `YouTube Rere — Batch 001 Production`  
**Downstream generation:** Gemini  
**Final authority:** approved canonical references + locked production documents + human QA

## Non-negotiable rules

1. Never change a LOCKED storyboard during derivative production.
2. Never redesign canonical Rere identity, world, recurring props, or approved visual language.
3. Use the minimum relevant canonical references for every generation.
4. Shorts default to reuse/crop/reframe from approved long-form footage.
5. Generate a dedicated vertical derivative only when the crop fails framing, readability, continuity, or QA.
6. Preserve child-safe anatomy, language, actions, and learning clarity.
7. Do not mark a Todoist task complete until the actual deliverable and required QA are complete.
8. Record important production decisions in GitHub so Gemini execution does not depend on chat history.
9. If a required future resource is missing, create the resource before execution rather than inventing an undocumented variant.
10. Maintain traceability from episode → shot → asset → prompt → output → QA → publish.

## Episode execution loop

For each EPxxx:

**LOCK → PACKAGE → GENERATE/REUSE → QA → VOICE/AUDIO → EDIT → PACKAGE → PUBLISH → REVIEW**

### 1. LOCK

Confirm content/script, storyboard, canonical references, learning objective, and acceptance criteria.

### 2. PACKAGE

Prepare asset mapping, Gemini prompt pack, shot prompts, reference attachments, voice/audio plan, editing instructions, packaging metadata, and QA checklist.

### 3. GENERATE / REUSE

In Gemini, execute only the approved resources. Reuse approved assets/footage whenever safe and technically appropriate.

### 4. QA

Apply asset, shot, scene, episode, and batch QA. P0/P1 failures require rejection or correction before progression.

### 5. VOICE / AUDIO

Use the canonical Rere voice/audio identity and preserve dialogue timing, especially PAUSE moments.

### 6. EDIT

Assemble long-form and Shorts according to locked timing and interaction architecture. Do not rewrite the learning flow merely for editing convenience.

### 7. PACKAGE

Finalize title, thumbnail, description, metadata, Shorts packaging, and publishing checklist.

### 8. PUBLISH

Pass the final publish gate, then publish the approved output.

### 9. REVIEW

Record post-publish learning and performance observations without retroactively altering the locked production record.

## Shorts operating standard

Baseline: **5 Shorts per episode**.

Short architecture:

**HOOK → QUESTION → PAUSE → ANSWER → REWARD/REINFORCEMENT → MICRO-CLOSE**

Recommended runtime: 22–35 seconds; acceptable 15–45 seconds when justified by learning clarity.

Format: 9:16 vertical, minimum 1080×1920.

## EP001–EP120 planning baseline

- 120 long-form episodes
- 600 Shorts at 5 per episode
- 720 planned video outputs total

This is a planning baseline. Future episodes are not considered content-locked until their episode-specific resources exist and are approved.

## Failure handling

If a source crop fails: attempt safe reframing first. If still failing, use the episode's dedicated vertical-generation prompt. If a canonical asset drifts, reject and regenerate from canonical references. If learning clarity is compromised, simplify rather than add complexity.

## Completion standard

An episode is complete only when all required outputs, QA, packaging, publishing, and post-publish review tasks are complete and the repository contains the corresponding production record.

## Handoff standard

Todoist task descriptions must point to the relevant GitHub documents and define the expected action. Gemini operators should be able to execute from those resources without needing undocumented context from previous ChatGPT conversations.
