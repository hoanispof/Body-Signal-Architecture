---
title: Stimulus-Pathway-Matrix
id: C01
version: 0.1
status: DRAFT
scope: What physical stimulus types exist across body-based therapies, and which body system pathways does each activate?
sources: [A01-A09, B01-B16]
confidence: 🟢 Research | 🟡 Synthesis | 🔴 Hypothesis
---

# Stimulus-Pathway-Matrix

## §1 — PURPOSE & METHODOLOGY

### §1.1 — Why This Cross-Reference Exists

Individual Track B files each map their therapy's activation of Track A systems (§6 in each file). But these profiles are therapy-centric — they answer "what does acupuncture activate?" not "what does needle penetration activate?" Since multiple therapies share stimulus types (B01 and B11 both use needle penetration; B02 and B13 both use sustained point pressure), and some therapies combine multiple stimulus types (B15 uses movement + breathing + attention), the therapy-level analysis obscures a more fundamental question:

**What is the relationship between the PHYSICAL STIMULUS TYPE and the BODY SYSTEM PATHWAYS it activates?**

This matrix answers that question by abstracting from therapy identity to stimulus type, creating an analytical product that cannot exist in any individual Track B file.

### §1.2 — Data Sources

- **Stimulus classification:** Extracted from all 15 Track B §2 (Stimulation Type) sections
- **Activation profiles:** Extracted from all 15 Track B §6 (Body System Pathways Activated) sections
- **System definitions:** Track A files A01-A09

### §1.3 — Standardization Decisions

**Activation levels.** Track B files used varying terminology for activation intensity. All levels have been normalized to a 6-point ordinal scale:

```
PRIMARY > STRONG > MODERATE > MINOR > MINIMAL > NONE
```

Assignment criteria:
- **PRIMARY:** This system is the dominant pathway — the stimulus would lose its defining character without it. Multiple mechanisms within the system are engaged. 🟢
- **STRONG:** Major contributor with substantial evidence. The stimulus reliably activates multiple mechanisms within this system. 🟢
- **MODERATE:** Meaningful engagement with evidence, but not the defining pathway. Typically 1-2 mechanisms within the system. 🟢/🟡
- **MINOR:** Some engagement, but limited in scope or evidence. Often secondary or inconsistent. 🟡
- **MINIMAL:** Theoretically possible but at the edge of detectability. Likely below clinical relevance. 🟡/🔴
- **NONE:** No plausible mechanism of engagement for this stimulus type. 🟢 (confident absence)

**Matrix scope.** The matrix shows POTENTIAL activation — the level achievable with optimal parameters and application. Actual activation in a given treatment depends on parameter modifiers (§3.2) and application location (deferred to C04). This means the matrix represents the ceiling, not the floor.

**Decomposition principle.** When a therapy uses multiple stimulus types (e.g., B15 Tai Chi = movement + breathing + balance), its overall Track A profile is decomposed into contributions from each stimulus component. The matrix captures stimulus-type-level contributions, not therapy-level composites.

---

## §2 — TAXONOMY / CLASSIFICATION

### §2.1 — Stimulus Type Taxonomy

Ten primary stimulus types were identified across 15 Track B therapies. Classification is based on the PHYSICAL NATURE of the stimulus — the mechanical, thermal, or electrical input applied to tissue.

```
MECHANICAL (9 types)                              NON-MECHANICAL (1 type)
├── Invasive                                      └── 7. THERMAL
│   └── 1. PENETRATION                               (radiant/conductive heat)
├── Compressive
│   ├── 2. SUSTAINED POINT PRESSURE
│   ├── 3. GENERAL PRESSURE (broad manual)
│   └── 4. DEEP PRESSURE (sustained deep force)
├── Decompressive
│   └── 5. NEGATIVE PRESSURE (suction)
├── Shear
│   └── 6. HORIZONTAL SHEAR (scraping)
├── Articular
│   └── 8. JOINT THRUST (HVLA)
├── Percussive
│   └── 9. LIGHT PERCUSSION (tapping)
└── Active
    └── 10. SELF-GENERATED MOVEMENT (composite)
```

### §2.2 — Stimulus Type Definitions

**1. PENETRATION (Needle Insertion)**
- Physical: Solid filiform needle (0.12-0.40mm Ø) inserted through skin into tissue (5-50mm depth)
- Creates: micro-wound, tissue penetration, collagen winding (needle grasp), De Qi sensation (Aβ/Aδ/C composite)
- Unique: Only stimulus type that bypasses skin barrier to reach deep tissue directly
- Therapies: B01 Acupuncture (PRIMARY), B11 Dry Needling (PRIMARY)
- Parameter range: depth 5-50mm, diameter 0.12-0.40mm, retention 0-30 min, manipulation (lifting-thrusting, twirling, pistoning)
- 🟢 Physical parameters well-characterized (B01 §2, B11 §2)

**2. SUSTAINED POINT PRESSURE**
- Physical: Perpendicular pressure applied to specific anatomical points via thumb, finger, or tool; held 3-120 seconds per point
- Creates: localized tissue compression, mechanoreceptor activation (primarily Aβ), possible Aδ at high force
- Unique: Combines pressure with point specificity — same locations as acupuncture but without tissue penetration
- Therapies: B02 Acupressure (PRIMARY), B06 Reflexology (PRIMARY, foot), B13 Shiatsu (PRIMARY, whole-body), B14 Craniosacral (PRIMARY, ultra-light cranial)
- Parameter range: force 5-80N, contact area 1-4 cm², duration 3-120 sec/point, 4-660+ points/session
- Note: Activation profile is STRONGLY region-dependent (face vs. ear vs. body vs. foot → C04)
- 🟢 Physical parameters well-characterized (B02 §2)

**3. GENERAL PRESSURE (Broad Manual)**
- Physical: Hands, forearms, or body applying moving pressure across broad tissue areas
- Creates: area-wide mechanoreceptor activation, CT afferent engagement at light pressure/slow speed, progressive deeper receptor recruitment with increasing pressure
- Unique: Only stimulus type spanning the full pressure continuum from ultra-light (<0.5N) to deep (~110N) in a single session, with PRESSURE-DEPENDENT PATHWAY SWITCHING (B03 §2.2)
- Therapies: B03 Massage-General (PRIMARY)
- Parameter range: force 0.5-110N, speed 1-30 cm/s, 8 core techniques (effleurage, petrissage, friction, tapotement, vibration, compression, stretching, joint mobilization)
- 🟢 Pressure-Dependent Pathway Model supported by multiple independent studies (B03 §2.2)

**4. DEEP PRESSURE (Sustained Deep Mechanical Force)**
- Physical: Sustained high-force pressure (40-110+ N) targeting deep tissue layers (deep fascia, muscle belly, trigger points), held 5-120+ seconds per location
- Creates: fascial thixotropy (HA gel-to-sol), mechanotransduction signaling (integrin-FAK-YAP), ischemia→reactive hyperemia at trigger points, endocannabinoid system activation at fascial CB1/CB2 receptors
- Unique: TIME UNDER LOAD is the critical differentiator from general pressure — seconds of contact per area (B03) vs. 90-120+ seconds sustained at one spot (B04 MFR)
- Therapies: B04 Deep Tissue/MFR (PRIMARY)
- Parameter range: force 40-150+ N, duration 5-120+ sec per location, 5 force vectors (compression, longitudinal stripping, cross-fiber friction, sustained stretch, shear/scraping)
- 🟢 Mechanotransduction mechanism supported (Crane 2012, B04 §5.2)

**5. NEGATIVE PRESSURE (Suction)**
- Physical: Vacuum/suction (-75 to -500 mmHg) lifting skin and superficial tissue away from deeper structures
- Creates: capillary distension, controlled capillary microtrauma at sufficient pressure, tissue decompression
- Unique: ONLY stimulus type with inverted force direction (pulling tissue UP vs. pushing DOWN). Marks (petechiae/ecchymoses) = THE mechanism, not a side effect — they represent HO-1 pathway activation.
- Therapies: B07 Cupping (PRIMARY)
- Parameter range: pressure -75 to -500 mmHg, duration 5-20 min, cup diameter 2-8 cm, 1-12 cups/session
- 🟢 HO-1 pathway confirmed (Kwong 2009, Nielsen 2007 via B07/B09)

**6. HORIZONTAL SHEAR (Scraping)**
- Physical: Tool pressed against oiled skin at 30-45° angle and dragged horizontally; firm pressure sufficient to produce petechiae (sha)
- Creates: dual pathway activation — (Path A) controlled capillary microtrauma → HO-1 vascular cytoprotection + (Path B) inter-layer fascial sliding and adhesion disruption
- Unique: Only stimulus type with LATERAL/TANGENTIAL force as primary vector. Shared HO-1 endpoint with negative pressure (B07) but via different mechanical path.
- Therapies: B09 Gua Sha (PRIMARY), B04 IASTM variant (MINOR)
- Parameter range: estimated 200-500 kPa, 10-30 strokes/area, unidirectional, 10-20 min/treatment area
- 🟢 HO-1 pathway confirmed; fascial verification emerging (2025 TLF RCT, B09 §5)

**7. THERMAL (Radiant/Conductive Heat)**
- Physical: Heat application to skin surface, therapeutic range 40-55°C, via burning Artemisia moxa, ginger/salt barriers, or electronic devices
- Creates: TRPV1 activation (convergence hub), vasodilation, heat shock protein (HSP) induction, cutaneous HPA activation
- Unique: ONLY non-mechanical primary stimulus in all of Track B. TRPV1 is a molecular convergence node for heat + endocannabinoids (AEA) + eicosanoids (PGE2) + opioid sustain (prevents MOR desensitization, A06). HSP pathway is EXCLUSIVE to thermal stimulus.
- Therapies: B08 Moxibustion (PRIMARY)
- Parameter range: temperature 40-55°C (TRPV1 threshold 42-43°C), duration 15-60 min, method (direct/indirect/moxa stick/electronic)
- Note: Electronic moxibustion (pure heat, no smoke) = natural experiment for thermal vs. chemical specificity
- 🟢 TRPV1 molecular biology well-established; 🔴 spectral specificity hypothesis (Cheng 2017)

