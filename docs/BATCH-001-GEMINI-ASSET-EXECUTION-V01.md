# Rere — Batch 001 Gemini Asset Execution Protocol

**Version:** v1.0  
**Status:** READY FOR ASSET BUILD

## Objective

Convert the Batch 001 asset manifest into consistent, reviewable Gemini generations before scene generation.

## Mandatory workflow

1. Open `docs/BATCH-001-ASSET-BUILD-MANIFEST-V01.md`.
2. Open the relevant episode asset prompt document.
3. Attach only the required canonical references.
4. Generate one asset at a time.
5. Save/export using the exact proposed filename.
6. Human-review the result.
7. Mark the asset `LOCKED` only after approval.
8. Use the locked asset as the reference for every downstream scene.

## EP001 execution

Use `docs/EP001-ASSET-GENERATION-PROMPTS-V01.md`.

### Pass A — Individual assets

- `RERE-EP001-ASSET-RED-APPLE-V01.png`
- `RERE-EP001-ASSET-YELLOW-BANANA-V01.png`
- `RERE-EP001-ASSET-BLUE-BALL-V01.png`
- `RERE-EP001-ASSET-GREEN-PLANT-V01.png`
- `RERE-EP001-ASSET-PINK-FLOWER-V01.png`

### Pass B — Quiz set

Only after Pass A is approved:

- `RERE-EP001-ASSET-QUIZ-SET-V01.png`

Attach the five approved individual assets when generating the quiz set. Do not regenerate their designs from text alone.

## Gemini response handling

If Gemini produces multiple variants:

- keep only variants that pass the QA gate;
- do not let variant quantity become a reason to accept inconsistent designs;
- select one canonical candidate per Asset ID;
- increment the version when a replacement is materially different (`V02`, `V03`, etc.).

## Reject immediately if

- color is ambiguous;
- silhouette is unclear;
- extra objects create another plausible answer;
- object count is wrong;
- visual style drifts from the Rere universe;
- an existing canonical identity is redesigned;
- geometry is malformed;
- text/watermark/logo appears unintentionally;
- asset cannot be reused consistently across shots.

## Important

This document does not authorize automatic scene generation. Human approval remains the gate between asset generation and episode scene generation.
