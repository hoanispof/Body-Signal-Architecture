---
title: Location-Specificity-Map
id: C04
version: 0.1
status: DRAFT
scope: Does WHERE matter? When does the location of stimulus application determine therapeutic outcome? Validated vs unvalidated location systems, body region pathway hierarchy.
sources: [A07, A09, A01-A06, A08, B01-B16, C01, C03]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# Location-Specificity-Map

## §1 — PURPOSE & METHODOLOGY

### §1.1 — Why This Cross-Reference Exists

C01 established WHAT stimulus types activate WHICH body system pathways. C03 identified WHICH mechanisms are shared and unique. But both analyses treat location as a parameter modifier (C01 §3.2.5), not as a primary analytical dimension. Yet location is arguably the most clinically consequential variable in body-based therapy: practitioners spend years learning WHERE to apply their technique, and many therapeutic traditions are fundamentally organized around location systems (acupoint maps, dermatome charts, reflexology zones, trigger point atlases).

**This cross-reference answers the central location question no individual Track B file can:**

When does the LOCATION of stimulus application determine the therapeutic outcome — and when doesn't it?

Three subsidiary questions follow:

1. **Which location systems are neuroanatomically validated?** Acupoints have PROKR2 molecular basis (Liu 2021); Ingham foot zones have NO neuroanatomical basis (B06 §3.3). Where does each system fall on the evidence hierarchy?

2. **Do different body regions provide different pathway access?** Face (CN V → brainstem) vs ear (ABVN → vagal) vs foot (L4-S3 spinal) — does REGION predict therapeutic potential independently of stimulus type?

3. **What is the relationship between claimed precision and validated precision?** Some therapies claim detailed organ zones (B06) while lacking any validation; others claim no point specificity (B03) while using well-validated regional anatomy. Is there a pattern?

### §1.2 — Data Sources

- **Location systems:** A07 (Dermatome-Somatotopic Map — segmental convergence, Head zones, Kim 2017 neurogenic spots), A09 (Meridian Examination — 7 candidate substrates, composite substrate assessment)
- **Application points/areas:** All 15 Track B §3 sections, read in full
- **Stimulus context:** C01 (Stimulus-Pathway-Matrix — body region parameter modifier §3.2.5, CT afferent pattern §4.7)
- **Scaffolding context:** C03 (Common-Mechanisms — scaffolding analysis §3.4, specificity spectrum §3.5)
- **System definitions:** Track A files A01-A06, A08

### §1.3 — Methodology

**Location classification.** Each of the 15 therapies was classified on a Location Specificity Spectrum based on: (a) whether the therapy CLAIMS location matters, (b) the EVIDENCE level for that claim, and (c) the MECHANISM by which location might matter.

**Evidence hierarchy construction.** Location-specificity evidence was ranked by: molecular/causal evidence > anatomical correlation > clinical trials > traditional mapping > no evidence.

**Body region comparison.** Each major body region was assessed for: neural pathway access (which cranial/spinal nerves), available receptor types (CT afferents present/absent), segmental convergence (which organs accessible), and unique anatomical features (e.g., ABVN at ear concha).

**Validated vs unvalidated classification.** Location systems were classified as VALIDATED (mechanism identified at 🟢 confidence), PARTIALLY VALIDATED (some mechanisms at 🟡), or UNVALIDATED (no mechanism confirmed, 🔴). Connection to C03 scaffolding analysis: unvalidated maps may serve as therapeutic scaffolding with VALUE but without VALIDITY.

---

## §2 — TAXONOMY / CLASSIFICATION

### §2.1 — Three Levels of Location Specificity

Therapies differ fundamentally in HOW MUCH location matters for their mechanism of action. Three levels emerge from Track B data:

```
LEVEL               DEFINITION                              THERAPIES
──────────────────── ─────────────────────────────────────── ──────────────────────
POINT-SPECIFIC       Exact anatomical point matters for      B01 (acupoints),
                     mechanism. Shifting 1-3 cm changes      B02 (acupoints via
                     WHICH neural pathway is activated.       pressure), B08 (moxa
                     Validated by molecular/segmental          at acupoints), B11
                     evidence.                                (trigger points)

REGION-SPECIFIC      Body REGION matters (back vs face vs    B03 (massage regions),
                     limb) but precise point within region   B04 (fascial areas),
                     is less critical. Mechanism operates    B07 (cupping areas),
                     on tissue characteristics of the area,  B09 (gua sha areas),
                     not specific neural convergence sites.  B10 (spinal segments),
                                                             B13 (whole-body tsubos)

LOCATION-            Therapy works through whole-body        B15 (Tai Chi/Qigong),
INDEPENDENT          engagement. No specific application      B16 (Yoga)
                     points. Location matters for LOADING
                     (which joints/muscles bear force)
                     but NOT for therapeutic targeting.
```

### §2.2 — The Claimed-vs-Validated Distinction

A critical distinction cuts across all three levels: some therapies CLAIM high location specificity but lack evidence for it. Others CLAIM low specificity while using well-validated regional anatomy.

```
                          CLAIMED SPECIFICITY
                    HIGH                         LOW
                 ┌───────────────────────────┬─────────────────────────┐
          HIGH   │ B01: 361 acupoints        │ B03: area-based but     │
VALIDATED        │   PROKR2 🟢, Back-Shu     │   dermatome mapping 🟢, │
SPECIFICITY      │   1-in-5-billion match     │   CT afferent zones 🟢  │
                 │ B11: trigger points, 93.3% overlap  │ B04: Stecco CC/CF 🟢,  │
                 │   Dorsher 🟢               │   trigger point overlap 🟢        │
                 │ B08: acupoints + TRPV1     │ B10: segmental but      │
                 │   heat-sensitivity 🟡      │   palpation κ=0.02 🔴   │
                 ├───────────────────────────┼─────────────────────────┤
          LOW    │ B06: Ingham zones 🔴      │ B07: area-based, HO-1   │
VALIDATED        │ B12: 9 fixed points 🔴    │   not point-dependent 🟢│
SPECIFICITY      │ B14: CSR points 🔴        │ B09: area-based, fascial│
                 │ B13: Hara zones 🔴        │   shear 🟢               │
                 │                            │ B15/B16: no points,     │
                 │                            │   whole-body 🟢          │
                 └───────────────────────────┴─────────────────────────┘
```

**Key finding from taxonomy:** The upper-left quadrant (high claimed + high validated) contains only therapies using the acupoint/trigger point system or its validated components. The lower-left quadrant (high claimed + low validated) contains therapies whose elaborate location maps serve as therapeutic SCAFFOLDING (C03 §3.4) — enhancing the therapeutic encounter without providing mechanistic specificity. 🟡

---

## §3 — MAIN ANALYSIS

### §3.1 — Location-Dependent vs Location-Independent: The Full Spectrum

All 15 therapies ranked from most to least location-dependent, with evidence for each classification:

