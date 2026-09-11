# Rere Production Workflow — Gemini

**Status:** Working Workflow — 2026-09-11

## Purpose

Dokumen ini mendefinisikan bagaimana Gemini digunakan dalam produksi konten Rere tanpa menggantikan Rere's educational strategy, quality standards, atau human judgment.

## Principle

**Strategy is upstream. Production is downstream.**

Gemini menerima brief yang berasal dari framework Rere. Gemini membantu mempercepat produksi, tetapi tidak menentukan sendiri apa yang seharusnya dipelajari anak.

## Production Pipeline

```text
LEARNING FRAMEWORK
        ↓
EPISODE BRIEF
        ↓
GEMINI PRODUCTION
        ↓
QUALITY REVIEW
        ↓
FINAL SCRIPT / VISUAL / AUDIO ASSETS
        ↓
EDITING
        ↓
PUBLISH
        ↓
AUDIENCE FEEDBACK & ANALYTICS
        ↓
LEARNING LOOP
```

## Gemini Responsibilities

Gemini dapat digunakan untuk:

- generating episode concepts from an approved learning objective
- script drafting
- scene-by-scene breakdown
- dialogue drafting
- child-friendly wording variations
- Indonesian/English language variations
- visual prompt development
- character interaction ideas
- song/chant concept development
- repetition and interaction design
- title/description draft generation
- production checklists
- alternative versions for testing

## Rere Responsibilities

Rere's strategy layer remains responsible for:

- target age and developmental appropriateness
- learning objectives
- core/supporting domain classification
- educational philosophy
- language strategy
- values and safety principles
- character and brand rules
- episode structure
- quality standards
- final approval

## Human Review Gate

Every production output should pass review before publication.

Minimum review:

1. **Educational:** apakah learning objective benar-benar tercapai?
2. **Developmental:** apakah sesuai untuk anak usia 2–4?
3. **Language:** apakah Bahasa Indonesia dan English natural, jelas, dan tidak terlalu kompleks?
4. **Emotional/Safety:** apakah ada pesan yang berpotensi menakut-nakuti, mempermalukan, atau menyesatkan anak?
5. **Brand:** apakah karakter, tone, visual direction, dan nilai Rere konsisten?
6. **Production:** apakah scene dapat dibuat secara realistis dengan tools yang tersedia?

## Episode Brief Contract

Sebelum meminta Gemini menghasilkan konten, brief minimal harus berisi:

- Episode ID
- Working title
- Target age
- Primary learning pillar
- Primary learning objective
- Supporting learning outcomes
- Key vocabulary / phrases jika relevan
- Main situation or story
- Character(s)
- Desired emotional tone
- Interaction moments / pauses
- Indonesian-English direction
- Safety or sensitivity notes
- Expected output format

## Example

```text
Episode ID: FEEL-001
Target age: 2–4
Primary pillar: FEEL
Primary objective: mengenali perasaan sedih dan meminta bantuan
Supporting: SPEAK — sad, help, please
Story: Rere kehilangan mainan kesayangannya
Interaction: pause after Rere notices the toy is missing
Language: Indonesian context + simple English exposure
Tone: warm, playful, reassuring
Safety: do not shame crying; do not imply sadness is wrong
```

## Production Rule

Jangan memberikan Gemini brief yang terlalu terbuka seperti:

> "Buatkan video edukasi anak usia 2–4 tahun."

Lebih baik:

> "Gunakan episode brief Rere berikut. Jangan mengubah primary learning objective. Buat script dengan format scene, dialogue, action, visual direction, interaction pause, dan English exposure sesuai aturan brief."

## Versioning

Production outputs sebaiknya memiliki ID dan versi agar mudah dibandingkan.

Contoh:

- `FEEL-001-v01`
- `FEEL-001-v02`
- `FEEL-001-final`

Jika Gemini menghasilkan beberapa alternatif, jangan langsung menganggap versi terbaru sebagai versi terbaik. Pilih berdasarkan quality bar Rere.

## Long-Term Direction

Jika workflow sudah stabil, Rere dapat membangun reusable prompt/template system untuk Gemini berdasarkan:

- learning pillar
- target age
- episode type
- character
- language mix
- scene structure
- interaction pattern
- visual style
- safety rules
- quality checklist

Tujuannya bukan sekadar menghasilkan lebih banyak video, tetapi menghasilkan **lebih banyak konten berkualitas dengan proses yang konsisten**.
