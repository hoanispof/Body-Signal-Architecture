# Plan — Abbreviation Fix (Acupoint Atlas)

**Version:** 1.0
**Date:** 2026-08-24
**Status:** COMPLETE (2026-08-24, single session)
**Prerequisite:** Abbreviation sweep complete (4 agents, 22 content files,
2026-08-23). Cross-verified with targeted grep.

---

## §1 — Overview

**Mục tiêu:** Fix toàn bộ viết tắt tự tạo / không chuẩn trong Acupoint Atlas
project, đảm bảo framework đạt chất lượng đồng bộ cao nhất.

**Convention rule:** AP-00-Core line 452: "No abbreviations of framework
concepts." Framework-wide: "hạn chế tối đa tự tạo viết tắt mới."

**Scope:** ~413 content fixes across 16 files + ~91 plan file fixes.
Grand total: ~504 fixes.

**Method:** Grep-verified counts (not agent estimates). Each session reads
target file, verifies context, applies fixes, checks collateral.

**Principle:** Chậm mà chắc. Quality over speed. One session at a time.

---

## §2 — Abbreviation Replacement Map

### 2.1 — Project-Coined (MUST FIX)

| # | Abbreviation | → Replacement | Count | Rationale |
|---|---|---|---|---|
| 1 | WoH | Window of Heaven | 118+33 | Project-coined. Not in TCM literature |
| 2 | SA | scalp acupuncture | 22+3 | Conflicts SA I/SA II (A01). Already fixed in Phase 5 BSA files |
| 3 | MSSA | motion-style scalp acupuncture | 27+2 | Contains SA. Semi-standard in papers but expand for consistency |
| 4 | MSA / Foot MSA | Motor-Sensory Area / Foot Motor-Sensory Area | 18+5 | Project shorthand for Jiao's zones. Conflicts Multiple System Atrophy |
| 5 | GAN | great auricular nerve | 14+6 | Not standard anatomical abbreviation |
| 6 | APA | auricular point acupressure | 11 | Project shorthand |
| 7 | EV | Extraordinary Vessel(s) | 15+6 | Not standard TCM abbreviation |
| 8 | AMS | [full name from context] | 6 | Unique to Bo's system |
| 9 | KE SUBJECT | Ke-cycle subject | 17 total | All-caps makes romanization look like abbreviation |
| 10 | KE CONTROLLER | Ke-cycle controller | (incl above) | Same as above |

### 2.2 — Undefined (MUST FIX)

| # | Abbreviation | → Fix | Count | File |
|---|---|---|---|---|
| 11 | BAA | Expand to full name from context | 1 | AP-18 |
| 12 | AAS | Determine + expand from context | 1 | AP-16 |
| 13 | LSTS | Determine + expand from source paper | 1 | AP-12 |
| 14 | NV | neurovascular | 1 | AP-14 |
| 15 | DD | Add formal "(DD)" definition after "Dangerous depth" | 1 | AP-13 |
| 16 | AA | auricular acupuncture | 1 | AP-16 |

### 2.3 — Consistency Fixes (FIX)

| # | Abbreviation | → Replacement | Count | Rationale |
|---|---|---|---|---|
| 17 | WAA | Wrist-Ankle Acupuncture | 48+9 | Already fixed in Phase 5 BSA files. Expand in Atlas files for consistency |
| 18 | KHT | Korean Hand Therapy | 35+14 | Same as above |
| 19 | SJ | TE (in meridian/acupoint codes) | 72+13 | Project standard is TE. File named AP-10-Triple-Burner-**TE** |

### 2.4 — Define-on-First-Use (MINOR FIX)

| # | Abbreviation | → Fix | Count | File |
|---|---|---|---|---|
| 20 | EFT | Add "(Emotional Freedom Techniques)" on first use (line ~695) | 1 | AP-06 |
| 21 | PSD | Expand to "post-stroke depression" where not defined | 1 | AP-18 |
| 22 | MSK | Expand to "musculoskeletal" or define on first use | 3 | AP-10 |
| 23 | LBP | Verify defined on first use; expand if not | TBD | AP-16 |

---

## §3 — File × Abbreviation Matrix (Content Files, Grep-Verified)

