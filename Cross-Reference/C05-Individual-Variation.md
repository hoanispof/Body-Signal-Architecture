---
title: Individual-Variation
id: C05
version: 0.1
status: DRAFT
scope: Why does the same therapy produce different results in different people? Unified framework for inter-individual variation across body-based therapies — integrating genetics, dose-response, expectation, anatomy, demographics, and responder prediction.
sources: [A01-A09, B01-B16, C01, C02, C03, C04]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# Individual-Variation

## §1 — PURPOSE & METHODOLOGY

### §1.1 — Why This Cross-Reference Exists

C01 established WHAT stimulus types activate WHICH pathways. C03 identified WHICH mechanisms are shared and unique. C04 mapped WHERE on the body matters. C02 determined WHICH conditions respond to WHICH therapies. But all four analyses assume a GENERIC patient — they describe what SHOULD happen based on stimulus, mechanism, location, and condition, without addressing the most clinically important variable:

**Why does the same therapy, applied with the same technique, at the same location, for the same condition, produce dramatically different results in different people?**

This capstone document answers that question by integrating individual variation data from all 15 Track B §8 sections with the cross-cutting frameworks from C01-C04. It is the FINAL Track C synthesis — every finding in C05 connects back to at least one earlier Track C file.

The question matters because inter-individual variation is the single largest obstacle to:
1. **Clinical prediction** — who will respond to which therapy?
2. **Research interpretation** — why do RCTs show modest average effects when some patients improve dramatically and others not at all?
3. **Treatment matching** — how to select the optimal therapy for a specific patient?

### §1.2 — Data Sources

- **Individual variation data:** All 15 Track B §8 (Individual Variation & Contraindications) sections, read in full
- **Responder prediction models:** B01 §8.1 (neuroimaging predictors), B10 §8.3 (clinical prediction rules)
- **Genetic data:** B01 §8.2 (COMT, GABRB3, OPRM1, BDNF), B03 §8.1 (OXTR, FAAH candidates), B08 §8.3 (TRPV1 variants)
- **Stimulus parameters:** C01 §3.2 (parameter modifiers — pressure, speed, depth, electrical, body region, skin contact, movement style)
- **Mechanism context:** C03 §3.4 (therapeutic scaffolding), §3.5 (specificity spectrum), §4.4 (non-specific floor)
- **Location context:** C04 §3.5 (body region pathway hierarchy), §4.3 (dynamic acupoint phenomenon)
- **Clinical context:** C02 §4 (emergent patterns — active-passive divide, sham paradox, domain specificity)

### §1.3 — Methodology

**Variation source extraction.** Every source of individual variation mentioned in every Track B §8 was cataloged with: variation factor, mechanism affected, evidence level, and therapy applicability.

**Six-domain classification.** Variation sources were organized into six domains following the plan specification:
1. **Genetic** — polymorphisms affecting therapy-relevant receptors, enzymes, and pathways
2. **Dose-Response** — how treatment parameters (pressure, frequency, duration) interact with individual thresholds
3. **Expectation & Conditioning** — psychological modulation of therapeutic outcomes via Evaluative Gates
4. **Anatomical/Physiological** — structural differences in the tissues receiving and transmitting therapeutic stimuli
5. **Demographic** — population-level factors (sex, age, chronicity) that systematically shift response profiles
6. **Responder Phenotype** — multi-factor models combining domains 1-5 for prediction

**Cross-therapy synthesis.** For each variation source, applicability across all 15 therapies was assessed. A source identified in one therapy (e.g., TRPV1 variants in B08) was evaluated for relevance to other therapies based on mechanism overlap from C03.

**Evidence assessment.** Each variation factor was classified as:
- 🟢 **Research-supported** — studied directly in the therapy context with positive findings
- 🟡 **Synthesis-inferred** — supported by mechanism evidence but not directly tested as a variation source
- 🔴 **Hypothesis** — plausible based on physiology but no direct or indirect evidence

---

## §2 — TAXONOMY / CLASSIFICATION

### §2.1 — The Six Variation Domains

Individual variation in therapy response arises from six interacting domains. These are NOT independent — genetic variation (domain 1) determines anatomical features (domain 4), which interact with demographic factors (domain 5), modulated by expectations (domain 3), at a specific dose (domain 2). The responder phenotype (domain 6) is the integration of domains 1-5.

```
DOMAIN                    MODIFIES                         DATA RICHNESS
─────────────────────── ──────────────────────────────── ────────────────
1. Genetic               Receptor density, enzyme          B01 ONLY has
                          activity, pathway sensitivity    RCT data; rest
                                                           = hypothesis

2. Dose-Response          Which mechanisms activate at      C01 parameter
                          what intensity, for how long     modifiers + sparse
                                                           clinical data

3. Expectation &          Evaluative Gates modulation,     Ubiquitous across
   Conditioning           scaffolding contribution,        Track B but poorly
                          practitioner effects              quantified

4. Anatomical /           Tissue structure receiving       Scattered across
   Physiological          the stimulus (fascia, nerve,     B files; no
                          receptor distribution)           systematic mapping

5. Demographic            Population-level shifts in       Well-established
                          domains 1-4 (sex, age,           in general medicine,
                          chronicity)                      sparse for body
                                                           therapies

6. Responder              Multi-factor prediction          B01 neuroimaging
   Phenotype              combining domains 1-5            only; B10 CPR
                                                           unvalidated
```

### §2.2 — Variation Data Distribution Across Track B

The depth and quality of individual variation data varies enormously across Track B files:

```
THERAPY    §8 RICHNESS    KEY VARIATION DATA
─────────  ─────────────  ──────────────────────────────────────────
B01        ★★★★★          RICHEST. Genetics (COMT, GABRB3, OPRM1),
                           neuroimaging responder prediction (83-88%),
                           expectations (69.8% pain variance)

B10        ★★★☆☆          Clinical prediction rules (Flynn 2002),
                           pain catastrophizing, hypermobility spectrum,
                           age-related changes, VBA safety concern

B11        ★★★☆☆          trigger point palpation reliability (κ 0.2-0.4),
                           tissue characteristics, catastrophizing,
                           NO responder prediction models

B04        ★★★☆☆          Fascial thickness (sex differences), endocannabinoid system-fascia
                           connection (hydration), sex hormones (ERα),
                           practitioner skill

B03        ★★☆☆☆          CT afferent density, pain threshold, autonomic
                           baseline, genetic candidates (OXTR, FAAH
                           untested)

B08        ★★☆☆☆          TRPV1 genetic variation (unique), heat
                           sensitivity spectrum, disease-state
                           sensitization

B02        ★★☆☆☆          Point location accuracy (self vs practitioner),
                           pressure calibration, CT density, ABVN
                           anatomy variation

B07        ★★☆☆☆          Capillary fragility variation, mark response
                           variability, pressure sensitivity

B09        ★★☆☆☆          Sha appearance variability (differential
                           tissue pathology), child abuse misidentification

B15        ★★☆☆☆          Positive/negative predictors, style selection
                           table, adherence as key variable

B16        ★★☆☆☆          Style selection by patient profile,
                           hypermobility contraindication for Yin,
                           hot yoga heat risk

B06        ★☆☆☆☆          Practitioner/protocol variation dominant,
                           foot sensitivity, expectation

B12        ★☆☆☆☆          Delivery mode variation, psychological risk
                           from self-guided exposure

B13        ★☆☆☆☆          Practitioner skill variability, body
                           composition, clothing barrier

B14        ★☆☆☆☆          Psychological receptivity dominant,
                           suboccipital muscle state only specific factor
```

**Pattern:** Variation data richness correlates with C03's mechanism specificity spectrum (§3.5). Mechanistically rich therapies (B01, B10, B04) have more identified variation sources because their specific mechanisms create more dimensions along which individuals can differ. Mechanistically weak therapies (B06, B12, B14) have variation dominated by a single factor: psychological receptivity / Evaluative Gates. 🟡

---

## §3 — MAIN ANALYSIS

### §3.1 — Genetic Factors

#### §3.1.1 — Current Evidence: Acupuncture Only

Genetic prediction of therapy response has been studied ONLY for B01 acupuncture. No other Track B therapy has published genetic predictor data. All genetic evidence below comes from B01 §8.2 unless otherwise noted.

**COMT rs4680 (Val158Met) — Catechol-O-Methyltransferase:**

COMT metabolizes catecholamines (dopamine, norepinephrine, epinephrine). The Val158Met polymorphism affects enzyme activity: Met/Met = 3-4× lower activity = higher catecholamine and pain sensitivity.

```
STUDY                THERAPY    CONDITION       FINDING
───────────────────  ─────────  ──────────────  ─────────────────────────
Yang et al. 2023     EA         Cancer MSK      Met carriers: 74% response
(J Pain, PEACE       (electro-  pain            vs Val/Val: 50%
trial, n=317)        acupunc.)                  OR 2.79 (CI 1.31-6.05)
                                                p<0.01 🟢

Same study           Auricular  Cancer MSK      NOT significant (p=0.37)
                     acupunc.   pain            🟢

Wu et al. 2026       EA         Knee OA         NOT significant 🟢
(FASEB J, n=180)
```

