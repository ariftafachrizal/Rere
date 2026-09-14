# RERE — CHANNEL OPERATING SYSTEM V01

**Status:** ACTIVE / CANONICAL  
**Date:** 2026-09-14  
**Scope:** Channel management from idea through published content and learning review

## 1. System of record

### GitHub — SOURCE OF TRUTH

Stores:
- strategy
- decisions
- brand rules
- canonical assets
- learning standards
- curriculum
- content metadata
- production specifications
- QA standards
- publishing standards
- analytics learnings and durable decisions

### Todoist — EXECUTION QUEUE

Stores:
- actionable tasks
- dependencies
- execution order
- reminders/due dates when useful
- operational follow-up

Todoist does not replace canonical specifications in GitHub.

### YouTube — PUBLIC OUTPUT + PLATFORM DATA

Stores:
- published videos
- channel presentation
- playlists
- public metadata
- platform analytics

YouTube is not the source of truth for internal production rules.

## 2. Operating lifecycle

```text
IDEA
 ↓
RESEARCH / VALIDATE
 ↓
LEARNING OBJECTIVE
 ↓
CONTENT LOCK
 ↓
SCRIPT / STORYBOARD
 ↓
ASSET + GEMINI PREPARATION
 ↓
PRODUCTION
 ↓
VISUAL / AUDIO QA
 ↓
EDIT
 ↓
FINAL QA
 ↓
PACKAGING
 ↓
UPLOAD / PUBLISH
 ↓
ANALYTICS
 ↓
LEARNING REVIEW
 ↓
ITERATION
```

## 3. Work ownership

| Work | Primary system |
|---|---|
| Strategy | GitHub |
| Brand rules | GitHub |
| Character/prop/world canon | GitHub + canonical assets |
| Curriculum | GitHub |
| Episode specification | GitHub |
| Production task | Todoist |
| Actual production files | project asset storage / approved workflow |
| QA result | GitHub durable record + Todoist task status |
| Publishing metadata | GitHub + YouTube |
| Published video | YouTube |
| Analytics | YouTube + GitHub learning record |

## 4. Definition of ready states

### FOUNDATION READY
Channel exists, channel identity is locked, channel configuration is intentional, publishing templates exist, and operating procedures are usable.

### PRE-PRODUCTION READY
Learning objective, content, storyboard, asset mapping, prompts, handoff and QA requirements exist.

### IN PRODUCTION
Actual visual/audio/edit work has started.

### QA
Actual output exists and is being inspected against defined standards.

### PUBLISH READY
Actual output passed final QA and has complete metadata/thumbnail/playlist placement.

### PUBLISHED
Video is live or scheduled according to the release plan and publication data is recorded.

### LEARNING REVIEWED
Performance and qualitative observations have been reviewed and converted into explicit learning/decision records where useful.

## 5. Episode control contract

Every episode should be traceable using:

`EPISODE ID → CONTENT → SCRIPT → STORYBOARD → ASSETS → PROMPTS → OUTPUT → QA → PACKAGING → PUBLISH → ANALYTICS`

No stage should depend on undocumented tribal knowledge.

## 6. Channel publishing checklist

Before upload:
- final video exists
- correct aspect ratio/resolution
- correct audio
- opening/closing correct
- no P0/P1 QA issue
- thumbnail ready
- title approved
- description approved
- hashtags approved
- playlist selected
- audience/content settings checked
- filename follows convention

After upload:
- preview the actual YouTube presentation
- verify title/description/thumbnail
- verify playlist
- verify visibility/scheduling
- record publication details
- record URL/ID in the durable publication record

## 7. Analytics loop

### Long-form
Track at minimum:
- impressions
- click-through rate
- views
- average view duration
- average percentage viewed
- retention curve
- likes/comments where applicable
- subscribers gained
- returning viewers when available

### Shorts
Track at minimum:
- views
- viewed vs swiped away where available
- average percentage viewed / retention
- engagement
- subscribers gained
- traffic/discovery patterns

### Learning review
Do not optimize a single metric in isolation. Compare performance with the learning objective, hook, pacing, interaction, topic, packaging and audience response.

## 8. Experimentation rule

Change one major variable at a time when practical:
- topic
- hook
- title
- thumbnail
- pacing
- interaction design
- duration
- visual treatment

Record meaningful experiments in GitHub so successful patterns become system knowledge rather than temporary intuition.

## 9. Change control

If a new decision conflicts with an existing canonical rule:

1. Identify the conflict.
2. Decide whether the old rule should change.
3. Record the decision in `docs/DECISIONS.md` or a dedicated decision document.
4. Update the affected canonical document.
5. Update downstream Todoist instructions only after the canonical rule is changed.

Never silently fork the Rere identity or production system.

## 10. Minimum viable cadence

The project should favor a sustainable cadence that preserves quality. Volume is subordinate to:

**learning value + trust + consistency + repeatability.**

Cadence may be increased only when the production system can sustain it without weakening QA.

## 11. Operating principle

**Build the system once, document it, execute it, measure it, and improve it.**

Rere should become a repeatable media operation rather than a collection of individual videos.
