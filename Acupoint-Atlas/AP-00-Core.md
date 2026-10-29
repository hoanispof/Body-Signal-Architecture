---
title: Acupoint-Atlas Core Methodology
id: AP-00
version: 1.0
status: COMPLETE
scope: Data collection, evaluation, and synthesis methodology for the Acupoint Atlas. Operational reference for all phases.
dependencies: [plan.md, A09, C04, Core-Body-Architecture, Core-Therapy-Architecture]
confidence: 🟢 Research support | 🟡 Synthesis | 🔴 Hypothesis
date: 2026-08-06
---

# AP-00 — Acupoint-Atlas Core Methodology

> **What this file is:** The operational methodology guide for the entire
> Acupoint Atlas project. Establishes HOW to collect, evaluate, and
> synthesize per-point data across 450+ acupoints.
>
> **What this file is NOT:** Not the project plan (→ plan.md), not the
> template itself (→ plan.md §3), not individual point entries.
>
> **When to read this:** Before starting any child plan or entry session.
> This file + plan.md §3 (template) = everything needed to begin work.

---

## Table of Contents

- §1 — Epistemological Framework
- §2 — Data Collection Methodology
- §3 — Evidence Evaluation Standards
- §4 — Cross-Tradition Mapping Protocol
- §5 — Depth Tiering Decision Rules
- §6 — Quality Checklist
- §7 — Framework Integration Rules
- §8 — Source Hierarchy and Citation Standards
- §9 — Microsystem-Specific Methods
- §10 — Cross-References

---

## §1 — EPISTEMOLOGICAL FRAMEWORK

### §1.1 The Core Distinction: Data vs Mechanism

The Acupoint Atlas operates on the same epistemological principle as the
entire BSA framework (A09 §0, Design Principle #4):

```
TRADITIONAL CLINICAL OBSERVATIONS = DATA
  "ST36 treats stomach disorders" = clinical data point accumulated
  over 2000+ years, from millions of cases.
  → RECORD as observation. VALUE as data.

TRADITIONAL EXPLANATIONS = NOT MECHANISM
  "Because Qi flows through the Stomach meridian" = explanatory
  framework, not validated mechanism.
  → RECORD as tradition. Do NOT endorse as mechanism.

MODERN MECHANISM = TRACK A ATTRIBUTION
  "PROKR2+ neurons at ST36 → vagal-adrenal pathway → gastric
  motility via NTS/DMVN brainstem relay" (Liu 2021 Nature)
  → ATTRIBUTE to specific Track A systems with evidence.
```

This distinction is NOT dismissive of traditional knowledge. Traditional
observations identified clinically significant anatomical sites with
remarkable accuracy — 93.3% overlap with independently discovered trigger
points (Dorsher 2008), 80% at fascial convergence planes (Langevin 2002),
neurogenic inflammatory spots at predicted acupoint locations (Kim 2017).
The observations are validated; the explanatory framework requires revision.

**Practical rule:** Every Atlas entry separates "Chỉ định truyền thống"
(traditional indications — what was observed) from "Cơ chế giải thích"
(mechanism — why it works, attributed to Track A systems). Never merge
them. Never dismiss observations because mechanism is unknown. Never
accept traditional explanations as mechanism.

### §1.2 Acupoints as Multi-System Convergence Zones

The Atlas operates within BSA's established model (A09 §2.2,
Core-Body-Architecture §3.5):

Acupoints are NOT single-structure anatomical entities. They are
multi-system convergence zones where 4-6 body systems physically overlap:

- Neural: rich nerve endings (A01), PROKR2+ neurons (A02)
- Fascial: intermuscular connective tissue planes (A03)
- Vascular: arterioles, venules, elevated NO (A04)
- Immune: higher mast cell density (A05)
- Chemical: enriched local milieu — opioid, endocannabinoid,
  adenosine, 5-HT receptors (A06)

This convergence explains why needling these sites produces stronger
effects than needling random tissue — more systems activated simultaneously.

**Dynamic nature:** Acupoints are not fixed landmarks but emergent
physiological phenomena. Neurogenic inflammatory spots appear with organ
disease and resolve with treatment (Kim 2017). Standardized maps are
approximations of average convergence locations. 🟡

### §1.3 The Fundamental Asymmetry

A09 §3.1 established: evidence for POINTS is strong; evidence for
PATHWAYS (meridian channels) between them is significantly weaker.