**8. JOINT THRUST (HVLA)**
- Physical: Rapid high-velocity low-amplitude force applied to synovial joint, primarily spinal facet joints
- Creates: joint gapping (1-5mm), cavitation (tribonucleation, Kawchuk 2015), proprioceptive burst (Type II Pacinian activation), post-activation depression
- Unique: SPEED of application is the critical parameter (<200ms thrust, 1000-4000 N/s rate of force), not force magnitude. ONLY stimulus type targeting articular structures rather than soft tissue.
- Therapies: B10 Chiropractic (PRIMARY)
- Parameter range: peak force 100-600N, thrust duration 100-200ms, amplitude 1-5mm, preload 50-150N
- Note: Maitland Grade V (HVLA) vs. Grades I-IV (mobilization = slow rhythmic → effectively General Pressure applied to joint)
- 🟢 Biomechanics well-characterized (Herzog 1993/2001, Kawchuk 2015)

**9. LIGHT PERCUSSION (Tapping)**
- Physical: Repetitive light tapping on skin surface (~2-5N force, ~2 taps/second, 2-3 fingertips)
- Creates: rapidly-adapting Aβ mechanoreceptor (Meissner/Pacinian) activation only. Gate control ceases within milliseconds of stopping.
- Unique: WEAKEST somatic stimulus in Track B. In B12 (EFT), combined with a cognitive protocol (exposure + acceptance + restructuring) that is the likely primary active ingredient.
- Therapies: B12 EFT Tapping (PRIMARY)
- Parameter range: force ~2-5N, speed ~2 taps/sec, ~3-5 sec/point, ~30-40 sec total somatic contact per round
- Note: B03 tapotement uses similar physical stimulus but with different protocol and context
- 🟡 Physical parameters estimated, not measured in any EFT study

**10. SELF-GENERATED MOVEMENT (Active Composite)**
- Physical: Patient generates own movement, breathing, attention, and balance challenge. Multiple simultaneous stimulus components produced by the patient, not applied externally.
- Creates: proprioceptive-motor afferent activation, voluntary ANS access via breathing (Zone D Bridge), sustained vestibular-proprioceptive challenge, neuroplastic adaptation through motor learning
- Unique: PARADIGM SHIFT from passive reception (B01-B14) to active self-regulation. The patient IS the stimulus source. Voluntary breathing = the ONLY visceral function under both automatic AND voluntary control.
- Therapies: B15 Tai Chi/Qigong (PRIMARY), B16 Yoga Therapy (PRIMARY)
- Parameter range: intensity 2-8 METs, session 20-90 min, frequency daily to 2-3x/week, practice period weeks to years
- B15-B16 structural differences: B15 = continuous flow + balance-dominant + natural breathing; B16 = held postures + flexibility-dominant + structured pranayama (bidirectional: calming AND activating)
- 🟢 Exercise physiology well-established; 🟡 composite interaction effects

### §2.3 — Electrical Stimulation as Parameter Modifier

Electrical stimulation is NOT classified as a separate stimulus type because it is always delivered IN COMBINATION with another stimulus (needle penetration in EA/DNWES, surface contact in TENS). It functions as a PARAMETER MODIFIER of the penetration stimulus type (see §3.2).

Key electrical parameters (Han frequency-opioid map, B01 §2.4):
- 2 Hz → β-endorphin + enkephalin (μ/δ opioid receptors)
- 100 Hz → dynorphin (κ opioid receptors)
- 2/100 Hz alternating → all four opioid peptides
- Low intensity (0.5 mA) → PROKR2+ vagal-adrenal anti-inflammatory (Liu 2020)
- High intensity (3.0 mA) → spinal sympathetic pathway (Liu 2021)

---

## §3 — MAIN ANALYSIS

### §3.1 — Stimulus Type × Track A System Activation Matrix

```
                          A01   A02   A03   A04   A05   A06   A07   A08   A09
STIMULUS TYPE             PNS   ANS   FAS   VAS   NIM   END   DRM   MTJ   MER
──────────────────────── ───── ───── ───── ───── ───── ───── ───── ───── ─────
1. Penetration           PRI   STR   STR   MOD   STR   PRI   STR   MOD   STR
2. Sustained Pt Pressure STR   STR   MOD   MIN   MOD   MOD   STR   MOD   MOD
3. General Pressure      PRI   STR   STR   MOD   STR   STR   MOD   STR   MOD
4. Deep Pressure         STR   MOD   PRI   MOD   MOD   STR   MNR   STR   MIN
5. Negative Pressure     MOD   MOD   STR   PRI   STR   MOD   MIN   MIN   MIN
6. Horizontal Shear      MOD   MIN   STR   PRI   MOD   MIN   MIN   MOD   MIN
7. Thermal               PRI   MOD   MIN   PRI   MOD   MOD   STR   MIN   MOD
8. Joint Thrust          PRI   STR   MOD   MIN   MIN   MOD   STR   PRI   MIN
9. Light Percussion      MIN   MIN   NON   NON   NON   MIN   MIN   NON   MIN
10. Self-Gen Movement    STR   PRI   MOD   MOD   MOD   MOD   MOD   PRI   MOD

ABBREVIATIONS: PRI=PRIMARY, STR=STRONG, MOD=MODERATE, MNR=MINOR, MIN=MINIMAL, NON=NONE
COLUMN KEY: PNS=Peripheral Nervous, ANS=Autonomic Nervous, FAS=Fascia-Connective,
VAS=Vascular-Lymphatic, NIM=Neuroimmune, END=Endocrine-Local, DRM=Dermatome-Somatotopic,
MTJ=Muscle-Tendon-Joint, MER=Meridian-Composite
```

Confidence: 🟡 Synthesis — levels derived from standardizing 15 Track B §6 profiles. Individual cell evidence ranges from 🟢 (well-supported) to 🔴 (inferred from mechanism plausibility).

### §3.1.1 — Detailed Notes: PENETRATION

**A01 PNS = PRIMARY.** Engages all 5 PNS mechanisms identified in A01: (1) gate control via Aβ from needle grasp and tissue displacement, (2) descending modulation via Aδ/C from De Qi composite sensation, (3) axon reflex from local tissue disruption, (4) somatovisceral reflex from point-specific segmental input, (5) purinergic signaling — Goldman 2010 demonstrated 24× adenosine increase at needle site. No other stimulus type activates all five. 🟢 B01 §6.1, A01 §3-§4.

**A02 ANS = STRONG.** Three ANS pathways: somatoautonomic reflex (any somatic stimulus), PROKR2-specific vagal pathway (Liu 2021 Nature — intensity-dependent: low = vagal-adrenal anti-inflammatory, high = sympathetic), and general sympathetic inhibition from descending modulation. Not PRIMARY because ANS effects are secondary to neural — needle doesn't directly target autonomic structures. 🟢 B01 §6.1, A02 §3-§4.

**A03 Fascia = STRONG.** Needle grasp = collagen winding beyond 360° (Langevin 2006). All 3 fascial mechanotransduction pathways activated (integrin-FAK-YAP, ion channels, purinergic). 80% of acupoints at fascial convergence planes (Langevin 2002). Not PRIMARY because fascia is a medium of transmission rather than the primary target. 🟢 B01 §6.1, A03 §1-§3.

**A04 Vascular = MODERATE.** CGRP-mediated vasodilation (axon reflex), NO elevation at acupoints (Ma 2003/2017), Lewis triple response, adenosine A2A vasodilation. Meaningful but not the defining pathway. 🟢 B01 §6.1, A04 §2-§3.

**A05 Neuroimmune = STRONG.** B01 activates "most neuroimmune pathways of any therapy" (B01 §6.1): mast cell degranulation via micro-wound DAMPs, Ptgs2+ telocyte force-immune axis (Zhang 2025), CGRP-driven M2 macrophage polarization (Lu 2024 Nature), vagal cholinergic anti-inflammatory pathway (via A02). 🟢 B01 §6.1, A05 §2-§4.

**A06 Endocrine-Local = PRIMARY.** Multi-system chemical milieu shift: adenosine 24× (Goldman 2010), Han frequency-dependent opioid release (2Hz = enkephalin, 100Hz = dynorphin), β-endorphin from both immune cells and pituitary, endocannabinoid system cross-talk (CB2 → β-endorphin from keratinocytes, Su 2012), cutaneous HPA activation. The richest chemical response of any stimulus type. 🟢 B01 §6.1, A06 §2-§4.

**A07 Dermatome = STRONG.** Segmental convergence fully available via somatovisceral reflex. Back-Shu points: 9/12 match predicted segmental innervation (A07 §4). Kim 2017 neurogenic spots correlate with acupoints. Engagement is LOCATION-DEPENDENT — realized when acupoints matching target organ dermatomes are selected. 🟢 B01 §6.1, A07 §3-§4.

**A08 MTJ = MODERATE.** 70-93.3% overlap between trigger points and acupoints (Melzack 1977, Dorsher 2009). Needle deactivates motor endplates (LTR → ACh depletion). But musculoskeletal system is not the primary target of most acupuncture protocols. B11 (dry needling) uses penetration with A08 as PRIMARY because it targets trigger points specifically. 🟢 B01 §6.1, B11 §6.1, A08 §4.

**A09 Meridian = STRONG.** Acupoints = multi-system convergence zones: neural + fascial + vascular + immune + chemical overlap. PROKR2 molecular specificity provides the strongest candidate mechanism for point specificity (A09 §4). Meridian pathways as traditionally described remain unconfirmed (A09 §3). 🟡 B01 §6.1, A09 §4.

### §3.1.2 — Detailed Notes: SUSTAINED POINT PRESSURE

**A01 PNS = STRONG.** Primarily Aβ gate control (dominant mechanism). Somatovisceral reflex shared with penetration. Descending modulation reduced — deep acupressure may recruit some Aδ, but less than needle penetration. CT afferents available for light techniques (Jin Shin Jyutsu-style, 5-10N) on hairy skin. 4/5 PNS mechanisms available (purinergic absent — no 24× adenosine without tissue penetration). 🟢 B02 §6.1.

**A02 ANS = STRONG.** Somatoautonomic reflex fully shared. Baroreceptor-like vagal response documented. Auricular acupressure uniquely accesses ABVN → NTS → direct vagal pathway (B02 §2.4). Facial point pressure accesses CN V → brainstem vagal (DMN) directly (A02 §4.7). Body-region variability makes this STRONG overall but regionally PRIMARY (ear, face). 🟢 B02 §6.1.

**A03 Fascia = MODERATE.** Mechanotransduction partially available through force transmission. HA metabolism and thixotropy available at sufficient pressure. Needle grasp ABSENT — the single biggest mechanism loss compared to penetration (B02 §5.3). Force transmission attenuated with depth. 🟡 B02 §6.1.

