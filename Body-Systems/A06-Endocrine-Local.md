---
title: Local Endocrine Signaling
id: A06
version: 1.0
status: COMPLETE
date: 2026-07-28
scope: Paracrine/autocrine signaling systems at therapy sites — endogenous opioids, endocannabinoids, cutaneous neuroendocrine axis, oxytocin, eicosanoids, H₂S, peripheral serotonin — the chemical microenvironment that body therapies reshape
dependencies: [A01-Peripheral-Nervous-System, A02-Autonomic-Nervous-System, A04-Vascular-Lymphatic, A05-Neuroimmune-Interface]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# A06 — Local Endocrine Signaling

> **Position:** Track A file #8 — the LOCAL CHEMICAL MILIEU.
> A01 describes HOW signals travel through nerves. A05 describes HOW neurons and
> immune cells talk to each other. A04 describes HOW blood delivers effects to tissues.
> This file describes WHAT CHEMICAL MOLECULES are produced, released, and degraded
> locally at therapy sites, and how body therapies reshape this chemical environment.
>
> **Core Insight — The Local Chemical Milieu Principle:**
> Every therapy point exists within a dynamic CHEMICAL MICROENVIRONMENT where multiple
> paracrine/autocrine signaling systems operate simultaneously: endogenous opioids,
> endocannabinoids, eicosanoids, gasotransmitters, local hormones (oxytocin, cortisol,
> serotonin). These are NOT independent — they form an integrated LOCAL SIGNALING
> NETWORK with extensive cross-talk (e.g., CB2 activation triggers β-endorphin release;
> adenosine modulates both opioid and immune pathways).
>
> Body therapies work by RESHAPING this local chemical milieu: acupuncture releases
> adenosine and endogenous opioids; massage triggers oxytocin and endocannabinoids;
> exercise floods tissues with endocannabinoids and myokines. The therapeutic effect
> depends not on a single molecule but on the SHIFT IN CHEMICAL BALANCE at the tissue level.
>
> **Scope boundary:** This file covers the MOLECULES and their local signaling.
> A05 covers the neuroimmune CIRCUIT (cell-to-cell communication pathways).
> A04 covers the vascular DELIVERY SYSTEM. Neuropeptides (CGRP, SP) that serve
> primarily as neurotransmitters are detailed in A01/A05; here they appear only as
> components of the broader chemical milieu. Gasotransmitters NO and CO are detailed
> in A04; H₂S is covered here to complete the triad.

---

## Table of Contents

- §1 — Physical Architecture
- §2 — Function
- §3 — Pathways
- §4 — Relevance to Body-Based Therapy
- §5 — Key Research
- §6 — Human-Predictive-Drive Connection Points
- §7 — Individual Variation
- §8 — Open Questions
- §9 — Cross-References

---

## §1 — PHYSICAL ARCHITECTURE

### §1.1 — Overview: The Local Chemical Microenvironment

```
🟡 THE LOCAL CHEMICAL MILIEU — AN INTEGRATED SIGNALING NETWORK:

  At every point where body therapy contacts tissue, multiple
  paracrine/autocrine signaling systems are active simultaneously.
  These are NOT independent pathways — they form an integrated
  chemical network with extensive cross-talk.

  ┌───────────────────────────────────────────────────────────────────┐
  │  THE 6 LOCAL SIGNALING SYSTEMS COVERED IN THIS FILE:              │
  │                                                                   │
  │  ① ENDOGENOUS OPIOID SYSTEM          [§1.2]                      │
  │    β-endorphin, enkephalin, dynorphin                             │
  │    → Produced by: immune cells, keratinocytes, local neurons      │
  │    → Receptors: MOR, DOR, KOR on sensory nerve terminals          │
  │    → Function: LOCAL pain suppression                             │
  │                                                                   │
  │  ② ENDOCANNABINOID SYSTEM (endocannabinoid system)      [§1.3]                      │
  │    Anandamide (AEA), 2-AG                                         │
  │    → Produced by: keratinocytes, fibroblasts, immune cells        │
  │    → Receptors: CB1 on neurons, CB2 on immune cells               │
  │    → Function: pain modulation + immune regulation                │
  │                                                                   │
  │  ③ CUTANEOUS NEUROENDOCRINE AXIS     [§1.4]                      │
  │    CRH → POMC → ACTH + β-endorphin + α-MSH + cortisol           │
  │    → Produced by: keratinocytes, melanocytes, fibroblasts         │
  │    → = LOCAL HPA axis equivalent in skin                          │
  │    → Function: local stress response + immune modulation          │
  │                                                                   │
  │  ④ EICOSANOID SYSTEM                 [§1.5]                      │
  │    PGE2, PGI2, TXA2, lipoxins, leukotrienes                     │
  │    → Produced by: COX-1/2 and LOX in most cell types              │
  │    → Function: inflammation, pain, resolution                     │
  │                                                                   │
  │  ⑤ H₂S GASOTRANSMITTER              [§1.6]                      │
  │    Hydrogen sulfide (completing NO/CO/H₂S triad)                  │
  │    → Produced by: CBS, CSE, 3-MST enzymes                        │
  │    → Function: dose-dependent pain/anti-inflammation              │
  │                                                                   │
  │  ⑥ PERIPHERAL NEUROPEPTIDE HORMONES  [§1.7]                      │
  │    Oxytocin + peripheral serotonin (5-HT)                        │
  │    → Oxytocin: local + systemic, anti-nociceptive via OTR        │
  │    → 5-HT: 95% peripheral, dual pro/anti-nociceptive role        │
  │                                                                   │
  ├───────────────────────────────────────────────────────────────────┤
  │  ALREADY COVERED IN OTHER FILES (cross-reference only):           │
  │                                                                   │
  │  → Neuropeptides (CGRP, SP): A01 §3.4, A05 §2.1                 │
  │  → ATP/adenosine purinergic: A01 §3.7, A05 §3.2                 │
  │  → NO, CO gasotransmitters: A04 §3.3, §3.5                       │
  │  → Cytokines (TNF-α, IL-1β, IL-6, IL-10): A05 §2.3             │
  │  → SPMs (resolvins, protectins, maresins): A05 §2.4              │
  │  → Growth factors (NGF, BDNF, VEGF): A05 §1.3-§1.5             │
  │                                                                   │
  └───────────────────────────────────────────────────────────────────┘

  ⭐ CRITICAL CROSS-TALK:
    → CB2 activation → β-endorphin release from keratinocytes [§3.3]
    → Adenosine → modulates both opioid and immune pathways
    → PGE2 sensitizes nociceptors → opioids counter-regulate
    → Oxytocin → anti-sympathetic → changes entire milieu balance
    → H₂S ↔ NO cross-talk at TRPA1 channels
    → Local cortisol → modulates ALL inflammatory molecules

  🟡 The concept of an integrated chemical milieu at therapy sites
  is a synthesis across multiple research fields (opioid pharmacology,
  endocannabinoid research, cutaneous neuroendocrinology, eicosanoid
  biology). No single study has mapped the complete local signaling
  landscape; this integration is the contribution of this file.
```

### §1.2 — Endogenous Opioid System: Architecture

```
🟢 ENDOGENOUS OPIOID PEPTIDES — 4 FAMILIES:

  ┌──────────────────────────────────────────────────────────────────┐
  │  PRECURSOR → PEPTIDE → RECEPTOR → AFFINITY                      │
  │                                                                   │
  │  POMC        → β-endorphin     → μ (MOR) primary    ★ HIGHEST   │
  │              → α-MSH           → MC1R (melanocortin)             │
  │              → ACTH            → MC2R                             │
  │                                                                   │
  │  Proenkephalin → met-enkephalin → δ (DOR) primary               │
  │               → leu-enkephalin  → δ (DOR), μ (MOR)              │
  │                                                                   │
  │  Prodynorphin  → dynorphin A/B  → κ (KOR) primary               │
  │                                                                   │
  │  Proendomorphin → endomorphin-1 → μ (MOR) high affinity          │
  │                 → endomorphin-2 → μ (MOR)                        │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  PERIPHERAL PRODUCTION SITES:

  ┌──────────────────────────────────────────────────────────────────┐
  │  IMMUNE CELLS — PRIMARY PERIPHERAL SOURCE ⭐                      │
  │                                                                   │
  │  ALL opioid peptides identified in immune cells:                  │
  │    → β-endorphin = most prominent (from POMC)                    │
  │    → Also: met-enkephalin, dynorphin A                           │
  │                                                                   │
  │  TEMPORAL SEQUENCE IN INFLAMMATION:                               │
  │    Early (hours-days): neutrophils = 66% of opioid-containing    │
  │      cells (Rittner 2001, Machelska & Celik 2020)                │
  │    Late (days-weeks): monocytes/macrophages + lymphocytes = 73%  │
  │    → Activated T and B cells, M2 macrophages                     │
  │                                                                   │
  │  RELEASE TRIGGERS:                                                │
  │    → CRH (from local inflammatory cells) via CRH-R              │
  │    → IL-1β (from macrophages/mast cells)                         │
  │    → Noradrenaline (sympathetic nerve terminals)                  │
  │    → Cold water stress (Stein & Machelska)                       │
  │    → Release = Ca²⁺-dependent exocytosis                        │
  │      (chelating intracellular Ca²⁺ abolishes secretion)          │
  │                                                                   │
  │  🟢 Stein et al. 1990 (Lancet: peripheral opioid analgesia)     │
  │  🟢 Machelska & Celik 2020 (Immunol Lett: review)               │
  │  🟢 Celik et al. 2016 (Brain Behav Immun: Ca²⁺ mechanism)      │
  ├──────────────────────────────────────────────────────────────────┤
  │  KERATINOCYTES — SKIN OPIOID FACTORY                              │
  │                                                                   │
  │  → Express POMC → produce β-endorphin, α-MSH, ACTH              │
  │  → Also express MOR, DOR → autocrine signaling                   │
  │  → UV radiation → POMC upregulation → β-endorphin release       │
  │  → β-neoendorphin accelerates wound healing via MAPK/Erk1/2     │
  │  → EA upregulates β-endorphin in keratinocytes via CB2           │
  │                                                                   │
  │  🟢 Bigliardi-Qi et al. 2000 (J Invest Dermatol)                │
  │  🟢 Cheng et al. 2020 (Molecules: β-neoendorphin wound healing) │
  │  🟢 Su et al. 2012 (Mol Pain: EA CB2 → keratinocyte β-endorphin)│
  ├──────────────────────────────────────────────────────────────────┤
  │  OTHER PERIPHERAL SOURCES:                                        │
  │    → Chromaffin cells (adrenal medulla): β-endorphin             │
  │    → Fibroblasts, endothelial cells: in inflammatory context     │
  │    → DRG neurons: produce and transport to peripheral terminals  │
  └──────────────────────────────────────────────────────────────────┘

  PERIPHERAL OPIOID RECEPTORS:

  ┌──────────────────────────────────────────────────────────────────┐
  │  ON SENSORY NEURONS (DRG neurons → peripheral terminals):         │
  │                                                                   │
  │  MOR (μ): ~60% of DRG neurons, 74% co-express Nav1.8            │
  │    → Co-localize with TRPV1, TRPA1, PIEZO channels              │
  │    → PREFERENTIALLY on C-fiber nociceptors                       │
  │                                                                   │
  │  DOR (δ): ~67% of DRG neurons, co-localize with CGRP            │
  │    → More prominent in anti-inflammatory context                  │
  │                                                                   │
  │  KOR (κ): ~67% of DRG neurons                                   │
  │    → Activated by dynorphin                                       │
  │                                                                   │
  │  KEY: Under basal conditions, peripheral opioid receptors are    │
  │  largely INACTIVE. INFLAMMATION upregulates them:                 │
  │    → ↑ receptor expression                                       │
  │    → ↑ axonal transport to peripheral terminals                  │
  │    → Disruption of perineurial barrier → peptide ACCESS          │
  │    → = Peripheral opioid analgesia STRENGTHENS with inflammation │
  │    → = NO TOLERANCE develops at peripheral sites                 │
  │                                                                   │
  │  🟢 Mousa et al. 2025 (Cells: opioid receptors in human DRG)    │
  │  🟢 Stein et al. 1995 (NEJM: peripheral opioid analgesia)       │
  └──────────────────────────────────────────────────────────────────┘

  🟢 StatPearls 2024 (endogenous opioids review)
  🟢 Machelska & Celik 2020 (immune cell-mediated opioid analgesia)
```