**Assessment:** COMT is CONDITION-SPECIFIC and MODALITY-SPECIFIC. It predicts EA response for cancer MSK pain but NOT auricular acupuncture for the same condition and NOT EA for knee OA. This rules out COMT as a universal acupuncture predictor and suggests the genetic-therapy interaction is more complex than a single gene → therapy response model. 🟡

**Cross-therapy relevance:** COMT affects pain sensitivity generally, so it likely modulates response to ANY pain-related therapy. But the specific interaction with EA (not auricular) suggests the effect operates through a mechanism engaged by EA but not by surface pressure — likely descending modulation or Han frequency-dependent opioids (C03 §3.3). Therapies sharing these mechanisms (B11 dry needling, potentially B03 deep massage) might show similar COMT effects. UNTESTED. 🔴

**GABRB3 rs4906902 — GABA-A Receptor β3 Subunit:**

```
STUDY                THERAPY    CONDITION       FINDING
───────────────────  ─────────  ──────────────  ─────────────────────────
Wu et al. 2026       EA         Knee OA         AG/GG: 69.7% response
(FASEB J, n=180)                                vs AA: 38.1%
                                                OR 3.85 (CI 1.17-12.61)
                                                p=0.026 🟢
```

**Assessment:** First RCT to identify GABRB3 as a predictor. The GABA-A receptor is directly relevant to acupuncture analgesia via descending inhibition and spinal cord interneurons. The large effect size (OR 3.85) is notable but from a single study. 🟡

**Cross-therapy relevance:** GABRB3 is particularly interesting for B16 yoga because of Streeter's GABA hypothesis (B16 §5.2 L4: yoga > metabolically-matched walking for brain GABA). If GABRB3 variants predict acupuncture response via GABAergic pathways, the SAME variants might predict yoga response via the GABA mechanism. This would be a powerful cross-therapy validation of the GABA pathway. UNTESTED. 🔴

**OPRM1 A118G (rs1799971) — Mu-Opioid Receptor:**

```
STUDY                THERAPY    CONDITION       FINDING
───────────────────  ─────────  ──────────────  ─────────────────────────
Wu et al. 2026       EA         Knee OA         NOT significant (p>0.05)
(FASEB J, n=180)                                🟢
```

**Assessment:** Biologically the most plausible candidate — acupuncture analgesia involves endogenous opioid release via mu-opioid receptors (Han frequency-dependent model, C03 §3.3). Yet direct evidence is NEGATIVE. Possible explanations: (a) acupuncture engages multiple opioid receptor types (mu, delta, kappa via Han frequencies) so single-receptor variation is diluted, (b) non-opioid mechanisms (adenosine, PROKR2) dominate over opioid in knee OA specifically, (c) sample size insufficient to detect a real but modest effect. 🟡

**Other Genetic Candidates (studied but negative or preliminary):**

```
GENE        PATHWAY                  STATUS FOR ACUPUNCTURE
──────────  ──────────────────────── ─────────────────────────────
BDNF        Neuroplasticity          NOT significant (Wu 2026) 🟢
Val66Met

TRPV1       Heat/capsaicin receptor  NOT studied for acupuncture.
variants                             B08 §8.3: predicts moxibustion
                                     heat sensitivity. 🟡

OXTR        Oxytocin receptor        NOT studied for any Track B
                                     therapy. B03 §8.1: plausible
                                     for CT-afferent-dependent
                                     therapies (light massage,
                                     acupressure). 🔴

FAAH        Fatty acid amide         NOT studied. B03 §8.1: affects
            hydrolase (endocannabinoid system tone)     endocannabinoid system response to deep massage
                                     (McPartland AEA↑168%). 🔴

Gut         Paraprevotella           Zhou 2023 (n=79): AUC=0.76
microbiota  (not strictly genetic)   for postpartum depression.
                                     ONE study. 🔴
```

#### §3.1.2 — Cross-Therapy Genetic Prediction Gap

The genetic prediction landscape reveals a stark asymmetry:

```
THERAPY    GENETIC STUDIES    GENETIC PREDICTORS FOUND    STATUS
─────────  ────────────────── ─────────────────────────── ─────────
B01        3+ RCTs            COMT (condition-specific),  🟢 Active
                               GABRB3 (OR 3.85)           research
B02-B16    ZERO               None                        🔴 Desert
```

This gap is NOT because genetics is irrelevant to other therapies — it exists because:
1. **Research infrastructure:** Only acupuncture has sufficient RCT volume AND a tradition of biomarker substudies to identify genetic predictors
2. **Funding:** NCCIH/NIH funds acupuncture mechanism research; no comparable funding stream for massage, chiropractic, or yoga genetics
3. **Mechanistic framework:** B01's 6-level integrated model (B01 §5) provides specific molecular targets (PROKR2, adenosine, opioids) against which genetic variants can be tested. Other therapies lack equivalent molecular specificity.

**Which therapies would benefit MOST from genetic prediction research?** Based on C03 mechanism specificity spectrum:

```
PRIORITY   THERAPY    RATIONALE
─────────  ─────────  ──────────────────────────────────────────────
HIGH       B04        endocannabinoid system-fascia connection: FAAH variants → AEA
                       metabolism → deep massage response. Fede 2016
                       CB1/CB2 in fascia = molecular target.

HIGH       B08        TRPV1 variants → heat sensitivity → moxibustion
                       dosing. B08 §8.3 already identifies this as
                       clinically relevant variation source.

HIGH       B16        GABRB3 → GABA pathway → yoga response. If
                       Streeter's GABA hypothesis confirmed, GABRB3
                       becomes the first cross-therapy genetic predictor.

MODERATE   B10        Joint mechanoreceptor variants (Freeman-Wyke
                       types) → proprioceptive reset response.
                       Theoretical but no candidate genes identified.

MODERATE   B03        OXTR → CT afferent response → light massage.
                       CT pathway well-characterized; OXTR polymorphisms
                       well-studied in social neuroscience.

LOW        B06/B12    Non-specific mechanism dominance → genetic
           B14        variation in SPECIFIC mechanisms is irrelevant
                       because these therapies don't engage specific
                       mechanisms meaningfully.
```

🟡 Priority ranking based on C03 mechanism analysis. 🔴 All cross-therapy genetic hypotheses are untested.

#### §3.1.3 — The Condition-Specificity Problem

The most important finding from B01's genetic data is NOT which gene predicts response — it is that the SAME gene predicts response for ONE condition but not another (COMT: cancer pain YES, knee OA NO) and for ONE modality but not another (COMT: EA YES, auricular NO).

This means genetic prediction cannot be simplified to "gene X → therapy Y works." The correct model is:

```
Gene variant × Therapy modality × Specific condition × Mechanism engaged = Prediction
```

This four-way interaction makes genetic prediction research exponentially harder. For B01 alone, with ~4 candidate genes × 3 modalities (manual/EA/auricular) × 8+ conditions = ~96 possible interactions to test. Across all 15 therapies, the combinatorial space is enormous. 🟡

**Implication for clinical translation:** Genetic prediction of therapy response will likely remain condition-specific and modality-specific for the foreseeable future. A "universal responder gene" for body-based therapy does not exist and probably cannot exist, because different therapies engage different mechanisms through different molecular pathways. 🟡

### §3.2 — Dose-Response Synthesis

#### §3.2.1 — The Dose-Response Landscape

"Dose" in body-based therapy is multi-dimensional — unlike pharmacology where dose = drug quantity, body therapy dose includes: stimulus intensity, duration, frequency, total sessions, and parameter selection. C01 identified 7 parameter modifiers; each is a dose dimension.

```
DOSE DIMENSION        KNOWN DOSE-RESPONSE?    KEY DATA
────────────────────  ────────────────────── ──────────────────────────
Pressure magnitude    PARTIALLY               C01 §3.2.1: depth-mechanism
                                               cascade (10N → 80N = 
                                               qualitatively different
                                               mechanisms). B03 pressure-
                                               dependent pathway model.

Needle depth          PARTIALLY               B11: SDN vs DDN (superficial
                                               = L2 gate control, deep =
                                               L1 LTR + L3 DNIC). B01:
                                               depth affects PROKR2 access.

Session frequency     SPARSE                  B01 Vickers: more sessions
                                               → better, but FLAT above
                                               threshold. B03 Cochrane
                                               2024: high-dose subgroup
                                               = clinically important.

Session duration      VERY SPARSE             B08: heat-sensitive moxa
                                               30-60 min (Chen Rixin).
                                               B15/B16: 12+ weeks needed.
                                               Most therapies: unknown.

Total sessions        SPARSE                  B01 ATC: 15-20 sessions
                                               typical RCT protocol.
                                               B15: 24-week trials.
                                               No optimization data.

EA frequency          WELL-CHARACTERIZED      B01: Han frequency-dependent
                                               opioids (2Hz=enkephalin,
                                               100Hz=dynorphin). 🟢

Temperature (B08)     PARTIALLY               B08 §8.3: TRPV1 activation
                                               42-43°C. Disease-state
                                               sensitization lowers
                                               threshold. Heat-sensitive
                                               moxa = thermal reactivity
                                               varies with pathology.

Speed (CT afferents)  WELL-CHARACTERIZED      C01 §3.2.2: 1-10 cm/s
                                               optimal for CT afferents.
                                               Outside range = different
                                               receptor profile. 🟢
```

