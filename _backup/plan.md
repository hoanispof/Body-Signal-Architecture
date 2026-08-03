# Body-Signal-Architecture — Master Plan

> **Status:** v0.1 — Initial Plan
> **Date:** 2026-07-28
> **Goal:** Xây dựng kiến trúc "Body-Side Sender" — cơ chế mà qua đó các liệu pháp cơ thể (châm cứu, xoa bóp, bấm huyệt, diện chẩn...) tạo ra hiệu quả chữa bệnh thực sự.
> **Relationship to Human-Predictive-Drive:** Dự án này xây phần "bên gửi" (cơ thể → não). Human-Predictive-Drive đã xây phần "bên nhận" (não xử lý tín hiệu). Hai bộ bổ sung cho nhau nhưng KHÔNG ép khung lẫn nhau.
> **Approach:** Bottom-up. Data thực tế (bài thuốc, phương pháp đã được xác thực lâm sàng) = data đúng. Khung kiến trúc phải phục vụ data, không ngược lại.
> **Quality standard:** Mỗi claim phải có nguồn. 3-tier confidence: 🟢 Research support | 🟡 Synthesis | 🔴 Hypothesis
> **Language:** English (nội dung chính), Vietnamese (giao tiếp/notes)

---

## §0 — THE CENTRAL QUESTION

```
WHAT HAPPENS BETWEEN:
  "Stimulus applied to body surface"
    AND
  "Brain receives signal → therapeutic effect"?

Human-Predictive-Drive answers: HOW the brain PROCESSES the signal once received.
This project answers: HOW the signal TRAVELS from body to brain,
  and WHAT HAPPENS along the way that produces healing.

= Human-Predictive-Drive's Gap 2 ("Driver Layer") approached from the therapy side.

┌─────────────────────────────────────────────────────────────────┐
│                                                                   │
│  [THERAPY INPUT]  →  [??? BODY PATHWAYS ???]  →  [BRAIN/Human-Predictive-Drive]    │
│   needle, pressure     THIS PROJECT builds        Human-Predictive-Drive already    │
│   heat, touch          this middle section         has this      │
│                                                                   │
│  Track A: BODY SYSTEMS   ←──── independent foundation            │
│  Track B: THERAPY DATA   ←──── empirical evidence                │
│  Track C: CROSS-REF      ←──── connecting A and B               │
│  Track D: BRIDGE-Human-Predictive-Drive     ←──── connecting to brain-side          │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
```

---

## §1 — DESIGN PRINCIPLES

1. **Data-first, bottom-up**: Thu thập data thực (bài thuốc, phương pháp, kết quả lâm sàng) TRƯỚC khi tổng hợp pattern. Không bịa khung trước rồi ép data.

2. **Dual-track independence**: Track A (Body Systems) và Track B (Therapy Methods) xây SONG SONG, KHÔNG phụ thuộc nhau. Mỗi track có logic riêng. Cross-reference chỉ xảy ra ở Track C.

3. **Falsifiable claims**: Mỗi mechanism claim phải kèm cách kiểm chứng hoặc bác bỏ. Không chấp nhận "nó hoạt động vì khí/năng lượng" mà không có measurable pathway.

4. **Respectful to tradition**: Dữ liệu lâm sàng hàng nghìn năm (TCM, Ayurveda) = data thực. Không dismiss vì "chưa giải thích được." Nhưng cũng không chấp nhận giải thích truyền thống như mechanism — phải tìm mechanism riêng.

5. **Honest about unknowns**: Khi không biết → ghi rõ "unknown" + "candidates." Không đoán mò rồi ghi như fact.

6. **Human-Predictive-Drive-compatible, not Human-Predictive-Drive-dependent**: Dùng Human-Predictive-Drive concepts khi phù hợp (Zone D, Direct-State, Evaluative Gates). Nhưng dự án này phải đứng độc lập — đọc được mà không cần đọc Human-Predictive-Drive trước.

---

## §2 — 4 TRACKS

### Track A — Body Systems (nền tảng vật lý)

Mục tiêu: Xây bản đồ vật lý của các hệ thống cơ thể liên quan đến liệu pháp.
Tương đương vai trò Core-Hardware.md trong Human-Predictive-Drive, nhưng cho CƠ THỂ thay vì NÃO.
Mỗi system = 1 file riêng. Không cần đọc file nào khác trước.

```
Body-Systems/
  A01-Peripheral-Nervous-System.md   — Dây thần kinh ngoại vi, dermatome, reflex arc
  A02-Autonomic-Nervous-System.md    — Sympathetic/Parasympathetic, vagal tone chi tiết
  A03-Fascia-Connective-Tissue.md    — Mạng mô liên kết, mechanotransduction
  A04-Vascular-Lymphatic.md          — Tuần hoàn máu & bạch huyết, vi tuần hoàn
  A05-Neuroimmune-Interface.md       — Giao diện thần kinh-miễn dịch, cytokine, neurogenic inflammation
  A06-Endocrine-Local.md             — Nội tiết cục bộ (tại chỗ kích thích), hormone paracrine
  A07-Dermatome-Somatotopic-Map.md   — Bản đồ vùng da → dây thần kinh → cơ quan nội tạng
  A08-Muscle-Tendon-Joint.md         — Cơ, gân, khớp — trigger points, proprioception
  A09-Meridian-Examination.md        — Kinh lạc: data thực (electrical conductance, fascial lines) vs lý thuyết
```

### Track B — Therapy Methods (data thực tế)

Mục tiêu: Ghi nhận MỖI phương pháp trị liệu với data thực tế.
Mỗi therapy method = 1 FOLDER riêng. Trong folder:
  - `BXX-main.md` = file chính theo Template B (bắt buộc)
  - `BXX-plan.md` = plan riêng nếu Tier 1 multi-session (tùy chọn)
  - Sub-files bổ sung nếu data quá lớn cho 1 file (tùy chọn)
Data = what works, on what conditions, with what evidence level.

```
Therapy-Methods/
  B01-Acupuncture/                   — Châm cứu (kim châm vào huyệt)
    B01-plan.md                        plan riêng (Tier 1, multi-session)
    B01-main.md                        file chính theo Template B
    (sub-files nếu cần)
  B02-Acupressure/                   — Bấm huyệt (tay ấn vào huyệt)
  B03-Massage-General/               — Xoa bóp tổng quát
  B04-Massage-Deep-Tissue/           — Xoa bóp sâu / myofascial release
  B05-Dien-Chan/                     — Diện chẩn (phản xạ học mặt, Việt Nam)
  B06-Reflexology-Foot/              — Phản xạ học bàn chân
  B07-Cupping/                       — Giác hơi
  B08-Moxibustion/                   — Cứu ngải
  B09-Gua-Sha/                       — Cạo gió
  B10-Chiropractic/                  — Nắn chỉnh cột sống
  B11-Dry-Needling/                  — Châm kim khô (trigger point)
  B12-EFT-Tapping/                   — Emotional Freedom Technique
  B13-Shiatsu/                       — Chỉ áp Nhật Bản
  B14-Craniosacral/                  — Trị liệu sọ-cùng
  B15-Tai-Chi-Qigong/               — Thái cực quyền / Khí công (self-therapy)
  B16-Yoga-Therapy/                  — Yoga trị liệu
  (mở rộng khi cần)
```

### Track C — Cross-Reference (phát hiện pattern)

Mục tiêu: SAU KHI có đủ data từ Track A + B, tìm pattern chéo.
KHÔNG làm sớm. Chỉ bắt đầu khi có ít nhất 4-5 files Track A + 4-5 files Track B đã hoàn thành.

```
Cross-Reference/
  C01-Stimulus-Pathway-Matrix.md     — Loại kích thích nào → kích hoạt pathway nào
  C02-Condition-Response-Map.md      — Bệnh nào → phương pháp nào có evidence
  C03-Common-Mechanisms.md           — Cơ chế chung giữa các phương pháp
  C04-Location-Specificity-Map.md    — WHERE matters? Acupoint/dermatome/trigger point mapping
  C05-Individual-Variation.md        — Tại sao cùng phương pháp, khác người, khác kết quả
```

### Track D — Bridge to Human-Predictive-Drive (kết nối não)

Mục tiêu: Kết nối phát hiện của dự án này với kiến trúc Human-Predictive-Drive.
KHÔNG làm sớm. Chỉ bắt đầu khi Track C có kết quả rõ ràng.

```
Bridge-Human-Predictive-Drive/
  D01-Gap2-Signal-Transduction.md    — Lấp Gap 2 của Human-Predictive-Drive từ góc nhìn therapy
  D02-Zone-D-Expansion.md           — Mở rộng hiểu biết Zone D
  D03-Direct-State-Therapy-Paths.md  — Body-therapy → Direct-State Reward/Dissonance
  D04-Evaluative-Gates-Therapy.md    — Vai trò kỳ vọng/context trong hiệu quả trị liệu
  D05-Interoception-Training.md      — Liệu pháp cơ thể → cải thiện interoception
```

---

## §3 — PHASE PLAN (thứ tự triển khai)

### Phase 0 — Setup (session này)
- [x] Đọc Human-Predictive-Drive files liên quan
- [x] Xác định scope, approach, design principles
- [x] Tạo plan document
- [x] Tạo folder structure
- [x] Tạo templates
- [x] Tạo README.md

### Phase 1 — Body Systems Foundation (Track A)
Ưu tiên theo mức độ liên quan trực tiếp đến liệu pháp:

```
Session order (suggested):
  1.1  A01 — Peripheral Nervous System     ← nền tảng nhất, mọi liệu pháp đều qua đây
  1.2  A07 — Dermatome-Somatotopic Map     ← bản đồ da→thần kinh→cơ quan, trực tiếp giải thích huyệt
  1.3  A02 — Autonomic Nervous System       ← sympathetic/parasympathetic, vagal tone
  1.4  A03 — Fascia-Connective Tissue       ← mạng mô liên kết, nghiên cứu mới nhất
  1.5  A08 — Muscle-Tendon-Joint            ← trigger points, cơ chế massage
  1.6  A05 — Neuroimmune Interface          ← neurogenic inflammation, miễn dịch-thần kinh
  1.7  A04 — Vascular-Lymphatic             ← tuần hoàn, giải thích giác hơi/gua sha
  1.8  A06 — Endocrine-Local                ← hormone tại chỗ
  1.9  A09 — Meridian-Examination           ← kinh lạc: data vs lý thuyết
```

Mỗi session = 1 file, research sâu, chất lượng cao.
A01 nên làm đầu tiên vì là nền tảng cho tất cả các file còn lại.
A07 (Dermatome) nên làm ngay sau vì trực tiếp giải thích cơ sở khoa học của "huyệt."
A09 (Meridian) nên làm CUỐI CÙNG trong Phase 1 vì cần nền tảng từ A01-A08 để đánh giá.

### Phase 2 — Therapy Methods (Track B)
Ưu tiên theo lượng research evidence hiện có:

```
Session order (suggested):
  2.1  B01 — Acupuncture         ← nhiều RCT nhất, data phong phú nhất
  2.2  B03 — Massage-General     ← data rộng, nhiều meta-analyses
  2.3  B02 — Acupressure         ← so sánh trực tiếp với acupuncture (cùng huyệt, khác kích thích)
  2.4  B11 — Dry-Needling        ← so sánh với acupuncture (cùng kim, khác lý thuyết)
  2.5  B07 — Cupping             ← tăng nghiên cứu gần đây
  2.6  B05 — Dien-Chan           ← phản xạ học mặt, ít nghiên cứu nhưng data VN phong phú
  2.7  B06 — Reflexology-Foot    ← phản xạ học chân
  2.8  B04 — Deep-Tissue         ← myofascial release, trigger point therapy
  2.9  B09 — Gua-Sha             ← cạo gió
  2.10 B08 — Moxibustion         ← cứu ngải
  2.11 B10 — Chiropractic        ← nắn chỉnh
  2.12 B15 — Tai-Chi-Qigong      ← self-therapy movement
  2.13 B16 — Yoga-Therapy        ← self-therapy movement
  2.14 B12 — EFT-Tapping         ← ít evidence nhưng interesting mechanism question
  2.15 B13 — Shiatsu             ← variant của acupressure
  2.16 B14 — Craniosacral        ← controversial, ít evidence
```

Phase 1 và Phase 2 CÓ THỂ chạy song song (interleave).
Ví dụ: A01 → B01 → A07 → B03 → A02 → B02...
Điều này cho phép cross-pollination sớm mà không cần Track C formal.

### Phase 3 — Cross-Reference (Track C)

**Prerequisite:** ≥5 Track A + ≥5 Track B files complete.
**Status:** EXCEEDED — 9 Track A + 16 Track B = 25 source files completed.
**Validated by:** 7 Reality Checks across Phase 2 (~15 additions, ~4 corrections, 0 fundamental contradictions). Track A framework VALIDATED by Track B data.

Track C files = SYNTHESIS documents. Different from Track A (reference foundation) and Track B (therapy data). Purpose: discover CROSS-CUTTING PATTERNS not visible in individual files. Each C file pulls data from multiple A+B files to create new analytical products that cannot exist in any single source file.

**Execution order** (dependency-based, NOT numeric):

```
C01 → C03 → C04 → C02 → C05

C01 Stimulus-Pathway-Matrix    ← FOUNDATIONAL, no dependencies
  ↓
C03 Common-Mechanisms          ← builds on C01, identifies shared patterns
  ↓
C04 Location-Specificity-Map   ← uses C01 + C03 scaffolding analysis
  ↓
C02 Condition-Response-Map     ← uses C01+C03+C04 to explain WHY
  ↓
C05 Individual-Variation       ← capstone, synthesizes ALL C01-C04
```

#### C01 — Stimulus-Pathway-Matrix
> "Loại kích thích nào → kích hoạt pathway nào"

**Data sources:** ALL 16 Track B §2 (Stimulation Type) + §6 (Body System Pathways)
**Core output:** Matrix of Stimulus Types × Track A Systems with standardized activation levels

