# The Vacuum-Granule Waves:
## A Test-First Synthesis of AI-Analyzed Results

Author (pseudonym): "Gravity Resonance" [gravity.resonance@proton.me](mailto:gravity.resonance@proton.me)
DOI: [10.5281/zenodo.20729726](https://doi.org/10.5281/zenodo.20729726) Zenodo article published in pdf format
June 18, 2026
Link to A-series: [Github](https://github.com/gravity-resonance/toroid-quantum-gravity-resonance/blob/main/README.md), and [Zenodo](https://zenodo.org/records/18888582)

*with independent AI analyses by Claude (Anthropic)*

---

## Abstract

Two precision instruments, built for unrelated purposes, register a faint and so far unexplained signal. (i) The LIGO gravitational-wave detectors carry eighteen unidentified spectral lines that appear at the same frequency in both detectors three thousand kilometers apart. (ii) An independent re-analysis of a 912-day silicon spin-qubit record shows a 1/*f* noise spectrum with no measurable low-frequency floor across nearly four decades. Converted through a standard formula (a frequency times Planck's constant, divided by a characteristic speed), the LIGO and qubit channels return the same inferred mass near 10⁻⁴⁹ kg, on a continuous spectrum with no firm lower bound. Additional light-mediated datasets (NANOGrav, EDGES, ARCADE 2) extend to lower masses on the same spectrum and are discussed in §3. The proposed interpretation is that the common low-frequency hum is the projection onto each system of the Compton waves of low-mass quantum-vacuum excitations (*granules*). This places the framework in the company of, but distinct from, ultralight-boson models in the dark-sector literature, which reach to even lower masses and wavelengths approaching the size of the observable universe.

Two parameter-free relations produced by independent AI analysis, each built only from known constants of nature, anchor the geometry of the proposal. The *Temperature Borderline* R_th = (4π/3) ℏ*c*/(*k*_B *T*) fixes the size at which a body of temperature *T* sits on the classical-to-quantum crossover. The *Single-Vortex Compton Lock* fixes a droplet size at which a quantized superfluid vortex forces three independent characteristic lengths to coincide (*R*₁ ≈ 1.14 μm in helium-4, a size laboratories already produce). Both contain no adjustable numbers; both land on regimes that current experiments already probe.

All inputs are public and independently reproducible. The framework is the author's; the new parameter-free relations and the unifying symmetry are the AIs' own, orchestrated by the author.

---

**What "inferred granule mass" means.** None of these instruments weighs a granule directly. Each measures a frequency in its low-frequency (1/*f*) noise. The framework converts that frequency into a mass through one standard relation, *f* = *v*/λ_C, where λ_C = *h*/(*mc*) is the Compton wavelength and *v* is a characteristic speed: the speed of light *c* for LIGO, and the Fermi drift speed *v*_F of conduction electrons for the qubits. The significant point is that these two distinct conversions, applied to two physically unrelated machines, return the same mass to within a factor of two.

---

## 1. What the Instruments See

### 1.1 LIGO: Eighteen Unexplained Lines, Coincident at Both Detectors

The LIGO collaboration operates two gravitational-wave detectors on opposite sides of the continental United States (~3,000 km apart) and publishes a public catalogue (LIGO-T2100201) of faint spectral lines in the strain data whose origin its instrumental experts could not identify. From that catalogue, **eighteen unexplained lines appear at the same frequency in both detectors simultaneously**, after removing every line with a known cause (the power grid, calibration signals, the Earth–ionosphere Schumann resonances). They cluster non-uniformly rather than scattering randomly. Counting how many such coincidences one expects if the catalogue lines were placed at random, given their local density, predicts about nine; the data deliver twenty-one, of which three have conventional explanations, leaving eighteen. The excess over the random expectation, not the raw count, is the point.

*Figure 1 (in pdf): The eighteen surviving cross-detector lines (red), shown against the bands of every known conventional source (power mains, calibration tones, the Earth–ionosphere Schumann resonances). The survivors fall between the known bands, in structured clusters.*

### 1.2 Quantum Chips: A Floorless 1/*f* Noise over 912 Days

All precision instruments share a common low-frequency noise, the 1/*f* or "flicker" spectrum, whose amplitude rises as the inverse of frequency and whose microscopic origin remains unsettled. We independently re-analyzed, by three methods, a public 912-day record of a silicon spin qubit (Capannelli et al. 2025). The frequency noise follows a clean 1/*f* law across nearly four decades and shows **no low-frequency plateau**. The same 1/*f* behaviour appears in superconducting flux qubits, Josephson resonators at millikelvin temperatures, and MOSFETs at room temperature, across radically different materials. A floorless 1/*f* spectrum recurring across dissimilar systems is itself a standing puzzle with no accepted unified explanation.

*Figure 2 (in pdf): The frequency noise of a silicon spin qubit over 912 days, computed independently from the raw logs. It follows a 1/f law (a straight line on these axes) with no flattening at the lowest frequencies, the "floorless" hum.*

### 1.3 ARCADE: An Unexplained Radio Excess

The NASA radio experiment ARCADE 2 found that the sky carries more low-frequency radio emission than all known astronomical sources can account for. This is a genuine, published, still-unexplained excess. It is not reproduced here from raw data; it is included because it sits on the same continuous family of scales as the two results above. It does *not* coincide with the LIGO–qubit point. It lies about eight orders of magnitude lighter on the same proposed continuum. An unexplained excess that falls on a continuum already populated by two unrelated instruments is more interesting than one that does not.

*Figure 3 (in pdf): The ARCADE 2 absolute sky-brightness excess (blue points), with the standard Fixsen (2011) ν⁻²·⁶² fit (black dashed) and the framework's ν⁻¹·⁹¹ reading (green), mapped as a smooth continuum onto the same family of scales as the LIGO and qubit results.*

---

## 2. The Hypothesis, in Brief

The proposal is this: **the quantum vacuum carries a faint, structured background of very light excitations**, called *granules*, spanning a wide range of masses. Every sufficiently sensitive instrument is immersed in this field, and much of what has been recorded as "noise" may be the instrument's response to it.

**Central claim, in one sentence.** The floorless 1/*f* hum, the eighteen-line LIGO coincidence at 10 mHz tolerance, and the family of low-frequency anomalies in independent instruments share one quantitative reading: they are the responses of those instruments to the Compton waves of low-mass quantum-vacuum excitations on a continuous mass spectrum.

---

## 3. The Three Observations, in More Detail

### 3.1 The Resonance Origin of the Discrete LIGO Lines

If the granule field is a smooth background, as the continuous hum suggests, why would LIGO register sharp *lines* rather than a smooth hiss? Because the lines originate in the detector, not in the field. A smooth field passing over any finely built instrument drives it at its own natural resonances, much as a steady breeze makes a wine glass sound its own note. A detector with no sharp mechanical resonances (the quantum chip) registers only the smooth 1/*f* hiss, which is exactly what the qubit data shows. LIGO's two detectors are intentionally built to be nearly identical, so they resonate at the same frequencies, which is why the same eighteen lines appear at both. A free check anyone can run: overlay the eighteen lines on LIGO's published table of mechanical resonances (LIGO-T0900511). If they align, the resonance reading is confirmed. If they do not, the field itself carries structure at those frequencies. We have not yet run this overlay; either outcome would be informative.

### 3.2 The Granule Mass Spectrum, and the Question of Clusters

The framework's first estimate from the 1–5 Hz electronic hum placed a characteristic granule mass near 10⁻⁴⁴ kg (A7). Refinement along three independent paths widened this into a range, from about 10⁻⁴³ kg down to roughly 10⁻⁵⁰ kg (A9). The LIGO lines, read through the light channel, imply a mass on the lighter side, near 10⁻⁴⁸ to 10⁻⁴⁹ kg. The trend is the point: every more sensitive record reaches a lower frequency, and therefore a lighter mass, with no firm bottom yet found. Rather than one predicted value, the data describe a *continuous family* of vacuum granules, a spectrum extending to ever-lighter masses.

The non-uniform clustering of the LIGO lines, and the way different instruments overlap on the mass axis, leaves an open question: are the clusters real groupings that point to distinct *types* of granule, or are they samples of one smooth continuum? We do not claim to know. Particle physics began with three building blocks (electron, proton, neutron), uncovered a zoo of hundreds of composite hadrons, then a deeper layer of quarks and gluons, and today counts neutrinos as one candidate dark-matter species among many. It is reasonable to expect that the layers beneath ordinary matter are at least as varied. In this view the granules need not rival Planck-scale structure; they would be its long-wavelength, collective face, in the way that sound waves in a solid are the collective behaviour of its atoms rather than a competitor to them.

*Figure 4 (in pdf): Four light-mediated datasets (NANOGrav, LIGO, EDGES, ARCADE 2) on one granule-mass axis. Each independent measurement falls in a different region of the same A9 range. The qubit hum (the electron-mediated channel) is the separate result shown in Figure 2 and the overview.*

---

## 4. The Compton Waves of the Granules, in Context

Grok (xAI) offered a helpful image: the vacuum as an ocean. It is not empty but vast and structured, with depths and currents at scales we have only begun to map. At its deepest the ocean is violent, the Planck-scale "quantum foam" explored by Wheeler, Hawking, Penrose, and others; at its surface it is calm, with long, slow, gentle waves of macroscopic extent. The granules in this framework are the waves at the surface, not the foam at the bottom.

The complementary image is a pond, the same medium seen from closer up. Where the ocean is the global picture, the pond is what one experiment sees when it dips its instruments into the surface: a local patch surrounding the laboratory. The field across that patch is slow and smooth; what each instrument reports as a sharp *frequency* is set not by the field's own slow motion but by how the instrument couples to it (its mechanical resonances for LIGO, its electron drift speed for a chip). The structure is in the medium, but the line frequencies are the detector's.

We are describing a continuous, overlapping field of Compton waves belonging to these light masses. Because the Compton wavelength

> λ_C = *h*/(*mc*)

grows as the mass falls, the waves are macroscopically large. For the granule mass range derived from the hum, the wavelengths span from roughly hundreds of meters for the heaviest granules in the family, up to many kilometers for the lightest. Their ultimate extent is open: with no confirmed floor to the hum, there is no firm lower bound on how light a granule may be.

The framework is not alone in proposing very-light-boson backgrounds with macroscopic wavelengths. The dark-sector literature contains a broad family of ultralight-boson candidates spanning many orders of magnitude in mass: "fuzzy dark matter" near 10⁻²² eV (~10⁻⁵⁸ kg), with de Broglie wavelengths at the kiloparsec scale; intermediate-mass axion-like particles and dark photons; and "ultralight dark matter" candidates with masses down to ~10⁻³¹ eV (~10⁻⁶⁷ kg), whose wavelengths approach the size of the observable universe. The granule framework occupies the heavier end of this same general spectrum, where the wavelengths are still macroscopic (kilometers to Earth-sized coherence patches of order 20,000 km). Whether the granule spectrum is distinct from these dark-sector candidates or simply the heavy end of the same population is an open question; if the spectrum has no floor, the two may be parts of one continuum.

---

## 5. A Pattern Underneath: One Geometric Rule, Four Physical Speeds

Until recently the underlying framework looked like a handful of separate results. They are not separate. They are one simple geometric rule seen from different sides, each side selected by which physical process sets a particular speed. The unifying form of this section is due to Claude Opus 4.8.

### 5.1 The Geometric Rule, and the Cancellation

The central relation of the framework is the *angular-duality length*

> **λ_ad = κ *Rv*/*c***

where *R* is the radius of a rotating body, *v* is its rim speed, *c* is the speed of light, and κ is a dimensionless shape factor of order unity (κ = 2/3 for a uniform sphere, κ = 1 for a thin ring). This is the A-series's own definition, not a mainstream formula; it is derived in A8v2.

The origin of this relation, and the source of the mass cancellation that follows, is this. For any body of mass *M*, radius *R*, and rim speed *v*, the angular momentum is *J* = κ*MRv*. The angular-duality length is defined as

> λ_ad = *J*/(*Mc*) = κ*MRv*/(*Mc*) = κ *Rv*/*c*

The body's mass *M* appears in both the numerator (through *J*) and the denominator. It cancels exactly, leaving a length determined entirely by *R*, *v*, and *c*.

### 5.2 The Four Physical Speeds

The framework's *borderline* is the condition λ_ad equals one of two standard quantum lengths: the reduced Compton wavelength λ̄_C = ℏ/(*mc*) of a constituent of mass *m*, or its de Broglie wavelength. The geometry of the borderline is fixed. What changes from result to result is what physical process sets the rim speed *v*. Four such processes are presently identified.

**(a) Gravitational orbit.** For a test body in orbit at radius *R* around a central mass *M*:

> *v*_grav = √(*GM*/*R*)

Substituting into the angular-duality relation and matching against the test body's Compton wavelength returns Einstein's equivalence principle of general relativity: the borderline depends on *GM* and *R* but not on the test mass *m* (A8v2).

**(b) Quantized vortex circulation.** In a superfluid, the circulation around a vortex is quantized in units of *h*/*m* (Onsager 1949, Feynman 1955). For a single quantum of circulation at radius *R* in a superfluid of constituent mass *m*:

> *v*_vortex = ℏ/(*mR*)

Substituting:

> λ_ad = κ (*R*/*c*) · (ℏ/*mR*) = κ ℏ/(*mc*) = κ λ̄_C

The radius *R* cancels exactly, leaving the constituent's reduced Compton wavelength. This is the geometric content of the Single-Vortex Compton Lock (§6.2).

**(c) Thermal motion.** For a constituent of mass *m* at temperature *T*, the characteristic thermal speed is

> *v*_therm ≈ √(*k*_B *T*/*m*)

Substituting and matching against the Compton wavelength gives the parameter-free Temperature Borderline R_th = (4π/3) ℏ*c*/(*k*_B *T*) (§6.3). Both sides scale as *m*⁻¹/², so the constituent mass cancels exactly, leaving a relation in only three constants of nature.

**(d) Conduction-electron drift.** For conduction electrons in a metal, the characteristic speed is the Fermi velocity,

> *v*_F ~ 10⁵ to 10⁶ m/s

a material-dependent constant. Substituting gives the original granule-mass estimate of A7 from the 1–5 Hz electronic hum, with masses in the range 10⁻⁵⁰ to 10⁻⁴³ kg.

### 5.3 Why This Matters

Four physically distinct setups, fed into the same geometric relation, produce: the equivalence principle of general relativity, the Single-Vortex Compton Lock at the micron scale, the Temperature Borderline at the classical-to-quantum crossover, and the granule-mass spectrum read off the electronic hum. The relation is the same; only the velocity differs. A coincidence ends the conversation; a relation that generates four results from one rule keeps producing predictions.

A natural fifth case has been proposed by the same symmetry: the phonon velocity *v*_ph in a crystal, an acoustic analogue of *v*_F for lattice vibrations. The prediction is that a seismometer and a quantum chip at the same location, both showing 1/*f* noise, would show their characteristic features shifted in frequency by roughly the ratio *v*_F/*v*_ph ~ 10². This is a clean potential discriminator, offered as a prediction to be tested, not a measured result.

---

## 6. The New Results

The framework's earlier papers (A1–A9) supply the geometry. What is new in 2026, and reported here in one place, are the results produced in the AI-assisted analyses. Each is stated plainly and then given its mechanism.

### 6.1 The Geometric Scale Used in §1

The mass-to-frequency conversion of §1 (*f* = *c*/λ_C for LIGO, *f* = *v*_F/λ_C for qubits) rests on a geometric scale that the Kerr metric assigns to any spinning body. It is derived in A7v2: for bodies whose spin dominates their mass (true of every ordinary particle, and of ordinary macroscopic rotating bodies), the Kerr horizons become imaginary (the discriminant *m*² − *a*² − *e*² is negative), and the surviving real geometric scale is set by the spin. For a light constituent below the Planck mass, this scale coincides, up to a factor of 2π, with its reduced Compton wavelength ℏ/(*mc*), and that is the scale the §1 conversion uses. Carter (1968) showed that the Kerr–Newman solution reproduces the electron's measured *g* = 2 gyromagnetic ratio; Burinskii (2019) develops the same line. The A-series uses the same Kerr geometry, applied to ordinary spinning matter, with details in A7v2.

