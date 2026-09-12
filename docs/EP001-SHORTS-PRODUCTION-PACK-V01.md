# RERE EP001 — SHORTS PRODUCTION PACK V01

**Episode:** EP001 — Rere Belajar Warna / Petualangan Warna untuk Anak  
**Batch:** 001  
**Target:** 2–4 tahun  
**Format:** YouTube Shorts / vertical 9:16  
**Baseline:** 5 Shorts  
**Primary pillar:** DISCOVER  
**Secondary:** SPEAK / CREATE  
**Learning target:** mengenali dan menyebutkan merah, kuning, biru, hijau, dan pink melalui benda familiar.  
**Source authority:** `docs/EPISODE-001-STORYBOARD-PRODUCTION-MASTER-V02.md`  
**Shorts system:** `docs/BATCH-001-SHORTS-MASTER-V01.md`

---

## 1. PRODUCTION DECISION

EP001 menghasilkan lima Shorts mikro-pembelajaran dari lima learning-object scenes pada long-form:

| Short | Source | Concept | Expected action |
|---|---|---|---|
| SH01 | EP001 S04 | Merah / apel | menunjuk / menyebut |
| SH02 | EP001 S05 | Kuning / pisang | menunjuk / menyebut |
| SH03 | EP001 S06 | Biru / bola | menunjuk / menyebut |
| SH04 | EP001 S07 | Hijau / tanaman | menunjuk / menyebut |
| SH05 | EP001 S08 | Pink / bunga | menunjuk / menyebut |

**Default strategy:** reuse approved long-form visual wherever technically safe. Do not regenerate merely to make the Short look different.

**Vertical generation trigger:** only if 9:16 crop causes any of these failures: Rere face cropped, target object unclear, action unreadable, canonical prop/object distorted, important interaction outside safe area, or composition becomes visually confusing.

---

# 2. GLOBAL SHORTS SPEC

## 2.1 Runtime

Target: **22–35 seconds** per Short.

Acceptable range: **15–45 seconds** if learning clarity requires it.

Do not stretch a Short to hit a duration target. A shorter clear learning interaction is preferable to filler.

## 2.2 Vertical format

- Aspect ratio: **9:16**
- Recommended master: **1080 × 1920 minimum**
- Keep face + learning object in central safe region.
- Do not place critical object/word at extreme top/bottom UI zones.
- Prefer medium/close framing.

## 2.3 Interaction pattern

**HOOK → QUESTION → PAUSE → ANSWER → REWARD → MICRO-CLOSE**

The child must have a genuine opportunity to respond before the answer appears.

## 2.4 Voice

Rere voice follows `docs/VOICE-BIBLE-RERE.md`.

Delivery:
- warm
- cheerful
- clear
- preschool-appropriate
- not rushed
- slightly curious before PAUSE
- positive after answer

Do not overact or shout.

## 2.5 Music/SFX

Voice is priority.

During PAUSE:
- reduce music density
- no distracting SFX
- keep target object visible

Use a tiny recognition/reward cue after answer if consistent with Audio Identity Bible.

---

# 3. CANONICAL REFERENCE PACKAGE

Every Short uses the minimum relevant canonical references, in this order:

1. `assets/character/rere-character-sheet-canonical.png`
2. relevant expression/gesture reference when needed
3. approved EP001 outfit reference
4. `assets/environment/rere-world-environment-sheet-canonical.png` / approved Playroom reference
5. learning object canonical reference
6. source-shot reference if available
7. this production record

Reference hierarchy remains:

**Identity → Face → Anatomy → Outfit → Gesture/Expression → World → Props → Scene**

Never allow the learning object to override Rere identity.

---

# 4. UNIVERSAL GEMINI PROMPT ANCHOR

Use this anchor before the Short-specific scene instruction:

```text
Use the attached canonical Rere references as the authoritative source of identity.
Preserve the exact face structure, large brown eyes, curled eyelashes, distinctive nose,
distinctive small smiling lip shape, canonical preschool proportions, dark hair and
single high fountain ponytail, and approved Rere outfit.

Use the attached canonical Playroom/world and learning-object references as authoritative.
Do not redesign Rere, the environment, or the learning object.

Visual style: warm soft pastel 3D CGI/kawaii, rounded child-safe forms, clean friendly
preschool world, soft warm diffused lighting, gentle depth of field, expressive but
natural child emotion, educational without looking institutional.

Composition is designed for 9:16 vertical video. Keep Rere's face and the learning object
inside a central safe area. The learning object must remain clearly visible throughout
question and PAUSE moments.

Motion is gentle and readable. No unnecessary camera movement, no rapid cuts, no visual
chaos. Preserve physical plausibility and continuity.
```

