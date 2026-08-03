# Acupoint-Atlas — Master Plan

## 1. Tại sao project này cần thiết

Body-Signal-Architecture đã phân tích huyệt từ góc nhìn **"cơ chế nào giải thích huyệt"**
(A09 meridian substrates, C04 location specificity). Nhưng chưa bao giờ đi ngược lại và hỏi:

> **"Với mỗi vị trí huyệt cụ thể, TẤT CẢ data — đông y, tây y, cross-tradition — nói gì?"**

9 file BSA hiện tại đã establish:
- Multi-system convergence zone model (A09 S2.2, Core-Body-Architecture S3.5)
- 6-level location specificity hierarchy (C04 S3.4)
- 93.3% trigger point-acupoint correspondence (B11 S3.3, Dorsher 2008)
- Condition-therapy matrix by domain (C02 S3.2)
- 8 hệ thống point category (B01 S3.1: 361+ points)

Nhưng TẤT CẢ đều organized by system / condition / category — không bao giờ by individual point.

Data đông y = data lâm sàng thực, tích lũy hàng nghìn năm, từ hàng triệu ca bệnh.
5 truyền thống độc lập (TCM ~200 TCN, Head zones 1893, trigger points 1942,
Anatomy Trains 2001, neurogenic spots 2017) independently identified the same body sites.
Xác suất trùng hợp ngẫu nhiên: ~1/7 nghìn tỷ (Dorsher 2008).

Bỏ qua dataset này = thiếu sót lớn nhất của BSA.

**Nguyên tắc:** Data thực tế là trọng tài cao nhất. Nếu data từ Atlas thay đổi
hiểu biết về core framework → core framework phải cập nhật.

---

## 2. Cấu trúc folder

```
Body-Signal-Architecture/
  Acupoint-Atlas/
    plan.md                              ← file này (master plan)
    AP-00-Core.md                        ← methodology + template reference

    ├── 12 Kinh chính (Regular Meridians):
    │   AP-01-Lung-LU/
    │     ├── plan.md                    ← child plan (data survey + tier assignment)
    │     └── AP-01-Lung-LU.md           ← LU1-LU11 (11 huyệt)
    │   AP-02-Large-Intestine-LI/
    │     ├── plan.md
    │     └── AP-02-Large-Intestine-LI.md    ← LI1-LI20 (20 huyệt)
    │   AP-03-Stomach-ST/
    │     ├── plan.md
    │     └── AP-03-Stomach-ST.md        ← ST1-ST45 (45 huyệt)
    │   AP-04-Spleen-SP/
    │     ├── plan.md
    │     └── AP-04-Spleen-SP.md         ← SP1-SP21 (21 huyệt)
    │   AP-05-Heart-HT/
    │     ├── plan.md
    │     └── AP-05-Heart-HT.md          ← HT1-HT9 (9 huyệt)
    │   AP-06-Small-Intestine-SI/
    │     ├── plan.md
    │     └── AP-06-Small-Intestine-SI.md    ← SI1-SI19 (19 huyệt)
    │   AP-07-Bladder-BL/
    │     ├── plan.md
    │     └── AP-07-Bladder-BL.md        ← BL1-BL67 (67 huyệt — lớn nhất)
    │     └── (chia thêm file nếu cần: AP-07-BL-BackShu.md, etc.)
    │   AP-08-Kidney-KI/
    │     ├── plan.md
    │     └── AP-08-Kidney-KI.md         ← KI1-KI27 (27 huyệt)
    │   AP-09-Pericardium-PC/
    │     ├── plan.md
    │     └── AP-09-Pericardium-PC.md    ← PC1-PC9 (9 huyệt)
    │   AP-10-Triple-Burner-TE/
    │     ├── plan.md
    │     └── AP-10-Triple-Burner-TE.md  ← TE1-TE23 (23 huyệt)
    │   AP-11-Gallbladder-GB/
    │     ├── plan.md
    │     └── AP-11-Gallbladder-GB.md    ← GB1-GB44 (44 huyệt)
    │   AP-12-Liver-LR/
    │     ├── plan.md
    │     └── AP-12-Liver-LR.md          ← LR1-LR14 (14 huyệt)

    ├── 2 Mạch có huyệt riêng (Extraordinary Vessels with own points):
    │   AP-13-Governing-GV/
    │     ├── plan.md
    │     └── AP-13-Governing-GV.md      ← GV1-GV28 (28 huyệt, Đốc Mạch)
    │   AP-14-Conception-CV/
    │     ├── plan.md
    │     └── AP-14-Conception-CV.md     ← CV1-CV24 (24 huyệt, Nhâm Mạch)
    │   Note: 6 mạch kỳ kinh còn lại (Chong, Dai, Yin/Yang Qiao,
    │   Yin/Yang Wei) dùng huyệt từ kinh chính — không cần folder riêng.
    │   8 Confluent Points ghi trong template từng huyệt (§3 Point Category).

    ├── Extra Points:
    │   AP-15-Extra-Points/
    │     ├── plan.md
    │     └── AP-15-Extra-Points.md      ← EX-HN, EX-CA, EX-UE, EX-LE (48+)

    ├── Microsystems (logic giải phẫu độc lập — tách riêng vì KHÔNG follow
    │   meridian mapping, mỗi hệ có somatotopic model riêng):
    │   AP-16-Auricular/
    │     ├── plan.md
    │     └── AP-16-Auricular.md         ← ABVN vagal pathway, Nogier model
    │   AP-17-Scalp/
    │     ├── plan.md
    │     └── AP-17-Scalp.md             ← Jiao / YNSA / Zhu / WHO 14 lines
    │   AP-18-Other-Microsystems/
    │     ├── plan.md
    │     └── AP-18-Other-Microsystems.md  ← Korean Hand (KHT),
    │                                         foot zones (nếu đủ data)

    ├── Cross-reference (synthesis — Phase 3-5):
    │   AP-Cross-Tradition/
    │     └── AP-Cross-Tradition.md      ← convergence tables across 8 traditions
    │   AP-Mechanism-Summary/
    │     └── AP-Mechanism-Summary.md    ← per-point mechanism + gap analysis
    │
    └── Framework Impact (nếu cần):
        AP-Core-Framework-Impact.md      ← findings that change Core BSA
```

