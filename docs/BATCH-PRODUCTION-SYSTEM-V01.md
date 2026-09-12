# RERE — MULTI-EPISODE BATCH PRODUCTION SYSTEM

**Version:** 1.0  
**Status:** Production Standard  
**Date:** 2026-09-12  
**Purpose:** Menjadikan produksi beberapa episode sebagai satu sistem terkontrol, bukan kumpulan produksi satuan.

---

## 1. WHY BATCH PRODUCTION

Rere harus scalable tanpa mengorbankan:

- canonical character consistency
- world continuity
- educational quality
- voice identity
- audio identity
- production efficiency
- parent trust
- child-centered design

Batch production memisahkan pekerjaan yang mahal jika diulang-ulang dari pekerjaan yang unik per episode.

### Batch philosophy

> **Build once → lock once → reuse many times → review deliberately.**

---

## 2. BATCH UNIT

A production batch is a group of episodes sharing one or more production dependencies.

Recommended first batch:

**6 episodes**

Why six:

- enough volume to test the system
- small enough for manual quality control
- allows reusable locations and props
- creates a meaningful first content cluster
- exposes consistency problems early

A batch may later expand to 8–12 episodes after the pipeline proves stable.

---

## 3. TWO TYPES OF WORK

### A. Shared Batch Assets

Build once and reuse:

- canonical Rere references
- approved outfit variants
- recurring gestures
- canonical worlds
- recurring props
- learning prop libraries
- camera presets
- lighting presets
- audio identity
- voice identity
- transition library
- subtitle style
- title/thumbnail system

### B. Episode-Specific Assets

Build only when needed:

- unique learning objects
- unique story props
- episode-specific drawing/art
- special location dressing
- episode-specific visual effects
- unique sound effects

Never promote an episode-specific asset to canonical automatically.

---

## 4. BATCH ORDER OF OPERATIONS

### Phase 0 — System Readiness

1. Character canonical locked
2. Prop canonical locked
3. World canonical locked
4. Camera locked
5. Lighting locked
6. Voice locked
7. Audio identity locked
8. Editing locked
9. Packaging locked
10. Production Bible locked

### Phase 1 — Batch Planning

1. select episode cluster
2. define learning progression
3. create objective cards
4. identify shared worlds
5. identify shared props
6. identify new learning props
7. identify shared voice needs
8. identify shared visual motifs

### Phase 2 — Episode Development

For each episode:

**Concept → Objective → Script → Storyboard → Asset Map**

Do not generate scenes yet.

### Phase 3 — Shared Asset Preparation

Generate and approve all missing reusable learning props first.

### Phase 4 — Scene Generation

Generate episodes in grouped scene batches.

Recommended:

**same character/world context first → different episode content second**

This improves continuity and reduces prompt drift.

### Phase 5 — Voice Batch

Record/generate voice for all locked scripts in one session where practical.

### Phase 6 — Audio Batch

Prepare recurring music, sonic identity, SFX categories, and episode-specific cues.

### Phase 7 — Edit Batch

Use the same project template and sequence architecture.

### Phase 8 — QA Batch

Review:

- episode individually
- then batch-wide consistency

### Phase 9 — Packaging Batch

Create titles, thumbnails, descriptions, playlists, metadata, and release assets as a group.

### Phase 10 — Learning Review

After publication, evaluate the batch as a learning/content system, not only individual videos.

---

## 5. BATCH DEPENDENCY GRAPH

```text
CANONICAL SYSTEM
      ↓
BATCH SLATE
      ↓
OBJECTIVE CARDS
      ↓
SCRIPTS
      ↓
STORYBOARDS
      ↓
SHARED ASSET MATRIX
      ↓
MISSING LEARNING PROPS
      ↓
SCENE PROMPTS
      ↓
SCENE GENERATION
      ↓
VOICE BATCH
      ↓
AUDIO BATCH
      ↓
EDIT BATCH
      ↓
QA
      ↓
PACKAGING
      ↓
PUBLISH
      ↓
LEARNING REVIEW
```

A downstream task must not silently redefine an upstream decision.

---

## 6. SHARED-ASSET ECONOMICS

Before creating a new asset, classify it:

| Type | Action |
|---|---|
| Canonical recurring | use existing canonical |
| Batch recurring | create once, approve, reuse |
| Episode-specific | create for one episode |
| Decorative | prefer existing library |
| Unnecessary | remove |

The goal is to minimize the number of new visual identities created per episode.

---

## 7. BATCH SCENE GENERATION STRATEGY