Universal negative:

```text
no character redesign, no face drift, no hairstyle drift, no outfit drift, no adult
proportions, no photorealism, no scary mood, no uncanny face, no extra fingers, no extra
limbs, no malformed hands, no duplicate objects, no missing objects, no object morphing,
no prop redesign, no environment redesign, no random props, no clutter, no excessive bloom,
no excessive saturation, no rapid camera movement, no extreme perspective, no text artifacts,
no watermark, no logo, no UI elements, no impossible physics, no teleporting objects,
no distracting background action
```

---

# 5. SH01 — MERAH / APEL

## Identity

**Short ID:** `RERE-B001-EP001-SH01`  
**Source:** EP001 S04 — Red Apple  
**Learning word:** merah  
**Expected action:** anak menunjuk atau menyebut warna merah  
**Recommended duration:** 24–30s

## Learning objective

Setelah menonton, anak mendapat kesempatan mengenali warna **merah** pada benda familiar, yaitu apel.

## Shot architecture

| Beat | Time | Visual | Audio/dialogue | Edit |
|---|---:|---|---|---|
| Hook | 0:00–0:03 | Rere + apel clearly visible | “Teman-teman, lihat!” | Immediate cut-in |
| Question | 0:03–0:07 | Rere points to apple | “Apel ini warna apa?” | Hold |
| PAUSE | 0:07–0:11 | Apple remains large/clear; Rere waits | no answer; light ambience | 4s hold |
| Reveal | 0:11–0:16 | Rere smiles, confirms apple | “Betul! Merah!” | Gentle emphasis |
| Reinforce | 0:16–0:22 | Rere + apple | “Merah seperti apel!” | Simple push/hold |
| Close | 0:22–0:26 | Rere friendly gesture | “Hebat!” | End |

## Exact voice script

```text
RERE:
“Teman-teman, lihat!”

RERE:
“Apel ini warna apa?”

[PAUSE — 4 sec]

RERE:
“Betul! Merah!”

RERE:
“Merah seperti apel!”

RERE:
“Hebat!”
```

## Performance

Before question: curious, inviting.  
During PAUSE: eyes toward apple/camera, smile, no talking.  
After PAUSE: small excited smile, not exaggerated.

## Visual requirements

- apple is unmistakably red
- apple remains singular and stable
- Rere points naturally
- hand does not cover apple
- no other strongly colored object competes with red target
- background remains calm

## Vertical crop rule

If source S04 can be cropped to 9:16 while preserving Rere face + apple, reuse it. Otherwise generate a dedicated close-medium vertical derivative from canonical references.

## Dedicated vertical prompt

```text
Create a 9:16 vertical preschool learning shot based on the attached canonical Rere
character and attached canonical EP001 Playroom and red apple references.

Rere stands/sits naturally in the approved Playroom. A single clearly visible red apple
is the learning target. Rere gently points toward the apple and looks between the apple
and the viewer with a curious friendly expression. The apple is large enough to be
recognized immediately but remains physically child-scale.

Hold a stable composition suitable for a child to answer the question “Apel ini warna apa?”
with a clean 4-second visual PAUSE. During the PAUSE, keep Rere and the apple still enough
for processing. No new objects enter the frame.

9:16 vertical composition, central safe area, medium-close framing, soft warm diffused
lighting, warm pastel 3D CGI/kawaii, clean child-safe Playroom, gentle natural motion.

Preserve canonical identity and canonical apple design exactly.
```

## Edit notes

- Do not cut during PAUSE.
- Optional 1–2% digital push only if source resolution permits and it does not create a new camera feel.
- Answer “Merah!” should land immediately after PAUSE.
- Keep on-screen text optional; if used, show only **MERAH** after answer, not during the question.

## QA acceptance

- [ ] Rere identity canonical
- [ ] one apple only
- [ ] apple clearly red
- [ ] question understandable
- [ ] 4s PAUSE intact
- [ ] answer follows pause
- [ ] no competing red object
- [ ] face and apple survive 9:16

---

# 6. SH02 — KUNING / PISANG

**Short ID:** `RERE-B001-EP001-SH02`  
**Source:** EP001 S05 — Yellow Banana  
**Learning word:** kuning  
**Expected action:** menunjuk / menyebut  
**Recommended duration:** 24–30s

## Exact voice script

```text
RERE:
“Teman-teman, lihat pisang!”

RERE:
“Pisang ini warna apa?”

[PAUSE — 4 sec]

RERE:
“Betul! Kuning!”

RERE:
“Pisangnya berwarna kuning!”

RERE:
“Hebat!”
```

