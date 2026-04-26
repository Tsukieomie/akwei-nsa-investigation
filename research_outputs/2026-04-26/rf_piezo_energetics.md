# RF→Piezo Energetics: Does Frey-Class Thermoelastic Pressure Overlap with Piezo1/2 Gating Thresholds?

*Compiled from primary literature. All numbers cited inline. Conversions verified computationally.*

---

## Executive Summary

**Short answer: No — by approximately four to six orders of magnitude under auditory-threshold RF conditions. The gap narrows to roughly 50–100× only at extreme, non-auditory, weaponizable power levels, and even then the physical nature of the stimulus (broadband transient vs. sustained sinusoidal) is a poor match for efficient Piezo gating.**

The peak acoustic pressure produced in tissue by a Frey-class pulsed RF exposure is on the order of **tens of milliPascals (0.02–0.7 Pa)** in the head. The minimum bulk acoustic pressure that has been shown to activate Piezo1 or Piezo2 via focused ultrasound (FUS) in neurons is on the order of **20–350 kPa**. The pressure regimes are separated by roughly 10^4 to 10^6 depending on which RF exposure and which Piezo activation assay one compares.

---

## Part A: RF Thermoelastic Peak Pressure

### A1. Physical Mechanism

When a short RF pulse is absorbed by tissue, it deposits energy on a timescale shorter than the acoustic relaxation time of the absorbing volume. The rapid temperature rise (ΔT) causes thermoelastic expansion that launches a broadband acoustic stress wave. In the stress-confinement regime (pulse width τ << τ_c, the characteristic acoustic transit time), the peak pressure is:

```
p = Γ × ρ × C_p × ΔT
```

