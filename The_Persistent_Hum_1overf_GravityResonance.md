# The Persistent Hum: 1/f Noise as a Candidate Window on Vacuum Structure

**Author:** Gravity Resonance
**Date:** 31 May 2026
**Keywords:** 1/f noise, flicker noise, pink noise, vacuum fluctuations, spacetime foam, low-frequency gravitational-wave noise, SQUID flux noise, quantum vacuum, granular vacuum, persistent hum, Compton wavelength, macroscopic quantum crossover

The Quantum Vacuum Granule: Three Complementary Mass Scales from the 1--5 Hz Universal Hum - DOI 10.5281/zenodo.18888582 Zenodo published article https://zenodo.org/records/18888582

Independent note by Claude Sonnet 4.6 on Thermal case 
---

## Abstract

There is a noise that will not go away. Across utterly unrelated instruments — resistors, vacuum tubes, superconducting quantum interferometers, atomic clocks, the seismic ground, biological membranes, and the loudness of music — the measured power spectrum rises toward low frequency as approximately 1/f. After a century of study, this ubiquity is not in dispute. What *is* in dispute, and indeed largely unaddressed, is whether the shared spectral shape is a coincidence of many independent mechanisms or the signature of something common. This note makes a deliberately narrow and falsifiable argument. First, it documents the proven ubiquity of 1/f noise as established fact. Second, it isolates the genuinely open question the mainstream has been content to leave open. Third, it proposes the one measurement — cross-instrument, cross-site coherence — that could distinguish a common physical origin from a collection of private noises. The interpretive hypothesis that the residual hum reflects a structured vacuum is presented as a hypothesis, not a result. The strength of the argument lies entirely in the part that is already proven.

---

## 1. The phenomenon

"1/f noise" (also called flicker noise or pink noise) refers to a fluctuating signal whose power spectral density `S(f)` scales approximately as `1/f^α` with `α` near 1, over many decades of frequency. Unlike white noise (flat spectrum) or Brownian noise (`1/f²`), 1/f noise is *scale-free*: it looks statistically similar whether you examine it over seconds, hours, or years. There is no characteristic timescale, and — crucially — no observed bottom. However low in frequency the measurement is pushed, the rise continues.

The phenomenon was first reported by J. B. Johnson at Bell Laboratories in 1925, as a slow fluctuation in the emission current of vacuum-tube cathodes. Walter Schottky analysed it theoretically in 1926 and gave it the name it still carries: the *flicker effect*. A century later, the spectral law is one of the most reproduced empirical facts in physics — and one of the least explained.

## 2. The proven ubiquity — instrument by instrument

The following is the strong ground. Each item below is documented, mainstream, and not in serious dispute. The remarkable thing is not any single entry; it is the list itself.

**Vacuum tubes.** The original observation (Johnson 1925; Schottky 1926). Flicker fluctuations in thermionic emission, below a corner frequency where they overtake shot noise.