## Shot architecture

| Beat | Time | Visual | Audio |
|---|---:|---|---|
| Hook | 0:00–0:03 | Rere + single banana | “Teman-teman, lihat pisang!” |
| Question | 0:03–0:07 | Rere points | “Pisang ini warna apa?” |
| PAUSE | 0:07–0:11 | Stable target | silence/light ambience |
| Reveal | 0:11–0:16 | smile + banana | “Betul! Kuning!” |
| Reinforce | 0:16–0:22 | banana remains visible | “Pisangnya berwarna kuning!” |
| Close | 0:22–0:26 | Rere gesture | “Hebat!” |

## Visual constraints

- one banana only
- banana must be clearly yellow
- no yellow competing target near it
- no color shift during motion
- no text before answer

## Gemini vertical prompt

```text
Create a 9:16 vertical preschool learning shot using the attached canonical Rere,
Playroom, and yellow banana references.

Rere warmly presents one clearly recognizable yellow banana and gently points to it.
Rere asks the viewer to identify its color. Hold the exact composition long enough for a
4-second child response pause. Keep the banana visible, stable, and unobstructed.

The scene is calm, warm, playful, soft pastel 3D CGI/kawaii, child-safe, rounded,
with soft diffused lighting. No unrelated props enter the frame. Preserve exact canonical
Rere identity, outfit, Playroom continuity, and banana appearance.
```

## Edit/QA

Same global rules as SH01. Additional checks:

- [ ] banana silhouette remains recognizable
- [ ] yellow is visually clear and not washed out by lighting
- [ ] no banana duplication/morphing
- [ ] 4s PAUSE is uninterrupted

---

# 7. SH03 — BIRU / BOLA

**Short ID:** `RERE-B001-EP001-SH03`  
**Source:** EP001 S06 — Blue Ball  
**Learning word:** biru  
**Expected action:** menunjuk / menyebut  
**Recommended duration:** 24–30s

## Exact voice script

```text
RERE:
“Wah, ada bola!”

RERE:
“Bola ini warna apa?”

[PAUSE — 4 sec]

RERE:
“Betul! Biru!”

RERE:
“Bola ini berwarna biru!”

RERE:
“Hebat!”
```

## Shot architecture

| Beat | Time | Visual | Audio |
|---|---:|---|---|
| Hook | 0:00–0:03 | Rere + one blue ball | “Wah, ada bola!” |
| Question | 0:03–0:07 | Rere points | “Bola ini warna apa?” |
| PAUSE | 0:07–0:11 | ball stable | light ambience |
| Reveal | 0:11–0:16 | smile/reward | “Betul! Biru!” |
| Reinforce | 0:16–0:22 | ball visible | “Bola ini berwarna biru!” |
| Close | 0:22–0:26 | friendly gesture | “Hebat!” |

## Visual constraints

- one ball only
- blue is unmistakable
- ball cannot roll out during question/PAUSE
- no second ball in background
- Rere's hand must not obscure target

## Gemini vertical prompt

```text
Create a 9:16 vertical preschool learning shot using canonical Rere, canonical Playroom,
and the attached canonical blue ball reference.

Show Rere presenting one clearly visible blue ball. Rere points gently to the ball and
looks toward the viewer. The ball remains stationary and fully readable during a 4-second
response pause. No second ball appears anywhere in the frame.

Keep the camera stable and child-friendly. Use medium-close vertical framing, soft warm
pastel 3D CGI/kawaii, diffused lighting, rounded child-safe design, natural expression,
and minimal background movement.

Do not redesign Rere, the Playroom, or the ball.
```

## QA

- [ ] exactly one ball
- [ ] ball clearly blue
- [ ] no rolling/morphing during PAUSE
- [ ] Rere face visible
- [ ] 4s PAUSE
- [ ] answer timing clean

---

# 8. SH04 — HIJAU / TANAMAN

**Short ID:** `RERE-B001-EP001-SH04`  
**Source:** EP001 S07 — Green Plant  
**Learning word:** hijau  
**Expected action:** menunjuk / menyebut  
**Recommended duration:** 24–32s

## Exact voice script

```text
RERE:
“Teman-teman, coba lihat tanaman!”

RERE:
“Tanaman ini warna apa?”

[PAUSE — 4 sec]

RERE:
“Iya! Hijau!”

RERE:
“Daunnya berwarna hijau!”

RERE:
“Hebat!”
```

## Shot architecture