#### §3.2.2 — The Vickers Dose-Response Pattern (B01)

The most informative dose-response data in Track B comes from the Vickers ATC individual patient data meta-analysis (B01 §9.4):

**Pattern:** Acupuncture shows clear dose-response for sessions (more sessions → better) but FLAT dose-response relative to sham (verum-sham difference does not increase with more sessions).

**Interpretation for individual variation:** This pattern means that the NON-SPECIFIC component (shared between verum and sham) is dose-responsive, while the SPECIFIC component (verum minus sham) is relatively constant. For individual patients:
- **High non-specific responders** (strong Evaluative Gates) → benefit from more sessions regardless of acupuncture specificity
- **Low non-specific responders** → only benefit from the specific component, which doesn't increase with more sessions
- This explains why some patients improve dramatically (high non-specific + specific) while others show modest improvement (specific only) or none (neither) 🟡

#### §3.2.3 — The Pressure-Threshold Interaction

C01's depth-mechanism cascade (§3.6 Pattern 2) reveals that dose-response in manual therapies is NOT linear but STEPPED — crossing a threshold activates a qualitatively different mechanism set:

```
THRESHOLD              MECHANISM GAINED              INDIVIDUAL VARIATION
─────────────────────  ───────────────────────────── ──────────────────────
~5-10N (CT afferents)  Affective touch, oxytocin     CT density varies
                                                      between individuals
                                                      (B03 §8.1 ①) → some
                                                      need lower threshold

~40-65N (endocannabinoid system)          Endocannabinoid activation    FAAH genotype affects
                        (AEA ↑168%, McPartland)       baseline endocannabinoid system tone →
                                                      individual threshold
                                                      variation. 🔴

~65-110N (descending   PAG activation, DNIC          Pain threshold varies
modulation)                                           enormously: central
                                                      sensitization →
                                                      lower threshold;
                                                      athletes → higher. 🟢

TRPV1 ~42-43°C         Heat-specific mechanisms      TRPV1 genetic variants
(thermal only)          (HSP, TRPV1 hub)              → threshold ±3-5°C.
                                                      Inflammation → PGE2
                                                      → TRPV1 sensitization
                                                      → lower threshold. 🟡
```

**Key insight:** The same "dose" (e.g., 50N pressure) crosses different thresholds in different people. A fibromyalgia patient with central sensitization may reach the descending modulation threshold at 30N, while an athlete may need 80N. The MECHANISM ENGAGED is determined by the interaction between the applied dose and the individual's threshold landscape. This means that optimal dose must be individualized — a standardized protocol will inevitably under-dose some patients and over-dose others. 🟡

#### §3.2.4 — Dose-Response Data Gaps

The most striking finding about dose-response across Track B is how LITTLE is known:

```
THERAPY    DOSE-RESPONSE EVIDENCE
─────────  ────────────────────────────────────────────────────────
B01        BEST: Vickers ATC (sessions), Han (EA frequency). But
            optimal session frequency, needle count, retention
            time = NOT optimized.
B03        Cochrane 2024: high-dose subgroup > low-dose for LBP.
            No systematic pressure-response data.
B15/B16    Duration matters (12+ weeks), but optimal frequency,
            session length, style matching = UNKNOWN.
B08        Chen Rixin heat-sensitive moxa: 30-60 min, but
            temperature dose-response not characterized.
B04-B14    Essentially NO dose-response data. Optimal session
            parameters are based on tradition, not evidence.
```

**This is the SINGLE LARGEST gap in body-based therapy research.** Without dose-response data, it is impossible to determine whether negative trials reflect true therapy inefficacy or simply inadequate dosing. A trial using 6 sessions of acupuncture when 15 are needed, or using 20N massage when 60N is the endocannabinoid system threshold, would find null results not because the therapy doesn't work but because the dose was wrong for the studied population. 🟡

### §3.3 — Expectation & Conditioning (Evaluative Gates)

#### §3.3.1 — Expectation as a Universal Variation Source

Expectation/belief modifies outcomes for EVERY therapy in Track B. This was identified in Track B §8 sections across all files that discussed psychological factors — effectively all 16. The most precise quantification comes from B01:

**Vase et al. 2013 (B01 §9.4):** Expectations account for up to **69.8% of pain variance** in acupuncture outcomes.

This single finding reframes the individual variation question: for subjective outcomes (pain, anxiety, nausea, well-being), more than half the variation between patients may be attributable to what they BELIEVE will happen, not to what physically DOES happen.

#### §3.3.2 — The Scaffolding Contribution Gradient

C03 §3.4 established that therapeutic scaffolding (elaborate theoretical frameworks with value but not validity) varies across therapies. C05 extends this analysis to estimate the FRACTION of clinical effect attributable to scaffolding/Evaluative Gates vs specific mechanisms for each therapy:

```
THERAPY    C03 SPECIFICITY   ESTIMATED EVALUATIVE    RATIONALE
           RANK              GATES CONTRIBUTION
─────────  ────────────────  ────────────────────── ──────────────────
B14        16 (least         ~80-95%                 ALL stated mechanisms
           specific)                                  CONTRADICTED. Effects
                                                      entirely from context.
                                                      🟡

B06        14                ~70-90%                 Zone theory UNSUPPORTED.
                                                      Ernst 2009 inverse
                                                      quality-result. Descamps
                                                      2023 fMRI null. 🟡

B12        15                ~60-80%                 Somatic near-zero. But
                                                      cognitive component
                                                      (exposure) is real CBT
                                                      mechanism, not pure
                                                      scaffolding. 🟡

B13        12                ~40-60%                 Physical stimulus real
                                                      (= B02 mechanisms) but
                                                      Kyo/Jitsu theory and
                                                      Hara diagnosis =
                                                      scaffold. 🔴

B02        9                 ~30-50%                 Retained B01 mechanisms
                                                      real but blinding
                                                      problem inflates
                                                      expectation contribution.
                                                      Self-efficacy for self-
                                                      treatment adds
                                                      psychological component.
                                                      🔴

B03        8                 ~25-40%                 CT afferents, gate
                                                      control, Crane
                                                      mechanotransduction
                                                      all 🟢. But cortisol
                                                      reappraisal (Moyer)
                                                      reduces expected
                                                      specific contribution.
                                                      🔴

B15        10                ~25-40%                 Specific mechanisms
                                                      real (fall prevention
                                                      58%, NNT≈3-4 against
                                                      active control). But
                                                      adherence/self-efficacy
                                                      = psychological factor.
                                                      🔴

B16        11                ~25-40%                 Depression SMD -0.52
                                                      but ≈ exercise for LBP.
                                                      Self-efficacy mediates
                                                      36% of disability (B16
                                                      §5.2). GABA unreplicated.
                                                      🔴

B11        7                 ~20-35%                 LTR, Shah milieu real.
                                                      But trigger point palpation
                                                      κ 0.2-0.4 means
                                                      targeting imprecision
                                                      inflates non-specific
                                                      contribution. 🔴

B07        6                 ~15-30%                 HO-1 pathway 🟢
                                                      (marks = mechanism).
                                                      Pain-only profile
                                                      matches narrow HO-1
                                                      mechanism. 🟡

B10        4                 ~20-35%                 Proprioceptive reset 🟢.
                                                      But subluxation theory
                                                      = scaffold. Flynn CPR
                                                      unvalidated. 🟡

B09        5                 ~15-30%                 HO-1 + HIF-1α (causal
                                                      DMOG reversal). TLF
                                                      structural verification.
                                                      🟡

B04        3                 ~15-25%                 endocannabinoid system-fascia 🟢 (3-study
                                                      chain). Structural-
                                                      Neural Dissociation
                                                      model. 🟡

B08        2                 ~15-30%                 TRPV1, HSP unique.
                                                      But BL67 breech
                                                      = mechanistically
                                                      inexplicable success.
                                                      🟡

B01        1 (most           ~15-30%                 PROKR2, adenosine,
           specific)                                  Han opioids all 🟢.
                                                      But verum ≈ sham
                                                      in many trials →
                                                      non-specific floor
                                                      (C03 §4.4) = ~SMD
                                                      0.2-0.4. 🟡
```

**Critical caveat:** These estimates are 🔴 Hypothesis for most therapies. The EXACT fraction is unknown for any therapy because no study has successfully isolated specific from non-specific effects with sufficient precision. The non-specific floor (C03 §4.4, ~SMD 0.2-0.4) provides a lower bound for Evaluative Gates contribution; the scaffolding spectrum (C03 §3.4) provides the ordinal ranking. The percentages are the synthesis of these two data sources. 🔴

#### §3.3.3 — Expectation Sources and Their Variation

Evaluative Gates are not a single construct — they comprise multiple interacting sources that vary independently between individuals:

