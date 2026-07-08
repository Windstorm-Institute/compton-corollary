# Paper 16: The Compton Corollary

**Bekenstein's Bound at the Compton Scale of a Massive Elementary Particle: A Hilbert-Space Ceiling and a Numerical Coincidence with the Exceptional Lie Group Sequence**

Grant Lavell Whitmer III · Windstorm Labs, The Windstorm Institute · Fort Ann, NY, USA

[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20163450-blue)](https://doi.org/10.5281/zenodo.20163450)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)
[![Track: Entropic Bounds](https://img.shields.io/badge/Track-2_·_Entropic_Bounds-8b5cf6)](https://windstorminstitute.org/#track2)

**Zenodo**: [10.5281/zenodo.20163450](https://doi.org/10.5281/zenodo.20163450) · **Current version: v0.4** (May 2026)

**Notation borrowed from:** [Paper 15 — The 𝒩<sub>esc</sub> Recipe](https://github.com/Windstorm-Institute/nesc-recipe) ([10.5281/zenodo.20145105](https://doi.org/10.5281/zenodo.20145105))

> **A note on series membership.** This is a *short empirical observation paper*. It uses the 𝒩<sub>esc</sub>(*E*, *L*) ≡ 2π*EL*/(ℏ*c*) notation introduced in Paper 15, but **does not invoke the escrow recipe** of Papers 11/14/15. The function under evaluation here is Bekenstein's; the recipe of [9] applies only to gravitational regimes, and a free elementary particle in vacuum is not one of them. The corollary stands or falls on its own merits.

---

## The two observations recorded

**1. A universal Hilbert-space ceiling at the Compton scale.**

Evaluating Bekenstein's bound at the reduced Compton wavelength λ̄<sub>C</sub> = ℏ/(*mc*) of a massive elementary particle with rest energy *E* = *mc*² gives a value **independent of mass**: the *m* in *E* cancels the 1/*m* in λ̄<sub>C</sub>. The result is

> *S*<sub>max</sub>(λ̄<sub>C</sub>) = 2π *k*<sub>B</sub>   ⟺   *D* ≤ *e*<sup>2π</sup> ≈ **535.49**

where *D* is the dimension of the particle's internal Hilbert space (spin × color × any other gauge index). All massive Standard Model elementary particles satisfy this ceiling comfortably — *D* ≤ 12 for quarks (Dirac × 3-color), against a ceiling of about 9.06 qubits.

**2. A numerical coincidence with the exceptional Lie group sequence.**

The five Cartan-exceptional simple Lie algebras have adjoint dimensions 14, 52, 78, 133, 248. Forming the natural one-particle-state count *D* = 2 dim(adj *G*):

| Group | dim adj | D = 2·dim(adj) | D / *e*<sup>2π</sup> | log₂*D* / log₂*e*<sup>2π</sup> |
|---|---:|---:|---:|---:|
| G₂ | 14 | 28 | 5.2% | 53.0% |
| F₄ | 52 | 104 | 19.4% | 73.9% |
| E₆ | 78 | 156 | 29.1% | 80.4% |
| E₇ | 133 | 266 | 49.7% | 88.9% |
| **E₈** | **248** | **496** | **92.6%** | **98.8%** |

The exceptional sequence climbs monotonically toward the Compton-Bekenstein ceiling. **E₈ sits at 92.6% of *e*<sup>2π</sup> (98.8% in log₂ units).** The Cartan classification terminates with E₈; no E₉ exists. The largest natural exceptional dimension falls below the formal ceiling by **7.4% (linear)** or **1.2% (log₂)**.

## What the paper does NOT claim

The paper is unusually explicit (§6) about the domain mismatches and interpretive limits:

- **Domain mismatch acknowledged up front (§3).** The Bekenstein bound applies to massive elementary particles at their Compton scale. The 2 dim(adj *G*) state count is the natural one-particle count for a *massless* gauge boson of an *unbroken* gauge symmetry — which has no finite Compton wavelength at which to apply the bound. The two numbers refer to physically distinct settings. The comparison is displayed despite this, with the caveat made visible rather than relegated to a footnote.
- **The localization at λ̄<sub>C</sub> is at the limit of Bekenstein's formal domain.** Confining a particle to its own Compton wavelength saturates the relativistic localization theorem — pair-production contamination is unavoidable at this scale. The bound is read as a formal counting statement, not a literal claim about a sharply localized particle.
- **Both ratio metrics reported (linear and log₂)** to avoid metric cherry-picking. The choice of metric substantially changes the perceived strength of the pattern (92.6% vs 98.8% for E₈). The reader is invited to weight whichever they find more natural.
- **Coincidence reading is given the most defensible weight (§6).** Absent a physics-grounded reason for treating the Compton-scale Bekenstein number as the comparison point for Lie-algebra dimensions — especially given that gauge bosons of unbroken symmetries are massless — the paper does not push beyond "we record the pattern for future reference."

## Read the Paper

- **[paper.pdf](paper.pdf)** — full academic paper (v0.4)
- **[Zenodo record](https://doi.org/10.5281/zenodo.20163450)** — archived with DOI
- **[Website article](https://windstorminstitute.org/articles/compton-corollary.html)** — long-form companion

## Companion code

**[Windstorm-Labs/compton-corollary](https://github.com/Windstorm-Labs/compton-corollary)** — minimal computational artifact reproducing the ratios in the Lie-group table (the paper has no lattice content; the comparison is one transcendental constant against five Lie-algebra dimensions).

## In the Series

### Track 2 — Entropic Bounds in Analog Systems · 7 papers (Papers 10–16)

| # | Paper | DOI |
|---|---|---|
| 10 | [Phonon Extraction Bound](https://github.com/Windstorm-Institute/phonon-extraction-bound) | [10.5281/zenodo.20014390](https://doi.org/10.5281/zenodo.20014390) |
| 11 | [Gravitational Entropy Escrow](https://github.com/Windstorm-Institute/gravitational-entropy-escrow) *(framework)* | [10.5281/zenodo.20031931](https://doi.org/10.5281/zenodo.20031931) |
| 12 | [C8 Clarification Note](https://github.com/Windstorm-Institute/c8-clarification-note) | [10.5281/zenodo.20041991](https://doi.org/10.5281/zenodo.20041991) |
| 13 | [Lattice QFT Test](https://github.com/Windstorm-Institute/lattice-qft-test) | [10.5281/zenodo.20057537](https://doi.org/10.5281/zenodo.20057537) |
| 14 | [Spacetime as Escrow Bookkeeping](https://github.com/Windstorm-Institute/escrow-spacetime) | [10.5281/zenodo.20126090](https://doi.org/10.5281/zenodo.20126090) |
| 15 | [The 𝒩<sub>esc</sub> Recipe](https://github.com/Windstorm-Institute/nesc-recipe) | [10.5281/zenodo.20145105](https://doi.org/10.5281/zenodo.20145105) |
| 16 | [The Compton Corollary](https://github.com/Windstorm-Institute/compton-corollary) *(this paper — short Bekenstein observation; uses 𝒩<sub>esc</sub> notation only, recipe not invoked)* | [10.5281/zenodo.20163450](https://doi.org/10.5281/zenodo.20163450) |

---

## How to cite

```bibtex
@misc{whitmer_2026_compton_corollary,
  author       = {Whitmer III, Grant Lavell},
  title        = {Bekenstein's Bound at the Compton Scale of a Massive
                  Elementary Particle: A Hilbert-Space Ceiling and a
                  Numerical Coincidence with the Exceptional Lie Group
                  Sequence},
  month        = may,
  year         = 2026,
  publisher    = {Zenodo},
  version      = {v0.4},
  doi          = {10.5281/zenodo.20163450},
  url          = {https://doi.org/10.5281/zenodo.20163450}
}
```

## License

Paper: CC BY 4.0 · Code: MIT (see [Windstorm-Labs/compton-corollary](https://github.com/Windstorm-Labs/compton-corollary))

---

*The Windstorm Institute · Independent research at the intersection of information theory, non-equilibrium thermodynamics, molecular biology, and artificial intelligence. [windstorminstitute.org](https://windstorminstitute.org)*