### §1.3 — Endocannabinoid System: Architecture

```
🟢 THE ENDOCANNABINOID SYSTEM (endocannabinoid system) — ON-DEMAND LIPID SIGNALING:

  Unlike classical neurotransmitters (stored in vesicles, released
  by depolarization), endocannabinoids are synthesized ON DEMAND
  from membrane phospholipids and act as RETROGRADE messengers.

  ┌──────────────────────────────────────────────────────────────────┐
  │  TWO PRIMARY ENDOCANNABINOIDS:                                    │
  │                                                                   │
  │  ANANDAMIDE (AEA):                                               │
  │    Synthesis: NAPE-PLD (from membrane N-acyl phosphatidyl-       │
  │      ethanolamine)                                                │
  │    Degradation: FAAH (fatty acid amide hydrolase) — postsynaptic │
  │    Affinity: CB1 (partial agonist), TRPV1 (dual target ⭐)       │
  │    Half-life: minutes (rapidly degraded by FAAH)                  │
  │    Key property: LIPOPHILIC — crosses blood-brain barrier freely  │
  │                                                                   │
  │  2-ARACHIDONOYLGLYCEROL (2-AG):                                   │
  │    Synthesis: DAGLα/β (Ca²⁺-dependent)                           │
  │    Degradation: MAGL (monoacylglycerol lipase) — presynaptic     │
  │      + minor: ABHD6, ABHD12                                      │
  │    Affinity: CB1 + CB2 (full agonist at both)                    │
  │    Concentration: ~170× higher than AEA in brain tissue           │
  │    Key property: primary endogenous CB1/CB2 agonist               │
  │                                                                   │
  │  RELATED LIPID MEDIATORS:                                         │
  │    → PEA (palmitoylethanolamide): TRPV1, PPARα agonist           │
  │    → OEA (oleoylethanolamide): PPARα, satiety signal             │
  │    → Both degraded by FAAH → FAAH inhibition ↑ ALL of these     │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  RECEPTOR DISTRIBUTION IN PERIPHERAL TISSUES:

  ┌──────────────────────────────────────────────────────────────────┐
  │  CB1 RECEPTOR:                                                    │
  │    → DRG sensory neurons (major sub-population of nociceptors)   │
  │    → Transported to both PERIPHERAL and CENTRAL terminals        │
  │    → At peripheral terminal: PRESYNAPTIC GATEKEEPER              │
  │      → Inhibits voltage-gated Ca²⁺ channels → ↓ neurotransmitter│
  │        release (SP, CGRP) at 34-65%                              │
  │    → Also: keratinocytes, hair follicle, eccrine glands          │
  │    → Brain: highest density in cortex, hippocampus, basal ganglia│
  │                                                                   │
  │  CB2 RECEPTOR:                                                    │
  │    → Immune cells (highest: B cells > NK > T cells > macrophages)│
  │    → Keratinocytes, sebocytes, melanocytes                       │
  │    → Activation: ↓ TNF-α, IL-1β, IL-6, IL-2, IL-17, IFN-γ     │
  │    → = IMMUNE MODULATOR (anti-inflammatory)                       │
  │    → ⭐ CB2 activation → β-endorphin release from keratinocytes  │
  │      = endocannabinoid system-OPIOID CROSS-TALK [§3.3]                              │
  │                                                                   │
  │  🟢 Price et al. 2003 (Neuroscience: CB1 on DRG neurons)        │
  │  🟢 Turcotte et al. 2016 (Cell Mol Life Sci: CB2 on immune)     │
  │  🟢 Biro et al. 2009 (Trends Pharmacol Sci: cutaneous endocannabinoid system)      │
  │  🟢 Rukwied et al. 2011 (CB1 inhibits CGRP release 34-65%)     │
  └──────────────────────────────────────────────────────────────────┘

  CUTANEOUS endocannabinoid system — COMPLETE SIGNALING IN SKIN:

  Human keratinocytes possess ALL endocannabinoid system components:
    → CB1 receptor (functional)
    → AEA membrane transporter
    → FAAH (for AEA degradation)
    → NAPE-PLD (for AEA synthesis)
    → = COMPLETE autocrine endocannabinoid system loop in epidermis

  CB1 activation by AEA in keratinocytes:
    → Inhibits proliferation and differentiation (via PKC inhibition)
    → In wound healing: AEA/2-AG levels correlate with normal repair;
      ABSENT in hypertrophic scars (Scientific Reports 2020)
    → AEA also activates TRPV1 on keratinocytes (dual target)

  🟢 Maccarrone et al. 2003 (J Biol Chem: keratinocyte endocannabinoid system)
  🟢 Scientific Reports 2020 (AEA in wound healing)
```

### §1.4 — Cutaneous Neuroendocrine Axis: Skin as Endocrine Organ

```
🟢 SKIN — A FULLY FUNCTIONAL NEUROENDOCRINE ORGAN (Slominski):

  PARADIGM SHIFT:
    Traditional view: skin = passive barrier + target for hormones
    Slominski (2000-2024): skin = ACTIVE ENDOCRINE ORGAN that
    produces its own hormones including cortisol, β-endorphin,
    melatonin, serotonin, catecholamines, and vitamin D

  ┌──────────────────────────────────────────────────────────────────┐
  │  LOCAL HPA AXIS EQUIVALENT IN SKIN ⭐:                            │
  │                                                                   │
  │  The skin contains ALL elements of the hypothalamic-pituitary-   │
  │  adrenal axis, organized in functional cell-type-specific        │
  │  regulatory loops that IMITATE the HPA signaling hierarchy:      │
  │                                                                   │
  │  Stress/UV/inflammation                                           │
  │       ↓                                                          │
  │  CRH (corticotropin-releasing hormone)                           │
  │    Produced by: keratinocytes, fibroblasts, melanocytes,         │
  │      mast cells, endothelial cells, hair follicle epithelium     │
  │    Also: urocortin (CRH family member)                            │
  │       ↓                                                          │
  │  CRH binds CRH-R1 on keratinocytes/melanocytes                  │
  │       ↓                                                          │
  │  POMC upregulation → cAMP-dependent pathway                     │
  │       ↓                                                          │
  │  POMC PROCESSING PRODUCTS:                                        │
  │    → ACTH — stimulates local cortisol production                  │
  │    → β-endorphin — LOCAL OPIOID (connection to §1.2)             │
  │    → α-MSH — melanogenesis + anti-inflammatory                   │
  │       ↓                                                          │
  │  CORTISOL SYNTHESIS:                                              │
  │    → Melanocytes: CRH-induced cortisol + corticosterone          │
  │    → Hair follicles: fully functional cortisol synthesis          │
  │      (complete steroidogenic enzyme cascade: CYP11A1, CYP17A1,   │
  │       CYP21A2, CYP11B1)                                          │
  │    → Fibroblasts: CRH → POMC → ACTH → corticosterone            │
  │       ↓                                                          │
  │  NEGATIVE FEEDBACK:                                               │
  │    → Local cortisol → ↓ CRH expression (just like systemic HPA) │
  │    → = SELF-REGULATING LOCAL STRESS RESPONSE                      │
  │                                                                   │
  │  🟢 Slominski et al. 2000 (Physiol Rev: CRH and POMC in skin)   │
  │  🟢 Slominski et al. 2000 (Endocrine Rev: neuroendocrinology    │
  │    of the skin)                                                   │
  │  🟢 Slominski 2005 (CRH stimulates POMC in fibroblasts)         │
  │  🟢 Ito et al. 2005 (hair follicle cortisol synthesis)           │
  ├──────────────────────────────────────────────────────────────────┤
  │  LOCAL CORTISOL METABOLISM — 11β-HSD ENZYMES:                     │
  │                                                                   │
  │  11β-HSD1: cortisone (inactive) → cortisol (active)              │
  │    → In keratinocytes, fibroblasts, sebocytes                    │
  │    → Amplifies local glucocorticoid action                        │
  │                                                                   │
  │  11β-HSD2: cortisol (active) → cortisone (inactive)              │
  │    → Protective — prevents excess local cortisol                  │
  │    → Less expressed in skin than 11β-HSD1                        │
  │                                                                   │
  │  = Skin can REGULATE its own glucocorticoid exposure              │
  │    independently of systemic cortisol levels                      │
  ├──────────────────────────────────────────────────────────────────┤
  │  OTHER LOCAL HORMONE PRODUCTION:                                   │
  │                                                                   │
  │  VITAMIN D:                                                       │
  │    → UVB → 7-dehydrocholesterol → pre-vitamin D3 → vitamin D3   │
  │    → Local conversion: 25(OH)D → 1,25(OH)₂D (active) by CYP27B1│
  │    → Autocrine: anti-proliferative, pro-differentiation          │
  │    → Immunomodulatory: modulates Langerhans cells, T cells       │
  │                                                                   │
  │  MELATONIN:                                                       │
  │    → Synthesized from serotonin in keratinocytes, melanocytes    │
  │    → Pathway: tryptophan → 5-HTP → serotonin → NAS → melatonin │
  │    → Antioxidant, photoprotective, anti-inflammatory              │
  │    → Independent of pineal gland                                  │
  │                                                                   │
  │  CATECHOLAMINES:                                                   │
  │    → Keratinocytes express tyrosine hydroxylase (TH)              │
  │    → Produce: L-DOPA, dopamine, norepinephrine, epinephrine      │
  │    → Melanocytes: L-DOPA is melanin precursor AND catecholamine  │
  │                                                                   │
  │  SEROTONIN (5-HT):                                               │
  │    → Produced locally from tryptophan                             │
  │    → Keratinocytes express tryptophan hydroxylase (TPH1)         │
  │    → Detail in §1.7                                               │
  │                                                                   │
  │  ACETYLCHOLINE:                                                    │
  │    → Non-neuronal ACh produced by keratinocytes                   │
  │    → Paracrine regulator of proliferation, differentiation        │
  │                                                                   │
  │  🟢 Slominski et al. 2012 (Adv Anat Embryol Cell Biol:           │
  │    sensing the environment — skin neuroendocrine system)          │
  │  🟢 Slominski et al. 2011 (Dermato-Endocrinology: review)       │
  └──────────────────────────────────────────────────────────────────┘

  ⭐ THERAPY IMPLICATION:
    Every needle insertion or pressure application interacts with
    the skin's neuroendocrine system:
    → Local stress (CRH release) → POMC → β-endorphin (analgesic)
    → Simultaneously: α-MSH (anti-inflammatory)
    → + local cortisol modulation
    → = Skin is NOT just a passive entry point — it ACTIVELY
      participates in the therapeutic response

  🟢 Slominski et al. 2000-2024 (body of work on skin neuroendocrine)
```