**Tổng: 361 huyệt chính + 48 extra + microsystems ≈ 450+ điểm**

**Folder pattern:** Giống Therapy-Methods — mỗi đơn vị = 1 folder chứa file chính + child plan.
Folder cho phép chia nhỏ, thêm file phụ, giữ working notes mà không phình folder gốc.
Kinh lạc lớn (BL 67 huyệt, ST 45, GB 44) có thể cần chia nhiều file.

**Microsystems tách riêng vì:**
- Auricular: ABVN vagal pathway, somatotopic mapping riêng (Nogier inverted fetus)
- Scalp: cortical projection mapping, 3+ hệ thống độc lập (Jiao/YNSA/Zhu)
- Hand/Foot: microsystem mapping riêng, không follow meridian logic
- Template cho microsystems sẽ KHÁC template chính (xem §3.2)

---

## 3. Template chuẩn hóa

### 3.1 Template cho huyệt kinh lạc (AP-01 → AP-15)

Tất cả fields, nhưng depth khác nhau tùy evidence tier (xem §4):

```markdown
### [Code] — [Tên Hán-Việt] ([Tên tiếng Trung], [Pinyin])

**Vị trí giải phẫu:**
  WHO standard location (WPRO 2008)
  Anatomical landmarks + measurement (cun/cm)
  Needle depth range (standard clinical, cm)

**Cấu trúc mô học tại điểm:**
  Nerve supply: [specific branch, spinal segment]
  Fascial plane: [superficial/deep fascia]
  Vascular: [artery/vein tại điểm]
  Muscle layer: [từ nông → sâu]
  Receptor density: [nếu có data — Ma SX]
  → Cross-ref: A01, A03, A04, A05, A08

**Phân loại huyệt (Point Category Membership):**
  (Một huyệt có thể thuộc NHIỀU category — ghi tất cả)
  Five Shu: [Jing-Well / Ying-Spring / Shu-Stream / Jing-River / He-Sea + element]
  Yuan-Source: [có/không]
  Luo-Connecting: [có/không, kết nối kinh nào]
  Xi-Cleft: [có/không]
  Back-Shu: [organ + vertebral level]
  Front-Mu: [organ]
  Eight Confluent: [extraordinary vessel pairing]
  Hui-Meeting: [tissue type: Qi/Blood/Tendon/Vessel/Bone/Marrow/Zang/Fu]
  Special: [Command Point / Ma Dan-yang Star / Sun Si-miao Ghost / Lower He-Sea, etc.]

**Cross-tradition mapping:**
  TCM acupoint: [code + traditional function]
  Trigger point: [Dorsher mapping — muscle + referred pain pattern]
  Ashi correspondence: [palpation-finding tại vùng này]
  Marma point: [107-point Ayurvedic system, nếu có tương ứng]
  Head zone: [dermatome-viscerotome, Beissner 2011]
  Anatomy Trains: [myofascial line, Myers/Dorsher 2009]
  Neurogenic spot: [Kim 2017 overlap]
  Cupping point: [TCM / Sunnah, nếu applicable]
  Convergence score: [n/8 traditions có overlap tại điểm này]

**Chỉ định truyền thống (DATA — ghi nhận, không endorse as mechanism):**
  Nguồn cổ: [Neijing / Jiayi Jing / Nanjing / Dacheng — ghi nguồn cụ thể]
  Nguồn hiện đại: [Deadman / WHO]
  Kinh nghiệm lâm sàng nổi bật: [patterns nhất quán across sources]

**Bằng chứng hiện đại:**
  Systematic review / Meta-analysis: [citation + kết quả chính]
  RCT data: [nếu có]
  Sham comparison: [active vs sham outcome]
  Confidence: 🟢 Confirmed / 🟡 Plausible / 🔴 Unvalidated
  (Assigned PER INDICATION — cùng huyệt có thể 🟢 cho A và 🔴 cho B)

**Dynamic acupoint properties:**
  Disease-state sensitization: [có data? Kim 2017, Chen Rixin heat-sensitive]
  Threshold change under pathology: [nếu có data]
  → Cross-ref: C04 S4 (Dynamic Acupoint Phenomenon)

**Cơ chế giải thích (BSA framework attribution):**
  Track A systems activated at this specific point
  WHY this location produces these effects (mechanism, not theory)
  Gap: truyền thống nói gì mà mechanism chưa giải thích được
  ⚡ Framework note: [nếu findings extend/challenge Core BSA — xem §7.2]

**Kỹ thuật kích thích + dose-response:**
  Châm (B01): needle depth, De Qi characteristics
    EA: [frequency/intensity mapping — Han: 2Hz→enkephalin, 100Hz→dynorphin]
  Bấm huyệt (B02): pressure range, technique
    PROKR2 depth question: [surface pressure đủ reach?]
  Cứu (B08): method (direct/indirect/stick), thermal parameters
  Dry needling (B11): technique variant, LTR expected?
  So sánh: [kỹ thuật nào hiệu quả nhất tại điểm này, nếu có data]

**An toàn:**
  Pneumothorax risk: [vùng ngực/lưng — ghi max safe depth]
  Vascular risk: [gần mạch lớn?]
  Pregnancy: [LI4, SP6, BL67, sacral points — contraindicated/caution]
  Special restriction: [VD: CV8 = moxa-only, needle-prohibited]
```