| File | WoH | SJ | WAA | KHT | MSSA | SA | MSA | KE | GAN | EV | APA | AMS | Other | Total |
|------|-----|----|----|-----|------|----|-----|----|-----|----|-----|-----|-------|-------|
| AP-00 | — | — | — | 1 | — | — | — | — | — | — | — | — | — | 1 |
| AP-01 | — | — | — | — | — | — | — | 3 | — | — | — | — | — | 3 |
| AP-02 | 12 | — | — | — | — | — | — | 4 | — | — | — | — | — | 16 |
| AP-03 | 12 | — | — | — | — | — | — | — | — | — | — | — | — | 12 |
| AP-06 | 27 | — | — | — | — | — | — | 6 | — | — | — | — | EFT↑1 | 34 |
| AP-07 | 9 | 57 | — | — | — | — | — | — | — | 12 | — | — | — | 78 |
| AP-08 | — | 4 | — | — | — | — | — | — | — | — | — | — | — | 4 |
| AP-10 | 37 | — | 4 | — | — | — | — | 4 | — | — | — | — | MSK3 | 48 |
| AP-12 | — | — | — | — | — | — | — | — | — | — | — | — | LSTS1 | 1 |
| AP-13 | — | — | — | — | — | — | — | — | — | — | — | — | DD1 | 1 |
| AP-14 | 21 | 10 | — | — | — | — | — | — | — | 2 | — | — | NV1 | 34 |
| AP-16 | — | — | — | — | — | — | — | — | 14 | — | 11 | — | AAS1,AA1 | 27 |
| AP-17 | — | — | — | — | 17 | 17 | 18 | — | — | — | — | — | — | 52 |
| AP-18 | — | — | 33 | 23 | — | — | — | — | — | — | — | 6 | BAA1,PSD1 | 64 |
| AP-Mech | — | — | 10 | 9 | 10 | 5 | — | — | — | — | — | — | — | 34 |
| AP-Cross | — | 1 | 1 | 2 | — | — | — | — | — | 1 | — | — | — | 5 |
| **Total** | **118** | **72** | **48** | **35** | **27** | **22** | **18** | **17** | **14** | **15** | **11** | **6** | **10** | **413** |

**Clean content files (no fixes needed):** AP-04, AP-05, AP-09, AP-11,
AP-15, AP-Core-Framework-Impact

---

## §4 — Execution Sessions

### Session 1: AP-07-Bladder-BL (78 fixes)
**File:** AP-07-Bladder-BL.md (~13,000 lines)
**Fixes:**
- SJ → TE: 57 occurrences. CAUTION: check context for each.
  - In acupoint codes (SJ5, SJ17): SJ → TE mechanically
  - In "SJ channel/meridian": → "TE channel/meridian"
  - In organ reference "San Jiao": keep as-is (full Chinese name, not abbreviation)
- EV → Extraordinary Vessel(s): 12 occurrences
- WoH → Window of Heaven: 9 occurrences
**Special:** SJ is most context-sensitive. Read each occurrence before replacing.

### Session 2: AP-18-Other-Microsystems (64 fixes)
**File:** AP-18-Other-Microsystems.md
**Fixes:**
- WAA → Wrist-Ankle Acupuncture: 33. Can use replace_all after verifying
  no false positives
- KHT → Korean Hand Therapy: 23. Same approach
- AMS → [full name from context]: 6. Read context to determine expansion
- BAA → [expand from context]: 1. Read context
- PSD → post-stroke depression: 1. Single inline expansion
**Special:** WAA and KHT are header-level terms in this file (section
headings start with "Wrist-Ankle Acupuncture (WAA)"). After replacing,
remove the "(WAA)" parenthetical from first-use definitions.

### Session 3: AP-17-Scalp (52 fixes)
**File:** AP-17-Scalp.md
**Fixes:**
- MSSA → motion-style scalp acupuncture: 17. Replace BEFORE SA.
- SA → scalp acupuncture: 17. Replace AFTER MSSA to avoid collision.
  CAUTION: check each — "SA" may appear in compounds like "SA-alone",
  "static SA", "(SA)". Ensure no false positives (SA I/SA II, other uses).
- MSA → Motor-Sensory Area: 18. Check for "Foot MSA" → "Foot Motor-Sensory
  Area". Check for compound forms.
**Special:** Replacement ORDER matters: MSSA first, then SA, then MSA.