### 6.2 The Single-Vortex Compton Lock (Claude, June 2026)

Any spinning body in this framework carries three lengths: the angular-duality length λ_ad = κ*Rv*/*c*, the constituent's Compton wavelength λ_C = *h*/(*mc*), and the body's de Broglie wavelength λ_dB = *h*/(*Mv*). In an ordinary object these three lengths are wildly different numbers; the framework's borderline is the condition where two of them coincide.

In a superfluid carrying a single quantized vortex, no tuning is needed to force the coincidence. Substituting the quantized vortex speed *v* = ℏ/(*mR*) into the angular-duality relation makes λ_ad collapse exactly to the constituent's reduced Compton wavelength: two of the three lengths fuse automatically by the topology of the vortex.

Matching the third length, the collective de Broglie wavelength λ_dB = 2π*R*/*N* for a body of *N* constituents, gives the lock condition

> *N* = 2π*R* / λ̄_C

The body locks when it holds *one constituent per reduced Compton wavelength around its rim*. For a uniform droplet of mass density ρ, this fixes one specific radius,

> *R*₁ = *m* √(3*c* / (2ℏρ))

For ordinary superfluid helium-4 the locked radius is *R*₁ ≈ 1.14 μm, with *N* ≈ 1.35×10¹¹ atoms. Micron helium droplets carrying a single vortex *already exist* and have been imaged by X-ray free-electron-laser diffraction (Gomez et al., *Science* 2014). The abstract borderline is therefore not something to engineer; it is a property certain droplets already possess. A tunable version appears in intercalated or twisted-graphene superconductors (one Cooper pair per pair-Compton wavelength of the rim), for example a CaC₆ ring ~0.4 μm wide whose lock can be switched on and off with a gate voltage.

*Honest status:* this is an exact coincidence of lengths fixed by topology; whether any physical interaction accompanies the lock is the open question the experiments in §7 would test.

### 6.3 The Temperature Borderline (Claude Sonnet, March 2026)

Feed the same borderline a thermal speed instead of a quantized one. A body at temperature *T* has constituents moving at a thermal speed *v*_therm ≈ √(*k*_B *T*/*m*). Setting the borderline speed equal to this thermal speed, the mass cancels exactly (both sides scale as *m*⁻¹/²), leaving a relation in only three constants of nature:

