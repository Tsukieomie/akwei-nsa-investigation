# D-Wave Quantum Inc. (NYSE: QBTS) — Institutional Research Briefing
**Prepared:** April 2026 | **Classification:** Public | **Analyst:** Computer Research Assistant

---

## EXECUTIVE SUMMARY

D-Wave Quantum Inc. (NYSE: QBTS) is the world's longest-operating commercial quantum computing company, founded in 1999 and headquartered in Burnaby, British Columbia, with US operations in Palo Alto, California. The company pioneered quantum annealing — a specialized, physics-based approach to combinatorial optimization — and in August 2022 completed a SPAC merger with DPCM Capital to list on the New York Stock Exchange. As of early 2026, D-Wave is executing a pivotal strategic transition: from a single-platform annealing vendor into a dual-platform quantum computing company following its $550 million acquisition of gate-model developer Quantum Circuits Inc. (QCI), completed January 20, 2026.

**Financial inflection:** D-Wave reported fiscal year 2025 revenue of $24.6 million, a 179% year-over-year increase from $8.8 million in FY 2024, driven by on-premises system sales, a growing cloud access bookings backlog, and expanded government engagements. Gross margin improved to 82.6%. Cash and marketable securities stood at $884.5 million at December 31, 2025 — a 397% increase from the prior year — providing substantial runway. The company remained unprofitable, with an adjusted net loss of $58.5 million. Market capitalization peaked near $9.2 billion in late 2025 and hovered around $5.5–7.7 billion in early 2026.

**Defense pivot:** D-Wave has materially accelerated its engagement with the US defense and intelligence communities. It achieved "Awardable" status on the DoD CDAO Tradewinds marketplace (October 2024), deployed an Advantage2 system at defense contractor Davidson Technologies in Huntsville, Alabama (November 2025), formed a dedicated US Government Business Unit led by Jack Sears Jr. (December 2025), and announced a three-way collaboration with Anduril Industries and Davidson Technologies on air and missile defense optimization (January 2026). The CIA-affiliated venture fund In-Q-Tel participated in a $30 million D-Wave funding round in 2012. D-Wave has also collaborated with Australia's Department of Defence on last-mile resupply optimization (April 2021).

**Technology claims and debate:** D-Wave's March 2025 peer-reviewed paper in *Science* — "Beyond-Classical Computation in Quantum Simulation" — claims quantum computational supremacy on magnetic spin-glass simulation, outperforming the Frontier exascale supercomputer by approximately one million years of equivalent computation time. This claim has been challenged by independent researchers at the Flatiron Institute and EPFL, who demonstrated that classical algorithms can match or exceed D-Wave's results on subsets of the tested problems. D-Wave is not included in DARPA's Quantum Benchmarking Initiative Stage B cohort (November 2025), which selected eleven gate-model and other approaches; quantum annealing is generally considered outside scope for that program's utility-scale fault-tolerant goals.

**Key risks:** D-Wave's annealing technology is limited to optimization-class problems and cannot run universal quantum algorithms (Grover, Shor). The quantum speedup debate remains unresolved relative to best-in-class classical solvers. The QCI acquisition represents a strategic bet on a gate-model technology that remains pre-commercial. Short-sellers (notably Kerrisdale Capital, April 2025) have questioned the company's valuation and the commercial viability of its hybrid offerings. The dual-platform strategy carries significant execution risk.

---

## SECTION 1: COMPANY PROFILE AND 2026 STATUS

### 1.1 Founding and Origins