**A04 Vascular = MINIMAL.** No tissue penetration → no DAMPs, no direct lymphatic/vascular stimulation. Only surface vasodilation from minor axon reflex. Weakest Track A engagement for this stimulus type. 🟢 B02 §6.1.

**A05 Neuroimmune = MODERATE.** Vagal anti-inflammatory pathway fully shared (via A02). Crane mechanotransduction (NF-κB↓) available at sufficient pressure. But micro-wound cascade absent (no tissue penetration → no mast cell degranulation from DAMPs). 🟡 B02 §6.1.

**A06 Endocrine = MODERATE.** Oxytocin via CT afferents shared (if skin-to-skin contact on hairy skin). Cortisol reduction partial (Moyer caveat applies). Endogenous opioids reduced — β-endorphin from immune cells still possible but adenosine 24× amplification absent. Endocannabinoid system threshold uncertain — can surface pressure reach deep fascia CB1/CB2? (B02 §10 Q1 CRITICAL). 🟡 B02 §6.1.

**A07 Dermatome = STRONG.** Dermatome-somatotopic mapping fully applies. Segmental convergence at Lamina V shared with penetration. Head zones = Mu/Shu validation. Location-dependent engagement (same as penetration). 🟢 B02 §6.1, A07 §3.

**A08 MTJ = MODERATE.** Muscle tone regulation available. Trigger point ischemic compression is a PRESSURE-SPECIFIC ADVANTAGE — sustained pressure on the trigger point produces ischemia → reactive hyperemia → biochemical normalization, without needing LTR. But LTR/endplate reset lost (needs needle). 🟡 B02 §6.1.

**A09 Meridian = MODERATE.** Acupoint locations valid for pressure application. Same convergence zone concept applies. But PROKR2 depth access is the critical question — can surface pressure activate PROKR2+ neurons in deep fascia? (B02 §10 Q1). 🟡 B02 §6.1, A09 §4.

### §3.1.3 — Detailed Notes: GENERAL PRESSURE

**A01 PNS = PRIMARY.** Engages 4/5 PNS mechanisms in a PRESSURE-DEPENDENT cascade (B03 §2.2): CT afferents at light pressure (8-10N, optimal 1-10 cm/s speed), gate control at moderate pressure (20-60N, Aβ dominant), descending modulation at deep pressure (65-110N, Aδ/C recruitment), somatovisceral reflex at specific points. Only purinergic absent (no tissue penetration). 🟢 B03 §2.2, §6.1.

**A02 ANS = STRONG.** Three parasympathetic routes documented. HRV increase consistent across studies. Vagal-gastric pathway validated (preterm infant weight gain). Cortisol reduction modest (Moyer between-group d = 0.05-0.30, B03 §9.3). 🟢 B03 §6.1.

**A03 Fascia = STRONG.** Crane 2012 landmark: FAK/ERK1/2 → NF-κB↓ + PGC-1α↑ = molecular proof of mechanotransduction. TLF shear strain ↓56% in chronic LBP patients with massage. Best mechanotransduction evidence of any manual therapy. 🟢 B03 §6.1, B04 §5.2.

**A04 Vascular = MODERATE.** Genuine for MLD (manual lymphatic drainage) and trigger point ischemia-hyperemia cycle. "Improves circulation" historically overemphasized for general massage — neural and immune are primary (B03 §5.2.5). 🟢/🟡 B03 §6.1.

**A05 Neuroimmune = STRONG.** Best immune biomarker data of any manual therapy: Rapaport JAMA (NK cells ↑, decreased cortisol), Crane tissue biopsies (NF-κB↓ via mechanotransduction, not circulation). 🟢 B03 §6.1.

**A06 Endocrine = STRONG.** Key evidence for pressure-dependent chemical switching: light = oxytocin via CT afferents (no endocannabinoid system change), deep = AEA ↑168% (McPartland 2005). Demonstrates that the SAME stimulus type produces DIFFERENT chemical profiles depending on pressure parameter. 🟢 B03 §6.1, A06 §4.

**A07 Dermatome = MODERATE.** Most relevant for point-based massage traditions (Tui Na, Thai, Abhyanga). Less relevant for area-based techniques (Swedish, effleurage). 🟡 B03 §6.1.

**A08 MTJ = STRONG.** Stretch reflex modulation, autogenic inhibition (GTO), trigger point deactivation, stretch tolerance. Clinically the most visible effects — patients experience immediate tension reduction. 🟢 B03 §6.1.

**A09 Meridian = MODERATE.** Primarily relevant for meridian-based traditions (Tui Na following channel lines, Thai on Sen lines). Less relevant for area-based techniques. 🟡 B03 §6.1.

### §3.1.4 — Detailed Notes: DEEP PRESSURE

**A01 PNS = STRONG.** Aδ/C nociceptor recruitment at deep pressures (40-110+ N) → descending modulation activation. Central sensitization reversal through sustained input. Gate control also present but descending modulation is primary neural mechanism. 🟢 B04 §5.2, §6.1.

**A02 ANS = MODERATE.** Some parasympathetic shift during treatment. Not the primary pathway — deep tissue work can be uncomfortable, which may initially increase sympathetic tone before parasympathetic dominance. 🟡 B04 §6.1.

**A03 Fascia = PRIMARY.** The MOST fascial-engaged stimulus type. B04 is the ONLY therapy where A03 is the dominant system. Five force vectors target different fascial structures. Sustained loading (90-120+ sec) produces thixotropy (HA gel-to-sol transition), mechanotransduction (Crane 2012), and viscoelastic deformation (creep). CB1/CB2 in fascial fibroblasts (Fede 2016) = molecular substrate for endocannabinoid system-fascia connection. 🟢 B04 §5.2, §6.1, A03 §1.4.

**A04 Vascular = MODERATE.** Ischemia → reactive hyperemia at trigger points. Microcirculation improvement at treatment site. Not the defining pathway. 🟡 B04 §6.1.

**A05 Neuroimmune = MODERATE.** Crane 2012 mechanotransduction → NF-κB↓. Immune modulation via deep tissue engagement. Less than general pressure because deep tissue work is typically more focal. 🟡 B04 §6.1.

**A06 Endocrine = STRONG.** Endocannabinoid System-Fascia Connection = key finding: deep OMT → AEA ↑168% (McPartland 2005) + CB1/CB2 in fascia (Fede 2016) + gentle touch = NO endocannabinoid system change (Lindgren 2015). This chain demonstrates a PRESSURE-DEPENDENT ENDOCANNABINOID SYSTEM ACTIVATION THRESHOLD with molecular substrate in fascial CB receptors. 🟢 B04 §5.2, A06 §4.2.

**A07 Dermatome = MINOR.** Deep tissue work is typically area-based (along muscle/fascial planes), not point-specific. Segmental overlap incidental rather than targeted. 🟡 B04 §6.1.

**A08 MTJ = STRONG.** Gamma loop reset, trigger point deactivation (ischemic compression + reactive hyperemia + biochemical normalization), stretch tolerance. B04's Structural-Neural Dissociation: structural effects (thixotropy, HA) are REAL but TRANSIENT (minutes); neural effects (descending modulation, gamma loop reset) are PERSISTENT (days). 🟢 B04 §5.3, §6.1.

**A09 Meridian = MINIMAL.** Not point/meridian-based. Applied to muscle/fascial anatomy, not traditional point systems. 🟢 B04 §6.1.

### §3.1.5 — Detailed Notes: NEGATIVE PRESSURE

**A01 PNS = MODERATE.** Gate control (Aβ from sustained skin stretch under suction) and axon reflex (C fiber). 2/5 PNS mechanisms. Area-based → no somatovisceral reflex from point specificity. 🟢 B07 §6.1.

**A02 ANS = MODERATE.** Some sympathetic withdrawal from prolonged sensory input. No specific vagal engagement documented. Not a relaxation-oriented therapy. 🟡 B07 §6.1.

**A03 Fascia = STRONG.** Fascial decompression/distraction — the REVERSE of compression. Tissue lifted away from deeper structures, creating fascial stretch from the opposite direction. Unique mechanical environment not replicated by any compressive stimulus. 🟡 B07 §6.1.

**A04 Vascular = PRIMARY.** The DOMINANT pathway. HO-1 activation chain: capillary microtrauma (at sufficient suction) → macrophage phagocytosis of extravasated RBCs → heme oxygenase-1 induction → CO (anti-inflammatory gasotransmitter) + biliverdin (antioxidant) + ferritin (iron sequestration). Li 2023 NIRS: oxyHb ↑6.75 μM at -300 mmHg. Marks (petechiae/ecchymoses) = visible evidence of the mechanism in action. 🟢 B07 §5.2, A04 §3.5.

**A05 Neuroimmune = STRONG.** HO-1 → NF-κB↓ → cytokine reduction. M1-to-M2 macrophage polarization. Systemic HO-1 upregulation at multiple organ sites 48-120 hours post-treatment (Kwong 2009). The strongest evidence for systemic anti-inflammatory effect from a LOCAL stimulus. 🟢 B07 §5.2, B09 §5 (foundational HO-1 evidence).

**A06 Endocrine = MODERATE.** CO as gasotransmitter (HO-1 derivative, completing NO/CO/H₂S triad). Some β-endorphin release from immune cells in treatment area. Endocannabinoid system unlikely at this depth (no deep fascia CB engagement). 🟡 B07 §6.1.

**A07 Dermatome = MINIMAL.** Area-based application, not dermatome-specific, though traditionally applied at Back-Shu points and along Bladder channel. Any segmental effect is incidental to location choice, not to the stimulus type itself. 🟡 B07 §6.1.

**A08 MTJ = MINIMAL.** Suction is primarily superficial — affects skin and superficial fascia but does not reach deep muscle belly or joint structures. 🟢 B07 §6.1.

**A09 Meridian = MINIMAL.** Applied at traditional points/channels but mechanism is vascular/fascial, not meridian-specific. 🟡 B07 §6.1.

### §3.1.6 — Detailed Notes: HORIZONTAL SHEAR

**A01 PNS = MODERATE.** Gate control via Aβ from sustained tissue drag. Axon reflex from C fiber activation → CGRP/SP release. 2/5 PNS mechanisms. Area-based, no somatovisceral reflex from point specificity. 🟢 B09 §6.1.

