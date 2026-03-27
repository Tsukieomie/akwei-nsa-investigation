# Review: Clint McLean — Books, Code, and Claims

**Date:** March 27, 2026
**Subject:** Independent review of ClintMclean74's published work on Havana Syndrome and biological effects of RF

---

## Who Is Clint McLean?

**Stated credential:** Master's degree in Computer Science (AI, Neural Networks) — per his [paper on diplomat symptoms](https://invasaoecontrolemental.com.br/wp-content/uploads/2020/04/The-Science-of-Microwaves-Causing-the-Symptoms-of-the-Diplomats-in-Cuba-and-China_final_version.pdf). [LinkedIn](https://me.sh/profile/clint-mclean) lists background in Practical Management, Business Administration, and Film & Television.

**Affiliation:** "Mclean Research Institute" — this appears to be a self-created entity. The institute has no independent web presence beyond McLean's own publications. The books are self-published through it ([Google Books](https://books.google.com/books/about/Solving_Havana_Syndrome_and_Biological_E.html?id=6IP_zwEACAAJ)).

**Not a neuroscientist, physicist, or biomedical engineer.** His credential is in computer science with a focus on AI and neural networks — meaning he has competence in computational modeling but not in the biophysics, electrophysiology, or RF engineering that underpin his claims.

---

## The Published Works

### Book 1: "Solving Havana Syndrome and Biological Effects of RF Using the Hodgkin-Huxley Neuron Model" (2022)

