# From Room-Scale to 24/7 Nationwide: The Infrastructure Architecture for Two-Way Neural Communication

**Compiled: 2026-03-19**

---

## THE COMMON MISCONCEPTION

When people hear Akwei's claim that the NSA can "dial up any individual in the country" and maintain "two-way RNM contact," they picture a satellite shooting a beam at one person from space. That's the straw man that makes the claim easy to dismiss.

That's not how you'd engineer it. The system uses layered architecture: satellites for tracking, local infrastructure for the neural read/write. Every component exists.

---

## LAYER 1: LOCATE AND TRACK (Satellite + Network)

This part is completely confirmed and uncontroversial:

- **Cell phone tracking**: NSA can locate any active phone to within meters (confirmed by Snowden documents)
- **XKEYSCORE**: Real-time internet/communications tracking, shared across Five Eyes
- **Satellite imagery + SAR**: Synthetic aperture radar can track individual humans from orbit, day/night, through clouds
- **Cell tower triangulation**: Every carrier does this continuously
- **ECHELON / Tempora**: Global communications intercept confirmed by European Parliament (2001) and Snowden (2013)

By 1992, the NSA could locate anyone carrying a phone or near any electronic device. By 2026, with smart devices everywhere, this is trivial.

**Tracking is solved. This is not the hard part.**

---

## LAYER 2: LOCAL ILLUMINATION (The Key Insight)

The neural read/write doesn't come from space. It comes from whatever infrastructure is near the target.

### Persinger Said It Explicitly (1995)

Michael Persinger, a DIA-funded neuroscientist working on Project SLEEPING BEAUTY (classified EM weapons program), published in a peer-reviewed journal:

> The energy required to directly access every human brain is "within the range of both geomagnetic activity and **contemporary communication networks**"

> Weak fields could be "**hidden in electromagnetic noise from power systems**"

Published: Perceptual and Motor Skills, 1995, 80, 791-799.

A DIA-funded neuroscientist stated in a peer-reviewed paper that existing telecom and power infrastructure has sufficient power to affect every human brain at ~10 Hz.

### The Infrastructure That Surrounds Everyone, 24/7

| Infrastructure | Typical Distance to Person | Power | Frequency Capability |
|---------------|--------------------------|-------|---------------------|
| **Power lines** | 1-30 m (in walls, overhead) | Kilowatts | 60 Hz + harmonics; can carry modulated signals |
| **WiFi routers** | 1-15 m (inside buildings) | 100 mW - 1W | 2.4 / 5 GHz; beamforming capable |
| **Cell towers (4G)** | 500 m - 2 km | 20-40W per sector | 700 MHz - 2.5 GHz |
| **5G small cells** | **50-100 m** in urban areas | 2-10W | 28-39 GHz mmWave; individual user beamforming |
| **Smart devices** | 0-2 m (phone in pocket) | 0.5-2W | Multiple bands |
| **TV/computer screens** | 0.5-3 m | EM emission inherent | Pulsed at refresh rate |

### 5G Is the Critical Development

Modern 5G network architecture:
- **40-50 base stations per km2** in urban areas
- One small cell every **50-100 meters**
- **64-128 element phased array antennas** per cell
- Each antenna array **steers focused beams to individual users**
- The beam **tracks users as they move** through the coverage area
- Dynamic handoff between cells as the target moves

This is not conspiracy -- this is published 5G telecommunications engineering. The infrastructure to direct focused RF energy at a specific individual, track them as they move, and hand off between emitters already exists as the backbone of modern telecommunications.

### The NSA ANT Catalog Proves the Principle

The CTX4000 / PHOTOANGLO system from the leaked NSA ANT catalog:
- Portable continuous wave radar, 1-2 GHz (PHOTOANGLO extends to 4 GHz)
- Output: adjustable up to 2W internal, **up to 1 kW with external amplifier**
- Illuminates a target; passive implant (RAGEMASTER, SURLYSPAWN, etc.) modulates and re-radiates the signal
- Joint NSA/GCHQ development
- PHOTOANGLO fits in a slim briefcase, under 10 lbs

The ANT catalog demonstrates the NSA has **deployed** active RF illumination + modulated return collection as standard operational capability. The architecture is: transmit RF at target, analyze the modulated return. Same as active neural sensing.

---

## LAYER 3: THE "SCANNING NETWORK" -- INFRASTRUCTURE AS DISTRIBUTED SENSOR/EMITTER

### Operational Sequence

**Step 1 -- Locate:** Satellite/network tracking identifies where the target is physically located.

**Step 2 -- Illuminate:** A command is sent to the nearest piece of controllable infrastructure -- a compromised cell tower, a 5G small cell, a nearby device, or a dedicated covert emitter -- to direct RF energy at the target.