### §1.5 — Eicosanoid System: Local Lipid Mediators

```
🟢 EICOSANOIDS — LIPID SIGNALING FROM MEMBRANE BREAKDOWN:

  Eicosanoids are oxygenated derivatives of 20-carbon polyunsaturated
  fatty acids (primarily arachidonic acid) that serve as LOCAL
  signaling molecules. They are NOT stored — produced on demand.

  ┌──────────────────────────────────────────────────────────────────┐
  │  SYNTHESIS PATHWAYS:                                              │
  │                                                                   │
  │  MEMBRANE PHOSPHOLIPIDS                                          │
  │       ↓ (phospholipase A2 — PLA2)                                │
  │  ARACHIDONIC ACID (AA)                                            │
  │       ↓                                                          │
  │  ┌─────────────────┬──────────────────┬────────────────────┐     │
  │  │ COX-1 pathway   │ COX-2 pathway    │ LOX pathways       │     │
  │  │ (constitutive)  │ (inducible ⭐)    │ (5-LOX, 12-LOX,   │     │
  │  │                 │                  │  15-LOX)           │     │
  │  ├─────────────────┼──────────────────┼────────────────────┤     │
  │  │ TXA2 (platelets)│ PGE2 ⭐ (major)   │ LTB4 (neutrophils) │     │
  │  │ PGI2 (endothel.)│ PGI2             │ LTC4/D4/E4 (mast)  │     │
  │  │ PGE2 (baseline) │ PGD2 (mast cells)│ LXA4 (resolution)  │     │
  │  │                 │ PGF2α            │ 15-HETE            │     │
  │  └─────────────────┴──────────────────┴────────────────────┘     │
  │                                                                   │
  │  COX-2 INDUCTION — THE KEY EVENT IN THERAPY:                      │
  │    → Induced by: mechanical stress, tissue damage, cytokines     │
  │    → Fibroblasts upregulate COX-2 under mechanical load          │
  │    → Result: PGE2 production at therapy site                     │
  │    → = NSAIDs (COX inhibitors) block this → ↓ pain AND          │
  │      ↓ some therapeutic effects of body therapies                │
  │                                                                   │
  │  ⭐ Ptgs2+ CPTCs (Zhang et al. 2025, FASEB J):                   │
  │    Cd34+/Pdgfra+ telocytes in fascia express Ptgs2 (= COX-2)    │
  │    → These cells function as "FORCE-IMMUNE AXIS"                 │
  │    → Respond to acupuncture mechanical stimulation               │
  │    → Activate M2 macrophages via IL-6–IL-6st–STAT3 pathway      │
  │    → Secrete IL-10 for anti-inflammatory effects                 │
  │    → = Molecular link: mechanical force → PGE2 → immune response│
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  PGE2 — THE CENTRAL LOCAL MEDIATOR:

  PGE2 is produced by nearly ALL cell types and acts through
  4 receptor subtypes (EP1-EP4) with OPPOSING effects:
    EP1: Ca²⁺ signaling → pro-nociceptive
    EP2: cAMP ↑ → anti-inflammatory, tissue repair
    EP3: cAMP ↓ → context-dependent
    EP4: cAMP ↑ → MOST IMPORTANT for pain sensitization
      → EP4 on nociceptors → PKA → sensitizes TRPV1, Nav1.8
      → = PRIMARY mechanism of inflammatory pain sensitization
      → = WHY NSAIDs reduce pain: ↓ PGE2 → ↓ EP4 activation

  PGE2 IN TISSUE REPAIR (dual role):
    → Early: pro-inflammatory (vasodilation, pain sensitization)
    → Later: promotes stem cell proliferation, tissue regeneration
    → = Excessive COX inhibition may IMPAIR healing

  🟢 Zhang et al. 2025 (FASEB J: Ptgs2+ CPTCs force-immune axis)
  🟢 Theranostics 2021 (PGE2 in tissue repair and regeneration)
  🟢 Smyth et al. 2009 (Physiol Rev: prostanoids review)
```

### §1.6 — Hydrogen Sulfide: The Third Gasotransmitter

```
🟢 H₂S — COMPLETING THE NO/CO/H₂S GASOTRANSMITTER TRIAD:

  Three gasotransmitters share key properties: low molecular weight,
  high membrane diffusibility, stimulus-dependent synthesis (NOT
  stored in vesicles), receptor-independent signaling.

  NO = A04 §3.3 (endothelial vasodilation, acupoint signaling)
  CO = A04 §3.5 (HO-1 pathway: cupping/gua sha → cytoprotection)
  H₂S = THIS SECTION

  ┌──────────────────────────────────────────────────────────────────┐
  │  SYNTHESIS:                                                       │
  │    CBS (cystathionine β-synthase): brain, liver, kidney           │
  │    CSE (cystathionine γ-lyase): cardiovascular, smooth muscle    │
  │    3-MST (3-mercaptopyruvate sulfurtransferase): mitochondria    │
  │    → All from L-cysteine substrate                               │
  │    → Expression in skin: CBS and CSE in keratinocytes,           │
  │      fibroblasts, endothelial cells                               │
  │                                                                   │
  │  SIGNALING MECHANISM:                                             │
  │    → Protein persulfidation (-SSH modification on cysteine        │
  │      residues) = primary post-translational mechanism             │
  │    → Also: TRPA1 channel activation (direct)                     │
  │    → KATP channel opening → neuronal hyperpolarization           │
  │    → Nrf2 pathway activation → antioxidant defense               │
  │                                                                   │
  │  DOSE-DEPENDENT DUAL ROLE ⭐:                                     │
  │    → LOW/physiological concentration:                             │
  │      ANTI-NOCICEPTIVE — opens KATP channels →                    │
  │      neuronal hyperpolarization → ↓ excitability                 │
  │      ANTI-INFLAMMATORY — NF-κB inhibition, Nrf2 ↑               │
  │    → HIGH/pathological concentration:                             │
  │      PRO-NOCICEPTIVE — activates TRPA1 on sensory neurons        │
  │      → Ca²⁺ influx → nociceptor sensitization                   │
  │      PRO-INFLAMMATORY — at very high levels                      │
  │                                                                   │
  │  H₂S ↔ NO CROSS-TALK:                                           │
  │    → H₂S stimulates TRPA1 → Ca²⁺ entry → eNOS activation → NO │
  │    → NO + H₂S → nitroxyl (HNO⁻) → activates TRPA1              │
  │    → = POSITIVE FEEDBACK LOOP at low levels                      │
  │    → Endothelium: both contribute to vasodilation                 │
  │                                                                   │
  │  H₂S ↔ CO CROSS-TALK:                                           │
  │    → CO inhibits CBS → ↓ H₂S production                         │
  │    → H₂S activates HO-1 → ↑ CO production                      │
  │    → = RECIPROCAL REGULATION between gasotransmitters             │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  BODY THERAPY RELEVANCE (limited evidence):
    → 🔴 Direct evidence for body therapy → H₂S levels = sparse
    → 🟡 Exercise likely modulates H₂S via shear stress → CSE ↑
    → 🟡 Meditation may involve H₂S as cardiovascular mediator
      (H₂S + oxytocin proposed as meditation effectors)
    → 🟡 EA at hippocampus: CBS-induced H₂S may INHIBIT
      EA-induced analgesia (Zhou et al. 2020)
    → = H₂S mostly operates through interaction with NO and CO
      pathways already activated by body therapies

  🟢 MDPI 2024 (H₂S: versatile molecule — comprehensive review)
  🟢 Springer 2025 (gasotransmitters NO, H₂S, CO in nociception)
  🟢 PMC 2022 (gasotransmitters in peripheral nervous system)
  🟢 Zhou et al. 2020 (CBS-H₂S inhibits EA analgesia)
```

### §1.7 — Peripheral Neuropeptide Hormones: Oxytocin and Serotonin

```
🟢 OXYTOCIN — THE TOUCH HORMONE:

  ┌──────────────────────────────────────────────────────────────────┐
  │  PERIPHERAL DISTRIBUTION AND ANTI-NOCICEPTION:                    │
  │                                                                   │
  │  SOURCES:                                                         │
  │    → Central: hypothalamic PVN and SON → posterior pituitary      │
  │    → Peripheral: also locally produced — emerging evidence        │
  │    → Released systemically AND acts at peripheral targets         │
  │                                                                   │
  │  RECEPTORS:                                                       │
  │    → OTR (oxytocin receptor) on cutaneous nociceptive fibers:    │
  │      C fibers and Aδ fibers (NOT Aβ fibers)                      │
  │      = Selectively modulates PAIN fibers, not touch fibers       │
  │    → OTR in dorsal horn spinal cord neurons                      │
  │    → OTR on immune cells (anti-inflammatory)                     │
  │                                                                   │
  │  ANTI-NOCICEPTIVE MECHANISM:                                      │
  │    → Direct: OTR on C-fiber terminals → reduces excitability     │
  │    → Spinal: rebalances dorsal horn circuits (2026 bioRxiv):     │
  │      ↑ inhibitory responses + ↓ excitatory responses             │
  │      preferential modulation of C-fiber inputs ⭐                 │
  │    → Anti-sympathetic: inhibits CRF release, actions at          │
  │      locus coeruleus, RVLM, sympathetic ganglia                  │
  │      (Uvnäs-Moberg et al. 2024)                                  │
  │    → = Changes internal state from STRESS to CALM,                │
  │      which modulates sensory processing at spinal level          │
  │                                                                   │
  │  OXYTOCIN AND MASSAGE/TOUCH:                                      │
  │    → Massage-like stroking in rats (20 strokes/min, 5 min):      │
  │      ↑ oxytocin, sedation, ↓ cortisol, ↓ BP, ↓ HR,             │
  │      ↑ nociceptive thresholds (Uvnäs-Moberg)                     │
  │    → Pattern comparable to HIGH-DOSE oxytocin administration     │
  │    → Linked to increased α2-adrenoceptor activity                │
  │    → OT antagonist reverses thermal (NOT mechanical)              │
  │      antinociception from massage → partial mediator             │
  │    → Intranasal OT enhances pleasantness of gentle stroking      │
  │      via CT afferents (eLife 2023)                                │
  │    → Subcutaneous OT injection reduces heat pain (RCT, 2024)     │
  │                                                                   │
  │  🟢 Uvnäs-Moberg et al. 2024 (oxytocin patterns with touch)     │
  │  🟢 Frontiers 2026 (oxytocin release patterns and effects)       │
  │  🟢 bioRxiv 2026 (OT modulation of spinal circuits in massage)  │
  │  🟢 eLife 2023 (OT enhances responses to social touch)          │
  └──────────────────────────────────────────────────────────────────┘

🟢 PERIPHERAL SEROTONIN (5-HT) — THE DUAL-ROLE MEDIATOR:

  ┌──────────────────────────────────────────────────────────────────┐
  │  95% OF BODY SEROTONIN IS PERIPHERAL:                             │
  │                                                                   │
  │  SOURCES:                                                         │
  │    → Enterochromaffin (EC) cells of GI tract: PRIMARY producer   │
  │    → Platelets: store and transport (uptake via SERT)             │
  │    → Keratinocytes: local synthesis from tryptophan (TPH1)       │
  │    → Mast cells: stored and released on degranulation             │
  │    → = Available at ANY tissue manipulation site                  │
  │                                                                   │
  │  PAIN MODULATION — DUAL ROLE:                                     │
  │    PERIPHERALLY: predominantly PRO-NOCICEPTIVE                    │
  │      → 5-HT3 (ionotropic): direct nociceptor activation         │
  │        EC cells → 5-HT → 5-HT3 on vagal/spinal afferents       │
  │      → 5-HT2A (metabotropic): sensitizes DRG neurons            │
  │        contributes to inflammatory and neuropathic pain          │
  │      → Platelets release stored 5-HT at injury sites →          │
  │        sensitizes local nociceptors                               │
  │                                                                   │
  │    CENTRALLY: predominantly ANTI-NOCICEPTIVE                      │
  │      → Descending serotonergic pathways from RVM (brainstem)     │
  │      → 5-HT1A/1B receptors: inhibitory (pain suppression)       │
  │      → BUT: 5-HT2A/3 become facilitatory after nerve injury     │
  │        → = Shift from anti-nociceptive → pro-nociceptive         │
  │          in chronic pain states                                   │
  │                                                                   │
  │  BODY THERAPY MODULATION:                                         │
  │    → Acupuncture stimulates 5-HT release both peripherally      │
  │      (at acupoints) and centrally                                 │
  │    → EA at GB20: antinociceptive via peripheral + central 5-HT   │
  │      in migraine models                                           │
  │    → Mast-cell-derived 5-HT at acupoints contributes to         │
  │      ATP release for acupuncture analgesia                       │
  │    → Exercise: meta-analysis confirms ↑ circulating 5-HT (2024) │
  │    → Massage: unclear direct effect on peripheral 5-HT           │
  │                                                                   │
  │  🟢 PMC 2024 (peripheral serotonin and gut-brain axis)           │
  │  🟢 Front Biosci 2023 (mast cell serotonin at acupoints)        │
  │  🟢 Wiley 2016 (EA at GB20 via 5-HT in migraine)                │
  │  🟢 J Neurosci 2013 (descending serotonergic facilitation)      │
  └──────────────────────────────────────────────────────────────────┘
```