```
EXPECTATION SOURCE         VARIATION BETWEEN INDIVIDUALS
────────────────────────── ──────────────────────────────────────────
Prior experience            First-time patients vs experienced:
                             B07 habituation effect, B10 reduced
                             anxiety with experience. First exposure
                             can go either way (anxiety↑ or
                             excitement↑). 🟡

Cultural alignment          Therapy's theoretical framework matches
                             patient's worldview: B13 Ki/meridians
                             resonates with East Asian patients,
                             B10 subluxation resonates with
                             chiropractic culture. Mismatch → reduced
                             engagement. B14 §8.1 ②. 🟡

Practitioner confidence     Confident practitioner → better outcomes
                             (therapeutic alliance). B14: practitioners
                             who believe they detect CSR are warmer
                             and more confident. B04 §8.2 ⑤:
                             B04 is MORE practitioner-dependent
                             than most Track B. 🟡

Therapeutic narrative       Elaborate theory → enhanced meaning →
                             stronger Evaluative Gates. B16:
                             self-efficacy mediates 36% of disability
                             (quantified). Dismantling scaffolding
                             might REDUCE effectiveness (C03 §3.4.3).
                             🟡

Treatment context           B14 §8.1 ⑤: quiet, warm, dim → better
                             relaxation. Time of day (evening →
                             more parasympathetic). B13: floor
                             position → vulnerable feeling for
                             some → sympathetic activation
                             COUNTERACTING treatment. 🟡

Touch comfort               B02 §8.1 ④, B03 §8.1 ④: trauma history,
                             autism spectrum, cultural norms → touch
                             aversion may override beneficial neural
                             pathways. B13 clothing barrier: reduces
                             CT engagement but INCREASES comfort for
                             touch-averse patients (trade-off). 🟡
```

#### §3.3.4 — The Sham Paradox as Individual Variation

C02 §4.6 resolved the sham paradox via a 3-layer model: encounter (~SMD 0.2-0.4) + contact (~SMD 0.1-0.3) + specific (~SMD 0.1-0.3). Individual variation in EACH layer produces different total responses:

```
PATIENT PROFILE           LAYER 1    LAYER 2    LAYER 3    TOTAL
                          (encounter) (contact)  (specific)
─────────────────────── ──────────  ─────────  ─────────  ──────
High-expectation          LARGE       LARGE      PRESENT    ★★★★
responder, touch-
positive

Low-expectation,          SMALL       LARGE      PRESENT    ★★★
touch-positive

High-expectation,         LARGE       SMALL      PRESENT    ★★★
touch-averse

Low-expectation,          SMALL       SMALL      PRESENT    ★★
touch-averse

Non-responder to          SMALL       SMALL      ABSENT     ★
specific mechanism
(gene/anatomy)
```

**The "non-responder" is often a low Layer 1 + low Layer 2 patient, not necessarily someone for whom the specific mechanism fails.** This reframes responder prediction: instead of asking "does the therapy work for this patient?" (binary), the question becomes "how much of each layer does this patient access?" (continuous, multi-dimensional). 🟡

---

### §3.4 — Anatomical/Physiological Variation

#### §3.4.1 — CT Afferent Density

CT (C-tactile) afferents are unmyelinated mechanoreceptors in hairy skin that respond optimally to gentle stroking at 1-10 cm/s. They mediate affective touch → oxytocin pathway (A01 §3, C01 §4.7). CT engagement is relevant to: B02 (light acupressure), B03 (massage), B04 (light techniques), B13 (but BLOCKED by clothing), B14 (cranial contacts), B15/B16 (self-touch minimal).

**Individual variation in CT system:**

```
VARIATION SOURCE          EFFECT ON THERAPY RESPONSE         EVIDENCE
────────────────────────  ───────────────────────────────── ─────────
CT fiber density          Higher density → stronger          🟡 Anatomical
(genetic)                  affective touch response →        variation
                           more oxytocin from light touch    documented

Body region               Hairy skin (arm, back) = CT       🟢 Well-
                           present. Glabrous skin (palm,     established
                           sole) = CT ABSENT. C04 §3.5.7:
                           foot sole = WEAKEST region.

Age                       CT density may decline with        🟡 Limited
                           aging → reduced affective touch   data
                           sensitivity in elderly

Neuropathy                Diabetic/other neuropathy →        🟡 Inferred
                           CT fiber damage → reduced         from nerve
                           affective touch response          pathology

Skin contact barrier      B13 Shiatsu through clothing       🟢 CT
                           → CT afferents CANNOT be          requires
                           activated. Real trade-off:        skin-to-skin
                           clothing reduces CT but           contact
                           increases comfort for
                           touch-averse patients.
```

**Cross-therapy implication:** Therapies where CT afferents are a MAJOR mechanism component (B03 light massage, B02 Jin Shin Jyutsu-style, B14 cranial contacts) will show MORE individual variation in outcomes driven by CT density than therapies where CT is MINOR (B01 needle, B07 cupping, B10 HVLA). For CT-dominant therapies, patients with low CT density or neuropathy may benefit from switching to moderate-pressure techniques that engage gate control (pressure-independent) instead. 🟡

#### §3.4.2 — Fascial Architecture

Fascia is the primary tissue target for B04 (A03 = PRIMARY) and a significant pathway for B01, B03, B07, B09, B11. Fascial architecture varies substantially between individuals:

```
VARIATION SOURCE          EFFECT ON THERAPY RESPONSE         EVIDENCE
────────────────────────  ───────────────────────────────── ─────────
Fascial thickness         Thinner fascia (women) → force     🟢 B04 §8.2
(sex difference)           attenuated before reaching        ② — sex
                           deep structures. Same external    differences
                           pressure = different tissue       documented
                           engagement.

Collagen I/III ratio      Sex hormones modulate ratio →      🟡 B04 §8.2
(hormonal)                 different viscoelastic properties  ④ — ERα on
                           → different thixotropic response.  fascia, A03 §7
                           Menstrual cycle effects plausible
                           but poorly studied.

Elastin content           Decreases with age → stiffer       🟢 Aging
(age-related)              fascia → potentially larger       effects well-
                           response to fascial mobilization  documented
                           (more to release) but also
                           higher fracture risk.

Athletic history          Trained individuals: denser, more   🟡 B04 §8.2
                           organized fascia → may need       ② — clinical
                           higher force for mobilization     observation
                           but have better structural
                           substrate for remodeling.

Chronic pathology         TLF thickening in chronic LBP      🟢 Langevin
                           (Langevin 2011: -56% shear        2011
                           strain) → MORE pathological
                           fascial substrate → potentially
                           GREATER benefit from fascial
                           therapy but also harder to
                           mobilize.

Hydration status          HA viscosity depends on hydration.  🟡 B04 §8.2
                           Dehydrated → more viscous ground   ③
                           substance → reduced thixotropic
                           response to treatment.

Subcutaneous fat          Greater adiposity → more pressure   🟡 B04, B13
(BMI)                      attenuation before reaching       §8.1 ③
                           deep fascia. B13 specifically
                           notes: same surface force →
                           different tissue engagement.

CB1/CB2 expression        Fede 2016: CB1/CB2 in fascial     🟡 One study
                           fibroblasts. Individual variation  — expression
                           in expression level → different    variation
                           endocannabinoid system response to deep pressure.    not mapped
```

**Endocannabinoid system activation threshold as a fascial variable:** C01 identified the endocannabinoid system threshold at ~40-65N (§4.6). This threshold is not fixed — it depends on fascial CB1/CB2 expression density, subcutaneous fat thickness (more fat = more pressure needed to reach deep fascia), and individual FAAH enzyme activity (faster AEA degradation = higher effective threshold). The combination of these factors means the endocannabinoid system threshold likely varies by a factor of 2-3× between individuals. 🔴

#### §3.4.3 — Nerve Distribution and Receptor Density

```
VARIATION SOURCE          EFFECT ON THERAPY RESPONSE         EVIDENCE
────────────────────────  ───────────────────────────────── ─────────
ABVN distribution         ABVN innervation of ear concha     🟡 B02 §8.1
(B02 auricular)            varies between individuals →       ⑤ — anatomy
                           optimal ear seed placement         variation
                           differs. Some people have more     documented
                           vagal-accessible concha area.

Dermatome overlap         A07 §7: dermatome boundaries       🟢 A07 —
zones                      vary ±1-2 segments between         well-
                           individuals. For segmentally       established
                           specific therapies (B01, B10),     anatomy
                           this means the "correct" point
                           for a given organ may shift by
                           1-2 vertebral levels.

PROKR2+ neuron            Liu 2021: 16.7% lumbar vs 6.1%     🟡 Mouse
density                    thoracic DRG in mice. Human        data only
                           distribution unknown. If
                           analogous, limb-point EA should
                           show STRONGER anti-inflammatory
                           response than trunk-point EA.
                           C04 P4 predicts this.

Mechanoreceptor           Type I-IV joint receptors           🟡 B10 §8.3
population (B10)           (Freeman-Wyke): facet              ① — age-
                           degeneration alters receptor        related
                           population → changed response      changes
                           to HVLA thrust.

Mast cell density         Varies by body region and           🟡 B11 §8.1
(B11)                      individual. Higher density at       ③ — known
                           acupoints (A05). Affects micro-    variation
                           wound inflammatory cascade
                           magnitude after needling.
```

#### §3.4.4 — The Autonomic Baseline Effect

Multiple Track B files independently identified autonomic baseline as a variation source (B03 §8.1 ③):

**Individuals with higher baseline sympathetic tone → GREATER parasympathetic shift response to therapy.** Individuals already parasympathetic-dominant → CEILING EFFECT.

