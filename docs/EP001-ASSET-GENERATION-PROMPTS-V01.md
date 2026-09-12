# Rere — EP001 Learning Asset Generation Prompts

**Version:** v1.0  
**Status:** READY FOR GEMINI ASSET BUILD  
**Target:** children age 2–4  
**Episode:** EP001 — Rere Belajar Warna / Petualangan Warna

---

## 1. Purpose

This document is the execution pack for the six learning assets required before EP001 scene generation.

Reference hierarchy follows the Canonical Asset Registry: canonical character/prop/world references are authoritative; a newly generated learning asset must not redefine an existing identity.

### Required shared visual references

Attach only relevant references, with this priority:

1. `assets/character/rere-character-sheet-canonical.png` — when Rere appears in the reference composition.
2. `assets/props/utility/rere-crayon-kit-canonical.png` — for the drawing/learning context.
3. `assets/environment/rere-world-playroom-canonical.png` — for contextual scene assets.
4. `rere-learning-colors-sheet-canonical.png` — authoritative learning-color visual language.

For isolated learning-object generation, Rere itself does not need to appear unless Gemini requires the character reference to maintain universe style.

---

## 2. Universal Asset Prompt

Paste this before the asset-specific instruction:

> Create a production-ready educational learning asset for the Rere preschool universe. Use the attached approved Rere references and learning-color reference as authoritative visual sources. Preserve the soft pastel 3D CGI/kawaii visual language, rounded child-safe forms, clean readable silhouettes, warm friendly presentation, gentle materials, and restrained pink signature accent. The asset is for children age 2–4, so the learning target must be immediately recognizable. Keep the composition simple and uncluttered. Do not redesign Rere, recurring props, or recurring environments. Do not introduce random decorative objects. Create a clean reference-ready visual that can be reused consistently in multiple episode shots. No watermark, no logo, no photorealism, no scary mood, no malformed geometry, no text artifacts.

### Universal negative prompt

> no character redesign, no face drift, no adult proportions, no photorealism, no scary or uncanny mood, no clutter, no random props, no unnecessary decoration, no ambiguous answer, no malformed geometry, no duplicate object unless explicitly requested, no watermark, no logo, no text artifacts, no excessive bloom, no extreme depth of field, no excessive saturation, no visual noise.

---

# 3. Asset A — Red Apple

**Asset ID:** `RERE-LEARN-EP001-APPLE-01`  
**Output:** `RERE-EP001-ASSET-RED-APPLE-V01.png`

### Prompt

> Create one friendly preschool learning object: a clearly recognizable red apple. The apple must have a simple rounded silhouette, natural but stylized apple shape, red as the dominant and unmistakable color, with a small green leaf and short brown stem. Use soft pastel 3D CGI/kawaii rendering consistent with Rere. Present the apple isolated on a clean neutral background as a reference asset. The red body must be visually dominant; the green leaf must remain small and must not compete with the learning target. No other fruit or object.

### QA

- [ ] unmistakably an apple
- [ ] red is dominant
- [ ] one apple only
- [ ] clean silhouette
- [ ] no competing objects
- [ ] style matches Rere learning library

---

# 4. Asset B — Yellow Banana

**Asset ID:** `RERE-LEARN-EP001-BANANA-01`  
**Output:** `RERE-EP001-ASSET-YELLOW-BANANA-V01.png`

### Prompt

> Create one friendly preschool learning object: a clearly recognizable yellow banana. Use a simple curved banana silhouette with yellow as the overwhelmingly dominant color and subtle natural brown tips. Soft pastel 3D CGI/kawaii rendering, rounded and child-safe. Present one banana isolated on a clean neutral background as a reusable reference asset. The shape must be immediately recognizable to a 2–4-year-old. No bunch of bananas and no other fruit.

### QA

- [ ] unmistakably a banana
- [ ] yellow is dominant
- [ ] one banana only
- [ ] clear curved silhouette
- [ ] no competing objects

---

# 5. Asset C — Blue Ball

**Asset ID:** `RERE-LEARN-EP001-BALL-01`  
**Output:** `RERE-EP001-ASSET-BLUE-BALL-V01.png`

