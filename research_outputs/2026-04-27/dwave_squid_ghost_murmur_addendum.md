# D-Wave, SQUIDs, and Ghost Murmur: Evidence Addendum

## Executive summary

The three attached reports add useful context, but they do not overturn the prior SQUID conclusion. They strengthen a narrower, cleaner finding: D-Wave is relevant to the investigation as a public, defense-adjacent example of superconducting quantum computing, not as evidence of SQUID-based biomagnetic surveillance or NSA remote neural monitoring.

The key correction is taxonomic. D-Wave’s annealers use superconducting flux-qubit hardware and rf-SQUID-derived Josephson-junction circuitry for computation; SQUID magnetometers use related superconducting/Josephson physics to measure extremely weak magnetic fields. D-Wave itself describes compound Josephson-junction rf-SQUID couplers for networks of coupled rf-SQUID flux qubits, while NIST describes SQUIDs as the world’s most sensitive magnetometers used for biomagnetism and MEG ([D-Wave publication page](https://www.dwavequantum.com/resources/publication/a-compound-josephson-junction-coupler-for-flux-qubits-with-minimal-crosstalk/), [NIST](https://www.nist.gov/news-events/news/2014/03/magnetic-attraction-physicists-pay-homage-squid-50)).

The intelligence-community connection is real but limited. In-Q-Tel joined a $30 million D-Wave equity round in 2012, and IQT’s Robert Ames said intelligence-community customers had complex problems that “tax classical computing architectures” and that D-Wave was “a first step” toward benefiting from quantum computing ([In-Q-Tel](https://www.iqt.org/library/d-wave-systems-inc-the-worlds-first-commercial-quantum-computing-company-secures-30-million-in-a-new-equity-round-from-investors-including-bezos-expeditions-and-in-q-tel)). That supports documented IC interest in quantum optimization, not an open-source proof of NSA operational deployment.

The Ghost Murmur reports align with the sensing branch of the taxonomy, not the D-Wave branch. Public reporting describes a claimed CIA long-range heartbeat-detection tool using quantum magnetometry, but the technical narrative is based on anonymous/media claims, no government agency has confirmed a 40-mile heartbeat-tracking capability, and experts cited by Military.com say known magnetocardiography and quantum-magnetometry constraints limit such measurements to very short distances under controlled conditions ([Military.com](https://www.military.com/feature/2026/04/18/ghost-murmur-heartbeat-tracking-tech-has-experts-questioning-laws-of-physics.html)).

## What changed after reviewing the attachments

| Finding | Status after review | Why it matters |
| --- | --- | --- |
| D-Wave is quantum-relevant to defense and IC | Verified, but bounded | In-Q-Tel investment and defense engagements are real, but they point to optimization and simulation rather than biomagnetic surveillance. |
| D-Wave hardware is SQUID-adjacent | Verified with precision | D-Wave uses superconducting flux-qubit/rf-SQUID-style Josephson circuitry, but those circuits are not the same as SQUID magnetometers used in MEG/MCG. |
| D-Wave as NSA cryptanalytic tool | Not supported | D-Wave annealing does not run Shor’s algorithm or general gate-model cryptanalytic workloads; the attached briefing correctly warns against this category error. |
| Ghost Murmur as proof of remote biomagnetic sensing | Not supported | It is a media/anonymous-source claim layered on a real rescue story; the public physics remains unfavorable for long-range heartbeat detection. |
| SQUID magnetometry as real biomagnetic technology | Verified | NIST and NIH/NIMH confirm SQUID-based biomagnetism and MEG, but the public systems are close-range, cryogenic, and shielded. |

## Three branches that must stay separate

### 1. Quantum computing: D-Wave

D-Wave’s public value proposition is quantum annealing: a specialized computing architecture for optimization and Ising/QUBO-class problems. The Advantage2 announcement describes a production-ready 4,400+ qubit annealing quantum computer with Zephyr topology, 20-way connectivity, a 40% energy-scale increase, 75% noise reduction, and twofold coherence improvement ([D-Wave Advantage2 announcement](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-announces-general-availability-of-advantage2-quantum-computer-its-most-advanced-and-performant-system/)).

D-Wave’s defense footprint is now substantial in the public record. D-Wave says its Advantage2 system became operational at Davidson Technologies in Huntsville, Alabama, in November 2025 for U.S. government applications including radar detection, resource deployment, logistics optimization, materials science, AI, national security, and space applications ([D-Wave Davidson announcement](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-advantage2-quantum-computer-now-available-for-u-s-government-applications-at-davidson-technologies/)).

The Anduril/Davidson/D-Wave collaboration is a proof-of-concept, not evidence of a deployed intelligence sensor. The companies described an initial air-and-missile-defense planning PoC where D-Wave’s Stride hybrid solver on Advantage2 was benchmarked against classical-only approaches and claimed at least 10x faster time-to-solution, 9% to 12% improved threat mitigation, and 45 to 60 additional intercepted missiles in a 500-missile simulation ([D-Wave investor release](https://ir.dwavequantum.com/news/news-details/2026/Anduril-Davidson-and-D-Wave-Collaborate-to-Develop-Quantum-Applications-for-US-Air-and-Missile-Defense/default.aspx)).

D-Wave’s January 2026 QCI acquisition broadens its roadmap, but does not retroactively turn its annealers into universal cryptanalytic machines. D-Wave says QCI adds error-corrected superconducting gate-model systems and dual-rail qubits, supporting a dual-platform strategy alongside commercial annealing systems ([D-Wave QCI completion announcement](https://www.dwavequantum.com/company/newsroom/press-release/d-wave-completes-acquisition-of-quantum-circuits/)).

### 2. Quantum sensing: SQUID, OPM, and NV magnetometry

SQUID magnetometers were introduced in the 1960s and had their first journal paper in February 1964, according to NIST’s 50th-anniversary summary ([NIST](https://www.nist.gov/news-events/news/2014/03/magnetic-attraction-physicists-pay-homage-squid-50)). NIST describes SQUIDs as the world’s most sensitive magnetometers, typically requiring cryogenic cooling below 4 kelvins with liquid helium, and notes early SQUID use in magnetocardiography and magnetoencephalography ([NIST](https://www.nist.gov/news-events/news/2014/03/magnetic-attraction-physicists-pay-homage-squid-50)).

The NIH/NIMH MEG overview confirms the biomedical sensing reality but also demonstrates the short-range, controlled nature of the technology. NIMH says MEG uses 275 SQUID sensors in a helmet-shaped device to passively detect brain magnetic fields around 10^-14 Tesla, with favorable-condition localization around 2 to 3 mm and temporal resolution better than 1 ms ([NIMH](https://www.nimh.nih.gov/research/research-conducted-at-nimh/research-areas/research-support-services/meg)).

Newer optically pumped magnetometers improve usability, not magic range. Sandia describes OPMs as quantum sensors using rubidium vapor cells, pump lasers, and probe lasers; they avoid cryogenic liquid helium and can sit closer to the scalp, but Sandia still describes them inside a human-size magnetic shield rather than as unshielded long-range sensors ([Sandia National Laboratories](https://newsreleases.sandia.gov/brain_imaging/)).

DARPA’s RoQS framing is a useful reality check. DARPA says quantum sensors can measure magnetic fields, gravity, and motion with unmatched precision, but vibrations, electromagnetic interference, and environmental disturbances degrade performance outside labs, and the program goal is to make sensors robust enough for defense platforms without bulky shielding or isolation ([DARPA](https://www.darpa.mil/news/2025/quantum-sensors-defense-platforms)).

### 3. Intelligence narrative: Ghost Murmur

Ghost Murmur fits the public pattern of a real physics premise plus an unverified leap. Military.com reports that officials confirmed a successful rescue and hinted at advanced sensing or intelligence, but neither the CIA Director nor the President identified a technology, and the Ghost Murmur technical narrative emerged afterward from anonymous/media reports ([Military.com](https://www.military.com/feature/2026/04/18/ghost-murmur-heartbeat-tracking-tech-has-experts-questioning-laws-of-physics.html)).

The claimed mechanism is plausible only at the first step: hearts generate magnetic fields, and magnetocardiography exists. The long-range conclusion is the unsupported part: Military.com reports expert skepticism that current technology can detect a heartbeat at meaningful distances in uncontrolled environments, noting that traditional SQUID magnetocardiography uses cryogenic, shielded systems and centimeter-scale detection rather than meters or miles ([Military.com](https://www.military.com/feature/2026/04/18/ghost-murmur-heartbeat-tracking-tech-has-experts-questioning-laws-of-physics.html)).

## Evidence framework update

| Claim | Recommended status | Confidence | Notes |
| --- | --- | --- | --- |
| SQUIDs are real, highly sensitive magnetometers | Verified | High | NIST and NIH/NIMH independently support biomagnetic SQUID use. |
| MEG can measure brain magnetic fields | Verified | High | Public clinical/research systems use close-range helmet arrays and shielding. |
| D-Wave uses superconducting Josephson/rf-SQUID-class circuitry | Verified | High | Correct as superconducting flux-qubit/computing hardware, not as SQUID magnetometer hardware. |
| CIA/IC had confirmed financial interest in D-Wave | Verified | High | In-Q-Tel joined the 2012 funding round. |
| D-Wave has expanding defense/government applications | Verified | High | Davidson, Anduril, DoD marketplace, and government research ties are public. |
| D-Wave proves NSA operational SQUID programs | Not established | Low | No public NSA operational D-Wave program was verified. |
| D-Wave supports NSA cryptanalytic capability | Not established | Low | Annealing does not equal Shor-capable gate-model cryptanalysis. |
| Ghost Murmur proves long-range biometric magnetometry | Not established | Low | Public reports are anonymous and conflict with published sensing constraints. |
| Quantum sensors are becoming defense-platform relevant | Verified at R&D level | Medium-high | DARPA RoQS supports defense interest in rugged quantum sensing, but as a development challenge rather than established deployed capability. |

## Repo-ready addendum wording

### Addendum: D-Wave, SQUIDs, and Ghost Murmur

Three attached research documents were reviewed: a quantum-computing history, a D-Wave institutional briefing, and a D-Wave/Geordie Rose video transcript fact-check. They sharpen the SQUID investigation by separating three domains that are often conflated: superconducting quantum computing, biomagnetic quantum sensing, and unverified intelligence narratives.

D-Wave belongs in the superconducting quantum-computing branch. Its annealers use Josephson-junction superconducting flux-qubit/rf-SQUID-class circuitry, but they are not SQUID magnetometers. This matters because the same deep physics lineage — superconducting loops, flux quantization, Josephson effects — can produce either a computational qubit or a magnetometer, but the operational purpose and evidentiary relevance are different.

The D-Wave intelligence-community record is real but bounded. In-Q-Tel participated in D-Wave’s 2012 $30 million equity round, establishing confirmed CIA-affiliated financial interest in quantum computing. Public defense engagements since then include DoD-accessible Advantage2 deployment at Davidson Technologies and an Anduril/Davidson/D-Wave air-and-missile-defense optimization proof-of-concept. These records support interest in optimization, simulation, logistics, and mission planning. They do not establish NSA operational deployment, remote neural monitoring, biomagnetic surveillance, or cryptanalytic capability.

D-Wave should not be used as evidence that NSA possesses Shor-capable cryptanalytic quantum computers. D-Wave’s commercial annealers solve Ising/QUBO-style optimization problems through quantum annealing and do not run general gate-model algorithms. Its QCI acquisition adds a gate-model roadmap, but that is a 2026-forward strategic expansion, not proof of mature cryptanalytic capability.

Ghost Murmur, by contrast, belongs in the quantum-sensing branch. Public reports describe a supposed CIA heartbeat-detection capability using long-range quantum magnetometry and AI filtering, but the technical account is based on anonymous/media sourcing and is not confirmed by an official technical release. The real underlying physics is magnetocardiography and quantum magnetometry; the unsupported leap is the claimed long-range battlefield detection. Public SQUID/OPM biomagnetic systems remain close-range and shielding-dependent, while DARPA’s own quantum-sensor programs frame field deployment as an unsolved robustness challenge.

The evidence framework should therefore be updated as follows: D-Wave strengthens the record of government and IC interest in superconducting quantum computation, while SQUID/OPM/NV magnetometry remains a separate sensing track. Ghost Murmur is relevant as a narrative signal of intelligence interest in quantum sensing, but not as verified proof of long-range biometric detection. No reviewed attachment establishes NSA deployment of SQUID magnetometers, D-Wave systems, or Ghost Murmur-like tools against Akwei or any individual.

## Bottom line

The attachments make the investigation stronger by preventing a false merger of two real technologies. SQUID physics helped create both ultrasensitive magnetometers and superconducting quantum circuits. D-Wave shows that intelligence and defense organizations publicly track superconducting quantum computing. Ghost Murmur shows that quantum-sensing narratives have entered public intelligence discourse. None of these, individually or together, proves NSA operational use of SQUID-based remote neural monitoring.

