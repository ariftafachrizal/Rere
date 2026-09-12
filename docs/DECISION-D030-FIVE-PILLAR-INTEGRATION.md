# Decision D-030 — Five-Pillar Integration & Learning Standard

**Status:** Approved — 2026-09-12

## Decision

Rere menyatukan lima Core Pillars menjadi satu **Three-Year Learning Architecture** yang digunakan sebagai sumber kebenaran untuk curriculum dan episode design:

1. DISCOVER — Understand the World
2. SPEAK — Communicate with the World
3. FEEL — Understand Myself & Others
4. LIVE — Care for Myself, Others & My World
5. CREATE — Imagine, Express & Make

Kelima pillar adalah learning lenses, bukan lima mata pelajaran terpisah.

## Rules

- Setiap episode memiliki tepat satu Primary Pillar dan satu Primary Learning Intention.
- Supporting Pillars bersifat opsional dan tidak boleh mengambil alih primary intention.
- Cross-domain capabilities bukan pillar keenam.
- Early Literacy dan Early Numeracy adalah cross-domain foundations/capabilities.
- Activity/topic tidak menentukan pillar; learning intention yang menentukan.
- Age adalah developmental reference, bukan cutoff.
- Curriculum tetap fleksibel di atas architecture yang stabil.
- PLAY → EXPERIENCE → IMITATE → LEARN tetap menjadi learning philosophy Rere.
- Gemini production harus diturunkan dari approved Episode Brief dan Learning Standard; Gemini tidak mengubah educational source of truth.

## New Quality Gate

`docs/LEARNING-STANDARD.md` menjadi shared quality gate sebelum episode masuk production.

Episode dapat berstatus:
- PASS
- REVISE
- REDESIGN

Critical safety, developmental, coercion, or architecture failures memblokir production.

## Architecture Documents

- `docs/RERE-THREE-YEAR-LEARNING-ARCHITECTURE.md`
- `docs/LEARNING-STANDARD.md`
- individual pillar frameworks and three-year roadmaps

## Rationale

Integrasi ini mempertahankan breadth perkembangan anak tanpa membuat curriculum menjadi fragmented school subjects. Primary learning tetap jelas, sementara bahasa, numeracy, literacy, motor, social, emotional, creative, dan thinking capabilities dapat tumbuh secara natural melalui pengalaman yang sama.

## Next Phase

Setelah Learning Standard stabil, pekerjaan berikutnya adalah membangun **Episode System**: Episode Brief schema, content taxonomy, format library, mapping ke developmental progression, production handoff ke Gemini, human review, dan feedback loop setelah publish.
