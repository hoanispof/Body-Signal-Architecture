---
title: Condition-Response-Map
id: C02
version: 0.1
status: DRAFT
scope: Which conditions respond to which body-based therapies, at what evidence level, and WHY — connecting clinical outcomes to mechanisms via C01+C03+C04
sources: [A01-A09, B01-B16, C01, C03, C04]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# Condition-Response-Map

## §1 — PURPOSE & METHODOLOGY

### §1.1 — Why This Cross-Reference Exists

Individual Track B files each document clinical effects for their therapy (§4) and assess evidence quality (§9). But these profiles are therapy-centric — they answer "what does acupuncture treat?" not "what treats chronic low back pain?" Since multiple therapies claim efficacy for the same conditions (chronic LBP appears in 12/16 therapies), and some conditions respond to seemingly unrelated therapies (anxiety improves with acupuncture, massage, EFT, Tai Chi, and yoga), the therapy-level analysis obscures a more fundamental question:

**For a given condition, which therapy has the strongest evidence — and WHY does it work?**

This matrix answers that question by inverting the Track B perspective: instead of therapy → conditions, it maps condition → therapies, creating an analytical product that cannot exist in any individual Track B file. The mechanism-based explanation (§3.4) connects clinical outcomes to the unified framework from C01 (stimulus types), C03 (shared/unique mechanisms), and C04 (location specificity).

### §1.2 — Data Sources

- **Clinical effects:** All 16 Track B §4 (Documented Clinical Effects) sections, read in full
- **Evidence quality:** All 16 Track B §9 (Evidence Assessment) sections, read in full
- **Stimulus context:** C01 (Stimulus-Pathway-Matrix — which stimulus activates which pathways)
- **Mechanism context:** C03 (Common-Mechanisms — shared vs unique mechanisms, specificity spectrum)
- **Location context:** C04 (Location-Specificity-Map — body region pathway hierarchy, validated vs unvalidated location systems)

### §1.3 — Methodology

**Condition extraction.** Every condition mentioned in every Track B §4 was cataloged with: evidence level, effect size (when available), key citation, and comparator type (sham/active/waitlist/no treatment).

**Evidence level standardization.** Track B files used varying evidence terminology. All evidence levels have been normalized to a 3-point scale for the matrix:

```
🟢 STRONG    SR/MA with consistent positive results AND/OR guideline endorsement.
             Typically: Cochrane review, ATC IPD meta-analysis, or VA Evidence Map
             at moderate-high certainty. Effect size reported.

🟡 MODERATE  Multiple RCTs with positive direction but limitations: small samples,
             mixed results, low GRADE certainty, weak comparators, high heterogeneity.
             Positive signal but insufficient for strong recommendation.

🔴 WEAK      Case reports, uncontrolled studies, preliminary RCTs, or contradicted by
             better-quality evidence. Traditional claims without modern validation.
             Also: positive vs waitlist only, null vs sham.

—            No evidence or not studied for this therapy-condition pair.
```

**Comparator hierarchy.** Effect sizes are interpreted differently based on comparator:
- vs sham/placebo: most informative (isolates specific effect)
- vs active control: informative for clinical decision-making
- vs waitlist/no treatment: INFLATES effect sizes by 0.3-0.8 SMD (includes non-specific effects)
- vs usual care: intermediate but variable

**Head-to-head extraction.** Every direct therapy comparison mentioned in Track B §4 or §9 was cataloged separately (§3.3).

**Mechanism mapping.** For each condition-therapy pair with 🟢 or 🟡 evidence, the mechanism chain was traced through C01 → C03 → C04 to explain WHY the therapy works for that condition (§3.4).

---

## §2 — TAXONOMY / CLASSIFICATION

### §2.1 — Condition Domain Classification

Clinical conditions extracted from 16 Track B files organized into 12 domains, ordered by coverage across therapies (most therapies → fewest):

```
DOMAIN                          CONDITIONS INCLUDED                   THERAPIES WITH
                                                                      ANY EVIDENCE
─────────────────────────────── ───────────────────────────────────── ─────────────
1. MUSCULOSKELETAL PAIN         Chronic LBP, neck pain, knee OA,      14/16
                                 fibromyalgia, trigger point/myofascial,
                                 shoulder, lateral epicondylitis,
                                 plantar fasciitis, tendinopathy

2. PSYCHOLOGICAL                Depression, anxiety, PTSD,             10/16
                                 phobias, stress

3. HEADACHE                     Migraine, TTH, cervicogenic            7/16

4. SLEEP                        Insomnia, sleep quality                8/16

5. AUTONOMIC/VISCERAL           PONV, CINV, hypertension,              7/16
                                 IBS/digestive

6. OBSTETRIC/GYNECOLOGICAL      Breech, labor pain, dysmenorrhea,      6/16
                                 breast engorgement, perimenopausal

7. CANCER SUPPORTIVE            Cancer pain, fatigue, QoL,             7/16
                                 chemo side effects

8. NEUROLOGICAL/BALANCE         Fall prevention, Parkinson's,          4/16
                                 cognitive/MCI, post-stroke

9. SPORTS/RECOVERY              DOMS, sports performance              4/16

10. METABOLIC                   T2DM, hypertension, obesity            3/16

11. RESPIRATORY                 COPD, asthma, allergic rhinitis        4/16

12. INFLAMMATORY/IMMUNE/OTHER   Hepatitis B, herpes zoster,            5/16
                                 urticaria, preterm growth
```

### §2.2 — Why These Domains

The 12 domains reflect natural clustering based on: (a) pathophysiology — conditions sharing underlying mechanisms group together, (b) evidence patterns — therapies effective for one condition in a domain tend to show signals for others, (c) clinical decision-making — practitioners choose between therapies within domains, not across them.

**Notable boundary decisions:**
- Fibromyalgia is classified under MSK Pain despite significant psychological and autonomic components, because Track B evidence primarily targets pain/function outcomes.
- Hypertension appears in BOTH Autonomic/Visceral AND Metabolic. In the matrix, it is listed under Metabolic because the strongest evidence (B15, B16) comes from sustained lifestyle interventions, not acute autonomic modulation.
- Cancer supportive care is separated from the conditions it targets (pain, fatigue, nausea) because the evidence base, population, and clinical context differ substantially.

### §2.3 — Evidence Tier Classification (Therapy-Level)

Distinct from condition-level evidence (🟢/🟡/🔴), therapies were classified into 5 evidence TIERS reflecting overall research infrastructure quality. This classification emerged organically across Track B and reflects STRUCTURAL features of the evidence base, not just clinical results.

```
TIER   CRITERIA                                      THERAPIES
─────  ───────────────────────────────────────────── ─────────────────────────
  1    Large RCT base (300+), multiple Cochrane       B01 Acupuncture (862 SRs,
       reviews, top-tier publications (NEJM/JAMA/       56 Cochrane)
       BMJ/Lancet), guideline endorsement,            B03 Massage (400+ RCTs,
       active comparator trials                         8 Cochrane, VA Evidence Map)
                                                      B15 Tai Chi (210+ SRs,
                                                        NEJM/BMJ/JAMA)
                                                      B16 Yoga (312+ RCTs,
                                                        51+ SRs, Cochrane)

  2    Moderate RCT base (50-300), some Cochrane      B10 Chiropractic (Cochrane,
       or equivalent SRs, some guideline                ACP 2017)
       endorsement, moderate quality                  B02 Acupressure (642 RCTs,
                                                        PONV guideline)
                                                      B04 Deep Tissue (~85 RCTs,
                                                        landmark mechanism)
                                                      B11 Dry Needling (~80 SRs,
                                                        NICE NG193)

  3    Limited RCTs (15-50), no Cochrane completed,   B07 Cupping (72 RCTs,
       predominantly low quality, cultural               no completed Cochrane)
       concentration                                  B08 Moxibustion (breech
                                                        exception, rest low)
                                                      B09 Gua Sha (~15-20 RCTs,
                                                        strong mechanism)

  4    RCTs exist but quality UNDERMINED by            B06 Reflexology (50-80 RCTs
       structural problems: inverse quality-             but inverse quality-outcome,
       outcome correlation, extreme COI, waitlist        null vs sham)
       controls dominant, no guideline endorsement    B12 EFT (69+ RCTs but
                                                        extreme COI, waitlist
                                                        controls, Spielmans 2020)

  5    Near-zero RCTs or foundational claims           B05 Dien Chan (~0 RCTs)
       CONTRADICTED. Evidence base too weak for        B13 Shiatsu (1 proper RCT)
       meaningful clinical assessment                  B14 Craniosacral (theory
                                                        contradicted, CSR r=0.004)
```