Scope:
- §2 Stimulus Type Taxonomy (~8-10 categories extracted from 16 therapies):
  Penetration, sustained pressure (point/general/deep), negative pressure,
  horizontal shear, thermal, joint thrust, percussion, self-generated movement,
  electrical. Plus parameter dimensions (force, depth, speed, area, temperature, duration).
- §3.1 Main Matrix: Stimulus Type × Track A System (standardized activation levels:
  PRIMARY > STRONG > MODERATE > MINOR > MINIMAL > NONE). Each cell backed by
  specific Track B file(s) as evidence source.
- §3.2 Parameter Modifiers: How changing parameters within a stimulus type shifts the
  activation profile (e.g., light massage → CT afferent dominant; deep massage → endocannabinoid system dominant).
- §3.3 Therapy-to-Stimulus Mapping: Which therapies use which stimulus types (many-to-many).
- §4 Emergent Patterns: system dominance profiles, pressure continuum, force-pathway
  thresholds, active vs passive paradigm shift.
- §5 Predictions: untested stimulus-pathway combinations, expected effects.

Dependencies: None (foundational)
Estimated: 1 session

#### C03 — Common-Mechanisms
> "Cơ chế chung giữa các phương pháp"

**Data sources:** ALL 16 Track B §5 (Mechanisms) + 7 Reality Check findings
**Core output:** Shared vs unique mechanism catalog + cross-therapy synthesis models

Scope:
- §3.1 Mechanism Level Unification: Reconcile B01's 6-level, B10's 5-level,
  B11's 4-level, B07's 5-level, B04's structural-neural dissociation into
  ONE common framework. Not every therapy uses all levels.
- §3.2 Shared Mechanism Catalog: Which mechanisms appear in how many therapies,
  ranked by frequency. (e.g., gate control = ~14/16 therapies, HSP = B08 only)
- §3.3 Unique Mechanisms: Therapy-specific mechanisms that no other therapy shares.
  HSP (B08 only), HO-1 microtrauma pathway (B07+B09 only), PROKR2 molecular
  specificity (B01, uncertain B02/B11), voluntary ANS access (B15/B16 only).
- §3.4 Therapeutic Scaffolding Analysis: The B05/B06/B12/B14 cluster where
  stated mechanism is unsupported/contradicted yet clinical effects partially
  exist via non-specific pathways. Implications for evidence assessment and
  the role of Evaluative Gates across ALL therapies.
- §3.5 Specific-to-Non-Specific Mechanism Spectrum: Full spectrum from
  B01 (most mechanism-specific) to B14 (most non-specific). Where each therapy falls.
- §3.6 Key Cross-Therapy Mechanism Patterns: endocannabinoid system pressure threshold
  (McPartland+Fede), cortisol reappraisal (Moyer), CT afferent engagement
  pattern (clothing/skin type barriers), HO-1 pathway family (B07+B09),
  "different entry point, same building" (B01/B11), needle vs non-needle.
- §5 Predictions: mechanism-based therapy equivalence predictions.

Dependencies: C01 (stimulus→pathway as foundation)
Estimated: 1-2 sessions (most analytically rich C file)

#### C04 — Location-Specificity-Map (RENAMED from Acupoint-System-Map)
> "Does WHERE matter? Acupoint/dermatome/trigger point/zone mapping across therapies"

**Data sources:** A07, A09, ALL Track B §3 (Application Points/Areas)
**Core output:** Location-specificity analysis across all therapies

RENAMED because "Acupoint-System-Map" was too narrow — only relevant to ~6/16
therapies. The actual cross-cutting question is broader: "When does the LOCATION
of stimulus application determine the therapeutic outcome?"

Scope:
- §3.1 Location-Dependent vs Location-Independent: Classification of all 16
  therapies. Some therapies REQUIRE specific location (B01: PROKR2 at specific
  acupoints); others work equally at any location (B04: deep tissue anywhere
  muscles are tight). This distinction has major implications for mechanism.
- §3.2 Validated Location Systems: Acupoints (PROKR2 molecular basis, 93.3% trigger point
  overlap, fascial plane convergence), dermatome-viscerotome convergence (A07,
  Head zones), trigger points (A08, NMJ hypothesis), segmental anatomy.
- §3.3 Unvalidated Location Maps: BQC 257 facial points (B05), Ingham foot zones
  (B06), Hara zones (B13), CSR palpation points (B14). Evidence status for each.
  Connection to therapeutic scaffolding (C03 §3.4).
- §3.4 Location Specificity Evidence Hierarchy: Neural substrate (PROKR2) >
  fascial convergence (80% at planes) > vascular (VNB weakened by Maurer 2019) >
  bioelectrical (Ahn 2008 inconclusive). What MAKES a "point" special.
- §3.5 Body Region Pathway Comparison: Face (trigeminal CN V → brainstem),
  ear (ABVN → vagal), foot (L4-S3 spinal), back (T1-L5 segmental), limbs
  (mixed nerve). Different regions = different pathway access = different
  therapeutic potential from same stimulus.
- §5 Predictions: which "location-specific" claims will survive future testing.

Dependencies: C01 (stimulus context), C03 (scaffolding analysis)
Estimated: 1 session

#### C02 — Condition-Response-Map
> "Bệnh nào → phương pháp nào có evidence"

**Data sources:** ALL 16 Track B §4 (Clinical Effects) + §9 (Evidence Assessment)
**Core output:** Condition × Therapy matrix with evidence levels + mechanism explanation