**A02 ANS = MINIMAL.** No specific vagal evidence. Not a relaxation therapy. Sympathetic withdrawal minor. 🟡 B09 §6.1.

**A03 Fascia = STRONG.** Shear-SPECIFIC fascial mechanism: inter-layer sliding, adhesion disruption, HA thixotropy. 2025 TLF RCT (n=32, p=0.005): FIRST structural fascial verification — TLF thickness REDUCTION measurable by ultrasound after gua sha. Shear force is biomechanically distinct from compression for fascial effects. 🟢 B09 §5, A03 §8 Q8.

**A04 Vascular = PRIMARY.** Same HO-1 pathway as negative pressure: capillary microtrauma → macrophage → HO-1 → CO + biliverdin + ferritin. 400% microcirculation increase (Nielsen 2007). HIF-1α suppression with DMOG causal reversal (Ge 2025). Key irony: foundational HO-1 evidence comes FROM gua sha research, not cupping. Hepatoprotective effect via systemic HO-1 (Chan 2011: gua sha on skin → ↓ALT/AST in hepatitis B). 🟢 B09 §5, A04 §3.5.

**A05 Neuroimmune = MODERATE.** HO-1 → NF-κB↓, M1-to-M2 macrophage shift, Th1/Th2 modulation (Chan 2011). Less than negative pressure because shear produces more focal tissue disruption. 🟡 B09 §6.1.

**A06 Endocrine = MINIMAL.** CO gasotransmitter from HO-1. Endocannabinoid system engagement unlikely — gua sha targets skin/superficial fascia, too superficial for deep fascia CB1/CB2 (Fede 2016 localized CB receptors in deep fascial tissue). This differentiates horizontal shear from deep pressure. 🟡 B09 §6.1.

**A07 Dermatome = MINIMAL.** Area-based. Back treatment incidentally covers BL channel/paravertebral territory. 🟡 B09 §6.1.

**A08 MTJ = MODERATE.** Superficial muscle engagement from shear force transmission. IASTM variant specifically targets muscle tissue. No direct trigger point mechanism for standard gua sha (too superficial). 🟡 B09 §6.1.

**A09 Meridian = MINIMAL.** Traditionally applied along TCM channel trajectories but mechanism is vascular/fascial, not meridian-specific. 🟡 B09 §6.1.

### §3.1.7 — Detailed Notes: THERMAL

**A01 PNS = PRIMARY.** TRPV1 = molecular convergence hub (B08 §5.2): the "capsaicin receptor" activated at 42-43°C is ALSO the convergence node for endocannabinoids (AEA), eicosanoids (PGE2), and prevents MOR desensitization (sustains opioid analgesia, A06 line 817). C fiber activation → descending modulation. No other stimulus type directly activates this molecular hub via its primary stimulus. 🟢 B08 §5.2, A01 §3.