This has cross-therapy implications because parasympathetic shift is a Tier 1 universal mechanism (C03 §3.2: ≥10/15 therapies). Every body-based therapy produces SOME parasympathetic shift — but the magnitude depends on where the patient starts. Chronically stressed patients (high sympathetic) show the LARGEST measurable changes, which partially explains why:
- Cortisol reduction appears largest in stressed populations (regression to mean, B03 §9.3 Moyer)
- HRV improvement is more dramatic in anxiety patients
- "Relaxation" therapies (B06, B14) produce measurable autonomic changes despite minimal specific mechanisms — because their patients seek them BECAUSE they are stressed (self-selection → large baseline → large shift)

This is NOT an artifact — the autonomic response is real. But it is a BASELINE-DEPENDENT variation source, not a therapy-specific one. 🟢

### §3.5 — Demographic Factors

#### §3.5.1 — Sex and Hormonal Factors

Sex differences affect therapy response through multiple pathways:

```
FACTOR                   PATHWAY                           THERAPIES AFFECTED
──────────────────────── ──────────────────────────────── ──────────────────
Fascial thickness         Women: thinner fascia, more       B04 (most), B03,
                           subcutaneous fat → force          B09, B11
                           attenuation before deep tissue.
                           🟢

Collagen ratio            Sex hormones → ERα on fascia →    B04, B03 (deep
                           different viscoelastic properties. techniques)
                           Menstrual cycle effects plausible.
                           🟡

Pain sensitivity          Women: generally lower pain        ALL pain-related
                           thresholds → same treatment       therapies
                           intensity perceived as MORE
                           intense. Central sensitization
                           more prevalent in women
                           (fibromyalgia F:M ≈ 7:1).
                           🟢

CT afferent response      Sex differences in affective       B03 light, B02,
                           touch response documented in      B14
                           social neuroscience. Relevance
                           to therapy response unstudied.
                           🟡

Hormonal cycling          Menstrual cycle → fluctuating      B04, potentially
                           fascial stiffness, pain           B01 (EA response
                           sensitivity, autonomic tone.      may vary with
                           NO Track B study has controlled    cycle)
                           for menstrual cycle phase.
                           🔴
```

**The most clinically significant sex difference:** Women's thinner fascia + lower pain threshold + higher central sensitization prevalence means that deep-tissue therapies (B04, B11 DDN) may need DIFFERENT dosing protocols for women vs men — lighter pressure reaching the same tissue depth, or alternative techniques (B04 MFR-indirect vs direct, B11 SDN vs DDN). No study has tested sex-specific dosing. 🔴

#### §3.5.2 — Age

```
FACTOR                   YOUNG (<18)                       ELDERLY (>65)
──────────────────────── ──────────────────────────────── ─────────────────
Neuroplasticity          Higher → potentially faster        Lower → slower
                          motor learning (B15/B16)          adaptation but
                                                            still present

Bone density             Not a concern                      Osteoporosis →
                                                            contraindication
                                                            for B10 HVLA,
                                                            deep B04, B07

Skin                     Thicker, more elastic              Thinner → more
                                                            fragile, bruises
                                                            easily (B07, B09)

CT afferents             Full density                       May decline →
                                                            reduced affective
                                                            touch response

Fascial                  More elastic, hydrated             Stiffer (↓elastin),
                                                            BUT potentially
                                                            more responsive
                                                            to mobilization

Safety                   B01: Shonishin preferred <7yr,     B10: lower force
                          fewer needles. B08: heat           (Activator, Drop).
                          calibration difficult.             B15: Chair Tai Chi.
                          B15: Baduanjin safest.             B16: Iyengar+props.
```

**The style-matching opportunity:** B15 and B16 are the ONLY Track B therapies with explicit style-selection tables for different age groups (B15 §8.2, B16 §8.3). This represents a maturity of clinical thinking absent from other therapies — most other Track B files discuss age only as a contraindication modifier, not as a positive selection criterion. 🟡

#### §3.5.3 — Chronicity

The most underappreciated demographic variable. Acute and chronic versions of the "same" condition engage DIFFERENT mechanisms and respond to DIFFERENT therapies:

```
                         ACUTE (<3 months)               CHRONIC (>3 months)
──────────────────────── ──────────────────────────────  ──────────────────
Dominant mechanism       Peripheral nociception,          Central sensitization,
                          inflammation                    descending modulation
                                                          failure, neuroplastic
                                                          changes

Optimal therapy match    Passive, input-based (B01,       Active, capacity-
(from C02 Active-        B02 P6 PONV, B03)               building (B15, B16)
Passive Divide §4.3)                                     OR deep specific
                                                          (B01 EA, B04)

Dose-response            Often single-session or          12+ weeks, sustained
                          short-course effective           practice, cumulative

Key variation factor     Inflammation level (acute         Central sensitization
                          phase) → determines which        level → determines
                          anti-inflammatory pathways       pain threshold →
                          are engaged                      determines dose
                                                           perception

Treatment goal           Resolution                       Management, functional
                                                           restoration, self-
                                                           efficacy development
```

**Central sensitization as a variation multiplier:** Chronic pain patients with central sensitization perceive ALL therapeutic stimuli as more intense. A 40N massage pressure that is "comfortable deep tissue" for an acute patient may be "painful" for a centrally sensitized fibromyalgia patient. This shifts the entire depth-mechanism cascade (C01 §3.6 Pattern 2) DOWNWARD — the same external force accesses deeper-level mechanisms because the neurological thresholds are lower. B04 §8.2 ① notes this directly: central sensitization → "moderate" pressure may feel "deep." 🟢

### §3.6 — Responder Phenotype Synthesis

#### §3.6.1 — Current Prediction Models

Only B01 acupuncture and B10 chiropractic have published responder prediction models:

```
MODEL                     METHOD          ACCURACY   VALIDATION    STATUS
────────────────────────  ──────────────  ─────────  ────────────  ──────
Yang et al. 2020          MRI + SVM       83%        No external   🟡
(migraine, n=41)          (structural)               validation

Gao et al. 2025           fMRI + SVM      85%        No external   🟡
(neck pain, n=80)         (functional)               validation

Yin et al. 2023           fMRI + SVM      88%        Independent   🟢
(dyspepsia, n=89+58)     (resting-state)             validation
                                                      R²=0.61

Chan et al. 2026          Scoping review  70-88%     Across 17     🟡
(36 articles)             (multiple)      range       studies

Flynn et al. 2002         Clinical exam   LR+ 24.4   External      🟡
(LBP → chiropractic,     (5 criteria)    (4/5 met)   validation
n=71)                                                 INCONSISTENT
```

**Key observations:**

1. **All B01 models are neuroimaging-based.** SVM classification of brain structural/functional features predicts who will respond to acupuncture with 70-88% accuracy. This is remarkable but clinically impractical — fMRI costs $500-2000 per scan, far exceeding acupuncture treatment cost. 🟢

2. **B10's clinical prediction rule is simpler but less reliable.** Flynn 2002 uses 5 bedside criteria (symptom duration, leg symptoms, hip ROM, lumbar hypomobility, fear-avoidance score). Elegant for clinical use, but external validation has been inconsistent (Nim et al. 2021: no reliable single predictor). 🟡

3. **B02-B09, B11-B16: ZERO prediction models.** The 14 remaining therapies have no published responder prediction data. B11 §8.1 ④ explicitly notes this gap. 🟢

#### §3.6.2 — A Multi-Factor Responder Model (Novel Synthesis)

Integrating all six variation domains from §3.1-§3.5, the following multi-factor model emerges for predicting individual therapy response:

```
RESPONSE = f(Genetic × Dose-Match × Expectation × Anatomy × Demographics × Chronicity)
```

Each factor operates through specific mechanisms identifiable from C01-C04:

```
FACTOR              MECHANISM PATHWAY            HOW IT MODIFIES RESPONSE
──────────────────  ──────────────────────────── ────────────────────────
Genetic profile     Receptor variants (COMT,      Shifts mechanism CAPACITY:
                     GABRB3, TRPV1, OXTR, FAAH)   some pathways work better
                                                    in some genotypes

Dose-match          C01 parameter modifiers ×      Determines which MECHANISMS
                     individual thresholds          are ACTUALLY activated at
                     (CT, endocannabinoid system, descending mod.)     the applied dose

Expectation         Evaluative Gates (C03 §3.4)    Modulates LAYER 1+2 of
profile              × scaffolding alignment        sham paradox model (C02
                     × practitioner confidence      §4.6). Can amplify or
                                                    suppress 50-70% of total
                                                    effect.

Anatomical          CT density, fascial thickness,  Determines TISSUE RESPONSE
substrate            nerve distribution, PROKR2     to stimulus: same force →
                     expression, BMI                 different mechanism
                                                    engagement per C01 matrix

Demographic         Sex (fascial, pain threshold),  Population-level SHIFTS in
context              age (neuroplasticity, safety),  multiple factors above.
                     hormonal status                 Not independent — modulates
                                                    anatomy + genetics

Chronicity          Acute vs chronic pathology,     Changes which MECHANISMS
                     central sensitization level     are therapeutically
                                                    relevant (C02 Active-
                                                    Passive Divide §4.3)
```

#### §3.6.3 — Predicted Responder Profiles for Key Therapy Families

Based on the multi-factor model, optimal responder profiles can be predicted for therapy families defined by their C03 mechanism specificity:

**Passive-Specific Therapies (B01, B04, B08, B10, B07, B09):**
- **Optimal responder:** Genetic: favorable receptor variants (COMT Met, GABRB3 AG/GG). Anatomy: PROKR2+ density high (B01), fascial pathology present (B04). Dose: matched to individual threshold. Chronicity: chronic > acute for lasting change. Expectation: culturally aligned.
- **Poor responder:** Val/Val COMT, low PROKR2 expression, acute condition, negative expectations, inadequate dose.
- 🔴 Predicted, not validated.

**Active Therapies (B15, B16):**
- **Optimal responder:** High motivation/self-efficacy (because adherence = THE critical variable, B15 §8.2). Chronic multi-system condition (matches multi-system mechanism). Social context (group practice). Prior movement experience (faster motor learning). Baseline balance deficit (B15) or depression (B16). NOT acute conditions.
- **Poor responder:** Low adherence, acute conditions, severe mobility/cognitive limitation, preference for passive intervention.
- 🟡 Partially supported by B15/B16 §8 positive/negative predictor data.

**Scaffolding-Dominant Therapies (B06, B12, B14):**
- **Optimal responder:** HIGH expectation/belief in therapy framework. Touch-positive. High baseline sympathetic tone (maximizes autonomic shift). Cultural alignment with theoretical framework. Preference for passive, gentle intervention.
- **Poor responder:** Skeptical, touch-averse, already relaxed (ceiling effect), preference for evidence-based. Note: "poor responder" here means poor response to the FULL package; the SPECIFIC mechanism contribution is too small to differentiate responders from non-responders.
- 🟡 Consistent with C03 scaffolding analysis and B14 §8.1 data.

#### §3.6.4 — The Responder Prediction Paradox

The therapies with the MOST specific mechanisms (Group A from C03: B01, B08, B04, B10) have the most IDENTIFIABLE responder profiles because their mechanisms create dimensions along which individuals can differ. But paradoxically, these same therapies also have the BROADEST responder populations because their universal mechanisms (C03 Tier 1: gate control, parasympathetic, opioids) work for almost everyone — the specific mechanisms add ADDITIONAL benefit for optimal responders but don't exclude others.

Conversely, therapies with the WEAKEST specific mechanisms (Group C from C03: B06, B12, B14) have the HARDEST to predict responder profiles because their effects are almost entirely non-specific — and non-specific responses are modulated by psychological factors that are harder to measure and more variable than biological ones.

**The practical implication:** Responder prediction is MOST useful for mechanistically rich therapies (where it can identify who gets the ADDITIONAL specific benefit) and LEAST useful for mechanistically weak therapies (where prediction reduces to "who has high expectations?" — a question better addressed by clinical conversation than by prediction algorithms). 🟡

---

## §4 — EMERGENT PATTERNS

Patterns discovered from the cross-reference that are NOT visible in individual Track B files.

### §4.1 — The Variation Data Inequality 🟢

Individual variation research is concentrated in B01 acupuncture to an extreme degree. B01 has genetic predictors (4+ genes), neuroimaging prediction (3+ models at 70-88%), and expectations research (69.8% pain variance). The remaining 15 therapies combined have essentially ZERO genetic data and ZERO prediction models.

