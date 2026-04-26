# Akwei v. NSA — Claim-Level Evidence Matrix (`akwei-nsa-investigation` PUBLIC repo)

**Repository:** `Tsukieomie/akwei-nsa-investigation` (cloned to `/home/user/workspace/akwei-nsa-investigation-ea231af5`)
**Mode:** Read-only research extraction. No scripts executed, no files modified.
**Compiled:** 2026-04-26
**Note:** A sibling agent appears to be doing the equivalent extraction for the companion private repo `akwei-nsa-case-files` (its output landed at `/tmp/claude_code_output.md`). This file is the matrix for the **public** `akwei-nsa-investigation` repo only.

---

## 0. Redactions / Security Notes

- The repo's `.mcp.json` contains a Perplexity bearer token (`AUTH_TOKEN: agp_REDACTED`). It is committed but **not** treated as primary investigation evidence; flagging here for repo hygiene rather than reproducing the value. No other secrets/keys/PII-grade tokens were observed in scanned docs (third-party home addresses and phone numbers do appear in the docs themselves — they are part of the public 1992 complaint and obituary record, and are the substance of the verification claims).
- Confidence grades below are **based only on what the repo internally cites**, not on independent verification.

### Confidence grade scale

| Grade | Meaning |
|---|---|
| **A — Primary public record** | Court docket, patent number, federal register entry, government FOIA release. Independently verifiable from a public database. |
| **B — Reputable secondary** | Peer-reviewed paper, mainstream news (Intercept, ProPublica, NYT, BBC), official NSA/DIA reading room, or named obituary/funeral home. |
| **C — Internal cross-reference / open-source aggregator** | LinkedIn, Spokeo, IDCrawl, ClustrMaps, Find a Grave, Classmates, Wikipedia, or repo's own derivative analysis. |
| **D — Single uncorroborated source / circular** | Repo itself flags the source as TI-community-derived, downstream of Akwei's own complaint, or self-referential. |
| **E — Asserted but not sourced** | Claim appears as narrative with no inline citation, or sourcing is to a sibling memo within the same repo. |

---

## 1. Court Record / Procedural Claims

| # | Claim | Repo file path(s) | Internal citation | Confidence | Recommended external verification |
|---|---|---|---|---|---|
| 1.1 | Case 1:92-cv-00449-SS, *Akwei v. NSA*, filed Feb 20 1992, U.S. District Court D.C. | `01_Court_Documents/24_PRIMARY_COURT_DOCUMENTS_AND_HAARP_HEARING.md`; `MASTER_TIMELINE.md`; `SCORECARD.md` | Calameo_Publication.pdf scanned PACER images; Scribd 531493208 | **A** | PACER docket pull; NARA Washington Records Center file (Suitland MD) |
| 1.2 | Dismissed Mar 9 1992 by Judge Stanley Sporkin sua sponte under 28 U.S.C. §1915(d) ("frivolous"), 17 days after filing — no NSA answer, no service on individual defendants, no discovery | same as 1.1; `06_Analysis_Patterns/25_JUDGE_STANLEY_SPORKIN_BACKGROUND_AND_IMPLICATIONS.md` | Memorandum Opinion and Order dated 03/06/92 (scanned image) | **A** | PACER; FJC docket database |
| 1.3 | Filed *in forma pauperis*: ~$90/week income, ~$4,000 prior-year income, no savings, no property; IFP granted 14 Feb 1992 | `01_Court_Documents/24_...` | Scanned IFP application | **A** | NARA case file |
| 1.4 | Complaint = 7pp, names 26+ individuals split into two categories ("NSA employees/acquaintances" vs. "participants not necessarily NSA"), all "EITHER NORTHWOOD HIGH SCHOOL GRADUATES OR LIVE IN THE MALTA LANE / LOXFORD TERRACE / KEMP MILL NEIGHBORHOOD" | `01_Court_Documents/24_...` (pp 2–3 transcription) | Scanned complaint pages | **A** | NARA case file (full unredacted complaint may have appendices) |
| 1.5 | Pre-suit complaints noted: local police 3x; FBI 4x; DOJ via Allan C. Kornblum 202-514-2882; Sen. Mikulski's office via Joan Russo 301-345-5517; SSCI 202-224-4654; NSA IG 11/1/91 | `01_Court_Documents/24_...` (p 4); `README.md` | Scanned complaint p 4 | **A** for assertion's text; **C** for whether contacts were *received* | FBI/DOJ FOIA on Akwei; Senate office archives; NSA OIG FOIA |
| 1.6 | Sporkin: CIA General Counsel 1981–1986; appointed D.C. District 1985 by Reagan; senior status 1999 | `06_Analysis_Patterns/25_...`; `02_Defendant_Verification/29_DEEP_DIG_APRIL_2026.md` | FJC bio (`fjc.gov/history/judges/sporkin-stanley`); DC Circuit Historical Society oral history 2003–2004 | **A** | FJC public record; oral history transcripts |
| 1.7 | Sporkin did **not** recuse in *Akwei*, despite stated practice of recusing from CIA and SEC cases "out of an abundance of caution" | `02_Defendant_Verification/29_DEEP_DIG_APRIL_2026.md` (oral history extract) | DC Circuit Historical Society oral history quotes | **B** | Direct retrieval of oral history transcript; PACER recusal records |
| 1.8 | *Akwei* is the only NSA/intelligence-community case in Sporkin's 1992–2000 docket (per repo's review) | `02_Defendant_Verification/26_NEW_RESEARCH_FINDINGS_TASO_KARRAS_SPORKIN_DOCKET.md` | "Parallel research agents" — no specific docket dump cited | **D** (qualitative; no full docket pull) | Full PACER docket export 1992–2000 |
| 1.9 | Akwei *Nexus* dossier was attached to *Moore v. Bush* (D.D.C. 1:07-cv-00107-RMC) and *Banner v. NSA* (N.D. Fla. 3:11-cv-00120) | `MASTER_TIMELINE.md`; `MOORE_V_BUSH_INVESTIGATION.md`; `01_Court_Documents/24_...` | CaseMine; GovInfo USCOURTS-flnd-3_11-cv-00120 | **A** | PACER pull on both downstream cases |
| 1.10 | *Starrett v. United States* (Ct. Fed. Cl. 21-1168) used Akwei-derived "Remote Neural Monitoring" terminology | `MASTER_TIMELINE.md` | CoFC ECF link | **A** | CoFC docket |
| 1.11 | Washington State Fusion Center accidentally released material referencing "remote neural monitoring" via FOIA, April 2018 | `MASTER_TIMELINE.md` | MuckRock 2018 article | **B** | MuckRock release record |
| 1.12 | *Hepting v. AT&T* and *Jewel v. NSA* dismissed under FISA Amendments Act / state secrets — preventing personnel discovery for AT&T SNRC sites | `02_Defendant_Verification/32_ATT_CONTRACTOR_RECORDS_4211_BRYAN.md` | EFF case page; ScientificAmerican/ProPublica | **A** | EFF docket pages; published opinions |