**Key distinction: Tier 4 vs Tier 5.** Both are weak, but for different reasons. Tier 4 therapies HAVE evidence that fails quality standards (B06 inverse quality-outcome, B12 COI/waitlist). Tier 5 therapies LACK evidence entirely (B05, B13) or have their theoretical basis CONTRADICTED (B14). Tier 4 = weak positive evidence; Tier 5 = insufficient or negative evidence. 🟡

**Important caveat:** Evidence tier reflects RESEARCH INFRASTRUCTURE quality, not therapeutic value. B05 Dien Chan (Tier 5) may be effective — eTNS at the same trigeminal territory is FDA-approved — but no RCTs exist to assess it. B14 Craniosacral (Tier 5) produces real relaxation effects despite contradicted theory. Tier = confidence in our KNOWLEDGE, not therapy WORTH. 🟡

---

## §3 — MAIN ANALYSIS

### §3.1 — Condition Taxonomy Detail

Each condition domain is characterized by its dominant pathophysiology, which predicts which mechanism profile (C03) and stimulus type (C01) should be most effective.

```
DOMAIN                    DOMINANT PATHOPHYSIOLOGY          PREDICTED OPTIMAL MECHANISMS
───────────────────────── ──────────────────────────────── ────────────────────────────────
MSK Pain (chronic)        Central sensitization,            Descending modulation (L3),
                           peripheral nociception,          gate control (L2), opioids (L5),
                           motor dysfunction                endocannabinoid system (L1), neuroplasticity (L4)

MSK Pain (acute/DOMS)     Peripheral inflammation,         Anti-inflammatory (L1), gate
                           tissue damage                    control (L2), vasodilation (L1)

Psychological             HPA dysregulation, limbic        Vagal tone (L3), cortisol mod
                           hyperactivation, low GABA,       (L5), evaluative gates (L6),
                           rumination                       self-efficacy (L6), GABA (L4?)

Headache                  Trigeminal-vascular,             Trigeminal modulation (L3),
                           cervicogenic, central            descending inhibition (L3),
                           sensitization                    gate control (L2), DNIC (L3)

Sleep                     Autonomic imbalance,             Parasympathetic shift (L3),
                           cortical hyperarousal,           cortisol modulation (L5),
                           HPA dysregulation                melatonin/GABA (L4/L5)

Autonomic/Visceral        Vagal dysfunction,               Somatovisceral reflex (L2),
                           visceral hypersensitivity        vagal activation (L3),
                                                            segmental convergence (L2)

Obstetric/Gyn             Hormonal, smooth muscle,         Somatovisceral reflex (L2),
                           labor physiology                 oxytocin (L5), autonomic
                                                            balance (L3), UNKNOWN (breech)

Cancer Supportive         Treatment side effects,          Anti-inflammatory (L1/L5),
                           fatigue, nausea, pain            vagal anti-inflammatory (L3),
                                                            evaluative gates (L6)

Neurological/Balance      Proprioceptive deficit,          Motor learning (L4),
                           neurodegeneration,               neuroplasticity (L4/L5),
                           central processing               proprioceptive input (L1/L2)

Metabolic                 Insulin resistance, vascular     Sustained autonomic retuning
                           dysfunction, HPA chronic         (L3/L5), myokine pathway (L5),
                                                            self-regulation (L6)

Respiratory               Airway inflammation,             Vagal bronchodilation (L3),
                           reduced capacity                 respiratory muscle training,
                                                            anti-inflammatory (L5)
```

🟡 Mapping pathophysiology → predicted mechanisms is synthetic. The predictions are testable via head-to-head trials targeting mechanism-matched vs mechanism-mismatched therapy-condition pairs.

### §3.2 — Main Matrix: Condition × Therapy

The central analytical product. Each cell contains: evidence level (🟢/🟡/🔴), effect size where available. Empty cells = no evidence or not studied.

#### Domain 1: MUSCULOSKELETAL PAIN

```
CONDITION        B01    B02    B03    B04    B07    B08    B09    B10    B11    B13    B14    B15    B16
                 Acu    Acu-P  Mass   Deep   Cup    Moxa   GuaSh  Chiro  DN     Shiat  CST    TaiCh  Yoga
─────────────── ────── ────── ────── ────── ────── ────── ────── ────── ────── ────── ────── ────── ──────
Chronic LBP      🟢     🟡     🟢     🟡     🟡     🟡     🟢     🟢     🟢     🟡     🟡     🟡     🟢
                 0.23s  auri   Cochr  6 RCT  netMA         TLF-   -3.17  -2.74         -0.32  -0.81  =PT
                 0.55w  cular  2015   LBP    2025          RCT    100sc  SMD           vs pas -1.43  Cochr
                                                                                                     2022

Chronic neck     🟡     —      🟡     🟢     🟡     🟡     🟢     🟢     🟢     —      🟡     —      🟢
                 -0.79         Cochr  10RCT  9RCT         -29.9  Bronf  Hern-         Halle         -1.13
                 adj           2024   MFR    Li26         VAS    2012   2023          2016          SMD

Knee OA          🟢     —      🟡     —      🟡     🟡     —      —      🟡     —      —      🟢     🟡
                 0.16s         Perl-         mulRCT Li16                Knee                 =PT    8RCT
                 -0.96w        2012                                     OA                   Wang16 -0.92

Fibromyalgia     🟡     —      🟢     🟡     🟡     —      —      —      🔴     🟡     🟡     🟢     🟡
                 EA-           -1.16  5+wk                       2026  Yuan   Castr  Wang   Cars
                 0.63          SMD    sust                       rev   2013   2011   2018   pilot

trigger point/Myofascial   —      —      🟢     🟡     —      —      —      —      🟢     —      —      —      —
                              Denne  mixed                       Llama
                              2019                               2014

Lat Epicond      —      —      —      🟡     —      —      —      —      🟢     —      —      —      —
                                      IASTM                      -1.37
                                                                 SMD

Plantar Fasc     —      —      —      —      —      —      —      —      🟢     —      —      —      —
                                                                 NNT=4

Shoulder         —      —      🟡     🟡     —      —      —      🟡     🟡     —      —      —      —
                              Kong   RotCf                VL     -0.27
                              2022                                SMD
```

**Notes:** B05 Dien Chan, B06 Reflexology, B12 EFT = no MSK pain evidence meeting 🟡 threshold. B06 pain evidence exists but is inconsistent and null vs sham (Ernst 2009). B12 pain = weak/not primary domain.

#### Domain 2: HEADACHE

```
CONDITION        B01    B04    B07    B10    B11    B16
                 Acu    Deep   Cup    Chiro  DN     Yoga
─────────────── ────── ────── ────── ────── ────── ──────
Migraine prev    🟢     —      🟡     🔴     —      —
                 NNT=4         6RCT   Chaib
                 NNT=11s              2017NS

TTH              🟢     🟡     —      🟡     🟡     —
                 NNT=3  Lu     Cast   2024
                 NNT=8s 2024   2011   SR

Cervicogenic     —      🟡     —      🟢     🟡     —
                        Lu            Jull
                        2024          2002
```