### 3.2 Template cho microsystem (AP-16 → AP-18)

Microsystems có logic giải phẫu khác — template điều chỉnh:

```markdown
### [Code/Zone] — [Tên] ([System: Auricular/Scalp/Hand/Facial])

**Vị trí trên microsystem map:**
  Somatotopic location + anatomical landmark trên ear/scalp/hand/face
  Corresponding body region/organ in microsystem model

**Giải phẫu tại điểm:**
  Nerve supply: [đặc biệt: ABVN cho auricular, trigeminal branches cho facial]
  Pathway to CNS: [vagal → NTS? trigeminal → brainstem?]

**Cross-system mapping:**
  Microsystem A (Nogier/Jiao/KHT): [vị trí trong system A]
  Microsystem B (NADA/YNSA/Dien Chan): [vị trí trong system B, nếu có]
  Body acupoint tương ứng: [TCM point nào có cùng indication?]
  Convergence: [các microsystems agree hay diverge?]

**Chỉ định truyền thống:**
  [Theo từng microsystem tradition]

**Bằng chứng hiện đại:**
  [RCT/SR data, confidence tier]

**Cơ chế giải thích:**
  [Vagal pathway? Cortical mapping? Somatotopic reflex?]
```

### 3.3 Conventions cho template

- **WHO 2008** = primary location reference (khi available)
- Nerve naming: **specific branch** (không chỉ "sciatic nerve" — branch nào?)
- Depth: **cm** (không cun — precision hiện đại)
- Spinal segment: luôn ghi
- Field không applicable → bỏ (không ghi "N/A")
- Field không có data → ghi "No data" (phân biệt với "not applicable")
- Cross-tradition: check tất cả 8 traditions trong §6, ghi rõ "No correspondence found"
  nếu đã check mà không tìm thấy