Do not generate all scenes randomly across all episodes.

Preferred grouping:

### Group A — Character-facing shots

Opening, CTA, review, achievement, closing.

### Group B — Same-location learning shots

Object discovery and quiz shots.

### Group C — Activity shots

Drawing, sorting, counting, matching, building.

### Group D — Special locations

Only when an episode requires a new world.

This allows visual comparison between generations and makes drift easier to detect.

---

## 8. REFERENCE PACK PER EPISODE

Every episode receives a compact reference pack containing:

1. Rere canonical character
2. required outfit
3. expression/gesture references
4. primary world
5. recurring props
6. episode learning props
7. camera presets
8. lighting preset
9. voice direction
10. relevant audio cues
11. storyboard
12. negative prompt

No scene should be generated without a complete reference pack.

---

## 9. BATCH NAMING

Batch:

`RERE-BATCH-001`

Episode:

`RERE-EP-001`

Scene:

`RERE-EP-001-S01`

Asset:

`RERE-ASSET-[TYPE]-[NAME]-V01`

Examples:

`RERE-EP-004-S07`  
`RERE-ASSET-LEARNING-RED-APPLE-V01`

---

## 10. VERSION RULE

Batch versioning:

`BATCH-001-V01`

Episode versioning remains independent:

`EP-001-SCRIPT-V01`

If a shared canonical asset changes, create a new canonical version and document all affected episodes.

Never silently update a shared reference while episodes are in production.

---

## 11. BATCH FREEZE

Before scene generation, freeze:

- character
- outfit
- primary world
- recurring props
- learning objective
- script
- storyboard
- camera language
- lighting language

This is the **Production Freeze**.

After freeze, changes require an explicit revision.

---

## 12. BATCH QA MATRIX

Each episode is scored independently, then compared across the batch.

| Area | Episode QA | Batch QA |
|---|---|---|
| Character | identity match | cross-episode consistency |
| World | location match | recurring location continuity |
| Props | object match | recurring prop consistency |
| Voice | Rere identity | voice session consistency |
| Audio | mix quality | sonic identity consistency |
| Learning | objective achieved | progression across episodes |
| Editing | child-friendly pacing | consistent rhythm |
| Packaging | honest promise | visual/title family consistency |

---

## 13. BATCH REJECTION CONDITIONS

Reject or pause the batch when:

- canonical Rere drifts across episodes
- same recurring prop appears in multiple designs
- same location changes architecture unexpectedly
- educational progression is incoherent
- voice identity changes
- batch becomes visually repetitive without meaningful variation
- batch becomes overstimulating
- packaging creates misleading expectations

---

## 14. PARALLELIZATION RULES

Safe to parallelize:

- objective-card drafting after topic selection
- episode scripts after shared learning progression is locked
- learning-prop exploration for independent objects
- thumbnail concept exploration
- metadata drafting

Do not parallelize without a locked dependency:

- scene generation before canonical asset approval
- scene generation before storyboard lock
- animation before voice timing is sufficiently stable
- final packaging before episode content is locked

---

## 15. BATCH REVIEW CEREMONY

Before publishing a batch:

### Review A — Watch individually

Each episode must work by itself.

### Review B — Watch consecutively

Look for:

- repeated gestures becoming annoying
- repeated music patterns
- visual fatigue
- inconsistent character identity
- learning progression gaps

### Review C — Parent perspective

Can a parent trust the whole set?

### Review D — Child perspective

Can a child follow, participate, and recognize the recurring Rere world?

---

## 16. BATCH DASHBOARD REQUIRED FIELDS

| Field | Description |
|---|---|
| Batch ID | unique batch identifier |
| Episode ID | episode identifier |
| Cluster | learning/topic cluster |
| Objective | learning promise |
| Pillar | primary pillar |
| World | primary location |
| New assets | assets requiring creation |
| Shared assets | reused canonical assets |
| Script | status/version |
| Storyboard | status/version |
| Scene | generation status |
| Voice | status/version |
| Audio | status/version |
| Edit | status/version |
| QA | status |
| Packaging | status |
| Publish | status |
| Notes | blockers/decisions |

---

## 17. BATCH COMPLETION DEFINITION

A batch is complete only when:

- every episode has passed content QA
- every episode has passed child-centered QA
- canonical consistency is intact
- packaging is approved
- files are versioned
- production decisions are documented
- post-publish learning review can be performed

---

## 18. GOLDEN RULE

> **Batch production is not mass generation. It is controlled reuse.**