**Notes:** B01 dominates headache domain. Migraine prevention NNT=4 vs no treatment, NNT=11 vs sham = one of strongest acupuncture findings. B10 cervicogenic headache = mechanism-matched (cervical proprioceptive input).

#### Domain 3: PSYCHOLOGICAL

```
CONDITION        B01    B02    B03    B06    B12    B15    B16
                 Acu    Acu-P  Mass   Reflex EFT    TaiCh  Yoga
─────────────── ────── ────── ────── ────── ────── ────── ──────
Depression       🟡     🟡     🟡     🟡     🟢†    🟡     🟢🟢
                 adj    auri   0.62   Wang   1.31†  SMD    -0.52
                 -1.15  cular  pre-p  2020   Nelms  0.4-   I²=6%
                 VL     small               †wait  0.8

Anxiety          🟡     🟢     🟡     🟡     🟢†    🟡     🟡
                 -0.41  -1.30  0.37   vs     1.23†  VA     -0.55
                 no     preop  contr  pass   †wait  MOD    I²=60%
                 sham                 only          CBT>

PTSD             🟡     —      —      —      🟡     —      🟢
                 =CBT                        vs act        -0.51
                 pilot                       0.15-         vdKol
                                             0.79          2014

Phobias          —      —      —      —      🟡     —      —
                                             SUDS
                                             expos
```

**Notes:** B16 Yoga = STRONGEST for depression (SMD -0.52, I²=6% = lowest heterogeneity of ANY outcome in Track B). B12 EFT depression/anxiety marked with † because effect sizes are from waitlist controls; independent meta-analysis (Gilomen): g=0.51-0.66, much smaller. B02 preoperative anxiety SMD -1.30 is very large but blinding concern. CBT > yoga for diagnosed GAD (Simon 2021 JAMA Psychiatry).

#### Domain 4: SLEEP

```
CONDITION        B01    B02    B03    B06    B15    B16
                 Acu    Acu-P  Mass   Reflex TaiCh  Yoga
─────────────── ────── ────── ────── ────── ────── ──────
Insomnia/        🟡     🟡     🟡     🟡     🟡     🟡
Sleep Quality    PSQI   HT7    state  -1.37  mult   PSQI
                 -2.60  Shen   anxi   vs     studi  -0.33
                        Men    ety    pass   es
```

**Notes:** No therapy reaches 🟢 for sleep as primary outcome. B06 shows g=-1.37 but this is vs passive controls only; sham-controlled evidence is null. Sleep improvements across therapies are often secondary to pain reduction or anxiety reduction, not primary sleep-specific mechanisms.

#### Domain 5: AUTONOMIC/VISCERAL

```
CONDITION        B01    B02    B08    B15    B16
                 Acu    Acu-P  Moxa   TaiCh  Yoga
─────────────── ────── ────── ────── ────── ──────
PONV (PC6)       🟢     🟢     —      —      —
                 0.68RR 0.68RR
                 NNT≈4  NNT≈4
                 =drugs =drugs

CINV             🟡     🟡     —      —      —
                 EA     ONS
                 0.74   PEP

IBS/Digestive    —      —      🟡     —      —
                               ST36
                               Park13

Hypertension     🟡     —      —      🟡     🟢
                 -6.73               VA      -0.48
                 SBP                 HIGH    SBP
```

**Notes:** PONV at PC6 = the single condition-therapy pair where B01 and B02 have EQUIVALENT 🟢 evidence (Cochrane, NNT≈4, = antiemetic drugs). This is because PC6 antiemetic effect operates via somatovisceral reflex at median nerve → vagal pathway — surface pressure sufficient, penetration not required. B16 hypertension = VA HIGH certainty.

#### Domain 6: OBSTETRIC/GYNECOLOGICAL

```
CONDITION        B01    B02    B03    B07    B08    B09    B13
                 Acu    Acu-P  Mass   Cup    Moxa   GuaSh  Shiat
─────────────── ────── ────── ────── ────── ────── ────── ──────
Breech (BL67)    —      —      —      —      🟢     —      —
                                             JAMA
                                             1.58RR

Labor pain       —      🟢     🟢     —      —      —      🟡
                        LI4    Cochr                       point
                        SP6    2018                        spec

Dysmenorrhea     —      🟡     —      🟡     🟡     —      —
                        SP6                  Yang
                        >acu!                2017

Breast engorge   —      —      —      —      —      🟢     —
                                                    RCT

Perimenopausal   —      —      —      —      —      🟡     —
                                                    Meng18
```

**Notes:** B08 BL67 breech = STRONGEST single-point clinical evidence in Track B AND most mechanistically inexplicable (S1 dermatome has NO uterine viscerotome connection). B02 dysmenorrhea at SP6 OUTPERFORMED B01 acupuncture at SP6 (p=0.001 vs p=0.371) — acupressure more effective than acupuncture at same point for this condition.

#### Domain 7: CANCER SUPPORTIVE CARE

```
CONDITION        B01    B02    B03    B06    B08    B15    B16
                 Acu    Acu-P  Mass   Reflex Moxa   TaiCh  Yoga
─────────────── ────── ────── ────── ────── ────── ────── ──────
Cancer pain      🟡     🟡     🟡     🟡     —      —      —
                 -0.93  auri   Boyd   Klaus
                 NRS    46-50  2016   2024

Cancer fatigue   —      🟡     —      —      🟡     🟡     🟢
                        Zick                 ST36          -0.40
                        2016                              SMD

Cancer QoL       —      —      —      🟡     —      🟡     🟡
                                      Klaus         mult
                                      2024
```

#### Domain 8: NEUROLOGICAL/BALANCE

```
CONDITION        B15    B16
                 TaiCh  Yoga
─────────────── ────── ──────
Fall prevention  🟢🟢   —
                 58%↓
                 NNT≈3-4

Parkinson's      🟢     —
balance          NEJM
                 >resis

Cognitive/MCI    🟡     —
                 AIM
                 2023

Post-stroke      🟡*    —
                 (B01🟡
                  China
                  bias)
```

**Notes:** B15 fall prevention = Li 2018 JAMA Intern Med (n=670): 58% reduction vs stretching, 31% vs multimodal exercise. NNT≈3-4. One of the strongest intervention RCTs in ALL of Track B. B15 Parkinson's balance = Li 2012 NEJM: Tai Chi SUPERIOR to resistance training. *B01 stroke rehabilitation has 3,645 RCTs mapped but 99.92% from China — extreme geographic bias.

#### Domain 9: METABOLIC

```
CONDITION        B15    B16
                 TaiCh  Yoga
─────────────── ────── ──────
T2DM/Glucose     —      🟢
                        FBG
                        -1.24
                        HbA1c
                        -0.72

Blood Pressure   🟡     🟢
                 VA     -0.48
                 HIGH   SBP
```

**Notes:** B16 T2DM = FBG SMD -1.24, HbA1c reduction ~0.55-0.64 percentage points over 3 months. Only active/movement-based therapies show metabolic effects — passive therapies (B01-B14) have no meaningful metabolic evidence.

#### Domain 10: SPORTS/RECOVERY

```
CONDITION        B03    B04    B11
                 Mass   Deep   DN
─────────────── ────── ────── ──────
DOMS             🟢     🟡     —
                 -0.75  Crane
                 SMD    2012

Sports Perf      —      🟡     🟡
                        foam   athl
                        roll   etes
```

#### Domain 11: RESPIRATORY

```
CONDITION        B01    B15    B16
                 Acu    TaiCh  Yoga
─────────────── ────── ────── ──────
COPD             🟡     🟡     🟡
                 GOLD   Cochr  mult
                 2021   2025   studi

Allergic rhinitis 🟡    —      —
                 -1.09
                 TNSS

Asthma           —      —      🟡
                               mult
```

#### Domain 12: INFLAMMATORY/IMMUNE/OTHER