### Session 4: AP-10-Triple-Burner-TE (48 fixes)
**File:** AP-10-Triple-Burner-TE.md (~5,900 lines)
**Fixes:**
- WoH → Window of Heaven: 37. Largest WoH count. Can use replace_all
- WAA → Wrist-Ankle Acupuncture: 4
- KE SUBJECT → Ke-cycle subject: ~2
- KE CONTROLLER → Ke-cycle controller: ~2
- MSK → musculoskeletal: 3 (define-on-first-use or expand)
**Special:** WoH appears heavily in TE6 and TE16/TE17 entries.

### Session 5: AP-14-Conception-CV (34 fixes)
**File:** AP-14-Conception-CV.md
**Fixes:**
- WoH → Window of Heaven: 21. Dense in CV22 entry (lines 4603-5028)
- SJ → TE: 10. Same context rules as Session 1
- EV → Extraordinary Vessel(s): 2
- NV → neurovascular: 1
**Special:** WoH appears in headings, labels, summaries within CV22.
Preserve formatting.

### Session 6: AP-06-Small-Intestine-SI + AP-Mechanism-Summary (67 fixes)
**Files:**
- AP-06-Small-Intestine-SI.md: WoH(27) + KE(6) + EFT↑(1) = 34
- AP-Mechanism-Summary.md: WAA(10) + KHT(9) + MSSA(10) + SA(5) = 34
**Fixes:**
- AP-06: WoH → Window of Heaven (27), KE SUBJECT/CONTROLLER → Ke-cycle
  subject/controller (6), EFT define-on-first-use (1)
- AP-Mech: WAA → Wrist-Ankle Acupuncture (10), KHT → Korean Hand Therapy (9),
  MSSA → motion-style scalp acupuncture (10), SA → scalp acupuncture (5)
**Special:** AP-Mech replacement ORDER: MSSA first, then SA.

### Session 7: AP-16-Auricular (27 fixes)
**File:** AP-16-Auricular.md
**Fixes:**
- GAN → great auricular nerve: 14
- APA → auricular point acupressure: 11
- AAS → [determine from context + expand]: 1
- AA → auricular acupuncture: 1
- LBP → verify defined on first use: TBD
**Special:** GAN is used frequently in nerve pathway descriptions.
Verify no false positive (GAN as part of another term).

### Session 8: Small Files Batch (36 fixes)
**Files and fixes:**
- AP-02 (16): WoH→Window of Heaven (12), KE→Ke-cycle (4)
- AP-03 (12): WoH→Window of Heaven (12)
- AP-01 (3): KE SUBJECT/CONTROLLER→Ke-cycle subject/controller (3)
- AP-08 (4): SJ→TE (4)
- AP-Cross-Tradition (5): WAA(1), KHT(2), SJ(1), EV(1)
- AP-00-Core (1): KHT (1) — check if glossary entry; if so, update to
  reflect full name is preferred
- AP-12 (1): LSTS→[determine + expand from context]
- AP-13 (1): DD→add formal "(DD)" after "Dangerous depth"

### Session 9: Plan Files (~91 fixes)
**All plan.md files in subdirectories.**
Same replacement rules as content files. Mechanical replace_all for
most abbreviations. Key plan files:
- AP-10/plan.md: WoH (6)
- AP-14/plan.md: WoH (9), SJ (3), EV (2)
- AP-18/plan.md: WAA (7), KHT (9)
- AP-07/plan.md: SJ (8), WoH (2), EV (2)
- AP-06/plan.md: WoH (7)
- master plan.md: WoH (3), KHT (4), WAA (1), EV (1), GAN (1)
- Others as found by grep

### Session 10: Verification Sweep
- Grep each abbreviation across ALL Acupoint Atlas files
- Confirm zero remaining occurrences
- Verify no collateral damage (broken references, formatting issues)
- Update master plan status
- Update memory

---

## §5 — Special Handling Notes

### 5.1 — SJ → TE Context Rules
SJ may appear in 3 contexts:
1. **Acupoint codes** (SJ5, SJ17): → TE5, TE17 (mechanical)
2. **Meridian reference** ("SJ channel", "SJ meridian"): → "TE channel",
   "TE meridian"
3. **Organ name** ("San Jiao" written as "SJ"): → "San Jiao" (full
   Chinese name) or "Triple Burner"