**Resistors and semiconductors.** Every resistor, diode, and MOSFET exhibits a 1/f component that dominates below a corner frequency. The two standard frameworks — carrier-number fluctuations from trapping/detrapping at defects (McWhorter) and mobility fluctuations (Hooge's empirical relation) — describe the data well but still contend over the underlying cause. In modern CMOS, 1/f noise is the limiting low-frequency noise source.

**SQUIDs and superconducting qubits.** Superconducting quantum interference devices show 1/f *flux* noise; superconducting qubits show 1/f flux and charge noise that is a principal source of decoherence. The microscopic origin — often attributed to fluctuating surface spins — remains genuinely unsettled. This is significant: a frontier quantum technology is rate-limited today by a 1/f noise nobody can fully account for.

**Atomic clocks and quartz oscillators.** Frequency stability is ultimately bounded by a "flicker floor" — a regime of the Allan deviation where 1/f frequency noise dominates and no amount of averaging improves the result. Even the best oscillators meet this wall.

**The seismic ground.** Earth's low-frequency background motion rises toward low frequency with a 1/f-like character. Together with Newtonian (gravity-gradient) coupling, this is the noise environment that shapes the low end of every ground-based precision instrument — and it is the domain on which a careful treatment of the hum should concentrate, because it is both well-characterised and directly relevant to gravitational-wave detectors.

**Biological systems.** Ion-channel currents, neural membrane potentials, and heart-rate variability all display 1/f spectra. The empirical fact is solid across many independent studies.

**Natural and astrophysical signals.** Voss and Clarke (Nature, 1975) showed that loudness and pitch fluctuations in music and speech follow a 1/f spectrum down to the inverse length of the piece. Comparable scaling appears in sunspot records, quasar luminosity, and river flows. The pattern is not confined to the laboratory; it is in the world.

## 3. What is established, and what is open

It is important to separate the two, because the credibility of any further claim depends on the separation.

**Established.** That 1/f noise appears across these systems, over many decades of frequency, with no observed low-frequency cutoff. This is not speculative. It is one of the best-replicated phenomena in measurement science.

**The standard interpretation.** The prevailing mainstream position is that these are *separate* mechanisms that happen to share a spectral shape — trapping in semiconductors, surface spins in SQUIDs, and, more generally, a superposition of many relaxation processes with a broad distribution of time constants (the Dutta–Horn picture). On this view, the universality of the *shape* is a mathematical near-inevitability and carries no deep physical message.

**The open question.** The standard interpretation explains how to *fit* 1/f spectra; it does not explain why the same scale-free law recurs so insistently across systems with nothing physically in common. "A superposition of relaxation times" is a description of the data, not a derivation of why nature so reliably arranges those times into a 1/f law. This is the gap. It is a real gap, and acknowledging it is not fringe — it is simply declining to look away from a coincidence the field has agreed to tolerate.

## 4. A necessary caveat about gravitational-wave detectors

Because the hypothesis below touches gravitational-wave instruments, one point must be stated plainly to avoid an easy dismissal. The low-frequency sensitivity wall of detectors such as LIGO and Virgo is dominated by *identified* noise sources: seismic motion, suspension thermal noise, and Newtonian gravity-gradient noise. It would be incorrect to claim that the detector wall "is" a fundamental hum. The honest and defensible statement is narrower: beneath the identified and modelled noise contributions, the question of a residual, irreducible flicker character has not been exhausted, and the instruments most able to probe it (cryogenic, underground, and space-based designs) are only now arriving.

## 5. The hypothesis: a structured vacuum and the hum

What follows is *hypothesis*, clearly marked, and the rest of the argument does not depend on accepting it.

The conjecture is that part of the universal low-frequency hum reflects structure in the quantum vacuum itself — that "empty" space possesses a granularity whose collective excitations leave a scale-free imprint on sufficiently quiet instruments. The idea that the vacuum is not smooth has a respectable lineage: John Wheeler's *quantum foam* (1955) proposed a granular, fluctuating spacetime at the Planck scale, and Stephen Hawking developed the spacetime-foam picture further. The hypothesis advanced here differs from Planck-scale foam in one essential respect — the relevant scale is taken to be far larger, set not by the Planck length but by a characteristic excitation whose Compton wavelength `λ_C = h/(mc)` places it in the low-frequency, long-wavelength regime where the hum is observed. A reverse de Broglie construction then assigns the excitation a small effective mass from the observed frequency; the exact value depends on the assumed propagation speed (the speed of light, a Fermi-type velocity, or none if the excitation is static), and that ambiguity is acknowledged rather than hidden.

This framework also offers an internally consistent answer to the obvious objection — *if the vacuum hums, why is daily life silent?* The answer is thermal. Setting the de Broglie / angular-duality borderline speed equal to the thermal rms speed yields a temperature-dependent crossover length that scales as 1/T (the mass cancels exactly, because both speeds scale as `m^(−1/2)`). At room temperature this length is microscopic and any coherent structure is buried under incoherent thermal agitation; only in cold, isolated regimes does it climb to laboratory scale (of order millimetres near 4 K, centimetres near 0.1 K). The prediction is therefore not that the effect is everywhere visible, but that it should emerge specifically where instruments are coldest and quietest — which is exactly where the SQUID, the cryogenic oscillator, and the underground interferometer operate.

To be clear about status: the mass-cancellation identity is exact algebra; the crossover length is a clean dimensional result; the claim that the granule is a real excitation, and that it is what hums, is unproven. The value of the hypothesis is that it is *shaped to be tested*, not that it is established.

## 6. The decisive test: coherence, not coincidence

A frequency catalogue can never settle this, in either direction. An instrumental artifact does not immunise a frequency against also carrying a real signal, and the absence of a line in a deaf instrument is not evidence of absence. The degeneracy between "shared artifact" and "shared physical origin" cannot be broken by *where* lines sit. It can only be broken by *what they correlate with*.

An instrumental line has a local witness: a magnetometer or accelerometer near the apparatus that registers the same fluctuation, so the line is coherent with an environmental channel and not with distant instruments in any physically meaningful way. A genuine signal of vacuum origin would show the opposite signature — coherence *across* independent instruments and, for spatially separated detectors, a definite relationship consistent with propagation between them, while remaining incoherent with any single local witness.

The proposed measurement is therefore a cross-instrument, cross-site coherence analysis of the low-frequency residual, after subtraction of identified noise, with explicit use of environmental witness channels and (for separated sites) inter-site timing. The falsifiable prediction is sharp: if the hum is private to each instrument, the residual will correlate only with local witnesses and not across sites; if it has a common physical origin, a coherent component will survive across instruments that share nothing but the vacuum they sit in. This is a test a properly resourced collaboration can perform, and its outcome is decisive either way.

## 7. What this argument deliberately excludes

One tempting extension is set aside on purpose. Financial and economic time series display long-memory, 1/f-like behaviour in volatility. Whatever its interest, it introduces non-stationarity, reflexivity, and unresolved questions about the direction of causality that would only weaken a physical argument. It is mentioned here once, as suggestive and explicitly beyond present scope, and is excluded from the formal case. The disciplined ground is physical instrumentation — and within that, the seismic and electronic domains are the cleanest and best documented.

## 8. Closing

The persistent hum is not a fringe curiosity. It is one of the few genuinely universal, genuinely unexplained-at-root phenomena in measurement science, hiding in plain sight inside every quiet instrument humanity has built. The mainstream has fitted it many times and explained it once for each system, while leaving its universality unexplained. That gap is an opportunity, not an embarrassment — and it can be addressed without asking anyone to accept a new mechanism on faith. The proven ubiquity stands on its own. The vacuum-structure interpretation is offered as a hypothesis that has the one virtue a hypothesis must have: it tells you precisely what experiment would prove it wrong.

---

### Selected references and pointers

- J. B. Johnson (1925); W. Schottky (1926) — first observation and naming of the flicker effect in vacuum tubes.
- R. F. Voss and J. Clarke, "'1/f noise' in music and speech," *Nature* **258**, 317–318 (1975).
- E. Milotti, "1/f noise: a pedagogical review," arXiv:physics/0204033 — overview of mechanisms and the Dutta–Horn framework.
- J. A. Wheeler (1955) — spacetime / quantum foam; later developed by S. Hawking.
- Gravitational-wave open data and instrumental-line catalogues: Gravitational Wave Open Science Center (GWOSC), gwosc.org.

*This note states proven facts as proven and hypotheses as hypotheses. The author welcomes correction on any point of fact.*