---

## §2 — FUNCTION

### §2.1 — Pain Modulation: The Local Analgesic Balance

```
🟡 PAIN AT ANY TISSUE SITE = BALANCE BETWEEN PRO- AND ANTI-NOCICEPTIVE
  LOCAL CHEMICAL SIGNALS:

  ┌──────────────────────────────────────────────────────────────────┐
  │  ANTI-NOCICEPTIVE (pain-reducing):                                │
  │                                                                   │
  │  → β-endorphin (MOR) — from immune cells, keratinocytes         │
  │  → Enkephalin (DOR) — from immune cells                          │
  │  → Anandamide (CB1) — inhibits SP/CGRP release 34-65%           │
  │  → 2-AG (CB1/CB2) — neuronal + immune anti-inflammatory         │
  │  → Adenosine (A1) — direct analgesia (Goldman 2010)              │
  │  → Oxytocin (OTR) — modulates C-fiber input at spinal level     │
  │  → H₂S at low concentration (KATP) — hyperpolarization          │
  │  → Local cortisol — anti-inflammatory                             │
  │  → α-MSH — anti-inflammatory (from POMC)                        │
  │  → IL-10, SPMs — resolution mediators (detail: A05 §2.3-2.4)   │
  │                                                                   │
  ├──────────────────────────────────────────────────────────────────┤
  │  PRO-NOCICEPTIVE (pain-amplifying):                               │
  │                                                                   │
  │  → PGE2 (EP4) — sensitizes TRPV1, Nav1.8 on nociceptors        │
  │  → 5-HT peripherally (5-HT3, 5-HT2A) — direct activation      │
  │  → Bradykinin — direct nociceptor activation (A05 §2.3)         │
  │  → TNF-α, IL-1β — sensitize nociceptors (A05 §2.3)             │
  │  → H₂S at high concentration (TRPA1) — Ca²⁺ influx             │
  │  → NGF — upregulates TRPV1, promotes nerve sprouting            │
  │  → ATP at high concentration (P2X3) — pain signal (A01 §3.7)   │
  │                                                                   │
  ├──────────────────────────────────────────────────────────────────┤
  │  ⭐ THERAPY = SHIFTING THE BALANCE TOWARD ANTI-NOCICEPTIVE:       │
  │                                                                   │
  │  Body therapies activate MULTIPLE anti-nociceptive pathways      │
  │  simultaneously:                                                  │
  │    Acupuncture → opioids + adenosine + endocannabinoids          │
  │    Massage → oxytocin + endocannabinoids + opioids               │
  │    Exercise → endocannabinoids + opioids + SPMs                  │
  │                                                                   │
  │  While also REDUCING pro-nociceptive signals:                     │
  │    → ↓ sympathetic tone → ↓ NE-driven inflammation              │
  │    → ↓ cortisol chronic elevation → ↓ PGE2 over-production      │
  │    → ↑ resolution mediators → active inflammation clearance      │
  │                                                                   │
  │  The net effect = CHEMICAL MILIEU SHIFT                           │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘
```

### §2.2 — Inflammation Control: Local Orchestration

```
🟡 LOCAL INFLAMMATION = ORCHESTRATED BY CHEMICAL MILIEU:

  The same tissue site simultaneously produces molecules that
  PROMOTE and RESOLVE inflammation. The balance determines outcome.

  TEMPORAL SEQUENCE:
    Minutes: PGE2 + leukotrienes → vasodilation, recruitment
    Hours: cytokines (TNF-α, IL-1β) → amplification
    Days: lipoxins → class-switching signal ("stop recruiting")
    Days-weeks: SPMs (resolvins, maresins) → active resolution
    Weeks: TGF-β, VEGF → tissue repair

  THERAPY INTERVENTION POINTS:
    → Acupuncture needle at early phase → accelerates to resolution
    → Massage at chronic phase → shifts milieu toward resolution
    → Exercise → ↑ SPM precursors + ↑ endocannabinoid anti-inflammatory

  🟡 Synthesis from: Serhan 2015 (SPMs), A05 §2.4, eicosanoid literature
```

### §2.3 — Tissue Repair: Local Chemical Drivers

```
🟢 LOCAL CHEMICAL SIGNALS DRIVE TISSUE REPAIR:

  Growth factors and repair signals from the local chemical milieu:

  → PGE2 (EP2/EP4): promotes stem cell proliferation
  → TGF-β: ECM deposition, fibroblast activation
  → VEGF: angiogenesis (new blood vessel formation, A04 §3.6)
  → FGF: proliferation, wound repair
  → EGF: epithelial regeneration
  → β-neoendorphin: accelerates keratinocyte migration (Cheng 2020)
  → AEA/2-AG: correlate with normal wound healing
  → CGRP → M2 macrophage → repair cascade (A05 §3.6)
  → Local cortisol: modulates repair-inflammation balance

  ⭐ EXCESSIVE COX INHIBITION (NSAIDs) MAY IMPAIR REPAIR:
    PGE2 is both pro-inflammatory AND pro-repair
    Blocking COX-2 → ↓ pain BUT also ↓ regenerative signaling
    = Potential trade-off in body therapy context

  🟢 Theranostics 2021 (PGE2 in tissue repair)
  🟢 Scientific Reports 2020 (AEA in wound healing)
```

### §2.4 — Local Stress Response: Cutaneous Adaptation

```
🟡 SKIN RESPONDS TO LOCAL STRESS INDEPENDENTLY:

  Mechanical stress (needle, pressure) → local CRH release →
  POMC processing → β-endorphin + α-MSH + local cortisol

  This represents a LOCAL STRESS RESPONSE that:
    → Provides immediate analgesia (β-endorphin)
    → Reduces local inflammation (α-MSH, cortisol)
    → Self-regulates via negative feedback (cortisol → ↓ CRH)
    → Operates INDEPENDENTLY of systemic HPA axis

  Cytokine modulation:
    IL-1β → upregulates POMC mRNA, POMC peptides, and MSH receptors
    → = Inflammation AMPLIFIES the local endocrine response
    → = More β-endorphin produced in inflamed tissue
    → Consistent with Stein: peripheral opioid analgesia ↑ with
      inflammation duration

  🟡 Synthesis from Slominski body of work + Stein peripheral opioid model
```

---

## §3 — PATHWAYS

### §3.1 — Peripheral Opioid Analgesia Pathway

```
🟢 PATHWAY 1 — IMMUNE CELL-DERIVED PERIPHERAL OPIOID ANALGESIA:

  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  INFLAMMATION/TISSUE INJURY (including therapy stimulus)          │
  │       ↓                                                          │
  │  Step 1: IMMUNE CELL RECRUITMENT                                  │
  │    → Selectins (L, P) → rolling of opioid-containing leukocytes │
  │    → ICAM-1 → adhesion and diapedesis into inflamed tissue       │
  │    → Chemokines (CXCL1, CXCL2/3) guide migration                │
  │    → Early: neutrophils (66% opioid-containing)                  │
  │    → Late: macrophages + lymphocytes (73%)                       │
  │       ↓                                                          │
  │  Step 2: OPIOID RELEASE TRIGGERS                                  │
  │    → CRH (from local inflammatory cells) binds CRH-R →          │
  │      exocytosis of β-endorphin                                   │
  │    → IL-1β (from macrophages) → opioid release                   │
  │    → Noradrenaline (sympathetic terminals) → opioid release      │
  │    → Release = Ca²⁺-dependent (chelation abolishes it)           │
  │       ↓                                                          │
  │  Step 3: PERIPHERAL OPIOID RECEPTOR ACTIVATION                    │
  │    → β-endorphin binds MOR on C-fiber terminal                   │
  │    → MOR → Gαi/o → ↓ adenylyl cyclase → ↓ cAMP → ↓ PKA         │
  │    → PKA normally sensitizes TRPV1 + Nav1.8                      │
  │      → WITHOUT PKA: channels NOT sensitized = ↓ pain             │
  │    → Gβγ subunits:                                                │
  │      → Open GIRK (Kir3) K⁺ channels → HYPERPOLARIZATION         │
  │      → Inhibit N-type + P/Q-type Ca²⁺ channels →                │
  │        ↓ neurotransmitter release                                 │
  │      → Inhibit TRPM3 channels (Dembla et al. 2017, eLife)       │
  │    → NET EFFECT: reduced nociceptor excitability at peripheral   │
  │      terminal = LOCAL ANALGESIA without CNS involvement           │
  │       ↓                                                          │
  │  Step 4: INFLAMMATION-DEPENDENT AMPLIFICATION                     │
  │    → Inflammation ↑ opioid receptor expression on DRG neurons    │
  │    → Inflammation ↑ axonal transport to peripheral terminals     │
  │    → Inflammation disrupts perineurial barrier → access          │
  │    → TRPV1 activation paradoxically ↓ MOR desensitization        │
  │      (β-arrestin2 diverted via Ca²⁺/MAPK)                       │
  │    → = NO TOLERANCE at peripheral sites during inflammation ⭐   │
  │    → = Analgesia STRENGTHENS over time (opposite of central)     │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  🟢 Stein et al. 1990, 1995 (Lancet, NEJM: peripheral opioid analgesia)
  🟢 Machelska & Celik 2020 (Immunol Lett: review)
  🟢 Rittner et al. 2001, 2006 (leukocyte recruitment mechanisms)
  🟢 Dembla et al. 2017 (eLife: MOR inhibition of TRPM3)
  🟢 Mousa et al. 2025 (Cells: opioid receptors in human DRG)
```