---

## 4. Depth Tiering System

Không phải tất cả 450+ huyệt đều có cùng lượng evidence.
Depth tiering quyết định bao nhiêu effort cho mỗi huyệt:

### Tier A — Deep Analysis
**Criteria:** ≥1 systematic review + mechanism evidence + cross-tradition data
**Depth:** Full template, mọi field chi tiết. Web search cho từng huyệt.
Discussion section riêng nếu có findings quan trọng.
**Ước tính:** ~20-30 huyệt (ST36, PC6, LI4, SP6, BL67, Back-Shu group, etc.)

### Tier B — Standard Entry
**Criteria:** Có RCT data hoặc strong clinical tradition + ≥2 tradition mapping
**Depth:** Full template nhưng mỗi field ngắn gọn hơn. Web search theo nhóm.
**Ước tính:** ~80-120 huyệt (Five Shu points, Yuan-Source, Xi-Cleft, etc.)

### Tier C — Minimum Viable Entry
**Criteria:** Có trong WHO 2008 nhưng ít/không modern evidence
**Depth:** Location + anatomy + point category + cross-tradition + traditional indications.
Modern evidence = "No systematic modern study" nếu đúng vậy. Không web search riêng.
**Ước tính:** ~250-300 huyệt

**Tier assignment xảy ra trong child plan** — khi survey data thực tế cho từng kinh.
Tier không phải nhãn cố định — nếu trong quá trình tổng hợp phát hiện huyệt Tier C
có data interesting → nâng lên Tier B.

---

## 5. Quality Control Principles

### 5.1 Data truyền thống = DATA, không phải mechanism
Ghi nhận "TCM nói huyệt X trị bệnh Y" như **observation** (clinical data point).
KHÔNG endorse "vì Khí lưu thông" như mechanism.
Observation = valuable data. Tìm mechanism riêng từ Track A.
Observation + mechanism = complete picture. Observation alone = still valuable.

### 5.2 Confidence tiering cho evidence
- 🟢 **Confirmed** — Modern evidence confirms (RCT + mechanism identified)
- 🟡 **Plausible** — Partial mechanism, limited modern study, or plausible pathway
- 🔴 **Unvalidated** — Recorded, no modern mechanism, or mechanism contradicts

Confidence assigned **per indication**, không phải per huyệt.
Một huyệt có thể có 🟢 cho indication A và 🔴 cho indication B.

### 5.3 Cross-tradition convergence = signal strength
Convergence score (n/8) = quantified anatomical confidence signal.
≥3 traditions agree = high confidence vị trí này có ý nghĩa giải phẫu,
dù functional attribution khác nhau giữa các truyền thống.

### 5.4 "Không biết" = giá trị
Ghi rõ khi mechanism unknown. Gap = research opportunity, không phải failure.
BL67 breech = most important gap trong toàn bộ BSA. Framework phải honest.

### 5.5 Data thay đổi framework
Nếu per-point analysis reveal patterns mà Core BSA chưa capture:
1. Ghi ⚡ Framework note trong Atlas entry
2. Accumulate evidence across phases
3. Phase 5: formal assessment + proposed updates
Framework phục vụ data, không ngược lại.

