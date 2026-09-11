# Rere — Five-Pillar Learning Architecture

**Status:** Approved — 2026-09-11

## Purpose

Dokumen ini menetapkan arsitektur pembelajaran utama Rere untuk fase awal usia **2–4 tahun**.

Rere menggunakan **lima Core Pillars yang saling terhubung**, bukan lima mata pelajaran yang harus diajarkan secara terpisah.

Prinsip utamanya:

> **Satu aktivitas dapat melibatkan banyak domain, tetapi setiap episode harus memiliki satu Primary Learning Intention.**

## Five Core Pillars

### 1. DISCOVER — Understand the World

Fokus pada eksplorasi dan pemahaman dunia.

Contoh area:
- recognition & classification
- patterns and relationships
- early mathematical thinking
- early literacy foundations
- problem solving
- curiosity and exploration
- memory and attention

**Catatan penting:** Early Literacy dan Early Numeracy **bukan Core Area yang berdiri sendiri**. Keduanya merupakan kemampuan/fondasi yang dapat berkembang melalui DISCOVER maupun pillar lainnya.

### 2. SPEAK — Communicate with the World

Fokus pada komunikasi dan exposure English secara natural.

Contoh area:
- listening & comprehension
- functional vocabulary
- functional phrases
- narrative language
- sound awareness
- English exposure

### 3. FEEL — Understand Myself & Others

Fokus pada social-emotional development.

Contoh area:
- emotional recognition & naming
- self-regulation & coping
- social interaction
- empathy & early perspective-taking

### 4. LIVE — Care for Myself, Others & My World

Fokus pada nilai, kehidupan sehari-hari, kemandirian, dan keselamatan.

Contoh area:
- values & respect
- daily life skills & independence
- safety & body/environmental awareness
- responsibility
- healthy habits

### 5. CREATE — Imagine, Express & Make

Fokus pada kreativitas, imajinasi, ekspresi, dan penciptaan.

Contoh area:
- creative expression
- pretend play & imagination
- storytelling & narrative creation
- music, rhythm & movement
- open-ended making & exploration

## Cross-Domain Capabilities

Cross-domain capabilities bukan pillar keenam. Kemampuan ini berkembang melalui kombinasi beberapa pillar.

### Thinking
- curiosity
- attention
- memory
- problem solving
- exploration

### Doing
- fine motor
- gross motor
- coordination
- participation

### Self
- agency & choice
- persistence
- self-regulation

### Social
- communication
- cooperation
- social interaction
- relationship building

### Creative
- imagination
- expression
- experimentation

**PLAY** adalah mekanisme utama yang menghubungkan seluruh capabilities tersebut.

## Primary Learning Intention Rule

Pillar sebuah episode ditentukan oleh **learning intention**, bukan oleh aktivitas, alat, atau topiknya.

Contoh aktivitas balok:

| Learning intention | Primary Pillar |
|---|---|
| Mengenali bentuk | DISCOVER |
| Menghitung balok | DISCOVER |
| Membuat menara sendiri | CREATE |
| Mencari tahu mengapa menara roboh | DISCOVER |
| Bermain bersama teman | FEEL |
| Merapikan balok | LIVE |
| Belajar kata `block`, `big`, `small` | SPEAK |

Dengan demikian, overlap antar-pillar dianggap **fitur arsitektur**, bukan masalah.

## Early Literacy & Early Numeracy as Cross-Domain Foundations

### Early Literacy

Early literacy tidak dibatasi pada episode "belajar huruf".

Ia dapat muncul melalui:
- SPEAK → listening, vocabulary, story and narrative language
- CREATE → membuat cerita, simbol, gambar, dan sequence
- FEEL → menggunakan bahasa untuk mengenali dan mengekspresikan pengalaman
- LIVE → membaca tanda/routine language sederhana dalam konteks nyata
- DISCOVER → noticing symbols, print, sounds, sequences, and books

DISCOVER tetap menjadi rumah utama untuk eksplorasi kognitif yang berkaitan dengan fondasi literasi, tetapi literacy sendiri adalah **cross-domain capability/foundation**.

### Early Numeracy

Early numeracy tidak dibatasi pada episode berhitung.

Ia dapat muncul melalui:
- DISCOVER → quantity, counting, comparison, patterns, classification, spatial relationships
- SPEAK → number words, more/less, big/small, first/next/last
- FEEL → turn-taking dan menunggu giliran dengan urutan sederhana
- LIVE → counting objects dalam rutinitas, sequencing daily tasks
- CREATE → membuat pola, susunan, bentuk, dan konstruksi

DISCOVER tetap menjadi rumah utama untuk eksplorasi mathematical thinking, tetapi numeracy sendiri adalah **cross-domain capability/foundation**.

## What Counts as a Core Pillar?

Core Pillar harus:

1. memiliki tujuan perkembangan yang jelas;
2. memiliki identitas yang berbeda dari pillar lain;
3. cukup luas untuk menghasilkan banyak episode;
4. relevan untuk usia 2–4;
5. dapat berintegrasi dengan pillar lain tanpa kehilangan identitasnya;
6. tidak bergantung pada satu jenis aktivitas saja.

Kelima pillar memenuhi kriteria tersebut.

## What Should NOT Become a Separate Pillar?

Rere tidak membuat pillar terpisah untuk:

- Early Literacy
- Early Numeracy
- Physical Development
- Problem Solving
- Executive Function
- Fine Motor
- Gross Motor
- Curiosity
- Attention & Memory
- Self-Regulation
- Imagination

Semua merupakan foundation, capability, atau developmental process yang dapat tumbuh lintas pengalaman.

## Architecture Model

```text
                         RERE
                          │
                PLAY-BASED LEARNING
                          │
             PLAY → EXPERIENCE →
             IMITATE → LEARN
                          │
        ┌───────── FIVE CORE PILLARS ─────────┐
        │                                      │
        │ DISCOVER   SPEAK   FEEL   LIVE   CREATE
        │                                      │
        └──────────────────────────────────────┘
                          │
                 CROSS-DOMAIN CAPABILITIES
                          │
       Thinking · Doing · Self · Social · Creative
```

Kelima pillar bersifat **parallel dan interconnected**, bukan tahapan linear.

## Episode Architecture

Setiap episode dimulai dengan:

1. **Primary Pillar**
2. **Primary Learning Intention**
3. **Optional Supporting Pillars**
4. **Cross-Domain Capabilities** yang ingin dilatih
5. **Play/Interaction Mechanism**

Contoh:

> Primary Pillar: CREATE
>
> Learning Intention: Anak menciptakan kebun versinya sendiri.
>
> Supporting: DISCOVER + SPEAK + LIVE
>
> Capabilities: imagination, agency, fine motor, communication, exploration.

## Design Principle

Rere tidak mengejar jumlah domain dalam satu video.

Targetnya adalah:

> **Clear primary learning + rich natural integration.**

Satu episode tidak perlu mengajarkan lima pillar sekaligus. Integrasi hanya digunakan ketika memang memperkuat pengalaman bermain dan tujuan utama.

## Final Architecture Decision

Setelah stress test menggunakan berbagai topik usia 2–4 tahun, tidak ditemukan kebutuhan akan pillar keenam.

Physical development, literacy, numeracy, problem solving, executive function, self-regulation, imagination, dan kemampuan lainnya lebih tepat diperlakukan sebagai **cross-domain foundations/capabilities**.

Dengan keputusan ini, Rere memiliki arsitektur yang cukup luas untuk mencakup perkembangan anak secara holistik tanpa berubah menjadi sistem mata pelajaran yang terfragmentasi.