4. **In cross-references** ("AP-06-Small-Intestine-SI"): DO NOT change.
   "SI" ≠ "SJ"

Read each SJ occurrence in context before replacing.

### 5.2 — SA/MSSA Replacement Order
In files with both SA and MSSA:
1. Replace MSSA → "motion-style scalp acupuncture" FIRST
2. Then replace SA → "scalp acupuncture"

This prevents "MSSA" from being partially matched by SA replacement.
Edit tool's replace_all uses exact string matching, so "MSSA" won't
match "SA" — but replace MSSA first as a safety measure.

### 5.3 — WoH in Headers and Labels
WoH appears in various formats:
- "WoH point" → "Window of Heaven point"
- "WoH ring" → "Window of Heaven ring"
- "WoH inventory" → "Window of Heaven inventory"
- "FINAL WoH POINT" → "FINAL Window of Heaven POINT"
- "WoH architectural pattern" → "Window of Heaven architectural pattern"

Use replace_all for "WoH" → "Window of Heaven" — should work for all
patterns since WoH is always followed by a space or punctuation.

### 5.4 — WAA/KHT Section Headings
In AP-18, WAA and KHT appear in section definitions like:
```
## Wrist-Ankle Acupuncture (WAA) — 腕踝针
## Korean Hand Therapy (KHT) — 고려수지침
```
After replacing all "WAA" → "Wrist-Ankle Acupuncture", these become:
```
## Wrist-Ankle Acupuncture (Wrist-Ankle Acupuncture) — 腕踝针
```
FIX: After replace_all, manually remove the now-redundant parenthetical
definitions. Search for "(Wrist-Ankle Acupuncture)" and
"(Korean Hand Therapy)" and remove them.

### 5.5 — KE Capitalization
"KE SUBJECT" and "KE CONTROLLER" use ALL CAPS.
Replacement: "Ke-cycle subject" and "Ke-cycle controller" (title case
for Ke, lowercase for rest).
Note: Some files may use "KE" in other Five Element contexts. Grep
pattern was `KE (SUBJECT|CONTROLLER)` — verify no bare "KE" that also
needs fixing.

### 5.6 — AP-00-Core KHT
AP-00-Core may list KHT as a defined abbreviation in a glossary or
conventions section. After replacing KHT everywhere else, update AP-00
to either:
- Remove KHT from the abbreviation list, or
- Note that full name "Korean Hand Therapy" is preferred

---

## §6 — Edit Conventions

1. **Read first:** Read target sections before editing. Verify exact text.
2. **replace_all for mechanical fixes:** WoH, WAA, KHT, GAN can safely
   use replace_all (unique strings, no ambiguity).
3. **Context-check for ambiguous:** SJ, SA, MSA, KE — read each
   occurrence before replacing.
4. **Verify after each file:** Quick grep to confirm zero remaining.
5. **Check collateral:** Ensure no broken formatting, table alignment,
   or cross-references.
6. **English files only:** Vietnamese translations are separate project.
7. **Preserve existing formatting:** Match file's style.

---

## §7 — Status Tracking

| Session | Scope | Fixes | Status |
|---------|-------|-------|--------|
| 1 | AP-07 (SJ+EV+WoH) | 78 | **COMPLETE** (2026-08-24) |
| 2 | AP-18 (WAA+KHT+AMS+BAA+PSD) | 64 | **COMPLETE** (2026-08-24) |
| 3 | AP-17 (SA+MSSA+MSA) | 52 | **COMPLETE** (2026-08-24) |
| 4 | AP-10 (WoH+WAA+KE+MSK) | 48 | **COMPLETE** (2026-08-24) |
| 5 | AP-14 (WoH+SJ+EV+NV) | 34 | **COMPLETE** (2026-08-24) |
| 6 | AP-06 + AP-Mechanism-Summary | 67 | **COMPLETE** (2026-08-24) |
| 7 | AP-16 (GAN+APA+AAS+AA) | 27 | **COMPLETE** (2026-08-24) |
| 8 | Small files batch (7 files) | 36 | **COMPLETE** (2026-08-24) |
| 9 | Plan files | ~91 | **COMPLETE** (2026-08-24) |
| 10 | Verification sweep | — | **COMPLETE** (2026-08-24) |

**Estimated total: ~497 fixes across 16 content files + plan files.**