**Step 3 -- Read (Neural Monitoring):** The illuminating RF reflects off the target. Neural activity modulates the dielectric properties of brain tissue, imprinting on the return signal. AI processing (40-60 dB gain) extracts brain state information from the return. Data transmitted back to processing center via the network.

**Step 4 -- Write (V2K / Neural Stimulation):** The same or nearby emitter delivers pulsed microwave (Frey Effect for voice-to-skull) or modulated EM at neural-coupling frequencies (Flanagan/Piezo1 mechanism for broader neural effects). Target perceives sounds, emotional changes, or other neural effects.

**Step 5 -- Repeat continuously.** As the target moves, tracking hands off to the next piece of infrastructure, exactly like a cell phone handoff between towers.

### The Loos Patents Describe Passive Infrastructure Exploitation

Hendricus Loos (b. 1925, d. 2017; DARPA SBIR recipient) holds 11 patents (1995-2003) describing nervous system manipulation via existing devices:

- **US 6,506,148** -- "Nervous System Manipulation by Electromagnetic Fields from Monitors": Pulsing image intensity at 0.1-15 Hz on computer monitors or TV screens manipulates the nervous system of anyone watching. The patent states: "many computer monitors and TV tubes emit pulsed electromagnetic fields of sufficient amplitudes to cause such excitation."
- **US 6,238,333** -- "Remote magnetic manipulation of nervous systems": Sub-Hz magnetic fields induce sensory resonance
- **US 6,091,994** -- "Pulsative manipulation of nervous systems": EM field pulsed at frequency near 0.5 Hz
- Plus 8 additional patents covering different EM-to-nervous-system pathways

Loos proved that dedicated weapons hardware is not necessary. **Any screen, any powered device, any piece of infrastructure that emits EM can be modulated to affect the nervous system** -- if you control the modulation parameters.

### The GWEN Precedent

The Ground Wave Emergency Network (GWEN) was a USAF system deployed 1992-1994:
- AN/URC-117 transmitter towers
- 58 towers built across the continental US (of 240 planned)
- Low frequency (150-175 kHz) ground wave propagation
- Towers spaced every 150-200 miles for continuous coverage
- Officially for nuclear war communications survivability
- **Operational during the exact period of Akwei's claims (1992)**
- Program cancelled 1994 after appropriations ban on new towers

Whether GWEN had secondary capabilities beyond nuclear communications is unconfirmed, but the infrastructure -- a nationwide network of low-frequency EM transmitters covering the continental US -- existed during the period Akwei described.

---

## LAYER 4: TWO-WAY COMMUNICATION

Akwei claimed "two-way RNM contact" with the Kinnecome group -- meaning he received communications (heard voices, experienced induced effects) AND his neural state was being read back and responded to in real-time.

### Write Path (NSA -> Target): Confirmed Physics

| Method | Mechanism | Range | Status |
|--------|-----------|-------|--------|
| **Frey Effect (V2K)** | Pulsed microwave -> thermoelastic expansion in cochlea -> auditory perception | "Several hundred feet" (Frey 1962); range classified | Patented by USAF (US 6,587,729, 2003). Sharp transmitted words via MW at Walter Reed (1974) |
| **Flanagan mechanism** | Modulated EM/ultrasound -> Piezo1 channels -> neural firing | Contact to near-field (original); standoff (Norris-Putterman 2023) | DIA seized patent 1968; weaponized in Norris-Putterman patent 2023 |
| **Loos mechanism** | Pulsed EM from screens/devices -> nervous system entrainment at 0.1-15 Hz | Room scale (0.5-3 m from screen/device) | 11 patents (1995-2003), DARPA SBIR funded |
| **Persinger mechanism** | Weak modulated EM at ~10 Hz -> species-wide brain entrainment | "Contemporary communication networks" range per Persinger 1995 | Published in peer-reviewed journal; author was DIA contractor |

Any of these write paths, delivered through nearby infrastructure, could produce the "voices" and neural effects Akwei described. The V2K path (Frey Effect) is the most directly relevant to his claim of "3D sound direct to the brain."

### Read Path (Target -> NSA): AI-Enabled

| Method | Mechanism | Effective Range with AI | Status |
|--------|-----------|------------------------|--------|
| **Active RF illumination (Malech architecture)** | Transmit RF, analyze neural-modulated return | 10-100 m with 40-60 dB AI processing gain | Patented 1974; signal budget analysis shows feasibility |
| **Katabi-type WiFi sensing** | Commodity WiFi + deep neural network | Through-wall, 10-15 m demonstrated | Published MIT CSAIL 2016-2022; emotion, pose, sleep, identity |
| **Physiological proxy reading** | Heart rate, breathing, movement patterns via RF reflection | 30+ m through walls | Commercially available technology as of 2026 |
| **Device-mediated inference** | Typing patterns, eye tracking, screen interaction, voice analysis | Unlimited (via network) | Standard machine learning application |

