# RERE — BATCH PRODUCTION TRACKER

**Version:** 1.0  
**Status:** Operational Template  
**Date:** 2026-09-12

## 1. Purpose

Use this tracker as the single operational checklist for a multi-episode batch.

## 2. Status Codes

- `NOT STARTED`
- `BLOCKED`
- `IN PROGRESS`
- `REVIEW`
- `REVISION`
- `APPROVED`
- `LOCKED`
- `PUBLISHED`

## 3. Batch Master Tracker

| ID | Episode | Cluster | Objective | Script | Storyboard | Assets | Scenes | Voice | Audio | Edit | QA | Packaging | Publish |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 001 | Rere dan Petualangan Warna | Colors | recognize/name 5 colors | LOCKED | LOCKED | IN PROGRESS | READY | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED |
| 002 | Rere Mencari Bentuk | Shapes | recognize/match 3 shapes | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED |
| 003 | Rere Belajar Angka 1–5 | Numeracy | recognize/count 1–5 | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED |
| 004 | Rere Memilih dan Mencocokkan | Matching | match attributes | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED |
| 005 | Rere Belajar Bagian Tubuh | Body | name/imitate body parts | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED |
| 006 | Rere Rapikan Mainan | Daily Routine | act/sort toys | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED | NOT STARTED |

## 4. Episode Gate Tracker

Every episode must pass these gates:

| Gate | Deliverable | Owner/Action | Required |
|---|---|---|---|
| G01 | Objective Card | define learning promise | ✓ |
| G02 | Concept Lock | story premise | ✓ |
| G03 | Script Lock | production dialogue | ✓ |
| G04 | Storyboard Lock | shot plan | ✓ |
| G05 | Asset Map | canonical/new asset list | ✓ |
| G06 | Learning Props | approved new objects | if needed |
| G07 | Scene Prompt Pack | Gemini prompts | ✓ |
| G08 | Scene Generation | approved visual scenes | ✓ |
| G09 | Voice | approved voice | ✓ |
| G10 | Audio | mix/SFX/music | ✓ |
| G11 | Edit | review cut | ✓ |
| G12 | Content QA | story + learning | ✓ |
| G13 | Child QA | participation + pacing | ✓ |
| G14 | Parent QA | trust + age appropriateness | ✓ |
| G15 | Packaging | title/thumbnail/metadata | ✓ |
| G16 | Final Export | master file | ✓ |
| G17 | Publish | platform upload | ✓ |
| G18 | Learning Review | post-publish data | ✓ |

## 5. Batch Shared-Asset Tracker

| Asset Group | Status | Notes |
|---|---|---|
| Rere Character | LOCKED | canonical |
| Regular Outfit | LOCKED | canonical |
| Muslimah Outfit | LOCKED | canonical variant |
| Playroom | LOCKED | canonical world |
| Other Worlds | LOCKED | available for later episodes |
| Signature Props | LOCKED | bunny/backpack/book/heart |
| Utility Props | LOCKED | crayons/bottle/etc. |
| Camera | LOCKED | production standard |
| Lighting | LOCKED | production standard |
| Voice | LOCKED | production standard |
| Audio Identity | VERIFY | confirm file/registry status |
| Editing Motion | LOCKED | production standard |
| Packaging | LOCKED | production standard |

## 6. Learning Asset Tracker

| Asset | Used By | Status | Canonical/Derivative |
|---|---|---|---|
| Red Apple | EP001 | APPROVED DESIGN | batch derivative |
| Yellow Banana | EP001 | APPROVED DESIGN | batch derivative |
| Blue Ball | EP001/EP003 | APPROVED DESIGN | batch derivative |
| Green Plant | EP001 | APPROVED DESIGN | batch derivative |
| Pink Flower | EP001 | APPROVED DESIGN | batch derivative |
| Quiz Set | EP001 | APPROVED DESIGN | batch derivative |
| Shape Set | EP002/EP004 | PLANNED | batch derivative |
| Number Set 1–5 | EP003 | PLANNED | batch derivative |
| Matching Set | EP004 | PLANNED | batch derivative |
| Body Cards | EP005 | OPTIONAL | episode derivative |
| Storage/Sorting Set | EP006 | PLANNED | batch derivative |

## 7. Scene Tracker Template

| Scene | Prompt | Reference Pack | Generated | Review | Revision | Approved |
|---|---|---|---|---|---|---|
| S01 | — | — | — | — | — | — |
| S02 | — | — | — | — | — | — |
| S03 | — | — | — | — | — | — |
| S04 | — | — | — | — | — | — |
| S05 | — | — | — | — | — | — |
| S06 | — | — | — | — | — | — |
| S07 | — | — | — | — | — | — |
| S08 | — | — | — | — | — | — |
| S09 | — | — | — | — | — | — |
| S10 | — | — | — | — | — | — |
| S11 | — | — | — | — | — | — |
| S12 | — | — | — | — | — | — |

## 8. QA Scoring

Each scene candidate can use a 24-point review:

### Identity — 6
- face
- hair
- anatomy
- outfit
- expression
- age/proportion

### Environment — 4
- architecture
- furniture
- scale
- lighting continuity

### Props — 4
- silhouette
- color
- markings
- interaction

### Camera — 3
- framing
- focal point
- perspective

### Learning — 4
- object readability
- color/shape/quantity accuracy
- participation clarity
- visual simplicity

### Safety/Quality — 3
- child-safe
- no artifacts
- no overstimulation

**Minimum target:** 21/24.  
**Automatic reject:** any critical identity or safety failure.

## 9. Voice Tracker

For each episode:

- [ ] script version recorded
- [ ] canonical opening correct
- [ ] canonical closing correct
- [ ] pronunciation reviewed
- [ ] emotion reviewed
- [ ] pacing reviewed
- [ ] PAUSE timing preserved
- [ ] voice identity consistent
- [ ] master WAV/export approved

## 10. Edit Tracker

- [ ] picture lock candidate
- [ ] voice aligned
- [ ] scene timing aligned
- [ ] PAUSE preserved
- [ ] music ducking correct
- [ ] SFX timing correct
- [ ] subtitles correct
- [ ] transitions correct
- [ ] end card correct
- [ ] export checked

## 11. Packaging Tracker

- [ ] title clear
- [ ] title honest
- [ ] thumbnail clear at small size
- [ ] Rere recognizable
- [ ] learning promise visible
- [ ] no misleading claims
- [ ] description prepared
- [ ] playlist assigned
- [ ] metadata reviewed

## 12. Final Release Gate

Do not publish until all are true:

- [ ] content QA PASS
- [ ] child-centered QA PASS
- [ ] parent QA PASS
- [ ] character continuity PASS
- [ ] prop continuity PASS
- [ ] world continuity PASS
- [ ] audio PASS
- [ ] export PASS
- [ ] packaging PASS
- [ ] final master archived

## 13. Post-Publish Learning Review

Record:

- publication date
- impressions
- click-through rate
- average view duration
- retention curve
- completion behavior
- repeat viewing indicators
- comments/parent feedback where available
- learning/engagement observations
- production issues
- candidate improvements

Do not change canonical identity solely because one episode underperformed.

## 14. Decision Log

Every batch should record:

- why a scene was rejected
- why a prop was redesigned
- why a script changed
- why a title changed
- what was learned
- what should become a system improvement

This converts production experience into institutional knowledge.