```
CONDITION        B01    B03    B07    B09
                 Acu    Mass   Cup    GuaSh
─────────────── ────── ────── ────── ──────
Hepatitis B      —      —      —      🟡
(HO-1)                                Chan
                                       2011

Herpes zoster    —      —      🟡     —
                               20RCT

Urticaria        🟡     —      —      —
                 1.20RR

Preterm growth   —      🟢     —      —
                        5.1g
                        /day
```

**Notes:** B03 preterm infant growth = Field 1986 landmark finding: 47% greater weight gain with moderate pressure massage. Moderate pressure 5.60 g/day vs light 1.08 g/day (>5x difference). -4.5 days hospital stay.

### §3.3 — Head-to-Head Comparison Data

Direct therapy comparisons are rare but analytically valuable. All available head-to-head data from Track B:

#### 3.3.1 — Within-Domain Comparisons (Same Condition)

```
COMPARISON              CONDITION       RESULT                          CITATION        SIGNIFICANCE
─────────────────────── ─────────────── ──────────────────────────────── ─────────────── ────────────────
B01 vs prophylactic     Migraine        B01 ≥ drugs, fewer AEs          Cochrane Linde  Clinical: B01
drugs                    prevention      (114/1000 vs 341/1000)          2016            preferred (safety)

B01 vs antiemetic       PONV            NO significant difference        Cochrane Lee    Interchangeable
drugs                                                                    2015

B02 vs antiemetic       PONV            NO significant difference        Cochrane 2025   Interchangeable
drugs

B01 vs B02 at SP6       Dysmenorrhea    B02 > B01 at SAME POINT         Chen & Chien    Acupressure
                                         (p=0.001 vs p=0.371)            2013 MA         OUTPERFORMS
                                                                                         for this condition

B15 vs resistance       Parkinson's     B15 SUPERIOR for balance         Li 2012 NEJM    Tai Chi > RT
training                 balance

B15 vs multimodal       Fall prevention B15 SUPERIOR (58% vs 31%         Li 2018 JAMA    Tai Chi > multi
exercise                                 reduction)                      Intern Med

B15 vs PT               Knee OA         B15 = PT (noninferior)           Wang 2016       Equivalent
                                                                         Ann Int Med

B16 vs PT               Chronic LBP     B16 = PT (noninferior)           Saper 2017      Equivalent
                                                                         Ann Int Med

B16 vs stretching       Chronic LBP     B16 NOT superior to              Sherman 2011    Equivalent
                                         generic stretching

B16 vs CBT              GAD             CBT OUTPERFORMED Kundalini       Simon 2021      CBT > yoga
                                         yoga                            JAMA Psych

B16 vs walking          Mood/GABA       B16 > walking (GABA↑,            Streeter 2010   Yoga > walking
                                         mood↑, anxiety↓)                                 (if replicated)

B12 vs CBT              Food cravings   B12 ≈ CBT                       Stapleton 2016  Equivalent

B12 vs EMDR             PTSD            BOTH effective, similar          Karatzias 2011  Equivalent
                                         effect sizes

B10 vs exercise         Chronic LBP     COMPARABLE, not superior         Rubinstein 2019 Equivalent
                                                                         Cochrane

B10 vs medication       Neck pain       B10 > medication at 8-52 wk      Bronfort 2012   Chiro > meds
                                         B10 ≈ home exercise                              Chiro ≈ exercise

B10 mobilization        Spinal pain     SIMILAR outcomes in most          Gross 2015      Equivalent
vs manipulation                          studies                          Coulter 2019

B06 vs sham massage     Brain           IDENTICAL brain connectivity     Descamps 2023   NO specificity
                         connectivity    changes (fMRI)

B09 vs B07 clinical     Pain range      B09 BROADER (pain + hepato +     No direct       B09 broader
profile                                  breast + perimeno) vs B07        comparison      profile
                                         (pain only)

Active relaxation       Autonomic       Active relaxation > Shiatsu       Lucini 2009     Active > passive
vs B13                   markers
```

#### 3.3.2 — Cross-Therapy Patterns from Head-to-Head Data 🟡

1. **Active therapy equivalence:** B15 Tai Chi = PT for knee OA; B16 Yoga = PT for LBP. Active therapies match physical therapy for MSK conditions — suggesting shared exercise-level mechanisms dominate.

2. **Passive therapies vs drugs:** B01 = antiemetics for PONV; B01 ≥ prophylactic drugs for migraine (with better safety). Body-based therapies can match pharmaceuticals for specific conditions where mechanism alignment is strong.

3. **B02 > B01 at SP6 for dysmenorrhea:** The ONLY condition where acupressure outperforms acupuncture at the same point. Possible explanation: sustained pressure at SP6 produces prolonged uterine smooth muscle relaxation via continuous somatovisceral reflex, while brief needle stimulation produces phasic response. This finding challenges the assumption that needling is always superior.

4. **B16 ≈ exercise for MSK pain:** Yoga's most consistent finding. Combined with B15 ≈ PT data, suggests that for pain conditions, the exercise-equivalent mechanism base (myokine, cardiovascular, motor learning) dominates over any therapy-specific mechanism.

### §3.4 — Mechanism-Based Explanation

WHY certain therapies work for certain conditions — connecting clinical outcomes to C01 stimulus types, C03 mechanism hierarchy, and C04 location specificity.

#### 3.4.1 — The Mechanism-Condition Matching Principle 🟡

The strongest therapy-condition pairs occur when the therapy's UNIQUE or DEFINING mechanisms (C03 §3.3) match the condition's dominant pathophysiology (§3.1):

```
THERAPY     UNIQUE/DEFINING MECHANISM(S)         MATCHED CONDITION(S)           EVIDENCE
────────── ────────────────────────────────────── ────────────────────────────── ─────────
B01         PROKR2 vagal-adrenal (EA),            PONV/CINV (vagal),             🟢 PONV
            Han opioid frequency-dependent,        chronic pain (opioid),         🟢 migraine
            Goldman adenosine 24×,                  migraine (trigeminal mod)      🟢 LBP/OA
            point specificity (6 levels)

B08         HSP cytoprotection,                   Breech (UNKNOWN — mismatch     🟢 breech
            TRPV1 hub,                              is the paradox),              🟡 knee OA
            thermal vasodilation                    knee OA (thermal anti-inflam)

B10         Proprioceptive reset (Pacinian),      Cervicogenic headache (cerv    🟢 CGH
            joint gapping,                          proprioception),              🟢 LBP
            cavitation (Type II burst)              acute LBP (segmental reset)

B11         LTR/ACh depletion (trigger point-specific),     trigger point/myofascial pain,           🟢 trigger point
            DDN micro-wound at trigger point,                lateral epicondylitis (trigger point     🟢 lat epi
            FSN fascial specific                    at common extensor origin)

B15         Motor learning + proprioception        Fall prevention (balance =     🟢🟢 falls
            (continuous weight shift),              motor learning),              🟢 PD bal
            voluntary ANS (breathing)               Parkinson's (proprioception)

B16         GABA modulation (🟡),                  Depression (GABA↓ in MDD),     🟢🟢 depr
            transcriptional NF-κB↓ (Bower),         T2DM (NF-κB chronic inflam),  🟢 T2DM
            self-efficacy (36% mediator)             chronic conditions (self-eff)

B07/B09     HO-1 microtrauma pathway               MSK pain (cytoprotection),     🟡 pain
            (capillary → CD163 → CO/biliv)          hepatitis B (B09: systemic     🟡 hep B
                                                    HO-1 → hepatoprotection)
```

**The matching principle predicts that therapies should be MOST effective for conditions matching their unique mechanisms and LEAST effective for conditions requiring mechanisms they lack.** This is broadly confirmed:
- B10 (proprioceptive reset) = effective for cervicogenic headache, NOT for depression
- B15 (motor learning) = effective for falls/balance, NOT for acute pain
- B12 (cognitive exposure) = effective for anxiety/PTSD, NOT for MSK pain
- B07 (HO-1) = effective for pain only, NOT for psychological or autonomic conditions