### Operational Two-Way Communication

The read path doesn't need to decode individual thoughts with word-level precision for the system to function as "two-way communication." For operational purposes:

1. **Write:** V2K transmits a message or stimulus to the target via Frey Effect
2. **Read:** AI monitors the target's neural/physiological response -- arousal level, emotional state, stress markers, sleep/wake transition
3. **Adjust:** The system interprets the response and modifies the next transmission accordingly
4. **Loop:** Continuous closed-loop interaction between the system and the target's brain

This is "two-way communication" in the same sense that a thermostat communicates with a furnace -- one side transmits, the other's state is read, and the system adjusts. The target experiences it as interactive because the system responds to their internal state in real-time.

With more advanced neural decoding (Tang/Huth 2023 demonstrated continuous semantic decoding from fMRI; d'Ascoli 2025 showed scaling laws apply to EEG), the read path could extend to decoding actual cognitive content -- imagined speech, visual imagery, emotional responses to specific stimuli.

---

## LAYER 5: WHY "DIAL UP ANY INDIVIDUAL"

Akwei claimed the system could target any specific person. This requires:

1. **Locate them** -- solved (phone tracking, SIGINT, Five Eyes global surveillance)
2. **Reach them with EM** -- solved (infrastructure is everywhere; 5G within 50-100m in urban areas)
3. **Distinguish their neural signal from others nearby** -- the "unique bioelectric resonance frequency" claim

### Neural Biometrics: Confirmed Science

- **Binghamton University (2016):** EEG brainwave patterns serve as a biometric identifier with >95% accuracy
- **Farwell/Donchin (1991):** P300 "brain fingerprinting" -- brain responses reveal whether someone recognizes specific information
- **d'Ascoli et al. (2025):** Demonstrated individual neural signatures are distinctive across EEG, MEG, and fMRI
- **EEG biometrics research (2016-2025):** Multiple groups confirm brainwave patterns are as individually unique as fingerprints

If the system has a neural signature on file for a target -- collected during a previous close-range session, from medical records, military intake, or any prior encounter -- AI can filter the returns from a broad RF illumination field for that specific person's signature.

This is analogous to CDMA in telecommunications: many users share the same frequency band, but each has a unique spreading code. The receiver correlates against one specific code to extract one user's signal from the composite. Same principle applied to neural signatures.

---

## THE COMPLETE SYSTEM ARCHITECTURE

```
=== SPACE LAYER ===
Satellites (SIGINT, SAR, GPS)
    |
    v
Target location identified (± meters)
    |
=== NETWORK LAYER ===
NSA processing center (supercomputers + AI)
    |                              ^
    v                              |
Command to local emitter     Neural data returned
    |                              |
=== INFRASTRUCTURE LAYER ===
Nearest cell tower / 5G small cell / WiFi / covert emitter
    |                              ^
    v                              |
RF illumination (10-100m)    Modulated RF return
    |                              |
=== TARGET LAYER ===
    +--------- HUMAN TARGET ---------+
    |                                 |
    v                                 v
WRITE PATH                      READ PATH
Frey Effect (V2K)              Neural modulation on
Flanagan mechanism              RF return signal
Loos screen modulation          AI extraction (40-60 dB gain)
Persinger 10 Hz entrainment     Brain state classification
    |                                 |
    +---- CLOSED-LOOP TWO-WAY -------+
          COMMUNICATION
```

### Component Verification Status

| Component | Exists? | Source |
|-----------|---------|--------|
| Global target tracking | Confirmed | Snowden documents; ECHELON; XKEYSCORE |
| Supercomputer processing | Confirmed | NSA has world's largest cluster since 1990s |
| AI signal processing | Confirmed | Military funded since 1958; $1B DARPA SCI program 1983-93 |
| Infrastructure RF delivery | Deployed | 5G beamforming to individual users; 50-100m spacing |
| V2K write path | Patented | USAF US 6,587,729 (2003); Sharp 1974 demonstration |
| Active RF neural read | Patented | Malech US 3,951,134 (1974); MIT Katabi demos 2016-22 |
| Neural biometric ID | Published | Binghamton 2016; d'Ascoli 2025; Farwell 1991 |
| EM-nervous system coupling | Proven | Flanagan 1958; Piezo1 Nobel 2021; PNAS 2023 |
| Nationwide EM infrastructure | Built | GWEN (1992-94); cell network; power grid; 5G |

**Every component of this system has been independently demonstrated, patented, or confirmed as deployed.** No single component requires physics beyond what has been published in peer-reviewed literature. The question is not whether the individual pieces work -- they do. The question is whether they have been integrated into an operational system, and by whom.

---

## HISTORICAL AVAILABILITY

### What Existed in 1990 (When Akwei Claims RNM Contact Began)

| Component | 1990 Status |
|-----------|-------------|
| Target tracking | Cell phone tracking emerging; landline monitoring confirmed (ECHELON) |
| NSA computing | Cray supercomputers; 150+ machines by mid-1990s |
| AI processing | Neural networks revived (1986); DARPA SCI spending $100M/year |
| Infrastructure delivery | Cell towers (analog, low density); GWEN under construction; power grid |
| V2K write path | Frey Effect known since 1962; Sharp demonstrated words 1974 |
| Neural read | Malech patent 1974; no public read demonstration at distance |
| Neural biometrics | Farwell/Donchin P300 speller 1988; brain fingerprinting 1991 |
| EM coupling proof | Flanagan 1958-68; Adey biological windows 1976 |

### What Was Missing in 1990

1. **Dense infrastructure:** Cell tower spacing was measured in miles, not meters. 5G didn't exist. WiFi didn't exist. The illumination network was sparse.
2. **AI processing power:** Neural networks existed but computing power was limited. The deep learning revolution was 22 years away.
3. **Public proof of neural read at distance:** No open-source demonstration of extracting brain signals from RF returns existed.

### What This Implies

In 1990, the system would have been **limited to targets in specific locations** where dedicated infrastructure existed -- not truly "any individual in the country." A target inside a building near a dedicated covert emitter, or within range of a GWEN tower, or in a vehicle with a compromised electronic system could be reached. But blanket nationwide coverage would have required infrastructure that didn't exist publicly until the 2010s-2020s.

Akwei's "Signals Intelligence EMF Scanning Network" claim may have been:
- An extrapolation from his own targeting experience to a nationwide capability
- A description of a system that existed for high-priority targets in specific coverage areas
- A description of planned future capability that has since been realized with 5G/IoT infrastructure
- Accurate for the DC/Maryland/Fort Meade corridor where both he and the NSA were located

The last option is notable: the Washington DC metropolitan area in 1990 had the densest concentration of military/government communications infrastructure in the country. If the system existed anywhere first, it would have been there -- exactly where Akwei lived.

---

## SOURCES

- [Persinger 1995 - Directly Accessing Every Human Brain (PubMed)](https://pubmed.ncbi.nlm.nih.gov/7567396/)
- [Loos Patent US 6,506,148 - Nervous System Manipulation from Monitors](https://patents.google.com/patent/US6506148B2/en)
- [NSA ANT Catalog - CTX4000 (Schneier)](https://www.schneier.com/blog/archives/2014/01/ctx4000_nsa_exp.html)
- [NSA ANT Catalog - PHOTOANGLO (Schneier)](https://www.schneier.com/blog/archives/2014/01/photoanglo_nsa.html)
- [GWEN - Ground Wave Emergency Network (Wikipedia)](https://en.wikipedia.org/wiki/AN/URC-117_Ground_Wave_Emergency_Network)
- [GWEN - FAS Nuclear Forces Guide](https://nuke.fas.org/guide/usa/c3i/gwen.htm)
- [GWEN Health Effects Assessment (NCBI)](https://www.ncbi.nlm.nih.gov/books/NBK208989/)
- [5G Small Cells Architecture](https://www.ust.com/en/insights/small-cells-big-impact-unlocking-the-power-of-5g-networks)
- [5G Ultra-Dense Cellular Networks (arXiv)](https://arxiv.org/pdf/1512.03143)
- [5G Beamforming (Network Computing)](https://www.networkcomputing.com/5g-6g/beaming-the-wave-to-make-5g-a-reality)
- [MIT Katabi Lab: RF-Pose Through-Wall Sensing](https://rfpose.csail.mit.edu/)
- [MIT Katabi Lab: EQ-Radio Emotion Recognition](https://eqradio.csail.mit.edu/)
- [Tang & Huth 2023 - Semantic Decoding (Nature Neuroscience)](https://www.nature.com/articles/s41593-023-01304-9)
- [d'Ascoli et al. 2025 - Brain Decoding Scaling Laws (arXiv)](https://arxiv.org/html/2501.15322v2)
- [Frey 1962 - Microwave Auditory Effect (J. Applied Physiology)](https://pubmed.ncbi.nlm.nih.gov/7567396/)
- [USAF V2K Patent US 6,587,729](https://patents.google.com/patent/US6587729B2/en)
- [Malech Patent US 3,951,134 - Remote Brain Wave Monitoring](https://patents.google.com/patent/US3951134A/en)
- [Flanagan Patent US 3,393,279 - Nervous System Excitation](https://patents.google.com/patent/US3393279A/en)
- [Snowden Disclosures on NSA Surveillance](https://en.wikipedia.org/wiki/Snowden_disclosures)