```
Points (acupoints)    🟢 Strong evidence
  80% at fascial planes, 93% trigger point overlap,
  PROKR2 molecular basis, neurogenic spots

Pathways (meridians)  🟡 Weak evidence
  ~50% fascial correspondence, PVS unconfirmed,
  radiotracer = venous drainage (Simon 1988),
  PSC explainable by known mechanisms
```

**Atlas implication:** We catalog POINTS comprehensively. We note which
meridian each point traditionally belongs to (organizational structure),
but we do NOT assume the connecting pathway carries therapeutic significance.
Point category membership (Five Shu, Yuan-Source, etc.) is recorded as
DATA from the traditional classification system.

---

## §2 — DATA COLLECTION METHODOLOGY

### §2.1 Per-Point Research Workflow

For each acupoint, data collection follows this sequence:

```
STEP 1: LOCATION AND ANATOMY
  Primary: WHO Standard Acupuncture Point Locations (WPRO 2008)
  Secondary: Deadman Manual of Acupuncture
  Anatomy: specific nerve branch, fascial plane, vascular supply,
           muscle layers, spinal segment
  → Sources: anatomy textbooks, cadaver studies

STEP 2: POINT CATEGORY MEMBERSHIP
  Check ALL 8 categories (B01 §3.1):
    Five Shu, Yuan-Source, Luo-Connecting, Xi-Cleft,
    Back-Shu, Front-Mu, Eight Confluent, Hui-Meeting
  + Special designations:
    Command Points, Ma Dan-yang Stars, Sun Si-miao Ghost Points,
    Lower He-Sea Points
  One point may belong to MULTIPLE categories — check all.
  → Sources: Neijing, Nanjing, Deadman, WHO 2008

STEP 3: TRADITIONAL INDICATIONS
  Record from classical sources with SPECIFIC citations:
    Neijing, Zhenjiu Jiayi Jing, Nanjing, Zhenjiu Dacheng
  + Modern textbook synthesis (Deadman, WHO)
  Note consistent patterns across sources.
  → Record AS DATA, do not evaluate for mechanism.

STEP 4: CROSS-TRADITION MAPPING
  Check all 8 traditions per §4 protocol.
  Record convergence score (n/8).
  → See §4 for detailed protocol.

STEP 5: MODERN EVIDENCE
  Search for systematic reviews/meta-analyses mentioning this point.
  Record RCT data if available.
  Assign confidence tier per indication (§3).
  Note sham comparison results.
  → Web search for Tier A points. Batch search for Tier B.
    No individual search for Tier C.

STEP 6: MECHANISM ATTRIBUTION
  Which Track A systems are activated at this specific location?
  WHY does this location produce these effects?
  What is the GAP between observation and mechanism?
  → Cross-reference: A01-A09, C04 evidence hierarchy

STEP 7: TECHNIQUE-SPECIFIC DATA
  Needle depth, De Qi characteristics (B01)
  EA frequency mapping (B01): 2Hz → enkephalin, 100Hz → dynorphin
  Pressure parameters (B02), PROKR2 depth question
  Moxa method (B08), thermal parameters
  Dry needling technique (B11), local twitch response
  → Sources: B01, B02, B08, B11 clinical data

STEP 8: SAFETY
  Pneumothorax risk (chest/back points)
  Vascular proximity
  Pregnancy contraindications (LI4, SP6, BL67, sacral)
  Special restrictions (CV8 = moxa-only)
  → Sources: WHO safety guidelines, Deadman, clinical literature
```

### §2.2 Batch Processing Rules

Not every point gets the same research depth. Depth tiering (§5)
determines effort allocation:

```
TIER A (Deep Analysis, ~20-30 points):
  Full 8-step workflow per point. Individual web search.
  Discussion section if findings are significant.
  Time: ~1 point per 15-20 minutes of focused work.

TIER B (Standard Entry, ~80-120 points):
  Full 8-step workflow but each field more concise.
  Web search in batches (group related points).
  Time: ~3-5 points per session batch.

TIER C (Minimum Viable Entry, ~250-300 points):
  Steps 1-4 + 8 only (location, category, tradition, cross-tradition, safety).
  Modern evidence = "No systematic modern study" if true.
  No individual web search.
  Time: ~10-15 points per session batch.
```

### §2.3 Session Structure

Each working session follows this pattern:

1. **Load context:** Read AP-00-Core.md + relevant child plan
2. **Set batch:** Identify which points to cover this session
3. **Execute:** Follow per-point workflow at appropriate tier depth
4. **Review:** Check consistency within batch
5. **Update status:** Mark progress in child plan

