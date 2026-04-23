# Repository Relationship: akwei-nsa-investigation ↔ akwei-nsa-case-files

These two repositories are **companion archives** covering the same investigation — Akwei v. NSA (Civil Action 92-0449, 1992). They are deliberately split by subject matter. A researcher working on either repo should be aware of both.

---

## Division of Labor

| | `akwei-nsa-investigation` (this repo) | `akwei-nsa-case-files` |
|---|---|---|
| **Visibility** | Public | Private |
| **Primary focus** | Defendant verification, court documents, geographic analysis | Physics, institutional history, technology pipeline, clinical documentation |
| **Start here if...** | You want to know who the defendants are and whether the case was real | You want to understand whether the technology is feasible and how the institutional chain works |
| **Epistemic anchor** | `FINDINGS.md` | `LAYER39_EPISTEMIC_AUDIT.md` |
| **Key document** | `00_INDEX.md` — master index of all 38 files | `LAYER28_MASTER_SYNTHESIS.md` — full evidence table across all layers |
| **Defendant verification** | ✅ Primary location | Referenced |
| **Court documents** | ✅ Primary location | Referenced |
| **Patent chain** | Summary in `03_Technology_Patents/` | Full treatment in LAYER1, LAYER41, LAYER47, LAYER48 |
| **Physics / science** | Brief in `DEEP_DIVE_TECHNOLOGY_REPORT.md` | Full treatment across LAYER10–LAYER47 |
| **Institutional history** | Referenced | ✅ Primary location (LAYER23–LAYER26) |
| **Clinical / misdiagnosis pipeline** | Referenced in `34_DIRD26_AUTHENTICATION_AND_MISDIAGNOSIS_PIPELINE.md` | Full treatment in LAYER17, LAYER31, LAYER35 |
| **Havana Syndrome** | Brief | Full treatment in LAYER13, LAYER19, LAYER33–LAYER36 |
| **Tooling** | None | Supermemory semantic search (`supermemory/`) |

---

## Reading Order for New Researchers

**To understand the case in 30 minutes (this repo):**
1. `README.md` — overview and key findings
2. `01_Court_Documents/24_PRIMARY_COURT_DOCUMENTS_AND_HAARP_HEARING.md` — the original 7-page complaint and dismissal
3. `FINDINGS.md` — what the investigation has established

**To understand the technology (case-files repo):**
1. `LAYER39_EPISTEMIC_AUDIT.md` — read this first; it defines what is proven vs. speculative
2. `03_Technology_Patents/00_TECHNOLOGY_CLAIMS_FRAMEWORK.md` — the three-layer argument structure
3. `LAYER47_CONFIRMED_PIPELINE.md` — all seven pipeline components confirmed by civilian science

**To understand the institutional chain:**
1. `LAYER23_PANDORA_RECONSTRUCTION.md` — PANDORA program, WRAIR, Silver Spring
2. `LAYER24_INSTITUTIONAL_CHAIN.md` — WRAIR → INSCOM → DIA → Kit Green
3. `LAYER25_AAWSAP_GREEN_PAPER.md` — DIA DIRD 26 full extraction

---

## Cross-Reference Map

Key findings that appear in both repos:

| Topic | This Repo | Case-Files Repo |
|---|---|---|
| Judge Sporkin conflict of interest | `06_Analysis_Patterns/25_JUDGE_STANLEY_SPORKIN_BACKGROUND_AND_IMPLICATIONS.md` | LAYER40 |
| Robert Kinnecome verification | `02_Defendant_Verification/09_KINNECOME_FAMILY_COMPLETE.md` | LAYER35 (Akwei pattern comparison) |
| Malech patent US3951134 | `03_Technology_Patents/04_FLANAGAN_NEUROPHONE_AND_COUPLING.md` | LAYER1, LAYER47 |
| V2K / Frey effect | `DEEP_DIVE_TECHNOLOGY_REPORT.md` | LAYER23, LAYER41, LAYER47 |
| DIRD 26 (Kit Green) | `34_DIRD26_AUTHENTICATION_AND_MISDIAGNOSIS_PIPELINE.md` | LAYER25 (full extraction) |
| Havana Syndrome device (2024/2026) | `DEEP_DIVE_TECHNOLOGY_REPORT.md` | LAYER13, LAYER47 |
| Master timeline | `MASTER_TIMELINE.md` | `LAYER28_MASTER_SYNTHESIS.md` |

---

## Epistemic Framework (Shared)

Both repos use the same three-layer technology argument structure:

- **Layer 1 — Existence:** Does the technology exist? (patents, declassified programs, peer-reviewed science)
- **Layer 2 — Feasibility:** Could it work as Akwei described in 1992? (physics, engineering, capability gaps)
- **Layer 3 — Deployment:** Was it actually used against Akwei specifically? (the unverified layer)

**Layers 1 and 2 are strongly supported across both repos. Layer 3 remains unverified.**

The canonical epistemic ruling is in `akwei-nsa-case-files/LAYER39_EPISTEMIC_AUDIT.md`. When in doubt about what the investigation has actually proven vs. what it infers, that file is the authority.

---

*Last updated: April 23, 2026*