**A02 ANS = MODERATE.** Thermal somatoautonomic reflex: heat → TRPV1 → C fiber → segmental autonomic reflex (A02 §4.7, added in RC#5). Diving reflex parallel noted. No direct vagal pathway equivalent to needle/pressure. A02 §4 GAP flagged: heat as autonomic stimulus was undocumented before B08 analysis. 🟡 B08 §6.1, A02 §4.7.

**A03 Fascia = MINIMAL.** No mechanical force → no fascial engagement. Heat does not produce mechanotransduction, thixotropy, or fascial deformation. 🟢 B08 §6.1.

**A04 Vascular = PRIMARY.** Vasodilation is the primary EFFECTOR of heat. Local blood flow increase is direct and reliable. Lewis triple response enhanced by thermal stimulus. But mechanism is vasodilation, NOT HO-1 — thermal does not produce capillary microtrauma at therapeutic doses. 🟢 B08 §6.1, A04 §2.

**A05 Neuroimmune = MODERATE.** Cutaneous HPA activation (Slominski pathway). Some immune modulation. HSP (heat shock proteins HSP70/HSP27) = cytoprotective mechanism UNIQUE to thermal stimulus. No other stimulus type induces HSP. 🟢 B08 §5.2, A05 §2.

**A06 Endocrine = MODERATE.** Cutaneous HPA activation: skin CRH → POMC → ACTH + β-endorphin + α-MSH + cortisol. HSP pathway unique. TRPV1 prevents MOR desensitization → heat SUSTAINS opioid analgesia (A06). Oxytocin thermal selectivity: OT reverses thermal NOT mechanical antinociception (A06 line 589) — potentially more relevant to moxibustion than to needle therapies. 🟡 B08 §6.1, A06 §4.

**A07 Dermatome = STRONG.** Point-dependent somatovisceral reflex fully available when heat applied at specific acupoints. But: BL67 Breech Paradox = S1 dermatome has NO uterine viscerotome connection, yet Cardini 1998 JAMA (n=260, 75.4% vs 47.7%) = STRONGEST clinical evidence in Track B for its most MECHANISTICALLY INEXPLICABLE application. This challenges the A07 model. 🟢/🔴 B08 §4, A07 §3.

**A08 MTJ = MINIMAL.** No mechanical force on muscle, tendon, or joint structures. Indirect muscle relaxation via heat-induced vasodilation and reduced muscle spindle sensitivity, but this is secondary. 🟡 B08 §6.1.

**A09 Meridian = MODERATE.** Applied at same acupoint system as B01. 针灸 (zhēn jiǔ) = "needle + moxa" as historical TWIN — Western separation is artificial. Warm needling (温针灸) directly combines penetration + thermal at a single point. 🟡 B08 §6.1.

### §3.1.8 — Detailed Notes: JOINT THRUST

**A01 PNS = PRIMARY.** Proprioceptive burst: HVLA produces massive, brief activation of Type II (Pacinian, rapidly-adapting) mechanoreceptors in joint capsule (Pickar 2002). Post-activation depression in dorsal horn neurons (Reed 2014). Gate control also present. The VELOCITY of activation preferentially targets rapidly-adapting receptors — this is unique to HVLA vs. slow mobilization (which targets slowly-adapting Type I Ruffini). 🟢 B10 §5.2, A01 §3.

**A02 ANS = STRONG.** Somatoautonomic reflex via sympathetic chain proximity — thoracic spine HVLA directly borders sympathetic ganglia (unique anatomical feature, B10 §5.2). Budgell 2000: demonstrated autonomic effects. Welch 2008: sympathoexcitation → rebound. Kingston 2014: HRV inconsistent but autonomic response real (response ≠ treatment direction). 🟢 B10 §6.1, A02 §4.6.

**A03 Fascia = MODERATE.** Periarticular fascial stretch during joint gapping. Not the primary target — joint thrust passes through fascia but targets articular structures. 🟡 B10 §6.1.

**A04 Vascular = MINIMAL.** No vascular mechanism identified. HVLA does not target blood vessels or produce microtrauma. 🟢 B10 §6.1.

**A05 Neuroimmune = MINIMAL.** No tissue damage, no inflammatory cascade, no immune activation from joint thrust. 🟢 B10 §6.1.

**A06 Endocrine = MODERATE.** β-endorphin release documented (Plaza-Manzano 2014). Some local chemical milieu shift but not the defining pathway. 🟡 B10 §6.1.

**A07 Dermatome = STRONG.** Segmental convergence through SCLEROTOME (unique to joint thrust — other stimulus types work through dermatome). Each spinal level HVLA targets the corresponding vertebral segment, with potential somatovisceral reflex to organs sharing that segment. Budgell 2000: orphan citation now connected (A07 §4.7). Limitation: palpation reliability is low (κ = 0.02-0.39, A07 §4.7). 🟢 B10 §6.1, A07 §4.7.

**A08 MTJ = PRIMARY.** Joint = SENSORY ORGAN with 4 Freeman-Wyke receptor types (B10 §5.2). HVLA = sensory INPUT triggering proprioceptive reset — not mechanical realignment. Spindle burst + post-activation depression (Pickar 2002, Reed 2014). The ONLY stimulus type where A08 engagement is ARTICULAR rather than muscular/tendinous. This is conceptually distinct from all other A08 engagement in the matrix. 🟢 B10 §5.2, §6.1, A08 §3.

**A09 Meridian = MINIMAL.** Joint-based treatment, not meridian-based. Acupuncture point system is irrelevant to chiropractic targeting. 🟢 B10 §6.1.

### §3.1.9 — Detailed Notes: LIGHT PERCUSSION

**A01 PNS = MINIMAL.** Only rapidly-adapting Aβ mechanoreceptors (Meissner, Pacinian) activated. Gate control minimal — ceases within milliseconds of stopping. 0-1 of 5 PNS mechanisms at minimal intensity. B12 §6.1: "the WEAKEST somatic stimulus in Track B." 🟢 B12 §2.2, §6.1.

**A02 ANS = MINIMAL.** Possible trigeminal-vagal pathway (56% of EFT points are on the face = CN V territory). Cortisol reduction observed (Church 2012 ↓24%) but likely from cognitive/exposure component, not somatic. Status: uncertain, listed as MINIMAL due to insufficient evidence that the tapping itself (vs. the cognitive protocol) drives ANS effects. 🟡 B12 §6.1.

**A03-A04-A05 = NONE.** No tissue deformation → no fascial engagement. No sustained pressure or microtrauma → no vascular response. No inflammation → no immune activation. Confident absence. 🟢 B12 §6.1.

**A06 Endocrine = MINIMAL.** No opioid release, no endocannabinoid system activation, no adenosine. Cutaneous HPA possible but minimal at ~2-5N tapping force. 🟡 B12 §6.1.

**A07 Dermatome = MINIMAL.** Points map to CN V (trigeminal) + C3-C4, C8-T1, T2 territories. But all points are tapped every round regardless of condition → no somatovisceral specificity. 🟡 B12 §6.1.

**A08 MTJ = NONE.** No muscle engagement, no trigger point targeting, no proprioceptive input. 🟢 B12 §6.1.

**A09 Meridian = MINIMAL.** Uses TCM point names (e.g., "Karate Chop" = SI-3) but does not use the meridian point-selection system. Points are fixed regardless of presentation. 🟡 B12 §6.1.

**Critical note:** If EFT has clinical effects (meta-analyses suggest modest effects for anxiety/PTSD vs. active controls: g = -0.66, Gilomen 2015), those effects are almost certainly NOT driven by Track A body system mechanisms. The therapeutic effect must come from the cognitive protocol (exposure + acceptance + restructuring), therapeutic relationship, and expectancy. B12 is the therapy that most clearly demonstrates that clinical effects CAN arise without meaningful somatic mechanism engagement. 🟡 B12 §6.2.

### §3.1.10 — Detailed Notes: SELF-GENERATED MOVEMENT

**A01 PNS = STRONG.** Proprioceptive and motor afferents — self-generated, sustained activation of mechanoreceptors in muscles, tendons, joints, and fascia. Different from passive therapies: the MOTOR component means PNS is engaged bidirectionally (afferent sensing + efferent motor commands). 🟢 B15 §6.1, B16 §6.1.

**A02 ANS = PRIMARY.** Voluntary breathing = Zone D Bridge — the ONLY visceral function under BOTH automatic AND voluntary control. This gives B15/B16 UNIQUE voluntary ANS access that no passive therapy can match. Slow breathing (4-6/min, resonance frequency) maximizes HRV via respiratory sinus arrhythmia amplification. B16 pranayama is uniquely BIDIRECTIONAL: calming techniques (Ujjayi, Nadi Shodhana, 4:7:8) increase parasympathetic + activating techniques (Kapalabhati, Bhastrika) increase sympathetic. No other stimulus type can deliberately induce sympathetic activation as a therapeutic tool. Sustained practice → autonomic retuning (A02 §4.8-§4.9). 🟢 B15 §2.2, B16 §2.2, A02 §4.8-§4.9.

**A03 Fascia = MODERATE (style-dependent).** Ranges from STRONG (Yin yoga: sustained passive poses 1-20 min for connective tissue creep) to MODERATE (Tai Chi: continuous movement, less sustained load) to MINIMAL (standing qigong). B16's Yin style is the second most fascial-engaged after B04, but the generic stimulus type is MODERATE. 🟡 B16 §2.3, B15 §6.1.

**A04 Vascular = MODERATE.** Cardiovascular effects from sustained low-intensity movement. Blood pressure reduction documented for both B15 and B16. But vascular is not the defining pathway — it's a consequence of movement, not the therapeutic mechanism. 🟢 B15 §6.1, B16 §6.1.

**A05 Neuroimmune = MODERATE.** Dual anti-inflammatory pathway: (1) myokine IL-6 from muscle contraction (A05 §4.4) + (2) vagal anti-inflammatory from breathing (A05 §2.4). Shu 2021: TNF-α SMD -0.92, IL-6 SMD -0.62 for Tai Chi. But effects require sustained practice. 🟢 B15 §5.2, A05 §4.

**A06 Endocrine = MODERATE.** Endocannabinoid system activation from sustained movement (eCB hypothesis, NCT03823157 pending). GABA hypothesis unique to B16 yoga (Streeter 2007-2012: yoga > metabolically-matched walking for brain GABA). Bower 2014: transcriptional anti-inflammatory (NF-κB↓, GR↑). But chemical milieu effects are secondary to neural/autonomic. 🟡 B16 §5.2, B15 §6.1.

**A07 Dermatome = MODERATE.** Whole-body proprioceptive input provides broad segmental activation. Not dermatome-specific but covers multiple levels simultaneously. 🟡 B15 §6.1, B16 §6.1.

**A08 MTJ = PRIMARY.** Proprioceptive challenge (continuous weight shifting, single-leg phases in B15), motor learning (complex movement sequences → neuroplastic adaptation), strength/flexibility (isometric holds, eccentric loading, gravity-loaded body weight). Joint mechanoreceptors (Freeman-Wyke Types I-III) continuously activated during balance work. B15 fall prevention (Li 2018 JAMA: 58% reduction, NNT~3-4) and Parkinson's balance (Li 2012 NEJM) demonstrate A08 as the primary clinical outcome pathway. 🟢 B15 §5.2, B16 §5.2, A08 §4.

**A09 Meridian = MODERATE.** Relevant for Tai Chi/Qigong meridian theory and yoga nadi theory, but the mechanism is exercise physiology, not meridian-specific. 🟡 B15 §6.1, B16 §6.1.

### §3.2 — Parameter Modifiers

Within each stimulus type, changing parameters shifts the activation profile. The most clinically important parameter modifiers are documented below.

#### §3.2.1 — Pressure Magnitude (Compressive Stimulus Types)

Affects: Sustained Point Pressure, General Pressure, Deep Pressure
The B03 Pressure-Dependent Pathway Model (B03 §2.2) describes a systematic pathway switch as pressure increases:

```
PRESSURE LEVEL      FORCE        PRIMARY PATHWAY          DOMINANT SYSTEM
─────────────────── ──────────── ──────────────────────── ────────────────
Ultra-light         <0.5 N       Lymphangion pump         A04 (lymphatic)
Light               ~8-10 N      CT afferents, oxytocin   A01 (CT), A06 (OT)
Moderate            ~20-60 N     Aβ gate control + vagal  A01 (gate), A02
Deep                ~65-110 N    Aδ/C desc. modulation    A01 (desc.), A06 (endocannabinoid system)
Very deep           >110 N       Full desc. mod. cascade  A01+A03+A06+A08
```

**Critical threshold: endocannabinoid system activation.** Light touch = NO endocannabinoid system change (Lindgren 2015); deep OMT = AEA ↑168% (McPartland 2005). CB1/CB2 in fascial fibroblasts (Fede 2016). This implies a discrete depth/pressure threshold for endocannabinoid system engagement, somewhere in the transition from moderate to deep pressure. 🟡 The exact threshold has not been measured across therapies. (B04 §5.2, A06 §4.2)

#### §3.2.2 — Speed/Velocity

Affects: General Pressure, Joint Thrust, Light Percussion
- **CT afferent optimal window:** 1-10 cm/s (A01 §3). Speed ABOVE this range → CT engagement drops sharply. Massage speed must be slow for affective touch pathway activation.
- **Joint thrust velocity threshold:** HVLA requires <200ms thrust duration. Below this speed → mobilization (Grade I-IV), qualitatively different receptor activation (Type I Ruffini slowly-adapting vs. Type II Pacinian rapidly-adapting). B10 §2.5: "the defining feature is RATE of force application, not peak force." 🟢

#### §3.2.3 — Depth of Penetration (Needle Stimulus)

Affects: Penetration only
- **Superficial (5-10mm, SDN):** Subcutaneous tissue only. Aδ gate control dominant (L2 segmental). No LTR. 90% response rate for uncomplicated nociceptive pain (Baldry). Profile approaches Sustained Point Pressure.
- **Deep (20-50mm, DDN):** Muscle belly. Trigger point targeting, LTR, endplate disruption. A08 engagement increases to PRIMARY.
- **Variable-depth variants:** FSN (subcutaneous connective tissue, A03 fascial-dominant), periosteal pecking (bone surface, DNIC-dominant).
- **Key finding:** SDN ≈ deep DN for clinical outcomes in several studies (Cummings & White 2001 systematic review). This suggests L2 gate control may be sufficient for many pain conditions without needing L1 local trigger point disruption. 🟢 B11 §2.1-§2.6.

#### §3.2.4 — Electrical Parameters (Modifier of Penetration)

Affects: Penetration with electrical augmentation (EA, DNWES, PENS)
- **Frequency → opioid type:** 2 Hz = enkephalin/β-endorphin (μ/δ); 100 Hz = dynorphin (κ); alternating = all (Han Ji-Sheng, B01 §2.4)
- **Intensity → pathway:** Low (0.5 mA) = PROKR2+ vagal-adrenal anti-inflammatory; High (3.0 mA) = spinal sympathetic (Liu 2020/2021)
- **Clinical implication:** Electrical augmentation SELECTIVELY enhances A06 (endocrine/opioid) beyond what manual needle manipulation achieves. This is a PARAMETER MODIFIER, not a separate stimulus type.
- **EA vs. TENS:** Same frequency-dependent opioid release but EA delivers current through tissue depth (via needle) while TENS delivers to skin surface only. 🟢 B01 §2.4.

#### §3.2.5 — Body Region (All Stimulus Types)

Affects: ALL stimulus types, but most dramatically for Sustained Point Pressure
- **Face (CN V trigeminal territory):** Direct brainstem access → DMN (vagal), NTS, LC (NE), DRN (5-HT). A02 engagement ELEVATES to PRIMARY for facial stimulation.
- **Ear (ABVN territory):** Direct vagal nerve branch access → NTS. A02 engagement ELEVATES to PRIMARY for auricular stimulation.
- **Body (mixed spinal nerves):** Standard somatovisceral reflex. A07 engagement depends on dermatome-organ match.
- **Foot sole (L4-S3):** NO special pathway. Glabrous skin → NO CT afferents (cannot activate affective touch). Weakest regional pathway access.
- This modifier is the primary subject of C04 (Location-Specificity-Map). See C04 for full analysis.
- 🟢 Neuroanatomy (B06 §2.1, A07 §3-§4)

#### §3.2.6 — Skin Contact Barrier

Affects: All compressive stimulus types
- **Skin-to-skin:** CT afferents AVAILABLE (if hairy skin + slow speed). Oxytocin via CT→PVN pathway active.
- **Through clothing (B13 Shiatsu):** CT afferents BLOCKED. Removes affective touch pathway entirely. Real mechanistic trade-off for modesty/practicality. 🟢 (B13 §5, A01 §3)
- **Glabrous skin (palms, soles):** CT afferents ABSENT regardless of contact type. B06 foot reflexology cannot activate affective touch pathway. 🟢 (A01 §3)

#### §3.2.7 — Movement Style (Self-Generated Movement)

Affects: Self-Generated Movement only
B16 Yoga's Adaptive Spectrum Model (B16 §5.3): the SAME stimulus category produces different Track A profiles depending on style selection:

```
STYLE          INTENSITY   PRIMARY SYSTEM EMPHASIS
────────────── ─────────── ────────────────────────
Yin Yoga       ~2 METs     A03 Fascial (sustained passive holds)
Restorative    ~2 METs     A02 Autonomic (parasympathetic dominance)
Hatha          ~3 METs     Balanced (general MSK + ANS)
Iyengar        ~3 METs     A08+A01 (alignment + proprioception)
Vinyasa        ~5 METs     A04+A08 (cardiovascular + strength)
Ashtanga       ~7-8 METs   A08 (athletic, exercise physiology)
Kundalini      Variable    A02+A06 (autonomic + neurochemical)
Bikram         ~5 METs     A04 + Thermal (heat overlay)
```

This makes Self-Generated Movement the ONLY stimulus type where the activation profile is user-configurable. 🟡 B16 §2.3.

### §3.3 — Therapy-to-Stimulus Mapping

Each therapy uses one or more stimulus types. This many-to-many mapping connects the stimulus-level matrix (§3.1) back to the therapy-level profiles documented in Track B §6 sections.

```
THERAPY                  PRIMARY STIMULUS          SECONDARY/MINOR           NOTES
──────────────────────── ───────────────────────── ───────────────────────── ──────────────────
B01 Acupuncture          Penetration               Electrical (EA variant)   Warm needle adds
                                                    Thermal (warm needle)     thermal overlay
B02 Acupressure          Sustained Point Pressure   —                        Self-admin capable
B03 Massage-General      General Pressure           —                        Spans full pressure
                                                                              continuum
B04 Deep Tissue/MFR      Deep Pressure              Horiz. Shear (IASTM)     5 force vectors
B06 Reflexology          Sustained Point Pressure   —                        Foot L4-S3 only
                          (foot)
B07 Cupping              Negative Pressure          Thermal (moxa-cupping)    Wet adds bloodlet
B08 Moxibustion          Thermal                    Penetration (warm needle) 针灸 unity
B09 Gua Sha              Horizontal Shear           —                        HO-1 sibling B07
B10 Chiropractic         Joint Thrust               General Pressure          Grade I-IV =
                                                     (mobilization)            mobilization
B11 Dry Needling         Penetration                Electrical (DNWES)        trigger point-focused entry
B12 EFT Tapping          Light Percussion           COGNITIVE COMPONENT*      *Non-somatic
B13 Shiatsu              Sustained Point Pressure   Joint Mobilization        Through clothing
                          (whole-body, clothed)       (Zen Shiatsu stretches)
B14 Craniosacral         Sustained Point Pressure   —                        Ultra-light (~5g
                          (ultra-light, cranial)                               claimed, 50-500g
                                                                              likely)
B15 Tai Chi/Qigong       Self-Generated Movement    —                        6-component
                          (composite)                                         composite
B16 Yoga Therapy         Self-Generated Movement    —                        Style-configurable
                          (composite)

* B12's cognitive component (exposure + acceptance + restructuring) is NOT a Track A
  stimulus type. It operates through psychological mechanisms (Evaluative Gates in Human-Predictive-Drive
  framework). This is the ONLY therapy where the non-somatic component is likely the
  primary active ingredient.
```

**Pattern from mapping:** Most therapies (11/15) use a single primary stimulus type. B01 is the most multi-modal (penetration + electrical + thermal variants). B15/B16 use a COMPOSITE stimulus that combines multiple simultaneous sub-components (movement + breathing + attention + balance) under one category.

---

## §4 — EMERGENT PATTERNS

Patterns discovered FROM the cross-reference that are NOT visible in individual Track A or Track B files.

### §4.1 — System Dominance Fingerprints 🟡

Each stimulus type produces a distinctive "fingerprint" of 1-2 dominant Track A systems. This fingerprint predicts the therapy's primary mechanism pathway better than the therapy's identity:

```
STIMULUS TYPE              DOMINANT SYSTEMS              FINGERPRINT LABEL
────────────────────────── ───────────────────────────── ──────────────────────
Penetration                A01 PNS + A06 Endocrine       Neural-Chemical
Sustained Point Pressure   A01 PNS + A07 Dermatome       Neural-Convergence
General Pressure           A01 PNS + A05 Neuroimmune     Neural-Immune
Deep Pressure              A03 Fascia + A06 Endocrine    Fascial-Endocannabinoid
Negative Pressure          A04 Vascular + A05 Neuroimm   Vascular-Immune
Horizontal Shear           A04 Vascular + A03 Fascia     Vascular-Fascial
Thermal                    A01 PNS + A04 Vascular        Detection-Effector
Joint Thrust               A08 MTJ + A01 PNS             Articular-Proprioceptive
Light Percussion           (No dominant system)           Sub-threshold
Self-Generated Movement    A02 ANS + A08 MTJ             Autonomic-Motor
```

**Implication:** STIMULUS TYPE predicts mechanism pathway. Two therapies using the same stimulus type (e.g., B01 and B11 both using penetration) should have similar Track A profiles regardless of their theoretical frameworks. B01 and B11 confirm this: 93.3% anatomical overlap, "Different Entry Point, Same Building" (B11 §5.3). Conversely, therapies using different stimulus types (e.g., B01 penetration vs. B03 general pressure) will have different mechanism profiles even when applied to the same body area. 🟡 Synthesis from all 15 Track B §6 profiles.

### §4.2 — Force Direction Typology 🟡

The body responds to force DIRECTION, not just force MAGNITUDE. Five distinct force directions are represented in Track B, each activating different pathways:

```
FORCE DIRECTION    STIMULUS TYPE         PRIMARY PATHWAY          UNIQUE MECHANISM
────────────────── ───────────────────── ──────────────────────── ─────────────────────
Perpendicular ↓    Point/General/Deep    Gate control → endocannabinoid system       Pressure-dependent
                    Pressure                                       pathway switching
Penetration ↓↓     Needle insertion      Micro-wound → adenosine  Tissue penetration
                                          → chemical milieu        bypass
Decompression ↑    Negative Pressure     Capillary distension     Inverted force
                                          → HO-1                   direction
Lateral →          Horizontal Shear      Inter-layer sliding      Shear-specific
                                          + HO-1                   fascial effect
Rapid thrust →→    Joint Thrust          Proprioceptive burst     Velocity as primary
                                          (Type II Pacinian)       parameter
```

**Key insight:** Force DIRECTION predicts Track A profile more accurately than force MAGNITUDE. B10 chiropractic (thrust, 100-600N) and B04 deep tissue (compression, 40-110N) have comparable force magnitudes but completely different Track A fingerprints (Articular-Proprioceptive vs. Fascial-Endocannabinoid) because force direction and target tissue differ. 🟡

### §4.3 — The Mechanical Dominance of Body-Based Therapy 🟢

14 of 15 Track B therapies use MECHANICAL stimulus as their primary input. B08 moxibustion is the ONLY purely thermal therapy.

This reveals: **mechanotransduction is the dominant signal pathway in body-based therapy.** The cellular machinery for converting mechanical force into biological signals (integrin-FAK-YAP, Piezo1/TRPV4 ion channels, purinergic ATP signaling, collagen winding) is more broadly engaged across therapies than any other signal type.

TRPV1 (B08's primary target) is molecularly unique — a convergence hub for heat + endocannabinoid system + eicosanoids + opioid sustain. This suggests thermal stimulation may be systematically under-explored as a therapeutic modality, given the molecular richness of its primary receptor.

No purely CHEMICAL or BIOELECTRICAL primary stimulus types exist in Track B. Both are always secondary or hypothetical. 🟢

### §4.4 — The Active-Passive Paradigm Shift 🟡

```
PASSIVE (B01-B14): Stimulus applied TO patient
  → Reflex/response pathways → Involuntary system engagement
  → Patient role: recipient

ACTIVE (B15-B16): Stimulus generated BY patient
  → Voluntary ANS access + proprioceptive-motor loop + neuroplasticity
  → Patient role: agent
```

This paradigm shift introduces mechanisms UNAVAILABLE to passive therapies:
1. **Voluntary ANS access** via breathing (Zone D Bridge) — no passive therapy can voluntarily modulate ANS
2. **Motor learning** → neuroplastic adaptation that persists and compounds over years
3. **Self-efficacy** → psychological empowerment (B16: self-efficacy mediates 36% of disability effect)
4. **Safety** → highest in Track B (no external risk; Wayne 2014: 153 RCTs, no serious adverse events)
5. **BROADEST Track A activation** — B15 activates ALL 9 systems at MODERATE or above (7/9 systems), the widest profile in Track B

**But:** Active therapies require patient motivation, learning capacity, and sustained practice (12+ weeks in most positive RCTs). The "practice IS the therapy" — acute effects are modest, cumulative effects are substantial. This fundamentally differs from passive therapies where a single session can produce measurable physiological change. 🟡

### §4.5 — HO-1 Microtrauma Pathway Family 🟢

Two stimulus types — negative pressure (B07) and horizontal shear (B09) — share the SAME biochemical endpoint (HO-1 activation) via DIFFERENT mechanical paths:

```
B07 Cupping (vertical suction)  →  capillary distension/rupture  ──┐
                                                                     ├→ HO-1 → CO + biliverdin + ferritin
B09 Gua Sha (horizontal shear)  →  capillary shear disruption   ──┘
```

Requirements for HO-1 activation: controlled capillary microtrauma sufficient to produce extravasated RBCs for macrophage phagocytosis. This means:
- ✓ Activated by: B07 cupping (marks), B09 gua sha (sha), B04 IASTM (if sha produced)
- ✗ NOT activated by: B03 general massage (insufficient microtrauma), B02 acupressure (no capillary disruption), B08 moxibustion (thermal ≠ mechanical microtrauma), B01 acupuncture (needle micro-wound → different pathway: DAMPs/mast cell, not HO-1)

Key irony: foundational HO-1 evidence (Kwong 2009, Nielsen 2007, Ge 2025) comes FROM gua sha research, not cupping — yet cupping has more clinical trials. 🟢 B07 §5.2, B09 §5, A04 §3.5.

### §4.6 — Endocannabinoid System Pressure Threshold 🟡

A discrete pressure/depth threshold separates two distinct chemical responses:

```
BELOW THRESHOLD (light-moderate pressure)     ABOVE THRESHOLD (deep pressure)
──────────────────────────────────────────    ─────────────────────────────────
Oxytocin via CT afferents                    AEA ↑168% (endocannabinoid)
No endocannabinoid system change (Lindgren 2015)                CB1/CB2 in fascial fibroblasts (Fede 2016)
Affective touch pathway                      Deep fascial mechanotransduction
B03 light massage, B14, B02 light hold       B04 deep tissue, B03 deep, B01 (needle reaches)
```

The molecular substrate for this threshold is CB1/CB2 receptor expression in DEEP fascial fibroblasts (Fede 2016, A03 §1.4). Pressure must be sufficient to reach deep fascia where CB receptors are located. This creates a binary: therapies that reach deep fascia → can activate the endocannabinoid system; therapies that remain superficial → cannot.

The threshold appears to be in the 40-65N range based on the B03/B04 transition, but has NOT been systematically measured. 🟡 B04 §5.2, B03 §2.2, A06 §4.2.

### §4.7 — CT Afferent Engagement Pattern 🟢

CT (C-tactile) afferents — the slow-conducting unmyelinated fibers that encode pleasant/affective touch — have MORE RESTRICTIVE activation requirements than commonly assumed:

```
REQUIREMENT                          WHICH THERAPIES MEET IT?
──────────────────────────────────── ────────────────────────────────────────────
(a) Skin-to-skin contact             B01✓ B02✓ B03✓ B04✓ B06✓ B07✓ B08-
                                      B09✓ B10✓ B11✓ B12~  B13✗ B14✓ B15✗ B16✗
(b) Hairy skin (not glabrous)        Face: partial (forehead/temples ✓, lips ✗)
                                      Foot sole: ✗ (glabrous)
                                      Scalp: ✓ (hairy)
                                      Body: mostly ✓
(c) Slow speed 1-10 cm/s             B03 effleurage ✓, B12 tapping ✗ (too fast),
                                      B10 HVLA ✗ (too fast), B04 sustained ✓
```

**Therapies with CONFIRMED CT engagement:** B03 light massage (optimal), B14 craniosacral (hairy scalp, slow), B02 light hold techniques
**Therapies BLOCKED from CT engagement:** B13 Shiatsu (clothing), B06 foot reflexology (glabrous sole), B15/B16 (self-generated, no external practitioner touch)
**Therapies with UNCERTAIN CT engagement:** B12 EFT (face but too fast)

B13's clothing barrier is a measurable mechanistic loss: Shiatsu through clothing → NO CT afferent activation → no oxytocin via CT→PVN pathway. This is a real trade-off between practicality/modesty and affective touch mechanism. 🟢 A01 §3, B13 §5, B06 §2.1.

### §4.8 — Needle Family Convergence 🟡

B01 (acupuncture) and B11 (dry needling) use the same physical tool (filiform needle) at largely the same anatomical locations (93.3% overlap, Dorsher 2009) with the same primary stimulus type (penetration). Their Track A profiles are nearly identical — the differences are in EMPHASIS (B01 broader scope L1-L6, B11 narrower trigger point-focused L1-L2) and THEORETICAL FRAMEWORK (TCM meridians vs. Western NMJ hypothesis).

```
                        B01 Acupuncture          B11 Dry Needling
                        ───────────────────      ──────────────────
Tool                    Filiform needle           Filiform needle (same)
Anatomical sites        Acupoints                 trigger points (93.3% overlap)
Primary stimulus        Penetration               Penetration (same)
Manipulation           Lifting-thrusting/         Pistoning/pecking
                        twirling (De Qi)           (LTR)
EA variant             Yes (electroacupuncture)   Yes (DNWES/PENS)
A06 emphasis           PRIMARY (adenosine, Han)   MODERATE
A08 emphasis           MODERATE                   PRIMARY (trigger point focus)
Scope                  L1-L6 (broadest)           L1-L2 (narrowest)
Theory                 TCM meridians              NMJ hypothesis
```

"Different Entry Point, Same Building" (B11 §5.3). The physical stimulus is ≈identical; the divergence is in how practitioners conceptualize and deploy the needle. 🟡 Prediction: well-designed RCTs matching needle parameters should show minimal outcome difference for overlapping conditions.

### §4.9 — Therapeutic Scaffolding Cluster 🟡

Four therapies cluster at the BOTTOM of Track A engagement while maintaining some clinical effects:

```
THERAPY     PRIMARY        A01  A02  A03  A04  A05  A06  A07  A08  A09  TOTAL
            STIMULUS                                                     ABOVE MOD
──────────  ───────────── ──── ──── ──── ──── ──── ──── ──── ──── ──── ────────
B06 Reflex  Pt Pressure   MOD  MNR  MNR  MNR  MIN  MIN  MNR  MIN  NON  1
            (foot)
B12 EFT     Light Perc    MIN  MIN  NON  NON  NON  MIN  MIN  NON  MIN  0
B14 CST     Pt Pressure   MIN  MNR  MIN  NON  NON  MIN  NON  MNR  NON  0
            (ultra-light)
```

B06, B12, B14 share: weakest somatic engagement + unvalidated/contradicted stated mechanisms + clinical effects (when present) likely from non-specific pathways + elaborate theoretical frameworks that serve as SCAFFOLDING (enhance therapeutic context via Evaluative Gates, Human-Predictive-Drive).

Full analysis of therapeutic scaffolding is the subject of C03 §3.4. C01 contributes: these therapies cluster at the bottom of the matrix NOT by coincidence but because their stimulus types (light percussion, ultra-light point pressure on foot/skull) are below effective threshold for most Track A systems. 🟡

### §4.10 — Pressure Continuum Across Therapies 🟡

Arranging all pressure-based therapies by force magnitude reveals a continuous spectrum with qualitative pathway transitions:

```
FORCE        THERAPY/CONTEXT              PATHWAY TRANSITION
───────────  ──────────────────────────── ─────────────────────────────────────
~5g (0.05N)  B14 Craniosacral (claimed)   Below ALL activation thresholds?
~5-10N       B02 Jin Shin Jyutsu hold     CT afferents (if hairy skin)
~8-10N       B03 Light effleurage         CT afferent optimal → oxytocin
~20-60N      B03 Moderate petrissage      Aβ gate control + vagal shift
~30-50N      B02 Standard acupressure     Gate control + somatovisceral
~40-65N      ── endocannabinoid system ACTIVATION THRESHOLD ── (estimated, not measured)
~40-110N     B04 Deep tissue/MFR          A03 fascial + A06 endocannabinoid system dominant
~65-110N     B03 Deep compression         Descending modulation + endocannabinoid system
~75-150 kPa  B06 Foot reflexology         Gate control (thick skin barrier)
~150+ N      B04 Elbow on trigger point             Full descending modulation cascade
```

This continuum explains why "pressure-based therapies" is not a homogeneous category — pressure MAGNITUDE determines which Track A systems are engaged, making a B14 craniosacral session and a B04 deep tissue session fundamentally different interventions despite both using "pressure." 🟡

---

## §5 — PREDICTIONS & TESTABLE HYPOTHESES

Each prediction states what would confirm or refute it. All predictions are 🔴 Hypothesis.

### P1 — Endocannabinoid System Activation Threshold Is Measurable and Consistent

**Prediction:** There exists a specific force threshold (~40-65N based on B03/B04 data) above which endocannabinoid system engagement begins, measurable by plasma AEA levels. Below this threshold: oxytocin-dominant (CT pathway); above: AEA-dominant (endocannabinoid system pathway). This threshold should be consistent across pressure-based therapies (B02, B03, B04) because the underlying mechanism (pressure reaching fascial CB1/CB2 receptors) is stimulus-type-independent.

**Confirm:** Systematic force-response study measuring AEA at 5 pressure levels (10, 30, 50, 70, 100N) across therapists shows consistent threshold with ≤20% inter-individual variation.
**Refute:** AEA response is idiosyncratic, or varies dramatically by body region/therapy type at the same pressure level, suggesting receptor-independent factors.

### P2 — Superficial Dry Needling ≈ Deep Acupressure

**Prediction:** Superficial dry needling (B11 SDN, 5-10mm, subcutaneous only) should have a Track A profile closer to sustained point pressure (B02 deep tool, 50-80N) than to deep dry needling (B11 DDN, 20-50mm, intramuscular). Both SDN and deep acupressure activate predominantly L2 gate control without reaching deep muscle trigger points.

**Confirm:** Head-to-head SDN vs. deep acupressure at matched points for myofascial pain shows comparable outcomes (difference < 0.3 SMD) and similar EEG/fMRI activation patterns.
**Refute:** SDN clearly outperforms deep acupressure (>0.5 SMD), suggesting needle penetration adds mechanistic value even at superficial depth.

### P3 — Sliding Cupping Dissociates A03 from A04

**Prediction:** Sliding cupping (B07 variant, low pressure -100 to -200 mmHg, continuous movement) should activate MORE fascial (A03) mechanisms and LESS vascular (A04/HO-1) than stationary cupping, because sliding reduces capillary microtrauma (no marks) while maintaining fascial decompression.

**Confirm:** Sliding cupping produces no sha/petechiae, comparable fascial outcomes (TLF thickness by ultrasound), but lower HO-1 markers than stationary cupping in same patients.
**Refute:** Sliding cupping produces equivalent HO-1 despite no visible marks, suggesting HO-1 activation threshold is lower than visible capillary rupture.

### P4 — EFT Tapping Without Cognitive Protocol Is Inert

**Prediction:** EFT tapping alone (tapping on the standard 9 points while thinking of neutral content, no exposure/acceptance/restructuring) should show no clinical benefit for anxiety or PTSD, because C01 matrix shows light percussion activates virtually NO Track A systems above MINIMAL.

**Confirm:** Tap-only condition shows no significant difference from no-treatment control on SUDS, cortisol, or anxiety measures.
**Refute:** Tap-only shows partial effect (0.3-0.5 SMD reduction in anxiety), suggesting trigeminal-vagal pathway (CN V) activation from facial tapping is more mechanistically relevant than current data indicates. This would require upgrading A02 for light percussion from MINIMAL to MODERATE.

### P5 — Breathing Component Decomposition in Tai Chi

**Prediction:** Tai Chi/Qigong breathing exercises alone (paced breathing at 4-6/min, no movement) should activate A02 (autonomic) at similar levels to full Tai Chi but with substantially LOWER A08 (musculoskeletal) and A03 (fascial). If confirmed, this validates decomposition of B15's composite stimulus.

**Confirm:** Breathing-only matches full Tai Chi on HRV, blood pressure, and autonomic markers (within 0.3 SMD) but shows significantly less improvement in balance, strength, and fall risk.
**Refute:** Full Tai Chi shows significantly better autonomic outcomes than breathing alone, suggesting movement-breathing INTERACTION produces emergent autonomic effects beyond breathing component.

### P6 — Machine Pressure ≈ Human Pressure for Somatovisceral, Not Psychological

**Prediction:** Machine-applied standardized pressure at acupoints (B02-type) should produce effects comparable to human acupressure for somatovisceral conditions (like P6 anti-nausea, NNT≈4) but LOWER effects for psychological conditions (anxiety, insomnia), because the machine lacks CT afferent engagement (no warm human skin), therapeutic relationship, and Evaluative Gates that human touch provides.

**Confirm:** Machine acupressure matches human on P6/PONV and blood pressure, but underperforms on anxiety and sleep outcomes.
**Refute:** Machine performs equivalently across all conditions, suggesting Evaluative Gates contribution is smaller than expected for somatovisceral-targeted point pressure.

### P7 — Thermal + Penetration Interaction (Warm Needling)

**Prediction:** Warm needling (温针灸, B08 + B01 combined) should show a Track A profile that is MORE than the sum of penetration and thermal profiles, because TRPV1 activation by heat PREVENTS MOR desensitization (A06 line 817), meaning heat SUSTAINS the opioid analgesia produced by needling. This predicts a SYNERGISTIC interaction, not merely additive.

**Confirm:** Warm needling produces longer-lasting analgesia (>48h vs <24h) than same-duration needling alone, with β-endorphin levels remaining elevated longer.
**Refute:** Warm needling ≈ needling + sham heat in duration of analgesia, suggesting TRPV1-MOR interaction is insufficient for clinical synergy.

### P8 — Stimulus Type Predicts Clinical Domain Better Than Therapy Identity

**Prediction:** Two therapies sharing the same stimulus type (e.g., B01 acupuncture and B11 dry needling — both penetration) should have MORE overlapping clinical efficacy profiles than two therapies with different stimulus types (e.g., B01 acupuncture and B03 massage — penetration vs. general pressure), controlling for condition severity and study quality.

**Confirm:** Meta-analytic comparison of clinical overlap shows >70% condition overlap within-stimulus-type vs. <40% across-stimulus-type.
**Refute:** Clinical efficacy profiles are more determined by treatment protocol, dosing, or practitioner factors than by stimulus type, showing similar overlap rates within and across types.

---

## §6 — LIMITATIONS & GAPS

### §6.1 — Methodological Limitations

1. **Ordinal scale is semi-quantitative.** PRIMARY vs. STRONG is a judgment call based on mechanism analysis, not a measured physiological value. Direct comparative measurement studies between stimulus types are largely absent from the literature.

2. **System independence assumption.** The matrix treats each Track A system as independent, but systems interact extensively: A01 gate control facilitates A02 parasympathetic shift, A03 fascial mechanotransduction activates A05 neuroimmune pathways (NF-κB↓), A06 endocannabinoid system cross-talks with A01 opioid pathways. The matrix captures individual system engagement but not system interactions.

3. **Decomposition challenge.** Assigning activation levels to stimulus types (not therapies) requires decomposing therapy-level data. For therapies with single stimulus types (B07 cupping → negative pressure), this is straightforward. For composite therapies (B15 Tai Chi = 6 components), decomposition involves judgment calls about which component drives which system.

4. **Inferred profiles.** B13 Shiatsu has ZERO dedicated mechanism studies — all activation levels are inferred from B02/B03 research. B14 Craniosacral's stated mechanism is contradicted but alternative mechanisms are inferred. These inferred profiles are less reliable than directly studied profiles (B01, B03, B04).

### §6.2 — Missing Data

1. **No systematic force-response studies** comparing the SAME stimulus type across different therapies at standardized parameters.
2. **Endocannabinoid system activation threshold** has not been precisely measured — estimated from B03/B04 comparison only.
3. **CT afferent contribution** to clinical outcomes has not been isolated in any therapy.
4. **Light percussion** (B12) lacks any force measurement studies — all parameters are estimated.
5. **B14 Craniosacral** actual applied force has never been measured with a force transducer — "5g" is self-reported.
6. **Composite stimulus interactions** (B15/B16) have never been decomposed in component-isolation RCTs.

---

## §7 — OPEN QUESTIONS

Questions RAISED BY the cross-reference analysis that only become visible when comparing across therapies.

**Q1 (CRITICAL). Universal force-pathway function?** Is there a single mathematical function relating applied force to Track A system activation, or does receptor density variation (by body region, individual, pathology state) make force thresholds fundamentally region-specific? The pressure continuum (§4.10) suggests regularity, but C04 may reveal region-specific exceptions.

**Q2. Endocannabinoid system activation threshold.** What is the precise pressure/depth threshold for endocannabinoid system engagement? Can it be measured consistently across therapies and body regions? Is it a sharp threshold or a gradual transition? (§4.6)

**Q3. Velocity as independent parameter.** Does the VELOCITY of force application (B10 HVLA <200ms vs. B03 massage over seconds) activate fundamentally different neural processing, or is it merely a quantitative difference in the same pathways? The Type I/Type II receptor distinction (B10 §2.5) suggests qualitative difference. (§3.2.2)

**Q4. Composite stimulus emergence.** Do multiple simultaneous stimulus types (as in B15/B16 composite) produce EMERGENT effects beyond the sum of individual components? B15's fall prevention superiority over matched exercise suggests possible emergence. Component decomposition studies are needed. (§4.4)

**Q5. Thermal therapy under-explored?** Given TRPV1's unique molecular convergence properties (heat + endocannabinoid system + eicosanoid + opioid sustain), why has thermal stimulus not been more systematically developed as a therapeutic modality? Is the historical dominance of mechanical therapies due to genuine mechanistic advantage or cultural/historical accident? (§4.3)

**Q6. Habituation dynamics.** How does repeated exposure to the same stimulus type change the activation profile over time? Do receptors adapt, requiring dose escalation? Or does neuroplastic adaptation make repeated exposure MORE effective (as suggested by B15/B16 practice effects)? This question crosses all stimulus types but has only been studied for B01 (Vickers ATC dose-response). (§3.2)

**Q7. Cognitive component contribution.** B12 demonstrates that clinical effects can occur with near-zero Track A engagement. What fraction of clinical effects in OTHER therapies (even strongly somatic ones like B01, B03) comes from cognitive/contextual factors rather than somatic mechanisms? This is fundamentally the Evaluative Gates question extended across the matrix. (§4.9, C03 will address further)

**Q8. Stimulus-type-based therapy design.** Can novel therapies be rationally designed by selecting stimulus types to target specific Track A system profiles? For example: a therapy targeting A03 + A06 (fascial-endocannabinoid) would use deep pressure with sustained holds — which is exactly what MFR (B04) already does. But what about untested combinations?

---

## §8 — CROSS-REFERENCES

### §8.1 — Track A Files Referenced

| File | Sections Referenced | Key Concept Used |
|------|-------------------|-----------------|
| A01 Peripheral Nervous System | §3 Pathways, §4 Therapy Relevance | 5 PNS mechanisms, CT afferents, fiber classification |
| A02 Autonomic Nervous System | §3 Pathways, §4.6-§4.9 | Somatoautonomic reflex, PROKR2 vagal, Zone D Bridge |
| A03 Fascia-Connective Tissue | §1.4, §3, §8 Q8 | Mechanotransduction, CB1/CB2, Gao 2026 verification gap |
| A04 Vascular-Lymphatic | §2-§3, §3.5 | HO-1 pathway, NO at acupoints, Lewis triple response |
| A05 Neuroimmune Interface | §2-§4 | Mast cell, vagal anti-inflammatory, myokines, force-immune |
| A06 Endocrine-Local | §2-§4 | Adenosine, Han opioids, endocannabinoid system-fascia, cutaneous HPA, TRPV1 |
| A07 Dermatome-Somatotopic | §3-§4 | Segmental convergence, Head zones, sclerotome (B10) |
| A08 Muscle-Tendon-Joint | §3-§4 | trigger points, Freeman-Wyke receptors, gamma loop, proprioception |
| A09 Meridian-Examination | §3-§4 | Convergence zones, PROKR2, composite substrate |

### §8.2 — Track B Files Referenced

All 15 Track B files were referenced, primarily:
- **§2 (Stimulation Type):** Physical stimulus classification, parameter ranges, technique variants
- **§5 (Mechanisms):** Mechanism models used to assign activation levels
- **§6 (Body System Pathways):** Primary source for activation profile standardization

Key Track B files for specific patterns:
- B01 + B11: Needle Family Convergence (§4.8)
- B03: Pressure-Dependent Pathway Model (§3.2.1)
- B04: Endocannabinoid System-Fascia Connection, Structural-Neural Dissociation (§4.6)
- B07 + B09: HO-1 Pathway Family (§4.5)
- B08: TRPV1 Convergence Hub, thermal uniqueness (§4.3)
- B10: Velocity parameter, articular-proprioceptive fingerprint (§4.2)
- B12: Therapeutic Scaffolding Cluster (§4.9)
- B15 + B16: Active-Passive Paradigm Shift, composite stimulus (§4.4)

### §8.3 — Track C Dependencies and Connections

- **C01 → C03:** System Dominance Fingerprints (§4.1) feed into mechanism unification. Therapeutic Scaffolding Cluster (§4.9) identified here, full analysis in C03 §3.4.
- **C01 → C04:** Body Region modifier (§3.2.5) flagged for full analysis. Location-dependent vs. location-independent classification (§3.1 notes) provides C04 foundation.
- **C01 → C02:** Stimulus-pathway relationships explain WHY certain therapies work for certain conditions. C02 connects clinical outcomes to mechanism pathways identified here.
- **C01 → C05:** Parameter modifiers (§3.2) are individual variation sources. Endocannabinoid system threshold variation, CT afferent density variation, receptor distribution variation feed C05.

### §8.4 — Human-Predictive-Drive Connection Points

- **Zone D (PFC reach ≈ 0):** Body therapies work IN Zone D. The matrix shows which signal pathways carry information from Zone D to central processing.
- **Direct-State Reward:** CT afferent pathway (§4.7) = direct-state pleasant touch. Pressure-dependent pathway model maps the transition from reward (light/oxytocin) to modulation (deep/endocannabinoid system).
- **Evaluative Gates:** Therapeutic Scaffolding Cluster (§4.9) connects to Evaluative Gates — theory enhances therapeutic context. B12 is the clearest case.
- **Breathing = Zone D Bridge:** Self-Generated Movement A02 PRIMARY (§3.1.10) = the voluntary ANS access mechanism.
- **Gap 2 (Driver Layer):** This entire matrix IS Gap 2 content — mapping how body-side signals travel through specific pathways.

### §8.5 — Citations for NEW Sources

No new primary sources introduced in C01. All citations referenced through Track A/B files where they were originally documented. This is consistent with Track C's role as SYNTHESIS of existing data, not introduction of new research.