### §3.2 — Endocannabinoid Analgesia Pathway

```
🟢 PATHWAY 2 — THREE-LEVEL endocannabinoid system ANALGESIA:

  Electroacupuncture engages the endocannabinoid system at THREE levels —
  peripheral, spinal, and supraspinal — constituting a
  multi-level endocannabinoid analgesic mechanism DISTINCT
  FROM but SYNERGISTIC with the opioid pathway.

  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  LEVEL 1 — PERIPHERAL (tissue level):                             │
  │    → Tissue manipulation → AEA/2-AG produced on demand           │
  │    → CB2 on immune cells → ↓ cytokine release                   │
  │    → CB1 on C-fiber terminals → ↓ SP/CGRP release               │
  │      (presynaptic gatekeeper: 34-65% reduction)                  │
  │    → EA ↑ AEA in inflamed skin tissue                            │
  │    → Peripherally restricted FAAH inhibitor (URB937)             │
  │      produces CB1-mediated analgesia WITHOUT central effects     │
  │                                                                   │
  │  LEVEL 2 — SPINAL (dorsal horn):                                  │
  │    → CB1 upregulation in spinal cord after EA                    │
  │    → Combined-acupoint EA activates spinal endocannabinoid system signaling         │
  │    → Modulates synaptic transmission in laminae I-II              │
  │                                                                   │
  │  LEVEL 3 — SUPRASPINAL (PAG):                                    │
  │    → CB1 on GABAergic neurons in ventrolateral PAG (vlPAG)       │
  │    → EA activates CB1 → disinhibits descending anti-nociceptive │
  │      output from vlPAG to spinal cord                            │
  │    → CB1 knockout on GABAergic neurons ABOLISHES EA analgesia    │
  │    → AM251 (CB1 antagonist) blocks this effect                   │
  │                                                                   │
  │  ⭐ DUAL FAAH/MAGL INHIBITION — AMPLIFIED EFFECT:                │
  │    Simultaneous FAAH + MAGL inhibition:                           │
  │    → ↑ AEA + ↑ 2-AG (both elevated)                             │
  │    → SIMULTANEOUSLY ↓ arachidonic acid (shared substrate)        │
  │    → Less AA → less PGE2 (pro-nociceptive)                      │
  │    → = SYNERGISTIC: more anti-nociceptive + less pro-nociceptive │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  🟢 Clapper et al. 2010 (Nat Neurosci: URB937 peripheral FAAH)
  🟢 Yuan et al. 2018 (Front Neurosci: CB1 on vlPAG GABAergic)
  🟢 Su et al. 2012 (Mol Pain: EA and peripheral CB2)
  🟢 Ding et al. 2023 (PLOS ONE: EA peripheral CB1 pathway)
  🟢 Su et al. 2025 (Acupunct Herb Med: endocannabinoid system review)
  🟢 Guindon & Bhavsar 2024 (Expert Opin Ther Targets: endocannabinoid system review)
```

### §3.3 — Endocannabinoid System-Opioid Cross-Talk: The Synergistic Cascade

```
🟢 PATHWAY 3 — CB2 → β-ENDORPHIN RELEASE — CROSS-SYSTEM SYNERGY:

  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  DISCOVERY: The endocannabinoid and opioid systems are NOT       │
  │  independent — they form a SYNERGISTIC analgesic cascade.        │
  │                                                                   │
  │  EA / tissue manipulation                                         │
  │       ↓                                                          │
  │  ↑ Anandamide (AEA) in inflamed tissue                           │
  │       ↓                                                          │
  │  AEA binds CB2 receptors on:                                      │
  │    → KERATINOCYTES                                                │
  │    → MACROPHAGES                                                  │
  │    → T-LYMPHOCYTES                                                │
  │       ↓                                                          │
  │  CB2 → Gi/o → Gβγ subunits → MAPK pathway                      │
  │    (specifically Gβγ, NOT Gαs — Su et al. 2012)                  │
  │    (MAPK kinase inhibition abolishes the response)               │
  │       ↓                                                          │
  │  β-ENDORPHIN RELEASE from keratinocytes + immune cells           │
  │       ↓                                                          │
  │  β-endorphin binds MOR on C-fiber terminals                      │
  │       ↓                                                          │
  │  PERIPHERAL OPIOID ANALGESIA (§3.1 pathway)                      │
  │                                                                   │
  │  ⭐ IMPLICATION:                                                   │
  │    EA simultaneously activates:                                   │
  │    → endocannabinoid system directly (AEA/2-AG production)                           │
  │    → Opioid system INDIRECTLY via CB2 → β-endorphin              │
  │    → = TWO analgesic systems activated by ONE stimulus            │
  │    → = Explains why blocking EITHER CB2 OR MOR partially         │
  │      reduces EA analgesia (but neither fully abolishes it)       │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  EA ALSO INCREASES CB2 EXPRESSION:
    → EA increases CB2 receptor expression on keratinocytes
      and infiltrating inflammatory cells at the site
    → = EA upregulates the PATHWAY itself, not just the ligand

  🟢 Su et al. 2012 (Mol Pain: CB2 → β-endorphin)
  🟢 Su et al. 2012 (J Pain: EA increases CB2 on keratinocytes)
  🟢 Su et al. 2015 (Mol Neurobiol: CB2 signaling mechanism)
```

### §3.4 — Adenosine-Opioid Integration

```
🟢 PATHWAY 4 — ADENOSINE AS PARALLEL ANALGESIC:

  Goldman et al. 2010 (Nature Neuroscience) demonstrated that
  acupuncture analgesia has a NON-OPIOID component mediated
  by local adenosine signaling.

  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  Acupuncture needle rotation → tissue deformation                │
  │       ↓                                                          │
  │  Fibroblasts, mast cells, keratinocytes release ATP              │
  │  (pannexin-1 hemichannels, vesicular release — A01 §3.7)        │
  │       ↓                                                          │
  │  ECTOENZYMES: CD39 → CD73 → ATP → ADP → AMP → ADENOSINE        │
  │       ↓                                                          │
  │  Adenosine at interstitial levels ↑ 24-fold at acupoint          │
  │       ↓                                                          │
  │  A1 receptor on nociceptors → ANALGESIA                          │
  │    → Confirmed: A1R knockout mice → NO acupuncture analgesia    │
  │    → A1R agonist injection replicates acupuncture effect          │
  │       ↓                                                          │
  │  AMPLIFICATION:                                                    │
  │    → Inhibiting adenosine degradation enzymes →                  │
  │      TRIPLED analgesic duration                                   │
  │    → Deoxycoformycin (EHNA, adenosine deaminase inhibitor)       │
  │      potentiated acupuncture analgesia                            │
  │                                                                   │
  │  PARALLEL BUT COMPLEMENTARY TO OPIOID PATHWAY:                   │
  │    → Adenosine pathway = rapid, local, non-opioid               │
  │    → Opioid pathway = slower (immune cell recruitment), longer   │
  │    → Together: multi-mechanism analgesia                         │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  CONNECTION TO PURINERGIC PATHWAY (A01 §3.7, A05 §3.2):
    → ATP (pro-nociceptive at P2X3) → enzymatic conversion →
      adenosine (anti-nociceptive at A1)
    → = TIME-DEPENDENT SWITCH from alarm to analgesia
    → A06 adds: this is part of the LOCAL CHEMICAL MILIEU that
      shifts balance from pro- to anti-nociceptive over time

  🟢 Goldman et al. 2010 (Nature Neuroscience)
  🟢 Takano et al. 2012 (adenosine anti-nociception mechanism)
```

### §3.5 — Oxytocin Pathway: Touch-Mediated Analgesia

```
🟢 PATHWAY 5 — OXYTOCIN: FROM TOUCH TO SYSTEMIC CALM:

  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  GENTLE REPETITIVE TOUCH (massage, stroking)                      │
  │       ↓                                                          │
  │  CT afferents activated (optimal 1-10 cm/s, A01 §1.4)           │
  │  + Mechanoreceptors in skin + fascia                              │
  │       ↓                                                          │
  │  Ascending signal → posterior insular cortex → PVN hypothalamus  │
  │       ↓                                                          │
  │  OXYTOCIN RELEASE:                                                │
  │    → Systemic (posterior pituitary → bloodstream)                │
  │    → Central (direct hypothalamic → spinal cord projection)      │
  │       ↓                                                          │
  │  PERIPHERAL EFFECTS:                                              │
  │    → OTR on C/Aδ fiber terminals → ↓ nociceptor excitability    │
  │    → OTR on immune cells → anti-inflammatory                     │
  │    → Anti-sympathetic: ↓ CRF, ↓ NE (via LC, RVLM, ganglia)    │
  │    → ↓ cortisol, ↓ BP, ↓ HR, ↑ GI motility                    │
  │       ↓                                                          │
  │  SPINAL EFFECTS (2026 bioRxiv — new mechanism):                   │
  │    → OT neurons project DIRECTLY to dorsal horn                  │
  │    → OT rebalances dorsal horn circuits:                         │
  │      ↑ inhibitory (GABAergic) responses                          │
  │      ↓ excitatory responses                                      │
  │      PREFERENTIAL modulation of C-fiber inputs (pain)            │
  │    → = Touch-induced internal state change MODULATES              │
  │      sensory processing at SPINAL level                          │
  │    → = Mechanism by which rewarding touch directly               │
  │      reduces pain signaling                                       │
  │                                                                   │
  │  NET OUTCOME:                                                     │
  │    → Immediate: anti-nociception (OTR on fibers)                 │
  │    → Short-term: autonomic shift (↓ sympathetic, ↑ calm)        │
  │    → Long-term: α2-adrenoceptor-mediated sedation/calm pattern  │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  ⭐ MASSAGE IS NOT "JUST RELAXATION":
    The oxytocin pathway provides a specific MOLECULAR mechanism
    for how gentle touch produces:
    → Pain relief (OTR on nociceptors + spinal modulation)
    → Blood pressure reduction (anti-sympathetic)
    → Anxiety reduction (↓ CRF → ↓ HPA activation)
    → Enhanced social bonding (central OT effects)

  🟢 Uvnäs-Moberg (body of work: oxytocin and anti-stress)
  🟢 Frontiers 2025 (touch as emotion regulation)
  🟢 bioRxiv 2026 (OT spinal circuit modulation in massage)
```

### §3.6 — Frequency-Dependent Opioid Release (Han Ji-Sheng)