> **R_th = 2*hc* / (3*k*_B *T*) = (4π/3) ℏ*c* / (*k*_B *T*)**

R_th is the size at which a body of temperature *T* sits on the boundary between classical and quantum behavior. It contains no adjustable numbers, and equals 4π/3 times the standard thermal (Matsubara) length ℏ*c*/(*k*_B *T*).

**Table: The Temperature Borderline ladder**

| Temperature | R_th | Regime that probes it |
|-------------|------|----------------------|
| 300 K | 32 μm | room-temperature optomechanics |
| 77 K | 125 μm | liquid-nitrogen devices |
| 4.2 K | 2.3 mm | liquid-helium circuits |
| 0.1 K | 9.6 cm | dilution-fridge superconducting circuits |

*Why it is interesting.* With nothing fitted, these sizes are precisely the regimes in which experiments have pushed quantum behavior up to objects we can handle, including the centimeter-scale superconducting circuits near absolute zero recognized by the **2025 Nobel Prize in Physics**. A parameter-free length that lands on the measured quantum-classical crossover is suggestive of a deeper structural reason.

*Honest status.* The result is a clean exact identity that lands on a real crossover scale, worth testing, but not yet a derived mechanism.

### 6.4 A Candidate Mechanism for the Field Itself (Claude Opus 4.6, June 2026)