### 5.6 Consistency across entries
- WHO 2008 location = primary reference
- Nerve naming = specific branch
- Depth = cm (modern precision)
- Spinal segment = always noted
- Cross-tradition = checked against ALL 8 traditions (§6)
- Same terminology, same format, mọi entry

---

## 6. Cross-Tradition Mapping Scope

8 traditions/systems to check for every huyệt:

| # | Tradition / System | Primary Source | Era | BSA Reference |
|---|---|---|---|---|
| 1 | TCM Acupoint | WHO 2008, Neijing, Deadman | ~200 TCN — nay | B01 S3 |
| 2 | Western Trigger Point | Dorsher 2006-2022, Travell & Simons | 1942 — nay | B11 S3.3 |
| 3 | Ashi Point (palpation-based) | Sun Simiao 652 CE | 652 CE | B11 S3.3 |
| 4 | Marma Point (Ayurvedic) | Sushruta Samhita, Frawley | ~600 TCN | B02 S1.3 |
| 5 | Head Zone (dermatome-viscerotome) | Head 1893, Beissner 2011 | 1893 | C04 S3.2.2 |
| 6 | Anatomy Trains (myofascial line) | Myers 2001, Dorsher 2009 | 2001 | A09 S1.3 |
| 7 | Neurogenic Inflammatory Spot | Kim 2017 | 2017 | C04 S3.2.3 |
| 8 | Cupping Point | TCM Back-Shu, Sunnah | varies | C04 |

**Convergence data:**
- Traditions 1-2: 93.3% correspondence (Dorsher 2008)
- Traditions 1-6: 8/9 Anatomy Trains lines overlap meridians (Dorsher 2009)
- Traditions 1-5: Back-Shu match organ innervation 9/12 levels (A09)
- Traditions 1-8: TCM Back-Shu vs Sunnah cupping = DIVERGENCE (C04) — important negative finding

**Microsystems (AP-16 → AP-18) có mapping riêng:**
Auricular (Nogier/NADA/BFA), Scalp (Jiao/YNSA/Zhu/WHO), Hand (KHT), Facial (Dien Chan)
→ handled trong microsystem template (§3.2)

---

## 7. Integration Conventions with BSA

### 7.1 Cross-reference format
Atlas entry → BSA file:
```
→ Cross-ref: A01 S2.3, B01 S3.1, C04 S3.2.1
```
Format: [FileCode] [Section]. Luôn ghi section number.

### 7.2 Framework notes
Khi Atlas data extends hoặc challenges existing BSA analysis:
```
⚡ Framework note: [observation] extends/challenges [specific claim in FileCode SX.X]
```
Accumulate tất cả ⚡ notes → feed vào Phase 5 (Framework Impact).

### 7.3 Bidirectional linking
- Atlas → BSA files: ghi trong Atlas entries (§7.1)
- BSA files → Atlas: KHÔNG update trong Phase 2.
  Batch update trong Phase 5 nếu cần.
  Lý do: tránh disruption to existing corpus trong khi Atlas đang build.

### 7.4 Khi data contradicts framework
1. Ghi rõ contradiction trong Atlas entry
2. Không sửa framework ngay
3. Accumulate evidence
4. Phase 5: formal assessment

---

## 8. Nguồn data chính

### Sơ cấp (Primary — vị trí + chỉ định gốc)
- **WHO** Standard Acupuncture Point Locations (WPRO 2008) — vị trí chuẩn quốc tế
- **Huangdi Neijing** (黄帝内经, ~200 TCN) — chỉ định cổ nhất
- **Zhenjiu Jiayi Jing** (针灸甲乙经, Huangfu Mi, ~260 CE) — hệ thống hóa huyệt đầu tiên
- **Nanjing** (难经) — Five Shu logic, Yuan-Source theory
- **Zhenjiu Dacheng** (针灸大成, Yang Jizhou, 1601) — tổng hợp lâm sàng lớn nhất
- **Sushruta Samhita** (~600 TCN) — Marma point descriptions (Ayurvedic)