```
🟢 PATHWAY 6 — EA FREQUENCY SELECTS OPIOID TYPE:

  Ji-Sheng Han (Peking University) discovered that electroacupuncture
  frequency DETERMINES which endogenous opioid peptides are released —
  one of the most important findings in acupuncture research.

  ┌──────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  2 Hz (low frequency):                                            │
  │    → Releases: enkephalin + β-endorphin + endomorphin            │
  │    → Activates: μ (MOR) + δ (DOR) receptors                     │
  │    → Blocked by: intrathecal met-enkephalin antibodies           │
  │    → Clinical: deep, sustained analgesia                         │
  │    → Better for: chronic pain, addiction withdrawal               │
  │                                                                   │
  │  100 Hz (high frequency):                                         │
  │    → Releases: dynorphin (selectively)                            │
  │    → Activates: κ (KOR) receptors                                │
  │    → Blocked by: intrathecal dynorphin A antibodies              │
  │    → Clinical: rapid onset, shorter duration                     │
  │    → Better for: acute pain, surgical analgesia                  │
  │                                                                   │
  │  2/100 Hz alternating (DD mode, 3s each):                        │
  │    → Releases: ALL FOUR opioid peptides simultaneously ⭐        │
  │    → Activates: μ + δ + κ receptors                              │
  │    → MAXIMAL therapeutic effect (cross-tolerance avoided)        │
  │    → = Clinically superior to either frequency alone              │
  │                                                                   │
  │  15 Hz (intermediate):                                            │
  │    → Releases: enkephalin + β-endorphin AND dynorphin            │
  │    → Mixed activation pattern                                    │
  │                                                                   │
  └──────────────────────────────────────────────────────────────────┘

  MECHANISM:
    Different EA frequencies activate different neural pathways
    in spinal cord and brainstem → each pathway preferentially
    triggers release of specific opioid peptides from specific
    neuronal populations.

  CLINICAL APPLICATION:
    → Dose-effect relationship confirmed (2024 World J Acupunct):
      EA parameters (frequency, intensity, duration) can be
      PRESCRIBED like medication dosing
    → Cross-tolerance: continuous single-frequency → tolerance
      develops; alternating frequencies → sustained effect

  🟢 Han 2003 (Neurosci Lett: 2Hz endomorphin-1 but not 100Hz)
  🟢 Han 2004 (Neurosci Lett: frequency-dependent release review)
  🟢 Han 2013 (Int Rev Neurobiol: comprehensive review)
  🟢 2024 World J Acupunct (dose-effect relationship update)
  🟢 Fei et al. 1987 (spinal cord opioid levels during EA)
```

---

## §4 — RELEVANCE TO BODY-BASED THERAPY

### §4.1 — Core Principle: The Local Chemical Milieu Principle

```
🟡 SYNTHESIS — THE LOCAL CHEMICAL MILIEU PRINCIPLE:

  ┌───────────────────────────────────────────────────────────────────┐
  │                                                                   │
  │  [BODY THERAPY INPUT]                                             │
  │    needle, pressure, heat, stretch, movement                      │
  │         ↓                                                         │
  │  RESHAPES the local chemical microenvironment:                    │
  │                                                                   │
  │  ┌─────────────────────────────────────────────────────────┐     │
  │  │  BEFORE therapy:                                          │     │
  │  │    Pro-nociceptive milieu (chronic pain):                 │     │
  │  │    PGE2 ↑ | TNF-α ↑ | 5-HT3 ↑ | bradykinin ↑          │     │
  │  │    β-endorphin ↓ | AEA ↓ | adenosine baseline           │     │
  │  │    = Balance shifted toward PAIN + INFLAMMATION           │     │
  │  └──────────────────────────────────┬────────────────────────┘     │
  │                                     │ therapy                      │
  │  ┌──────────────────────────────────▼────────────────────────┐     │
  │  │  AFTER therapy:                                            │     │
  │  │    Anti-nociceptive milieu (therapeutic):                  │     │
  │  │    β-endorphin ↑ | AEA ↑ | adenosine ↑                   │     │
  │  │    oxytocin ↑ | IL-10 ↑ | SPMs ↑                         │     │
  │  │    PGE2 normalized | cortisol modulated                   │     │
  │  │    = Balance shifted toward ANALGESIA + RESOLUTION         │     │
  │  └─────────────────────────────────────────────────────────────┘     │
  │                                                                   │
  │  ⭐ KEY INSIGHTS:                                                  │
  │                                                                   │
  │  1. MULTI-SYSTEM ACTIVATION: no therapy activates just ONE       │
  │     signaling system. Acupuncture simultaneously triggers         │
  │     opioids, endocannabinoids, adenosine, neurogenic              │
  │     inflammation → explains why blocking any ONE pathway          │
  │     only PARTIALLY reduces the effect                             │
  │                                                                   │
  │  2. CROSS-TALK AMPLIFICATION: systems synergize:                  │
  │     CB2 → β-endorphin (endocannabinoid system drives opioid release)               │
  │     FAAH inhibition → ↑ AEA + ↓ AA → ↓ PGE2                    │
  │     Adenosine → modulates both opioid and immune pathways        │
  │     = MORE than sum of parts                                      │
  │                                                                   │
  │  3. PARAMETER-DEPENDENT: therapy parameters determine the         │
  │     chemical profile of the milieu shift:                         │
  │     EA 2Hz → enkephalin/endorphin (sustained analgesia)          │
  │     EA 100Hz → dynorphin (rapid onset)                            │
  │     Gentle touch → oxytocin (calm + anti-nociception)            │
  │     Deep manipulation → AEA 168% ↑ (endocannabinoid)             │
  │     Exercise → AEA + 2-AG + opioids (runner's high)              │
  │                                                                   │
  │  4. INFLAMMATION-ENHANCED: peripheral opioid and endocannabinoid system              │
  │     analgesia STRENGTHENS with inflammation — receptors           │
  │     upregulated, barrier permeability increased — body            │
  │     therapies are MOST effective where they are MOST needed      │
  │                                                                   │
  └───────────────────────────────────────────────────────────────────┘

  🟡 This principle integrates:
     A01 (purinergic signaling, axon reflex neuropeptides)
     A04 (NO at acupoints, HO-1 pathway)
     A05 (neuroimmune pathways, SPMs, cytokines)
     + THIS FILE (opioids, endocannabinoid system, oxytocin, cutaneous endocrine,
       eicosanoids, H₂S, cross-talk mechanisms)
     into a unified LOCAL CHEMICAL SIGNALING framework.
```

### §4.2 — Therapy-Specific Chemical Signatures

```
🟡 EACH THERAPY PRODUCES A DISTINCT CHEMICAL MILIEU PROFILE:

  ┌───────────────┬──────────────────────────────────────────────────┐
  │ Therapy       │ Chemical Milieu Signature                        │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ Acupuncture   │ ① Adenosine ↑ 24× (Goldman 2010, A1 analgesia) │
  │ (manual)      │ ② β-endorphin ↑ (immune cells + keratinocytes) │
  │               │ ③ AEA ↑ in inflamed tissue (CB2 pathway)       │
  │               │ ④ CGRP/SP (neurogenic inflammation → resolution)│
  │               │ ⑤ ATP → purinergic cascade                     │
  │               │ ⑥ Local CRH → POMC → β-endorphin + α-MSH      │
  │               │ = BROADEST chemical milieu shift                 │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ EA (2Hz)      │ All of above PLUS:                               │
  │               │ → Enkephalin + endomorphin + β-endorphin ↑      │
  │               │ → MOR + DOR activation (sustained analgesia)    │
  │               │ = OPIOID-DOMINANT milieu                         │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ EA (100Hz)    │ → Dynorphin ↑ (selective)                       │
  │               │ → KOR activation (rapid-onset analgesia)        │
  │               │ = DYNORPHIN-DOMINANT milieu                      │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ EA (2/100     │ → ALL 4 opioid peptides simultaneously ⭐       │
  │ alternating)  │ → MOR + DOR + KOR activation (maximal)          │
  │               │ → Avoids cross-tolerance                         │
  │               │ = OPTIMAL OPIOID milieu                          │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ Massage       │ ① Oxytocin ↑ (CT afferent-mediated)            │
  │ (gentle)      │ ② ↓ cortisol 20-30% pre-post (Field 2005);     │
  │               │    between-group d=0.05-0.30 (Moyer 2011).     │
  │               │    Massage-specific effect MODEST (B03 §9.3)   │
  │               │ ③ Endocannabinoids: NO increase (touch massage) │
  │               │ ④ Anti-sympathetic shift (NE ↓)                 │
  │               │ = OXYTOCIN-DOMINANT milieu                       │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ Deep tissue / │ ① AEA ↑ 168% (OMT, McPartland 2005)            │
  │ OMT / fascial │ ② OEA ↓ 27% (fatty acid rebalancing)          │
  │ manipulation  │ ③ ATP release from fibroblasts (A03)            │
  │               │ ④ PGE2 from COX-2 induction in fibroblasts     │
  │               │ = ENDOCANNABINOID-DOMINANT milieu                │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ Exercise      │ ① AEA + 2-AG ↑ (moderate-vigorous aerobic)     │
  │ (moderate)    │ ② β-endorphin ↑ (peripheral, NOT central high) │
  │               │ ③ 5-HT ↑ (circulating)                         │
  │               │ ④ Myokines (IL-6 classic signaling = anti-inflam)│
  │               │ ⑤ SPM precursors ↑                               │
  │               │ = ENDOCANNABINOID + MYOKINE milieu               │
  │               │ ⭐ Runner's high = eCB (crosses BBB), NOT opioid │
  │               │   Siebers 2021: naltrexone doesn't block euphoria│
  ├───────────────┼──────────────────────────────────────────────────┤
  │ Cupping /     │ ① HO-1 → CO (gasotransmitter, A04 §3.5)       │
  │ Gua Sha       │ ② Intense neurogenic inflammation (CGRP/SP)     │
  │               │ ③ PGE2 ↑ (tissue damage → COX-2)               │
  │               │ ④ β-endorphin from immune cell recruitment      │
  │               │ = MICROTRAUMA + HO-1 milieu (detail: A04)        │
  ├───────────────┼──────────────────────────────────────────────────┤
  │ Moxibustion   │ ① TRPV1 → CGRP/SP (thermal C-fiber activation)│
  │ (B08) [RC#5]  │ ② HSP (heat shock proteins) → immune modulation │
  │               │ ③ Local cortisol response (CRH → POMC from heat)│
  │               │ = THERMAL + NEUROENDOCRINE milieu                │
  └───────────────┴──────────────────────────────────────────────────┘

  ⭐ KEY DISTINCTION — DEEP vs GENTLE MANIPULATION:
    Gentle touch massage → oxytocin-dominant, NO eCB increase
    Deep fascial manipulation (OMT) → AEA ↑ 168%
    = Intensity and depth of stimulus determine endocannabinoid system engagement
    (Lindgren et al. 2015: touch massage = no AEA/2-AG change;
     McPartland et al. 2005: OMT = 168% AEA increase)

  ⭐ MOLECULAR SUBSTRATE IDENTIFIED:  [RC#4 addition, from B04 data]
    WHY does deep fascial work specifically activate endocannabinoid system?
    → Fede et al. 2016 (Eur J Histochem): CB1 and CB2 receptors
      are expressed in human fascial tissue and fibroblasts
    → = Fascia itself is an ENDOCANNABINOID-RESPONSIVE tissue
    → Deep mechanical stimulation of fascia → directly engages
      these fascial CB receptors → endocannabinoid system activation
    → Gentle touch does NOT reach fascial depth → no CB engagement
      → no endocannabinoid system activation (consistent with Lindgren 2015)
    → Cross-reference: A03 §1.4 (fascial fibroblast CB1/CB2)
    → This completes the chain:
      Deep pressure → fascial deformation → CB1/CB2 on fibroblasts
      → AEA ↑ 168% (McPartland) → ENDOCANNABINOID-DOMINANT milieu

  🟢 McPartland et al. 2005 (JAOA: OMT → AEA ↑ 168%)
  🟢 Fede et al. 2016 (Eur J Histochem: CB1/CB2 in fascial tissue)
  🟢 Lindgren et al. 2015 (BMC Res Notes: touch massage no endocannabinoid system change)
  🟢 Siebers et al. 2021 (runner's high = eCB not opioid)
  🟢 Field 2005 (cortisol reduction from massage — pre-post figure)
  🟢 Moyer et al. 2011 (cortisol between-group reappraisal: d=0.05-0.30)
```