```
RANK  THERAPY              LOCATION STATUS          EVIDENCE SUMMARY
────  ───────────────────  ─────────────────────── ────────────────────────────────
 1    B01 Acupuncture      POINT-SPECIFIC 🟢        361 codified points. PROKR2
      (EA)                  (strongest in Track B)   molecular basis at ST36 (Liu
                                                     2021). Back-Shu match organ
                                                     innervation 9/12 (odds 1 in 5
                                                     billion, Dorsher). 80% at
                                                     fascial planes (Langevin 2002).
                                                     Intensity-dependent pathway
                                                     segregation by location.

 2    B08 Moxibustion      POINT-SPECIFIC 🟢/🟡     Same 361-point system as B01.
                                                     TRPV1/nNOS density higher at
                                                     acupoints (Ma SX). Heat-
                                                     sensitive moxa: differential
                                                     thermal reactivity at different
                                                     points supports specificity.
                                                     BL67 Breech Paradox: strongest
                                                     clinical evidence but S1≠uterus.

 3    B11 Dry Needling     POINT-SPECIFIC 🟢         Trigger point targeting by
                                                     palpation (taut band → trigger point).
                                                     93.3% acupoint overlap (Dorsher
                                                     2008, 1 in 7 trillion odds).
                                                     Three targeting models: trigger point
                                                     (palpation), IMS (paraspinal),
                                                     FSN (fascial, AWAY from lesion).

 4    B02 Acupressure      POINT-SPECIFIC 🟡         Same point system as B01 but
                                                     NOT all points equally suited
                                                     to pressure. Fewer points per
                                                     session (3-6 vs 8-20). PROKR2
                                                     depth question UNRESOLVED
                                                     (surface pressure may not reach
                                                     PROKR2+ neurons in deep fascia).
                                                     ABVN auricular = strongest
                                                     location-specific rationale.

 5    B10 Chiropractic     SEGMENT-SPECIFIC 🟡/🔴    Claims segmental specificity at
                                                     individual vertebral level via
                                                     sclerotome-viscerotome
                                                     convergence (A07 §4.7). BUT:
                                                     palpation reliability POOR
                                                     (κ=0.02-0.42), thrust affects
                                                     adjacent segments (Ross 2004),
                                                     cavitation at non-target (Beffa
                                                     2004). If mechanism is
                                                     neurophysiological → precise
                                                     targeting less critical.

 6    B04 Deep Tissue      STRUCTURE-SPECIFIC 🟢     Targets fascial planes, trigger points,
                                                     areas of restriction by
                                                     palpation. Stecco FM CC/CF
                                                     points = most anatomically
                                                     specific within B04. trigger point overlap
                                                     93.3%. Anatomy Trains lines
                                                     verified but no superiority
                                                     evidence for treating along
                                                     lines vs individual structures.

 7    B13 Shiatsu          PATTERN-SPECIFIC 🟡/🔴    Namikoshi: 660 anatomical tsubos
                                                     (same locations as acupoints,
                                                     Western naming). Masunaga:
                                                     reactive points along extended
                                                     meridians. Hara zones
                                                     UNVALIDATED 🔴. But WHOLE-BODY
                                                     coverage means individual point
                                                     specificity matters less —
                                                     breadth over depth (C03 §4.2).

 8    B03 Massage          REGION-SPECIFIC 🟢         Area-based, NOT point-based.
      General                                        BUT regional specificity IS
                                                     validated: back dermatome→organ
                                                     mapping, abdomen→ENS access,
                                                     ear→vagal, face→trigeminal-
                                                     vagal. CT afferent distribution
                                                     (hairy vs glabrous) determines
                                                     receptor availability.

 9    B07 Cupping          AREA-BASED 🟢              Cups cover 700-5,000 mm² (vs
                                                     needle 0.05 mm²). TCM back-shu
                                                     vs Islamic sunnah = two
                                                     tradition-specific systems that
                                                     DON'T map to each other. HO-1
                                                     mechanism requires capillary bed
                                                     = area-dependent, NOT point-
                                                     dependent. Any region works.

10    B09 Gua Sha          AREA-BASED 🟢              Strokes across regions along
                                                     fascial planes. Location matters
                                                     at REGIONAL level (which body
                                                     area has relevant pathology).
                                                     Stroke DIRECTION along fascial
                                                     planes may optimize shear
                                                     transmission. Facial gua sha =
                                                     categorically different (no sha,
                                                     no HO-1).

11    B06 Reflexology      CLAIMED POINT-SPECIFIC    Detailed Ingham foot map claims
                            but UNVALIDATED 🔴        organ-zone correspondence. ~80%
                                                     of claimed zones have NO
                                                     neuroanatomical basis (L4-S3 ≠
                                                     most organ viscerotomes). Sham
                                                     trials: no zone specificity
                                                     (Descamps 2023 fMRI). Map =
                                                     scaffolding. Actual mechanism =
                                                     general foot massage.

12    B12 EFT Tapping      FIXED POINTS,             9 fixed points tapped every
                            NO SPECIFICITY 🔴         round regardless of condition.
                                                     NO condition-specific point
                                                     selection. 56% facial = CN V
                                                     territory (neuroanatomical
                                                     COVERAGE, not specificity).
                                                     Spielmans 2020: sham tapping ≈
                                                     real tapping (p=0.12 NS).

13    B14 Craniosacral     NO POINT SYSTEM 🔴         Broad diffuse hand contact on
                                                     cranial bones. NO codified
                                                     points. CSR detection
                                                     reliability r=0.004 (Moran &
                                                     Gibbons 2001). Myodural bridge
                                                     at suboccipital (Hack 1995) =
                                                     only anatomically specific
                                                     finding. LIGHTEST touch, LEAST
                                                     specificity, WEAKEST rationale.

14    B15 Tai Chi/Qigong   LOCATION-INDEPENDENT 🟢   NO application points. Whole-
                                                     body engagement. Region matters
                                                     for LOADING (knees, hips) not
                                                     for therapeutic targeting.
                                                     Traditional organ-Qigong claims
                                                     (each sound targets organ) =
                                                     UNVALIDATED, parallel to B06.

15    B16 Yoga             LOCATION-INDEPENDENT 🟢   NO application points. Region-
                                                     dependent by style/pose (forward
                                                     folds→posterior chain, twists→
                                                     spinal, inversions→vascular).
                                                     Yin yoga = most tissue-specific
                                                     (A03 fascia). Chakra/nadi claims
                                                     = UNVALIDATED.
```

🟡 Ranking derived from all 15 Track B §3 sections, cross-referenced with A07 segmental evidence and A09 substrate assessment.

### §3.2 — Validated Location Systems

Six location systems have neuroanatomical evidence supporting the claim that WHERE matters:

#### §3.2.1 — PROKR2 Molecular Specificity (🟢 Strongest)

**What:** PROKR2+ sensory neurons in deep fascia at specific anatomical locations. Ablating these neurons eliminates electroacupuncture effects at ST36 (Liu et al. 2020 Neuron, 2021 Nature).

**Evidence:** PROKR2+ neurons are NON-UNIFORMLY distributed: 16.7% of lumbar DRG vs 6.1% of thoracic DRG neurons. This predicts WHY hindlimb stimulation (ST36) produces vagal-adrenal anti-inflammatory effects that thoracic stimulation does not. Intensity-dependent pathway segregation: low-intensity at ST36 → PROKR2 → vagal anti-inflammatory; high-intensity at ST25 → sympathetic pathway = same needle, different location, different pathway, different effect.

**What it validates:** Specific anatomical POINTS can produce specific systemic effects through identified molecular pathways. This is the strongest evidence that location matters at the point level.

**Limitations:** Demonstrated for ONE pathway (vagal-adrenal via ST36) with electroacupuncture only. Whether other acupoint-specific effects have similarly identified molecular pathways is unknown. Whether surface pressure (B02) reaches deep fascia PROKR2+ neurons is unresolved.

**Therapies benefiting:** B01 (acupuncture, directly), B08 (moxibustion at same points), B11 (dry needling at overlapping sites), B02 (acupressure, IF pressure reaches depth). 🟢 B01 §5.2, A02 §3.5, A09 §1.2.

#### §3.2.2 — Segmental Convergence: Dermatome-Viscerotome (🟢 Strong)

**What:** Each spinal segment innervates a strip of skin (dermatome), muscles (myotome), bones (sclerotome), AND internal organs (viscerotome). All converge at the SAME dorsal horn neurons — specifically Lamina V Wide Dynamic Range (WDR) neurons (A07 §3.2). Stimulating the dermatome therefore activates the same spinal segment that controls the organ = somatovisceral reflex.

**Evidence:**
- Head zones (1893): visceral disease → skin tenderness at specific dermatomes, with "maximum points" at consistent locations — independently discovered 2000+ years after TCM's acupoint mapping (A07 §4.1)
- Beissner & Henke 2011: Head's maximum points ≈ TCM Mu/Shu acupoints. Back-Shu points match organ autonomic innervation at 9/12 spinal levels (Dorsher 2009-2022, odds ~1 in 5 billion) (A07 §4.2)
- Sato et al. 1997: systematic demonstration of somatovisceral reflexes. Different body sites drive DIFFERENT autonomic responses — limb stimulation = supraspinal vagal reflex; abdominal stimulation = segmental sympathetic reflex. Same organ, OPPOSITE effects depending on WHERE (A07 §1.6)

**What it validates:** Location matters because different skin areas connect to different organs via segmental anatomy. This is the oldest and most thoroughly validated location-specificity mechanism.

**Coverage:** Explains ~60-70% of acupoint-organ effects (A07 §4.4). The remaining 30-40% are non-segmental (e.g., ST36 at L4-L5 affecting stomach at T6-T9) — filled by PROKR2/supraspinal pathways (§3.2.1 above).

**Therapies benefiting:** ALL therapies that apply stimulus at specific dermatomes — B01, B02, B03 (back massage → organ modulation via T1-L5), B08, B10 (HVLA at specific vertebral segment → corresponding viscerotome), B11. 🟢 A07 §1.6, §2.2, §4.1-§4.4.

#### §3.2.3 — Neurogenic Inflammatory Spots: Dynamic Acupoints (🟢 Strong)

**What:** Kim et al. 2017 (Scientific Reports): diseased organs cause neurogenic inflammatory spots on the skin at acupoint locations. Evans blue dye injected intravenously leaks through vessels where SP + CGRP cause neurogenic inflammation. Hypertensive rats → spots at C8-T2 (cardiac dermatome), 67% matching acupoint locations. Colitis rats → spots at T10-L1 (large intestine dermatome).

**What it validates:** Acupoints are NOT arbitrary fixed anatomical landmarks — they are EMERGENT physiological phenomena that APPEAR when the corresponding organ is diseased. The body itself creates acupoints via antidromic C fiber activation → SP/CGRP release → neurogenic inflammation at dermatome-viscerotome convergence sites.

**Implications for location specificity:**
1. Point locations shift with disease state — standardized acupoint maps are APPROXIMATIONS
2. "Sham" acupuncture sometimes works because it may hit an active neurogenic spot off the standard map
3. Palpation-based point finding (Ashi, trigger point) may be more precise than chart-based point finding
4. Electrical detection of acupoints (lower skin resistance) is explained by neurogenic inflammation (SP + CGRP → vascular leakage → tissue water → lower resistance), NOT by a dedicated bioelectrical system (A09 §1.7, Kim 2018)