### Thứ cấp (Modern Synthesis + Evidence)
- **Deadman, Al-Khafaji & Baker** — A Manual of Acupuncture (chuẩn giáo dục phương Tây)
- **Dorsher** 2006-2022 — trigger point-acupoint correspondence series
  - 2008 (The Journal of Pain): 93.3%, 238/255 points
  - 2009 (Medical Acupuncture): Anatomy Trains correspondence
- **Liu et al.** 2020 (Neuron) + 2021 (Nature) — PROKR2 molecular basis
- **Langevin & Yandow** 2002 — fascial correspondence (80% at fascial planes)
- **Beissner** 2011 — Head zone-acupoint mapping
- **Kim** 2017 — neurogenic inflammatory spots at acupoint locations
- **Melzack** 1977 — trigger point-acupoint overlap (71%, foundational)
- **Birch** 2003 — reanalysis of Melzack (18-40%, methodological critique — lower bound)
- **Birch** 2025 — 862 systematic reviews across 184 conditions
- **Ma SX** — acupoint histology, receptor density at specific points
- **Han Jisheng** — EA frequency-opioid mapping (2Hz→enkephalin, 100Hz→dynorphin)
- **TARA project** (Langevin 2025) — standardized 3D acupoint atlas initiative

### Cross-tradition
- **Travell & Simons** — Myofascial Pain and Dysfunction (trigger point reference)
- **Frawley** — Marma point analysis (Ayurvedic, 107 points)
- **Myers** — Anatomy Trains (myofascial meridians)
- **Nogier** — auricular cartography (inverted fetus model)
- **Jiao Shunfa** — scalp acupuncture system
- **Yamamoto (YNSA)** — scalp acupuncture system


### BSA internal cross-references
- **Track A:** A01 (nerve), A03 (fascia), A04 (vascular), A05 (immune),
  A07 (visceral reflex), A08 (muscle), A09 (meridian substrates)
- **Track B:** B01 (acupuncture), B02 (acupressure), B08 (moxibustion), B11 (dry needling)
- **Track C:** C02 (condition-response), C04 (location specificity)
- **Core:** Core-Body-Architecture, Core-Therapy-Architecture

---

## 9. Phase Overview

### PHASE 0 — Core Methodology
**File:** AP-00-Core.md
**Nội dung:** Methodology document — cách thu thập, đánh giá, tổng hợp data.
Template reference. Confidence system. Working conventions.
**Scope:** 1 session.

### PHASE 1 — Tier 1 Points (Most-studied, highest evidence)
**Scope:** ~15-20 huyệt có bằng chứng mạnh nhất, cắt ngang nhiều kinh.
**Mục đích:** Validate template. Phát hiện pattern sớm. Thiết lập quality benchmark.
**Output:** Entries viết trực tiếp vào file kinh lạc tương ứng
(ST36 → AP-03, PC6 → AP-09, etc. — không tạo file riêng).

**Nhóm ưu tiên:**

| Nhóm | Huyệt | Lý do ưu tiên |
|---|---|---|
| A — Molecular | ST36, ST25 | PROKR2 pathway (Liu 2021 Nature) |
| B — Cochrane/RCT | PC6, LI4, SP6, BL67 | Strongest single-point clinical data |
| C — Clinical importance | HT7, LR3, GV20, KI1, Yintang | Most-used clinically |
| D — Segmental proof | BL13, BL15, BL18, BL20, BL23 | Back-Shu convergence with dermatomes |
| E — Auricular/vagal | Ear Shen Men, Sympathetic, Point Zero | ABVN pathway |

### PHASE 2 — Systematic by Meridian
**Scope:** Tất cả 361+ huyệt + extra + microsystems.
**Tiếp cận:** Child plan protocol (§10) — survey → plan → execute → review cho mỗi đơn vị.

**Thứ tự ưu tiên** (evidence density, clinical importance, convergence data):

| Batch | Đơn vị | Lý do ưu tiên |
|---|---|---|
| 1 | ST, BL, LI | Nhiều evidence, landmark points |
| 2 | SP, PC, LR, HT | Strong individual points (SP6, PC6, LR3, HT7) |
| 3 | KI, GB, LU | KI1, GB34, LU7 |
| 4 | SI, TE, GV, CV | GV20 evidence, CV clinical use |
| 5 | Extra Points, Microsystems | AP-15 → AP-18 |