| Beat | Time | Visual | Audio |
|---|---:|---|---|
| Hook | 0:00–0:03 | Rere + plant | “Coba lihat tanaman!” |
| Question | 0:03–0:07 | point to green leaves | “Tanaman ini warna apa?” |
| PAUSE | 0:07–0:11 | leaves clearly visible | light ambience |
| Reveal | 0:11–0:16 | smile | “Iya! Hijau!” |
| Reinforce | 0:16–0:23 | plant close enough | “Daunnya berwarna hijau!” |
| Close | 0:23–0:27 | Rere gesture | “Hebat!” |

## Visual constraints

- plant should have clearly green leaves
- avoid many other green objects that create ambiguity
- plant remains in place
- leaf geometry must not morph
- background stays quiet

## Gemini vertical prompt

```text
Create a 9:16 vertical preschool learning shot using the attached canonical Rere,
Playroom, and canonical green plant/leaf reference.

Rere discovers a friendly child-safe plant and gently points toward its clearly green
leaves. The leaves are the learning target. Keep the plant and Rere visible in a stable
composition while the child has a 4-second opportunity to answer the color question.

The plant does not move unnaturally and its leaf shapes do not change. Avoid adding other
strong green objects that could create a second plausible answer.

Warm soft pastel 3D CGI/kawaii, clean rounded preschool environment, soft warm diffused
lighting, medium-close 9:16 framing, minimal background motion, canonical identity and
continuity preserved.
```

## QA

- [ ] green target unambiguous
- [ ] no competing green answer
- [ ] plant stable
- [ ] Rere canonical
- [ ] 4s PAUSE
- [ ] no leaf morphing

---

# 9. SH05 — PINK / BUNGA

**Short ID:** `RERE-B001-EP001-SH05`  
**Source:** EP001 S08 — Pink Flower  
**Learning word:** pink / merah muda  
**Expected action:** menunjuk / menyebut  
**Recommended duration:** 24–32s

## Language decision

For ages 2–4, keep the spoken label simple and consistent with EP001 master vocabulary: **pink**. If Indonesian explanatory text is used, “merah muda” may appear after the answer, but do not introduce two competing spoken labels in the same recognition beat.

## Exact voice script

```text
RERE:
“Wah, ada bunga!”

RERE:
“Bunga ini warna apa?”

[PAUSE — 4 sec]

RERE:
“Betul! Pink!”

RERE:
“Bunganya berwarna pink!”

RERE:
“Hebat!”
```

## Shot architecture

| Beat | Time | Visual | Audio |
|---|---:|---|---|
| Hook | 0:00–0:03 | Rere + one pink flower | “Wah, ada bunga!” |
| Question | 0:03–0:07 | point to flower | “Bunga ini warna apa?” |
| PAUSE | 0:07–0:11 | flower clear/stable | light ambience |
| Reveal | 0:11–0:16 | smile | “Betul! Pink!” |
| Reinforce | 0:16–0:23 | flower visible | “Bunganya berwarna pink!” |
| Close | 0:23–0:27 | friendly gesture | “Hebat!” |

## Visual constraints

- one clear pink flower as target
- no competing pink object in immediate focal area
- flower remains stable
- color remains pink under lighting
- avoid excessive pink decoration because pink is the target

## Gemini vertical prompt

```text
Create a 9:16 vertical preschool learning shot using the attached canonical Rere,
canonical Playroom, and canonical pink flower reference.

Rere happily notices one clearly visible pink flower and gently points toward it. The
flower is the single learning target. Keep the flower large enough to identify while
maintaining child-scale proportions. Hold a stable 4-second response pause with no new
objects entering the frame and no distracting motion.

Use warm soft pastel 3D CGI/kawaii, clean rounded child-safe design, soft diffused light,
gentle depth of field, medium-close 9:16 framing. Preserve exact Rere identity, approved
outfit, Playroom continuity, and canonical flower design.
```

## QA

- [ ] pink target unambiguous
- [ ] no competing pink object
- [ ] flower stable
- [ ] Rere canonical
- [ ] 4s PAUSE
- [ ] spoken label remains “pink”

---

# 10. CROSS-SHORT EDITING TEMPLATE

Use the same edit rhythm for all five Shorts to create recognizable Rere packaging:

```text
00:00 — visual hook
00:02/03 — question begins
00:06/07 — question ends
00:07 — PAUSE begins
00:11 — answer/reveal
00:16 — repetition/context
00:22–00:27 — reward + micro-close
```

Do not force identical duration. Preserve the same **interaction rhythm**, not mechanical timestamps.

## Transition rules