#### 3.4.2 — Why Chronic Pain Responds to Almost Everything 🟡

Chronic LBP has evidence from 12/16 therapies. This is NOT because everything works — it is because chronic pain pathophysiology engages the UNIVERSAL mechanism base:

1. **Peripheral nociception** → gate control (L2) = activated by ANY Aβ stimulus = 13/16 therapies
2. **Central sensitization** → descending modulation (L3) = activated by sufficient Aδ/C input = 11/16 therapies
3. **HPA dysregulation** → cortisol modulation (L5) = activated by ANY structured therapeutic encounter = 12/16
4. **Catastrophizing/fear-avoidance** → evaluative gates (L6) = activated by ALL therapies = 16/16

Since chronic pain engages ALL levels of the mechanism hierarchy, and the universal mechanisms (gate control, descending modulation, opioids, evaluative gates) are sufficient for modest pain relief (SMD 0.2-0.5), MOST therapies produce SOME benefit. The therapy-specific mechanisms (PROKR2, HO-1, HSP, proprioceptive reset) add DIFFERENTIAL benefit on top of this shared base — but this differential is small (typically 0.1-0.3 SMD additional over sham).

**Clinical implication:** For chronic pain, the choice between therapies should be based on: (a) unique mechanism match to the specific pain subtype, (b) patient preference/adherence likelihood, (c) availability/cost, (d) safety profile. NOT "which therapy is best" — the universal base ensures similar outcomes.

#### 3.4.3 — Why Psychological Conditions Show Different Therapy Profiles 🟡

Unlike chronic pain (which responds to nearly all therapies), psychological conditions show a distinct pattern: B16 Yoga strongest for depression, B12 EFT strongest for anxiety, B15 Tai Chi moderate for both, passive therapies modest.

**Mechanism explanation via C03:**
- **Depression** requires sustained neurochemical/neuroplastic change (weeks-months). B16 provides: GABA modulation (Streeter, if confirmed), NF-κB transcriptional anti-inflammatory (Bower 2014), self-efficacy (36% mediator), and repeated practice building CAPACITY. Passive therapies provide only transient neurochemical shifts (opioids, parasympathetic) — insufficient for sustained mood change.
- **Anxiety** has a broader mechanism base: ANY parasympathetic shift helps acutely. B02 preop anxiety SMD -1.30 shows that even single-session passive intervention helps for STATE anxiety. But TRAIT anxiety/clinical GAD requires sustained change — where CBT > yoga > passive therapies.
- **PTSD** specifically responds to B16 (van der Kolk 2014) and B12 (with caveats). Both include COGNITIVE components: yoga via interoceptive awareness, EFT via explicit exposure/reframing. Pure passive-somatic therapies (B01, B03) have minimal PTSD evidence because PTSD requires processing trauma narratives, not just modulating pain pathways.

#### 3.4.4 — Why PONV Is the Perfect Mechanism-Condition Match 🟢

PONV (postoperative nausea/vomiting) at PC6 is the ONLY condition-therapy pair where two therapies (B01 and B02) both achieve 🟢 evidence AND match antiemetic drugs. This occurs because:

1. **Location:** PC6 = median nerve territory → vagal afferent access → NTS → vomiting center. C04 body region hierarchy: forearm = standard somatovisceral pathway, but PC6 specifically accesses the vagal-NTS-CTZ circuit.
2. **Mechanism:** Somatovisceral reflex (C03 Tier 2 common mechanism, 7/16 therapies) operates at SEGMENTAL level (L2). Surface pressure is SUFFICIENT — penetration adds no additional mechanism relevant to nausea.
3. **Why B02 = B01 here:** The antiemetic mechanism requires ONLY sustained median nerve stimulation → vagal afferent activation → NTS modulation of vomiting reflex. Needle penetration adds mechanisms (adenosine, PROKR2, collagen winding) that are IRRELEVANT to nausea suppression. For this specific condition, acupressure's retained mechanisms are the COMPLETE mechanism set.

This explains why P6 acupressure is the ONLY condition where B02 fully matches B01 — the condition's pathophysiology requires exactly the mechanisms that acupressure retains.

#### 3.4.5 — Why Only Active Therapies Show Metabolic/Balance Effects 🟡

B15 and B16 are the ONLY therapies with evidence for: fall prevention, Parkinson's balance, T2DM, sustained blood pressure reduction, and cognitive function. No passive therapy (B01-B14) has meaningful evidence for any of these conditions.

**Mechanism explanation via C03 §3.6 Pattern 5 (Active Therapy Emergence):**
Active therapies provide mechanisms UNAVAILABLE to passive therapies:
- **Motor learning → neuroplastic adaptation** (compounding over months-years): required for fall prevention and Parkinson's balance
- **Myokine anti-inflammatory** (exercise IL-6): required for sustained metabolic effects (insulin sensitivity, blood pressure)
- **Self-efficacy → sustained behavioral change**: required for chronic condition self-management
- **Cardiovascular conditioning**: required for sustained hemodynamic effects (VO2, BP)

Passive therapies provide INPUT (signals for the brain to process). Active therapies build CAPACITY (systems that generate their own signals). Metabolic and balance conditions require capacity-building, not signal-processing.

### §3.5 — Evidence Tier Classification Detail

#### 3.5.1 — What Distinguishes Evidence Tiers

The 5-tier classification (§2.3) reflects STRUCTURAL features of the evidence base:

```
FEATURE              TIER 1          TIER 2          TIER 3          TIER 4          TIER 5
───────────────────  ──────────────  ──────────────  ──────────────  ──────────────  ──────────────
RCT volume           300+            50-300          15-50           50+ (B06/B12)   0-15
Cochrane reviews     Yes (multiple)  Some            No              No              No
Top-tier journals    NEJM/JAMA/BMJ   Some            Rare            None            None
Active comparators   Yes             Some            Rare            Rare (waitlist) Rare
Guideline endorsed   Yes             Some            No              No              No
Sham technology      Moderate        Variable        Poor            Variable        Variable
Independent          Yes             Some            Few             No (B12)        N/A
replication
Geographic           Global          Mixed           Concentrated    Mixed           Concentrated
diversity
Quality-outcome      Positive or     Positive        Uncertain       INVERSE (B06)   N/A
correlation          neutral                                         or COI (B12)
```

#### 3.5.2 — Tier-Specific Biases