**Therapies benefiting:** Any therapy using palpation-based point location: B01 (Ashi points), B02, B04 (trigger point palpation), B11 (trigger point palpation). Less relevant for fixed-protocol therapies: B12 (same 9 points every time), B06 (same zone map). 🟢 A07 §4.3.

#### §3.2.4 — Trigger Point Correspondence (🟢 Strong)

**What:** Trigger points — hyperirritable spots in taut muscle bands — correspond to acupuncture points at 93.3% (Dorsher 2008: 238/255 most common trigger points have anatomically corresponding acupoints, probability of chance overlap ~1 in 7 trillion). 94% share pain indications. 91% of referred-pain patterns follow meridian distributions.

**Evidence chain:**
- Melzack 1977: 71% correspondence (smaller sample, foundational)
- Birch 2003: critical reanalysis argues 18-40% when correcting for Ashi points vs classical acupoints
- Dorsher 2006-2009: definitive expansion (255 trigger points vs 361 acupoints), comprehensive anatomical + clinical mapping
- A08 §3.3: Simons Integrated Hypothesis — trigger points at motor endplates (NMJ), Shah biochemistry (pH 4.7, SP, CGRP)

**What it validates:** Two independent discovery traditions — Chinese acupoint mapping (~2000+ years) and Western trigger point mapping (Travell & Simons, ~1942) — independently identified the same anatomical locations as clinically significant. Different conceptual frameworks (qi stagnation vs NMJ dysfunction), same physical sites. "The distinction is THEORY and APPROACH, not ANATOMY" (B11 §3.3).

**Therapies benefiting:** B01, B02, B04 (trigger point targeting), B11 (trigger point is the DEFINING target), B13 (tsubos ≈ acupoints ≈ trigger points). 🟢 A08 §4, B11 §3.3, A09 §1.2.

#### §3.2.5 — Fascial Convergence Points (🟢 Moderate-Strong)

**What:** 80% of acupoints are located at intermuscular or intramuscular connective tissue planes (Langevin & Yandow 2002). These are sites where fascial layers converge, creating tissue architecture favorable for mechanotransduction (needle grasp, collagen winding, fibroblast activation).

**Evidence:**
- Langevin & Yandow 2002 (Anatomical Record): 24 acupoints/6 meridians on Visible Human arm — >80% at CT planes (p < 0.001)
- **BUT the 80/50 split:** 80% of POINTS at fascial planes, only ~50% of PATHWAYS (A09 §1.3). Points = real fascial structures; connections between them = less clear
- Anatomy Trains (Myers 2001): 8/9 myofascial meridian lines substantially overlap with TCM meridian distributions (Dorsher 2009). Anatomically verified by cadaver dissection (Wilke 2016). Force transmission documented. BUT no evidence treating along a line is superior to treating individual structures
- Maurer et al. 2019: confirmed fascial correspondence BUT neurovascular bundles at only 2/100 acupoints (2%) — directly contradicting Heine's widely-cited 80% VNB claim

**What it validates:** Acupoints preferentially locate at fascial convergence sites where tissue architecture supports mechanotransduction. This is a STRUCTURAL explanation for point location (why HERE and not 3 cm to the left).

**Limitations:** Fascial planes are continuous structures — the 80% correspondence means acupoints are at fascial sites, but the converse is not true (not all fascial plane intersections are acupoints). Additional factors (nerve density, vascular access, PROKR2 expression) must explain why specific fascial convergence sites become clinically significant points.

**Therapies benefiting:** B01 (needle grasp mechanism), B04 (Stecco FM targets fascial plane intersections independently of TCM), B11 (needle reach to fascial tissue), B09 (stroke along fascial planes). 🟢/🟡 A09 §1.3, A03 §3.2.

#### §3.2.6 — Multi-System Convergence Zones: What "Acupoints" Actually ARE (🟡 Synthesis)

Integrating all evidence from §3.2.1-§3.2.5 above, acupoints are NOT a single anatomical structure but multi-system OVERLAP ZONES where multiple body systems physically converge (A09 §4.1):

```
SYSTEM            EVIDENCE FOR CONVERGENCE AT ACUPOINTS
──────────────── ──────────────────────────────────────────────────────
Neural            Rich nerve endings (A01), PROKR2+ neurons (A02),
                  93% trigger point correspondence (A08)
Fascial           80% at intermuscular CT planes (A03, Langevin 2002)
Vascular          Higher NO at acupoints (A04, Ma 2003/2017),
                  neurovascular access (weakened: only 2% have VNBs)
Immune            Higher mast cell density (A05), neurogenic
                  inflammation at disease-active points (Kim 2017)
Chemical          Local chemical milieu enriched with opioid/endocannabinoid system/
                  adenosine/5-HT receptors (A06)
Electrical        Lower skin resistance (some studies), explained by
                  neurogenic inflammation, NOT dedicated system (A09 §1.7)
```

**Key synthesis:** An acupoint is a site where needling (or pressing, or heating) simultaneously engages neural pathways, fascial mechanotransduction, vascular responses, immune activation, and chemical signaling — because all these systems physically overlap at that site. Needling random tissue engages fewer systems simultaneously because the overlap is less dense. This explains WHY point-specific therapy produces stronger effects than non-specific stimulation without requiring a "meridian channel" as mechanism.

**Dynamic nature:** These convergence zones are not fixed — they emerge and recede with organ pathology (Kim 2017 §3.2.3). Standardized acupoint maps represent AVERAGE locations of multi-system convergence zones; individual anatomy, disease state, and inflammatory status modulate which sites are most active at any given time. 🟡 A09 §2.2, §4.1.

### §3.3 — Unvalidated Location Maps

Six location systems CLAIM point-specific organ correspondences but LACK validated neuroanatomical mechanisms. These are analyzed here for evidence status and relationship to therapeutic scaffolding (C03 §3.4).

#### §3.3.1 — BQC 257 Facial Points (B05 Dien Chan) 🔴

> **B05 RETIRED** — Dien Chan moved to _backup/ (2026-08-03). ~0 RCTs, method expanded beyond face. Facial stimulation mechanisms covered by A02, B01, B02, B03.

#### §3.3.2 — Ingham Foot Zones (B06 Reflexology) 🔴

**System:** Body projected onto the foot sole as if a person is sitting down, folded forward (Ingham 1938). Great toe = brain/head, ball of foot = lungs/chest, arch = stomach/liver/kidneys, heel = pelvis/sciatic, medial edge = spine. 10 longitudinal zones (Fitzgerald 1917).

**Evidence status:** Zone-by-zone neuroanatomical assessment (B06 §3.3): ~80% of claimed organ correspondences have NO neuroanatomical basis. Foot sole is innervated by tibial nerve (L4-S3). L4-S3 dermatomes do NOT connect to most claimed organs (brain, lungs, liver, stomach). Only kidney (borderline L1), bladder (S2 overlap), pelvis (S2-S4), and sciatic nerve area (L4-S3 actual territory) have any segmental basis.

**Clinical evidence AGAINST zone specificity:**
- Ernst 2009 (18 RCTs): "not convincingly effective for any condition"
- Descamps 2023 fMRI (n=30): reflexology = sham massage on brain connectivity
- Hughes 2009: sham reflexology = real reflexology for MS symptoms

**Additional problem:** CT afferents ABSENT from foot sole (glabrous skin) — cannot activate affective touch pathway. Foot sole mechanoreceptors (Merkel, Meissner, Pacinian) serve BALANCE AND LOCOMOTION, not organ sensing (A07 §3.4).

**Assessment:** The Ingham map is a DIAGRAM projected by visual analogy, NOT by tracing neural pathways. Effects of foot reflexology (anxiety reduction, sleep improvement) arise from general foot massage + therapeutic context (gate control, relaxation response, Evaluative Gates). The zone map is SCAFFOLDING — providing protocol structure for systematic foot coverage. 🔴 B06 §3.1-§3.4.

#### §3.3.3 — Hara Zones (B13 Shiatsu) 🔴

**System:** Masunaga Zen Shiatsu maps 12 diagnostic zones on the abdomen, each corresponding to a meridian/organ system. Practitioner palpates for Kyo (depleted) vs Jitsu (excess) quality. Most Kyo zone determines primary treatment meridian.

**Evidence status:** NO reliability studies exist for Hara diagnosis. Inter-rater reliability is UNKNOWN (cf. chiropractic palpation κ=0.02-0.39, CSR detection r=0.004 — similarly structured claims with poor reliability when tested).

**What IS validated:** Abdominal palpation IS used in conventional medicine (hepatomegaly, ascites, peritonitis signs). Visceral referred pain to the abdominal wall IS neuroanatomically supported (A07 Head zones, viscerocutaneous reflexes). BUT Masunaga's specific 12-zone mapping to extended meridians is UNVALIDATED.