- Publisher: Mclean Research Institute (self-published)
- ISBN: 0639720064 / 9780639720067
- Available on [Amazon](https://www.amazon.com/Solving-Syndrome-Biological-Effects-Hodgkin-Huxley-ebook/dp/B0BCNG8H89)
- Goodreads: [0 reviews, 0.0 average rating](https://www.goodreads.com/author/list/29455158.Clint_Mclean)
- No citations found in Google Scholar, PubMed, or any peer-reviewed journal

### Book 2: "Methods for Detecting Biology Affecting Electromagnetic Frequency Ranges Causing Havana Syndrome"

- Referenced in prior review context but not found on major book databases
- Appears to describe the SDR-based detection system

### Paper: "The Science of Microwaves Causing the Symptoms of the Diplomats in Cuba and China"

- Not peer-reviewed; hosted on a Brazilian website about "invasion and mental control"
- Self-published; no journal, no DOI, no peer review

---

## The GitHub Repositories

McLean maintains [five repositories](https://github.com/ClintMclean74) on GitHub:

| Repository | Stars | Forks | Purpose |
|---|---|---|---|
| [Hodgkin-HuxleyCode](https://github.com/ClintMclean74/Hodgkin-HuxleyCode) | 0 | 0 | Simulation code for Book 1 — models neurons using Hodgkin-Huxley equations with RF input |
| [SDRSpectrumAnalyzer](https://github.com/ClintMclean74/SDRSpectrumAnalyzer) | 13 | 4 | Original SDR-based spectrum analyzer for detecting RF |
| [SDRReradiationSpectrumAnalyzer](https://github.com/ClintMclean74/SDRReradiationSpectrumAnalyzer) | ? | ? | Advanced version designed to detect "reradiated frequency ranges" from human bodies |
| test | — | — | Test repository |
| ClintMclean74 | — | — | Profile config |

### Hodgkin-HuxleyCode

Written primarily in C (83.6%), with OpenGL visualization (freeglut, GLEW). 8 commits total. The code simulates Hodgkin-Huxley neuron dynamics with configurable parameters via text files in the `settings/` folder. Settings files correspond to experiments described in Book 1 (e.g., `nn_amplification_layer_activity_testing_6_31C.txt`).

The code is functional — it builds with CMake, runs on Windows and Linux, and produces visual output. However, the simulation is entirely computational; there is no interface to experimental data, no validation against real electrophysiology recordings, and no comparison to published results from other Hodgkin-Huxley implementations.

### SDRReradiationSpectrumAnalyzer

This is the most ambitious repository. It uses RTL-SDR dongles (cheap software-defined radio receivers) with GNU Radio to scan frequency ranges (e.g., 430-470 MHz) and detect what McLean calls "reradiated frequencies" — electromagnetic energy re-emitted by the human body at its resonant frequencies.

The system includes:
- Automated reradiated frequency detection
- Near/far series recording (to compare signals when a person is near vs. away from the antenna)
- 2D/3D visualization of FFT, strength, and waterfall graphs
- Session-based tracking of "strongest reradiated frequencies"

McLean provides a [user guide](https://drive.google.com/file/d/1GixkhAa6bBUuEGLTBrWXw7OFkZQBzuxV/view?usp=share_link) describing how to use this system to detect your own resonant frequency ranges.

---

## The Scientific Claims — Assessed

### Claim 1: Sub-thermal temperature increases affect neural signaling

**McLean's argument:** Temperature increases below 1°C (the level that causes the microwave auditory effect) also directly affect neuron membrane voltage by increasing Brownian motion of ions, which drives them through voltage-gated channels, altering neural signaling.

**Assessment: The concept has some basis, but the implementation is problematic.**

The Hodgkin-Huxley model is indeed temperature-sensitive — the original 1952 equations include Q10 temperature coefficients that scale rate constants. It is well-established that even small temperature changes affect ion channel kinetics. Published research in [Cognitive Neurodynamics](https://pmc.ncbi.nlm.nih.gov/articles/PMC9120336/) and [Frontiers in Neuroscience](https://pmc.ncbi.nlm.nih.gov/articles/PMC10590107/) has used Hodgkin-Huxley models to study electromagnetic effects on neural networks, and some papers do find that electromagnetic stimulation affects stochastic resonance in neuronal networks.

However, McLean's specific simulation — modeling ion movement in an extracellular-channel-intracellular space and showing that increased Brownian motion drives more ions through channels — is a simplified toy model, not a validated biophysical simulation. Peer-reviewed work in this area (e.g., the [Cognitive Neurodynamics paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9120336/) using 200-neuron Newman-Watts networks) uses far more sophisticated coupling models and accounts for factors McLean's simulation ignores: membrane capacitance dynamics, synaptic plasticity, gap junction coupling, and realistic noise sources.

**Verdict:** The direction of inquiry is legitimate. The execution is amateurish by academic standards.

### Claim 2: Human resonance enables individual targeting

**McLean's argument:** Each person's head has a unique electromagnetic resonant frequency (around 400-500 MHz for adults) determined by its physical dimensions. Transmitting at that frequency causes maximally strong electrical currents in that individual's brain, while others with different resonant frequencies are unaffected.

**Assessment: The resonance concept is real but drastically oversimplified.**

Human head resonance is documented. The ARRL Handbook (1992) states adult heads resonate around 400 MHz. Gandhi et al. (1978) studied head resonance and SAR distributions. This is real physics.

However, McLean treats this as if it provides precision targeting — that one person at 435 MHz and another at 442 MHz would be differentially affected. In practice, the Q factor (selectivity) of biological tissue resonance is extremely low because biological tissue is lossy. The resonance is broad, not sharp. This means the "targeting" McLean describes would not work with the specificity he claims. Two people standing next to each other would have largely overlapping absorption profiles, not cleanly separated ones.

**Verdict:** The underlying physics (resonance, differential SAR) is real. The precision targeting claim is not supported by the actual bandwidth of biological resonance.

### Claim 3: Reradiated electromagnetic energy can be detected with SDR equipment

**McLean's argument:** When you transmit at someone's resonant frequency, they re-emit electromagnetic energy at that frequency, which can be detected by a receiver. His SDR system purportedly detects these reradiated signals.

**Assessment: This is the most problematic claim.**

The concept of electromagnetic scattering/re-radiation from the human body is real — it's the basis of radar. But the signal levels McLean is trying to detect with a $20 RTL-SDR dongle are many orders of magnitude below what such equipment can resolve against background RF noise. The dynamic range and sensitivity of RTL-SDR receivers (typically 8-bit ADC, ~50 dB dynamic range) is inadequate for detecting the minute re-radiation differences between a person being present or absent at range.

McLean shows graphs (Figures 8-9 in his paper) comparing spectral returns with a person present vs. absent, claiming a peak at ~470.65 MHz. But he provides no control for: multipath reflections, environmental RF changes, temperature drift in the SDR, body-mass absorption effects (simply blocking signals, not resonant re-radiation), or the dozen other factors that would produce spectral changes when a large conductive object (a human body) enters the field.

The prior technical review noted: "No one has demonstrated detection of neural activity at distance — all experimental work uses contact or near-contact sensors." The field has "moved toward structural imaging (stroke detection) rather than functional neural activity detection, because structural dielectric contrasts are orders of magnitude larger than activity-dependent changes."

**Verdict:** The claim that $20 SDR equipment can detect individual human resonant frequencies is not credible by any published standard in RF engineering or biomedical sensing.

### Claim 4: The Hodgkin-Huxley simulation "solves" Havana Syndrome

**McLean's argument:** His simulation demonstrates that sub-thermal RF-induced temperature changes, when propagated through a neural network model, produce large-scale disruption of neurological patterns — representing a "paradigm shift" and "solving" the Havana Syndrome mystery.

**Assessment: This massively overstates what a simulation demonstrates.**

A simulation shows that if you change input parameters (temperature), output changes (neural firing patterns). This is unsurprising — the Hodgkin-Huxley model is explicitly temperature-dependent by design. The question is whether the specific parameter changes McLean models correspond to what actually happens in living brain tissue exposed to pulsed RF at realistic power levels, distances, and frequencies.

McLean provides no experimental validation against any real neural recording. His simulation has never been tested against in vitro or in vivo data. He does not compare his results to the dozens of published Hodgkin-Huxley electromagnetic coupling studies that already exist in the literature. He does not address the well-known limitations of single-compartment Hodgkin-Huxley models for predicting whole-brain effects.

The claim to have "solved" Havana Syndrome is extraordinary. The published scientific community — including David Relman's NAS panel, the DIA AAWSA program, INSCOM, and dozens of RF bioeffects researchers — has not reached consensus on the mechanism. A self-published simulation by a computer science master's student does not resolve what hundreds of specialists have not.

**Verdict:** The simulation is a competently coded implementation of well-known equations. It does not constitute a solution to Havana Syndrome.

---

## Where McLean Aligns with Verified Evidence

Despite the significant methodological problems, McLean's work touches on several concepts that our prior investigations have confirmed:

| McLean's Claim | What We Verified Independently |
|---|---|
| Pulsed microwaves produce auditory effects | Confirmed — Sharp/Grove 1974 at Walter Reed; Frey 1961 |
| RF can cause neurological symptoms at range | Confirmed — INSCOM 1998 report; DIA AAWSA 2009; Havana Syndrome cases |
| Human head has resonant frequencies ~400 MHz | Confirmed — ARRL Handbook; Gandhi et al. 1978 |
| Electromagnetic energy can be used as a weapon | Confirmed — captured Russian device 2024; 60 Minutes March 2026 |
| VGCC activation by electromagnetic fields | Confirmed — [Pall 2015](https://pmc.ncbi.nlm.nih.gov/articles/PMC10590107/) cited in Frontiers in Neuroscience; 26 studies showing EMF blocked by calcium channel blockers |
| The Hodgkin-Huxley model can be used to study EMF neural effects | Confirmed — [Cognitive Neurodynamics](https://pmc.ncbi.nlm.nih.gov/articles/PMC9120336/), [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S221509862500093X), and other published H-H/EMF studies exist |

McLean is not wrong about the general direction. He identified real phenomena, real physics, and a legitimate modeling approach. What he lacks is: peer review, experimental validation, proper controls, acknowledged limitations, and the disciplinary expertise to distinguish between what a simulation shows and what reality demonstrates.

---

## The Meta-Question: Does McLean's Work Advance Understanding?

McLean occupies an unusual position in the landscape we've been investigating. He is not a "targeted individual" making personal victimization claims. He is not a conspiracy theorist. He is a technically literate person who has identified a real scientific question and attempted to answer it using computational tools within his competence.

His work suffers from the classic problems of independent research conducted outside institutional frameworks: no peer review, no collaboration with domain experts (RF engineers, electrophysiologists, neuroscientists), no experimental validation, and overclaiming results. But the underlying question — how does sub-thermal pulsed RF affect neural signaling? — is a legitimate open question that the mainstream scientific community is also working on, as evidenced by the published H-H/EMF studies in Cognitive Neurodynamics and Frontiers in Neuroscience.

**Where McLean adds value:** He has produced open-source code that implements H-H neural models with RF coupling parameters, which anyone can examine and modify. He has built functional SDR-based tools for spectral analysis. He has synthesized a wide range of published research (Frey, Gandhi, Pall, Sharp, Jaski) into a coherent narrative.

**Where McLean falls short:** He has not submitted his work to peer review. His detection claims are not credible. His "solving" of Havana Syndrome massively overstates what his simulation demonstrates. His paper is hosted on conspiracy-adjacent websites rather than scientific archives (arXiv, bioRxiv, etc.). His self-created "Research Institute" lacks institutional legitimacy.

---

## Bottom Line

McLean is a self-taught researcher who has correctly identified several real phenomena in RF bioeffects and attempted to model them computationally. His work is more technically grounded than the typical "targeted individual" material — he cites real papers, uses real equations, and produces functional code. But it has not been peer-reviewed, experimentally validated, or recognized by the scientific community. The claim to have "solved" Havana Syndrome is not supported. The SDR detection claims are not credible.

His work is best understood as a technically informed hypothesis that needs institutional-grade testing — not as a finished scientific contribution.

---

## Sources

- [GitHub: ClintMclean74/Hodgkin-HuxleyCode](https://github.com/ClintMclean74/Hodgkin-HuxleyCode)
- [GitHub: ClintMclean74/SDRReradiationSpectrumAnalyzer](https://github.com/ClintMclean74/SDRReradiationSpectrumAnalyzer)
- [GitHub: ClintMclean74 profile](https://github.com/ClintMclean74)
- [McLean Research Institute — Book page](https://mcleanresearchinstitute.com/solving_havana_syndrome.htm)
- [Google Books — Book listing](https://books.google.com/books/about/Solving_Havana_Syndrome_and_Biological_E.html?id=6IP_zwEACAAJ)
- [Goodreads — Author page](https://www.goodreads.com/author/list/29455158.Clint_Mclean)
- [McLean paper — "The Science of Microwaves Causing the Symptoms of the Diplomats in Cuba and China"](https://invasaoecontrolemental.com.br/wp-content/uploads/2020/04/The-Science-of-Microwaves-Causing-the-Symptoms-of-the-Diplomats-in-Cuba-and-China_final_version.pdf)
- [Effects of magnetic fields on stochastic resonance in Hodgkin-Huxley neuronal network (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC9120336/)
- [System-level biological effects of ELF-EMFs (PMC)](https://pmc.ncbi.nlm.nih.gov/articles/PMC10590107/)
- [Complex latency dynamics of H-H neuron under electromagnetic induction (ScienceDirect)](https://www.sciencedirect.com/science/article/pii/S221509862500093X)
- [FEDweek comment by McLean](https://www.fedweek.com/fedweek/effects-of-havana-syndrome-are-clear-even-though-cause-isnt-says-gao/)
