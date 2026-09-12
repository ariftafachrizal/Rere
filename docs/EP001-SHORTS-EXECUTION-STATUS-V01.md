# RERE EP001 — SHORTS EXECUTION STATUS V01

**Episode:** EP001 — Rere Belajar Warna / Petualangan Warna untuk Anak  
**Status:** PRODUCTION-READY / EXECUTION TRACK LOCKED  
**Storyboard:** LOCKED — no storyboard changes permitted  
**Shorts baseline:** 5 outputs  
**Source:** EP001 S04–S08  
**Format:** 9:16 vertical

## 1. Locked production decision

EP001 Shorts are derivatives of the approved long-form scenes. The default production path is:

**Approved long-form source → 9:16 crop/reframe → voice/edit → QA → final master**

Do not regenerate a Gemini scene simply to create a different-looking Short.

A dedicated Gemini vertical derivative is allowed only when the crop fails QA because of:
- Rere face being cropped or unsafe;
- learning object becoming unclear or too small;
- learning action becoming unreadable;
- important interaction falling outside the safe area;
- canonical object/prop distortion;
- confusing composition or continuity failure.

## 2. EP001 Shorts queue

| Short | Long-form source | Learning target | Current execution path |
|---|---|---|---|
| SH01 | S04 | merah / apel | reuse + crop 9:16 |
| SH02 | S05 | kuning / pisang | reuse + crop 9:16 |
| SH03 | S06 | biru / bola | reuse + crop 9:16 |
| SH04 | S07 | hijau / tanaman | reuse + crop 9:16 |
| SH05 | S08 | pink / bunga | reuse + crop 9:16 |

## 3. No storyboard changes

The authoritative long-form production storyboard remains:

`docs/EPISODE-001-STORYBOARD-PRODUCTION-MASTER-V02.md`

The Shorts system is an editing/format derivative and does not modify the long-form storyboard, shot order, learning progression, or canonical episode narrative.

## 4. Shorts editing template

Each Short follows:

**HOOK → QUESTION → PAUSE → ANSWER → REINFORCEMENT/REWARD → MICRO-CLOSE**

Target duration: 22–35 seconds.  
Acceptable duration: 15–45 seconds when required for learning clarity.  
Vertical master: 1080 × 1920 minimum.

During PAUSE:
- preserve uninterrupted visual access to the learning target;
- keep Rere readable;
- remove distracting SFX;
- preserve approximately 4 seconds of response time.

## 5. Gemini policy

Gemini is not required for SH02–SH05 unless the existing approved long-form source fails the vertical crop QA. This is intentional: consistency and canonical continuity have priority over visual novelty.

## 6. Definition of done for each Short

A Short is complete only when all of the following are true:

- source shot approved;
- 9:16 framing approved;
- Rere identity remains canonical;
- learning object is singular, clear, and correct;
- question is understandable;
- response pause is intact;
- answer lands immediately after the pause;
- voice is clean and intelligible;
- music/SFX do not compete with voice;
- final vertical export passes QA;
- final master is stored using the canonical naming convention.

## 7. Important execution boundary

This document records the locked execution path and production control state. It does **not** claim that a final rendered video has been produced unless the corresponding visual/audio master has actually been generated, reviewed, and accepted.

## 8. Forward project rule

Batch 001 currently contains EP001–EP006. After EP006 is completed, the same controlled production system continues through EP036 unless a later explicit project decision changes the scope.

The workflow remains:

**LOCK REFERENCES → PREPARE PROMPTS → GENERATE/REUSE → EDIT → QA → PACKAGE → PUBLISH → LEARNING REVIEW → NEXT EPISODE**