The two results above are geometric coincidences. This subsection sketches, as one model's hypothesis, the physics that could underlie them. Treat a granule as a very light scalar field φ of mass μ. Its wave equation gives the standard dispersion relation

> ω² = *c*²*k*² + ω_C²

with a gap at the Compton frequency ω_C = μ*c*²/ℏ. For the granule mass range this gap lies far above the recorded band, so the 1–5 Hz hum we actually record is *not* the field vibrating: it is the slow spatial sampling of a nearly static field by electrons moving through it. That is why the detected frequency is set by the detector's electron speed rather than by the field.

A scale-free mass distribution (equal energy in each decade of mass) produces precisely the observed 1/*f* law with no floor. One coupling constant ties the laboratory to the cosmos: if the granule field's total energy density equals the measured dark-energy density, a coupling α_g ~ 10⁻⁹ reproduces the measured qubit-noise amplitude. That same α_g then becomes a quantitative prediction for any second channel (LIGO strain, Casimir), a cross-check rather than a free fit.

*Honest status:* this is a candidate, internally consistent and falsifiable through that shared α_g. It is not a complete quantum field theory.

---

## 7. How to Check It, Cheaply

None of the following requires new instruments; all use archived data or a tabletop, and each is publishable whether it finds something or nothing.

**Cross-detector coherence test on LIGO archived strain (zero-delay phase lock):** take LIGO's archived raw data and measure whether the two detectors' signals are genuinely *coherent* (rising and falling in locked phase, at zero time delay) at the eighteen lines. A shared external field would force that lockstep; independent local noise would not. The public catalogue records that the lines exist; it does not record whether the two detectors move in step. One analyst, standard methods, one week.

**Cross-continental atomic-clock residual correlation (BIPM Circular T):** the BIPM Circular T archive (clock residuals from ~60 national metrology institutes since the 1990s) is a public log of unexplained low-frequency drift. A graduate-student program of cross-correlation across continents would either find a shared component or set the strongest existing bound.

**Electromagnetic emission spectroscopy of single-vortex helium-4 droplets at 1.14 μm (Claude, §6.2):** produce 1.14-micrometer single-vortex helium-4 droplets, or graphene rings at the predicted size, and look for any electromagnetic signature at the locked rotation frequency.

**Temperature-dependent Casimir-force deviation near granule wavelengths (Claude Opus 4.7):** if the vacuum carries granule modes, two close plates suppress those modes with wavelengths larger than the gap, predicting a small temperature-dependent departure from the standard *d*⁻⁴ Casimir law. Beyond present precision; a falsifiable direction, not a result.

---

## 8. Limits and Open Questions

**What is and is not established.** The eighteen LIGO lines and the floorless 912-day hum are reproducible facts from public data. The granule explanation of them is a hypothesis. The LIGO line coincidences exceed the random-placement expectation by a measured factor of about 2.4. Whether they are new physics or an as-yet-undiagnosed instrumental effect is genuinely open. Low-frequency noise is usually presumed to have a conventional cause; but the floorless 1/*f* hum has resisted any unified conventional explanation for decades, and the present proposal is that it may be worth treating as a signal.

**What is still missing:** a complete quantum field theory of the granule. A preliminary scaffolding exists (§6.4); a finished theory is the right object for a dedicated team rather than a half-built sketch presented here.

**The honest posture.** The claim of this paper is not that a new force has been found. It is that specific, inexpensive, falsifiable tests are worth running. A falsifiable idea that later proves wrong advances science and is respectable; an asserted discovery that others must labor to refute is not. Nor is it reasonable to require one unaffiliated researcher to deliver a finished theory, its full proof, and zero errors at once — a standard that would have buried most foundational ideas in their start. The eighteen lines are a thread for a team to pull.

---

## 9. Provenance and Reproducibility

The framework and its guiding ideas are the author's, including the original by-hand download of the LIGO catalogue, the coincidence search, the geometry of imaginary Kerr horizons (A4, A7), the vacuum granules (A7, A9), and the mass cancellation (A8). The AI contributions are as follows. **Claude Sonnet:** the Temperature Borderline and the BIPM archive proposal. **Claude Opus 4.7:** the LIGO line analysis, the resonance reading, the cross-detector coherence test, and the Casimir prediction. **Claude Opus 4.6:** the dispersion relation and the amplitude link to dark energy. **Claude Opus 4.8:** the floorless-1/*f* reproduction and the unifying "one rule, four speeds" relation of §5. **Claude (Anthropic):** the Single-Vortex Compton Lock.

All analyses use public data; the core analyses ran in a compute sandbox, with code and inputs preserved. The claims rest on re-runnable public data, independent of whether the models agreed with one another.

The author presents these AI-derived results as the findings of the respective models, credited honestly but not personally vouched for. The Temperature Borderline in particular met the author's initial scepticism when Sonnet derived it during the work on A9, and was only later accepted as a possibility to be tested, not a certainty. The same standing applies to every result above and to the author's own framework: each needs rigorous testing, and none is presented here as a finished theory or a proven experiment. They are included because the scientific community should have access to genuine AI-assisted discoveries, and because no one person — the author included — should serve as gatekeeper for what AI may legitimately contribute.

---

*For a century the hum has been the thing we subtract. This paper asks whether it is also a thing we might listen to. If the vacuum has a sound, it has been playing in every quiet instrument we have ever built, and we have simply been calling it noise. The tests proposed here cost almost nothing. The only expensive thing would be to keep not listening.*

---

## References

1. Capannelli et al. (2025), *Tracking spin qubit variations over 912 days*, arXiv:2509.20990; data DOI [10.5281/zenodo.15632269](https://doi.org/10.5281/zenodo.15632269)
2. LIGO-T2100201 (unidentified O3 lines), LIGO-T2100200 (vetted O3 lines/combs), LSC, tag O3_lines_v1.7.
3. Carter, B. (1968), *Phys. Rev.* **174**, 1559.
4. Burinskii, A. (2019), *Features of spinning gravity in particle physics: supersymmetric core of the Kerr–Newman electron*, J. Phys.: Conf. Ser.; see also *The Dirac–Kerr–Newman electron*, arXiv:hep-th/0507109.
5. Lake, M. & Carr, B. (2015), *JHEP* **11**, 105, arXiv:1505.06994.
6. Gomez, L.F. et al. (2014), *Shapes and vorticities of superfluid helium nanodroplets*, *Science* **345**, 906.
7. ARCADE 2: Fixsen, D.J. et al. (2011), *ApJ* **734**, 5.
8. A-series papers, published under the name "Gravity Resonance." DOIs at 10.5281/zenodo: A1b [16449277](https://doi.org/10.5281/zenodo.16449277); A2 [17541112](https://doi.org/10.5281/zenodo.17541112); A3 [17594467](https://doi.org/10.5281/zenodo.17594467); A4 [17619734](https://doi.org/10.5281/zenodo.17619734); A5 [17634226](https://doi.org/10.5281/zenodo.17634226); A6 [17684823](https://doi.org/10.5281/zenodo.17684823); A7v2 [19320019](https://doi.org/10.5281/zenodo.19320019); A8v2 [19275058](https://doi.org/10.5281/zenodo.19275058); A9 [18888582](https://doi.org/10.5281/zenodo.18888582).