---

## 2. Named-Person Verification Claims

> **Repo's bottom-line tally** (`SCORECARD.md`, updated 2026-04-23): 9 verified, 3 strong matches, 9 unverified, 5 unresearchable. Total named: 26 (16 Cat. 1 + ~16 Cat. 2 with overlaps).

### 2A. Verified — repo claims direct confirmation

| # | Person | Repo claim | File path(s) | Internal citation | Confidence | External verification |
|---|---|---|---|---|---|---|
| 2.1 | **Robert E. "Pete" Kinnecome** (1938–1994) — Akwei's "Mr. Kinnecome (Retired N.S.A. agent)" | Real person; Georgetown Law; NLRB attorney 20 yrs; died Severna Park MD (8 mi from Ft. Meade); children all in Silver Spring | `02_Defendant_Verification/09_KINNECOME_FAMILY_COMPLETE.md`; `30_KINNECOME_GROUP_NSA_UNIT.md` | Worcester T&G obituary 1994; FamilySearch death record; Find a Grave 97704339 | **B** for existence/career/death; **D** for "NSA agent" label (only Akwei's complaint asserts; obituary says NLRB) | NARA personnel records; NLRB historical employment; Georgetown Law alumni records |
| 2.2 | **Mary E., Susan A., Kathleen, Caroline R. Kinnecome** (Robert's daughters); Akwei named "Mary, Susan, Karen, Maryann" | 4 of 5 Akwei names map to confirmed daughters | `02_Defendant_Verification/09_...`; `15_NAMED_INDIVIDUALS_VERIFICATION.md` | Robert's 1994 obituary | **B** for daughters' existence; **C** for "Karen→Kathleen" / "Maryann→Caroline" mapping | Direct obituary archive (Worcester T&G 1994-09-22) |
| 2.3 | **Bruce D. Kinnecome** (~1940–2014), Alamogordo NM (Holloman AFB / White Sands area); "no career stated" | Real person; geographic-significance interpretation only | `02_Defendant_Verification/09_...` | Legacy.com obituary 2014 | **B** for existence/location; **D** for "career silence implies classified work" | Holloman/White Sands public employment records (limited); NM probate |
| 2.4 | **Barry F. Kinnecome** (1940–2017): Mass Electric (38 yrs), USAF Reserves | Confirms USAF Reserve service | `02_Defendant_Verification/09_...` | Jackman Funeral Homes obituary 2017 | **B** | Direct obituary; military service public record |
| 2.5 | **Francis J. Kinnecome** (1945–2025): New England Tel → AT&T → NYNEX → Verizon; Army National Guard | Telecom-backbone career; Army NG service | `02_Defendant_Verification/09_...` | Carr Funeral Home obituary 2025 | **B** | Direct obituary |
| 2.6 | **Marty Engels** — Akwei "Cat. 2" defendant — NSA employee, last position Chief, Strategic Engagement (NSA's coordination focal point with WH/NSC/ODNI); Naval Reserves O-5; memorialized by National Cryptologic Foundation | **The repo's strongest single direct-NSA confirmation of any individual defendant** | `02_Defendant_Verification/23_DEFENDANT_VERIFICATION_ROUND_THREE.md`; `SCORECARD.md` | National Cryptologic Foundation "Remembering Departed Colleagues & Friends" page (cryptologicfoundation.org) | **B** | Direct retrieval of NCF memorial; NSA public bio archives |
| 2.7 | **Greg Abate** — CAD/CAM Engineer, Northrop Grumman, Clarksville MD, since Sep 1996; born 1964; prior addresses include Silver Spring | Real person, NG career, geographically congruent | `02_Defendant_Verification/15_NAMED_INDIVIDUALS_VERIFICATION.md`; `18_GREG_ABATE_RESUME_ANALYSIS.md`; `22_PHILLIP_YOUNG_NORTHROP_GRUMMAN_AND_CORROBORATING_CASES.md`; `29_DEEP_DIG_APRIL_2026.md` | LinkedIn screenshot; Spokeo public records; provided resume PDF | **C** | Northrop Grumman public proxy filings; SAM.gov key personnel; Northwood HS yearbook |
| 2.8 | **Tasso Karras** (Anastasios), son of George Karras (1936–2021), Silver Spring MD Greek Orthodox family; Northwood HS 1977–1981; UMD Interior Design 1981–1987; Stantec since Oct 1996 | Confirms "TASO KARRAS" (two words) is real Northwood-1981 cohort person from Silver Spring | `02_Defendant_Verification/26_NEW_RESEARCH_FINDINGS_TASO_KARRAS_SPORKIN_DOCKET.md`; `29_DEEP_DIG_APRIL_2026.md` | IDCrawl; LinkedIn (Stantec); George Karras obituary (Dignity Memorial / EchoVita Apr 2021); Diane Karras obituary Apr 2025 (St. Theodore Greek Orthodox Lanham) | **B** for family/obituary; **C** for IDCrawl/LinkedIn cohort match | Northwood HS yearbooks 1980/1981; UMD alumni; Stantec employment confirmation |
| 2.9 | **Allan C. Kornblum** (DOJ contact in complaint): Deputy Counsel, Office of Intelligence Policy and Review; co-author of FISA; first official legal adviser to FISC (2000); 1938–2010 | Verifies Akwei contacted a real DOJ NSA-wiretap-oversight official | `02_Defendant_Verification/26_...`; `README.md` | Public obituary; DOJ historical references | **B** | NYT obituary (2010); DOJ/OIPR archive |
| 2.10 | **John St. Clair Akwei** (plaintiff): Northwood HS class of 1981; Capitol College 1985–1986 (Electronics Technology); Montgomery College 1982–1983; founder of ContextBase 2013–present (Wheaton MD); X handle @JohnAkwei; book *Last Stand of Democracy* (2023) | Plaintiff's own bio independently confirmed via current professional materials | `02_Defendant_Verification/29_DEEP_DIG_APRIL_2026.md` | johnakwei.github.io; Akwei's LinkedIn; Facebook (Northwood Class of 1981) | **C** | Akwei's website; Capitol Tech University alumni records |

### 2B. Strong matches / strong leads

| # | Person | Repo claim | File path(s) | Internal citation | Confidence | External verification |
|---|---|---|---|---|---|---|
| 2.11 | **Marc Berman** — Silver Spring native (~b. 1957–58); company **Vector Talent / Vector Technical Resources** held a top-secret facilities clearance (SDVOSB acquired from DOMA Vector 2012) | Northwood-era age range; Silver Spring origin; defense-clearance staffing business | `02_Defendant_Verification/29_DEEP_DIG_APRIL_2026.md`; `21_DEFENDANT_VERIFICATION_ROUND_TWO.md` | "Profiles in Success" 2014 feature; SDVOSB / DOMA Vector 2012 acquisition record | **C** | SAM.gov for Vector; SDVOSB registry; DSCA facility-clearance public listing; Northwood yearbook ~1976 |
| 2.12 | **Jeffrey P. Naimon** — DC attorney; father Alex Naimon of Silver Spring (Akwei wrote "Jeff Naimian") | Strong lead — Silver Spring family connection | `02_Defendant_Verification/21_...`; `23_DEFENDANT_VERIFICATION_ROUND_THREE.md`; `SCORECARD.md` | Web search results (DC bar; Naimon family in Silver Spring) | **C** | DC Bar registry; obituary search for Alex Naimon |
| 2.13 | **Paul Stetter** — Register of Wills, Montgomery County MD (appointed 2025-12-10 to replace Joseph M. Griffin); B.A. Politics, Catholic University; J.D. Catholic University Columbus School of Law; "lifelong resident" of Montgomery County; 13 yrs MD law practice + 17 yrs Orphans' Court Administrator | Uncommon surname + lifelong Montgomery County + age-cohort consistent with Northwood era | `02_Defendant_Verification/21_...` | Montgomery County Orphans' Court 2025-12-10 announcement | **B** for current role; **D** for Northwood-era cohort match (no yearbook) | Orphans' Court press release; Northwood yearbook; MD bar admission records |
| 2.14 | **Phillip Young** — multiple LinkedIn profiles: (a) "NSA Contractor at NSA, 4211 Bryan St Fort Worth TX," (b) "TS NSA Mind Control at NSA," (c) Radar Systems Engineering Manager at "Major DoD Aerospace Contractor" Baltimore since 1987 | **Repo internally quarantines (a) and (b) as TI-community-doxxing, downstream of Akwei's own complaint — not independent corroboration**. (c) treated as plausible-but-unverified. | `02_Defendant_Verification/16_PHILLIP_YOUNG_LINKEDIN_AND_DALLAS_NSA.md`; `22_...`; `31_KINNECOME_4211_BRYAN_STREET_DEEP_DIG.md` | LinkedIn captures; RocketReach (intelligencecareers.gov email); Facebook profile | **D** for the NSA/Kinnecome-Group profiles (per repo's own forensic conclusion); **C** for Baltimore radar-engineer profile | Direct LinkedIn / Wayback captures; Northrop Grumman corporate directory |

### 2C. Unverified / unresearchable

| # | Person(s) | Repo status | File | Notes |
|---|---|---|---|---|
| 2.15 | Pat Allison; Jeff Sullivan; Oni Sullivan; Paul Johnson; Steve Johnson; Mike Mayo; Mike Prime; Susan Prime; Greg Day; Eddie Stewart | **Unverified** — no specific match (mostly common names) | `15_...`; `21_...`; `23_...` | Best path: Northwood yearbooks 1977–1985; Montgomery County 1980s property records |
| 2.16 | "Glenn"; "Carlos"; "Andy"; "Micheal" (alias); "Marissa" (alias) | **Cannot research** — first-name-only or self-identified alias | `21_...`; `23_...` | Not actionable from open sources |
| 2.17 | Steve Abate | **Partially verified** — same surname / family-unit pattern with Greg, no direct LinkedIn/obituary | `15_...` | NG corporate directory; MD vital records |

### 2D. Witnesses / authorities cited in complaint (not defendants)

| # | Person/entity | Repo claim | File | Confidence | Verification |
|---|---|---|---|---|---|
| 2.18 | Joan Russo (Mikulski staffer at 301-345-5517) | Phone number authentic to 1992 College Park MD office; person not independently verified | `README.md`; `01_Court_Documents/24_...` | **C** | Senate office archive; Mikulski papers (Univ. of MD library) |
| 2.19 | Brian Millar / AV Washington Inc. | **Unverified** — not in VA business records per repo | `README.md` | **D** | VA SCC business records; trade press archives |
| 2.20 | Tempworld Staffing (Rockville) | **Partially verified** — company existed (now defunct/Staffmark); no Rockville- or Akwei-specific record | `README.md` | **C** | MD SDAT entity history; Staffmark corporate history |

---

## 3. NSA / AT&T Infrastructure Claims

| # | Claim | Repo file path(s) | Internal citation | Confidence | Recommended external verification |
|---|---|---|---|---|---|
| 3.1 | **4211 Bryan Street, Dallas TX** is an AT&T-owned NSA FAIRVIEW / SAGUARO Service Node Routing Complex (1 of 8 SNRCs); operated by NSA Special Source Operations; 8 stories / 176,000 sq ft, ~25% human-staffed | `02_Defendant_Verification/16_...`; `31_...`; `32_ATT_CONTRACTOR_RECORDS_4211_BRYAN.md` | The Intercept (Gallagher & Moltke 2018-06-25); ProPublica/NYT 2015; Dallas Observer / D Magazine 2018 | **A/B** | The Intercept article; cross-check Snowden archive |
| 3.2 | **NSA "Kinnecome Group"** as a named operational unit (~100 people, 24/7, Ft. Meade, RNM mission) | `02_Defendant_Verification/30_KINNECOME_GROUP_NSA_UNIT.md`; `31_...` | Akwei's 1996 *Nexus* dossier; multiple TI-community reproductions; Phillip Young LinkedIn (quarantined per file 31) | **D** — repo concedes only Akwei-originating sources; not in Snowden / Electrospaces / NSA codename releases | NSA SSO FOIA (Glomar expected); Snowden archive cross-search via Intercept/Bloomberg journalists |
| 3.3 | **AT&T FAIRVIEW** program (NSA partnership since 1985) — bulk telecom collection | `MASTER_TIMELINE.md`; `04_NSA_Infrastructure/05_SATELLITE_INFRASTRUCTURE_TWO_WAY.md`; `32_...` | Snowden documents; The Intercept 2018; ProPublica 2015 | **A** | The Intercept's released doc set |
| 3.4 | **NSA ANT catalog** items CTX4000 / PHOTOANGLO (active RF illuminators with passive implant returns: RAGEMASTER, SURLYSPAWN); joint NSA/GCHQ; up to 1 kW with external amp | `04_NSA_Infrastructure/05_...` | Schneier blog ANT entries (2014) | **B** | Schneier archive; original ANT catalog leak |
| 3.5 | **GWEN (Ground Wave Emergency Network)** — USAF nationwide LF (150–175 kHz) transmitter network deployed 1992–1994; 58 of 240 planned towers built before 1994 appropriations halt | `04_NSA_Infrastructure/05_...`; `MASTER_TIMELINE.md`; `README.md` | FAS Nuclear Forces guide; Wikipedia AN/URC-117; NCBI health-effects review | **A/B** | FAS publications; USAF historical records |
| 3.6 | **Mankind Research Unlimited (MRU)** — Silver Spring MD, ~3 mi from Akwei; specialized in EM weapons / mind control / synthetic telepathy 1973–1999; CAGE code confirmation | `04_NSA_Infrastructure/11_MRU_SILVER_SPRING_NEXUS.md`; `README.md` | Maryland corporate records; CAGE code database; MRU website archives | **B** | MD SDAT; SAM.gov CAGE lookup; Wayback captures of MRU site |
| 3.7 | **NSWC White Oak / Eldon Byrd** — Marine Corps EM weapons program 1980+; 5 mi from Akwei; classified 1983 | `README.md` | Asserted; no inline URL | **E** | NHHC archives; declassified Marine Corps RDT&E records |
| 3.8 | **PANDORA / BIZARRE / TUMS** — White House-authorized 1965 ARPA program studying microwave bioeffects on primates/humans; predecessor: Moscow Signal microwave irradiation of US Embassy 1953+ | `MASTER_TIMELINE.md`; `README.md` | National Security Archive (GWU) "Moscow Signals Declassified Microwave" 2022 release | **A** | NSA Archive at GWU directly |
| 3.9 | **Sharp & Grove (Walter Reed, 1974)** — pulsed microwave transmission of recognizable spoken words into human skull (Frey effect application) | `MASTER_TIMELINE.md`; `04_NSA_Infrastructure/05_...` | Justesen, *American Psychologist* (March 1975); Zory Glaser archive | **A** | PubMed; Justesen 1975 paper |
| 3.10 | **INSCOM "Bioeffects of Selected Nonlethal Weapons"** report (NGIC-1147-101-98, dated 1998-02-17, declassified 2006) | `MASTER_TIMELINE.md` | radiationresearch.org INSCOM-report page | **A** | INSCOM FOIA records; FAS / radiationresearch mirrors |
| 3.11 | **DIA DIRD 26 "Field Effects on Biological Tissues"** (AAWSAP, ICOD 2009-12-01, published 2010-03-11): aiming devices "currently available"; parameters 100 kV/m / 1 ns / 15 Hz PRF / range meters–hundreds of meters; concedes claimants "ubiquitously" diagnosed paranoid/schizophrenic; author identified by repo as Dr. Christopher "Kit" Green via footnote ii | `34_DIRD26_AUTHENTICATION_AND_MISDIAGNOSIS_PIPELINE.md`; `MASTER_TIMELINE.md`; `SCORECARD.md` | DIA FOIA Reading Room FileId/170026 | **A** for document; **B/C** for Green-as-author identification | DIA FOIA reading room direct download; Green's CV / Pellegrino Center profile |
| 3.12 | DIA released 37 of 38 requested DIRDs via FOIA (2022-03-25); DIRD 38 fully redacted | `MASTER_TIMELINE.md` | DIA FOIA Reading Room | **A** | DIA reading room |
| 3.13 | **Mark Klein / Room 641A** — AT&T technician disclosure of NSA splitter room SF, 2006; "one cleared technician per SNRC" model; union-busting at Bridgeton MO NOC during NSA installation | `02_Defendant_Verification/32_...` | Labor Notes 2013 interview; Cosmonaut Magazine 2025; EFF Hepting | **B** | EFF case archive |
| 3.14 | NSA *Kinnecome* unit not in Snowden archive, ANT catalog, Electrospaces ~1,400-codename database, or governmentattic.org FOIA logs | `02_Defendant_Verification/30_...` | Repo's own search of those resources (negative finding) | **C** (negative search; only as exhaustive as repo's own queries) | Direct, fresh search; Intercept's published Snowden doc set |