**Assessment:** Hara diagnosis may detect real tissue quality changes (visceral referred tenderness) but attributes them to an unvalidated framework. The Namikoshi-Masunaga natural experiment (C03 §4.5) could test this: same physical stimulus, Namikoshi uses Western anatomy WITHOUT Hara, Masunaga uses Hara as the FOUNDATION. If outcomes are equivalent → Hara = scaffolding. No head-to-head data exists. 🔴 B13 §3.2.

#### §3.3.4 — CSR Palpation Points (B14 Craniosacral) 🔴

**System:** Practitioners claim to detect CranioSacral Rhythm (CSR) at cranial bones, sacrum, and spinal contacts. Treatment directed to areas of "restricted" CSR.

**Evidence status:** CSR inter-rater reliability = NEAR ZERO (Moran & Gibbons 2001: r=0.004; Hartman & Norton 2002: ICC 0.02-0.26). Practitioners examining the SAME skull at the SAME time report DIFFERENT rates. Cranial bone mobility: adult suture motion 1-25 μm (Downey 2006) = below human palpation threshold (~200 μm). 5g claimed force NEVER independently measured — likely 50-500g actual.

**What IS validated:** The myodural bridge (Hack et al. 1995): rectus capitis posterior minor → spinal dura at C1-C2 = real anatomical pathway for cranial base release to affect dural tension. BUT this works through MYOFASCIAL mechanism (A08), NOT CSR.

**Assessment:** The diagnostic framework for WHERE to treat (CSR detection) has no reliability. The ONLY anatomically specific finding (myodural bridge at suboccipital region) operates through a completely different mechanism than the one claimed. CST's location system is PURE scaffolding — the most thoroughly contradicted in Track B. 🔴 B14 §3.1-§3.3.

#### §3.3.5 — Islamic Sunnah Cupping Points (B07 context) 🟡

**System:** Traditional cupping points specified in Hadith (Islamic scripture): Al-Akhda'ain (posterior neck, bilateral), Al-Kahil (between shoulders, ~GV14), Yafukh (vertex), plus interscapular, sacral, behind ears.

**Evidence status:** NOT based on meridian theory — independent tradition. Some anatomical overlap with TCM Back-Shu points (Al-Kahil ≈ GV14) but NO systematic mapping between systems. Clinical evidence for hijama mostly from Arabic/Islamic medical literature with different research methodologies.

**Assessment:** Sunnah points represent an INDEPENDENT tradition-specific location system with its own internal logic but no neuroanatomical validation beyond incidental overlap with TCM/segmental anatomy. The existence of TWO unrelated point systems for the SAME therapy (cupping) that DON'T map to each other suggests location specificity is less critical for cupping's area-based HO-1 mechanism. 🟡 B07 §3.2.

#### §3.3.6 — Qigong Organ-Sound Claims (B15) and Yoga Chakra/Nadi Claims (B16) 🔴

**System:** Qigong (Liu Zi Jue): 6 specific sounds each claimed to target a different organ (liver/heart/spleen/lung/kidney/triple heater). Qigong (Wuqinxi): 5 animal mimicry movements each claimed to target a different organ system. Yoga: 7 chakras as energy centers corresponding to endocrine glands/organs along the spine; 72,000 nadis as energy channels.

**Evidence status:** BROAD physiological effects of Tai Chi/Qigong and yoga are well-supported (B15/B16 §4). SPECIFIC organ-targeting claims for individual sounds/movements/chakras lack scientific evidence. These parallel the zone-specificity claims of B06 reflexology.

**Assessment:** Like other unvalidated location maps, the organ-specific claims in movement therapies serve as SCAFFOLDING — providing structure and meaning to practice sessions. The therapeutic effects arise from exercise physiology, breathing, and neuroplasticity (C03 §3.6 Pattern 5), not from organ-specific targeting by specific movements or sounds. 🔴 B15 §3.2, B16 §3.1.

#### §3.3.7 — The Scaffolding-Map Pattern

All six unvalidated location maps share a common structure (C03 §3.4):

```
UNVALIDATED MAP        SCAFFOLDING FUNCTION              WHAT ACTUALLY WORKS
─────────────────────  ──────────────────────────────── ─────────────────────────
Ingham foot zones      Protocol for systematic foot      General foot massage +
                       coverage + organ narrative        gate control + relaxation
Hara 12 zones          Meridian selection protocol +     Palpation detects real
                       diagnostic confidence             tenderness; zone-organ
                                                         assignment unvalidated
CSR palpation          Treatment direction protocol +    Relaxation + suboccipital
                       practitioner-patient narrative    myodural bridge (if occipital)
Sunnah points          Tradition-specific protocol       HO-1 from cupping at any
                                                         capillary-rich area
Qigong sounds/animals  Practice structure + meaning      Exercise physiology +
                                                         breathing + neuroplasticity
Chakra/nadi            Practice structure + meaning +    Exercise physiology +
                       interoceptive focus               pranayama + neuroplasticity
```

**The consistent pattern:** Unvalidated maps provide PROTOCOL STRUCTURE (what to do systematically), PATIENT NARRATIVE (why it should work), and PRACTITIONER CONFIDENCE (certainty about what to treat). These are the same positive scaffolding functions identified in C03 §3.4.3. The maps have therapeutic VALUE (via Evaluative Gates) without mechanistic VALIDITY. 🟡

### §3.4 — Location Specificity Evidence Hierarchy

Ranking all location-specificity evidence from strongest to weakest:

```
RANK  EVIDENCE TYPE                 CONFIDENCE  STATUS
────  ──────────────────────────── ──────────── ─────────────────────────────────
  1   PROKR2 molecular specificity  🟢          CAUSAL. Ablation eliminates effect.
      (Liu 2021 Nature)                          Demonstrated for ST36 → vagal-
                                                 adrenal axis. One pathway, one
                                                 point, full molecular chain.

  2   Segmental convergence          🟢          ESTABLISHED. 130+ years of
      (Head 1893, Sato 1997,                     evidence. Dorsal horn Lamina V
      Dorsher 2009)                              convergence. Back-Shu match 9/12
                                                 segments (1 in 5 billion). Covers
                                                 ~60-70% of acupoint effects.

  3   Neurogenic inflammatory spots  🟢          OBJECTIVE. First visible proof
      (Kim 2017)                                 acupoints are real physiological
                                                 phenomena. Disease-dependent.
                                                 Explains dynamic nature of points.

  4   Trigger point correspondence   🟢          INDEPENDENT CONVERGENCE. Two
      (Dorsher 2008, Melzack 1977)               traditions, same sites (93.3%).
                                                 Probability of chance: 1 in 7
                                                 trillion. NMJ basis (A08).

  5   Fascial convergence           🟢/🟡        STRUCTURAL. 80% of acupoints at
      (Langevin 2002, Maurer 2019)               CT planes. BUT: 80/50 split —
                                                 points correspond, pathways only
                                                 ~50%. Maurer 2019 refutes Heine's
                                                 VNB claim (2% not 80%).

  6   Neurovascular bundles          🟡→🔴       WEAKENED. Heine 1987 claimed 80%
      (Heine 1987, Maurer 2019)                  VNBs at acupoints. Maurer 2019:
                                                 only 2/100 (2%). NO at acupoints
                                                 is real (Ma 2003) but may reflect
                                                 nerve density, not unique VNBs.

  7   Bioelectrical properties       🟡          MIXED. Lower skin resistance at
      (Ahn 2008 review)                          SOME acupoints in SOME studies.
                                                 Quality "generally poor" (Ahn).
                                                 Best explained by neurogenic
                                                 inflammation (Kim 2018), not
                                                 dedicated bioelectrical system.

  8   Interstitial fluid channels    🟡          EMERGING. Zhang WB LHRC work is
      (Zhang WB 2008-2015)                       most experimentally grounded
                                                 meridian research. But "interstitium
                                                 is everywhere" problem.

  9   Primo Vascular System          🔴          UNCONFIRMED. <5 independent labs.
      (Soh 2002-present)                         Artifact concerns. Sub-skin
                                                 subtype (most meridian-relevant)
                                                 is LEAST verified. De Vernejoul
                                                 radiotracer REFUTED (Simon 1988).

 10   Propagated Sensation (PSC)     🟡          REAL phenomenon (10-30% of
                                                 patients), follows meridian
                                                 trajectories. But explainable by
                                                 axon reflex, fascial wave,
                                                 referred sensation — does NOT
                                                 require dedicated channel.

 11   Unvalidated location maps      🔴          NO evidence for organ-point
      (Ingham, Hara, CSR,                        specificity in any of these
      Sunnah, Chakra)                            systems. All serve as
                                                 therapeutic scaffolding.
```

**The hierarchy reveals a clear pattern:** The strongest evidence (ranks 1-4) converges on a single conclusion — acupoints are real, multi-system convergence zones at specific anatomical sites that correspond to neural, fascial, and inflammatory convergence. The weakest evidence (ranks 9-11) represents claims of dedicated channels or organ-specific maps that lack neuroanatomical basis. 🟡

### §3.5 — Body Region Pathway Comparison

The SAME stimulus type produces DIFFERENT effects depending on WHERE on the body it is applied (C01 §3.2.5). This section provides the full analysis of WHY — each major body region offers different pathway access.