Scope:
- §3.1 Condition Taxonomy (by clinical domain): Pain (acute/chronic, MSK/visceral/
  headache), psychological (anxiety/depression/PTSD), autonomic (nausea/hypertension),
  musculoskeletal (LBP/neck/OA/fibromyalgia), neurological (balance/Parkinson's),
  metabolic (T2DM), obstetric (breech), immune/inflammatory.
- §3.2 Main Matrix: Condition × Therapy with evidence level per cell:
  🟢 Strong (systematic review/meta-analysis + guideline endorsed), 🟡 Moderate (RCTs, mixed),
  🔴 Weak/preliminary (case reports, uncontrolled). Effect size where available.
- §3.3 Head-to-Head Comparison Data: Where direct therapy comparisons exist
  (e.g., B16 yoga ≈ exercise for LBP, B15 Tai Chi > resistance training for
  Parkinson's balance, B01 acupuncture > sham for chronic pain).
- §3.4 Mechanism-Based Explanation: WHY certain therapies work for certain
  conditions — connecting clinical outcomes (C02) to mechanisms (C01+C03+C04).
  "Therapy X works for condition Y BECAUSE stimulus type Z activates pathway W
  which addresses pathophysiology of Y."
- §3.5 Evidence Tier Classification: Tier 1-5 evidence quality across therapies
  (emerged organically from Track B). What distinguishes high vs low quality.
  Structural biases: funding, publication, sham control challenges, COI.
- §5 Predictions: underexplored condition-therapy pairs worth investigating.

Dependencies: C01, C03, C04
Estimated: 1 session

#### C05 — Individual-Variation
> "Tại sao cùng phương pháp, khác người, khác kết quả"

**Data sources:** ALL 16 Track B §8 (Individual Variation) + B01 §8 (Responder Prediction)
**Core output:** Comprehensive variation framework explaining inter-individual differences

Scope:
- §3.1 Genetic Factors: COMT (condition-specific, NOT universal predictor),
  GABRB3 (new, OR 3.85), OPRM1 (negative direct evidence for acupuncture),
  responder prediction models (Yang 2020 83%, Gao 2025 85%, Yin 2023 88%).
  Cross-therapy applicability assessment.
- §3.2 Dose-Response Synthesis: What we know about dose-response across therapies.
  Vickers dose-response for acupuncture (clear vs none, flat vs sham). Pressure-
  dependent pathway activation (C01 §3.2). Session frequency/duration patterns.
- §3.3 Expectation & Conditioning (Evaluative Gates): How beliefs, context,
  therapeutic relationship, practitioner confidence modify outcomes across
  therapies. Therapeutic scaffolding (C03 §3.4) as variation source.
- §3.4 Anatomical/Physiological Variation: Fascial architecture (sex hormones,
  A03), nerve distribution density, dermatome overlap zones, CT afferent density
  (hairy vs glabrous skin), PROKR2 expression variation.
- §3.5 Demographic Factors: Sex/hormonal (fascial collagen ratio, pain sensitivity),
  age (pediatric vs elderly neuroplasticity), chronicity (acute → different mechanism
  engagement than chronic, central sensitization).
- §3.6 Responder Phenotype Synthesis: Can we predict who responds to which therapy?
  Multi-factor model combining genetics + anatomy + psychology + chronicity.
- §5 Predictions: testable responder prediction hypotheses.

Dependencies: ALL C01-C04 (capstone)
Estimated: 1 session

### Phase 4 — Bridge to Human-Predictive-Drive (Track D)

Track D = BRIDGE documents. Khác Track C (synthesis WITHIN Body-Signal-Architecture), Track D kết nối
Body-Signal-Architecture (body-side sender) với Human-Predictive-Drive (brain-side receiver). Mỗi file bridge ONE Human-Predictive-Drive
concept to Body-Signal-Architecture evidence — bidirectional analysis showing what each side adds.

**Prerequisite:** Track C COMPLETE ✅ (5/5 files)

**Execution order:** D01 → D02 → D03 → D04 → D05 (dependency-based)

#### D01 — Gap2-Signal-Transduction
> "Body-Signal-Architecture lấp được bao nhiêu trong Gap 2 — khoảng trống LỚN NHẤT của Human-Predictive-Drive?"

**Human-Predictive-Drive side:** Gap 2 = Driver Layer (Blackbox-Map.md §3). Molecular biology between
physical body (Layer 1) and chunk processing (Layer 3). 6 sub-gaps:
  SG-2.1 receptor → neural signal conversion
  SG-2.2 signal → thalamus routing decisions
  SG-2.3 cortical → pattern formation (chunk creation)
  SG-2.4 neurotransmitter → behavioral function mapping
  SG-2.5 synaptic plasticity → compile mechanism
  SG-2.6 sleep consolidation → memory integration

**Body-Signal-Architecture side:** C01 (10 stimulus types × 9 systems), C03 (51 mechanisms, dual-axis
framework), C04 (somatotopic routing, body region hierarchy). All three files
explicitly state "this IS Gap 2 content" in §8.4.

**Core output:** Sub-gap by sub-gap mapping — which Body-Signal-Architecture data addresses which sub-gap,
to what depth, and what remains open.

**Key questions:**
- Does Body-Signal-Architecture FULLY close any of the 6 sub-gaps?
- Which sub-gaps does Body-Signal-Architecture not even touch? (SG-2.5 compile, SG-2.6 sleep?)
- Where does Body-Signal-Architecture data EXCEED what Human-Predictive-Drive expected in Gap 2?

Dependencies: None within Track D (foundational)
Estimated: 1 session

#### D02 — Zone-D-Expansion
> "Zone D — nơi body therapies hoạt động, PFC không với tới"

**Human-Predictive-Drive side:** Zone D = peripheral neural systems (Neural-Architecture.md §5). PFC
reach ≈ 0. ENS ~100-500M neurons, spinal cord, ANS, cardiac. Minimum 2 synaptic
relays from PFC. Breathing = ONLY voluntary access.

**Body-Signal-Architecture side:** All 5 C files reference Zone D. Body therapies work directly on Zone D
hardware, bypassing PFC bottleneck. Somatovisceral reflexes = pure Zone D.

**Core output:** Expanded Zone D architecture with Body-Signal-Architecture mechanism data. Zone D
sub-regions mapped to specific therapy mechanisms.

**Key questions:**
- "PFC reach ≈ 0" — chính xác sau Body-Signal-Architecture data? Có voluntary bridge nào NGOÀI breathing?
- Adherence Paradox: Zone D = PFC reach 0, but sustained practice (B15/B16) requires
  PFC → how is this resolved?
- Active vs Passive therapies: different Zone D engagement patterns?

Dependencies: D01 (signal transduction framework)
Estimated: 1 session

#### D03 — Direct-State-Therapy-Paths
> "Body therapy signals = Direct-State hay Evaluative? Hardware hay software?"

**Human-Predictive-Drive side:** Direct-State = hardware reward pathways (Reward-Signal-Architecture.md).
CT afferents, endocannabinoid system CB1, thermoreceptors. NOT opioid-dependent. NOT blocked by
naltrexone. Burnout-proof. Present from birth. Vs Evaluative = hedonic hotspot,
mu-opioid, requires 5 Body-Feedback-Preconditions.

**Body-Signal-Architecture side:** C01 stimulus→pathway mapping, C03 depth cascade (Direct-State →
modulation transition), C04 location-dependent pathway access (hairy skin only for CT),
C05 anatomical variation in Direct-State hardware (CT density, fascial CB1/CB2).

**Core output:** Classification of ALL Body-Signal-Architecture therapy mechanisms into Human-Predictive-Drive's Direct-State
vs Evaluative framework. Depth cascade → E₀-E₃ mapping.

**Key questions:**
- Does EVERY body therapy produce Direct-State reward, or do some operate purely
  through Evaluative?
- Depth cascade maps to E₀→E₃ complexity gradient how?
- CT afferent hairy-skin limitation — what about therapy at palms/soles?
- Is "burnout-proof" confirmed by Body-Signal-Architecture chronic-use data?

Dependencies: D01 (signal framework), D02 (architectural context)
Estimated: 1 session

#### D04 — Evaluative-Gates-Therapy
> "Therapeutic scaffolding = Evaluative Gates — cùng một thứ, khác tên?"

**Human-Predictive-Drive side:** Evaluative Gates Direct-State (Dissonance-Signal-Architecture.md).
4 outcomes: amplify (trusted therapist), suppress (threat context), raw (dissociation),
ambiguous (conflicted). Placebo (Zubieta 2005 endogenous opioid) / Nocebo (Colloca 2005
CCK) = empirical proof. Posterior-to-anterior insula gradient.

**Body-Signal-Architecture side:** C03 therapeutic scaffolding spectrum (B14 pure → B01 most specific).
C04 scaffolding-specificity inverse. C02 non-specific floor SMD 0.2-0.4.
C05 expectation gradient (~80-95% B14 → ~15-30% B01). Prediction error mechanism.

**Core output:** Unified model — Body-Signal-Architecture's scaffolding/non-specific-floor = Human-Predictive-Drive's Evaluative
Gates framework. Per-therapy gate-setting prediction.

**Key questions:**
- Non-specific floor SMD 0.2-0.4 = Direct-State floor UNMODULATED by Evaluative Gates?
- Scaffolding-specificity inverse: WHY does invalidity enhance therapeutic context?
- Can we predict the Evaluative Gate setting for each therapy type?
- Prediction error as gate-ACTIVATION mechanism — how?
- Asymmetric transition: reward→dissonance FAST (ms), dissonance→reward SLOW (min-hours)
  — implications for body therapy session design?

Dependencies: D03 (Direct-State framework — need to understand WHAT is being gated)
Estimated: 1 session

#### D05 — Interoception-Training
> "Body therapy trains the ability to READ body signals — the meta-skill"

**Human-Predictive-Drive side:** Interoception = L1 category 17 = META KEYSTONE (Body-Base.md). Self-
Observation 7-level gradient (Self-Observation.md, 0=none → 6=somatic articulation).
Body-Knowing Inward (Body-Knowing.md). Somatic-Articulation Loop = Gendlin Focusing
(SAL.md). If impaired → cascade failure across 5+ systems (~10% alexithymia).

**Body-Signal-Architecture side:** LEAST explicitly referenced in Track C. Interoception is IMPLICIT — 
embedded within other concepts (C05 responder variation, C02 psychological conditions,
C03 active therapy emergence, C04 body region hierarchy). Needs SYNTHESIS approach.

**Core output:** How body therapies systematically train interoceptive capacity. Active
vs passive therapy continuum as interoception development path.

**Key questions:**
- Does body therapy improve interoceptive ACCURACY or only CONFIDENCE?
- Active therapies (B15/B16) as interoception training — what's the mechanism?
- Passive → active continuum = interoception development gradient?
- Clinical implications: alexithymia, dissociation, chronic pain
- Self-treatment vs practitioner-administered: interoception difference?

Dependencies: ALL D01-D04 (capstone)
Estimated: 1 session

### Phase 5 — Core Synthesis

Tạo Core files tổng hợp (tương đương Core-Hardware + Core-Software trong Human-Predictive-Drive).
Đây là sản phẩm cuối cùng — kiến trúc Body-Side thống nhất.

**2 Core files:**

| Order | File | Role | Analogous Human-Predictive-Drive | Dependencies | Estimated |
|-------|------|------|---------------|-------------|-----------|
| 1st | Core-Body-Architecture.md | "WHAT IS WHERE" — Unified map of body's signaling infrastructure. 9 Track A systems as ONE integrated network, organized by depth × region × timing × stimulus. | Core-Hardware.md (331 lines) | All Track A, C01, C04, D02 | 1 session |
| 2nd | Core-Therapy-Architecture.md | "HOW IT WORKS" — Unified mechanism framework answering the Central Question (§0). Complete therapeutic process from stimulus to effect, integrating all Tracks. | Core-Software.md (1,803 lines) | ALL 35 files (A+B+C+D), Core-Body | 2-3 sessions |

**Core-Body-Architecture.md section structure:**
```
§0 — ORIENTATION (what this is, relationship to Human-Predictive-Drive Core-Hardware)
§1 — THE BODY'S SIGNALING NETWORK (map: 9 systems as interconnected architecture)
§2 — FOUR ARCHITECTURAL DIMENSIONS
  §2.1 Depth (Zone D Processing Hierarchy: Level 0 Local → Level 4 Compilation)
  §2.2 Region (Body Region Pathway Hierarchy: face > ear > back > foot)
  §2.3 Timing (Speed Gradient: axon reflex ms → immune hr → endocrine days)
  §2.4 Stimulus (10 types × 9 systems: C01 matrix, dominance fingerprints)
§3 — SYSTEM INTERACTION MAP (how 9 systems interconnect — NOT 9 silos)
§4 — SYSTEM PROFILES (compact: 1 role-in-network paragraph each)
§5 — HARDWARE VARIATION (from C05: CT density, fascial architecture, nerve distribution)
§6 — HONEST ASSESSMENT
§7 — CROSS-REFERENCES
```

**Core-Therapy-Architecture.md section structure:**
```
§0 — ORIENTATION (what this is, relationship to Human-Predictive-Drive Core-Software)
§1 — THE CENTRAL QUESTION ANSWERED (stimulus → body pathways → therapeutic effect)
§2 — DUAL-AXIS MECHANISM FRAMEWORK (spatial scale × mechanism domain, from C03)
§3 — THE THERAPEUTIC PROCESS FLOW
  §3.1 Stimulus Reception (C01 stimulus types + parameter modifiers)
  §3.2 Signal Transduction (D01 Gap 2 coverage, parallel streams)
  §3.3 Processing Architecture (D02 Zone D levels, D03 Direct-State/Evaluative)
  §3.4 Evaluative Modulation (D04 gate leverage, scaffolding paradox)
  §3.5 Interoception Integration (D05 training gradient, therapy multiplier)
§4 — UNIFIED THERAPY ARCHITECTURE
  §4.1 16-Therapy Classification (Direct-State/Evaluative ratio, reward depth)
  §4.2 Mechanism Catalog (universal/common/narrow/unique from C03)
  §4.3 Condition-Therapy Matching (from C02 evidence hierarchy)
  §4.4 Individual Variation (from C05 6-domain taxonomy)
§5 — EMERGENT ARCHITECTURE (Dual Economy, non-specific floor, key principles)
§6 — HONEST ASSESSMENT (what Body-Signal-Architecture explains, doesn't, open questions)
§7 — PREDICTIONS (consolidated from all tracks)
§8 — CROSS-REFERENCES
```

**Execution:** Core-Body first (simpler, reference-style). Core-Therapy second (denser, synthesis-heavy). Both go at project root level: `Body-Signal-Architecture/Core-Body-Architecture.md` and `Body-Signal-Architecture/Core-Therapy-Architecture.md`.

---

## §4 — TEMPLATES

### Template A — Body System File

```markdown
---
title: [System Name]
id: A[XX]
version: 0.1
status: DRAFT
scope: Physical architecture + pathways of [system]
dependencies: [] (hoặc list files cần đọc trước)
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# [System Name]

## §1 — PHYSICAL ARCHITECTURE
  What is it, where is it, what connects to what.
  Verifiable via imaging/dissection.

## §2 — FUNCTION
  What does it do in normal physiology.

## §3 — PATHWAYS
  How signals travel through this system.
  Receptor → relay → destination mapping.

## §4 — RELEVANCE TO BODY-BASED THERAPY
  Why this system matters for understanding how therapies work.
  Which therapies interact with this system and how.

## §5 — KEY RESEARCH
  Citations organized by sub-topic.

## §6 — Human-Predictive-Drive CONNECTION POINTS
  Mapping to Human-Predictive-Drive concepts: Zone A/B/C/D, Direct-State, timing hierarchy.
  Brief — detail in Track D.

## §7 — INDIVIDUAL VARIATION
  How this system varies between individuals.

## §8 — OPEN QUESTIONS
  What is NOT yet understood. Candidates, not conclusions.

## §9 — CROSS-REFERENCES
  Links to other files in this project + Human-Predictive-Drive files.
```

### Template B — Therapy Method File

```markdown
---
title: [Therapy Name]
id: B[XX]
version: 0.1
status: DRAFT
scope: [Therapy] — stimulation type, application, evidence, mechanisms
origin: [Country/tradition of origin]
dependencies: [] (Track A files that provide context)
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# [Therapy Name]

## §1 — DEFINITION & ORIGIN
  What it is, where it comes from, historical context.
  Traditional explanation (recorded as DATA, not endorsed as mechanism).

## §2 — STIMULATION TYPE
  What PHYSICAL stimulus is applied:
  - Modality: mechanical / thermal / invasive / pressure-differential / movement
  - Intensity: quantifiable if possible (force in N, temperature in °C, depth in mm)
  - Duration: typical session parameters
  - Frequency: typical treatment frequency

## §3 — APPLICATION POINTS & AREAS
  Where on the body the therapy is applied.
  Specific points (huyệt) or general areas.
  Maps/diagrams if available.

## §4 — DOCUMENTED CLINICAL EFFECTS
  What conditions has this therapy been shown to treat?
  For each condition:
  - Effect observed
  - Evidence level: 🟢 RCT/Meta-analysis | 🟡 Clinical trial | 🔴 Case report/Traditional
  - Key citations
  Organized by evidence strength, strongest first.

## §5 — PROPOSED MECHANISMS
  §5.1 — Traditional explanation (TCM, Ayurveda, etc.) — recorded as historical data
  §5.2 — Modern research-based mechanisms — what science currently proposes
  §5.3 — Framework hypothesis — our synthesis (if any, marked 🔴)

## §6 — BODY SYSTEM PATHWAYS ACTIVATED
  Which Track A systems does this therapy interact with?
  For each: what happens at the physiological level.
  Link to specific Track A files.

## §7 — COMPARISON WITH RELATED METHODS
  How does this therapy differ from similar ones?
  Same stimulus, different points? Same points, different stimulus?

## §8 — INDIVIDUAL VARIATION & CONTRAINDICATIONS
  Who responds well, who doesn't. Known contraindications.

## §9 — EVIDENCE ASSESSMENT
  Overall quality of evidence. Gaps in research.
  Potential biases (funding, cultural, publication).

## §10 — OPEN QUESTIONS
  What remains unexplained by current mechanisms.

## §11 — CROSS-REFERENCES
  Track A files, Track C patterns, Human-Predictive-Drive connections.
```

### Template C — Cross-Reference File

Track C files are SYNTHESIS documents — different structure from A/B.
Focus on CROSS-CUTTING analysis, not individual system/therapy data.

```markdown
---
title: [Cross-Reference Title]
id: C[XX]
version: 0.1
status: DRAFT
scope: [What this file synthesizes]
sources: [List of Track A and Track B files referenced]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# [Cross-Reference Title]

## §1 — PURPOSE & METHODOLOGY
  Why this cross-reference exists.
  How data was extracted and synthesized from Track A + B files.
  Standardization decisions (e.g., how activation levels were normalized).

## §2 — TAXONOMY / CLASSIFICATION
  The categories/dimensions being cross-referenced.
  Definitions and criteria for each category.
  Why these categories, not others.

## §3 — MAIN ANALYSIS
  The core cross-reference content: matrices, tables, mappings.
  Multiple subsections (§3.1, §3.2, §3.3...) as needed.
  Each cell/entry backed by specific Track A/B file + section reference.
  (This is the largest section — the analytical product.)

## §4 — EMERGENT PATTERNS
  Patterns discovered FROM the cross-reference that are NOT visible
  in individual Track A or Track B files.
  Each pattern:
  - Description
  - Evidence sources (Track A/B file + section)
  - Confidence level (🟢/🟡/🔴)
  - Why this pattern matters
  THIS is where Track C adds value beyond Track A+B.

## §5 — PREDICTIONS & TESTABLE HYPOTHESES
  What the cross-reference PREDICTS about:
  - Untested combinations or scenarios
  - Expected outcomes of future studies
  - Research priorities based on pattern analysis
  Each prediction: statement + what would confirm + what would refute.
  (FALSIFIABLE required.)

## §6 — LIMITATIONS & GAPS
  What the cross-reference CANNOT answer with current data.
  Missing data points. Methodological limitations.
  Confidence caveats for the entire analysis.

## §7 — OPEN QUESTIONS
  Questions RAISED BY the cross-reference analysis.
  Different from individual A/B file open questions — these are CROSS-CUTTING.
  Questions that only become visible when comparing across files.

## §8 — CROSS-REFERENCES
  §8.1 Track A files referenced (with specific sections)
  §8.2 Track B files referenced (with specific sections)
  §8.3 Track C dependencies and connections
  §8.4 Human-Predictive-Drive connection points
  §8.5 Citations for NEW sources (not already in Track A/B files)
```

### Template D — Bridge to Human-Predictive-Drive File

Track D files are BRIDGE documents — different structure from Track C (internal
synthesis). Track D connects Body-Signal-Architecture (body-side sender) to Human-Predictive-Drive (brain-side receiver).
Each file bridges ONE Human-Predictive-Drive concept to Body-Signal-Architecture evidence, showing bidirectional value.

```markdown
---
title: [Bridge Topic]
id: D[XX]
version: 0.1
status: DRAFT
scope: Bridge [Body-Signal-Architecture concept] to [Human-Predictive-Drive concept]
hpd_sources: [List of Human-Predictive-Drive files referenced]
bsa_sources: [List of Body-Signal-Architecture Track A/B/C files referenced]
dependencies: [D files that must be read first]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# [Bridge Topic]

## §1 — SCOPE & BRIDGE DEFINITION
  What Human-Predictive-Drive concept is being bridged.
  What Body-Signal-Architecture data connects to it.
  What this bridge aims to accomplish.
  What it does NOT cover (deferred to other D files).

## §2 — Human-Predictive-Drive CONCEPT
  What Human-Predictive-Drive says about this concept (citations to Human-Predictive-Drive files).
  Human-Predictive-Drive's assumptions and acknowledged gaps.
  Context within Human-Predictive-Drive's overall architecture.

## §3 — Body-Signal-Architecture EVIDENCE
  What Body-Signal-Architecture Tracks A-C have established.
  Summary organized by relevant findings.
  Track A/B/C file + section citations.

## §4 — BRIDGE ANALYSIS
  §4.1 Convergence: where Human-Predictive-Drive concept and Body-Signal-Architecture data align
  §4.2 Body-Signal-Architecture Fills Human-Predictive-Drive Gaps: Body-Signal-Architecture data addresses what Human-Predictive-Drive acknowledged as missing
  §4.3 Body-Signal-Architecture Challenges Human-Predictive-Drive: Body-Signal-Architecture data suggests Human-Predictive-Drive assumptions need refinement
  §4.4 Human-Predictive-Drive Frames Body-Signal-Architecture: Human-Predictive-Drive framework reveals patterns in Body-Signal-Architecture data
  §4.5 Remaining Gaps: what NEITHER side resolves
  (This is the largest section — the analytical product.)

## §5 — EMERGENT INSIGHTS
  Insights visible ONLY through the bridge.
  Neither Human-Predictive-Drive alone nor Body-Signal-Architecture alone could produce these.
  Each insight:
  - Description
  - Why it requires BOTH sides
  - Confidence level (🟢/🟡/🔴)

## §6 — PREDICTIONS & TESTABLE HYPOTHESES
  Arising from the bridge CONNECTION, not from either side alone.
  Each prediction: statement + confirm + refute.
  FALSIFIABLE required.

## §7 — LIMITATIONS & GAPS
  What the bridge CANNOT resolve with current data.
  Missing Human-Predictive-Drive detail. Missing Body-Signal-Architecture data. Methodological limits.

## §8 — OPEN QUESTIONS
  Questions RAISED BY the bridge analysis.
  Different from Track C open questions — these are INTER-PROJECT.
  Questions that only become visible when connecting Human-Predictive-Drive to Body-Signal-Architecture.

## §9 — CROSS-REFERENCES
  §9.1 Human-Predictive-Drive files referenced (with specific sections)
  §9.2 Body-Signal-Architecture Track A files referenced
  §9.3 Body-Signal-Architecture Track B files referenced
  §9.4 Body-Signal-Architecture Track C files referenced
  §9.5 Track D connections
  §9.6 Citations for NEW sources (not already in Human-Predictive-Drive or Body-Signal-Architecture files)
```

---

## §5 — HUMAN-PREDICTIVE-DRIVE CONNECTION POINTS (quick reference)

Các concepts Human-Predictive-Drive có sẵn mà dự án này sẽ tham chiếu:

```
Human-Predictive-Drive Concept                    → Relevance to This Project
─────────────────────────────────────────────────────────────
Zone D (PFC reach ≈ 0)        → Body therapies work IN Zone D — explains
                                  why cognitive approaches alone are insufficient
Direct-State Reward            → Touch, warmth, exercise = Direct-State pathways.
                                  Body therapies = Direct-State activation
Direct-State Dissonance        → Pain = Direct-State. Therapies modulate this
Evaluative Gates Direct-State  → Placebo/nocebo, practitioner trust, ritual context
                                  = Evaluative modulation of therapy effectiveness
Chronic Pain = Compound        → Original injury (Direct-State) + fear/identity layers
                                  (Evaluative). Body therapies address BOTH
Interoception (Keystone #17)   → Body therapies improve interoception over time
                                  = Indirect benefit beyond the specific condition
CT Afferents                   → Touch-specific reward pathway, optimal 1-10cm/s
                                  = Direct mechanism for massage effectiveness
Somatic-Articulation Loop      → Body-knowledge → explicit-knowledge mechanism
                                  = HOW body therapy insights become conscious
Cortisol = Amplifier           → Therapies shift cortisol mode, not just "reduce stress"
Breathing = Zone D Bridge      → The ONE voluntary pathway to ANS. Yoga, Tai Chi use this
Gap 2 (Driver Layer)           → This entire project is building Gap 2 from therapy side
Blackbox-Map candidates        → Immune system, microbiome = acknowledged Human-Predictive-Drive gaps
                                  this project may partially fill
```

---

## §6 — QUALITY RULES

1. **Mỗi session = 1 file, hoàn chỉnh.** Không để file dở dang. Nếu quá rộng, chia nhỏ thành 2 files.

2. **Research-first.** AI search + web search cho từng claim. Không viết từ "kiến thức chung" — tìm nguồn cụ thể.

3. **3-tier confidence bắt buộc** cho mỗi section:
   - 🟢 Research: published, peer-reviewed, replicated
   - 🟡 Synthesis: logical inference from multiple 🟢 sources, or expert consensus without formal study
   - 🔴 Hypothesis: our own reasoning, untested

4. **Template compliance.** Mỗi file phải theo đúng template. Nếu cần thêm section → thêm, nhưng không bỏ section nào.

5. **No premature synthesis.** Track A và Track B files ghi nhận data. KHÔNG tổng hợp pattern trong individual files. Pattern detection = Track C.

6. **Honest unknowns.** §Open Questions phải có nội dung thực. "Everything is well understood" = almost always wrong.

7. **Cross-reference explicitly.** Khi một file tham chiếu concept từ file khác → ghi rõ file name + section.

---

## §7 — ESTIMATED SCALE

```
Track A (Body Systems):     ~9 files × ~2-4 sessions/file  = ~20-35 sessions
Track B (Therapy Methods):  ~16 files × ~1-2 sessions/file = ~16-32 sessions
Track C (Cross-Reference):  ~5 files × ~2-3 sessions/file  = ~10-15 sessions
Track D (Bridge Human-Predictive-Drive):       ~5 files × ~1-2 sessions/file  = ~5-10 sessions
Phase 5 (Core Synthesis):   ~2-3 files × ~3-5 sessions     = ~6-15 sessions

TOTAL ESTIMATE: ~60-110 sessions for v1.0
(Not including iterations, corrections, and expansion)
```

---

## §8 — SESSION WORKFLOW

### §8.1 — Track A Workflow (Phase 1 — COMPLETED)

Mỗi session, bạn mở plan.md đầu tiên để biết đang ở đâu.
Workflow cho mỗi session:

```
1. OPEN plan.md → xác định file đang làm
2. OPEN template → copy structure
3. RESEARCH → AI search + web search cho từng section
4. WRITE → viết file theo template, ghi confidence mỗi section
5. REVIEW → đọc lại, check template compliance + confidence markers
6. UPDATE plan.md → đánh dấu file đã hoàn thành, ghi notes nếu có
7. COMPACT → sẵn sàng cho session tiếp theo
```

### §8.2 — Track B Workflow (Phase 2 — ADAPTIVE DEPTH)

Track B khác Track A: đây là DATA THỰC TẾ tích lũy hàng nghìn năm, phân mảnh,
nhiều tradition, varying evidence quality. KHÔNG thể biết trước scope cho đến khi
research sơ lược. → Dùng ADAPTIVE DEPTH workflow:

```
PHASE 2 WORKFLOW — FOR EACH THERAPY METHOD:

  SESSION 1 (ASSESSMENT):
    1. OPEN plan.md → xác định therapy method tiếp theo
    2. READ relevant Track A files cho context
    3. PRELIMINARY RESEARCH → web search + AI search
       để đánh giá TỔNG QUAN evidence landscape:
       - Bao nhiêu RCTs / meta-analyses?
       - Bao nhiêu traditions / variants?
       - Bao nhiêu conditions documented?
       - Mức độ phức tạp mechanism?
    4. SCOPE ASSESSMENT:
       ┌─────────────────────────────────────────────────────┐
       │  SCOPE SMALL → 1 session đủ → viết luôn trong      │
       │    session này (standard workflow)                    │
       │                                                      │
       │  SCOPE LARGE → cần multi-session:                    │
       │    → Tạo PLAN RIÊNG cho therapy method này           │
       │    → Chia thành phases rõ ràng                       │
       │    → COMPACT → mỗi session sau = 1 phase             │
       │    → Session cuối = TỔNG HỢP viết file               │
       └─────────────────────────────────────────────────────┘
    5. COMPACT → sẵn sàng cho session tiếp theo

  KEY PRINCIPLES:
    ✦ DATA OVERRIDES FRAMEWORK: nếu therapy data mâu thuẫn với
      Track A → UPDATE Track A. Framework phục vụ data, không ngược lại.
    ✦ REALITY CHECK: sau mỗi 3-4 files Track B → kiểm tra Track A
      consistency. Ghi notes về changes cần thiết.
    ✦ QUALITY > SPEED: chậm mà chắc. Thông tin phải chính xác
      vì đây là NỀN TẢNG cho toàn bộ hệ thống.
    ✦ EACH SESSION STARTS CLEAN: compact giữa mỗi therapy method
      để context sạch = chất lượng cao nhất.

  EXPECTED DEPTH BY THERAPY:
    (preliminary estimate — sẽ điều chỉnh sau assessment)
    TIER 1 — Multi-session (plan riêng):
      B01 Acupuncture       ~2-3 sessions (largest evidence base)
      B03 Massage-General    ~1-2 sessions (very broad)
    TIER 2 — Careful 1 session:
      B02, B04, B07, B10, B11, B15, B16
    TIER 3 — Standard 1 session:
      B05, B06, B08, B09, B12, B13, B14
    (These are ESTIMATES — actual depth decided per assessment)
```

### §8.3 — Track C Workflow (Phase 3 — SYNTHESIS)

Track C = SYNTHESIS documents. Different workflow from Track A (research-first)
and Track B (data-first). Track C pulls from EXISTING source files (25 completed
A+B files), identifies cross-cutting patterns, and creates new analytical products.

```
PHASE 3 WORKFLOW — FOR EACH CROSS-REFERENCE FILE:

  1. OPEN plan.md → xác định C file tiếp theo
     (follow dependency order: C01 → C03 → C04 → C02 → C05)
  2. IDENTIFY source sections in Track A+B files relevant to this C file
  3. READ relevant sections systematically (§2/§4/§5/§6/§8 depending on C file)
  4. EXTRACT data points into structured categories
  5. BUILD matrix/table (draft version with standardized levels)
  6. IDENTIFY emergent patterns (what's NOT visible in individual files)
  7. VERIFY patterns against source files (cross-check against ≥2 sources)
  8. WRITE C file following Template C
  9. UPDATE plan.md → mark complete, record key findings
  10. COMPACT → next file

  KEY PRINCIPLES:
  ✦ SYNTHESIS ≠ REPETITION: C files must add VALUE beyond what individual
    A/B files already say. If a finding exists in one Track B file and
    applies only to that therapy, it belongs there, not in Track C.
    Track C captures patterns that span MULTIPLE therapies or systems.
  ✦ PATTERNS MUST BE VERIFIABLE: each pattern cites specific A/B files
    + section numbers as evidence sources. No unsourced claims.
  ✦ PREDICTIONS MUST BE FALSIFIABLE: each prediction states what would
    confirm or refute it. 🔴 tag required for all predictions.
  ✦ CROSS-CUTTING ONLY: Track C captures patterns that require data
    from ≥2 Track B files to identify. Single-therapy findings stay in
    their Track B file.
  ✦ 3-tier confidence applies to PATTERNS, not just individual facts:
    🟢 Pattern supported by ≥3 independent Track B sources
    🟡 Pattern synthesized from 2 sources or indirect evidence
    🔴 Pattern hypothesized from 1 source or logical inference
  ✦ EACH SESSION STARTS CLEAN (same as Phase 2)
  ✦ NO FORMAL REALITY CHECK: Track C has built-in quality via
    dependency chain — each file builds on verified previous files.
    Final C05 serves as implicit completeness check.
  ✦ STANDARDIZED LEVELS for matrices:
    PRIMARY > STRONG > MODERATE > MINOR > MINIMAL > NONE
    Applied consistently across all Track B data.
```

### §8.4 — Track D Workflow (Phase 4 — BRIDGE)

Track D = BRIDGE documents connecting Body-Signal-Architecture (body-side sender) to Human-Predictive-Drive (brain-side
receiver). Different from Track C (internal synthesis) — Track D requires reading
BOTH Body-Signal-Architecture and Human-Predictive-Drive source files, then analyzing the CONNECTION between them.

```
PHASE 4 WORKFLOW — FOR EACH BRIDGE FILE:

  1. OPEN plan.md → xác định D file tiếp theo
     (follow dependency order: D01 → D02 → D03 → D04 → D05)
  2. READ Human-Predictive-Drive source files for the Human-Predictive-Drive-side concept
     (each D file specifies which Human-Predictive-Drive files to read)
  3. READ relevant Body-Signal-Architecture Track C sections (+ Track A/B sections as needed)
  4. MAP Human-Predictive-Drive concept → Body-Signal-Architecture evidence:
     → Where do they CONVERGE? (same finding, different framing)
     → Where does Body-Signal-Architecture FILL Human-Predictive-Drive gaps? (Body-Signal-Architecture data → Human-Predictive-Drive acknowledged unknowns)
     → Where does Body-Signal-Architecture CHALLENGE Human-Predictive-Drive? (Body-Signal-Architecture data → Human-Predictive-Drive assumption revision)
     → Where does Human-Predictive-Drive FRAME Body-Signal-Architecture? (Human-Predictive-Drive framework → Body-Signal-Architecture data interpretation)
     → Where do GAPS REMAIN? (neither side resolves)
  5. IDENTIFY emergent insights that require BOTH sides
  6. WRITE D file following Template D
  7. UPDATE plan.md → mark complete, record key findings
  8. COMPACT → next file

  KEY PRINCIPLES:
  ✦ BRIDGE ≠ SUMMARY: D files must show what becomes visible ONLY when
    connecting Human-Predictive-Drive concepts to Body-Signal-Architecture data. If an insight exists in Track C
    alone, it belongs there, not in Track D.
  ✦ Human-Predictive-Drive CONCEPTS ARE FRAMEWORK: Body-Signal-Architecture data may refine, challenge, or extend
    Human-Predictive-Drive's framework, but Human-Predictive-Drive's conceptual architecture is the TARGET for
    bridging — not the other way around.
  ✦ BIDIRECTIONAL VALUE: each bridge document must show what Body-Signal-Architecture adds TO
    Human-Predictive-Drive AND what Human-Predictive-Drive adds TO Body-Signal-Architecture interpretation.
  ✦ Body-Signal-Architecture DATA OVER Human-Predictive-Drive ASSUMPTION: where Body-Signal-Architecture evidence conflicts with Human-Predictive-Drive
    framework predictions, the data takes priority. Flag for Human-Predictive-Drive update.
  ✦ PREDICTIONS ARE BRIDGE-SPECIFIC: predictions should arise from the
    CONNECTION between Human-Predictive-Drive and Body-Signal-Architecture, not from either side alone.
  ✦ 3-tier confidence applies to BRIDGE ANALYSIS:
    🟢 Both Human-Predictive-Drive concept and Body-Signal-Architecture data are well-established
    🟡 One side strong, other side synthesized/inferred
    🔴 Bridge connection hypothesized from indirect evidence
  ✦ EACH SESSION STARTS CLEAN (same as Phase 2 + 3)
  ✦ D05 = CAPSTONE (depends on D01-D04, serves as implicit completeness check)
```

---

## §9 — PROGRESS TRACKER

### Phase 1 — Body Systems (Track A)
| ID | File | Status | Session | Notes |
|----|------|--------|---------|-------|
| A01 | Peripheral-Nervous-System | ✅ COMPLETE | 2026-07-28 | v1.0. 5 PNS mechanisms: gate control, descending modulation, axon reflex, somatovisceral reflex, purinergic signaling. CT afferents. 40+ citations. |
| A02 | Autonomic-Nervous-System | ✅ COMPLETE | 2026-07-28 | v1.0. Autonomic Bridge Principle: ANS converts somatic input → organ response via somatoautonomic reflexes. 3 divisions (sympathetic, parasympathetic, enteric). Vagus nerve deep dive (80% afferent, NTS hub). PROKR2 neurons (Liu 2021 Nature) = molecular basis for acupoint-autonomic specificity. Cholinergic anti-inflammatory pathway (Tracey 2002). Breathing = Zone D Bridge mechanism. Polyvagal debate documented honestly. HRV as universal biomarker. 60+ citations. |
| A03 | Fascia-Connective-Tissue | ✅ COMPLETE | 2026-07-28 | v1.0. Fascial Continuum Principle: fascia = active body-wide mechanosensitive communication network, not passive wrapping. 3 layers (superficial/deep/visceral) as continuous system. ECM composition (collagen, elastin, HA, water 70%). Fibroblasts as key cellular targets (Rho/Rac mechanotransduction, Langevin 2006). Hidden neural network in deep fascia (Fede 2021). 3 mechanotransduction pathways (integrin-FAK-YAP, ion channels Piezo1/TRPV4, purinergic). Needle grasp mechanism (Langevin complete chain). 80% acupoints at fascial planes (Langevin 2002). Anatomy Trains myofascial meridians (Myers). Fascial pathology: densification (reversible) vs fibrosis (harder). TLF model: +25% thickness, -56% shear strain in chronic LBP. Sex hormone modulation (ERα, collagen I/III ratio). 7 open questions. 50+ citations. |
| A04 | Vascular-Lymphatic | ✅ COMPLETE | 2026-07-28 | v1.0. Circulatory Mediation Principle: vascular-lymphatic system = both DELIVERY MECHANISM and THERAPEUTIC TARGET. Every acupoint = neurovascular bundle (nerve+artery+veins). NO elevated at acupoints (Ma 2003/2017). HO-1 pathway: cupping/gua sha → controlled capillary microtrauma → macrophage phagocytosis → HO-1 → CO (anti-inflammatory) + biliverdin (antioxidant) + ferritin. Gua sha: 400% microcirculation increase (Nielsen 2007), HO-1 upregulation 48-120h at MULTIPLE organ sites (Kwong 2009), HIF-1α suppression (Ge 2025). Cupping NIRS: oxyHb ↑6.75μM at -300mmHg (Li 2023). Lewis triple response: CGRP arteriolar vasodilation + SP venular extravasation. Endothelial glycocalyx as mechanosensor (revised Starling principle, Levick & Michel 2010). Lymphangion intrinsic pump (Ca²⁺/NO oscillator, Davis 2025). Vascular pathology in chronic pain: trigger point ischemia, CRPS endothelial dysfunction, fibromyalgia microvascular changes. Blood stasis (Xue Yu) ↔ fibrinaloid microclots (2025). EA promotes angiogenesis via VEGF/Notch (Zhang 2023). 50+ citations. |
| A05 | Neuroimmune-Interface | ✅ COMPLETE | 2026-07-28 | v1.0. Neuroimmune Bidirectional Communication Principle: nervous+immune = unified bidirectional network. Neuropeptides (CGRP dual role: immunosuppressive in infection but pro-healing in tissue repair; SP pro-inflammatory via MRGPRX2 on mast cells). 6 pathways: local mast cell-neuron loop, purinergic ATP/P2X7→NLRP3→adenosine/A1 bridge, vagal anti-inflammatory (α7nAChR, Nature Medicine 2025 RA RCT), sympathetic-immune (β2-AR on lymphoid organs), central glial-mediated chronification (SGC→microglia P2X4→BDNF→Cl⁻ shift→astrocyte), CGRP-driven wound healing (Lu 2024 Nature: RAMP1-TSP1→M2). Force-immune axis (Frontiers 2026: macrophage mechanosensing, Ptgs2+ CPTC). SPMs (Serhan: resolvins/protectins/maresins → active resolution). Exercise myokines (IL-6 dual role). Cutaneous neuroimmunology (SALT, keratinocyte AMPs). Fibromyalgia as neuroimmune pathology (Goebel 2021 IgG→SGC). 60+ citations. |
| A06 | Endocrine-Local | ✅ COMPLETE | 2026-07-28 | v1.0. Local Chemical Milieu Principle: therapy points exist within dynamic chemical microenvironment of multiple paracrine/autocrine systems with extensive cross-talk. 6 signaling systems: (1) Endogenous opioids (β-endorphin/enkephalin/dynorphin from immune cells + keratinocytes, MOR/DOR/KOR on DRG neurons, peripheral opioid analgesia strengthens with inflammation, NO tolerance), (2) Endocannabinoid system (AEA/2-AG, CB1 presynaptic gatekeeper on nociceptors, CB2 immune modulation, 3-level endocannabinoid system analgesia: peripheral/spinal/supraspinal), (3) Cutaneous HPA axis (Slominski: skin CRH→POMC→ACTH+β-endorphin+α-MSH+cortisol, 11β-HSD enzymes, hair follicle cortisol synthesis), (4) Eicosanoids (COX-2 → PGE2, Ptgs2+ CPTCs force-immune axis), (5) H₂S gasotransmitter (completing NO/CO/H₂S triad, dose-dependent dual role), (6) Oxytocin + peripheral 5-HT (OTR on C/Aδ fibers, spinal circuit rebalancing). Key discoveries: endocannabinoid system-opioid cross-talk (CB2→β-endorphin from keratinocytes, Su 2012), Han frequency-dependent opioid release (2Hz=enkephalin 100Hz=dynorphin), Goldman 2010 adenosine A1 acupuncture, runner's high = eCB not opioid (Siebers 2021), OMT 168% AEA increase vs gentle touch = no change, parameter-dependent chemical prescribing. 55+ citations. |
| A07 | Dermatome-Somatotopic-Map | ✅ COMPLETE | 2026-07-28 | v1.0. Convergence Principle: dermatome+viscerotome share spinal segment → skin stim → organ effect. 4-level somatotopy (peripheral→spinal→thalamic→cortical). Head zones ↔ acupoints (Beissner 2011). Neurogenic spots = acupoints (Kim 2017). Cortical body matrix + chronic pain. 50+ citations. |
| A08 | Muscle-Tendon-Joint | ✅ COMPLETE | 2026-07-28 | v1.0. Musculoskeletal Reflex Modulation Principle: muscle-tendon-joint = self-regulating sensorimotor loop. Proprioceptors (spindle/GTO/joint receptors) → spinal reflexes (stretch/autogenic/reciprocal inhibition) → automatic tension regulation. Trigger points deep dive: Simons Integrated Hypothesis (motor endplate → ACh excess → ischemia → energy crisis → vicious cycle), Shah Biochemistry (pH 4.7, SP, CGRP, cytokines), Hocking 2023 unified theory (NMJ feedback failure), Strickland 2026 protective model (strain-repair mismatch). Dry needling mechanism (LTR → ACh depletion → endplate noise ↓). PNF debate (reflex inhibition vs stretch tolerance). DOMS pathway. Tendon mechanotransduction (PIEZO1-MKX/SCX, Cook-Purdam continuum). Enthesis structure (4 fibrocartilaginous zones). Joint mechanoreceptors (Freeman-Wyke 4 types). Wolff's law/mechanostat. 70% trigger point-acupoint overlap (Melzack 1977). 60+ citations. |
| A09 | Meridian-Examination | ✅ COMPLETE | 2026-07-28 | v1.0. Composite Substrate Assessment: meridians as traditionally described (qi channels) NOT found anatomically, BUT clinical observations (acupoint locations, some organ effects) correspond to measurable multi-system convergence zones. 7 candidate substrates evaluated: (1) Neural = strongest (93% trigger point-acupoint, PROKR2 molecular basis, 9/12 Back-Shu segmental match p<1 in 5 billion), (2) Fascial = strong for points (80%) but only 50% for pathways, (3) Neurovascular = weakened (Maurer 2019: VNBs at only 2% not 80%), (4) PVS = unconfirmed/controversial, (5) Interstitial = emerging (Zhang LHRC measurable), (6) Bioelectrical = mixed (Ahn 2008 review: inconclusive), (7) PSC = real but explainable by known mechanisms. Key findings: De Vernejoul radiotracer refuted (Simon 1988), Cho BL67 retracted (2006), sham ≈ verum at same points but verum > sham at non-indicated points. No consensus among 4 competing camps. TARA project (Langevin 2025) = most promising initiative. 70+ citations. TRACK A PHASE 1 COMPLETE (9/9). |

### Phase 2 — Therapy Methods (Track B)
| ID | File | Status | Session | Notes |
|----|------|--------|---------|-------|
| B01 | Acupuncture | ✅ COMPLETE | 2026-07-30 | TIER 1 multi-session. S1-S4 ALL DONE. B01-main.md ~3,600 lines, all 11 sections. §5: 6-level mechanism model, PROKR2, 2025-2026 breakthroughs. §6: all 9 Track A mapped. §7: 12+ traditions compared. §8: responder prediction + genetics. §10: 8 open questions. §11: full cross-references. Track A reality check DONE (2026-07-30): 4 areas checked, NO contradictions. B01 data STRENGTHENS A09 neural substrate ranking (PROKR2). |
| B02 | Acupressure | ✅ COMPLETE | 2026-07-31 | TIER 1 lite (2 sessions). ~2,847 lines, all 11 sections. Pressure-Point Divergence Model: RETAINED (location-dependent: gate control, somatovisceral, ABVN) + LOST (penetration-dependent: needle grasp, adenosine 24×, PROKR2, LTR) + GAINED (pressure-native: wider Aβ field, CT afferents, HA metabolism, trigger point compression, self-treatment frequency). 11 shared, 9 lost, 3 uncertain mechanisms mapped. Auricular = mechanistically distinct sub-modality. 8 open questions. 28 landmark citations. |
| B03 | Massage-General | ✅ COMPLETE | 2026-07-30 | TIER 1 multi-session. S1-S4 ALL DONE. B03-main.md ~3,100 lines, all 11 sections. §5: 6 mechanism categories integrated via pressure-dependent pathway model. §6: all 9 Track A mapped + parameter-system matrix. §7: 12+ traditions compared, B03 vs B01/B02/B04. §8: 5 variation sources + safety profile. §10: 8 open questions (Rapaport OT puzzle, endocannabinoid system threshold, PROKR2 in massage). §11: full cross-references. Cortisol reappraisal (Moyer vs Field) → Track A correction DONE (Reality Check #2, 2026-07-31). |
| B04 | Massage-Deep-Tissue | ✅ DONE | 2026-07-31 | TIER 2 (1 session). ALL 11 sections COMPLETE. B04-main.md ~2,500 lines. Structural-Neural Dissociation Model: deep tissue produces BOTH structural (fascial) and neural effects, but PERSISTENT therapeutic benefits are primarily NEURAL (descending modulation, gamma loop reset, central sensitization reversal). Structural changes (thixotropy, HA) are REAL but TRANSIENT (A08: stiffness returns minutes, pain relief lasts days). endocannabinoid system-Fascia Connection: deep OMT → AEA ↑168% (McPartland 2005), CB1/CB2 in fascia (Fede 2016) = molecular substrate for pressure-dependent endocannabinoid system threshold. 8 sub-modalities differentiated (DTM, MFR-D, MFR-I, Rolfing, trigger point-MT, Stecco FM, IASTM, self-MFR). A03 DOMINANT Track A activation (MOST fascial-engaged in Track B). Crane 2012 mechanotransduction (FAK/ERK → NF-κB↓). Rolfing 70+ years but near-zero controlled evidence. Gao 2026 structural verification gap. 8 open questions (structural vs neural persistence CRITICAL). |
| B05 | Dien-Chan | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B05-main.md 1,551 lines. Trigeminal Gateway Model: face = gateway to brainstem via CN V, with direct connections to vagal nucleus (DMN), NTS, LC (NE), DRN (5-HT). ~0 RCTs on Dien Chan specifically — LEAST evidence-supported therapy in Track B. BUT: eTNS (same V1 territory) is FDA-approved for migraine + ADHD, validating the nerve territory. 257 BQC points + 30+ projection maps UNVALIDATED — neuroanatomy supports 3 broad zones (V1/V2/V3), not 257 specific organ connections. Bùi Quốc Châu (Vietnam, 1980). Evidence gap = structural (geopolitical isolation, linguistic barrier, no research catalyst). 8 open questions (organ specificity CRITICAL). |
| B06 | Reflexology-Foot | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B06-main.md 1,680 lines. Non-Specific Mechanism Dominance Model: foot reflexology's clinical effects are REAL (anxiety, sleep, vital signs) but arise from NON-SPECIFIC mechanisms (gate control, relaxation response, therapeutic context) — NOT from zone-specific organ correspondence. Ingham map (1938) has NO neuroanatomical basis: foot L4-S3 does NOT segmentally connect to most claimed organs. Ernst 2009 (18 RCTs): "not convincingly effective." Descamps 2023 fMRI RCT (n=30): reflexology = sham massage on brain connectivity. WEAKEST Track A activation profile in Track B (A01 only MODERATE). HIGHEST Evaluative Gates contribution. Reflexology hierarchy: auricular (vagal) > facial (trigeminal) > foot (spinal, weakest). Zone map = therapeutic scaffolding, not mechanism. 8 open questions (zone specificity CRITICAL). |
| B07 | Cupping | ✅ DONE | 2026-07-31 | TIER 2 (1 session). ALL 11 sections COMPLETE. B07-main.md 2,076 lines. Negative Pressure Divergence Model: cupping = ONLY negative-pressure therapy, VASCULAR-DOMINANT mechanism (HO-1 primary, A04 §3.5). L1 Vascular PRIMARY, L2 Fascial STRONG, L3 Neural MODERATE, L4 Neuroimmune MODERATE, L5 Endocrine SECONDARY. 12+ variants, 6+ cultural traditions (oldest documented: 1550 BCE). Clinical profile: pain ONLY (short-term), no function/psychology improvement — consistent with narrow mechanism. Marks = THE mechanism, not side effect. Cultural research divide: dry (TCM/Western) vs wet (Islamic hijama). A04 data discrepancy flagged for RC#3. |
| B08 | Moxibustion | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B08-main.md 1,792 lines. Thermal-Point Convergence Model: moxibustion = ONLY purely thermal therapy in Track B (all others = mechanical). Dual-input system: Thermal component (TRPV1 hub, vasodilation, HSP, cutaneous HPA — location-independent) + Point component (somatovisceral reflex — location-dependent). TRPV1 Convergence Hub: moxibustion DIRECTLY activates TRPV1 which is convergence node for heat + endocannabinoid system (AEA) + eicosanoid (PGE2) + opioid sustain (prevents MOR desensitization, A06 line 817). HSP pathway UNIQUE to B08 — no other Track B therapy induces heat shock proteins. 针灸 (zhēn jiǔ) historical TWIN of B01 — Western separation is artifact; warm needling (温针灸) recovers unity. Breech Paradox: STRONGEST clinical evidence (Cardini 1998 JAMA n=260, 75.4% vs 47.7%, BL67) but WEAKEST mechanism explanation (S1→uterus violates A07 model). Moxa may PREDATE needling (Mawangdui ~168 BCE). Cross-cultural: cứu ngải (VN), okyū (JP), tteum (KR). A02 GAP flagged (heat as autonomic stimulus undocumented). OT thermal selectivity (A06). Track A: A01≈A04 PRIMARY > A07 STRONG > A02≈A06≈A05≈A09 MODERATE > A08>A03 MINIMAL. 8 open questions (BL67 breech mechanism CRITICAL). |
| B09 | Gua-Sha | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B09-main.md 1,656 lines. Shear-Force Convergence Model: gua sha = ONLY shear-dominant therapy in Track B. Single mechanical input (horizontal shear) activates TWO independent pathways: Path A = HO-1 vascular cytoprotection (shared with B07) + Path B = shear-specific fascial mobilization (unique to B09). HO-1 sibling to B07 cupping — same endpoint, different force vector. Key irony: foundational HO-1 evidence (Kwong 2009, Nielsen 2007, Ge 2025) actually comes FROM gua sha research, not cupping. 2025 TLF RCT (n=32, p=0.005): FIRST structural fascial verification — may partially address Gao 2026 gap (A03 §8 Q8). Broader clinical profile than cupping: pain + hepatoprotection (Chan 2011 HO-1→liver) + breast engorgement + perimenopausal. IASTM = Western derivative with different intensity/rationale. Cross-cultural: cao gio (VN), kerok (Indonesia), khoud lam (Laos). Unique concern: child abuse misidentification of sha marks. Facial cosmetic gua sha = different therapy (no sha → no HO-1). Track A: A04 PRIMARY > A03 STRONG > A05≈A01≈A08 MODERATE. 8 open questions (TLF replication CRITICAL). |
| B10 | Chiropractic | ✅ DONE | 2026-07-31 | TIER 2 (1 session). ALL 11 sections COMPLETE. B10-main.md 2,311 lines. Joint-as-Sensory-Organ Model: chiropractic reconceptualized — joint = SENSORY ORGAN (4 Freeman-Wyke receptor types), not passive hinge. HVLA = sensory INPUT triggering neural cascade, not mechanical realignment. ONLY therapy in Track B primarily targeting JOINTS (not soft tissue/skin/fascia). ONLY therapy where A08 is PRIMARY system. 5-level mechanism model: L1 Biomechanical (cavitation, gapping), L2 Proprioceptive Reset PRIMARY (Pickar 2002, Reed 2014 — spindle burst + post-activation depression), L3 Pain Modulation (gate control + descending inhibition, Plaza-Manzano 2014 β-endorphin), L4 Autonomic (somatoautonomic reflex, sympathetic chain proximity UNIQUE, Budgell 2000, Welch 2008), L5 Central Integration (Haavik 2012 SEP changes, sensorimotor processing). Velocity-Dependent Receptor Profile hypothesis: HVLA preferentially activates Type II (Pacinian, rapidly adapting) vs mobilization activates Type I (Ruffini, slowly adapting). Subluxation theory: historical foundation, 🔴 UNSUPPORTED as disease cause (WFC 2019). Clinical: LBP MODERATE (Rubinstein 2019 Cochrane, Paige 2017 JAMA — comparable to exercise/standard care, NOT superior), neck pain MODERATE (Bronfort 2012 > medication), non-MSK claims 🔴 UNSUPPORTED. Safety: VBA stroke rare (Cassidy 2008 — association similar for chiro vs PCP visit). D.D. Palmer 1895, profession vs technique distinction, technique taxonomy (7 variants, diversified 90%). Track A: A08≈A01 PRIMARY > A02≈A07 STRONG > A03≈A06 MODERATE > A04≈A05≈A09 MINIMAL. LEAST REPRESENTED therapy in Track A (2/9 files). Track A GAPS flagged: A02 MAJOR (zero B10 mentions despite somatoautonomic content), A07 SIGNIFICANT (no B10 mapping despite foundational segmental anatomy), A01 MINOR (§4.2 omits B10). 8 open questions (HVLA vs mobilization velocity question CRITICAL). |
| B11 | Dry-Needling | ✅ DONE | 2026-07-31 | TIER 1 lite (2 sessions). ALL 11 sections COMPLETE. S1 (~1,365L): §1-§4, §9. S2 (~1,050L): §5-§8, §10-§11. Total ~2,415 lines. DN 4-level model mapped to B01 6-level (L1 Local PRIMARY, L2 Segmental STRONG, L3 Supraspinal MODERATE, L4 Fascial VARIANT-DEPENDENT). "Different Entry Point, Same Building" synthesis: DN enters L1-L2, acupuncture L1-L6, 93.3% overlap = same anatomical substrate. LTR paradox resolved: LTR is ADDITIVE not exclusive (SDN works via L2 gate control). 6 variants mapped to mechanism levels (DNWES = most acupuncture-like). Unique scope-of-practice debate. 8 open questions. |
| B12 | EFT-Tapping | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B12-main.md 1,656 lines. Cognitive-Somatic Dissociation Model: B12 = ONLY therapy in Track B explicitly combining separable somatic (tapping) + cognitive (exposure/restructuring) components. WEAKEST Track A activation in ALL of Track B (0-1 systems at MINIMAL). 56% face points = trigeminal territory (B05 parallel). Clinical profile = psychological NOT MSK (anxiety d=1.23, depression d=1.31, PTSD d=1.88 vs waitlist but d=0.27 NS vs active). Cortisol ↓24-43% (Church 2012, Stapleton 2020) but cortisol-subjective dissociation. Spielmans 2020 re-analysis: sham tapping evidence NOT significant (d=-0.38, p=0.12). Gilomen & Lee 2015 (ONLY independent MA): g=-0.66 (moderate, much lower than advocate MAs). SEVERE structural COI: Church = editor+publisher+trainer+researcher simultaneously. NO guideline endorsement (VA/DoD, NICE, WHO, APA Div 12 denied Oct 2025). TIER 4 evidence quality. 8 open questions (somatic contribution CRITICAL). |
| B13 | Shiatsu | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B13-main.md ~1,560 lines. Whole-Body Protocol Deployment Model: B13 = same fundamental mechanisms as B02 acupressure but DIFFERENT DEPLOYMENT — "shotgun" (100-660+ points × 3-7 sec, whole-body coverage) vs B02's "rifle" (4-20 points × 30-120 sec, point-focused). Same physical stimulus (perpendicular sustained pressure at tsubos/acupoints), different treatment philosophy. TWO competing schools = NATURAL EXPERIMENT: Namikoshi (Western anatomy, NO meridians, 1940s) vs Masunaga Zen Shiatsu (extended meridians, Kyo/Jitsu energetics, 1970s) — same physical stimulus, opposed theories. If outcomes similar → theory = scaffolding, not mechanism. Hara diagnosis (abdominal palpation) UNIQUE to Shiatsu (esp. Zen Shiatsu) — UNVALIDATED zone-organ mapping, no reliability studies. KEY MECHANISTIC DIFFERENCE from B02: clothing barrier removes CT afferent activation entirely (no skin-to-skin contact → no oxytocin via CT→PVN pathway). KEY ADDITION: Zen Shiatsu stretching/rotation adds A08 joint/fascial engagement. ZERO dedicated mechanism studies — all mechanisms INFERRED from B02/B03 research. Clinical: labor pain MODERATE (but studies often = point-specific B02, not full Shiatsu protocol, Cabo 2018 critique), chronic LBP (Kobayashi 2019 only proper RCT, n=59, ODI p<0.01 wk8), fibromyalgia (Yuan 2013 n=34, pain ↓40.6%). TIER 5 evidence quality (alongside B05/B14 = WEAKEST in Track B). Track A: 7/9 systems at LOW-MODERATE, NO system at PRIMARY. Generalist profile similar to B15 but PASSIVE. Track A gaps: NONE — B13 adds no novel mechanism beyond B02/B03 entries. 8 open questions (Shiatsu vs massage head-to-head CRITICAL). |
| B14 | Craniosacral | ✅ DONE | 2026-07-31 | TIER 3 (1 session). ALL 11 sections COMPLETE. B14-main.md ~1,400 lines. Unfounded Premise, Non-Specific Effect Model: B14 = CLEAREST case in Track B where STATED MECHANISM is unsupported/contradicted yet clinical effects may partially exist. CSR inter-rater reliability = NEAR ZERO (Moran & Gibbons 2001 r=0.004, Hartman & Norton 2002 ICC 0.02-0.26 — practitioners examining SAME skull at SAME time report DIFFERENT rates). Cranial bone mobility: adult suture motion 1-25 μm (Downey 2006) = below palpation threshold (~200 μm). CSF rhythm: correlates with cardiac/respiratory, NOT separate rhythm. 5g force claim NEVER measured — likely 50-500g actual. LIGHTEST touch in Track B. Sutherland (1930s Cranial Osteopathy) → Upledger (1983 CranioSacral Therapy, commercialized, added SomatoEmotional Release). CO vs CST split parallels B13 Namikoshi vs Masunaga. Clinical: chronic neck pain MODERATE (Haller 2016 BMJ Open n=54, sham-controlled but dose mismatch), fibromyalgia (Castro-Sánchez 2011 n=92, inappropriate sham), LBP (Cerritelli 2017 n=46). Haller 2020 MA: vs passive SMD -0.32, vs active NS. If effects real → non-specific mechanisms: relaxation response (A02), CT afferents on hairy scalp, suboccipital myodural bridge (Hack 1995), therapeutic context/Evaluative Gates. MOST important therapeutic scaffolding case study in project — theory is CONTRADICTED (not just unproven) yet may enhance treatment via therapeutic context. TIER 5 evidence (weakest in Track B — foundational claims contradicted, not just unproven). Track A: WEAKEST alongside B12 — 0 systems MODERATE+, 2 at LOW, 4 MINIMAL/NONE. Track A gaps: NONE. 8 open questions (CST vs equivalent relaxation CRITICAL). LAST TRACK B FILE. |
| B15 | Tai-Chi-Qigong | ✅ DONE | 2026-07-31 | TIER 2 (1 session). ALL 11 sections COMPLETE. B15-main.md 1,180 lines. Multi-System Integration Model: B15 = ONLY therapy that simultaneously activates ALL 9 Track A systems at LOW-MODERATE intensity through SELF-GENERATED composite stimulus (movement + breathing + attention + balance + social + practice). First ACTIVE/MOVEMENT-BASED therapy in Track B — paradigm shift from passive reception to active self-regulation. 6-component composite stimulus: movement (3-4 METs), breathing (Zone D Bridge, resonance frequency 6/min), attention (interoceptive-proprioceptive), balance (continuous weight shifting), social (group practice), practice (motor learning). Clinical profile matches model: STRONGEST evidence for multi-system chronic conditions (fall prevention Li 2018 58% reduction NNT~3-4, Parkinson's balance Li 2012 NEJM > resistance training, knee OA Wang 2016 = PT, fibromyalgia Wang 2018 BMJ ≥ aerobic). 210+ SRs, but only 7% HIGH GRADE certainty. BROADEST Track A activation: A08+A02 PRIMARY, A01 STRONG, A05+A03+A06+A04 MODERATE. External Qigong assessed separately (🔴 no evidence). 8 open questions (Tai Chi vs matched exercise CRITICAL). Safest therapy in Track B (no serious AEs, Wayne 2014, Cui 2019). |
| B16 | Yoga-Therapy | ✅ DONE | 2026-07-31 | TIER 2 (1 session). ALL 11 sections COMPLETE. B16-main.md 1,214 lines. Adaptive Spectrum Model: B16 = ONLY therapy in Track B that can be CONFIGURED to target different Track A systems by selecting different styles (Yin=A03 fascial, Restorative=A02 autonomic, Hatha=balanced, Iyengar=A08 alignment, Vinyasa=A04 cardiovascular, Ashtanga=exercise physiology, Kundalini=A02+A06 neurochemical, Bikram=thermal). Wider intensity range than B15 (2-8 vs 2-4 METs). STRONGEST evidence for depression (Wang 2025 umbrella SMD -0.52, I²=6% very consistent), blood pressure, T2DM glycemic control, cancer-related fatigue. LBP = equivalent to exercise (Sherman 2011, Saper 2017, Cochrane 2022) — critical caveat. GABA hypothesis (Streeter 2007-2012) = unique B16 mechanism (yoga > walking for brain GABA). Bower 2014 transcriptional anti-inflammatory (NF-κB↓). Self-efficacy mediates 36% of disability effect (PMC9510936). CBT > yoga for diagnosed GAD (Simon 2021 JAMA Psych). Component dismantling gap (posture vs breath vs meditation never separated). Safety ≈ exercise (Cramer 2015). Track A: A02+A08 PRIMARY, A03 STRONG, A01 MOD-STRONG, A05+A06+A04 MODERATE. Sister modality to B15 — B15 for balance/falls, B16 for depression/autonomic. 8 open questions (yoga vs exercise-equivalent mechanisms CRITICAL). |

#### Track A Reality Checks
| # | After | Date | Findings |
|---|-------|------|----------|
| 1 | B01 | 2026-07-30 | 4 areas checked, NO contradictions. B01 STRENGTHENS A09 PROKR2 ranking. |
| 2 | B01+B02+B03 | 2026-07-31 | Cortisol Moyer qualification DONE. 4 claims across A02/A05/A06 qualified (Field "20-30%" = pre-post; Moyer between-group d=0.05-0.30). 3 Human-Predictive-Drive "Cortisol = Amplifier" rows updated. Moyer 2011 added to all 3 bibliographies. Human-Predictive-Drive convergence noted: cortisol responds to source removal (rest/safety), consistent with Human-Predictive-Drive amplifier model. |
| 3 | B01+B03+B02+B11+B07 | 2026-07-31 | **2 corrections, 3 areas no contradiction.** (1) A04 §4.3 PMC ATTRIBUTION FIXED: data from 2 studies had been conflated into 1 citation — PMC12121573 (Jia 2025, 10 RCTs, 656 pts, SMD -1.17) separated from PMC11955767 (Wang 2025, 72 trials, 5720 pts, MD). (2) A08 §4.2 LTR QUALIFICATION ADDED: "Multiple LTRs correlate with better outcomes" (Hong 1994) now notes Fernández-de-las-Peñas 2022 SR challenge + LTR = ADDITIVE not exclusive (SDN works without LTR). (3) No contradiction: A04 vascular-dominant ↔ B07 consistent, A01 cupping ①+③ ↔ B07 consistent, A09 neural substrate ↔ B11 STRENGTHENED. |
| 4 | B01+B03+B02+B11+B07+B05+B06+B04 | 2026-07-31 | **3 additions, 4 areas no contradiction.** (1) A03 §1.4 FIBROBLAST CB1/CB2 ADDED: Fede et al. 2016 (Eur J Histochem) — fascial tissue and fibroblasts express CB1 and CB2 cannabinoid receptors → fascia = endocannabinoid-responsive tissue. Added to §1.4, §5 citations. (2) A03 §8 Q8 STRUCTURAL VERIFICATION GAP ADDED: Gao & Gao 2026 (Front Cell Dev Biol) — "changes in pain/ROM do not verify altered fascial stiffness, hydration, adhesion, or inter-layer glide." Added to §8, §5 citations. (3) A06 §4.2 MOLECULAR SUBSTRATE IDENTIFIED: Fede 2016 connects A03 fascial CB1/CB2 → A06 McPartland 2005 AEA ↑168% → explains WHY deep fascial work = endocannabinoid system-dominant (gentle touch doesn't reach fascia → no CB engagement). Added to §4.2, §5 citations. (4) No contradiction: A07 trigeminal→DMX ↔ B05 consistent, A07 L4-S3 viscerotomes ↔ B06 consistent, A08 stiffness/gamma loop concepts ↔ B04 consistent (B04 named them, A08 already had the data). |
| 5 | B01+...+B04+B09+B08+B10 | 2026-07-31 | **6 additions/corrections, 0 contradictions.** (1) A02 §4.6 NEW: Spinal Manipulation + ANS — somatoautonomic reflex via sympathetic chain proximity (Budgell 2000), Welch 2008 sympathoexcitation→rebound, Kingston 2014 HRV inconsistent, response≠treatment distinction. (2) A02 §4.7 NEW: Moxibustion + ANS — thermal somatoautonomic pathway (Heat→TRPV1→C fiber→segmental reflex), diving reflex parallel. Old §4.6→§4.8 (1 cross-ref in B02 updated). §2.3 HRV, §5.2, §9 all updated. (3) A07 §4.7 NEW: Spinal Manipulation + Segmental Convergence — HVLA targets sclerotome (unique to B10), Budgell 2000 orphan citation now connected, palpation reliability limitation (κ=0.02-0.39). §5.1, §9 updated. (4) A01 §4.1 B09 row ADDED + §4.2 synthesis expanded: B10=①+②+④, B09=①+③, B04=①+②+③, B05=①+④ now listed. (5) A06 §4.2 moxibustion entry: (B08) code ADDED for consistency. (6) A03 §8 Q8 UPDATE: B09 2025 TLF RCT (PMC12419314, n=32, p=0.005) = first structural fascial verification. Partial but does not close gap. |
| 6 | B15+B16+B12 | 2026-07-31 | **4 additions, 2 cross-ref fixes, 0 contradictions.** (1) A01 §4.1: B15 Tai Chi + B16 Yoga rows ADDED to therapy table (proprioceptive/motor afferents, self-generated sustained activation). A01 §4.2: B15+B16 added to 5-mechanism synthesis list with note that movement therapies engage PNS via PROPRIOCEPTIVE/MOTOR pathways rather than PAIN-MODULATION focus. (2) A02 §4.8 NEW: Tai Chi/Qigong + ANS — voluntary breathing access (Zone D Bridge), parasympathetic shift during slow movement (Lu & Kuo 2003), sustained practice → autonomic retuning (partial Q3 answer). (3) A02 §4.9 NEW: Yoga + ANS — structured pranayama as BIDIRECTIONAL autonomic tool (unique: includes sympathetic activation via Kapalabhati, Telles 2011), GABA hypothesis (Streeter 2007-2012), inversions → baroreceptor activation. Old §4.8→§4.10 (2 cross-refs updated: B15 line 678, B02 line 1712). §5.2, §9 citations+cross-refs all updated. (4) B15/B16 §6.1 + §11.1 gap notes updated to reflect entries now exist. B12 Track A entries SKIPPED (LOW PRIORITY — minimal engagement). 4 areas checked = no contradiction: A02 breathing mechanism ↔ B15/B16 consistent, A01 proprioceptive pathways ↔ B15/B16 consistent, A02 §4.10 ANS dysregulation ↔ B15/B16 clinical profiles consistent, B12 Track A WEAKEST claim ↔ A01 confirmed. |
| 7 | B13+B14 (FINAL) | 2026-07-31 | **0 additions, 0 contradictions, 0 cross-ref fixes. CLEANEST RC.** B13: 5 Track A systems verified consistent (A01 gate control=B02, A02 parasympathetic, A08 gamma loop, CT absent due to clothing barrier correctly derived from A01). B14: 5 Track A systems verified consistent (A01 CT/Merkel below threshold, A02 relaxation response, A03 5g insufficient for mechanotransduction, A08 myodural bridge LOW). Myodural bridge (Hack 1995 RCPmi→dura C1-C2) noted as OPTIONAL A08 enrichment — general anatomy, not B14-specific. Both files confirmed: NO novel mechanisms beyond existing B02/B03 (B13) or non-specific pathways (B14). **FINAL TRACK A COMPLETENESS ASSESSMENT:** All 9 Track A files verified against all 16 Track B therapies. Coverage proportional to engagement level — PRIMARY/STRONG therapies represented, MINIMAL/NONE appropriately omitted. Total across 7 RCs: ~15 additions, ~4 corrections, 0 fundamental contradictions. **TRACK A FRAMEWORK VALIDATED BY TRACK B DATA. PHASE 2 COMPLETE. READY FOR PHASE 3 (TRACK C).** |

### Phase 3 — Cross-Reference (Track C)

**Execution order:** C01 → C03 → C04 → C02 → C05 (dependency-based)
**Prerequisite:** 9A + 16B = 25 source files COMPLETE. Track A VALIDATED by 7 RCs.

| Order | ID | File | Status | Session | Notes |
|-------|-----|------|--------|---------|-------|
| 1st | C01 | Stimulus-Pathway-Matrix | ✅ COMPLETE | 2026-07-31 | FOUNDATIONAL. 10 stimulus types taxonomized (penetration, sustained pt pressure, general pressure, deep pressure, negative pressure, horizontal shear, thermal, joint thrust, light percussion, self-generated movement). Main matrix: 10×9 stimulus×system with standardized levels. 7 parameter modifiers (pressure magnitude, speed/velocity, depth, electrical, body region, skin contact barrier, movement style). 10 emergent patterns (system dominance fingerprints, force direction typology, mechanical dominance, active-passive paradigm shift, HO-1 family, endocannabinoid system threshold, CT afferent pattern, needle family convergence, therapeutic scaffolding cluster, pressure continuum). 8 falsifiable predictions. ~1,200 lines. |
| 2nd | C03 | Common-Mechanisms | ✅ COMPLETE | 2026-08-01 | 51 distinct mechanism types identified across 16 therapies. Dual-Axis Unified Framework (spatial scale × mechanism domain) reconciling all therapy-specific level models. Shared Mechanism Catalog: 7 universal (≥10/16), 13 common (5-9/16), 16 narrow (2-4/16), 15 unique (1/16). 15 therapy-exclusive mechanisms across 8 therapies (B01=3, B08=3, B16=3, B07=2, B10=2, B09=1, B12=1). Therapeutic Scaffolding Analysis: B14 pure→B06 near-pure→B12 mixed→B05 partial spectrum. Specific-to-Non-Specific Spectrum ranking all 16 therapies. 6 cross-therapy patterns (gate control floor, depth-mechanism cascade, penetration bypass, HO-1 convergence, active therapy emergence, cognitive-somatic boundary). 4 emergent patterns (mechanism inequality distribution, 3 acquisition strategies, confidence gradient, non-specific floor ~SMD 0.2-0.4). 7 falsifiable predictions. ~1,100 lines. |
| 3rd | C04 | Location-Specificity-Map | ✅ COMPLETE | 2026-08-01 | WHERE matters? 16 therapies ranked on Location Specificity Spectrum (B01 most → B16 least). 6 validated location systems ranked: PROKR2 molecular (🟢 strongest) > segmental convergence (Head zones = Back-Shu, 1-in-5-billion) > neurogenic spots (Kim 2017 dynamic acupoints) > trigger point correspondence (93.3% Dorsher) > fascial convergence (80/50 split) > multi-system convergence zones. 7 unvalidated location maps analyzed (BQC 257, Ingham foot zones, Hara, CSR, sunnah, Qigong organs, chakra/nadi) — all serve as therapeutic SCAFFOLDING per C03. Body Region Pathway Hierarchy: face (CN V brainstem direct) > ear (ABVN vagal) > back (segmental + sympathetic chain) > abdomen (ENS) > limbs (PROKR2 supraspinal) > body general > foot sole (WEAKEST — no special pathway, no CT afferents). 7 emergent patterns: Precision Paradox, Fundamental Asymmetry (points > pathways), Dynamic Acupoint Phenomenon, Body Region Hierarchy, Scaffolding-Specificity Inverse, Independent Convergence (5 traditions → same sites), Location × Mechanism interaction. 6 falsifiable predictions. Claimed-vs-Validated 2×2 matrix. ~1,200 lines. |
| 4th | C02 | Condition-Response-Map | ✅ COMPLETE | 2026-08-01 | Condition × Therapy matrix across 12 clinical domains (~30 conditions × 16 therapies). 5-tier Evidence Classification (Tier 1: B01/B03/B15/B16 → Tier 5: B05/B13/B14). Head-to-head comparison catalog (16 direct comparisons). Mechanism-Based Explanation connecting clinical outcomes to C01 stimulus + C03 mechanisms + C04 location (5 subsections: mechanism matching, universal pain response, psychological profiles, PONV mechanism, active-passive divide). 6 emergent patterns: Universal Pain Response (12/16 therapies for LBP), Domain Specificity (each therapy has "home domain"), Active-Passive Divide, Evidence-Mechanism Dissociation, Condition-Specificity Gradient, Sham Paradox Resolved. 6 falsifiable predictions. ~1,300 lines. |
| 5th | C05 | Individual-Variation | ✅ COMPLETE | 2026-08-01 | CAPSTONE (depends ALL C01-C04). 6-domain variation taxonomy (genetic, dose-response, expectation, anatomical, demographic, responder phenotype). §3.1 Genetics: COMT condition-specific (EA cancer OR 2.79, knee OA NS), GABRB3 OR 3.85 (first RCT), OPRM1 NEGATIVE, cross-therapy genetic gap (B01 ONLY has data, 15/16 = desert). §3.2 Dose-Response: threshold vs linear model, Vickers flat verum-sham dose-response, pressure-threshold interaction (endocannabinoid system ~40-65N), dose-response gap = SINGLE LARGEST gap in field. §3.3 Expectation: scaffolding contribution gradient (~80-95% B14 → ~15-30% B01), 3-layer sham paradox per-patient variation, Vase 69.8% pain variance. §3.4 Anatomical: CT afferent density, fascial architecture (sex, age, BMI, CB1/CB2, hydration), nerve distribution (trigeminal, ABVN, PROKR2, dermatome ±1-2 segments), autonomic baseline effect. §3.5 Demographic: sex (fascial thickness, ERα, pain threshold), age, chronicity (central sensitization = threshold multiplier). §3.6 Responder Phenotype: B01 neuroimaging 83-88%, B10 Flynn CPR LR+24.4 (unvalidated), multi-factor model (gene × dose × expect × anatomy × demo × chronicity), predicted profiles per therapy family, Responder Prediction Paradox. 6 emergent patterns: Variation Data Inequality, Practitioner-as-Variable (κ 0.004-0.4), Adherence Divide (active vs passive), Threshold vs Linear, Expectation-Specificity Inverse, Self-Treatment Modifier. 6 falsifiable predictions. 8 open questions (Q1 CRITICAL: cross-therapy genetic predictor GABRB3→yoga). ~1,310 lines. **TRACK C COMPLETE (5/5 files).** |

### Phase 4 — Bridge Human-Predictive-Drive (Track D)
| ID | File | Status | Session | Notes |
|----|------|--------|---------|-------|
| D01 | Gap2-Signal-Transduction | ✅ COMPLETE | 2026-08-01 | FOUNDATIONAL. Sub-gap by sub-gap coverage assessment: SG-2.1 Receptor→Signal STRONG (60-70%, 10 stimulus types mapped to specific receptors), SG-2.2 Signal→Routing MODERATE (40-50%, routing table from C04 body region hierarchy, but thalamic gating not covered), SG-2.3 Cortical→Pattern MINIMAL (5-10%, B15/B16 neuroplasticity only), SG-2.4 NT→Function STRONG (50-60%, 12+ therapy-relevant NT-function pairs extending Human-Predictive-Drive's 3), SG-2.5 Plasticity→Compile MINIMAL (5-10%), SG-2.6 Sleep Consolidation NONE (0%). 3 Human-Predictive-Drive challenges: (1) Gap 2 = parallel streams not serial pipeline, (2) many therapy signals never reach cortex (Gap 2 partial dissolution), (3) thalamus not universal gateway (CN V, ABVN bypass). 4 Human-Predictive-Drive framework contributions: E₀→E₃ explains depth cascade, Direct-State explains non-specific floor, chunk framework explains persistence, insula gradient = bridge architecture. 5 emergent insights (Gap 2 = two halves body/brain-side, partial dissolution, L1 category mapping 9/17, delta rule→dose-response, 9 drivers at different Gap 2 depths). 6 falsifiable predictions. 7 open questions (Q1 CRITICAL: cortical pattern formation same/different for therapy signals). ~960 lines. |
| D02 | Zone-D-Expansion | ✅ COMPLETE | 2026-08-01 | v1.0 (~1,030 lines). Zone D = NOT monolithic but PROCESSING HIERARCHY (Level 0 Local Tissue → Level 4 Zone D Compilation). Body-Signal-Architecture expands Human-Predictive-Drive's 4-system Zone D to 9+ system FUNCTIONAL territory (includes fascia, circulation, immune, chemical, MSK). 5th sub-region: Local Tissue Processing (axon reflex, fascia, HO-1 — often doesn't reach spinal cord). Zone D Bridge = MULTI-CHANNEL (autonomic + circulatory + neuroimmune + chemical). Adherence Paradox DISSOLVES at initiation/processing boundary (PFC controls DECISION, Zone D controls MECHANISM). Active-Passive = two Zone D engagement strategies (injection vs bridge training). Non-specific floor + sham paradox = Zone D phenomena (stimulus-driven, not belief-driven). B16 reveals BIDIRECTIONAL Zone D Bridge (calming + activating pranayama). Zone D internal PFC-reach gradient (spinal motor=some → cardiac ganglia=zero → local tissue=zero). 7 predictions, 7 open questions (Q1 CRITICAL: additional voluntary Zone D bridges?). |
| D03 | Direct-State-Therapy-Paths | ✅ COMPLETE | 2026-08-01 | v1.0 (~970 lines). FULL 16-therapy Direct-State/Evaluative classification: EVERY therapy has some Direct-State (any physical contact), NO therapy purely Direct-State. Ratio varies ~8x: B03 massage (~75% Direct-State) to B14 craniosacral (~10% Direct-State). Therapy Reward Depth Gradient: Direct-State hardware → E₀ → E₁ → E₂ → E₃ (each therapy operates at MULTIPLE layers simultaneously). Body-Signal-Architecture reveals 6+ additional Direct-State pathways beyond Human-Predictive-Drive's 3 named (CT, endocannabinoid system, thermo): gate control, axon reflex, parasympathetic shift, HO-1, fascial mechanotransduction, proprioceptive comfort. CT hairy-skin limitation RESOLVED: Direct-State TOUCH is location-specific but Direct-State as CATEGORY is not (alternative pathways at glabrous skin). "Burnout-proof" REFINED: modality-specific — dynamic touch YES, static touch NO, thermal NO. Pressure = PATHWAY SELECTOR not just dose (light=CT, deep=endocannabinoid system, deeper=opioid E₁). A06 opioid tension identified and resolved (A06 used loose definition, Human-Predictive-Drive strict definition prevails). Dual Economy: Hardware Equity (Direct-State) + Software Variance (Evaluative). 6 predictions (naltrexone massage test, variance Direct-State vs Eval, dynamic vs static pressure pleasantness, reflexology CT-absent test, active practitioner experience, interoceptive accuracy correlation). 6 open questions (Q1 CRITICAL: naltrexone vs gate control). |
| D04 | Evaluative-Gates-Therapy | ✅ COMPLETE | 2026-08-01 | v1.0 (~980 lines). Body-Signal-Architecture scaffolding = Human-Predictive-Drive Evaluative Gates (same phenomenon, different vantage). Evaluative Gates Leverage Gradient: gates have DECREASING power at deeper therapy layers (Direct-State ~5-15% → E₃ ~70-95%). Non-specific floor REVISED from D01: floor = BOTH Direct-State (~SMD 0.1-0.2) AND minimum Evaluative Gates (~SMD 0.1-0.2), not just Direct-State. Per-therapy gate-setting predictions: Direct-State dominant therapies (B03) have STABLE gates, scaffolding-dominant (B14) have UNSTABLE gates. 5th gate outcome proposed: LAYERED (simultaneous different gate settings at different depth layers — "hurts good"). Prediction error = gate ACTIVATION mechanism (scaffolding generates predictions, Direct-State confirms → positive prediction error → AMPLIFY). Asymmetric transition → session design = gate management (front-load positive, grade intensity, protect gate setting, invest more in preventing negatives). Gate COMPILATION across sessions explains improving outcomes. Two responder types: Direct-State responder (biological) vs Evaluative responder (psychological). Scaffolding Paradox explained: scaffolding = prediction generator, truth irrelevant to function. Expectation-specificity inverse explained: STRUCTURAL consequence of gate leverage at different depth layers. 3 temporal scales for gates: structural (developmental), compilation (across sessions), acute (within session). 6 predictions, 6 open questions (Q1 CRITICAL: real-time gate measurement during therapy). |
| D05 | Interoception-Training | ✅ COMPLETE | 2026-08-01 | v1.0 (~1,410 lines). CAPSTONE — depends ALL D01-D04. Bridges Human-Predictive-Drive Interoception (Body-Base L1 #17 META KEYSTONE, Self-Observation 7-level gradient, Body-Knowing Inward, SAL) to Body-Signal-Architecture scattered interoception evidence across 19 files. Interoception Training Gradient: 4-tier passive-to-active continuum (Tier 1 pure passive B07-B11 = NO training → Tier 2 passive with attention B01-B04 = INCIDENTAL → Tier 3 guided B14/B05 = DIRECTED → Tier 4 active embodied B15/B16 = SYSTEMATIC), mapped to Self-Observation levels (0-1 → 1-2 → 2-3 → 3-5). Four Interoceptive Pathways × three Garfinkel dimensions: vagal (accuracy) + CT (sensibility) + proprioceptive (both) + fascial (sensibility). Accuracy vs Confidence distinction: most Body-Signal-Architecture evidence = sensibility only, only B16 has accuracy data (heartbeat counting pilot). Self-treatment = interoceptive ACCELERATOR (requires both signal generation AND reading). De Qi Paradox: passive therapy crosses into active territory through attention demands. Proprioception as interoception GATEWAY. Alexithymia (~10%) vs Compiled Suppress: OPPOSITE therapy implications (hardware=passive works, software=passive unlocks then active builds). THERAPY MULTIPLIER insight: interoception improvement multiplies value of ALL D01-D04 signals (Zone D access, Direct-State detection, gate compilation). Double virtuous cycle: gate compilation (D04) + interoception improvement = multiplicative improvement across sessions. 7 predictions, 6 open questions (Q1 CRITICAL: real-time interoceptive accuracy measurement during therapy). **TRACK D COMPLETE (5/5 files).** |

### Phase 5 — Core Synthesis
| Order | File | Status | Session | Notes |
|-------|------|--------|---------|-------|
| 1st | Core-Body-Architecture | ✅ COMPLETE | 2026-08-01 | v1.0 (~714 lines). "WHAT IS WHERE" — body-side circuit diagram. 9 systems as ONE INTEGRATED NETWORK (not 9 silos). Four architectural dimensions unified: (1) Depth = Zone D Processing Hierarchy 5 levels (Level 0 Local → Level 4 Compilation), with per-system depth reach map. (2) Region = Body Region Pathway Hierarchy (face CN V > ear ABVN > back segmental > abdomen ENS > limbs PROKR2 > body > foot WEAKEST). (3) Timing = Speed Gradient (ms axon reflex → months neuroplasticity) with parallel processing principle. (4) Stimulus = 10 types with dominance fingerprints + pressure as pathway selector (<5N CT → 40-65N endocannabinoid system threshold → 65-110N descending mod). 5 system interaction cascades: Detection→Response, Transmission→Amplification, Microtrauma→Repair, Movement→Multi-System, Convergence (A09 multi-system nodes). Compact system profiles (§4). Hardware variation: receptor density, fascial architecture (sex/age/BMI/CB1-CB2), nerve distribution (dermatome ±1-2, PROKR2, ABVN), autonomic baseline. 4 key principles: multi-system activation, depth stratification, partial dissolution (Gap 2), mechanical dominance (15/16). Honest assessment: 5 architectural open questions (Q1 CRITICAL: multi-system integration rules). |
| 2nd | Core-Therapy-Architecture | ✅ COMPLETE | 2026-08-01 | v1.0 (~1,750 lines). "HOW IT WORKS" — unified mechanism framework answering Central Question. §0 Orientation. §1 Central Question Answered (full 5-stage ASCII diagram, 3 key implications). §2 Dual-Axis Framework (51 mechanisms, 4 tiers, 3 strategies, confidence gradient). §3 Therapeutic Process Flow (§3.1 Stimulus Reception: 10 types + 10×9 matrix + pressure pathway selector + body region modifier; §3.2 Signal Transduction: Gap 2 two halves + parallel streams + partial dissolution + 9 drivers; §3.3 Processing Architecture: Zone D 5-level + Direct-State/Eval spectrum + reward depth gradient + dual economy + 16-therapy classification; §3.4 Evaluative Modulation: 5-step insula + gate leverage gradient + scaffolding paradox + gate compilation + session design; §3.5 Interoception Integration: 4 pathways×3 dimensions + training gradient + therapy multiplier + double virtuous cycle + alexithymia vs compiled suppress). §4 Unified Therapy Architecture (16-therapy unified profile table + condition-therapy matching + sham paradox 3-layer resolution + individual variation 6-domain taxonomy + responder prediction paradox). §5 Emergent Architecture (7 principles: multi-dimensional process, dual economy, mechanism inequality, confidence paradox, double virtuous cycle, scaffolding as prediction generator, active-passive as architectural distinction). §6 Honest Assessment (explains well/partially/cannot/may get wrong + open questions hierarchy from 32 Qs). §7 Predictions (14 consolidated from 64, organized by what they resolve: floor, matching, depth cascade, scaffolding, variation, interoception). §8 Cross-References (36 source files, Human-Predictive-Drive connections, 6 unique analytic products). **PHASE 5 COMPLETE.** |

---

## §10 — FIRST SESSION RECOMMENDATION

```
Session tiếp theo: A01 — Peripheral Nervous System

Lý do: Đây là nền tảng vật lý cơ bản nhất. MỌI liệu pháp cơ thể đều
tương tác với hệ thần kinh ngoại vi. Không hiểu PNS → không hiểu được
bất kỳ phương pháp nào.

Nội dung cần cover:
  - Somatic nervous system (sensory + motor fibers)
  - Spinal nerves (31 pairs) + cranial nerves (12 pairs)
  - Sensory receptor types: mechanoreceptors, nociceptors, thermoreceptors, proprioceptors
  - Nerve fiber classification: A-alpha, A-beta, A-delta, C fibers
  - Reflex arcs: monosynaptic, polysynaptic
  - Referred pain mechanism (viscerosomatic convergence)
  - Gate control theory of pain (Melzack & Wall 1965)
  - Peripheral sensitization / central sensitization
  - Axon reflex (local tissue response without CNS involvement)
  - Neuroplasticity in peripheral nerves

Human-Predictive-Drive cross-check:
  - Core-Hardware.md §4 (receptor system)
  - Neural-Architecture.md §5 (peripheral neural systems)
  - Dissonance-Signal-Architecture.md §1 (nociception pathways)
```