### §4.3 — Exercise as Chemical Milieu Reshaping

```
🟢 EXERCISE — THE MOST POTENT CHEMICAL MILIEU MODIFIER:

  INTENSITY THRESHOLD FOR ENDOCANNABINOID RELEASE:
    → LOW intensity: no significant AEA/2-AG increase
    → MODERATE-VIGOROUS aerobic: reliable AEA + 2-AG increase ⭐
    → VERY HIGH intensity: variable (may decrease)
    → = INVERTED-U PATTERN (Siebers et al. 2023)

  EXERCISE TYPE MATTERS:
    → Endurance exercise: ↑ AEA, ↑ 2-AG, ↑ peripheral β-endorphin
    → Resistance exercise: regulates eCB ligands and CB1 DIFFERENTLY
      from endurance (J Appl Physiol 2023)
    → Movement-based therapies (yoga, tai chi, qigong): operate in
      moderate intensity range → within eCB-release window

  CHRONIC EXERCISE PARADOX:
    → Acute bouts: ↑ AEA spike (consistent)
    → Long-term training: ↓ baseline eCB levels
    → BUT regular exercisers report stronger mood elevation
      despite lower baseline → enhanced receptor sensitivity?
    → 2024 data: mood, AEA, and 2-AG all ↑ post-run;
      2-AG increase MORE pronounced in occasional runners;
      mood increase STRONGER in regular runners

  RUNNER'S HIGH — THE PARADIGM SHIFT:
    → OLD: β-endorphin hypothesis (endorphins cause euphoria)
    → PROBLEM: β-endorphin is hydrophilic, CANNOT cross BBB
    → NEW: endocannabinoid hypothesis (AEA crosses BBB freely)
    → PROOF: Fuss et al. 2015 (PNAS): CB1 blockade abolishes
      anxiolysis in mice; opioid blockade does NOT
    → PROOF: Siebers et al. 2021: naltrexone (opioid blocker)
      in humans → still experience euphoria and anxiolysis
    → CLARIFICATION: peripheral β-endorphin still contributes
      to PERIPHERAL analgesia (muscle/joint), just not the "high"

  🟢 Fuss et al. 2015 (PNAS: runner's high CB1-dependent)
  🟢 Siebers et al. 2021, 2023 (exercise eCB in humans)
  🟢 Sparling et al. 2003 (first human AEA post-exercise data)
  🟢 Int J Mol Sci 2023 (exercise intensity and eCBs)
  🟢 J Appl Physiol 2023 (endurance vs resistance and eCBs)
```

---

## §5 — KEY RESEARCH

```
LANDMARK STUDIES — ORGANIZED BY SIGNALING SYSTEM:

ENDOGENOUS OPIOID SYSTEM:
  → Pomeranz & Chiu 1976 (Life Sci): first naloxone reversal of
    acupuncture analgesia — proved endorphin involvement
  → Stein et al. 1990, 1995 (Lancet, NEJM): peripheral opioid
    analgesia — immune cells produce opioids at inflammation sites
  → Han 2003, 2004 (Neurosci Lett): frequency-dependent opioid
    release — 2Hz = enkephalin, 100Hz = dynorphin
  → Machelska & Celik 2020 (Immunol Lett): immune cell-mediated
    opioid analgesia comprehensive review
  → Celik et al. 2016 (Brain Behav Immun): Ca²⁺-dependent
    opioid release from leukocytes
  → Celik et al. 2020 (JCI Insight): IL-4 → M2 macrophages →
    sustained opioid-mediated analgesia
  → Mousa et al. 2025 (Cells): opioid receptors in human DRG —
    MOR/DOR/KOR co-localize with CGRP, Nav1.8, TRPV1
  → Dembla et al. 2017 (eLife): MOR inhibits TRPM3 via Gβγ
  → Zhang et al. 2025 (Chinese J Integr Med): neuro-immune
    interactions of acupuncture via endogenous opioid system

ENDOCANNABINOID SYSTEM:
  → McPartland et al. 2005 (JAOA): OMT → AEA ↑ 168%
  → Fede et al. 2016 (Eur J Histochem): CB1/CB2 expressed in
    human fascial tissue and fibroblasts — molecular substrate
    for pressure-dependent endocannabinoid system activation [RC#4 addition]
  → Su et al. 2012 (Mol Pain): EA CB2 → β-endorphin from
    keratinocytes — endocannabinoid system-opioid cross-talk
  → Su et al. 2012 (J Pain): EA ↑ CB2 on keratinocytes/immune cells
  → Fuss et al. 2015 (PNAS): runner's high = CB1-dependent
  → Siebers et al. 2021 (Psychoneuroendocrinol): naltrexone doesn't
    block exercise-induced euphoria
  → Siebers et al. 2023 (Neuroscientist): eCB exercise review
  → Clapper et al. 2010 (Nat Neurosci): URB937 peripheral FAAH
    inhibitor produces analgesia without CNS effects
  → Ding et al. 2023 (PLOS ONE): EA peripheral CB1 pathway
  → Yuan et al. 2018 (Front Neurosci): CB1 on vlPAG GABAergic neurons
  → Su et al. 2025 (Acupunct Herb Med): endocannabinoid system as acupuncture mediator
  → Guindon & Bhavsar 2024 (Expert Opin Ther Targets): endocannabinoid system review
  → Lindgren et al. 2015 (BMC Res Notes): touch massage = no AEA change
  → Scientific Reports 2020: AEA in wound healing

ADENOSINE:
  → Goldman et al. 2010 (Nature Neuroscience): adenosine A1 receptor
    mediates acupuncture analgesia — 24× interstitial adenosine ↑
  → Takano et al. 2012: adenosine anti-nociception mechanism

CUTANEOUS NEUROENDOCRINE:
  → Slominski et al. 2000 (Physiol Rev): CRH/POMC in skin
  → Slominski et al. 2000 (Endocrine Rev): neuroendocrinology of skin
  → Slominski 2005: CRH → POMC in fibroblasts
  → Slominski et al. 2011, 2012 (Dermato-Endocrinol, Adv Anat):
    skin neuroendocrine system reviews
  → Ito et al. 2005: hair follicle cortisol synthesis
  → Bigliardi-Qi et al. 2000 (J Invest Dermatol): opioids in skin
  → Cheng et al. 2020 (Molecules): β-neoendorphin wound healing

OXYTOCIN:
  → Uvnäs-Moberg et al. 2024: oxytocin release patterns with touch
  → Frontiers 2026: oxytocin release patterns comprehensive review
  → bioRxiv 2026: OT modulation of spinal circuits in massage
  → eLife 2023: OT enhances responses to gentle stroking

EICOSANOIDS:
  → Zhang et al. 2025 (FASEB J): Ptgs2+ CPTCs force-immune axis
  → Theranostics 2021: PGE2 in tissue repair and regeneration
  → Smyth et al. 2009 (Physiol Rev): prostanoids review

H₂S:
  → MDPI 2024: H₂S comprehensive review
  → Springer 2025: gasotransmitters NO/H₂S/CO in nociception
  → Zhou et al. 2020: CBS-H₂S inhibits EA analgesia

PERIPHERAL SEROTONIN:
  → PMC 2024: peripheral serotonin and gut-brain axis
  → Front Biosci 2023: mast cell serotonin at acupoints
  → J Neurosci 2013: descending serotonergic facilitation

CROSS-SYSTEM:
  → McDonald & Bhatt 2017 (Neurosci Biobehav Rev): endocannabinoid system as key
    participant in acupuncture effects
  → Guilherme Dos Santos et al. 2025 (Metab Brain Dis): eCB
    modulation in pain — covers dual FAAH/MAGL inhibition
  → Nelson et al. 2024 (JAMA Network Open): massage for pain
    umbrella review (129 systematic reviews)
```

---

## §6 — HUMAN-PREDICTIVE-DRIVE CONNECTION POINTS

```
🟡 MAPPING TO Human-Predictive-Drive CONCEPTS:

  1. DIRECT-STATE REWARD:
     → Endogenous opioids = Direct-State reward molecules
     → β-endorphin from acupuncture = Direct-State activation
       without cognitive mediation
     → Endocannabinoids (runner's high) = Direct-State via
       movement, bypassing PFC evaluation
     → Oxytocin (touch) = Direct-State social reward

  2. ZONE D (PFC reach ≈ 0):
     → All local chemical signaling operates BELOW conscious awareness
     → Frequency-dependent opioid selection: patient doesn't "choose"
       which opioid — EA frequency determines it = Zone D process
     → Peripheral opioid analgesia requires NO cognitive involvement
     → Oxytocin release from touch = automatic Zone D response

  3. EVALUATIVE GATES → DIRECT-STATE:
     → Placebo analgesia involves endogenous opioid release
       (naloxone partially blocks placebo analgesia)
     → = Evaluative Gates can TRIGGER Direct-State opioid pathways
     → BUT body therapies also activate opioids INDEPENDENTLY of
       belief (Goldman 2010: A1 analgesia in mice = no placebo)
     → = Evaluative and Direct-State pathways CONVERGE on same
       chemical milieu

  4. CORTISOL = AMPLIFIER:
     → Local cutaneous HPA axis produces cortisol independently
     → Massage ↓ cortisol 20-30% pre-post (Field 2005)
       ⚠ Between-group: d=0.05-0.30 (Moyer 2011) — MODEST.
       Much of reduction attributable to REST, not massage-specific.
     → Local cortisol modulation = part of the chemical
       milieu shift, but SMALLER contributor than previously assumed
     → Connects to Human-Predictive-Drive's cortisol-as-amplifier framework:
       cortisol responds to source removal (rest/safety),
       consistent with Moyer's finding (B03 §9.3)

  5. BREATHING = ZONE D BRIDGE (A02 §3.7):
     → Breathing modulates oxytocin release
     → Slow breathing → vagal tone → ↓ sympathetic → ↓ NE →
       changed chemical milieu at tissue level

  6. GAP 2 (DRIVER LAYER):
     → This file provides the CHEMICAL DETAIL of Gap 2 Layer 3:
       the specific molecules that translate therapy input into
       therapeutic effect
     → Opioids, endocannabinoids, adenosine, oxytocin =
       the DRIVER MOLECULES of Gap 2

  7. BLACKBOX CANDIDATES:
     → endocannabinoid system-opioid cross-talk = previously unknown mechanism
     → Cutaneous HPA axis = skin as independent endocrine organ
     → Parameter-dependent chemical profiles = dosing precision
       beyond "more stimulation = more effect"
```

---

## §7 — INDIVIDUAL VARIATION