---

## §3 — EVIDENCE EVALUATION STANDARDS

### §3.1 Confidence Tier Assignment

Confidence tiers are assigned PER INDICATION, not per point.
One point may have 🟢 for indication A and 🔴 for indication B.

```
🟢 CONFIRMED
  Criteria: modern evidence CONFIRMS the indication.
  Required: ≥1 systematic review/meta-analysis with positive conclusion
            + identified mechanism from Track A
  Example: PC6 for PONV — Cochrane review positive, vagal mechanism
           via median nerve → brainstem NTS identified

🟡 PLAUSIBLE
  Criteria: partial evidence supports the indication.
  Any of:
    - RCT data positive but no SR/MA
    - SR/MA exists but inconclusive or low quality
    - Mechanism plausible from Track A but not confirmed for
      this specific indication
    - Strong consistent clinical tradition + plausible pathway
  Example: LI4 for headache — some RCT support, mechanism via
           trigeminal-cervical complex plausible but not specific

🔴 UNVALIDATED
  Criteria: no modern evidence, or evidence contradicts.
  Any of:
    - Traditional indication only, no modern study
    - Modern studies negative or contradictory
    - Mechanism unknown or implausible from Track A
  Example: Traditional indication "brightens the eyes" for
           a lower limb point with no optic/visual pathway
```

### §3.2 Evidence Assessment Rules

1. **Systematic reviews outrank individual RCTs.** When both exist,
   prioritize SR/MA conclusions.

2. **Sham comparison is critical.** Record whether real acupuncture at
   this point outperforms sham at the same point. If sham ≈ verum,
   note this — it suggests the effect is location-independent
   (non-specific mechanism).

3. **Sample size matters.** Single small RCTs (n<30) are noted but do
   not upgrade confidence from 🔴 to 🟡 alone.

4. **Negative evidence is valuable.** If a well-designed study shows
   NO effect for a traditional indication, record this clearly.
   Negative findings are not failures — they are data.

5. **Birch 2025 as overview source.** 862 systematic reviews across
   184 conditions — use as starting index for which conditions have
   been studied, then find specific point-level data within.

6. **Network meta-analyses** (2024-2025 generation): these compare
   multiple interventions and can show relative effectiveness. Cite
   when they provide point-specific or condition-specific data.

### §3.3 Handling the Sham Paradox

C02 and A09 established the 3-layer sham resolution:

```
Layer 1: Verum > no treatment          → 🟢 Acupuncture works
Layer 2: Verum ≈ sham at same point    → Location precision modest
Layer 3: Verum > sham at non-indicated → 🟢 Location matters somewhat

Resolution: effects are REAL but arise from MULTIPLE simultaneous
mechanisms — some location-dependent (PROKR2, segmental convergence),
some location-independent (gate control, relaxation, Evaluative Gates).
```

When recording evidence, always note which sham comparison was used.
"Sham at same point" ≈ verum does NOT mean the therapy doesn't work —
it means the specific point's contribution is modest relative to the
total therapeutic package.

---

## §4 — CROSS-TRADITION MAPPING PROTOCOL

### §4.1 The 8 Traditions

For every point, check correspondence with all 8 traditions/systems
(plan.md §6):

```
# | TRADITION                    | HOW TO CHECK
──┼──────────────────────────────┼──────────────────────────────────
1 | TCM Acupoint                 | = the point itself. Record code +
  |                              | traditional function.
2 | Western Trigger Point        | Dorsher 2006-2022 mapping.
  |                              | Which muscle? Referred pain pattern?
3 | Ashi Point                   | Palpation-based. Is this a common
  |                              | tender point in clinical practice?
4 | Marma Point (Ayurvedic)      | Frawley 107-point system. Check
  |                              | if anatomically corresponding
  |                              | Marma exists within 2-3 cm.
5 | Head Zone                    | Beissner 2011 mapping. Which
  |                              | dermatome-viscerotome? Maximum
  |                              | point correspondence?
6 | Anatomy Trains               | Myers/Dorsher 2009. Which
  |                              | myofascial line passes through?
7 | Neurogenic Inflammatory Spot | Kim 2017 overlap. Would this point
  |                              | be predicted by the neurogenic
  |                              | inflammation model?
8 | Cupping Point                | TCM cupping or Sunnah location?
  |                              | Primarily relevant for Back-Shu
  |                              | and paravertebral points.
```