#### §3.5.1 — Face: CN V Trigeminal → Brainstem Direct

**Neural pathway:** CN V (trigeminal nerve) with 3 divisions (V1 ophthalmic, V2 maxillary, V3 mandibular). All project to trigeminal sensory nuclear complex, which connects DIRECTLY to:
- DMN (dorsal motor nucleus of vagus) → parasympathetic output
- NTS (nucleus tractus solitarius) → autonomic integration hub
- LC (locus coeruleus) → norepinephrine modulation
- DRN (dorsal raphe nucleus) → serotonin modulation
- Reticular formation → arousal state

**What makes face UNIQUE:** Direct brainstem access WITHOUT spinal relay. Face stimulation triggers SUPRASPINAL effects (vagal, NE, 5-HT) immediately, not via segmental convergence. The diver's reflex demonstrates this: cold water on face (V1) → vagal bradycardia + peripheral vasoconstriction — a pure trigeminal-vagal reflex.

**Clinical validation:** eTNS (Cefaly device) at V1 territory is FDA-approved for migraine prevention and ADHD.

**Therapies accessing this region:** B12 (56% of points on face), B14 (forehead/temporal contacts), B03 (facial massage variant), B01 (facial acupoints).

**Confidence:** 🟢 — well-established neuroanatomy. A07 §1.7.

#### §3.5.2 — Ear: ABVN → Vagal Direct Access

**Neural pathway:** The outer ear is innervated by 4 converging nerve sources: auriculotemporal nerve (V3), great auricular nerve (C2-C3), lesser occipital nerve (C2), and Arnold's nerve (CN X auricular branch = ABVN). The ABVN at the concha is the ONLY place on the body surface where the vagus nerve is directly accessible.

**What makes ear UNIQUE:** ABVN afferents project directly to NTS — the same brainstem nucleus receiving cardiac, pulmonary, and gastrointestinal vagal afferents. Stimulating the ear concha = accessing the vagal system through the skin without invasive procedure. This is "transcutaneous auricular vagus nerve stimulation" (taVNS).

**Evidence:** Frangos 2015: fMRI confirms NTS activation with concha stimulation. HRV parasympathetic upregulation documented. Farmer 2020: gastric motility effects via auricular stimulation. NADA 5-point protocol (addiction/PTSD/anxiety). Battlefield Acupuncture (Niemtzow 2002): 5 ASP needles, US VA/DoD adopted, 2,800+ providers.

**Therapies accessing this region:** B01 (auricular acupuncture — most developed microsystem), B02 (auricular acupressure with seeds/pellets — Sea-Band, NADA), B14 (ear contact but NOT targeting ABVN specifically).