This inequality is structural, not random:
- B01 has the largest research infrastructure (NCCIH funding, thousands of researchers, hundreds of universities)
- B01 has specific molecular targets (PROKR2, adenosine, Han opioids) against which variants can be tested
- B01 has the longest tradition of mechanism-focused research (dating to Han's 1980s work)

**Implication:** The variation landscape in Track B looks like B01 has uniquely rich variation sources, but this is an OBSERVATION ARTIFACT. Every therapy likely has comparable variation — it simply hasn't been studied. The genetic candidates from B03 §8.1 ⑤ (OXTR, COMT, FAAH) are as plausible as B01's candidates were before they were tested. 🟡

### §4.2 — The Practitioner-as-Variable Pattern 🟡

Multiple Track B files independently identified practitioner variation as a major confound:

```
THERAPY    PRACTITIONER VARIATION          PALPATION RELIABILITY
─────────  ────────────────────────────── ──────────────────────
B14        CO vs CST tradition; UII         CSR: r = 0.004
           Level I (~30 hrs) vs advanced.   (effectively random)
           Therapeutic relationship =
           main variable.

B11        trigger point identification varies.       κ = 0.2-0.4
           Training: 27-150 hrs (PT)        (poor to fair)
           vs 1,905-4,000 hrs (acup.)

B10        Technique selection varies.       Segmental palpation:
           7 technique variants.             κ = 0.02-0.42
           Subluxation diagnosis.

B04        "MORE practitioner-dependent      No reliability data
           than most Track B" (B04 §8.2     for fascial restriction
           ⑤, Gao 2026)                     assessment.

B13        Training: Japan 3-year vs         Hara diagnosis: NEVER
           weekend course.                    formally tested.

B06        Training school differences.       Zone palpation:
           "Intuitive" adjustments.           no reliability data.
```

**The pattern:** Practitioner diagnostic reliability is LOWEST for therapies whose stated mechanisms are weakest (B14 CSR r=0.004, B06 zone palpation untested) and MODERATE for therapies with stronger mechanisms (B11 trigger point κ=0.2-0.4, B10 segmental κ=0.02-0.42). B01 acupuncture uses fixed anatomical landmarks (cun measurement + palpation) with HIGHER reproducibility than palpation-only methods.

**This means:** The variation attributed to "individual patient response" in clinical practice is CONFOUNDED with practitioner diagnostic inconsistency. When two practitioners treat the "same" condition and get different results, it may be because they targeted different structures, not because the patients responded differently. 🟡

### §4.3 — The Adherence Divide 🟡

Active therapies (B15, B16) have a fundamentally different variation structure from passive therapies (B01-B14):

```
PASSIVE THERAPIES (B01-B14)             ACTIVE THERAPIES (B15, B16)
────────────────────────────────────── ─────────────────────────────────────
Variation = who RESPONDS to input      Variation = who MAINTAINS practice

Single-session effects measurable      Effects require 12+ weeks sustained
                                        practice to manifest

Dose delivered BY practitioner         Dose delivered BY patient — compliance
                                        and skill = uncontrollable variables

Non-adherence = missed appointment     Non-adherence = therapy doesn't work
                                        (→ B15 §8.2: "B15 only works if
                                        practiced regularly")

Key predictor: anatomy/genetics        Key predictor: motivation/self-
                                        efficacy/social context
```

**Implication:** For active therapies, the BIGGEST variation source is NOT biological but behavioral. Predicting who will ADHERE (motivation, social support, enjoyment, accessibility) may be more clinically valuable than predicting who will RESPOND (genetics, anatomy). This is a qualitatively different prediction problem requiring psychology, not physiology. 🟡

### §4.4 — The Threshold vs Linear Model 🟡

Dose-response in body-based therapy follows a THRESHOLD model, not a LINEAR model:

```
LINEAR MODEL                        THRESHOLD MODEL
(assumes pharmacological analogy)   (supported by Track B data)
──────────────────────────────────  ─────────────────────────────────
More dose → more effect              Crossing threshold → qualitatively
proportionally                       NEW mechanism activated

Double the pressure → double         40N: gate control.
the effect                           65N: endocannabinoid system activation (step change).
                                      No effect between thresholds.

Continuous dose-response curve       Stepped function with plateaus
                                      between thresholds

Individual variation = shifts        Individual variation = shifts
the curve up/down                    THRESHOLDS left/right

Implication: dose can be             Implication: dose must be matched
optimized continuously               to individual threshold landscape
```

**This explains several Track B phenomena:**

1. **Why B03 Cochrane found high-dose > low-dose:** High-dose crosses MORE thresholds (endocannabinoid system, descending modulation) that low-dose does not reach. The benefit is not from MORE of the same mechanism but from ADDITIONAL mechanisms.

2. **Why Vickers found flat verum-sham dose-response:** The specific mechanisms (Layer 3 of sham model) have a LOW threshold — one session crosses it. More sessions add non-specific benefit (Layers 1-2) but not more specific benefit.

3. **Why individual variation is so large:** Two patients with different threshold landscapes experience the SAME dose as activating DIFFERENT mechanism sets — they are receiving functionally different treatments.

### §4.5 — The Expectation-Specificity Inverse 🟡

Combining C03's specificity spectrum (§3.5) with the scaffolding contribution estimates (§3.3.2), a clear inverse relationship emerges:

The MORE mechanistically specific a therapy is, the LESS its outcomes depend on expectations.
The LESS specific, the MORE expectations dominate.

```
                          EXPECTATION CONTRIBUTION
  HIGH ──────────────────────────────────────────── LOW
  │                                                  │
  B14  B06  B12  B13  B02  B03  B15  B16  B11  B07  B10  B09  B04  B08  B01
  │                                                  │
  LOW ──────────────────────────────────────────── HIGH
                     MECHANISM SPECIFICITY
```

**Clinical implication:** For mechanistically specific therapies (B01, B04, B08), individual variation is BIOLOGICALLY driven — genetics, anatomy, and dose-matching matter. For non-specific therapies (B14, B06, B12), individual variation is PSYCHOLOGICALLY driven — expectations, therapeutic alliance, and cultural alignment matter. The optimal approach to predicting and improving outcomes is fundamentally different for each end of the spectrum. 🟡

### §4.6 — The Self-Treatment Modifier 🟡

Several therapies have self-treatment variants (B02 self-acupressure, B07 self-cupping, B12 self-tapping, B15/B16 self-practice, B04 self-MFR). Self-treatment introduces a unique variation profile:

**Advantages:**
- Self-dosing: patient adjusts to their own threshold landscape (B02 §8.2: "pain prompts reducing pressure" = self-limiting)
- Self-efficacy building: patient as agent → psychological benefit (B16: mediates 36% of disability)
- Adherence: home practice enables sustained dosing impossible with clinic visits

**Disadvantages:**
- Point location imprecision: B02 §8.1 ①: self-administered = higher variance, though larger contact area (3-4 cm²) is more forgiving than needle (0.05 mm²)
- Pressure calibration: B02 §8.1 ②: same instruction ("press firmly") → wide force range
- No practitioner scaffolding: loses therapeutic alliance, narrative, confidence enhancement

**Net effect on variation:** Self-treatment INCREASES technical variation (imprecise location/pressure) but DECREASES biological variation dependency (patient self-adjusts to their own anatomy). The trade-off favors self-treatment for therapies with broad mechanism profiles (B15, B16, B03 self-massage) and disfavors it for therapies requiring precise targeting (B01, B11). 🟡

---

## §5 — PREDICTIONS & TESTABLE HYPOTHESES

Each prediction is 🔴 Hypothesis unless noted.

### P1 — GABRB3 Predicts Yoga Response for Depression

**Prediction:** GABRB3 rs4906902 AG/GG genotype (OR 3.85 for EA acupuncture, Wu 2026) will predict yoga response for depression with similar or larger effect size, because both acupuncture analgesia and yoga's depression benefit engage GABAergic pathways (Han opioids cross-talk with GABA; Streeter GABA hypothesis).

**Confirm:** RCT of yoga for depression, stratified by GABRB3 genotype, shows AG/GG response rate ≥60% vs AA ≤40% (effect size comparable to Wu 2026).
**Refute:** No genotype-outcome association, suggesting GABA pathway involvement in yoga operates through a different receptor subtype or that Streeter's hypothesis is incorrect.

### P2 — FAAH Genotype Predicts Deep Massage Response

**Prediction:** FAAH rs324420 (C385A) carriers (slower AEA metabolism → higher baseline endocannabinoid tone) will show REDUCED response to deep tissue massage (B04), because their endocannabinoid system is already partially activated at baseline, reducing the relative increase from pressure-induced AEA release (McPartland 2005: AEA ↑168%).

**Confirm:** Deep massage RCT stratified by FAAH genotype: C385A carriers show smaller AEA increase and smaller pain reduction (SMD difference ≥0.3).
**Refute:** No genotype-outcome association, suggesting endocannabinoid system contribution to deep massage is smaller than the McPartland-Fede-Lindgren chain implies, or FAAH-independent endocannabinoid system mechanisms dominate.

### P3 — Individualized Dosing Outperforms Standardized Protocols

**Prediction:** A massage protocol that adjusts pressure to each patient's individual endocannabinoid system threshold (measured by real-time AEA biomarker or pain threshold proxy) will produce larger effect sizes than a standardized-pressure protocol for chronic LBP, because individual threshold variation means a fixed dose inevitably under-doses some patients and over-doses others (§3.2.3).

**Confirm:** Individualized-dose group shows ≥0.3 SMD advantage over standardized-dose group for pain at 4 weeks.
**Refute:** No significant difference, suggesting threshold variation is clinically irrelevant or the proxy measurement is inadequate.

### P4 — Expectation Contribution Is Measurable by Therapy Position

**Prediction:** Therapies at the non-specific end of the specificity spectrum (B14, B06) should show LARGER patient-expectation correlations (r > 0.5 between pre-treatment expectation rating and outcome) than therapies at the specific end (B01, B04), because specific mechanisms operate independently of belief while non-specific mechanisms are expectation-dependent.

**Confirm:** Multi-therapy observational study measuring pre-treatment expectations across ≥4 therapies (one from each end of the spectrum) shows expectation-outcome r ≥ 0.5 for B14/B06 and r ≤ 0.3 for B01/B04.
**Refute:** Expectation-outcome correlations are similar across all therapies, suggesting either expectations modulate specific mechanisms too, or non-specific mechanisms are expectation-independent.

### P5 — Multi-Factor Model Outperforms Single-Gene Prediction

**Prediction:** A responder prediction model combining genetics (COMT + GABRB3) + anatomy (fascial thickness, CT density) + psychology (expectation rating, pain catastrophizing) + demographics (age, sex, chronicity) will achieve ≥90% accuracy for B01 acupuncture response prediction, exceeding the best single-modality model (Yin 2023: 88% with fMRI alone). The multi-factor model adds biological variation (genetics, anatomy) that fMRI captures indirectly through brain structure correlates.

**Confirm:** Multi-factor model ≥90% in independent validation cohort (n≥100).
**Refute:** Multi-factor model does not improve over fMRI alone, suggesting brain-based prediction already captures downstream effects of genetics/anatomy/psychology.

### P6 — Practitioner Reliability Training Improves Outcomes

**Prediction:** Standardized palpation training for B11 dry needling (targeting trigger point identification κ ≥ 0.6, up from current 0.2-0.4) will improve clinical outcomes by ≥0.2 SMD, because more reliable targeting → more consistent mechanism engagement → less practitioner-induced variation in outcomes.

**Confirm:** Trained group (κ ≥ 0.6) shows ≥0.2 SMD advantage over standard-training group for trigger point pain outcomes.
**Refute:** No outcome difference despite improved reliability, suggesting trigger point location precision matters less than other treatment parameters (depth, number of LTRs, session duration).

---

## §6 — LIMITATIONS & GAPS

### §6.1 — Methodological Limitations

1. **B01-centric data.** The genetic, neuroimaging, and expectation evidence comes overwhelmingly from B01 acupuncture. Extending these findings to other therapies requires assumptions about mechanism overlap that have not been tested.

2. **Scaffolding contribution estimates are speculative.** The §3.3.2 gradient assigns approximate percentage ranges to each therapy's Evaluative Gates contribution. These are SYNTHESIS estimates based on the C03 specificity spectrum and the non-specific floor, not measured values. No study has directly quantified the scaffolding fraction for any therapy.

3. **Threshold model is inferred, not measured.** The stepped dose-response model (§4.4) is consistent with Track B data but has not been tested with systematic dose-escalation protocols measuring biomarker transitions at predicted thresholds.

4. **Responder profiles are predicted, not validated.** The multi-factor responder model (§3.6.2) and therapy-family profiles (§3.6.3) are novel synthesis. None has been tested in a prospective study.

5. **Cross-therapy genetic hypotheses are entirely untested.** The priority rankings for genetic research (§3.1.2) are based on mechanism plausibility, not evidence. Whether FAAH predicts massage response or GABRB3 predicts yoga response is unknown.

### §6.2 — Missing Data

1. **Genetic data for 14/15 therapies.** Only B01 has genetic predictor data. The entire cross-therapy genetic analysis is extrapolation.

2. **Dose-response optimization for all therapies.** Optimal session parameters (pressure, frequency, duration, total course) are unknown for essentially all Track B therapies. Without dose-response data, we cannot determine whether negative trials reflect inadequate dosing or true inefficacy.

3. **CT afferent density mapping in therapy context.** CT density varies between individuals and body regions, but no study has measured whether CT density predicts therapy response for light-touch therapies.

4. **PROKR2 distribution in humans.** Liu 2021 data is from mice. Whether human PROKR2+ neuron distribution matches the murine pattern is assumed but not confirmed. This affects all predictions about acupoint-specific variation.

5. **Fascial CB1/CB2 expression variation.** Fede 2016 established that CB1/CB2 exist in fascial fibroblasts, but inter-individual expression variation has not been mapped. This limits predictions about endocannabinoid system threshold variation.

6. **Menstrual cycle effects on therapy response.** No Track B study has controlled for menstrual cycle phase. Given documented hormonal effects on fascial stiffness, pain sensitivity, and autonomic tone, this is a significant uncontrolled variable.

7. **Active therapy adherence predictors.** B15/B16 identify adherence as the key variation source but provide no validated adherence prediction models.

---

## §7 — OPEN QUESTIONS

Questions RAISED BY the cross-reference analysis that only become visible when comparing individual variation across therapies.

**Q1 (CRITICAL). Is there a cross-therapy genetic predictor?** GABRB3 predicts B01 acupuncture response via GABAergic pathways. If Streeter's GABA hypothesis for B16 yoga is correct, GABRB3 should predict yoga response too. If confirmed, this would be the FIRST genetic predictor validated across two different body-based therapies — demonstrating that genetic prediction follows MECHANISM pathways, not therapy identity. This single finding would transform the field.

**Q2. Can clinically practical responder prediction replace neuroimaging?** B01's neuroimaging models (83-88% accuracy) require $500-2000 fMRI scans. Can a bedside multi-factor model (genetic swab + clinical questionnaire + demographic data) achieve comparable accuracy at lower cost? B10's Flynn CPR (5 bedside criteria, LR+ 24.4) shows the concept is feasible but needs reliable validation.

**Q3. What is the true endocannabinoid system activation threshold, and how much does it vary?** C01 estimates ~40-65N, but this is inferred from the gap between light-touch studies (no endocannabinoid system change) and deep-tissue studies (AEA ↑168%). The actual threshold, its biological determinants (FAAH genotype, fascial CB density, BMI), and its inter-individual range are unknown. This is the most important dose-response question in manual therapy.

**Q4. Does the expectation-specificity inverse hold under controlled testing?** §4.5 predicts that expectation-outcome correlations are larger for non-specific therapies than for specific therapies. If this inverse is NOT found — if expectations modulate even highly specific therapies equally — then the distinction between "specific" and "non-specific" mechanisms is less sharp than C03's framework implies.

**Q5. Is practitioner diagnostic reliability a solvable problem?** Trigger point palpation (κ 0.2-0.4), segmental palpation (κ 0.02-0.42), and CSR detection (r=0.004) all show poor reliability. Can training improve reliability above clinically meaningful thresholds (κ > 0.6)? If NOT, then palpation-based targeting may be fundamentally imprecise, and therapy selection should prioritize area-based or patient-guided (Ashi) approaches over point-specific protocols.

**Q6. Does central sensitization create a "universal responder" phenotype?** Centrally sensitized patients have lower thresholds for ALL mechanisms → they access deeper-level mechanisms at lower doses. This might make them respond to a WIDER range of therapies (more mechanisms activated at any dose) — or alternatively, their altered pain processing might make them resistant to therapies targeting peripheral mechanisms. Which is it?

**Q7. Can the active-therapy adherence problem be solved?** B15/B16 are among the most effective therapies but only work with sustained practice. Can technology (apps, gamification, wearables), social structures (group classes, accountability partners), or clinical psychology (motivational interviewing, habit formation) reliably improve adherence enough to increase population-level effectiveness?

**Q8 (CAPSTONE). Can a unified responder prediction system work across therapies?** The ultimate goal: given a patient profile (genetics + anatomy + psychology + demographics + condition), predict which of the 15 Track B therapies will produce the best outcome for THAT specific patient. This requires: (a) the multi-factor model (§3.6.2) validated for each therapy, (b) cross-therapy genetic predictors confirmed (Q1), (c) dose-response optimization completed (§3.2.4). Current status: far from achievable but the FRAMEWORK exists in this document.

---

## §8 — CROSS-REFERENCES

### §8.1 — Track A Files Referenced

| File | Concept Used in C05 |
|------|-------------------|
| A01 PNS | CT afferent density variation (§3.4.1), fiber type thresholds (§3.2.3), TRPV1 genetic variation |
| A02 ANS | Autonomic baseline effect (§3.4.4), parasympathetic shift ceiling, Zone D breathing for active therapies |
| A03 Fascia | Fascial architecture variation (§3.4.2): ERα, collagen ratio, elastin aging, CB1/CB2 expression (Fede 2016), TLF pathology (Langevin 2011) |
| A04 Vascular | HO-1 pathway — individual variation in capillary fragility (B07 §8.1) |
| A05 Neuroimmune | Mast cell density variation at acupoints (§3.4.3), myokine pathway for active therapies |
| A06 Endocrine | endocannabinoid system threshold variation (§3.4.2), Han frequency-dependent opioids (genetic interaction), cortisol reappraisal (Moyer → autonomic baseline) |
| A07 Somatotopic | Dermatome overlap zones (§3.4.3): ±1-2 segment individual variation |
| A08 MSK | Freeman-Wyke receptor types (B10 §8.3), trigger point-acupoint overlap (B11 palpation reliability) |
| A09 Meridian | PROKR2 expression variation (§3.4.3), dynamic acupoint phenomenon (Kim 2017 — variation = feature not bug) |

### §8.2 — Track B Files Referenced

All 15 Track B §8 sections were read in full. Key contributions by therapy:

| Therapy | Key §8 Contribution to C05 |
|---------|---------------------------|
| B01 | RICHEST: genetics (COMT, GABRB3, OPRM1), neuroimaging prediction (83-88%), expectations (69.8%), safety |
| B02 | Point location accuracy (self vs practitioner), pressure calibration, OXTR hypothesis, ABVN anatomy variation |
| B03 | CT afferent density variation, autonomic baseline, genetic candidates (OXTR, FAAH untested) |
| B04 | Fascial thickness (sex), endocannabinoid system-fascia CB1/CB2, hydration, sex hormones (ERα), practitioner skill |
| B06 | Practitioner/protocol variation, expectation dominance, no standardized protocol |
| B07 | Capillary fragility, mark response variability (same protocol → different marks = tissue pathology indicator) |
| B08 | TRPV1 genetic variation (heat threshold), disease-state TRPV1 sensitization (PGE2) |
| B09 | Sha appearance variability (MORE sha = MORE pathology), child abuse misidentification |
| B10 | Clinical prediction rules (Flynn 2002), pain catastrophizing, hypermobility, age-related changes, VBA safety |
| B11 | trigger point palpation reliability (κ 0.2-0.4), tissue characteristics, NO responder prediction, 53% career nerve puncture |
| B12 | Delivery mode variation, psychological risk from self-guided exposure, treatment avoidance risk |
| B13 | Practitioner skill variation (training 3-year vs weekend), body composition, clothing barrier → CT blocked |
| B14 | Psychological receptivity dominant, suboccipital state = only specific predictor, infant safety concern |
| B15 | Positive predictors (baseline deficit, multi-system condition), negative (acute, low adherence), style selection table, SAFEST |
| B16 | Style selection by patient profile, hypermobility + Yin contraindication, hot yoga risk without additive benefit |

### §8.3 — Track C Dependencies and Connections

- **C01 → C05:** C01's parameter modifiers (§3.2) provide the dose dimensions along which individuals vary. The depth-mechanism cascade (C01 §3.6 Pattern 2) becomes the threshold model (§4.4) when individual variation in thresholds is considered. CT afferent engagement pattern (C01 §4.7) explains CT density as a variation source (§3.4.1).

- **C02 → C05:** C02's Active-Passive Divide (§4.3) explains why active vs passive therapies have fundamentally different variation structures (§4.3 Adherence Divide). The sham paradox 3-layer model (C02 §4.6) becomes the basis for understanding how expectations modulate each layer differently per patient (§3.3.4). C02's condition-therapy matrix provides the outcome data against which responder predictions can eventually be tested.

- **C03 → C05:** C03's specificity spectrum (§3.5) is the backbone of the expectation-specificity inverse (§4.5). C03's scaffolding analysis (§3.4) provides the framework for the scaffolding contribution gradient (§3.3.2). C03's universal mechanisms (Tier 1, ≥10/15) explain the non-specific floor that makes ALL patients respond somewhat. C03's unique mechanisms (15 therapy-exclusive) create the biological variation dimensions studied in §3.1 (genetics) and §3.4 (anatomy).

- **C04 → C05:** C04's body region hierarchy explains regional variation in response (face > ear > foot). C04's dynamic acupoint phenomenon (Kim 2017, §4.3) reframes individual variation as a FEATURE: the "right" treatment location varies by patient and disease state, not just by anatomy. PROKR2 expression variation (C04 §3.4, P4) connects to genetic variation in §3.1 and anatomical variation in §3.4.3.

- **C05 → Phase 4 (Track D):** C05's multi-factor responder model connects to Human-Predictive-Drive's Evaluative Gates: the expectation component (§3.3) IS the Human-Predictive-Drive contribution to body therapy outcomes. The active-therapy adherence question (§4.3, Q7) connects to Human-Predictive-Drive's Zone D (voluntary ANS regulation) and Executive function (sustained behavior change). The Responder Prediction Paradox (§3.6.4) connects to Human-Predictive-Drive's prediction error system: patients with strong expectation-prediction loops show larger non-specific responses.

### §8.4 — Human-Predictive-Drive Connection Points

- **Evaluative Gates:** The scaffolding contribution gradient (§3.3.2) quantifies Human-Predictive-Drive's Evaluative Gates contribution per therapy. This is the most direct Body-Signal-Architecture-Human-Predictive-Drive connection: Evaluative Gates = the brain-side mechanism underlying individual variation in non-specific response.
- **Zone D Bridge:** Active therapies (B15, B16) access Zone D via voluntary breathing. The adherence divide (§4.3) means Zone D access depends on sustained practice — connecting body therapy to Human-Predictive-Drive's executive function (sustaining voluntary behavior).
- **Prediction Error:** The sham paradox (§3.3.4) operates through prediction error: high-expectation patients have stronger prediction → experience larger prediction error when therapy stimulus arrives → larger Evaluative Gates activation. This connects body therapy variation to Human-Predictive-Drive's core predictive processing framework.
- **Direct-State Processing:** For psychological conditions (depression, anxiety), the responder profile depends on capacity for interoceptive awareness and emotional processing — Human-Predictive-Drive Direct-State mechanisms that determine who can access the therapeutic benefits of body-based interventions for mental health.

### §8.5 — Citations for New Sources

No new primary sources introduced in C05. All citations reference sources already documented in Track A (A01-A09) and Track B (B01-B16) files. C05 is purely synthetic — its analytical products derive from cross-referencing individual variation data across existing files with the frameworks established in C01-C04.