### §4.2 Convergence Score

After checking all 8 traditions, assign a convergence score:

```
Convergence score = n/8 (how many traditions identify this location
                        as clinically significant)

≥5/8 = VERY HIGH convergence — strong anatomical significance signal
3-4/8 = HIGH convergence — likely genuine multi-system zone
2/8   = MODERATE — typical for most points
1/8   = LOW — TCM only (most Tier C points)
0/8   = N/A — should not occur (TCM itself = 1)
```

Minimum score is 1/8 (the TCM tradition itself).

### §4.3 Recording Rules

- **Match found:** Record the correspondence with specific reference.
- **No match found after checking:** Record "No correspondence found"
  (explicitly confirming the check was done).
- **Not applicable:** Some traditions only apply to certain body regions.
  Cupping points are primarily back/shoulder. Do not force a mapping
  where the tradition has no coverage for that region.
- **Uncertain match:** Record as "Possible correspondence" with distance
  estimate (e.g., "Marma Kshipra — approximately 2 cm lateral").

---

## §5 — DEPTH TIERING DECISION RULES

### §5.1 Tier Assignment Criteria

Tier assignment happens during child plan creation (plan.md §10 Step 2),
based on the data survey. Decision rules:

```
ASSIGN TIER A IF ANY OF:
  □ ≥1 systematic review exists specifically studying this point
  □ Molecular mechanism evidence exists (PROKR2, specific pathway)
  □ Cross-tradition convergence ≥4/8
  □ Point is in the "most-studied" lists (B01, B02 three-tier rankings)
  □ BL67-class paradox: strong clinical evidence + unknown mechanism

ASSIGN TIER B IF ANY OF:
  □ RCT data exists (even if no SR/MA)
  □ Strong clinical tradition + plausible Track A pathway
  □ Cross-tradition convergence ≥2/8
  □ Point belongs to multiple categories (Five Shu + Yuan + ...)
  □ Special designation (Ma Dan-yang Star, Ghost Point, etc.)

ASSIGN TIER C IF:
  □ None of the above criteria met
  □ Standard WHO 2008 point with limited/no modern evidence
  □ Single-category membership
  □ Traditional indications only
```

### §5.2 Tier Mobility

Tiers are NOT fixed labels. During execution:

- **Upgrade:** If a Tier C point reveals unexpected data during
  research → upgrade to Tier B or A. Document the reason.
- **Downgrade:** If a Tier B point has less evidence than expected →
  treat as Tier C. Document the reason.
- **Flag in child plan:** Any tier change is noted in the child plan
  with rationale.

---

## §6 — QUALITY CHECKLIST

### §6.1 Per-Entry Verification

Before marking any entry as complete, verify:

```
LOCATION & ANATOMY:
  □ WHO 2008 location cited
  □ Specific nerve branch identified (not just "sciatic nerve")
  □ Spinal segment noted
  □ Depth in cm (not cun)
  □ Fascial plane identified

POINT CATEGORY:
  □ All 8 categories checked (Five Shu, Yuan, Luo, Xi-Cleft,
    Back-Shu, Front-Mu, Eight Confluent, Hui-Meeting)
  □ Special designations checked
  □ Multi-category membership correctly recorded

CROSS-TRADITION:
  □ All 8 traditions checked
  □ Convergence score calculated
  □ "No correspondence found" explicitly noted where applicable

EVIDENCE:
  □ Confidence tier assigned PER INDICATION (not per point)
  □ Sham comparison noted where available
  □ Negative evidence recorded (not omitted)

MECHANISM:
  □ Track A systems attributed with specific section references
  □ Gap identified: what tradition says vs what mechanism explains
  □ ⚡ Framework note flagged if findings extend/challenge BSA

CONSISTENCY:
  □ Same formatting as other entries in same file
  □ Cross-references use format: [FileCode] [Section]
  □ "No data" vs field omitted correctly applied
  □ No abbreviations of framework concepts
```

### §6.2 Per-Meridian Verification

After completing all points in a meridian file:

```
  □ All points in WHO 2008 standard accounted for
  □ Point ordering follows standard sequence (proximal → distal
    or as traditionally numbered)
  □ Tier assignments reviewed — any upgrades/downgrades documented
  □ Cross-references between points in same meridian consistent
  □ ⚡ Framework notes collected for Phase 5
  □ Child plan status updated
  □ Master plan status table (§11) updated
```

---