### Prompt

> Create one simple preschool learning object: a round blue ball. The ball must have a clean circular silhouette and blue as the dominant unmistakable color. Use a soft pastel 3D CGI/kawaii material with very subtle surface detail only. Present exactly one ball isolated on a clean neutral background. Avoid stripes, logos, letters, numbers, patterns, or secondary colors that could make the learning color ambiguous.

### QA

- [ ] perfectly/readably round
- [ ] blue is dominant
- [ ] exactly one ball
- [ ] no logo/text/pattern
- [ ] no ambiguous secondary color

---

# 6. Asset D — Green Plant / Leaf

**Asset ID:** `RERE-LEARN-EP001-PLANT-01`  
**Output:** `RERE-EP001-ASSET-GREEN-PLANT-V01.png`

### Prompt

> Create one friendly preschool learning object: a small potted green plant. The leaves must be the clear visual focus and green must be the dominant learning color. Use a simple child-safe rounded plant with several broad readable green leaves and a simple small neutral/pastel pot. Soft pastel 3D CGI/kawaii rendering consistent with Rere. Present one plant isolated on a clean neutral background. Keep the pot visually secondary and avoid flowers or colorful decorations.

### QA

- [ ] immediately recognizable as a plant
- [ ] green leaves dominate
- [ ] one plant only
- [ ] pot does not compete with green
- [ ] no flowers/decorative distractions

---

# 7. Asset E — Pink Flower

**Asset ID:** `RERE-LEARN-EP001-FLOWER-01`  
**Output:** `RERE-EP001-ASSET-PINK-FLOWER-V01.png`

### Prompt

> Create one friendly preschool learning object: a simple pink flower. Use a clearly readable flower silhouette with pink petals as the dominant and unmistakable learning color, plus a small simple green stem and leaves. Soft pastel 3D CGI/kawaii rendering consistent with Rere. Present one flower isolated on a clean neutral background. Keep the flower simple enough for a 2–4-year-old to identify immediately. No bouquet and no additional flowers.

### QA

- [ ] unmistakably a flower
- [ ] pink petals dominate
- [ ] exactly one flower
- [ ] green stem is secondary
- [ ] no bouquet or distractions

---

# 8. Asset F — Quiz Object Set

**Asset ID:** `RERE-LEARN-EP001-QUIZ-SET-01`  
**Output:** `RERE-EP001-ASSET-QUIZ-SET-V01.png`

### Prompt

> Create a clean preschool color-learning quiz reference set containing exactly five clearly separated objects: one red apple, one yellow banana, one blue ball, one green potted plant, and one pink flower. Each object must use the approved individual learning-object designs where available. Arrange the five objects with generous spacing so each object is instantly distinguishable. There must be exactly one representative of each target color: red, yellow, blue, green, pink. No additional objects, duplicate objects, extra colors that could become answers, labels, letters, numbers, or decorative elements. Use the same soft pastel 3D CGI/kawaii visual language as the individual assets.

### Critical QA

- [ ] exactly 5 objects
- [ ] exactly 1 red apple
- [ ] exactly 1 yellow banana
- [ ] exactly 1 blue ball
- [ ] exactly 1 green plant
- [ ] exactly 1 pink flower
- [ ] all five are visually distinct
- [ ] no alternative answer
- [ ] style/scale relationship is coherent

---

# 9. Gemini Execution Order

Generate in this order:

1. Red Apple
2. Yellow Banana
3. Blue Ball
4. Green Plant
5. Pink Flower
6. Quiz Object Set **only after A–E are approved**

For A–E, if a result fails QA, regenerate that asset only. Do not allow a failed asset to become a reference for another asset.

For F, attach the approved A–E assets and instruct Gemini to preserve their individual identity.

---

# 10. Approval Gate

An asset is **LOCKED** only after human review. Once approved, use the exact approved output as the source reference for EP001 scene generation. Never ask Gemini to recreate the asset from the text description when the approved image exists.

**Rule:** Generate the learning object once, approve it once, reuse it everywhere.