**Tier 1 biases:**
- B01: Sham debate (penetrating sham is active; Luo 2025: sham's share = 18.9% of total effect). Geographic publication bias (99.8% positive rate in Chinese trials).
- B03: Cortisol narrative overstatement (Moyer reappraisal: between-group d=0.05-0.30). Dose inadequacy in many trials.
- B15: Blinding impossible. Attention/social confounds. 81% risk of bias in SRs.
- B16: Style heterogeneity ("yoga" pools 8+ distinct modalities). Component dismantling gap. GABA unreplicated.

**Tier 2 biases:**
- B10: Professional allegiance (chiropractic researchers). Subluxation persistence despite WFC 2019 rejection.
- B02: Worst sham problem in Track B (no device equivalent). Geographic concentration (45% from 2020-2024).
- B04: No standardized definition. Structural verification gap (Gao 2026). Small samples (Crane n=11).
- B11: Scope-of-practice distortion. URJC Spain concentration (39.5% of all DN literature). No Cochrane.

**Tier 3 biases:**
- B07: Unsolvable sham problem (visible marks). Cultural research divide (dry vs wet).
- B08: Geographic concentration (China/Korea/Japan). Most studies confound moxa + acupuncture.
- B09: Cannot be blinded (sha marks). Cultural concentration.

**Tier 4 biases (STRUCTURAL problems):**
- B06: Ernst 2009 inverse quality-outcome correlation (higher quality → more likely negative). Descamps 2023 fMRI: reflexology = sham.
- B12: Church = editor + publisher + trainer + researcher (unprecedented COI). "99%" positive rate. Spielmans 2020 corrections. No guideline endorsement despite 69+ RCTs.

**Tier 5 biases (ABSENCE or CONTRADICTION):**
- B05: Geopolitical isolation, no RCTs at all.
- B13: Only 1 proper RCT (Kobayashi 2019). Japanese research tradition values clinical observation over RCTs.
- B14: CSR inter-rater reliability r=0.004. Cranial bone motion 1-25 μm vs palpation threshold ~200 μm.

---

## §4 — EMERGENT PATTERNS

Patterns discovered FROM the cross-reference that are NOT visible in individual Track B files.

### §4.1 — The Universal Pain Response 🟡

**Pattern:** 12/16 therapies have at least 🟡 evidence for chronic LBP. 14/16 have evidence for MSK pain generally. Pain is the UNIVERSAL clinical domain for body-based therapy.

**Explanation:** Chronic pain engages all 7 universal mechanisms from C03 Tier 1 (gate control, parasympathetic shift, evaluative gates, cortisol modulation, opioids, descending modulation, vasodilation). Since these mechanisms are shared by ≥10/16 therapies, nearly all therapies can modulate chronic pain to some degree.

**Implication:** Pain treatment trials comparing different body-based therapies will usually find small or non-significant differences (confirmed by Cochrane reviews showing B10 ≈ exercise ≈ PT ≈ B01 ≈ B16 for LBP). The 7 universal mechanisms create a "shared floor" of pain relief that ALL therapies access. Therapy-specific advantages (0.1-0.3 SMD) exist but require large, well-designed trials to detect.

### §4.2 — The Domain Specificity Pattern 🟡

**Pattern:** Despite the universal pain response, each therapy has a "home domain" where its evidence is strongest — and this domain MATCHES its unique mechanism profile:

```
THERAPY    HOME DOMAIN              UNIQUE MECHANISM MATCH              PREDICTED BY C03?
────────── ──────────────────────── ─────────────────────────────────── ──────────────────
B01        Pain + autonomic         PROKR2 + Han opioids + adenosine    Yes (most specific)
B02        Anti-nausea + anxiolysis Retained somatovisceral reflex      Yes (B02 §5.3)
B08        Breech (!)               UNKNOWN                             No (paradox)
B10        Cervicogenic headache    Proprioceptive reset                Yes (L1-L2 MSK)
B11        trigger point/lateral epicondylitis LTR + ACh depletion                Yes (trigger point-specific)
B12        Anxiety/PTSD             Cognitive exposure (not somatic)    Yes (L6 dominant)
B15        Fall prevention/balance  Motor learning + proprioception     Yes (active therapy)
B16        Depression/T2DM          GABA + NF-κB + self-efficacy        Yes (unique to B16)
```

**Two therapies break the pattern:**
- B08 breech presentation = strongest evidence for its most MECHANISTICALLY INEXPLICABLE application. C02 cannot explain this — it remains the most important unsolved puzzle in the project.
- B02 dysmenorrhea at SP6 outperforms B01 at the same point — unexpected given B01's broader mechanism profile. Sustained pressure may provide better smooth muscle modulation than phasic needle stimulation.

### §4.3 — The Active-Passive Divide 🟡

**Pattern:** Certain condition domains are EXCLUSIVELY responsive to active therapies (B15, B16), while others are primarily responsive to passive therapies (B01-B14):

```
ACTIVE-ONLY domains (B15/B16 only):     Fall prevention, Parkinson's, cognitive/MCI,
                                          T2DM, sustained BP reduction, osteoporosis

PASSIVE-DOMINANT domains (B01-B14):      Acute pain, PONV, DOMS, breech, trigger point deactivation,
                                          cervicogenic headache

SHARED domains (both active + passive):  Chronic LBP, fibromyalgia, anxiety, depression,
                                          sleep, cancer supportive care
```

**Mechanism:** Active-only domains require CAPACITY-BUILDING mechanisms (motor learning, cardiovascular conditioning, myokine anti-inflammatory) unavailable to passive therapies. Passive-dominant domains require TARGETED INPUT (specific stimulus at specific location) that active therapies cannot provide with the same precision. Shared domains respond to both targeted input AND capacity-building.

### §4.4 — The Evidence-Mechanism Dissociation 🟡

**Pattern:** Mechanism science quality and clinical evidence quality are DISSOCIATED across Track B:

```
                    HIGH MECHANISM SCIENCE          LOW MECHANISM SCIENCE
                   ────────────────────────         ──────────────────────
HIGH CLINICAL      B01 (PROKR2, adenosine,          B15 (exercise physiology
EVIDENCE            Han opioids → PONV,               = well-known, BUT no
                    migraine, LBP)                     unique mechanism →
                                                       falls, PD, OA)

LOW CLINICAL       B09 (HO-1 + HIF-1α               B06, B12, B14
EVIDENCE            causal proof →                     (weak mechanism +
                    few good RCTs)                     weak clinical)
```

B09 Gua Sha exemplifies the dissociation: strongest mechanism science in Track B (4/5: HO-1 pathway, HIF-1α causal proof, TLF structural verification) but only 2/5 clinical evidence. B15 Tai Chi exemplifies the reverse: no unique mechanism beyond exercise physiology, but strongest clinical evidence for fall prevention (Li 2018 JAMA).

**Explanation:** Mechanism science requires basic research investment (molecular biology, animal models, imaging). Clinical evidence requires clinical research investment (RCTs, systematic reviews, guideline committees). These are DIFFERENT research ecosystems with DIFFERENT funding sources and DIFFERENT incentive structures. A therapy can be well-understood mechanistically yet poorly tested clinically (B09), or well-tested clinically yet mechanistically unremarkable (B15).

### §4.5 — The Condition-Specificity Gradient 🟡

**Pattern:** Therapies can be ranked by how many clinical domains they effectively serve:

```
BROAD (5+ domains):   B01 (8 domains), B16 (7), B15 (7), B03 (6), B02 (6)
MODERATE (3-4):       B04 (4), B11 (4), B10 (3), B08 (3)
NARROW (1-2):         B07 (1: pain only), B09 (2: pain + hepato), B12 (1: psych only)
INSUFFICIENT:         B05, B06, B13, B14 (insufficient evidence to assess domain range)
```

The condition-specificity gradient correlates with:
- C03 mechanism specificity spectrum (r ≈ 0.7 estimated): mechanistically rich therapies serve more domains
- Evidence tier (r ≈ 0.8 estimated): better-studied therapies show broader clinical range
- The UNIVERSAL mechanism base ensures minimum 1-2 domains (pain + relaxation) for any therapy

### §4.6 — The Sham Paradox Resolved 🟡

**Pattern:** Across Track B, the most common finding is: therapy > no treatment (consistent), therapy > waitlist (consistent), therapy vs sham (small or NS). This pattern appears for B01 (GERAC), B06 (Ernst 2009), B10 (chiro vs sham), B12 (Spielmans 2020), B14 (Haller 2020).

**Resolution via C03 + C04:** The sham paradox is not paradoxical once the mechanism hierarchy is understood:
1. ANY therapeutic encounter activates universal mechanisms (evaluative gates, parasympathetic shift, cortisol modulation) = the non-specific floor (SMD 0.2-0.4)
2. ANY physical contact activates gate control, CT afferents (if skin contact + hairy skin), and relaxation = adds SMD 0.1-0.3
3. Therapy-SPECIFIC mechanisms (PROKR2, HO-1, HSP, proprioceptive reset) add SMD 0.1-0.3 ON TOP

Since sham treatments (especially penetrating sham, sham massage, light touch) activate layers 1-2, the SPECIFIC-mechanism layer (#3) is the only detectable difference in sham-controlled trials. This layer is REAL but SMALL — explaining why therapy > no treatment is always significant (layers 1+2+3 combined) but therapy vs sham is often non-significant (layer 3 alone, requiring large N to detect).

**Clinical significance:** The sham paradox does NOT mean body-based therapies are "just placebo." It means the majority of therapeutic effect comes from mechanisms shared between therapy and sham — and those mechanisms are REAL physiological processes (gate control, vagal activation, opioid release), not illusory.

---

## §5 — PREDICTIONS & TESTABLE HYPOTHESES

Each prediction is 🔴 Hypothesis unless noted.

### P1 — Mechanism-Condition Matching Predicts Superiority

**Prediction:** Head-to-head trials matching therapy-specific mechanisms to condition pathophysiology will show >0.3 SMD advantage over mechanism-mismatched therapies:
- B10 > B03 for cervicogenic headache (proprioceptive reset matches cervical mechanism)
- B11 > B03 for trigger point-specific pain (LTR/ACh depletion matches trigger point pathophysiology)
- B16 > B03 for depression (GABA + NF-κB + self-efficacy vs transient relaxation)
- B07/B09 > B01 for HO-1-responsive inflammatory conditions (direct HO-1 vs indirect)

**Confirm:** Mechanism-matched pair shows >0.3 SMD advantage in ≥3 of 4 predicted comparisons.
**Refute:** No advantage, suggesting universal mechanisms dominate ALL clinical outcomes regardless of unique mechanism match.

### P2 — Active Therapies Will Not Help Acute Pain

**Prediction:** B15 Tai Chi and B16 Yoga will show NO benefit for acute pain (postoperative, acute injury, headache attack) because their mechanisms require sustained practice for capacity-building. Active therapies are CHRONIC-condition therapies, not acute interventions.

**Confirm:** RCTs of single-session Tai Chi/Yoga for acute pain show no significant difference from no treatment.
**Refute:** Single-session yoga/Tai Chi shows significant acute pain relief, suggesting breathing/relaxation components provide sufficient acute mechanism.

### P3 — Evidence Tier Predicts Research Investment Return

**Prediction:** Tier 3 therapies (B07, B08, B09) will show the highest research investment return — moving conditions from 🟡 to 🟢 — because they have strong mechanisms but weak clinical evidence. Tier 1 therapies have diminishing returns (already well-studied). Tier 4-5 therapies have no specific mechanisms to validate.

**Confirm:** A single well-designed RCT for B09 gua sha (n≥100, sham-controlled for neck pain) produces 🟢 evidence, while equivalent investment in B01 acupuncture for a new condition produces only 🟡.
**Refute:** Tier 3 trials fail due to unsolvable sham problems, suggesting mechanism quality is insufficient without solvable methodology.

### P4 — The Non-Specific Floor Is Universal and Measurable

**Prediction:** Any structured therapeutic encounter involving touch, time (≥30 min), attention, and narrative will produce SMD 0.25 ± 0.10 for anxiety and SMD 0.15 ± 0.10 for pain, regardless of technique. This should be consistent across B06 reflexology, B14 craniosacral, and a novel "structured compassionate touch" control with NO technique.

**Confirm:** Structured compassionate touch produces equivalent outcomes to B06/B14.
**Refute:** B06/B14 significantly outperform structured compassionate touch, suggesting even weak specific mechanisms contribute measurably.

(Overlaps with C03 P1, testing same floor from the condition side.)

### P5 — Depression Will Respond Preferentially to Active Therapies

**Prediction:** For clinical depression, B16 Yoga and B15 Tai Chi will consistently outperform passive body-based therapies (B01, B03) by >0.3 SMD, because depression requires sustained neuroplastic/neurochemical change (GABA, NF-κB, self-efficacy) that only repeated active practice provides.

**Confirm:** Head-to-head RCT: B16 > B01 acupuncture for depression (primary) with >0.3 SMD and sustained benefit at 6 months.
**Refute:** B01 = B16 for depression, suggesting acupuncture-specific mechanisms (opioids, adenosine) contribute to sustained mood change via pathways not captured in current models.

### P6 — The Breech Paradox Will Not Replicate

**Prediction:** Large pre-registered RCT of B08 moxibustion at BL67 for breech presentation (n≥500, multi-center, Western setting) will show effect size substantially smaller than Cardini 1998 (RR 1.58). The original finding may reflect: (a) natural version rate differences between populations, (b) unknown confounds in the original trial, or (c) an effect that exists but is smaller than reported.

**Confirm:** Large RCT shows RR <1.15 (NS) for moxibustion at BL67.
**Refute:** Large RCT replicates RR >1.30, confirming a real effect that demands a new mechanistic model (non-segmental ascending pathway? sympathetic reflex via S1?).

---

## §6 — LIMITATIONS & GAPS

### §6.1 — Methodological Limitations

1. **Evidence level collapse.** The 3-level system (🟢/🟡/🔴) collapses important distinctions. B01 🟢 for LBP (39 trials, 20,827 patients in ATC IPD analysis) is fundamentally different quality from B15 🟢 for fall prevention (1 landmark trial, n=670). Both map to 🟢 in the matrix.

2. **Comparator heterogeneity.** Effect sizes are not directly comparable across therapies because comparators differ. B01 LBP SMD 0.23 (vs sham) ≠ B15 LBP SMD -0.81 (vs inactive). Adjusting for comparator type would change the matrix substantially.

3. **Condition definition heterogeneity.** "Chronic LBP" in B01 Cochrane reviews may not be the same population as "chronic LBP" in B16 yoga trials. Different inclusion criteria, chronicity thresholds, and outcome measures make cross-therapy comparison imprecise.

4. **The active-control problem.** For B15/B16, no adequate sham exists. "Yoga > waitlist" is uninformative about yoga-SPECIFIC effects. But "yoga ≈ exercise" may be the MORE important clinical finding — it tells practitioners that yoga IS exercise.

5. **Publication bias asymmetry.** B01 acupuncture: 99.8% positive rate in Chinese trials (Wang 2014). B12 EFT: "99%" positive rate from EFT-affiliated researchers. These extreme rates make overall evidence assessment unreliable for both therapies — but for opposite reasons (B01 = large global base dilutes Chinese bias; B12 = small network amplifies COI).

### §6.2 — Missing Data

1. **No head-to-head trials designed to test mechanism matching.** All predictions in §5 remain untested. The most informative possible trial — comparing two therapies for the SAME condition chosen because one matches and one mismatches the mechanism profile — has never been conducted.

2. **Component dismantling absent for most therapies.** B16 has ZERO RCTs separating posture vs breathing vs meditation. B15 has ZERO separating movement vs breathing vs attention. B01 cannot separate needle-specific from point-specific from context-specific effects in a single trial.

3. **Long-term follow-up rare.** Most trials report outcomes at 4-12 weeks. Chronic conditions require evidence of sustained benefit (6-12+ months). Only B01 ATC data (85% effect maintained at 12 months) and B15 fall prevention (24-week trial) provide meaningful long-term data.

4. **Dose-response characterization incomplete.** Only B03 massage has systematic dose-response data (Cochrane 2024: high-dose subgroup shows clinically important differences; low-dose does not). For most therapies, optimal session duration, frequency, and total dose are unknown.

5. **Cost-effectiveness data sparse.** Clinical decision-making requires not just efficacy but cost-effectiveness. Only B01 acupuncture and B10 chiropractic have published cost-effectiveness analyses.

6. **Patient selection/responder prediction underdeveloped.** B01 has responder prediction models (Yang 2020 83%, Gao 2025 85%), but no other therapy has attempted prediction. WHO responds to WHICH therapy remains essentially unknown.

---

## §7 — OPEN QUESTIONS

Questions RAISED BY the cross-reference analysis that only become visible when comparing clinical evidence across therapies.

**Q1 (CRITICAL). Does mechanism-condition matching improve outcomes?** §3.4 proposes that matching therapy-specific mechanisms to condition pathophysiology should predict superiority. But this has NEVER been tested. The strongest finding in the matrix — that almost all therapies work modestly for chronic pain — suggests universal mechanisms may dominate all clinical outcomes. If universal mechanisms account for >80% of effect, mechanism-condition matching adds only marginal value. The practical significance of the 51-mechanism taxonomy (C03) depends on this question.

**Q2. Why does B08 BL67 work for breech?** The most important specific clinical puzzle. BL67 is at S1 dermatome → NO uterine viscerotome connection (T10-L1, S2-S4). The ONLY 🟢 evidence in Track B that CANNOT be explained by ANY mechanism model in the project. If the effect replicates, it implies unknown ascending pathways. If it doesn't replicate, the strongest single-point clinical evidence in Track B dissolves.

**Q3. Is there a genuine active-therapy advantage beyond exercise equivalence?** B15 and B16 produce the broadest clinical range. But is this because they are THERAPEUTIC modalities or because they are EXERCISE with good marketing? The most consistent finding is yoga ≈ PT ≈ exercise for MSK. If this extends to depression and metabolic conditions (yoga ≈ matched exercise for depression), the mind-body component may add nothing beyond exercise physiology. Streeter's GABA finding is the strongest candidate for a genuine yoga-specific mechanism — but remains unreplicated.

**Q4. What is the optimal therapy for conditions that respond to multiple therapies?** Chronic LBP responds to 12/16 therapies. How should a clinician choose? The matrix suggests: (a) mechanism match to pain subtype, (b) patient preference, (c) availability/cost, (d) safety. But NO study has compared therapy-selection strategies (mechanism-matched vs random vs patient-preference) to determine which selection method improves outcomes.

**Q5. Can evidence Tier 3 therapies be upgraded efficiently?** B07, B08, B09 have strong mechanisms but weak clinical evidence. Would a single well-designed RCT per therapy (n≥100, sham-controlled, adequate follow-up) upgrade them to Tier 2? Or are the structural barriers (sham problem, cultural concentration) insurmountable for manual therapies?

**Q6. Is the non-specific floor truly floor, or does it contain substructure?** C03 estimated SMD 0.2-0.4. But does the floor vary by condition domain? Is the non-specific floor for anxiety (parasympathetic shift) larger than for pain (gate control)? If so, therapy-specific effects may matter MORE for pain (where the floor is lower) than for anxiety (where the floor already captures most of the effect).

**Q7. Why does clinical evidence cluster in certain geographic regions?** B01 in China, B11 in Spain (URJC), B07 wet cupping in Saudi Arabia, B15/B16 in India/USA. Is this cultural affinity, research tradition, funding structure, or genuine population-level differences in therapy responsiveness? The answer determines how generalizable the evidence is.

**Q8. Can the sham problem be solved for manual therapies?** B01 has Streitberger/Park devices. B02-B14 have no adequate sham. Without sham control, specific effects cannot be isolated. But if sham IS the treatment (as argued for B14 and partially for B06), the question becomes: does it MATTER that we can't isolate specific effects, or is the combined specific + non-specific effect the clinically relevant outcome?

---

## §8 — CROSS-REFERENCES

### §8.1 — Track A Files Referenced

| File | Concept Used in C02 |
|------|-------------------|
| A01 PNS | Gate control as universal pain mechanism, CT afferents in non-specific floor |
| A02 ANS | Parasympathetic shift as universal mechanism, vagal anti-inflammatory for chronic conditions |
| A03 Fascia | endocannabinoid system threshold depth → which therapies access fascial mechanisms for MSK pain |
| A04 Vascular | HO-1 pathway → B07/B09 narrow clinical range explained |
| A05 Neuroimmune | Anti-inflammatory pathways → cancer supportive, chronic conditions |
| A06 Endocrine | Han opioids → B01 pain advantage; cortisol reappraisal → Moyer caveat across all therapies |
| A07 Somatotopic | Segmental convergence → why location matters for visceral conditions (PONV at PC6) |
| A08 MSK | trigger point-acupoint overlap → B11 mechanism match; proprioceptive input → B10/B15 specificity |
| A09 Meridian | PROKR2 → B01 specific mechanism advantage; fundamental asymmetry informs evidence patterns |

### §8.2 — Track B Files Referenced

All 16 Track B files referenced via §4 (Clinical Effects) and §9 (Evidence Assessment):

**Every cell in the Main Matrix (§3.2) traces to a specific Track B §4 subsection.** Key contributions by therapy:
- B01 §4: 8+ Tier 1 conditions (largest clinical range)
- B02 §4: PONV PC6 (matching B01), preoperative anxiety (SMD -1.30)
- B03 §4: Preterm infant growth (Field 1986), DOMS (Crane 2012), fibromyalgia
- B04 §4: Structural-Neural Dissociation for MSK pain
- B05 §4: Zero RCTs but eTNS validates trigeminal territory
- B06 §4: Inverse quality-outcome (Ernst 2009), fMRI null (Descamps 2023)
- B07 §4: Pain-only profile matching narrow HO-1 mechanism
- B08 §4: Breech paradox (Cardini 1998 JAMA = strongest single-point evidence)
- B09 §4: Broader profile than B07 (HO-1 + HIF-1α)
- B10 §4: Spinal pain moderate, non-MSK unsupported
- B11 §4: Lateral epicondylitis strongest (SMD -1.37), NICE endorsed
- B12 §4: Psychological-only profile, waitlist inflation, Spielmans 2020
- B13 §4: Labor pain (often point-specific = B02), Kobayashi 2019 only proper RCT
- B14 §4: vs passive SMD -0.32 (small), vs active NS
- B15 §4: Fall prevention 58% (Li 2018), Parkinson's > RT (Li 2012)
- B16 §4: Depression SMD -0.52 (I²=6%), T2DM FBG -1.24, yoga ≈ exercise for LBP

### §8.3 — Track C Dependencies and Connections

- **C01 → C02:** C01's stimulus-pathway matrix identifies WHAT physical stimulus activates WHICH pathways. C02 uses this to explain WHY certain stimuli are effective for certain conditions (§3.4). The depth-mechanism cascade (C01 §3.6 Pattern 2) explains why deep therapies (B04, B11) serve MSK pain better than light-touch therapies (B14).

- **C03 → C02:** C03's shared mechanism catalog (7 universal, 13 common, 16 narrow, 15 unique) provides the mechanism framework for C02's explanation of clinical outcomes. The universal pain response (§4.1) is explained by C03's Tier 1 universal mechanisms. Domain specificity (§4.2) is explained by C03's unique mechanisms. The non-specific floor (C03 §4.4) quantifies the baseline all therapies share.

- **C04 → C02:** C04's body region hierarchy explains condition-specific location effects. PONV at PC6 (§3.4.4) is explained by C04's segmental convergence at median nerve. The face-ear-foot triangle (C04 §4.4) explains why facial/auricular therapies serve autonomic conditions better than foot reflexology.

- **C02 → C05:** C02's condition-therapy matrix provides the clinical outcome data that C05 (Individual Variation) will use to explain WHY the same therapy produces different results in different people. Responder prediction (B01 §8) becomes more powerful when the condition-mechanism match is understood.

### §8.4 — Human-Predictive-Drive Connection Points

- **Evaluative Gates:** The non-specific floor (§4.6) is largely attributable to Human-Predictive-Drive's Evaluative Gates — the cognitive/contextual modulation that ALL therapeutic encounters activate. C02 quantifies this floor at SMD 0.2-0.4.
- **Zone D Bridge:** Active therapies (B15, B16) access Zone D via voluntary breathing — explaining their exclusive advantage for chronic/metabolic conditions requiring sustained autonomic change.
- **Direct-State Processing:** Psychological conditions (depression, anxiety, PTSD) require Direct-State modification — explaining why therapies with cognitive components (B12 exposure, B16 interoceptive awareness) serve these conditions better than purely somatic therapies.

### §8.5 — Citations for New Sources

No new primary sources introduced in C02. All citations reference sources already documented in Track A (A01-A09) and Track B (B01-B16) files. C02 is purely synthetic — its analytical products derive from cross-referencing existing data.