**Limitation:** Detailed organ-specific mapping on the ear (Nogier's inverted fetus) has some clinical evidence but lacks the convergent neuroanatomical basis of body acupoints. Vagal activation via concha is 🟢; organ-specific auricular mapping is 🟡/🔴 (A07 §4.6).

**Confidence:** 🟢 for vagal mechanism; 🟡 for organ-specific mapping. A07 §1.8, §4.6, B01 §3.3, B02 §3.3.

#### §3.5.3 — Back Paravertebral: Segmental Convergence + Sympathetic Chain

**Neural pathway:** Dorsal rami of spinal nerves T1-L5. Paravertebral territory contains Back-Shu points (BL channel, 1.5 cun lateral to spinous processes). Each vertebral level corresponds to a specific organ's autonomic innervation. UNIQUE: sympathetic chain ganglia lie anterior to transverse processes — paravertebral therapy has PRIVILEGED ACCESS to sympathetic output (B10 §5.2).

**What makes back UNIQUE:** The most direct segmental anatomy: vertebral level → dermatome → viscerotome mapping is most precise at paravertebral regions. The thoracolumbar fascia (TLF) is the largest continuous fascial surface in the body. T1-L5 covers ALL major organ viscerotomes (heart T1-T5, lungs T3-T5, stomach T6-T9, liver T7-T9, kidney T10-L1, large intestine T10-L1, bladder T11-L2).

**Evidence:** Back-Shu match organ innervation at 9/12 spinal levels (Dorsher). Bindegewebsmassage back reflex zones → documented organ effects. TLF shear strain -56% in chronic LBP (Langevin 2011) = location-specific pathology.

**Therapies accessing this region:** B01 (back-shu points), B03 (back massage — most common treatment area), B07 (most common cupping area), B09 (most common gua sha area — bilateral paravertebral strokes), B10 (spinal HVLA — the ONLY therapy targeting sclerotome directly).

**Confidence:** 🟢 — segmental anatomy is the most established basis for location specificity. A07 §1.6, §4.4.

#### §3.5.4 — Abdomen: Direct ENS Access

**Neural pathway:** T5-L2 segmental innervation (varying by organ) + the enteric nervous system (ENS) — the "second brain" with ~500 million neurons. Abdominal stimulation provides UNIQUE direct access to the ENS myenteric plexus via mechanical pressure on the GI wall.

**What makes abdomen UNIQUE:** The ONLY body region where mechanical surface stimulation can directly influence the ENS. Abdominal massage → ENS myenteric plexus → increased peristalsis = a direct mechanical-to-neural pathway.

**Therapies accessing this region:** B03 (Chi Nei Tsang, abdominal massage), B13 (Hara diagnosis — palpation-based), B04 (psoas release), B08 (CV4, CV8 — moxa-only navel point).

**Confidence:** 🟢 for ENS access; 🟡 for specific organ-targeting via abdominal palpation. B03 §3.2, B13 §3.2.

#### §3.5.5 — Body General: Mixed Spinal Nerves

**Neural pathway:** Mixed spinal nerve innervation. Standard somatovisceral reflex based on segmental convergence. Receptor types vary by skin type (hairy vs glabrous) and tissue depth.

**Key differentiator — CT afferents:** Present in hairy skin (arms, legs, trunk) but ABSENT from glabrous skin (palms, soles). CT afferent engagement requires: (a) skin-to-skin contact, (b) hairy skin territory, (c) slow velocity 1-10 cm/s (C01 §4.7). This creates a biological basis for WHY location matters within body general territory: forearm hairy skin → CT afferents → oxytocin pathway; palm glabrous skin → Meissner/Merkel → discriminative touch only.

**Therapies:** B03 (body massage — broadest CT afferent engagement in hairy skin), B04 (deep tissue — structure-based), B13 (whole-body but through clothing → CT BLOCKED).

**Confidence:** 🟢 — somatovisceral reflex and CT distribution are well-established. A07 §1.2, C01 §4.7.

#### §3.5.6 — Limbs: Distal Point Effectiveness

**Neural pathway:** Brachial plexus (C5-T1, upper limb) and lumbosacral plexus (L1-S3, lower limb). Limb acupoints are often DISTAL points — far from the target organ — yet some are among the most effective in clinical evidence (LI4 for facial pain, ST36 for GI function, P6 for nausea).

**The non-segmental paradox:** Limb points DO NOT share spinal segments with many target organs. ST36 (L4-L5) → stomach (T6-T9) = no segmental convergence. This 30-40% non-segmental gap (A07 §8 Q1) is filled by PROKR2 supraspinal pathways (Liu 2020/2021): hindlimb → PROKR2+ neurons → ascending to NTS/DMVN brainstem → vagal output → organ modulation.

**Therapies:** B01 (distal point selection = fundamental TCM principle), B02 (self-accessible distal points: LI4, P6, ST36), B11 (extremity muscles as trigger point targets).

**Confidence:** 🟡 — non-segmental limb point effects are real (P6/PONV has Cochrane evidence, ST36 has PROKR2 pathway) but the general mechanism for distal effectiveness is still being mapped. B01 §3.2, A09 §3.2.

#### §3.5.7 — Foot Sole: The Weakest Region

**Neural pathway:** Tibial nerve branches (L4-S3). The LEAST privileged neural access of any major body region targeted in Track B.

**Why foot sole is WEAKEST:**
1. **NO special brainstem pathway** — unlike face (CN V → DMN/NTS) or ear (ABVN → NTS), foot sole has only standard spinal nerve L4-S3 with NO privileged pathway to any brainstem nucleus
2. **CT afferents ABSENT** — glabrous skin = no affective touch pathway = no oxytocin via CT→PVN
3. **Segmental mismatch** — L4-S3 does NOT connect to most organs claimed by reflexology (brain, lungs, liver, stomach). Only bladder (S2), pelvis (S2-S4), and sciatic territory have any overlap
4. **Mechanoreceptor function** — foot sole Merkel/Meissner/Pacinian receptors serve BALANCE AND LOCOMOTION, not organ sensing

**The foot reflexology implication:** B06's zone-organ claims fail at every level of the evidence hierarchy. The foot is the WORST possible location for organ-specific therapy. Reflexology effects (anxiety↓, sleep↑) arise from non-specific mechanisms (gate control, relaxation, therapeutic context) that any systematic foot massage would produce equally well — and fMRI confirms this (Descamps 2023: reflexology = sham massage on brain connectivity).

**The body region hierarchy restated:**

```
REGION          PATHWAY ACCESS                     PRIVILEGE LEVEL
─────────────── ──────────────────────────────── ─────────────────
Face (CN V)     Direct brainstem (DMN, NTS,       HIGHEST
                LC, DRN) via trigeminal
Ear (ABVN)      Direct vagal (NTS) via             HIGH
                Arnold's nerve
Back (T1-L5)    Segmental convergence +            HIGH
                sympathetic chain proximity
Abdomen         Direct ENS access +                MODERATE-HIGH
                visceral innervation
Limbs           Non-segmental via PROKR2           MODERATE
                supraspinal pathways
Body general    Standard somatovisceral via        MODERATE
                segmental convergence
Foot sole       L4-S3 only, NO special             LOWEST
                pathway, NO CT afferents
```

🟡 Hierarchy derived from neuroanatomical evidence across A07, A09, and all 15 Track B §3 sections.

---

## §4 — EMERGENT PATTERNS

Patterns discovered FROM the cross-reference that are NOT visible in individual Track A or Track B files.

### §4.1 — The Precision Paradox 🟡

Therapies claiming the HIGHEST location precision often have the WEAKEST validation for it. Therapies claiming the LOWEST precision often use well-validated anatomy:

```
THERAPY    CLAIMED PRECISION     VALIDATION           PARADOX
─────────  ────────────────────  ────────────────────  ────────────────────
B06        Detailed organ zones  🔴 ~80% refuted       Elaborate map,
                                                       no basis
B14        CSR detection points  🔴 r=0.004            Specific diagnosis,
                                                       random results
B01        361 codified points   🟢 PROKR2, 93% trigger point    High claim,
                                                       HIGH validation
B03        "Wherever is tight"   🟢 Dermatome,          Low claim,
                                   CT distribution      solid anatomy
B04        "Where tissue is      🟢 trigger point + fascial      Low claim,
           restricted"              planes              solid anatomy
```

**The pattern:** Precision is CLAIMED in inverse proportion to evidence quality for B06/B14 (the scaffolding cluster from C03 §3.4). Elaborate point systems substitute for empirical validation. Conversely, B03/B04 practitioners make modest claims ("treat the tight area") but their targeting is guided by validated anatomy (dermatomes, trigger point overlap, fascial planes).

**Exception:** B01 acupuncture claims HIGH precision AND has HIGH validation — the 361-point system is both elaborate AND neuroanatomically grounded. This makes B01 the ONLY therapy where the traditional location system matches modern anatomy. 🟡

### §4.2 — The Fundamental Asymmetry: Points vs Pathways 🟡

A09's central finding applies directly to location specificity: evidence for ACUPOINTS is strong; evidence for CONNECTED PATHWAYS between them is much weaker.

```
                     EVIDENCE QUALITY
                     ──────────────────────
Points (acupoints)   🟢 STRONG
                     • 80% at fascial planes (Langevin)
                     • 93% trigger point overlap (Dorsher)
                     • PROKR2 molecular basis (Liu)
                     • Neurogenic spots (Kim 2017)
                     • Multi-system convergence zones

Pathways (meridians) 🟡 WEAK
                     • Only ~50% pathway fascial correspondence
                     • PVS unconfirmed
                     • Radioactive tracer = venous (Simon 1988)
                     • fMRI: NO meridian-exclusive patterns
                     • PSC explainable by known mechanisms
```

**Implication for location specificity:** The POINTS matter, but the LINES connecting them may not. This validates point-based therapies (B01, B02, B11) without validating meridian-based treatment logic (treating along a meridian trajectory). Dry needling (B11) discards meridian theory entirely and achieves comparable results for musculoskeletal conditions — suggesting the points, not the pathways, carry the therapeutic weight. 🟡 A09 §3.1.

### §4.3 — The Dynamic Acupoint Phenomenon 🟢/🟡

Kim 2017 introduces a paradigm shift: acupoints are not FIXED anatomical landmarks but EMERGENT physiological phenomena that appear with organ disease and resolve with treatment.

**Implications for location specificity:**
1. **Standardized maps are APPROXIMATIONS** — individual patients may have active points at non-standard locations based on their current pathology
2. **Palpation-based targeting > chart-based targeting** — finding where the body is CURRENTLY active (tender, warm, swollen, electrically different) may be more precise than following a standard point prescription
3. **"Sham" acupuncture works because sham may hit active non-standard points** — if Kim's neurogenic spots shift with disease state, a needle placed "randomly" may still land on an active spot
4. **Location specificity is TIME-DEPENDENT** — the same point may be active during acute illness and inactive during health

**The Ashi advantage:** B01's Ashi point concept ("take the pain as the point") and B11's trigger point palpation both prioritize finding WHERE the body is currently active over following a fixed map. This palpation-based approach aligns with Kim's dynamic acupoint model better than chart-based approaches (B06, B14). 🟡

### §4.4 — The Body Region Hierarchy 🟡

§3.5 revealed that body regions form a natural hierarchy for therapeutic pathway access. This hierarchy is INDEPENDENT of stimulus type — the same stimulus (sustained point pressure) produces different effects at different regions because the underlying neural architecture differs:

```
Sustained point pressure at:
  Face → trigeminal-vagal activation (parasympathetic, NE, 5-HT modulation)
  Ear concha → vagal activation (NTS → cardiac, pulmonary, GI modulation)
  Back T4 → segmental convergence (cardiac somatovisceral reflex)
  Abdomen → ENS activation (direct peristalsis)
  Forearm → CT afferents + segmental (affective touch + somatovisceral)
  Foot sole → gate control only (no CT, no special pathway, minimal convergence)
```

This explains why B02 acupressure at P6 (wrist, median nerve → vagal) has Cochrane-level evidence (NNT≈4 for PONV) while B06 reflexology at "stomach zone" (foot sole, L4-S3 → no GI connection) has no condition-specific evidence. SAME stimulus type, SAME pressure, DIFFERENT region → DIFFERENT pathway access → DIFFERENT clinical evidence.

**The face-ear-foot triangle:** Three body regions with reflexology/microsystem traditions show this hierarchy most starkly:
- Face: CN V → brainstem DIRECT → eTNS FDA-approved = REAL pathway access
- Ear (B01/B02 auricular): ABVN → NTS → vagal DIRECT → taVNS validated = REAL pathway access
- Foot (B06): L4-S3 → spinal only → NO special pathway = MINIMAL pathway access with unvalidated map

🟡 All region comparisons supported by A07 §1.7, §1.8, B06 §3.4.

### §4.5 — The Scaffolding-Specificity Inverse 🟡

Combining C03's scaffolding analysis with C04's location specificity evidence reveals an inverse relationship:

```
                MORE SCAFFOLDING ────────────────────── LESS SCAFFOLDING
                (elaborate unvalidated location map)    (no special map needed)

B14 ──── B06 ──── B12 ──── B13 ──── B03 ──── B07 ──── B01 ──── B15
PURE     NEAR     FIXED    HARA     AREA     AREA     VALIDATED  NO
SCAFFOLD PURE     POINTS   UNVAL    BASED    BASED    POINTS    POINTS
(CSR)    (zone    (no                                  (PROKR2)
          refuted) specif.)
```

Therapies that NEED elaborate location maps to justify their treatment protocol tend to be those whose specific mechanisms are weakest. Therapies with strong specific mechanisms (B01 PROKR2, B07 HO-1, B15 exercise physiology) either have VALIDATED location systems or don't need one.

**This is NOT coincidental:** Strong specific mechanisms are discoverable (they produce measurable effects at specific sites). Weak or absent specific mechanisms produce effects only through non-specific pathways — but an elaborate map CREATES the appearance of specificity, even when the mechanism doesn't support it. The map is the scaffolding. 🟡

### §4.6 — The Independent Convergence Pattern 🟢

Multiple independent traditions, separated by millennia and geography, identified the SAME anatomically significant body sites:

```
TRADITION              ORIGIN            SYSTEM         OVERLAP WITH ACUPOINTS
─────────────────────  ──────────────── ──────────── ──────────────────────
Chinese Acupoints      ~200 BCE China    361 points    = reference standard
Western Head Zones     1893 UK           Max. points   ≈ Mu/Shu (Beissner 2011)
Trigger Points         1942 USA          255 trigger points      93.3% (Dorsher 2008)
Anatomy Trains         2001 USA          12 lines      8/9 overlap (Dorsher 2009)
Neurogenic Spots       2017 Korea        Dynamic       67% (Kim 2017)
```

Five independent discovery traditions converging on the same body sites — this is among the strongest evidence that these locations reflect genuine BIOLOGICAL features, not cultural artifacts. The convergence is explained by multi-system overlap zones (§3.2.6): wherever neural, fascial, vascular, and immune systems converge densely, multiple traditions independently identify the site as clinically significant. 🟢

### §4.7 — Location Matters MORE for Some Mechanisms Than Others 🟡

Combining C01's mechanism-pathway matrix with C04's location analysis reveals that location specificity varies by MECHANISM, not just by therapy:

```
MECHANISM                    LOCATION-DEPENDENT?     WHY
──────────────────────────── ─────────────────────── ──────────────────────
PROKR2 vagal-adrenal         YES — highly            PROKR2+ neuron density
                              location-specific       varies by body region
Somatovisceral reflex        YES — segmentally       Dermatome-viscerotome
                              specific                convergence is segmental
HO-1 pathway                 NO — area-dependent     Any capillary bed works
Gate control                 NO — ubiquitous         Aβ fibers are everywhere
CT afferents                 PARTIALLY — skin-type   Hairy skin only, 1-10 cm/s
                              dependent
endocannabinoid system activation               NO — depth-dependent    Requires reaching deep fascia
                              (not location)          CB1/CB2 (>40-65N anywhere)
Evaluative Gates             NO — context-dependent  Therapeutic encounter, not
                                                     anatomical location
Relaxation response          NO — ubiquitous         Any sustained touch/warmth
```

**Pattern:** Location-DEPENDENT mechanisms (PROKR2, segmental convergence) are concentrated in Group A Mechanistically Rich therapies from C03 §3.5. Location-INDEPENDENT mechanisms (gate control, HO-1, endocannabinoid system, Evaluative Gates) operate across Group B and C therapies. This explains WHY the location specificity spectrum (§3.1) correlates with the mechanism specificity spectrum (C03 §3.5). 🟡

---

## §5 — PREDICTIONS & TESTABLE HYPOTHESES

Each prediction is 🔴 Hypothesis unless noted.

### P1 — Facial Stimulation at ANY Point ≈ Point-Specific Facial Stimulation for Autonomic Outcomes

**Prediction:** Structured facial stimulation at randomly selected facial points should produce equivalent autonomic outcomes (HRV, blood pressure, anxiety) to protocol-prescribed facial points, because the trigeminal-vagal pathway operates at the ZONE level (V1/V2/V3), not at individual-point level.

**Confirm:** Randomized study (same tools, same duration, random facial points vs prescribed points) shows no significant outcome difference for autonomic measures (HRV, BP, anxiety scales).
**Refute:** Prescribed points significantly outperform random facial stimulation for ≥2 autonomic outcomes with p<0.01, suggesting point specificity beyond trigeminal zone effects.

### P2 — Foot Reflexology = Foot Massage for All Outcomes

**Prediction:** Non-zone foot massage (same duration, same pressure, therapist follows no foot map) should produce equivalent outcomes to Ingham-zone reflexology for ALL measured outcomes (anxiety, sleep, vital signs), because foot sole L4-S3 innervation provides no organ-specific pathway.

**Confirm:** Head-to-head RCT shows non-zone foot massage = reflexology for anxiety (primary) + ≥2 secondary outcomes (sleep, BP, HR).
**Refute:** Ingham-zone reflexology significantly outperforms non-zone foot massage for condition-specific outcomes, suggesting some zone specificity exists despite absent neuroanatomical basis.

### P3 — Dynamic Acupoint Detection Improves Targeting

**Prediction:** Acupuncture guided by real-time detection of active neurogenic spots (electrical impedance scanning, thermography, or palpation tenderness mapping) should outperform standard fixed-chart acupuncture for chronic conditions, because Kim 2017 shows acupoints are disease-state-dependent, not fixed.

**Confirm:** Neurogenic-spot-guided acupuncture shows >0.3 SMD advantage over standard-chart acupuncture for chronic pain (primary) or GI dysfunction (secondary) in a blinded RCT with ≥60 participants.
**Refute:** No outcome difference, suggesting standard maps are sufficiently accurate approximations of active neurogenic sites, or the precision gain is too small to detect clinically.

### P4 — PROKR2 Density Maps Predict Point Effectiveness

**Prediction:** Body regions with higher PROKR2+ neuron density (limbs > trunk, based on Liu 2021 data: 16.7% lumbar vs 6.1% thoracic DRG) should show stronger EA anti-inflammatory effects. ST36 (hindlimb, high PROKR2 density) > back-shu points (trunk, lower PROKR2 density) for vagal-adrenal anti-inflammatory response.

**Confirm:** Systematic EA comparison across body regions shows PROKR2 density predicts anti-inflammatory response magnitude (r > 0.5).
**Refute:** Anti-inflammatory response is equivalent across body regions regardless of PROKR2 density, suggesting other pathways dominate or PROKR2 density is uniform in humans.

### P5 — Body Region Predicts Optimal Stimulus Type

**Prediction:** Because body regions provide different pathway access (§3.5), optimal therapy matching should follow the region-pathway hierarchy: face → pressure-based (trigeminal-vagal), ear → seed/needle (ABVN-vagal), back → deep pressure or needle (segmental convergence), foot → movement/exercise (proprioceptive, not organ-specific). A therapy applied to its non-optimal region should show weaker effects than the same therapy at its optimal region.

**Confirm:** Cross-region randomized trial (same therapy at optimal vs non-optimal region) shows >0.3 SMD advantage for region-matched therapy.
**Refute:** No region-matching effect, suggesting mechanism operates independently of region.

### P6 — Namikoshi ≈ Masunaga for Clinical Outcomes

**Prediction:** Namikoshi Shiatsu (660 anatomical points, NO meridian theory, NO Hara diagnosis) and Masunaga Zen Shiatsu (extended meridians, Hara diagnosis, reactive point selection) should produce equivalent outcomes for chronic pain and well-being, because the physical stimulus is IDENTICAL and the theoretical difference (anatomical vs meridian framework) is SCAFFOLDING, not mechanism.

**Confirm:** Head-to-head RCT shows no significant outcome difference for chronic pain (primary) + well-being (secondary).
**Refute:** Masunaga significantly outperforms Namikoshi, requiring investigation of whether (a) extended meridian point selection identifies genuinely different anatomical targets, or (b) more elaborate theory = stronger scaffolding = stronger Evaluative Gates enhancement.

Note: This prediction duplicates C03 P4 (Shiatsu natural experiment) but adds the location-specificity framing. C03 P4 tests whether theory = scaffolding; C04 P6 tests whether point-selection logic matters for location specificity.

---

## §6 — LIMITATIONS & GAPS

### §6.1 — Methodological Limitations

1. **"Point specificity" is poorly defined.** Shifting 1 cm from an acupoint may or may not change the therapeutic effect — the "point" may actually be a 1-3 cm ZONE of multi-system convergence, not a pinpoint. The level of spatial precision required for location to matter is uncertain and likely varies by mechanism (PROKR2 may require precision; gate control does not).

2. **Region comparison confounded by skin type.** Face vs foot comparison is confounded by MULTIPLE differences (nerve territory, skin type, receptor density, cultural meaning) — isolating the contribution of neural pathway access alone is difficult.

3. **Validated/unvalidated distinction is binary but reality is continuous.** Some "unvalidated" location systems may contain PARTIAL validity masked by overall system invalidity. A detailed point map may include a subset at genuine nerve branch points — but without validation research, we cannot distinguish valid from invalid subsets.

4. **Evidence hierarchy is based on current evidence, not inherent importance.** PROKR2 ranks highest because it has the most rigorous evidence (Nature 2021, causal ablation). Other location mechanisms may be equally important but less studied (interstitial fluid channels, dynamic acupoint biology).

5. **Location-specificity evidence is overwhelmingly from acupuncture research.** The evidence hierarchy (§3.4) draws primarily from B01 literature. Whether the same location principles apply to B03 massage, B07 cupping, or B15 movement therapy is largely untested.

### §6.2 — Missing Data

1. **PROKR2 distribution in humans.** Liu 2021 data is from mice. Whether human PROKR2+ neuron distribution matches the murine pattern is assumed but not confirmed.

2. **No head-to-head region comparison trials.** No RCT has tested the SAME therapy at DIFFERENT body regions to isolate the region contribution. All existing evidence is cross-therapy (comparing a face therapy to B06 foot therapy confounds region with therapy).

3. **Hara diagnosis reliability unknown.** Unlike CSR (r=0.004) and chiropractic palpation (κ=0.02-0.42), Hara diagnosis has NEVER been formally tested for inter-rater reliability.

4. **CT afferent threshold mapping incomplete.** The boundary between hairy and glabrous skin is well-known, but CT afferent density varies WITHIN hairy skin regions — a detailed map of where CT engagement is strongest/weakest is not available.

5. **BL67 breech mechanism unresolved.** The most mechanistically puzzling location-specific finding in all of Track B: BL67 at S1 dermatome has NO known connection to uterine function (T10-L1, S2-S4), yet Cardini 1998 JAMA (n=260, 75.4% vs 47.7%) provides the strongest single-point clinical evidence. This finding CANNOT be explained by ANY current location-specificity model.

6. **No systematic test of unvalidated maps.** None of the 6 unvalidated location maps (§3.3) has been tested with a proper sham design that preserves SCAFFOLDING while randomizing LOCATION. This design would isolate the location contribution from the scaffolding contribution.

---

## §7 — OPEN QUESTIONS

Questions RAISED BY the cross-reference analysis that only become visible when comparing location specificity across therapies.

**Q1 (CRITICAL). Can personalized acupoint mapping improve outcomes?** Given that acupoints are dynamic (Kim 2017), standardized maps are approximations, and individual dermatome variation is significant (A07 §7), would real-time detection of active neurogenic spots (via impedance, thermography, or palpation) outperform standard-chart point selection? This could reconcile the "sham ≈ verum at same points" problem: if both sham and verum are near active neurogenic sites, they both work. The TARA project (Langevin 2025) may provide the standardized atlas needed to test this systematically.

**Q2. Why does B01 have BOTH validated points AND validated pathways, while all other therapies have at most one?** Only acupuncture has both an elaborated point system AND neuroanatomical evidence supporting it. Is this because: (a) 2000+ years of empirical refinement converged on genuine anatomy, (b) more research investment than any other therapy, or (c) the needle-as-stimulus uniquely requires point precision (other stimuli work at area/region level)? If (c), then location specificity is a property of the STIMULUS-LOCATION interaction, not location alone.

**Q3. Is the BL67 breech effect a real non-segmental pathway or a statistical artifact?** The Breech Paradox (B08 §3.2) is the most important unsolved location-specificity puzzle. If the effect is real AND reproducible, it implies a location-specific pathway that NONE of the current models (segmental convergence, PROKR2, fascial) can explain. Possible mechanisms: long spinal cord propriospinal pathways, sympathetic reflex via S1 innervation, or an unknown ascending pathway. If the effect fails to replicate in a large pre-registered trial, the paradox dissolves.

**Q4. Does the body region hierarchy hold across stimulus types?** §3.5 shows face > ear > back > body > foot for pathway access. But this hierarchy was derived primarily from pressure/needle stimulation data. Does it hold for thermal (moxibustion), movement (yoga face exercises vs yoga foot exercises), or microtrauma (facial gua sha vs back gua sha) stimuli? The region hierarchy may be stimulus-type-dependent.

**Q5. What fraction of location-specific clinical effects survives rigorous sham control?** Network meta-analyses (A09 §4.2) show verum acupuncture ≈ sham at same points but > sham at non-indicated points. This suggests location matters MODESTLY but not dramatically. What is the SMD attributable to LOCATION ALONE (controlling for stimulus type, duration, depth, and therapeutic context)? No study has isolated the location variable with sufficient rigor.

**Q6. Can the scaffolding-location maps be salvaged?** For Ingham (B06) and Hara (B13): is there a SUBSET of points within each system that corresponds to validated anatomy, embedded within a larger system of unvalidated points? If so, the valid subset could be extracted, validated, and used — while acknowledging the rest as scaffolding. This "extraction and validation" approach would be more productive than wholesale acceptance or rejection.

**Q7. Does location matter for non-specific mechanisms?** Gate control, relaxation response, and Evaluative Gates are classified as location-INDEPENDENT (§4.7). But is this entirely true? Does gate control at a painful region provide more relief than gate control at a non-painful region (likely yes — segmental gating)? Does relaxation response differ by body region (possible — facial relaxation triggers diving reflex)? The "location-independent" classification may need refinement.

**Q8. Why did multiple independent traditions converge on the same body sites?** The Independent Convergence Pattern (§4.6) shows 5 traditions identifying overlapping body sites. Is this convergence driven by: (a) biological universals (multi-system convergence zones are species-level features), (b) shared cultural transmission (TCM influenced all subsequent systems), or (c) selection bias (researchers looked for correspondence and found it)? Dorsher's statistical analysis (1 in 7 trillion for trigger point-acupoint) argues against (c), and B11/B04 were developed without TCM influence, arguing against (b). Biological universals remain the strongest candidate.

---

## §8 — CROSS-REFERENCES

### §8.1 — Track A Files Referenced

| File | Sections Referenced | Key Concept Used |
|------|-------------------|-----------------|
| A01 PNS | §3 (CT afferents, fiber types) | CT engagement pattern — hairy skin, 1-10 cm/s, location-dependent |
| A02 ANS | §3.5 (PROKR2, vagal), §4.6-§4.9 | PROKR2 molecular specificity, somatoautonomic reflex, Zone D Bridge |
| A03 Fascia | §1.4, §3 (mechanotransduction) | 80% acupoints at fascial planes (Langevin), 80/50 split, CB1/CB2 depth |
| A04 Vascular | §3.3 (NO at acupoints) | Ma 2003/2017 NO elevation, VNB weakened (Maurer 2019 2% not 80%) |
| A05 Neuroimmune | §2 (mast cell, neurogenic) | Higher mast cell density at acupoints, neurogenic inflammation |
| A06 Endocrine | §1-§3 (chemical milieu) | Local chemical enrichment at convergence zones, Han opioids |
| A07 Somatotopic | §1-§4 (ALL) | Segmental convergence (CORE of C04), Head zones, Kim 2017, dermatome maps, trigeminal territory, auricular somatotopy, body region pathway analysis |
| A08 MSK | §3-§4 (trigger points, proprioception) | trigger point-acupoint 93.3% overlap (Dorsher), NMJ hypothesis, Freeman-Wyke receptors |
| A09 Meridian | §1-§4 (ALL) | 7 candidate substrates, evidence scorecard, fundamental asymmetry (points > pathways), multi-system convergence zones, dynamic acupoints |

### §8.2 — Track B Files Referenced

All 15 Track B files referenced via §3 (Application Points & Areas), specifically:

**Point-specific therapies (§3 data most relevant):**
- B01 §3: 361 acupoints (8 categories), point selection logic, microsystems, PROKR2 at ST36
- B02 §3: Same points via pressure, ABVN advantage, P6 evidence, PROKR2 depth question
- B08 §3: Acupoints for moxa, BL67 breech paradox, heat-sensitive moxibustion
- B11 §3: trigger point targeting, 93.3% overlap, three targeting models (trigger point/IMS/FSN)

**Region/structure-specific therapies:**
- B03 §3: Area-based, regional pathways (back T1-L5, face CN V, abdomen ENS), tradition-specific maps
- B04 §3: Structure-based (fascial planes, trigger points, Stecco CC/CF, Anatomy Trains)
- B07 §3: Area-based (700-5000 mm²), TCM vs Islamic point systems
- B09 §3: Area-based (stroke along fascial planes), facial gua sha as different modality
- B10 §3: Spinal segments, facet joint targeting, palpation reliability poor (κ=0.02-0.42)
- B13 §3: Namikoshi 660 tsubos vs Masunaga reactive points, Hara diagnosis unvalidated

**Unvalidated location maps:**
- B06 §3: Ingham foot zones, ~80% no neuroanatomical basis, CT afferents absent from sole
- B12 §3: 9 fixed points, no condition-specific variation, 56% facial/trigeminal
- B14 §3: No point system, CSR r=0.004, myodural bridge only specific finding

**Location-independent therapies:**
- B15 §3: No application points, whole-body engagement, loading by region
- B16 §3: No application points, region by style/pose, Yin yoga most tissue-specific

### §8.3 — Track C Dependencies and Connections

- **C01 → C04:** C01's body region parameter modifier (§3.2.5) identified face > ear > body > foot but deferred full analysis to C04. C04 provides that analysis with neuroanatomical detail for each region. C01's CT afferent engagement pattern (§4.7) explains location-dependent receptor availability.

- **C03 → C04:** C03's scaffolding analysis (§3.4) identifies WHICH therapies' location maps are scaffolding. C04 maps every unvalidated location system to the scaffolding framework. C03's specificity spectrum (§3.5) correlates with C04's location specificity spectrum. The Scaffolding-Specificity Inverse (§4.5) is a novel cross-C03/C04 pattern.

- **C04 → C02:** C04's body region pathway hierarchy explains WHY certain therapies work for certain conditions at certain locations. C02 will use this to explain condition-therapy matching (e.g., why P6 acupressure works for PONV — region pathway + stimulus type + mechanism).

- **C04 → C05:** Individual variation in location specificity (dermatome variation, PROKR2 expression, neuroanatomical variants, dynamic acupoint shifting) feeds directly into C05's variation framework.

### §8.4 — Human-Predictive-Drive Connection Points

- **Evaluative Gates:** Unvalidated location maps enhance Evaluative Gates (therapeutic context) — the scaffolding-specificity inverse (§4.5) is an extended application of Human-Predictive-Drive's concept. The MORE elaborate the map, the STRONGER the Evaluative Gate enhancement, even without mechanistic validity.
- **Zone D (PFC reach ≈ 0):** Somatovisceral reflexes are pure Zone D — they operate at spinal cord level with no PFC involvement or awareness. Location specificity at the segmental level bypasses consciousness entirely.
- **Direct-State Reward:** CT afferents → posterior insula → direct-state pleasant touch. CT engagement is LOCATION-DEPENDENT (hairy skin only, §3.5.5) — making direct-state reward from touch a location-specific phenomenon.
- **Gap 2 (Driver Layer):** Somatotopic organization IS the routing table for Gap 2. Segmental maps (A07) determine WHICH signals reach WHERE. C04 adds the dimension of WHERE the therapy is applied determining which route the signal takes.

### §8.5 — Citations for NEW Sources

No new primary sources introduced in C04. All citations referenced through Track A/B files where they were originally documented. This is consistent with Track C's role as SYNTHESIS of existing data, not introduction of new research.