- Prefer direct cut or gentle dissolve.
- Avoid whip pans, spins, zoom explosions, glitch effects, strobe effects, or meme-style transitions.
- No transition may occur during PAUSE.

## On-screen text

Default: **none during question/PAUSE**.

Optional after answer:

- MERAH
- KUNING
- BIRU
- HIJAU
- PINK

Typography must follow Rere brand rules and remain secondary to Rere/learning object.

---

# 11. VOICE / AUDIO MASTERING CHECKLIST

For each Short:

- [ ] voice recorded/generated from locked script
- [ ] pronunciation reviewed
- [ ] child-friendly pace
- [ ] question has clear intonation
- [ ] PAUSE is actual silence/low-density audio, not filled with speech
- [ ] answer is clearly articulated
- [ ] music below voice
- [ ] no SFX masks consonants
- [ ] no clipping/distortion
- [ ] beginning and ending are clean

---

# 12. VIDEO QA — EP001 SHORTS

## P0 — Automatic reject

- unsafe content
- malformed child anatomy
- identity unusable
- learning answer visually wrong
- duplicated/missing learning object causing wrong lesson

## P1 — Reject/revise

- Rere face drift
- outfit drift
- Playroom continuity drift
- learning object redesign
- wrong color
- answer ambiguity
- missing PAUSE
- severe crop failure
- broken physical action
- voice inconsistency

## P2 — Revise when useful

- minor framing imbalance
- minor timing issue
- small background distraction
- unnecessary text

## P3 — Cosmetic

- tiny polish issue with no learning impact

---

# 13. SHORT SCORECARD

Score each Short 0–2 on:

1. Identity
2. Learning clarity
3. Child participation
4. PAUSE quality
5. Object clarity
6. Vertical composition
7. Continuity
8. Voice
9. Audio mix
10. Motion

**18–20:** APPROVE  
**15–17:** REVISE  
**<15:** REJECT  

P0/P1 overrides score.

---

# 14. FILE / ASSET NAMING

Use the Short ID consistently:

```text
RERE-B001-EP001-SH01-script-v01
RERE-B001-EP001-SH01-storyboard-v01
RERE-B001-EP001-SH01-prompt-v01
RERE-B001-EP001-SH01-voice-v01
RERE-B001-EP001-SH01-edit-v01
RERE-B001-EP001-SH01-master-v01
RERE-B001-EP001-SH01-qa-v01
```

Same pattern for SH02–SH05.

---

# 15. PRODUCTION CHECKLIST

## Before generation

- [ ] long-form source shot approved
- [ ] canonical Rere attached
- [ ] correct outfit attached
- [ ] Playroom reference attached
- [ ] correct learning-object reference attached
- [ ] source crop tested

## Generate only if needed

- [ ] dedicated 9:16 prompt used
- [ ] no canonical redesign
- [ ] no extra objects
- [ ] learning target dominant

## Before edit

- [ ] visual approved
- [ ] voice approved
- [ ] source shot / generated shot ID recorded

## Before publish

- [ ] vertical master approved
- [ ] audio approved
- [ ] QA score ≥18 or explicitly approved after minor revision
- [ ] title matches actual learning content
- [ ] thumbnail/frame is honest
- [ ] related long-form episode recorded

---

# 16. EP001 SHORTS MASTER MATRIX

| ID | Color | Source | PAUSE | Primary object | Preferred strategy |
|---|---|---|---:|---|---|
| SH01 | Merah | S04 | 4s | Apple | Reuse/crop |
| SH02 | Kuning | S05 | 4s | Banana | Reuse/crop |
| SH03 | Biru | S06 | 4s | Ball | Reuse/crop |
| SH04 | Hijau | S07 | 4s | Plant | Reuse/crop |
| SH05 | Pink | S08 | 4s | Flower | Reuse/crop |

**Production rule:** test crop first. Generate vertical derivative second.

---

# 17. HANDOFF TO EP001 EDIT

The editor receives:

1. approved source shot or dedicated vertical shot
2. approved Rere voice
3. music/audio identity assets
4. this production pack
5. QA checklist

The editor does not alter:

- Rere identity
- learning object design
- learning target
- question wording without script revision
- PAUSE removal

Any substantive change returns the Short to the relevant production gate.

---

# 18. DEFINITION OF DONE

EP001 Shorts are complete only when all five IDs have:

- approved source/generated visual
- approved voice
- finished vertical edit
- intact learning interaction
- QA pass
- final master
- publishing metadata
- link to related EP001 long-form

**EP001 Shorts Production Pack V01 is the detailed template to be adapted for EP002–EP006.**