D-Wave Systems was incorporated in April 1999 as a spinout from the University of British Columbia, founded by [Haig Farris, Geordie Rose, Bob Wiens, and Alexandre Zagoskin](https://en.wikipedia.org/wiki/D-Wave_Systems). The company originated from conversations among UBC students and faculty on the application of condensed matter physics — specifically superconducting flux qubits — to computational optimization. Early capital came from Canadian and German government sources and angel investors, with venture capital following from Draper Fisher Jurvetson; by 2005, D-Wave had raised approximately CAD $22 million ([MIT Technology Review](https://www.technologyreview.com/2005/07/01/230661/quantum-calculation/)).

The company operates with its primary engineering and manufacturing facilities in Burnaby, British Columbia, and its commercial and executive US headquarters in Palo Alto, California.

### 1.2 Key Milestones

| Year | Milestone | Details |
|------|-----------|---------|
| 1999 | Founded | UBC spinout; founders: Farris, Rose, Wiens, Zagoskin |
| 2007 | Orion prototype (16-qubit) | Demonstrated at Computer History Museum, Mountain View, CA |
| 2011 | D-Wave One (128-qubit) | First commercial quantum computer sale; Lockheed Martin as first customer; ~$10M per system |
| 2011 | USC-Lockheed QCC | USC Lockheed Martin Quantum Computing Center opened with D-Wave One |
| 2012 | In-Q-Tel / Bezos investment | $30M equity round; CIA's In-Q-Tel and Bezos Expeditions joined |
| 2013 | D-Wave Two (512-qubit) | NASA/Google/USRA Quantum AI Lab at NASA Ames; $10M system |
| 2015 | D-Wave 2X (1,000+ qubit, Chimera) | General availability; 7-year agreement with Google/NASA/USRA; Lockheed upgrade at USC |
| 2017 | D-Wave 2000Q | Open-source Qbsolv software released |
| 2018 | Leap cloud service launched | Real-time quantum cloud access |
| 2019 | First Advantage system sale | Los Alamos National Laboratory as first buyer of 5,000-qubit system |
| 2020 | Advantage general availability | 5,760 qubits; Pegasus topology (15-way connectivity) |
| 2022 | SPAC merger / NYSE listing | DPCM Capital merger; QBTS ticker; company valued at ~$1.2B |
| 2024 | Advantage2 prototype (1,200+ qubit) | Available via Leap cloud service; February 2024 |
| 2024 | Advantage2 processor (4,400+ qubit) | Calibration and benchmarking completed; November 2024 |
| 2025 | Advantage2 general availability | Full-scale system available May 20, 2025; Zephyr topology |
| 2025 | Science paper: quantum supremacy | "Beyond-Classical Computation in Quantum Simulation"; March 2025 |
| 2025 | Forschungszentrum Jülich sale | Advantage system installed at Jülich Supercomputing Centre, Germany |
| 2025 | Davidson Technologies deployment | Advantage2 system at Huntsville, Alabama, for US DoD missions |
| 2026 | QCI acquisition completed | $550M acquisition of Quantum Circuits Inc.; January 20, 2026 |
| 2026 | Anduril/Davidson collaboration | Air and missile defense proof-of-concept; January 27, 2026 |

Sources: [D-Wave Wikipedia](https://en.wikipedia.org/wiki/D-Wave_Systems); [D-Wave Newsroom](https://www.dwavequantum.com/company/newsroom/); [DPCM Merger Completion Press Release](https://www.dwavequantum.com/company/newsroom/press-release/dpcm-capital-inc-and-d-wave-systems-inc-announce-completion-of-business-combination/)

### 1.3 SPAC Merger and NYSE Listing

On February 8, 2022, D-Wave Systems announced a definitive merger agreement with DPCM Capital, Inc. (NYSE: XPOA), a special purpose acquisition company ([The Register](https://www.theregister.com/2022/02/08/dwave_spac_public/)). The deal valued D-Wave at approximately $1.2 billion and was expected to provide roughly $340 million in gross proceeds. D-Wave Quantum Inc. became the surviving parent entity, and [trading under ticker QBTS commenced on August 8, 2022](https://www.dwavequantum.com/company/newsroom/press-release/dpcm-capital-inc-and-d-wave-systems-inc-announce-completion-of-business-combination/), when CEO Alan Baratz rang the NYSE opening bell.

### 1.4 Financial Position (FY 2025 and Early 2026)

D-Wave reported its [fiscal year 2025 results on February 26, 2026](https://finance.yahoo.com/news/d-wave-reports-fourth-quarter-120000261.html):

| Metric | FY 2025 | FY 2024 | Change |
|--------|---------|---------|--------|
| Total Revenue | $24.6M | $8.8M | +179% |
| Gross Profit (GAAP) | $20.3M | $5.6M | +264% |
| Gross Margin | 82.6% | 63.0% | +19.6 pts |
| Non-GAAP Gross Profit | $21.1M | $6.4M | +229% |
| Adjusted Net Loss | ($58.5M) | ($75.6M) | Improved |
| Adjusted EBITDA Loss | ($71.8M) | ($56.0M) | Widened |
| Cash & Marketable Securities | $884.5M | $178.0M | +397% |
| FY 2025 Total Bookings | $18.7M | $23.9M | — |
| Q4 2025 Bookings | $13.4M | $2.4M (Q3 2025) | — |

**Post-period developments (as of Q1 2026):**
- Q1 2026 bookings exceeded $32.8 million — more than all of FY 2025 revenue ([MarketBeat, April 2026](https://www.marketbeat.com/instant-alerts/d-wave-quantum-nyseqbts-trading-up-225-heres-why-2026-04-15/))
- January 2026: $10 million two-year QCaaS contract with a Fortune 100 company; $20 million Advantage2 system acquisition by Florida Atlantic University
- Q1 2026 earnings scheduled for May 12, 2026

**Market capitalization trajectory:**

| Date | Market Cap |
|------|-----------|
| Dec 31, 2023 | ~$141M |
| Dec 31, 2024 | ~$2.26B |
| Dec 31, 2025 | ~$9.16B |
| April 2026 | ~$5.5–7.7B (volatile) |

Source: [Stock Analysis](https://stockanalysis.com/stocks/qbts/market-cap/)

The stock rose approximately 854% in 2024 and 211% in 2025, driven by growing interest in quantum computing as a sector and D-Wave's 2025 Science paper ([The Motley Fool / Yahoo Finance](https://finance.yahoo.com/news/why-shares-d-wave-quantum-173905823.html)). An April 2026 surge of 22.5% was catalyzed in part by Nvidia's launch of open-source quantum AI models ([MarketBeat](https://www.marketbeat.com/instant-alerts/d-wave-quantum-nyseqbts-trading-up-225-heres-why-2026-04-15/)). As of late April 2026, the share price was approximately $20–21, down roughly 15% year-to-date from its 2025 peak.

### 1.5 Leadership

**Board of Directors** ([D-Wave Investor Relations](https://ir.dwavequantum.com/leadership/board-of-directors/default.aspx)):

| Name | Role | Background |
|------|------|-----------|
| Alan Baratz | CEO & Director | CEO since 2020; former president JavaSoft/Sun; Warburg Pincus MD; IBM, Cisco, Avaya executive |
| Steve West | Board Chair | Former CEO Hitachi Data Systems; 23-year Cisco director; founder Emerging Company Partners |
| Roger Biscay | Director | SVP & Treasurer, Cisco Systems; former Royal Bank of Canada, Banque Paribas, Lehman Brothers |
| Kirstjen Nielsen | Director | Former US Secretary of Homeland Security; founder Lighthouse Strategies |
| John DiLullo | Director | CEO Deepwatch; former CEO LiveVox, Lastline; F5 Networks, HP, Cisco |
| Rohit Ghai | Director | Former president Dell EMC Enterprise Content Division; prior Symantec, CA Technologies |
| Sharon Holt | Director | Former SVP Rambus; Agilent/HP; board: Infinera |

**Key executives:**
- **John Markovich** — Chief Financial Officer
- **Lorenzo Martinelli** — Chief Revenue Officer
- **Trevor Lanting** — Chief Development Officer
- **Mohammad Amin** — Chief Scientist
- **Jack Sears Jr.** — VP, U.S. Government Solutions (joined December 2025)

### 1.6 Customer Roster

**Commercial customers (disclosed):** Mastercard, Volkswagen, DENSO, Siemens Healthineers, Unisys, ArcelorMittal, NEC Corporation, Pattison Food Group, Deloitte, GE Research, SavantX (Port of Los Angeles logistics)

**Government and research customers (disclosed):** Los Alamos National Laboratory (LANL), NASA/Google/USRA Quantum AI Lab at NASA Ames, University of Southern California / Lockheed Martin Quantum Computing Center, Lockheed Martin, Oak Ridge National Laboratory (Frontier supercomputer collaboration), Forschungszentrum Jülich (Germany), Davidson Technologies (US DoD contractor), Australia's Department of Defence (via NEC Australia partnership)

Source: [Carahsoft D-Wave Government Page](https://www.carahsoft.com/d-wave); [D-Wave Tradewinds Press Release](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-deemed-awardable-vendor-for-us-department-of-defense-chief-digital-and-artificial-intelligence-office-s-tradewinds-solutions-marketplace/)

### 1.7 Recent News (2025–April 2026)

- **May 2025:** Advantage2 system generally available via Leap cloud and for on-premises purchase
- **March 2025:** Landmark *Science* paper claiming quantum computational supremacy on spin-glass simulation
- **April 2025:** Kerrisdale Capital published short-seller report targeting D-Wave's valuation and technology claims
- **October 2024:** Achieved "Awardable" DoD CDAO Tradewinds Solutions Marketplace designation
- **November 2025:** Advantage2 deployed at Davidson Technologies' Huntsville facility for DoD missions
- **December 2025:** Formed dedicated US Government Business Unit under Jack Sears Jr.
- **January 2026:** $550M QCI acquisition completed; Anduril/Davidson missile defense proof-of-concept announced; $10M Fortune 100 QCaaS contract announced
- **February 2026:** FY 2025 earnings reported; Q1 2026 bookings exceeded $32.8M
- **April 2026:** Stock surged 22.5% on Nvidia quantum AI model announcements and sector momentum

---

## SECTION 2: DEFENSE, INTELLIGENCE COMMUNITY, AND FIVE EYES TIES

### 2.1 In-Q-Tel Investment

**Verified.** In October 2012, D-Wave Systems closed a $30 million equity round with participants including Bezos Expeditions and In-Q-Tel (IQT), the venture capital arm of the Central Intelligence Agency ([GeekWire, October 2012](https://www.geekwire.com/2012/bezos-cia-invest-30-million-quantum-computing-company/)). This investment was publicly confirmed by both D-Wave and In-Q-Tel at the time ([Nextgov/FCW, October 2012](https://www.nextgov.com/emerging-tech/2012/10/nobel-award-quantum-discovery-coincides-q-tel-investment/58679/)). The specific equity stake and current IQT holding status post-SPAC merger are not publicly disclosed. No subsequent IQT investment rounds have been publicly announced.

### 2.2 US Federal Contracts and Agency Relationships

#### Los Alamos National Laboratory (LANL / DOE)

LANL is D-Wave's longest-standing and most active government research partner. Key milestones:
- D-Wave One (128-qubit) installed at LANL; early research relationship established ~2011
- 2019: LANL became the **first purchaser** of the 5,000-qubit Advantage system ([D-Wave Newsroom via Tom's Hardware](https://www.dwavequantum.com/company/newsroom/media-coverage/tom-s-hardware-d-wave-announces-first-sale-of-its-5-000-qubit-quantum-computer/))
- Post-2021: LANL's Laboratory Directed R&D (LDRD) program funded ongoing research using D-Wave annealers for quantum phase transitions (Boltzmann sampling, renormalization group methods), magnetic monopole emulation, and critical phenomena ([Los Alamos National Laboratory, April 2026](https://www.lanl.gov/media/news/0416-quantum-computing))

Note: Specific contract numbers for LANL's purchases are not publicly disclosed through FPDS or USAspending.gov for DOE/NNSA management and operations contracts.

#### NASA Jet Propulsion Laboratory (JPL) — Space Act Agreement

A reimbursable Space Act Agreement (SAA number 82-16404 / 97-16404) between NASA and D-Wave Systems has governed collaborative fabrication of superconducting niobium integrated circuits since 2011. JPL's Microdevices Lab (MDL) fabricates D-Wave's superconducting test chips, conducts cryogenic characterization, and supports noise reduction R&D; D-Wave handles circuit design and functional testing. The agreement has been extended multiple times ([NASA SAA CA-0450-4, February 2022](https://www.nasa.gov/saa/international/CA-0450-4.pdf)):

| Amendment | Date | Cumulative Value |
|-----------|------|-----------------|
| Original | June 22, 2011 | $2.56M |
| Revision A | July 29, 2014 | $3.58M |
| Revision B | November 9, 2015 | $4.27M |
| Revision C | September 25, 2017 | $6.11M (incl. NASA cost) |
| Revision D | October 31, 2019 | $8.54M (lifecycle, incl. NASA cost) |
| Revision E / Amendment 4 | June 17, 2021 / Feb 2022 | $8.54M; extended to August 31, 2027 |

#### NASA Ames / Google / USRA — Quantum Artificial Intelligence Lab

- **2013:** NASA, Google, and the Universities Space Research Association (USRA) jointly purchased a D-Wave Two (512-qubit) system for $10 million, installed at the NASA Advanced Supercomputing Facility at NASA Ames Research Center ([Forbes, May 2013](https://www.forbes.com/sites/alexknapp/2013/05/16/nasa-and-google-partner-to-purchase-a-d-wave-quantum-computer/))
- **2015:** Seven-year upgrade agreement signed; D-Wave 2X installed September 2015 ([PC World](https://www.pcworld.com/article/423757/google-nasa-sign-7-year-deal-to-test-d-wave-quantum-computers-as-artificial-brains.html)); 2000Q subsequently installed (2017) ([Data Center Dynamics](https://www.datacenterdynamics.com/en/news/universities-space-research-association-upgrades-d-wave-used-by-google-nasa/))
- Current status: The seven-year agreement term ended around 2022; no subsequent public announcement of a renewal with NASA/Google/USRA has been made

#### Lockheed Martin and USC-Lockheed Martin Quantum Computing Center (QCC)

- **2011:** Lockheed Martin signed a multi-year contract and purchased D-Wave One — D-Wave's first commercial sale ([HPCwire, October 2011](https://www.hpcwire.com/2011/10/31/d-wave_entangles_with_usc_and_lockheed_at_new_quantum_computing_center/))
- **2011:** USC Lockheed Martin Quantum Computing Center established at USC's Information Sciences Institute; sole university in the world operating a commercial quantum computer
- **2015:** Lockheed upgraded to D-Wave 2X (1,000-qubit) system at USC QCC ([Business in Vancouver](https://www.biv.com/news/technology/d-wave-supply-lockheed-martin-new-1000-qubit-quant-8244739))
- **2020:** USC renewed the arrangement with D-Wave and Lockheed Martin; QCC upgraded to Advantage (5,000-qubit) system and became the first Leap cloud deployment in the United States ([USC Viterbi School of Engineering](https://viterbischool.usc.edu/news/2020/06/usc-renews-quantum-computing-collaboration-with-d-wave-lockheed-martin/))
- Financial terms of Lockheed Martin's contracts have not been publicly disclosed

#### DoD CDAO Tradewinds Marketplace

October 31, 2024: D-Wave achieved "Awardable" status on the Department of Defense Chief Digital and Artificial Intelligence Office's Tradewinds Solutions Marketplace, simplifying procurement for DoD customers ([D-Wave Press Release, October 2024](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-deemed-awardable-vendor-for-us-department-of-defense-chief-digital-and-artificial-intelligence-office-s-tradewinds-solutions-marketplace/)). D-Wave worked with defense broker Clipper Defense to submit use-case documentation covering supply chain optimization and transportation logistics.

#### Davidson Technologies Partnership

November 2025: D-Wave's Advantage2 quantum computer went operational at Davidson Technologies' headquarters in Huntsville, Alabama, accessible to US DoD and commercial aerospace customers via D-Wave's cloud ([Nextgov/FCW, November 2025](https://www.nextgov.com/emerging-tech/2025/11/d-wave-makes-its-quantum-annealers-available-national-security-work/409225/)). The system is designated for mission-critical tasks and eventually sensitive applications. Specific contract terms are not publicly disclosed.

#### Anduril Industries Collaboration (2026)

January 27, 2026: D-Wave, Davidson Technologies, and Anduril Industries announced a proof-of-concept collaboration on air and missile defense planning. Using Anduril's defense simulations and D-Wave's Stride hybrid solver on Advantage2, initial benchmarks showed at least 10x faster time-to-solution versus classical-only approaches, 9–12% improvement in threat mitigation, and the ability to intercept an additional 45–60 missiles in a 500-missile attack simulation ([D-Wave Press Release, January 2026](https://www.dwavequantum.com/company/newsroom/press-release/anduril-davidson-and-d-wave-collaborate-to-develop-quantum-applications-for-us-air-and-missile-defense/)). No contract dollar values were disclosed.

#### US Government Business Unit

December 2, 2025: D-Wave formed a dedicated US Government Business Unit led by Jack Sears Jr. (25+ years in defense contracting; former chief growth officer at Precise Systems; former roles at Parsons Corporation and Epsilon Systems; managed pipelines exceeding $3 billion). The unit targets DoD, aerospace, and infrastructure markets ([D-Wave Press Release, December 2025](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-announces-formation-of-u-s-government-business-unit/)).

### 2.3 DARPA — Quantum Benchmarking Initiative

D-Wave was **not selected** for Stage B of DARPA's Quantum Benchmarking Initiative (QBI) as of November 6, 2025 ([DARPA Stage B Selection](https://www.darpa.mil/research/programs/quantum-benchmarking-initiative/stage-b-selection)). The eleven selected companies span neutral atoms, trapped ions, superconducting gate-model, silicon spin qubits, and photonics — all gate-model approaches. Quantum annealing is architecturally ineligible for QBI, which targets fault-tolerant universal quantum computing capable of running Shor's algorithm and similar gate-based workloads by 2033. DARPA's Stage A remains open to new entrants through September 30, 2026 ([R&D World](https://www.rdworldonline.com/darpas-quantum-benchmarking-push-can-a-useful-quantum-computer-exist-by-2033/)).

D-Wave's QCI acquisition may enable future QBI participation through its gate-model track; no application has been announced.

### 2.4 Five Eyes / Allied Government Ties

#### Australia — Department of Defence

**Verified.** April 20, 2021: NEC Australia and D-Wave Systems were selected by the Australian Department of Defence to demonstrate hybrid quantum computing technology for a "last mile resupply" problem — optimizing autonomous vehicle resupply logistics for army forces from a central base ([D-Wave Press Release, April 2021](https://www.dwavequantum.com/company/newsroom/press-release/nec-d-wave-and-the-australian-department-of-defence-collaborate-on-quantum-computing-initiative/)). This was part of Australia's Army Quantum Technology Challenge. The NEC Australia–D-Wave collaboration dates to November 2019. No contract values were disclosed.

#### Canada — Defence Research and Development Canada (DRDC) / DND

No publicly verified direct contract between D-Wave and Canadian DND/DRDC has been identified in open sources. D-Wave is Canadian-headquartered and has historical ties to Canadian government funding (early government grants supporting its UBC-era research). The Canadian government's National Quantum Strategy may create future engagement opportunities, but no specific DND contracts are confirmed as of April 2026.

#### United Kingdom — Ministry of Defence

No publicly verified direct MoD contract with D-Wave has been identified. UK quantum computing strategy documents do not specifically cite D-Wave partnerships. **Flag: unverified; no primary source confirmation.**

#### New Zealand

No publicly identified engagement. **Flag: no primary source.**

### 2.5 NSA and Intelligence Community

No NSA-disclosed or officially confirmed work with D-Wave has been identified in open sources. The In-Q-Tel investment (2012) represents the only confirmed US intelligence community financial relationship. Given In-Q-Tel's mandate to invest in technologies relevant to CIA and broader IC missions, an unclassified interest in quantum optimization is implied, but no specific IC operational programs have been disclosed. **Flag: any IC operational use beyond IQT investment is unverified.**

### 2.6 Export Controls and National Security

The US Department of Commerce's Bureau of Industry and Security (BIS) implemented new Export Control Classification Numbers (ECCNs) covering quantum computing items effective September 2024, including ECCNs 3A904, 3B904, and others governing quantum computers, components, materials, and technology ([Cleary Foreign Investment Watch, September 2024](https://www.clearytradewatch.com/2024/09/commerce-imposes-export-controls-on-quantum-computing-and-other-advanced-technologies-expands-scope-of-cfius-mandatory-filing-requirement/)). These controls also expanded CFIUS mandatory filing requirements for foreign investments in quantum computing companies.

As a Canadian-headquartered company listed on the NYSE with significant US government customer relationships, D-Wave operates at the intersection of these regimes. No CFIUS review of D-Wave's SPAC transaction or subsequent investments has been publicly disclosed or confirmed. Canada is an A:1 country listed under the new License Exception IEC, reducing export license requirements for bilateral technology sharing. Australia and the UK are also on the IEC eligible list, consistent with Five Eyes alignment.

### 2.7 Public Sector Customers — Summary Table

```csv
Customer,Relationship,Status,Key Details,Approximate Value/Contract
Los Alamos National Laboratory,First Advantage system buyer; ongoing LDRD research,Active (2011–present),First 5000-qubit Advantage sale (2019); LDRD-funded research,Undisclosed (system ~$10–15M est.)
NASA JPL,Space Act Agreement 82-16404/97-16404,Active (2011–August 2027),Niobium superconductor fabrication for D-Wave chips,~$8.5M total (cumulative amendments)
NASA Ames / USRA / Google,Quantum AI Lab; D-Wave Two + 2X + 2000Q,Concluded (2013–~2022),$10M system sale 2013; 7-year upgrade agreement 2015,~$10M+ system; upgrade terms undisclosed
USC / Lockheed Martin QCC,Commercial quantum computing center; multiple system upgrades,Active (2011–present),First university to host commercial quantum computer,Undisclosed
Lockheed Martin,First-ever D-Wave commercial customer,Active (ongoing) ,D-Wave One 2011; upgrades through Advantage; USC QCC host,Undisclosed (first sale ~$10M)
Australian Dept. of Defence,Army Quantum Technology Challenge (via NEC Australia),Completed PoC (2021),Last-mile resupply autonomous vehicle optimization,Undisclosed
Davidson Technologies,Advantage2 on-premises deployment,Active (2025–present),Huntsville AL; DoD/aerospace missions; basis for Anduril collab,Undisclosed
DoD CDAO Tradewinds,Awardable vendor designation,Active (Oct 2024),Simplified procurement path for DoD customers,N/A (procurement vehicle)
In-Q-Tel,Equity investor (CIA venture arm),Investment (2012),Part of $30M round with Bezos Expeditions,Part of $30M round
Forschungszentrum Jülich,Advantage system sale (Germany),Completed (2025),Jülich Supercomputing Centre; JUPITER exascale integration,Undisclosed
```

---

## SECTION 3: TECHNICAL ARCHITECTURE

### 3.1 Quantum Annealing — Physical Principles

Quantum annealing is an analog optimization technique that leverages quantum mechanical effects — specifically quantum tunneling and superposition — to find low-energy (ground) states of a physical system representing a computational problem. D-Wave's implementation is a physical realization of the transverse-field Ising model, governed by the time-dependent Hamiltonian:

```
H(s) = -A(s)/2 * Σᵢ σˣᵢ + B(s)/2 * [Σᵢ hᵢ σᶻᵢ + Σᵢ<ⱼ Jᵢⱼ σᶻᵢ σᶻⱼ]
```

where `s = t/T` is the normalized anneal time (0 to 1), `A(s)` is the transverse field energy (decreasing from a large initial value), `B(s)` is the problem Hamiltonian energy (increasing), `σˣ` and `σᶻ` are Pauli operators, `hᵢ` are qubit biases, and `Jᵢⱼ` are coupler strengths encoding the problem ([Nature Scientific Reports, April 2025](https://www.nature.com/articles/s41598-025-96220-2)).

The **adiabatic theorem** guarantees that if the Hamiltonian evolves slowly enough relative to the energy gap above the ground state, the quantum system remains in the instantaneous ground state throughout — yielding the solution to the encoded optimization problem. In practice, D-Wave operates in a non-strictly-adiabatic regime, using thermal and quantum fluctuations jointly, which complicates theoretical analysis of its speedup properties.

Problems must be formulated as **Quadratic Unconstrained Binary Optimization (QUBO)** or equivalently as Ising spin problems. Many real-world problems require reformulation overhead and auxiliary variable introduction to fit this structure.

### 3.2 Hardware Architecture

**Qubits:** D-Wave uses superconducting **niobium flux qubits** — loops of niobium wire in which the quantum state is encoded in the direction of circulating electrical current. The qubits must be cooled to approximately **15 millikelvin** (roughly 180 times colder than interstellar space) using a dilution refrigerator, isolating them from thermal noise.

**Processor Generations and Topologies:**

| Generation | Commercial Year | Qubit Count | Topology | Qubit Connectivity | Notes |
|------------|----------------|-------------|----------|--------------------|-------|
| D-Wave One | 2011 | 128 | Chimera | 6-way | First commercial quantum computer |
| D-Wave Two | 2013 | 512 | Chimera | 6-way | NASA/Google Ames system |
| D-Wave 2X | 2015 | 1,000+ | Chimera | 6-way | 15x speedup claim on specific problems |
| D-Wave 2000Q | 2017 | 2,048 | Chimera | 6-way | Open-source Qbsolv released |
| Advantage | 2020 | 5,760 | Pegasus | 15-way | 10x improvement over 2000Q |
| Advantage2 | 2025 (GA) | 4,400+ | Zephyr | 20-way | 40% higher energy scale; 75% noise reduction; 2x coherence |

**Topology Details:**
- **Chimera:** Grid graph with K₄,₄ unit cells; each qubit connected to 6 others; used through 2000Q generation
- **Pegasus:** Each qubit connects to 15 others; nominal length 12; enables embedding of larger problems with fewer physical qubits; native K₄ and K₆,₆ subgraphs ([HPCwire, February 2019](https://www.hpcwire.com/2019/02/27/d-wave-previews-next-gen-platform-debuts-pegasus-topology-targets-5000-qubits/))
- **Zephyr:** Each qubit connects to 20 others via 16 internal, 2 external, and 2 odd couplers; enables native K₄ and K₈,₈ subgraphs; higher nominal degree than any prior D-Wave topology ([D-Wave Topology Documentation](https://docs.dwavequantum.com/en/latest/quantum_research/topologies.html); [Zephyr Topology Technical Paper](https://www.dwavequantum.com/media/2uznec4s/14-1056a-a_zephyr_topology_of_d-wave_quantum_processors.pdf))

**Advantage2 Performance Specifications (as of general availability, May 2025):**
- 4,400+ qubits; Zephyr topology; 20-way connectivity
- 40% increase in energy scale vs. Advantage
- 75% noise reduction
- 2x coherence time improvement
- Benchmarks show 25,000x faster than Advantage on 3D lattice (materials science) problems
- Hybrid solvers via Leap support up to 2 million variables and constraints
- 99.9% availability; sub-second response times; SOC 2 Type 2 compliant

Source: [D-Wave Advantage2 GA Press Release, May 2025](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-announces-general-availability-of-advantage2-quantum-computer-its-most-advanced-and-performant-system/)

### 3.3 Limitations and the Quantum Speedup Debate

**Structural limitations:**
1. **Problem class restriction:** Quantum annealing solves only QUBO/Ising-class problems. It cannot implement universal gate-model algorithms such as Grover's search (quadratic speedup for unstructured search) or Shor's algorithm (polynomial-time integer factorization). This eliminates D-Wave systems from cryptanalysis and most of the gate-model quantum computing research agenda.

2. **Embedding overhead:** D-Wave's sparse connectivity requires "minor embedding" of logical problem graphs into the hardware graph. For dense problems, a single logical qubit may require a "chain" of many physical qubits, consuming >90% of available qubits for complex real-world problems — an overhead problem that grows superlinearly with problem density ([Kerrisdale Capital Report, April 2025](https://www.kerrisdalecap.com/wp-content/uploads/2025/04/Dwave-Kerrisdale.pdf)).

3. **Analog noise:** As an analog device, D-Wave systems suffer from control parameter imprecision (flux noise, charge noise, material defects) that can corrupt solutions. The Advantage2 design substantially reduces noise relative to Advantage but does not eliminate it.

4. **No error correction:** D-Wave does not implement quantum error correction. The system operates in a noisy intermediate-scale regime where thermal fluctuations at ~15 mK remain significant.

**The quantum speedup controversy:**

The foundational debate over whether D-Wave systems deliver genuine quantum advantage over optimized classical algorithms dates to 2014. In a landmark *Science* paper, [Rønnow, Wang, Job, Boixo, Isakov, Wecker, Martinis, Lidar, and Troyer (2014)](https://arxiv.org/abs/1401.2910) found "no evidence of quantum speedup" comparing D-Wave Two performance against optimized classical and quantum Monte Carlo algorithms on random spin-glass instances. Physicist Matthias Troyer (ETH Zürich, now Microsoft) and Daniel Lidar (USC) were co-authors; both participated in the USC D-Wave One benchmarking work.

Key findings in the speedup debate:
- Troyer's group wrote simulated annealing code that solved the D-Wave problem on a classical PC approximately 15x faster than the D-Wave machine itself ([Shtetl-Optimized, Scott Aaronson](https://scottaaronson.blog/?p=1400))
- Later D-Wave papers adopted a "time-to-target" (TTT) metric designed to compare performance at near-optimal solutions rather than ground state success rates, finding 2–15x speedups at largest problem sizes versus competing software — explicitly noting this does not address quantum speedup ([The Register, August 2015](https://www.theregister.com/2015/08/27/dwave_whether_or_not_its_quantum_its_faster/))
- The academic debate continues; subsequent D-Wave hardware generations have shown improved performance, but no universally accepted demonstration of superpolynomial quantum speedup on practical problem classes had been published prior to 2025

**2025 quantum supremacy claim:**

On March 12, 2025, D-Wave published "Beyond-Classical Computation in Quantum Simulation" in *Science*, authored by Andrew D. King and colleagues across 11 institutions worldwide. The paper reports that D-Wave's Advantage2 prototype simulated quantum dynamics of spin glasses (transverse-field Ising model on various lattice geometries) in minutes, achieving accuracy that would require nearly one million years on the Frontier GPU-based supercomputer at Oak Ridge National Laboratory ([D-Wave Press Release, March 2025](https://www.dwavequantum.com/company/newsroom/press-release/beyond-classical-d-wave-first-to-demonstrate-quantum-supremacy-on-useful-real-world-problem/)).

This claim was immediately contested:
- Researchers at the Flatiron Institute posted an arXiv paper demonstrating that classical belief propagation algorithms could outperform D-Wave's results on a subset of the tested spin-glass problems
- EPFL researchers (Mauron, Carleo) demonstrated that time-dependent variational Monte Carlo (t-VMC) methods achieved correlation errors below 7% for systems up to 128 spins in 3D diamond lattice geometry — rivaling D-Wave's results
- CEO Alan Baratz defended the paper, arguing that critics tested only subsets and that D-Wave's work covered a broader range of lattice geometries and evolution conditions ([The Quantum Insider, March 2025](https://thequantuminsider.com/2025/03/14/d-wave-ceo-responds-to-criticisms-about-quantum-supremacy-claim/))

The peer-reviewed publication in *Science* carries significant weight, and endorsements came from MIT's Seth Lloyd and Tokyo Tech's Hidetoshi Nishimori (a co-inventor of quantum annealing). However, the scope of the advantage — limited to quantum simulation of specific spin models — does not generalize to combinatorial optimization use cases that are D-Wave's commercial focus.

### 3.4 Gate-Model Comparison

D-Wave's annealing architecture is fundamentally different from gate-model quantum computers, which implement universal computation through sequences of discrete logical gates. The table below compares leading quantum computing approaches:

| Company / System | Technology | Qubits | Connectivity | Key Metric | Use Case |
|------------------|-----------|--------|-------------|-----------|---------|
| D-Wave Advantage2 | Annealing (superconducting flux) | 4,400+ | 20-way (Zephyr) | Speed on QUBO optimization | Combinatorial optimization |
| D-Wave / QCI (roadmap) | Gate-model (dual-rail superconducting) | 8→17→49 (2026–2027) | TBD | Error detection built-in | Universal gate-model |
| IBM Nighthawk | Superconducting transmon (gate) | 120 | 4-way (square lattice) | 5,000 two-qubit gates per circuit | General quantum computation |
| IBM Heron | Superconducting transmon (gate) | 133 | Heavy-hex (2–3 way) | 3–5x over Eagle; 1,800 gates/cycle | General quantum computation |
| IBM Condor | Superconducting transmon (gate) | 1,121 | Heavy-hex | First 1,000+ superconducting qubit | Research/scale demonstration |
| Google Willow | Superconducting transmon (gate) | 105 | ~3.5-way average | Below QEC threshold; 5 min vs. 10²⁵ yr on RCS | Error correction demonstration |
| Quantinuum H2-1 | Trapped ion (QCCD) | 56 | All-to-all | QV 2²⁵; 4,620 two-qubit gates coherently | High-fidelity universal computing |
| IonQ Forte/Tempo | Trapped ion | 36 AQ | All-to-all | AQ 64 achieved; 99.99% two-qubit fidelity | Universal computing |
| Rigetti (modular) | Superconducting (gate) | 84–108 | Limited | Chiplet modular design | Universal computing |

Sources: [Google Willow Spec Sheet](https://quantumai.google/static/site-assets/downloads/willow-spec-sheet.pdf); [IBM Nighthawk announcement](https://thequantuminsider.com/2025/11/12/ibm-reveals-new-quantum-processors-software-and-algorithm-advances/); [IBM Heron specs](https://postquantum.com/industry-news/ibm-133-qubit-heron-quantum/); [Quantinuum H2 QV](https://quantumcomputingreport.com/quantinuum-achieves-quantum-volume-of-2%C2%B2%E2%81%B5-on-system-model-h2/)

**Key architectural distinction:** D-Wave's 4,400-qubit count should not be compared directly with gate-model qubit counts. Annealing qubits do not execute logic gates, do not support circuit-model algorithms, and derive their computational relevance entirely from the physical structure of the problem being solved and the quality of the Ising embedding. A fair comparison for D-Wave's annealing performance is against optimized classical solvers (e.g., Gurobi, CPLEX, simulated annealing) for the same QUBO/Ising problem class.

### 3.5 Gate-Model Roadmap: Quantum Circuits Inc. Acquisition

**January 7, 2026:** D-Wave announced a $550 million acquisition of Quantum Circuits Inc. (QCI), a Yale University spinout led by Dr. Rob Schoelkopf (inventor of the transmon qubit and dual-rail qubit architecture) ([D-Wave Press Release, January 2026](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-to-acquire-quantum-circuits-inc-establishing-world-s-leading-quantum-computing-company/)). The deal closed January 20, 2026 ([D-Wave Completion Press Release](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-completes-acquisition-of-quantum-circuits/)).

**QCI's technology:** Dual-rail qubits with hardware-native error detection built directly into the qubit architecture. A dual-rail qubit encodes quantum information across two microwave resonator modes; any photon-loss error causes a detectable syndrome, allowing error detection at the hardware level without the large ancilla qubit overhead of surface codes. This reduces the physical qubit count required for logical qubits.

**Roadmap (as of January 2026):**

| Timeline | System | Notes |
|---------|--------|-------|
| 2026 (current) | 8 dual-rail qubits | Alpha user testing |
| 2026 (GA) | 17 dual-rail qubits | Generally available |
| 2027 | 49 dual-rail qubits | Error correction testing possible |
| 2028 | 181 dual-rail qubits | Sufficient for surface code techniques |
| 2030s | ~1,000 dual-rail qubits | Long-term commercial target |

Source: [Quantum Computing Report, January 2026](https://quantumcomputingreport.com/d-wave-quantum-to-acquire-quantum-circuits-inc-to-accelerate-error-corrected-gate-model-roadmap/)

D-Wave plans to integrate QCI gate-model systems into its Leap cloud service alongside annealing systems. The R&D center in New Haven, Connecticut, will be led by Dr. Schoelkopf and the former QCI team. The combined company is positioned as the only vendor offering both annealing and gate-model superconducting quantum computing in production.

### 3.6 Hybrid Solvers and Commercial Software

D-Wave's **Leap** quantum cloud service (launched 2018) provides:
- Access to Advantage2 quantum processors in over 40 countries
- Hybrid solver suite supporting problems up to 2 million variables
- Non-linear hybrid solver; Stride solver (used in Anduril missile defense PoC)
- SOC 2 Type 2 compliance; 99.9% uptime SLA; sub-second response times

The **Ocean SDK** provides open-source Python tools for problem formulation, embedding, and hybrid classical-quantum workflow orchestration. D-Wave's commercial value proposition increasingly rests on the Stride and other hybrid solvers, which use quantum hardware as an accelerator within predominantly classical workflows. Critics note that the quantum contribution in these hybrid pipelines is difficult to isolate and may be minimal for many problem instances ([Kerrisdale Capital, April 2025](https://www.kerrisdalecap.com/wp-content/uploads/2025/04/Dwave-Kerrisdale.pdf)).

---

## SOURCES APPENDIX

All primary sources cited in this report:

1. D-Wave Wikipedia — https://en.wikipedia.org/wiki/D-Wave_Systems
2. MIT Technology Review (2005 founding profile) — https://www.technologyreview.com/2005/07/01/230661/quantum-calculation/
3. D-Wave SPAC merger completion press release — https://www.dwavequantum.com/company/newsroom/press-release/dpcm-capital-inc-and-d-wave-systems-inc-announce-completion-of-business-combination/
4. The Register — D-Wave SPAC announcement — https://www.theregister.com/2022/02/08/dwave_spac_public/
5. D-Wave Q4 & FY 2025 Earnings (Yahoo Finance) — https://finance.yahoo.com/news/d-wave-reports-fourth-quarter-120000261.html
6. Stock Analysis — QBTS Market Cap History — https://stockanalysis.com/stocks/qbts/market-cap/
7. The Motley Fool / Yahoo Finance — QBTS 2025 stock returns — https://finance.yahoo.com/news/why-shares-d-wave-quantum-173905823.html
8. D-Wave Board of Directors — https://ir.dwavequantum.com/leadership/board-of-directors/default.aspx
9. Carahsoft D-Wave Government Page — https://www.carahsoft.com/d-wave
10. D-Wave Tradewinds "Awardable" Designation — https://www.dwavequantum.com/company/newsroom/press-release/d-wave-deemed-awardable-vendor-for-us-department-of-defense-chief-digital-and-artificial-intelligence-office-s-tradewinds-solutions-marketplace/
11. D-Wave US Government Business Unit — https://www.dwavequantum.com/company/newsroom/press-release/d-wave-announces-formation-of-u-s-government-business-unit/
12. Nextgov/FCW — Davidson Technologies deployment — https://www.nextgov.com/emerging-tech/2025/11/d-wave-makes-its-quantum-annealers-available-national-security-work/409225/
13. D-Wave / Anduril / Davidson missile defense — https://www.dwavequantum.com/company/newsroom/press-release/anduril-davidson-and-d-wave-collaborate-to-develop-quantum-applications-for-us-air-and-missile-defense/
14. GeekWire — In-Q-Tel / Bezos investment — https://www.geekwire.com/2012/bezos-cia-invest-30-million-quantum-computing-company/
15. Nextgov/FCW — In-Q-Tel investment 2012 — https://www.nextgov.com/emerging-tech/2012/10/nobel-award-quantum-discovery-coincides-q-tel-investment/58679/
16. IQT Library — D-Wave $30M round — https://www.iqt.org/library/d-wave-systems-inc-the-worlds-first-commercial-quantum-computing-company-secures-30-million-in-a-new-equity-round-from-investors-including-bezos-expeditions-and-in-q-tel
17. D-Wave / NEC / Australian DoD — https://www.dwavequantum.com/company/newsroom/press-release/nec-d-wave-and-the-australian-department-of-defence-collaborate-on-quantum-computing-initiative/
18. NASA Space Act Agreement CA-0450-4 — https://www.nasa.gov/saa/international/CA-0450-4.pdf
19. Forbes — NASA/Google/USRA D-Wave Two purchase — https://www.forbes.com/sites/alexknapp/2013/05/16/nasa-and-google-partner-to-purchase-a-d-wave-quantum-computer/
20. PC World — Google/NASA 7-year agreement — https://www.pcworld.com/article/423757/google-nasa-sign-7-year-deal-to-test-d-wave-quantum-computers-as-artificial-brains.html
21. Data Center Dynamics — USRA 2000Q upgrade — https://www.datacenterdynamics.com/en/news/universities-space-research-association-upgrades-d-wave-used-by-google-nasa/
22. USC Viterbi — QCC renewal 2020 — https://viterbischool.usc.edu/news/2020/06/usc-renews-quantum-computing-collaboration-with-d-wave-lockheed-martin/
23. HPCwire — USC/Lockheed QCC opening 2011 — https://www.hpcwire.com/2011/10/31/d-wave_entangles_with_usc_and_lockheed_at_new_quantum_computing_center/
24. Business in Vancouver — Lockheed 2X upgrade 2015 — https://www.biv.com/news/technology/d-wave-supply-lockheed-martin-new-1000-qubit-quant-8244739
25. D-Wave LANL first Advantage sale — https://www.dwavequantum.com/company/newsroom/media-coverage/tom-s-hardware-d-wave-announces-first-sale-of-its-5-000-qubit-quantum-computer/
26. LANL — D-Wave research 2026 — https://www.lanl.gov/media/news/0416-quantum-computing
27. DARPA QBI Stage B Selection — https://www.darpa.mil/research/programs/quantum-benchmarking-initiative/stage-b-selection
28. DARPA — US2QC/QBI overview — https://www.darpa.mil/news/2025/quantum-computing-approaches
29. R&D World — DARPA QBI Stage A expansion — https://www.rdworldonline.com/darpas-quantum-benchmarking-push-can-a-useful-quantum-computer-exist-by-2033/
30. Cleary — Export controls September 2024 — https://www.clearytradewatch.com/2024/09/commerce-imposes-export-controls-on-quantum-computing-and-other-advanced-technologies-expands-scope-of-cfius-mandatory-filing-requirement/
31. D-Wave Science paper press release (quantum supremacy) — https://www.dwavequantum.com/company/newsroom/press-release/beyond-classical-d-wave-first-to-demonstrate-quantum-supremacy-on-useful-real-world-problem/
32. The Quantum Insider — CEO response to supremacy criticism — https://thequantuminsider.com/2025/03/14/d-wave-ceo-responds-to-criticisms-about-quantum-supremacy-claim/
33. D-Wave Advantage2 GA press release — https://www.dwavequantum.com/company/newsroom/press-release/d-wave-announces-general-availability-of-advantage2-quantum-computer-its-most-advanced-and-performant-system/
34. HPCwire — Advantage2 4,400 qubit benchmarks — https://www.hpcwire.com/2024/11/06/d-wave-readies-4400-plus-qubit-advantage2-system-for-use/
35. D-Wave QCI acquisition announcement — https://www.dwavequantum.com/company/newsroom/press-release/d-wave-to-acquire-quantum-circuits-inc-establishing-world-s-leading-quantum-computing-company/
36. D-Wave QCI acquisition completion — https://www.dwavequantum.com/company/newsroom/press-release/d-wave-completes-acquisition-of-quantum-circuits/
37. Quantum Computing Report — QCI acquisition analysis — https://quantumcomputingreport.com/d-wave-quantum-to-acquire-quantum-circuits-inc-to-accelerate-error-corrected-gate-model-roadmap/
38. HPCwire — Pegasus topology preview — https://www.hpcwire.com/2019/02/27/d-wave-previews-next-gen-platform-debuts-pegasus-topology-targets-5000-qubits/
39. D-Wave Zephyr topology documentation — https://docs.dwavequantum.com/en/latest/quantum_research/topologies.html
40. D-Wave Zephyr topology paper — https://www.dwavequantum.com/media/2uznec4s/14-1056a-a_zephyr_topology_of_d-wave_quantum_processors.pdf
41. arXiv — Rønnow et al. (2014) — Defining and detecting quantum speedup — https://arxiv.org/abs/1401.2910
42. Wired — Troyer quantum speedup 2014 — https://www.wired.com/2014/06/d-wave-quantum-speedup/
43. Scott Aaronson (Shtetl-Optimized) — D-Wave speedup analysis — https://scottaaronson.blog/?p=1400
44. The Register — D-Wave TTT metric 2015 — https://www.theregister.com/2015/08/27/dwave_whether_or_not_its_quantum_its_faster/
45. Nature Scientific Reports — Quantum annealing applications (2025) — https://www.nature.com/articles/s41598-025-96220-2
46. arXiv — Three generations D-Wave benchmarks — https://arxiv.org/abs/2301.03009
47. Kerrisdale Capital — D-Wave short report — https://www.kerrisdalecap.com/wp-content/uploads/2025/04/Dwave-Kerrisdale.pdf
48. Google Willow spec sheet — https://quantumai.google/static/site-assets/downloads/willow-spec-sheet.pdf
49. IBM Nighthawk (The Quantum Insider) — https://thequantuminsider.com/2025/11/12/ibm-reveals-new-quantum-processors-software-and-algorithm-advances/
50. IBM Heron (PostQuantum) — https://postquantum.com/industry-news/ibm-133-qubit-heron-quantum/
51. Quantinuum H2 QV benchmark — https://quantumcomputingreport.com/quantinuum-achieves-quantum-volume-of-2%C2%B2%E2%81%B5-on-system-model-h2/
52. Quantinuum H2-1 56 qubit announcement — https://www.quantinuum.com/blog/quantinuums-h-series-hits-56-physical-qubits-that-are-all-to-all-connected-and-departs-the-era-of-classical-simulation
53. MarketBeat — QBTS April 2026 surge — https://www.marketbeat.com/instant-alerts/d-wave-quantum-nyseqbts-trading-up-225-heres-why-2026-04-15/
54. Quantum Computing Report — D-Wave US Government Business Unit — https://quantumcomputingreport.com/d-wave-forms-dedicated-u-s-government-business-unit-to-accelerate-quantum-adoption-in-defense-sector/
55. PostQuantum — DARPA QBI Stage B — https://postquantum.com/industry-news/darpaqbi-stage-b/

---

*This briefing was prepared using publicly available information from primary sources including SEC-disclosable press releases, NASA Space Act Agreements, DARPA official program pages, peer-reviewed scientific papers, and verified financial reporting. It does not constitute investment advice. No classified or non-public information was used.*