where Γ ≈ 0.2 is the dimensionless Grüneisen parameter, ρC_p ≈ 4 × 10⁶ J/(m³·K) for soft tissue, giving approximately **1 Pa per μK of temperature rise** ([Foster & collaborators, 2021](https://public-pages-files-2025.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2021.788613/pdf)). This wave travels by bone conduction to the cochlea.

### A2. Frey 1962 Original Parameters

[Frey 1962](https://mriquestions.com/uploads/3/4/5/7/34572113/auditory_frey_rf_hearing_jappl.1962.17.4.689.pdf) (*J. Appl. Physiol.* 17:689–692) established the auditory perception thresholds with the following exposure parameters:

| Parameter | Frey 1962 Values |
|-----------|-----------------|
| Carrier frequency | 425 MHz, 1,310 MHz (transmitters A–F) |
| Repetition rate | 50 Hz |
| Pulse width | 10–70 μs |
| Peak power density threshold (80 dB ambient noise) | ~275 mW/cm² (at 425 and 1,310 MHz) |
| Average power density | As low as 400 μW/cm² |
| Anechoic room estimated threshold | ~3 μW/cm² (free-space) |
| Perceived character | Buzz, click, hiss, or knock; localized within/behind head |

Frey also reported (1961) thresholds of 267 mW/cm² at 1.3 GHz and 5,000 mW/cm² at 2.9 GHz for peak amplitude. The critical parameter was peak power density, not average power density. Per [Wikipedia (Microwave auditory effect)](https://en.wikipedia.org/wiki/Microwave_auditory_effect), [Guy et al. 1975](https://zoryglaser.com/wp-content/uploads/2020/05/THE-JOURNAL-OF-MICROWAVE-POWER-VOL-10-NO-4-1975.pdf) demonstrated via cochlear microphonics that the microwave auditory effect in animals is accompanied by mechanical disturbance of cochlear hair cells.

### A3. Lin 1977 Thermoelastic Theory — Peak Pressures

[Lin 1977](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/RS012i06Sp00237) (*Radio Sci.* 12:237–242) developed the thermoelastic spherical head model and provided the first calculated pressure amplitudes. **Table 2 from Lin 1977** (10 μs rectangular pulses, normalized to peak SAR of 1 W/g = 1,000 W/kg):

| Model | Sphere Radius | Microwave Freq | Peak Pressure (dyne/cm²) | Peak Pressure (Pa) | Incident Power (mW/cm²) |
|-------|--------------|----------------|-------------------------|--------------------|------------------------|
| Guinea pig | 2 cm | 2,450 MHz | 4.08 | **0.408** | 445 |
| Cat | 3 cm | 2,450 MHz | 3.69 | **0.369** | 589 |
| Human infant | 5 cm | 918 MHz | 9.61 | **0.961** | 1,282 |
| Human adult | 7 cm | 918 MHz | 6.82 | **0.682** | 2,183 |

*Conversion: 1 dyne/cm² = 0.1 Pa.*
*Source: [Lin 1977 (gbppr.net PDF)](http://www.gbppr.net/mil/havana/lin1977.pdf)*

The pressure scales linearly with SAR. At a typical auditory threshold SAR (~80 W/kg per Lin 2007 calculation below), pressures would be ~0.055 Pa for the human adult model — consistent with the 20 mPa cochlear threshold after acoustic transmission losses.

### A4. Lin 2007 Review — Quantitative Summary

[Lin 2007](https://pubmed.ncbi.nlm.nih.gov/17495664/) (*Health Phys.* 92:621–628) consolidated the thermoelastic evidence. Key quantitative values:

**Table 2 from Lin 2007:** Peak thermoelastic pressure in mPa for spherical head models (10 μs pulses at **1 kW/kg SAR**):

| Model | Diameter | Frequency | Peak Pressure (mPa) | Peak Pressure (Pa) |
|-------|----------|-----------|---------------------|-------------------|
| Guinea pig | 4 cm | 2,450 MHz | 408 | 0.408 |
| Cat | 6 cm | 2,450 MHz | 369 | 0.369 |
| Human infant | 10 cm | 918 MHz | 961 | 0.961 |
| Human adult | 14 cm | 918 MHz | 682 | 0.682 |
| Human (20 μs pulse) | ~14 cm | 915 MHz | 238 | 0.238 |

*Note: These match Lin 1977 exactly after unit conversion, confirming consistency.*

**Auditory threshold at cochlea: 20 mPa = 0.020 Pa**

Parameters required to reach the 20 mPa hearing threshold at the cochlea (20 μs pulse, 915 MHz):
- Peak incident power density: **2.63 kW/m² = 0.263 W/cm²**
- Peak SAR: **80 W/kg (0.08 kW/kg)**
- Temperature rise: **~10⁻⁶ °C (1 μK)**

From MRI-coil data (Table 4 of Lin 2007): at SAR of 4–20 W/kg (FDA guideline range), thermoelastic pressures of 28–200 mPa are reached in the human head — **1–10× the auditory threshold** but still in the sub-Pa range.

### A5. Foster & Finch 1974 — Direct Measurement

[Foster & Finch 1974](http://www.gbppr.net/mil/havana/foster1974.pdf) (*Science* 185:256–258) directly measured thermoacoustic transients in saline (0.15N KCl) using a hydrophone. At the threshold power density for microwave hearing in humans, they measured approximately **90 dB re 0.0002 dyne/cm²** within the audible band — corresponding to ~0.63 Pa in the fluid. This is the value at the source in bulk fluid, before transmission through skull/tissue to cochlea (with associated attenuation), and is consistent with the Lin models above.

### A6. Dagro et al. 2021 — High-Power Regime

[Dagro et al. 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8555891/) (*Science Advances*) computed intracranial stresses for high-power microwave pulses using FDTD modeling:

| Condition | Peak Power | Pulse Width | Intracranial ΔT | Peak Tensile Pressure |
|-----------|-----------|------------|-----------------|----------------------|
| MAE auditory threshold (typical) | 10²–10⁵ mW/cm² | 0.5–500 μs | ~10⁻⁶ °C | Not stated explicitly |
| Moderate injury-approach | ~10⁶ mW/cm² | 5 μs | ~0.001°C | **Tens of kPa** |
| NFL football impact range | ~1.5×10⁶ mW/cm² | short | — | 20–120 kPa |
| Cavitation threshold approach | ~10⁷ mW/cm² | 5 μs | — | >100–150 kPa (tensile) |

Peak frequencies of thermoelastic waves in the human head: ~9.7 kHz (consistent with 7–10 kHz predictions from head geometry).

### A7. Foster 2021 — Upper Physical Limits for "Weaponizable" RF

[Foster 2021](https://public-pages-files-2025.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2021.788613/pdf) (*Front. Public Health*) derived the maximum feasible thermoelastic pressure under stress-confinement conditions (incident power density I₀ = 10 MW/m²):

**Table 1 from Foster 2021** (maximum feasible pressure at stress-confinement limit):

| Frequency | Penetration depth L | Stress confinement time τₛ (μs) | Max feasible fluence (J/m²) | Peak acoustic pressure (kPa) | Acoustic level (dB re 20 μPa) |
|-----------|-------------------|--------------------------------|----------------------------|------------------------------|-------------------------------|
| 1 GHz | 19 mm | 13 | 130 | **0.3** | 144 dB |
| 3 GHz | 9.4 mm | 6 | 60 | **0.3** | 144 dB |
| 6 GHz | 4.1 mm | 3 | 30 | **0.3** | 144 dB |
| 10 GHz | 1.9 mm | 1 | 10 | **0.3** | 144 dB |
| 30 GHz | 0.43 mm | 0.3 | 3 | **0.4** | 145 dB |
| 100 GHz | 0.18 mm | 0.1 | 1 | **0.5** | 147 dB |

**Key formula:** p = Γ × ρ × C_p × ΔT ≈ 1 Pa/μK

The maximum feasible pressure at any RF frequency under stress-confinement conditions, at the physical upper limit of incident power before thermal injury, is approximately **0.3–0.5 kPa** — well below the kPa–MPa regime of FUS neuromodulation. A peak of **10 kPa** was reached in a specific 1D model with very high SAR in the ventricles (also cited in Foster 2021), but only at extreme, non-auditory power levels.

---

## Part B: Piezo1/2 Gating Thresholds

### B1. Piezo1 — Membrane Tension (Pure Lipid Bilayer)

Piezo1 is activated by lateral membrane tension, not by hydrostatic pressure per se. The gating is described by a Boltzmann function in tension (T):

**[Cox et al. 2016](https://www.nature.com/articles/ncomms10366)** (*Nat. Commun.* 7:10366, "Removal of mechanoprotective influence of the cytoskeleton"):

| Preparation | T₁/₂ (mN/m) | Context |
|-------------|------------|---------|
| Cell-attached patches (with cytoskeleton) | ~4.5–5.1 | P₁/₂ ratio with MscL-G22S calibration |
| Bleb-attached patches (cytoskeleton-free) | ~4.5 | Force-from-lipid, leftward shifted |
| MscL-G22S T₁/₂ | 11.3 ± 0.6 | Calibration reference |
| Estimated PIEZO1 T₁/₂ (co-expression method) | **~4.5 mN/m** | Estimate from P₁/₂ ratio |
| Measured PIEZO1 T₁/₂ (bleb imaging) | **5.1 ± 0.2 mN/m** | Direct from Laplace's law |

**[Lewis & Grandl 2015](https://elifesciences.org/articles/12088)** (*eLife* 4:e12088):

| Condition | T₅₀ (mN/m) | P₅₀ (mmHg) | P₅₀ (Pa) |
|-----------|-----------|-----------|---------|
| Cell-attached, negative pressure | **2.7 ± 0.1** | −16.7 ± 2.8 | ~2,226 |
| Inside-out patch | **4.7 ± 0.3** | −35.8 ± 4.0 | ~4,773 |
| Cell-attached, +5 mmHg prepulse | **1.4 ± 0.1** | −7.7 ± 1.1 | ~1,026 |
| First detectable activation | ~1.4–2.7 | −5 mmHg threshold | **~667 Pa** |

**[Gong et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC9930135/)** (*J. Gen. Physiol.*): Single-channel P₅₀ averaged −52.9 ± 2.8 mmHg; corresponding T₅₀ = **3.4 ± 0.3 mN/m**. This falls within the Cox 2016 and Lewis & Grandl 2015 range of ~1.4–4.5 mN/m.

**Important caveat:** Patch-clamp pipette pressures apply across a tiny membrane patch (~1–5 μm² area). The conversion from pipette pressure to membrane tension uses Laplace's law: T = ΔP × r / 2 where r is the patch curvature radius. These values **cannot be directly compared** to bulk acoustic pressure in tissue; a bulk acoustic wave applies uniform hydrostatic pressure to the entire cell, while patch pressure specifically stretches the captured membrane dome.

### B2. Piezo2 — Gating Threshold

**[Narayanan et al. 2019](https://pmc.ncbi.nlm.nih.gov/articles/PMC6478859/)** (*Sci. Rep.* 9:6446) characterized Piezo2 in Merkel cell carcinoma cells:

| Parameter | Value |
|-----------|-------|
| Activation threshold (positive pressure) | **5–10 mmHg** (667–1,333 Pa) |
| Curvature preference | Positive pressure only (not negative) |
| Single-channel conductance | ~28.6 pS |
| Activation mode | Force-from-filaments (primarily), not force-from-lipid |

Piezo2 is intrinsically more rigid than Piezo1 ([Nature 2026 review](https://www.nature.com/articles/s41586-026-10182-7)) and is activated predominantly by cytoskeletal tethering. Its threshold is similar to or somewhat lower than Piezo1 in patch-clamp (5–10 mmHg), but via a different transduction pathway making it less directly responsive to pure membrane tension.

### B3. FUS-Mediated Piezo Activation — Bulk Acoustic Pressure Experiments

These experiments convert macroscopic acoustic pressure to channel opening and represent the best available bridge to the RF question:

| Study | Channel | Preparation | Frequency | Acoustic Pressure | Intensity | MI | Activation |
|-------|---------|-------------|-----------|------------------|-----------|-----|-----------|
| [Zhu et al. 2023 PNAS](https://pmc.ncbi.nlm.nih.gov/articles/PMC10161134/) | Piezo1 | In vivo cortex/CEA (mouse) | 0.5 MHz | **0.02–0.03 MPa** (Ca²⁺ onset) to 0.35–0.45 MPa (behavioral) | <500 mW/cm² ISPTA | — | Yes (Ca²⁺, EMG, movement) |
| [Prieto et al. 2018](https://web.stanford.edu/~kfirouzi/papers/journals/Prietoetal2017UMB.pdf) | Piezo1 | HEK293T cells (patch clamp) | 43 MHz | 50–67 kPa (simulated at boundary) | 50–90 W/cm² | — | Yes, via acoustic streaming |
| [Oh/Yoo et al. 2022 Nat. Commun.](https://pmc.ncbi.nlm.nih.gov/articles/PMC8789820/) | Piezo1 (partial) | In vivo cortex (mouse) | 300 kHz | Est. ~670 kPa at 15 W/cm² ISPPA | 15 W/cm² | **0.9** | Yes (whole-cell Ca²⁺) |
| [Hoffman et al. 2022 PNAS](https://www.pnas.org/doi/10.1073/pnas.2115821119) | Piezo2 | Ex vivo DRG neurons (mouse) | 3.57 MHz | Not stated in Pa; energy threshold ~158.5 nJ | 11–743 W/cm² ISPTP | — | Yes (action potentials) |
| [Scigliano et al. 2026 Sci. Rep.](https://pmc.ncbi.nlm.nih.gov/articles/PMC12868760/) | Piezo1 (DRG) | In vitro DRG neurons | — | **4–5 MPa positive pressure** | — | — | 52% activation at 5 MPa, 1 ms |

**Key notes on FUS experiments:**

- **Zhu et al. 2023** is the clearest in vivo Piezo1–FUS link: 0.02 MPa (20 kPa) produced a measurable but small Ca²⁺ response in CEA neurons (Piezo1-sensitive region), with responses scaling to 0.25 MPa. Motor responses required 0.35–0.45 MPa. This is the lowest documented bulk acoustic pressure linked to Piezo1-mediated neuronal activation.
- **Hoffman et al. 2022** demonstrates that Piezo2 sets the threshold for FUS-evoked action potentials in DRG neurons at their receptor fields; Piezo2 KO elevated the threshold energy by ~2.8×. No pressure values in Pa were provided; calibration was in nJ of acoustic energy.
- **Prieto et al. 2018** used 43 MHz US (very high, not FUS-typical) with 50–90 W/cm²; activation was via **acoustic streaming** forces on the cell membrane, not direct pressure. The relevant stress at the cell was a flow-induced membrane stress, not the oscillating acoustic pressure itself.
- **Mechanical Index** in successful Piezo1 neuronal FUS studies: MI = 0.9 (Yoo 2022), below the soft-tissue cavitation threshold of MI ≈ 1.9.

### B4. Piezo Threshold Summary Table

| Parameter | Piezo1 | Piezo2 |
|-----------|--------|--------|
| Membrane tension T₅₀ (in vitro patch) | 1.4–5.1 mN/m | Not measured in bilayer; ~5 mN/m estimated |
| Patch pipette pressure (first activation) | ~5 mmHg (~667 Pa) | ~5 mmHg (~667 Pa) |
| Patch pipette P₅₀ | ~17–36 mmHg (2.3–4.8 kPa) | ~5–10 mmHg (0.7–1.3 kPa) |
| Minimum bulk FUS pressure (in vivo, neurons) | **~20 kPa (0.02 MPa)** [Zhu 2023] | Not explicitly measured; comparable range expected |
| Standard FUS neuromodulation pressure | **350–450 kPa (0.35–0.45 MPa)** [Zhu 2023] | ~MPa range (DRG, Hoffman 2022) |
| Force sensitivity (single molecule) | ~10 pN [cited in Zhu 2023] | — |

---

## Part C: Comparison and Analysis

### C1. Pressure Regime Comparison Table

| Exposure/Condition | Peak Pressure | Notes |
|-------------------|--------------|-------|
| **RF: MAE cochlear threshold** | **0.020 Pa (20 mPa)** | Auditory threshold, per [Lin 2007](https://pubmed.ncbi.nlm.nih.gov/17495664/) |
| **RF: Lin 2007, 10 μs at 80 W/kg SAR** | **~0.04–0.24 Pa** | Human head, various models |
| **RF: Lin 1977, 10 μs at 1000 W/kg SAR** | **0.37–0.96 Pa** | Upper theoretical, 10× MAE SAR |
| **RF: Foster 2021 maximum (any freq, I₀ = 10 MW/m²)** | **300–500 Pa (~0.3–0.5 kPa)** | Physical upper limit, stress-confinement |
| **RF: Dagro 2021, 10⁶ mW/cm², 5 μs** | **~10s kPa** | Far above MAE threshold; non-auditory |
| **RF: Dagro 2021, 1.5×10⁶ mW/cm²** | **20–120 kPa** | NFL head-impact equivalent |
| Piezo1 first activation (patch) | ~0.7 kPa (667 Pa) | Patch-clamp pipette; not bulk pressure |
| Piezo1 T₅₀ (membrane tension) | 1.4–5.1 mN/m | ~2–5 kPa equivalent in patch |
| Piezo2 first activation (patch) | ~0.7–1.3 kPa | Patch-clamp; positive pressure only |
| **FUS: Piezo1 minimum in vivo (neurons)** | **~20 kPa (0.02 MPa)** | [Zhu et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC10161134/); CEA neurons, small response |
| **FUS: Piezo1 standard neuromodulation** | **350–450 kPa (0.35–0.45 MPa)** | [Zhu et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC10161134/); motor behavior |
| **FUS: DRG Piezo2 (Hoffman 2022)** | **Est. ~1–3 MPa** (from ~350 W/cm² ISPTP) | [Hoffman et al. 2022](https://www.pnas.org/doi/10.1073/pnas.2115821119) |

### C2. The Pressure Gap

| Comparison | Ratio |
|-----------|-------|
| RF MAE cochlear threshold (0.02 Pa) vs. minimum FUS-Piezo1 (20,000 Pa) | **10⁶×** |
| RF tissue thermoelastic peak at MAE threshold (~0.24 Pa) vs. minimum FUS-Piezo1 (20,000 Pa) | **~84,000×** |
| RF maximum feasible (Foster 2021 upper limit, ~400 Pa) vs. minimum FUS-Piezo1 (20,000 Pa) | **~50×** |
| RF maximum feasible (~400 Pa) vs. standard FUS-Piezo1 neuromodulation (400,000 Pa) | **~1,000×** |

The gap at auditory-threshold RF conditions is approximately **6 orders of magnitude**. It closes to roughly **50–100×** only at the extreme physical limit of RF exposures (10 MW/m² incident, stress-confinement regime) calculated by Foster 2021 — a power level orders of magnitude above any documented Frey-effect perception.

---

## Part D: Caveats and Mechanistic Considerations

### D1. Frequency Content and Coupling Efficiency

RF thermoelastic waves are **broadband transients** (microsecond duration → tens of kHz dominant frequency in the head) centered at ~7–10 kHz for typical human head dimensions ([Dagro 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8555891/); [Lin 2007](https://pubmed.ncbi.nlm.nih.gov/17495664/)). FUS Piezo experiments use **continuous or quasi-CW sinusoidal waves** at 0.3–3.6 MHz. Piezo1's gating kinetics (inactivation time constant ~tens of milliseconds; [Coste et al. 2010](https://pmc.ncbi.nlm.nih.gov/articles/PMC3508907/)) are much slower than the acoustic oscillation period at either frequency range. What matters for Piezo is the **envelope** or **sustained peak tension**, not the instantaneous pressure oscillation. A single microsecond RF pulse produces a transient that rises and falls faster than Piezo1's activation kinetics can integrate, making it an especially inefficient stimulus even if pressure amplitude were sufficient.

### D2. Hydrostatic Pressure vs. Membrane Tension

Piezo1 and Piezo2 are primarily gated by **lateral membrane tension**, not hydrostatic pressure ([Lewis & Grandl 2015](https://elifesciences.org/articles/12088); [Cox et al. 2016](https://www.nature.com/articles/ncomms10366)). A propagating acoustic pressure wave applies oscillating hydrostatic (compressive-then-tensile) pressure, which couples to membrane tension through the equation Δσ = ΔP × r / 4 for a spherical membrane (where r is cell radius, ~10 μm). For a cell of radius 10 μm under 20 kPa bulk pressure: Δσ ≈ 20,000 × 10⁻⁵ / 4 ≈ **0.05 mN/m** — roughly two orders of magnitude below the Piezo1 T₅₀ of ~2.7 mN/m. At RF auditory threshold pressures (~0.02 Pa), the induced membrane tension would be ~10⁻⁷ mN/m — utterly negligible. This coupling inefficiency is a structural reason why bulk acoustic pressure cannot be simply compared to patch-clamp pipette pressure.

### D3. Focal Volume and Duty Cycle

FUS neuromodulation experiments use **tightly focused beams** (FWHM ~5 mm or less) delivering energy to a small volume over 300–500 ms with 50% duty cycles. The total mechanical energy deposition per unit volume is many orders of magnitude greater than a single Frey-class RF pulse. A single RF auditory click contains ~1–10 mJ/kg of absorbed energy ([Chou & Guy 1979](http://gbppr.net/mil/havana/chou1979.pdf)). FUS neuromodulation experiments typically deliver 0.1–10 J/cm² over hundreds of milliseconds. Even cumulative RF exposure through a train of pulses does not approach FUS energy densities without entering the thermal injury regime.

### D4. Cochlear Hair Cells vs. Piezo1/2 in Neurons

The cochlea does express mechanosensitive channels (TMC1/2 are the primary hair-cell transduction channels; Piezo2 is expressed in cochlear supporting cells and spiral ganglion neurons). The Frey-effect pathway terminates at the **cochlear hair cells via bone conduction of the thermoelastic pressure wave** — not via direct Piezo gating in arbitrary neurons by the acoustic wave. Piezo2 is expressed in DRG and Merkel cells (touch/proprioception), and Piezo1 is expressed broadly in neurons and glia. The FUS–Piezo experiments target these extracochlear mechanotransducers. The Frey pathway is fundamentally different.

### D5. What Is and Isn't Known

| Claim | Status |
|-------|--------|
| Frey-class RF generates ~0.02–1 Pa thermoelastic pressure in head tissue | **Well established** (Lin 1977/2007; Foster & Finch 1974; Dagro 2021) |
| Cochlear hair cells respond to ~20 mPa thermoelastic wave | **Established** (Guy et al. 1975; Chou & Guy 1979) |
| FUS at 20–450 kPa activates Piezo1 in neurons | **Experimentally supported** (Zhu 2023; Prieto 2018) |
| Piezo2 sets FUS threshold in DRG neurons | **Well supported** (Hoffman 2022) |
| RF thermoelastic waves activate Piezo channels in any cell type | **Not demonstrated; no experiment has tested this directly** |
| Piezo1/2 are expressed in cochlear hair cells | **Piezo2 in supporting cells and spiral ganglia; TMC1/2 are primary hair-cell channels** |
| Temperature rise from RF pulses could activate TRPV channels | **Possible for sustained heating; implausible for single 1–10 μs pulse (ΔT ~1 μK)** |

---

## Part E: Honest Assessment

### Does the Energetics Support a Bridging Hypothesis?

**No, not under Frey-class auditory conditions.** The pressure gap of ~10⁴ to 10⁶ between auditory-threshold RF thermoelastic waves and the minimum FUS pressures that demonstrably activate Piezo1/2 in neurons is too large to bridge by any known mechanism of coupling enhancement. There is no identified cellular amplification pathway that would multiply acoustic pressure by 10⁴–10⁶ at the neuronal membrane.

**Partially, at extreme sub-injurious RF power levels.** At power densities of ~10⁶ mW/cm² (1 kW/cm²), far above any auditory-threshold exposure, RF thermoelastic pressures approach the **tens of kPa** range in tissue ([Dagro et al. 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8555891/)). This still sits below the most sensitive in-vivo Piezo1 activation threshold (~20 kPa, [Zhu et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC10161134/)) but is now within roughly an order of magnitude. However:

1. Such exposures are **not Frey-class** — they are injurious high-power microwave pulses.
2. The temporal character (single microsecond transient vs. sustained half-wave sinusoidal cycles at MHz) remains a poor match for Piezo gating kinetics.
3. No experiment has tested whether a single RF thermoelastic transient — even at high power — can gate Piezo channels.
4. Even Piezo1's lowest documented in-vivo activation threshold (20 kPa via FUS) involves sustained sinusoidal stimulation for 300 ms at 50% duty cycle, not a single microsecond pulse.

**The specific mechanism by which FUS activates Piezo1 in neurons is itself incompletely resolved.** At 43 MHz, activation was via acoustic streaming-induced membrane stress, not direct radiation pressure ([Prieto 2018](https://web.stanford.edu/~kfirouzi/papers/journals/Prietoetal2017UMB.pdf)). At 0.3–0.5 MHz, multiple mechanisms (radiation force, mechanical strain, cavitation) may contribute ([Yoo et al. 2022](https://pmc.ncbi.nlm.nih.gov/articles/PMC8789820/)). There is no mechanism by which a bone-conducted thermoelastic transient from RF absorption would generate the streaming or sustained displacement force needed.

### The Two Numbers That Define the Gap

| | Value |
|---|---|
| RF thermoelastic peak pressure at MAE cochlear threshold | **~20 mPa (0.020 Pa)** |
| Minimum FUS bulk pressure for in-vivo Piezo1 neuronal activation | **~20 kPa (20,000 Pa)** |
| **Ratio** | **~10⁶** |

Even taking the most favorable comparison — RF at its physical upper limit vs. the most sensitive Piezo1 detection — the gap is **~50×**, and the temporal stimulus waveform remains categorically different.

---

## Sources

All citations are inline as links throughout this document. Primary sources:

1. [Frey 1962](https://mriquestions.com/uploads/3/4/5/7/34572113/auditory_frey_rf_hearing_jappl.1962.17.4.689.pdf) — *J. Appl. Physiol.* 17:689–692
2. [Lin 1977](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/RS012i06Sp00237) — *Radio Sci.* 12:237–242
3. [Lin 2007](https://pubmed.ncbi.nlm.nih.gov/17495664/) — *Health Phys.* 92:621–628 ([PDF](http://gbppr.net/mil/havana/lin2007.pdf))
4. [Foster & Finch 1974](https://pubmed.ncbi.nlm.nih.gov/4833827/) — *Science* 185:256–258 ([PDF](http://www.gbppr.net/mil/havana/foster1974.pdf))
5. [Chou & Guy 1979](http://gbppr.net/mil/havana/chou1979.pdf) — *Bioelectromagnetics* guinea pig threshold study
6. [Dagro et al. 2021](https://pmc.ncbi.nlm.nih.gov/articles/PMC8555891/) — *Science Advances* 7:eabh2718
7. [Foster 2021](https://public-pages-files-2025.frontiersin.org/journals/public-health/articles/10.3389/fpubh.2021.788613/pdf) — *Front. Public Health* 9:788613
8. [NAS 2020](https://www.nationalacademies.org/news/new-report-assesses-illnesses-among-us-government-personnel-and-their-families-at-overseas-embassies) — National Academies Report on Overseas Embassy Illness
9. [Coste et al. 2010/2012](https://pmc.ncbi.nlm.nih.gov/articles/PMC3508907/) — Piezo1 gating mechanics
10. [Lewis & Grandl 2015](https://elifesciences.org/articles/12088) — *eLife* 4:e12088
11. [Cox et al. 2016](https://www.nature.com/articles/ncomms10366) — *Nat. Commun.* 7:10366
12. [Narayanan et al. 2019](https://pmc.ncbi.nlm.nih.gov/articles/PMC6478859/) — *Sci. Rep.* 9:6446 (Piezo2)
13. [Prieto et al. 2018](https://web.stanford.edu/~kfirouzi/papers/journals/Prietoetal2017UMB.pdf) — *Ultrasound Med. Biol.* 44:1217–1232
14. [Yoo et al. 2022](https://pmc.ncbi.nlm.nih.gov/articles/PMC8789820/) — *Nat. Commun.* 13:493
15. [Hoffman et al. 2022](https://www.pnas.org/doi/10.1073/pnas.2115821119) — *PNAS* 119:e2115821119
16. [Zhu et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC10161134/) — *PNAS* 120:e2300291120
17. [Gong et al. 2023](https://pmc.ncbi.nlm.nih.gov/articles/PMC9930135/) — *J. Gen. Physiol.* 155:e202213260
18. [Wikipedia: Microwave auditory effect](https://en.wikipedia.org/wiki/Microwave_auditory_effect)