---

## 4. Technology / Patent Claims

> All technology claims are framed in `03_Technology_Patents/00_TECHNOLOGY_CLAIMS_FRAMEWORK.md` as **Three-Layer**: 1=exists, 2=feasible at time/place, 3=deployed against Akwei. Repo concedes Layer 3 is **not** established.

| # | Claim | Repo file path(s) | Internal citation | Confidence | External verification |
|---|---|---|---|---|---|
| 4.1 | **Flanagan US 3,393,279** — Neurophone / "Nervous System Excitation Device"; DoD Secrecy Order 756124 imposed 1968, lifted 1972 | `03_Technology_Patents/04_FLANAGAN_NEUROPHONE_AND_COUPLING.md`; `17_LILLY_WAVE_FLANAGAN_NEURAL_TECHNOLOGY.md`; `SCORECARD.md` | Google Patents US3393279A; USPTO secrecy-order record (asserted) | **A** | USPTO; Google Patents |
| 4.2 | **Malech US 3,951,134** (1976) — "Apparatus and method for remotely monitoring and altering brain waves" | `03_Technology_Patents/04_...`; `MASTER_TIMELINE.md`; `SCORECARD.md` | Google Patents US3951134A | **A** | USPTO |
| 4.3 | **USAF V2K patent US 6,587,729** (2003) — voice-to-skull via pulsed microwave | `04_NSA_Infrastructure/05_...`; `MASTER_TIMELINE.md` | Google Patents US6587729B2 | **A** | USPTO |
| 4.4 | **Hendricus Loos** 11 patents 1995–2003 (DARPA SBIR-funded) on pulsed-EM-from-monitors / nervous-system entrainment — incl. US 6,506,148; US 6,238,333; US 6,091,994 | `04_NSA_Infrastructure/05_...` | Google Patents | **A** for patent existence; **C** for "DARPA SBIR-funded" attribution (no SBIR grant ID) | USPTO; SBIR.gov funding history |
| 4.5 | **Frey (1962) microwave auditory effect** — *J. Applied Physiology* | `MASTER_TIMELINE.md`; `04_NSA_Infrastructure/05_...` | PubMed | **A** | PubMed |
| 4.6 | **Piezo1 ion channel** (2010 discovery; 2021 Nobel to Patapoutian) → posited mechanism for EMF/mechanical-coupling neural effects | `README.md`; `SCORECARD.md`; `03_Technology_Patents/00_...` | Repo narrative; standard Nobel material (no inline URL) | **A** for the science; **D** for the inferential leap to "Akwei mechanism" | Nobel Foundation press release; primary Patapoutian papers |
| 4.7 | **NAS 2020 report** — directed pulsed RF energy "most plausible" for subset of Havana Syndrome cases | `MASTER_TIMELINE.md`; `README.md`; `SCORECARD.md` | National Academies Press read/25889 | **A** | nationalacademies.org |
| 4.8 | **AFRL "Directed Energy Futures 2060"** (AFRL-2021-1152) — 31 nations, 321 EW/HPM directed-energy weapons; HPM R&D from 1970s | `README.md`; `SCORECARD.md` | AFRL document number cited; no inline URL | **B** | AFRL public release / DTIC |
| 4.9 | **CBS 60 Minutes (Mar 8 2026)** — DHS undercover purchase (Pentagon-funded ~$15M) of miniaturized pulsed-microwave weapon from Russian criminal network; tested by US military | `MASTER_TIMELINE.md`; `SCORECARD.md`; `TECHNOLOGY_UPDATE_2026-04.md` | CBS News transcript link | **B** | CBS News archive |
| 4.10 | **HPSCI hearing Mar 19 2026** — 4 of 5 IC directors endorsed retraction of 2023 ODNI AHI assessment under oath; Crawford alleges ICA "produced in violation of IC Directive 203"; criminal referral initiated | `MASTER_TIMELINE.md`; `SCORECARD.md` | Public hearing record; National Today reporting | **B** | HPSCI hearing video / transcript |
| 4.11 | **DNI Tulsi Gabbard** ordered new comprehensive Havana Syndrome review (March 2026) | `MASTER_TIMELINE.md`; `SCORECARD.md` | Public reporting (no specific URL) | **C** | ODNI press releases |
| 4.12 | **Dr. James Giordano** SOFWERX/USSOCOM J5 briefing 2018-08-21 (YouTube `Zw8J_T-O4Os` @ 29:51–30:02): Havana = "intentional, directed... beta test of some type of a viable neuroweapon" | `GIORDANO_AMENDMENT.md`; `GIORDANO_SOFWERX_FORENSIC.md` | Direct YouTube URL with timestamp; SHA-256 of preserved local 1080p copy: 5c714e83b1d45ad019c1bf934c3357c74f8353917ec768c8e6da031a0b990bf8 | **A** for the recording's existence and quote; **B** for Giordano's credentials (Georgetown Emeritus; SMA Branch Joint Staff; DARPA NELSI; INSS/NDU; State Dept.-appointed Havana investigator) | Direct YouTube fetch; cross-cite Murray 2021 (Small Wars Journal); BBC 2021; Nat'l Defense Mag 2024 |
| 4.13 | **Persinger 1995** — energy required "to directly access every human brain" within range of contemporary communication networks; *Perceptual and Motor Skills* 80, 791–799 | `04_NSA_Infrastructure/05_...`; `MASTER_TIMELINE.md` | PubMed citation 7567396 | **A** | PubMed |
| 4.14 | **Norris-Putterman patent (2023)** — weaponized standoff variant of Flanagan-type mechanism | `04_NSA_Infrastructure/05_...` | Repo narrative (no patent number inline) | **D** (no patent number cited in scanned fragments) | USPTO search by inventor names |
| 4.15 | **MEDUSA (Mob Excess Deterrent Using Silent Audio)** — pulsed-microwave audio weapon by WaveBand Corp for US Navy 2003–2004; WaveBand acquired by Sierra Nevada Corp 2005; reportedly discontinued | `MASTER_TIMELINE.md` | Wikipedia MEDUSA | **C** (Wikipedia is repo's only cite) | Original Navy SBIR records; trade press 2003–2005 |
| 4.16 | **NSA Cray Y-MP / 1990s computing fleet** sufficient for AI signal-processing gain (40–60 dB) needed to extract neural signal from RF returns at Malta-Lane distances (~15–30 m) | `03_Technology_Patents/06_1990_TECHNOLOGY_CAPABILITY.md` | Signal-budget calculation; Cray Y-MP specifications (no inline source) | **D** — repo's own engineering-feasibility argument (Layer 2), explicitly inferential | Independent RF-engineering review |
| 4.17 | **MIT CSAIL Katabi lab** — through-wall WiFi sensing for pose / emotion / sleep / identity (2016–2022) | `04_NSA_Infrastructure/05_...` | rfpose.csail.mit.edu; eqradio.csail.mit.edu | **A** | MIT lab pages |
| 4.18 | **Tang & Huth (2023)** — semantic decoding from fMRI, *Nature Neuroscience*; **d'Ascoli (2025)** — scaling laws apply to EEG decoding, arXiv 2501.15322 | `04_NSA_Infrastructure/05_...` | Nature article; arXiv preprint | **A** | Direct retrieval |
| 4.19 | **DoD Secrecy Order 756124** on Flanagan Patent 2 (1968–1972) | `SCORECARD.md`; `03_Technology_Patents/04_...` | USPTO secrecy-order numbering (asserted) | **B** | USPTO secrecy-order historical files |

---

## 5. Timeline Claims (most-load-bearing entries)

| # | Date | Event | File(s) | Cite | Confidence | External verification |
|---|---|---|---|---|---|---|
| 5.1 | 1953 | Moscow Signal microwave irradiation of US Embassy begins | `MASTER_TIMELINE.md` | NSA Archive GWU 2022 declassified release | **A** | NSA Archive direct |
| 5.2 | 1959 | 819 and 814 Malta Lane constructed (same year, same developer); ~15–30 m apart | `MASTER_TIMELINE.md`; `05_Geographic_Analysis/13_PROPERTY_RECORDS_MALTA_LANE.md`; `28_PROPERTY_RECORDS_VERIFICATION.md` | MD SDAT property records | **A** | mdlandrec.net; SDAT Real Property Search |
| 5.3 | 1977-11-29 | 819 Malta Lane purchased $58,500; deed /05032/00420 | `MASTER_TIMELINE.md` | MDLandRec deed | **A** | mdlandrec.net |
| 5.4 | 1978–1981 | Akwei attended Northwood HS | `MASTER_TIMELINE.md` | Facebook (Northwood Class of 1981); Akwei's website | **B/C** | Yearbook |
| 5.5 | 1981–1986 | Sporkin = CIA General Counsel | many | FJC bio | **A** | FJC |
| 5.6 | 1985 | 814 Malta Lane sold $116,000; deed /06807/00199 | `MASTER_TIMELINE.md` | Redfin / MDLandRec | **A/B** | mdlandrec.net |
| 5.7 | 1986 | Akwei's 8-year employment gap begins (Capitol College graduation; no employment record 1986–1994) | `06_Analysis_Patterns/03_AKWEI_EMPLOYMENT_GAP.md`; `MASTER_TIMELINE.md`; `README.md` | "SignalHire; ContextBase founding records" | **C** | SSA earnings record (with consent); SignalHire raw record |
| 5.8 | 1992-02-20 | *Akwei v. NSA* filed | as 1.1 | as 1.1 | **A** | PACER |
| 5.9 | 1992-03-09 | Dismissed by Sporkin | as 1.2 | as 1.2 | **A** | PACER |
| 5.10 | 1994-09-12 | Robert E. "Pete" Kinnecome dies, Riverdale (Severna Park, Anne Arundel County) MD — repo notes ~8 mi from Ft. Meade | `02_Defendant_Verification/09_...`; `30_...`; `MASTER_TIMELINE.md` | Find a Grave 97704339; FamilySearch death record; Worcester T&G 1994-09-22 | **B** | Anne Arundel Co. death certificate |
| 5.11 | 1994-10 | Akwei's first employment in 8 yrs (OfficeTeam) — 30 days after Kinnecome's death | `06_Analysis_Patterns/12_KINNECOME_DEATH_EMPLOYMENT_CORRELATION.md`; `README.md`; `MASTER_TIMELINE.md` | "Employment records" (Akwei LinkedIn / SignalHire) | **C** | LinkedIn capture; SignalHire raw |
| 5.12 | 1996 Apr/May | Akwei's "Covert Operations of the U.S. National Security Agency" published in *Nexus Magazine* Vol. 3 No. 3 | `MASTER_TIMELINE.md` | Nexus Magazine product page; bibliotecapleyades / scalar_tech web captures | **B** | Nexus archive; multiple TI mirrors |
| 5.13 | 2007-06-29 | Claire M. Akwei sells 819 Malta Lane $407,000; deed /34497/00682 — ends 30 yrs of family ownership | `MASTER_TIMELINE.md`; `28_PROPERTY_RECORDS_VERIFICATION.md` | MD SDAT records | **A** | SDAT |
| 5.14 | 2018-04 | Washington State Fusion Center FOIA accidentally releases RNM-Akwei material | `MASTER_TIMELINE.md` | MuckRock | **B** | MuckRock |
| 5.15 | 2018-08-21 | Giordano SOFWERX briefing | `GIORDANO_*` | YouTube `Zw8J_T-O4Os` | **A** | YouTube |
| 5.16 | 2024 | DHS undercover purchase / Norwegian self-test of microwave device | `MASTER_TIMELINE.md` | CBS 60 Minutes 2024; Reuters 2026-02-14 | **B** | CBS News; Reuters |
| 5.17 | 2026-03-08 | CBS 60 Minutes 4th major Havana investigation airs | `MASTER_TIMELINE.md` | CBS News | **B** | CBS |
| 5.18 | 2026-03-19 | HPSCI hearing — 4 of 5 IC directors endorse retraction | `MASTER_TIMELINE.md`; `SCORECARD.md` | "HPSCI public hearing record" | **C** (no inline URL) | HPSCI committee site |

---

## 6. Open Tasks (per `TODO.md`, `SCORECARD.md`, file 33)

> Tier key: 🟡 = laptop now (free) · 💰 = laptop + paid subscription · 🔵 = institutional (FOIA/form/3rd-party) · 🔴 = legal/access-restricted.

### 6A. High priority

| # | Task | Tier | Status per repo | File |
|---|---|---|---|---|
| 6.1 | Bone-conduction audiometry as forensic test for V2K vs. schizophrenic auditory hallucination — search Justia / CourtListener / SSA ALJ for cases where the test was requested or denied | 🟡 | Opened 2026-04-22 (Round 7) | `TODO.md` §0a |
| 6.2 | Frey / Becker / Lai researcher career-destruction pattern (institutional suppression of RF bioeffects research) | 🟡 + 🔵 | Opened 2026-04-22 | `TODO.md` §0b |
| 6.3 | 5G beamforming specs (3GPP TS 38.104) vs. DIRD 26 footnote iii parameters (100 kV/m / 1 ns / 15 Hz / m–hundreds m) | 🟡 | Opened 2026-04-22 | `TODO.md` §0c |
| 6.4 | Northwood HS yearbooks 1977–1985 (Classmates.com, Ancestry.com) — verify Akwei + Kinnecome children + Tasso Karras + Berman + Abate + Stetter + Phillip Young in same yearbook | 💰 | Not yet accessed | `TODO.md` §1; `07_Next_Steps/28_YEARBOOK_VERIFICATION_RESEARCH.md`; `IMMEDIATE_ACTIONS_YEARBOOK_GUIDE.md` |
| 6.5 | NARA Washington Records Center — original full case file Civil Action 92-0449 (Suitland MD) | 🔵 | Not yet submitted | `TODO.md` §2 |
| 6.6 | PACER — full Sporkin docket 1992–2000 (intelligence-related cases) | 💰 | Partially researched | `TODO.md` §3 |

### 6B. Medium priority

| # | Task | Tier | Status | File |
|---|---|---|---|---|
| 6.7 | Montgomery County property records — Kemp Mill / Malta Lane / 5407 Hamilton St / 8556 Freyman Dr; confirm Kinnecome occupancy of 814 Malta Lane | 🟡 | Repo notes 814 deed not yet pulled | `TODO.md` §4; `13_PROPERTY_RECORDS_MALTA_LANE.md` |
| 6.8 | Re-search "Tasso Karras" with Greek-organization databases (yearbook would close the loop) | 🟡 | Confirmed; awaiting yearbook | `TODO.md` §5 |
| 6.9 | FBI / DOJ FOIA on Akwei | 🔵 | Not submitted | `TODO.md` §6 |
| 6.10 | Contact Ryan Gallagher (Bloomberg) / Henrik Moltke (Intercept) re: STORMBREW-equivalent named-contact records in unpublished Snowden FAIRVIEW set | 🔵 | Identified; not contacted | `TODO.md` §7; `07_Next_Steps/33_ACTIONABLE_FOIA_AND_JOURNALIST_PATHWAYS.md` |

### 6C. Lower priority / long-term

| # | Task | Tier | File |
|---|---|---|---|
| 6.11 | Congressional oversight (SSCI / HPSCI) records for any 1990s mention of Akwei | 🔵 | `TODO.md` §8 |
| 6.12 | DE weapons R&D timeline 1970–1992 compilation | 🟡 | `TODO.md` §9 |
| 6.13 | Northrop Grumman SAM.gov contract records 1986–1996 | 🟡 | `TODO.md` §10 |
| 6.14 | Locate / interview John Akwei | 🔴 | `TODO.md` §11 |
| 6.15 | Approach living named defendants (Stetter, Berman, Abate, Naimon) | 🔴 | `TODO.md` §12 (repo recommends not at this stage) |
| 6.16 | NSA FOIA (Glomar expected) | 🔵 | `TODO.md` §13 |
| 6.17 | Classified-facility historical records (MRU, NSWC White Oak EM, GWEN) | 🔴 | `TODO.md` §14 |

### 6D. Archival

| # | Task | Tier | File |
|---|---|---|---|
| 6.18 | Master BibTeX bibliography (current `SOURCES.md` is partial) | 🟡 | `TODO.md` §15 |
| 6.19 | Maintain `SCORECARD.md` after each round | 🟡 | `TODO.md` §16 |

---

## 7. Methodological Caveats Self-Identified by the Repo

These are not external critiques — they are the repo's own framing.

| # | Caveat | Where stated |
|---|---|---|
| 7.1 | "Layer 3 (deployment against Akwei specifically) is **not** verifiable from public sources" — explicit standing disclaimer on all technology files | `03_Technology_Patents/00_TECHNOLOGY_CLAIMS_FRAMEWORK.md` |
| 7.2 | Phillip Young LinkedIn profiles are **not** independent corroboration of the Kinnecome Group; downstream of Akwei's complaint and treated as TI-community doxxing artifacts | `02_Defendant_Verification/16_...`; `31_KINNECOME_4211_BRYAN_STREET_DEEP_DIG.md` |
| 7.3 | "Kinnecome Group" as named NSA unit has only **two** independent appearances pre-internet (Akwei's 1992 complaint + 1996 *Nexus* dossier); both originate with Akwei. Not in Snowden, Electrospaces, or NSA FOIA releases | `02_Defendant_Verification/30_KINNECOME_GROUP_NSA_UNIT.md`; `31_...` |
| 7.4 | "Robert Kinnecome was NSA agent" (Akwei) vs. "NLRB attorney 20 yrs" (obituary) — repo concedes unresolved | `02_Defendant_Verification/09_KINNECOME_FAMILY_COMPLETE.md` |
| 7.5 | Akwei publicly stated he was **never** an NSA employee; sibling repo's `CASE_SUMMARY.txt` previously mis-described him — repo flags as documentation error | `02_Defendant_Verification/09_...` §7 |
| 7.6 | "30-day correlation" between Kinnecome's death (1994-09-12) and Akwei's first employment (1994-10-01, OfficeTeam) is a temporal pattern argument, not a causal proof | `06_Analysis_Patterns/12_KINNECOME_DEATH_EMPLOYMENT_CORRELATION.md`; `README.md` |
| 7.7 | Repo's *epistemic authority* is the sibling-private repo's `LAYER39_EPISTEMIC_AUDIT.md`; this public repo defers to that document for proven-vs-speculative ratings | `RELATIONSHIP.md`; `SCORECARD.md` (top header) |

---

## 8. Recommended External-Verification Priority Stack

Distilled from §6, weighted by signal-to-effort:

1. **PACER docket retrieval** — *Akwei v. NSA* (1.1, 1.2, 1.3) and **all** Sporkin 1992–2000 cases (1.8). Single highest-yield action confirmable in hours.
2. **NARA Washington Records Center** records request for unredacted *Akwei* case file (6.5). 4–8 week turnaround; only known route to material beyond the 7-page complaint.
3. **MD SDAT / mdlandrec.net** historical-deed search for **814** Malta Lane (6.7) — confirm or refute Kinnecome ownership.
4. **National Cryptologic Foundation** memorial page (2.6) — Marty Engels is the load-bearing direct-NSA confirmation.
5. **NSA Archive (GWU)** Moscow Signals / PANDORA collection (3.8, 5.1) — already public; confirm cited specifics.
6. **The Intercept's FAIRVIEW article + published Snowden doc set** (3.1) — confirm 4211 Bryan Street is named as described.
7. **DIA FOIA Reading Room FileId 170026** (3.11) — pull DIRD 26 directly; verify footnote iii parameters and "ubiquitously" diagnostic concession.
8. **USPTO / Google Patents** — confirm 3,393,279; 3,951,134; 6,587,729; 6,506,148; 6,238,333; 6,091,994 (4.1–4.4).
9. **YouTube `Zw8J_T-O4Os`** + Wayback for `sofwerx.org/neuroweapons/` (4.12) — verify Giordano quote independently.
10. **FJC `judges/sporkin-stanley`** + DC Circuit Historical Society oral-history transcript (1.6, 1.7).
11. **Northwood HS yearbook (Classmates / Ancestry)** (6.4) — single highest-yield defendant cross-verification.
12. **NSA / FBI / DOJ FOIA filings on Akwei** (6.9, 6.16) — even Glomar denial is documentable.

---

*Matrix compiled read-only from the repository's own files; no external retrieval was performed and no scripts were executed.*