## §7 — FRAMEWORK INTEGRATION RULES

### §7.1 When to Create a Framework Note

Flag ⚡ Framework note when Atlas data:

1. **Extends** existing BSA analysis — adds new evidence or dimension
   not covered in the Track A/B/C files.
   Example: "⚡ Framework note: ST36 dose-response data (Chen 2019)
   extends Core-Therapy-Architecture §6.3 gap on per-point dose-response."

2. **Challenges** existing BSA analysis — data contradicts or qualifies
   a claim made in the framework.
   Example: "⚡ Framework note: BL67 breech efficacy at S1 challenges
   A09 §3.2 claim that segmental convergence explains ~60-70% of
   acupoint-organ effects — S1 has NO uterine connection."

3. **Reveals patterns** not visible at the system level — patterns
   that only emerge when looking at per-point data across the Atlas.
   Example: "⚡ Framework note: Xi-Cleft points consistently show
   higher convergence scores than surrounding points on the same
   meridian — pattern not captured in A09."

### §7.2 What NOT to Flag

Do NOT flag when:
- Data simply confirms what BSA already states
- The observation is about a single point without broader implications
- The "extension" is trivially obvious from existing framework

### §7.3 Cross-Reference Format

Atlas entry → BSA file:
```
→ Cross-ref: A01 S2.3, B01 S3.1, C04 S3.2.1
```
Format: [FileCode] S[SectionNumber]. Always include section number.

BSA files → Atlas: NOT updated during Phase 2. Batch update deferred
to Phase 5 to avoid disrupting existing corpus during build.

### §7.4 Contradiction Handling

When data contradicts existing framework analysis:

1. Record the contradiction clearly in the Atlas entry
2. Flag with ⚡ Framework note
3. Do NOT modify the BSA framework files
4. Accumulate evidence — a single contradicting data point is
   interesting; a pattern across multiple points is actionable
5. Phase 5: formal assessment with all accumulated evidence

---

## §8 — SOURCE HIERARCHY AND CITATION STANDARDS

### §8.1 Source Priority

When sources disagree:

```
PRIORITY (highest → lowest):
  1. Peer-reviewed systematic review / meta-analysis
  2. Peer-reviewed RCT (large, pre-registered)
  3. WHO Standard Acupuncture Point Locations (WPRO 2008)
  4. Peer-reviewed observational/case studies
  5. Modern synthesis textbooks (Deadman)
  6. Classical primary sources (Neijing, Jiayi Jing, Nanjing, Dacheng)
  7. Clinical tradition consensus

For LOCATION specifically:
  WHO 2008 > Deadman > classical sources
  (WHO 2008 standardized modern locations; some differ from classical)

For TRADITIONAL INDICATIONS:
  Classical sources > modern textbooks
  (classical sources ARE the tradition; textbooks interpret)

For MECHANISM:
  Peer-reviewed research > framework synthesis > textbook claims
```

### §8.2 Citation Format

Within Atlas entries, citations are inline and brief:

```
Point-level clinical data:
  (Author Year, Journal/Source — key finding)
  Example: (Vickers 2018, JAMA — NNT≈4 for chronic pain)

Cross-reference to BSA:
  → Cross-ref: FileCode SectionNumber
  Example: → Cross-ref: A02 S3.5, B01 S3.1

Classical source:
  (Source Name, chapter/section if known)
  Example: (Neijing Lingshu Ch.1 — Ben Shu)
```

Full bibliographic details are in plan.md §8. Individual entries
reference these sources by author-year, not full citation.

### §8.3 Web Search Protocol

```
TIER A POINTS: individual web search per point.
  Search terms: "[point code] systematic review" + "[point code]
  mechanism" + "[point code] clinical trial"
  Example: "ST36 systematic review" "ST36 PROKR2" "ST36 RCT"

TIER B POINTS: batch web search by group.
  Search terms: "[meridian] acupuncture points evidence" +
  specific searches for points with known special status
  Example: "Lung meridian acupoints evidence" "LU7 systematic review"

TIER C POINTS: no individual web search.
  Data from WHO 2008 + Deadman + classical sources + cross-tradition
  mapping from existing BSA data.
```

---

## §9 — MICROSYSTEM-SPECIFIC METHODS

### §9.1 Why Microsystems Need Different Methods

Microsystems (AP-16 Auricular, AP-17 Scalp, AP-18 Other) have
fundamentally different anatomical logic than meridian-based acupoints:

- **No meridian organization** — points organized by somatotopic
  projection, not by channel/organ pairing
- **Independent neural pathways** — auricular via ABVN (vagal),
  scalp via cortical projection areas, hand via peripheral nerves
- **Different template** — plan.md §3.2 provides microsystem template
- **Multiple competing systems** — auricular alone has Nogier,
  NADA, BFA, WHO standards

### §9.2 Microsystem Data Collection Adjustments

```
AURICULAR (AP-16):
  Somatotopic model: record position in Nogier inverted fetus model
  Neural pathway: ABVN concha innervation map is PRIMARY data
  Evidence: taVNS literature as primary modern evidence source
  Cross-system: check Nogier, NADA 5-point, BFA, WHO standard
  Key question: which ear zones have ABVN innervation (vagal access)
  vs which do not (non-vagal, trigeminal or cervical plexus)?
  → Cross-ref: A02 S3.5, B01 S3.3, C04 S3.5.2

SCALP (AP-17):
  Multiple systems: Jiao Shunfa, YNSA (Yamamoto), Zhu, WHO 14 lines
  No single standard — record points in each system separately
  Neural basis: cortical projection mapping
  Evidence: stroke rehabilitation is best-studied application
  → Cross-ref: B01 S3.3

OTHER MICROSYSTEMS (AP-18):
  Korean Hand Therapy: 345 points on hand
  Foot microsystem: if sufficient data (separate from B06 reflexology
    zone claims — foot microsystem in TCM is acupoint-based,
    not zone-based)
  → Record available data, note evidence limitations
```

---

## §10 — CROSS-REFERENCES

### §10.1 BSA Files Referenced in This Methodology

| File | Content Used |
|---|---|
| A09 Meridian Examination | Convergence zone model (§2.2), fundamental asymmetry (§3.1), 7 candidate substrates, evidence scorecard |
| C04 Location Specificity | Evidence hierarchy (§3.4), validated vs unvalidated systems, body region pathway hierarchy, dynamic acupoint phenomenon |
| Core-Body-Architecture | 9 systems network (§1, §3.5), multi-system convergence at acupoints |
| Core-Therapy-Architecture | Dual-axis mechanism framework, 51 mechanisms, per-point dose-response gap |
| B01 Acupuncture | 8 point category systems (§3.1), point selection logic, microsystems |
| B02 Acupressure | PROKR2 depth question, most-studied points ranking |
| B08 Moxibustion | Heat-sensitive moxibustion, BL67 breech paradox |
| B11 Dry Needling | 93.3% trigger point-acupoint correspondence, three targeting models |

### §10.2 Key Evidence Cited

| Citation | Finding | Relevance |
|---|---|---|
| Liu et al. 2021 (Nature) | PROKR2 molecular basis at ST36 | Strongest evidence for point specificity |
| Dorsher 2008 (Journal of Pain) | 93.3% trigger point-acupoint overlap | Independent convergence validation |
| Langevin & Yandow 2002 | 80% acupoints at fascial planes | Structural basis for point locations |
| Kim et al. 2017 (Scientific Reports) | Neurogenic inflammatory spots at acupoints | Dynamic acupoint phenomenon |
| Beissner & Henke 2011 | Head zones = Mu/Shu acupoints | Cross-tradition convergence |
| Maurer et al. 2019 | VNBs at only 2% of acupoints | Corrects Heine's 80% claim |
| Vickers et al. 2012-2018 (JAMA/J Pain) | Verum > sham > no treatment | Sham paradox data |
| Birch 2025 | 862 SRs across 184 conditions | Evidence landscape overview |
| WHO WPRO 2008 | Standard point locations | Location reference standard |

### §10.3 Forward References

- **Phase 1 (Tier 1 Points):** Will test and refine this methodology
  against the 15-20 highest-evidence points.
- **Phase 2 (Systematic):** Each child plan references this file for
  methodology standards.
- **Phase 5 (Framework Impact):** All ⚡ Framework notes accumulated
  across Phases 1-4 are assessed here.

---

## Closing Note

This methodology prioritizes honesty over completeness. "No data"
for a field is more valuable than speculative fill. Gaps are research
opportunities, not failures. The BL67 breech paradox — strongest
clinical evidence, no known mechanism — is the most important
unsolved question in acupuncture science. A framework that hides
gaps is less useful than one that maps them clearly.

Data is the highest arbiter. If per-point analysis reveals patterns
that change the core framework, the core framework must update.
Framework serves data, not the other way around.