**Session count cho mỗi kinh → quyết định trong child plan, KHÔNG estimate trước.**

### PHASE 3 — Cross-Tradition Synthesis
**File:** AP-Cross-Tradition.md
**Scope:** Convergence tables across 8 traditions (§6) cho tất cả points đã cover.
Phân tích: highest convergence points, zero convergence points, pattern analysis.
**Prerequisite:** Phase 2 hoàn tất (hoặc gần hoàn tất).

### PHASE 4 — Mechanism Attribution
**File:** AP-Mechanism-Summary.md
**Scope:** Per-point mechanism map. Gap analysis.
Pattern discovery — patterns mới emerge từ per-point data mà core BSA chưa capture.

### PHASE 5 — Framework Impact Assessment
**File:** AP-Core-Framework-Impact.md (chỉ tạo nếu có findings)
**Scope:** Discoveries that challenge/extend Core BSA. Proposed modifications.
**Output:** Update Core-Body-Architecture / Core-Therapy-Architecture nếu evidence đủ mạnh.
Bidirectional links: update existing BSA files → Atlas.

---

## 10. Child Plan Protocol

Workflow cho mỗi kinh lạc / section mới.
Tương tự phương pháp Therapy-Methods: survey → plan → execute → review.

### Step 1: Data Survey (1 session, trước compact)
- Đọc master plan (file này) + AP-00-Core.md
- Đọc BSA files liên quan cho kinh này (A09, C04, B01, etc.)
- Web search sơ lược: tình trạng evidence tổng thể cho kinh
- List tất cả huyệt, ghi note nhanh:
  - Evidence tier sơ bộ (A/B/C) cho từng huyệt
  - Nguồn data chính available
  - Cross-tradition overlap sơ bộ
  - Đặc biệt / complications

### Step 2: Write Child Plan (folder/plan.md)
Child plan bao gồm:
- Danh sách huyệt + tier assignment (A/B/C)
- Nhóm huyệt batch together (vd: Back-Shu as group)
- Ước tính session count cho kinh này
- Specific sources cần tìm
- Quyết định chia file (vd: BL cần 2-3 file?)
- Special considerations

### Step 3: Compact → Execute
- Compact session
- Load child plan + master plan template
- Triển khai từng batch theo child plan
- Mỗi session kết thúc: update child plan status

### Step 4: Review + Finalize
- Khi hoàn tất toàn bộ kinh: review consistency across entries
- Collect ⚡ Framework notes
- Update master plan status table (§11)
- Note observations cho Phase 3-5

---

## 11. Status Tracking

| Phase | Status | Notes |
|---|---|---|
| 0 - Core Methodology | NOT STARTED | |
| 1 - Tier 1 Points | NOT STARTED | ~15-20 huyệt |
| 2 - Systematic | NOT STARTED | |
| — AP-01 Lung LU | — | 11 huyệt |
| — AP-02 Large Intestine LI | — | 20 huyệt |
| — AP-03 Stomach ST | — | 45 huyệt |
| — AP-04 Spleen SP | — | 21 huyệt |
| — AP-05 Heart HT | — | 9 huyệt |
| — AP-06 Small Intestine SI | — | 19 huyệt |
| — AP-07 Bladder BL | — | 67 huyệt |
| — AP-08 Kidney KI | — | 27 huyệt |
| — AP-09 Pericardium PC | — | 9 huyệt |
| — AP-10 Triple Burner TE | — | 23 huyệt |
| — AP-11 Gallbladder GB | — | 44 huyệt |
| — AP-12 Liver LR | — | 14 huyệt |
| — AP-13 Governing GV | — | 28 huyệt |
| — AP-14 Conception CV | — | 24 huyệt |
| — AP-15 Extra Points | — | 48+ huyệt |
| — AP-16 Auricular | — | microsystem |
| — AP-17 Scalp | — | microsystem |
| — AP-18 Other Microsystems | — | microsystem |
| 3 - Cross-Tradition | NOT STARTED | |
| 4 - Mechanism | NOT STARTED | |
| 5 - Framework Impact | NOT STARTED | |