```
🟢 HOW LOCAL ENDOCRINE SIGNALING VARIES BETWEEN INDIVIDUALS:

  1. OPIOID RECEPTOR GENETICS:
     → OPRM1 (μ-opioid receptor) polymorphisms:
       A118G variant → altered β-endorphin binding affinity
       → Different pain sensitivity AND acupuncture responsiveness
     → COMT (catechol-O-methyltransferase) Val158Met:
       → Affects dopamine/NE metabolism → influences pain threshold
       → Interacts with opioid system
     → = Genetic basis for "acupuncture responders vs non-responders"

  2. ENDOCANNABINOID TONE:
     → FAAH gene polymorphism (Pro129Thr):
       → Reduced FAAH activity → higher baseline AEA levels
       → Lower anxiety, different pain sensitivity
     → CNR1 (CB1 receptor) polymorphisms
     → Chronic cannabis use → CB1 downregulation →
       may reduce body therapy endocannabinoid system response
     → = Individual endocannabinoid system tone affects therapy responsiveness

  3. INFLAMMATORY STATUS:
     → Peripheral opioid analgesia DEPENDS on inflammation
     → More inflammation → more opioid receptors upregulated →
       STRONGER peripheral opioid effect
     → Chronic low-grade inflammation (metabolic syndrome) →
       altered endocannabinoid system tone (elevated 2-AG, reduced AEA)
     → = Inflammatory status modulates the chemical milieu baseline

  4. AGE-RELATED CHANGES:
     → Opioid receptor density ↓ with age
     → endocannabinoid system tone changes across lifespan
     → 11β-HSD1 ↑ with age → more local cortisol activation
     → = Older adults may have shifted chemical milieu baseline

  5. SEX DIFFERENCES:
     → Estrogen modulates: opioid receptor expression, endocannabinoid system tone,
       oxytocin receptor sensitivity, COX-2 expression
     → Women: higher opioid receptor density but different
       sensitivity patterns
     → Menstrual cycle: fluctuating estrogen → fluctuating
       opioid/endocannabinoid system responses
     → = Sex hormones as MODULATORS of the local chemical milieu

  6. EXERCISE HISTORY:
     → Regular exercisers: ↓ baseline eCB levels but ↑ receptor
       sensitivity (paradox: stronger mood effects)
     → Occasional exercisers: more pronounced 2-AG spikes post-exercise
     → = Training history shapes the endocannabinoid system response pattern

  🟢 Various sources on genetic polymorphisms and individual variation
```

---

## §8 — OPEN QUESTIONS

```
UNRESOLVED QUESTIONS FOR FUTURE RESEARCH:

  Q1: COMPLETE CHEMICAL MILIEU MAPPING
     🔴 No study has simultaneously measured ALL local signaling
     molecules (opioids + eCBs + adenosine + eicosanoids + oxytocin
     + gasotransmitters) at a single therapy point during treatment.
     What is the COMPLETE chemical signature of each therapy?
     Technology needed: multi-analyte microdialysis or spatial
     metabolomics at tissue level.

  Q2: endocannabinoid system-OPIOID CROSS-TALK IN HUMANS
     🟡 CB2 → β-endorphin pathway demonstrated in rodents (Su 2012).
     Does this same cross-talk operate at human acupoints?
     Does EA frequency modulate endocannabinoid system-opioid interaction?
     Clinical relevance: could endocannabinoid system-targeted adjuvants enhance
     acupuncture analgesia?

  Q3: CUTANEOUS HPA AND BODY THERAPY
     🔴 Slominski's work establishes skin produces cortisol locally.
     Does acupuncture/massage specifically modulate CUTANEOUS
     (not just systemic) HPA activity? Is local cortisol production
     at needle site part of the therapeutic mechanism?

  Q4: GENTLE vs DEEP MANIPULATION — endocannabinoid system THRESHOLD
     🟡 Touch massage = no endocannabinoid system change; OMT = 168% AEA increase.
     What is the MINIMUM mechanical intensity to trigger endocannabinoid system?
     Where exactly is the threshold between "oxytocin pathway"
     and "endocannabinoid pathway" activation?
     Clinical: optimal pressure for specific outcomes?

  Q5: EXERCISE INTENSITY OPTIMIZATION
     🟡 Inverted-U for eCB release is established.
     Can movement-based therapies (yoga, tai chi) be DOSED
     to maximize eCB release based on intensity monitoring?
     Clinical trial NCT03823157 (tai chi + eCBs) pending.

  Q6: PERIPHERAL OPIOID TOLERANCE
     🟢 No tolerance at peripheral sites during inflammation
     (Stein model). But what about CHRONIC therapy — does
     repeated acupuncture eventually show peripheral tolerance?
     Limited longitudinal data available.

  Q7: PARAMETER-DEPENDENT CHEMICAL PRESCRIBING
     🟡 Han's frequency-dependent opioid release is well-established.
     Can other therapy parameters (depth, duration, force, temperature)
     be similarly mapped to specific chemical outcomes?
     Would enable "chemical prescribing" — choosing therapy
     parameters to target specific signaling systems.
```

---

## §9 — CROSS-REFERENCES

### Internal Links (Body-Signal-Architecture)

```
  A01 — Peripheral Nervous System:
    → §3.4 Axon reflex: CGRP/SP release (neuropeptides as milieu components)
    → §3.7 Purinergic signaling: ATP → adenosine cascade
    → §1.4 C fibers: primary substrate for opioid/endocannabinoid system/OT receptors

  A02 — Autonomic Nervous System:
    → §3.6 Cholinergic anti-inflammatory pathway: vagal → systemic
    → §3.7 Breathing = Zone D bridge: modulates oxytocin, sympathetic
    → Sympathetic tone: NE levels = baseline chemical milieu modifier

  A03 — Fascia-Connective Tissue:
    → §3.2 Fibroblast ATP release under mechanical deformation
    → §3.4 Acupoints at fascial planes: site of chemical milieu
    → Telocytes (Ptgs2+ CPTCs): PGE2 production from fascial cells

  A04 — Vascular-Lymphatic:
    → §3.3 NO at acupoints (Ma 2003): gasotransmitter already in milieu
    → §3.5 HO-1 → CO pathway: cupping/gua sha gasotransmitter response
    → A06 completes gasotransmitter triad: NO (A04) + CO (A04) + H₂S (A06)
    → Microcirculation: DELIVERY of milieu components to tissue

  A05 — Neuroimmune Interface:
    → §2.1 Neurogenic inflammation: CGRP/SP as milieu components
    → §2.3 Cytokine sensitization: TNF-α, IL-1β, PGE2 as milieu
    → §2.4 SPMs: resolution mediators in the milieu
    → §3.1 Mast cell-neuron loop: mast cells produce 5-HT, histamine
    → §3.2 Purinergic bridge: ATP → adenosine (Goldman 2010 context)
    → §4.3 Force-immune axis: Ptgs2+ CPTCs

  A07 — Dermatome-Somatotopic Map:
    → Segmental organization: dermatome determines which chemical
      milieu shift reaches which spinal segment → organ effect

  A08 — Muscle-Tendon-Joint:
    → §3.5 Trigger point biochemistry (Shah 2008): pH 4.7, cytokines,
      neuropeptides = pathological chemical milieu
    → Trigger point = LOCAL CHEMICAL MILIEU GONE WRONG
    → Dry needling: resets the milieu (β-endorphin + adenosine release)
```

### Human-Predictive-Drive Links

```
  → Core-Hardware.md: receptor system (opioid/endocannabinoid system/OT receptors)
  → Dissonance-Signal-Architecture.md: pain pathways (opioid targets)
  → Cortisol-Threat-Architecture.md: cortisol local metabolism
  → Keystone-17: interoception (body therapies → improved via milieu)
```

### Key Citations (alphabetical)

```
  Bigliardi-Qi et al. 2000. J Invest Dermatol. Opioids in keratinocytes.
  Biro et al. 2009. Trends Pharmacol Sci. Cutaneous endocannabinoid system. 30(8):411-20.
  Celik et al. 2016. Brain Behav Immun. Ca²⁺-dependent opioid release.
  Celik et al. 2020. JCI Insight. IL-4 → M2 macrophages → opioid analgesia.
  Cheng et al. 2020. Molecules. β-neoendorphin wound healing.
  Clapper et al. 2010. Nat Neurosci. URB937 peripheral FAAH inhibitor.
  Dembla et al. 2017. eLife. MOR inhibits TRPM3 via Gβγ.
  Ding et al. 2023. PLOS ONE. EA peripheral CB1 pathway.
  Fei et al. 1987. Spinal cord opioid levels during EA.
  Field 2005. Cortisol reduction from massage.
  Fuss et al. 2015. PNAS. Runner's high is CB1-dependent. 112(42):13105.
  Goldman et al. 2010. Nature Neuroscience. Adenosine A1 acupuncture. 13:883.
  Guilherme Dos Santos et al. 2025. Metab Brain Dis. eCB modulation in pain.
  Guindon & Bhavsar 2024. Expert Opin Ther Targets. endocannabinoid system review. 28(9).
  Han JS. 2003. Neurosci Lett. 2Hz endomorphin but not 100Hz.
  Han JS. 2004. Neurosci Lett. Frequency-dependent release.
  Han JS. 2013. Int Rev Neurobiol. Acupuncture-induced opioid system.
  Ito et al. 2005. Hair follicle cortisol synthesis.
  Lindgren et al. 2015. BMC Res Notes. Touch massage no AEA change.
  Maccarrone et al. 2003. J Biol Chem. Keratinocyte endocannabinoid system.
  Machelska & Celik 2020. Immunol Lett. Immune cell opioid review.
  McDonald & Bhatt 2017. Neurosci Biobehav Rev. endocannabinoid system in acupuncture.
  McPartland et al. 2005. JAOA. OMT → AEA ↑ 168%.
  Moyer et al. 2011. J Clin Psychiatry. Cortisol reappraisal: between-group d=0.05-0.30.
  Mousa et al. 2025. Cells. Opioid receptors in human DRG neurons.
  Nelson et al. 2024. JAMA Network Open. Massage pain umbrella review.
  Pomeranz & Chiu 1976. Life Sci. Naloxone blocks acupuncture. 19:1757.
  Price et al. 2003. Neuroscience. CB1 on DRG neurons.
  Rukwied et al. 2011. Naunyn-Schmiedeberg's. CB1 inhibits CGRP 34-65%.
  Scientific Reports 2020. AEA in wound healing. 10:11134.
  Siebers et al. 2021. Psychoneuroendocrinol. Exercise euphoria not opioid.
  Siebers et al. 2023. The Neuroscientist. eCB exercise review.
  Slominski et al. 2000. Physiol Rev. CRH/POMC in skin. 80(3).
  Slominski et al. 2000. Endocrine Rev. Neuroendocrinology of skin. 21(5).
  Slominski et al. 2011. Dermato-Endocrinol. Skin neuroendocrine review.
  Slominski et al. 2012. Adv Anat Embryol Cell Biol. Sensing environment.
  Smyth et al. 2009. Physiol Rev. Prostanoids. 89:1.
  Sparling et al. 2003. First human AEA post-exercise.
  Stein et al. 1990. Lancet. Peripheral opioid analgesia.
  Stein et al. 1995. NEJM. Peripheral opioid analgesia.
  Su et al. 2012. Mol Pain. CB2 → β-endorphin keratinocytes.
  Su et al. 2012. J Pain. EA ↑ CB2 on keratinocytes.
  Su et al. 2015. Mol Neurobiol. CB2 signaling mechanism.
  Su et al. 2025. Acupunct Herb Med. endocannabinoid system as acupuncture mediator.
  Takano et al. 2012. Adenosine anti-nociception mechanism.
  Theranostics 2021. PGE2 in tissue repair. 11:8836.
  Turcotte et al. 2016. Cell Mol Life Sci. CB2 on immune cells.
  Uvnäs-Moberg et al. 2024. Oxytocin release patterns with touch.
  Yuan et al. 2018. Front Neurosci. CB1 on vlPAG GABAergic neurons.
  Zhang et al. 2025. Chinese J Integr Med. Neuro-immune acupuncture.
  Zhang et al. 2025. FASEB J. Ptgs2+ CPTCs force-immune axis.
  Zhou et al. 2020. CBS-H₂S inhibits EA analgesia.
```
