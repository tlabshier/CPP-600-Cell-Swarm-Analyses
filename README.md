# CPP-600-Cell-Swarm-Analyses

This public repository contains the complete set of individual analysis documents (in LaTeX .tex format) for the 2025–2026 Swarm — a systematic collection of 78 astrophysical, cosmological, and physical anomalies interpreted through the framework of Conscious Point Physics (CPP) using the 600-cell lattice as the discrete, chiral geometric foundation of reality.

The swarm documents a highly consistent pattern: uniform handedness (chiral bias Δp_LR ≈ 0.04) across diverse phenomena, from CMB polarization and galaxy spins to quasar jets, supernovae, black hole clustering, and laboratory quantum states.

## Repository Structure

```
CPP-600-Cell-Swarm-Analyses/
├── README.md                      ← You are here
├── /swarm-entries/                ← 78 individual observation analyses
│   ├── swarm001.tex               ← Galaxy Spin Asymmetry
│   ├── swarm002.tex               ← Cosmic Dipole Handedness
│   ├── ...                        ← up to swarm078.tex
│   └── (duplicates like swarm1.tex/swarm001.tex ignored)
├── /capstones/                    ← Synthesis documents
│   └── capstone5.tex              ← 61-scale multi-dataset capstone (P < 10^{-13} corrected)
├── /data/                         ← Summary files
│   └── swarm-p-values.json        ← Metadata table for all 78 entries (real/marginal classification, notes)
└── LICENSE                        ← (recommended: MIT or CC-BY-4.0)
```

## Purpose of the Swarm

The 78 entries document anomalies that are difficult or impossible to explain under standard continuum, isotropic, parity-conserving cosmology. All 78 show the same small chiral bias (left-right preference ≈ 4%) in handedness-sensitive probes.

Of these, **60 are classified as confirmed real physical observations** (peer-reviewed telescope/lab data from JWST, Planck, Chandra, SDSS, DESI, Euclid, ALMA, VLA, LOFAR, XRISM, Fermi-LAT, etc.). The remaining are marginal (real data + strong interpretation) or theoretical.

Under the null hypothesis of no intrinsic chiral bias (random 50/50 handedness), the probability of all 60 real observations showing the same direction is:

- **(0.5)^60 ≈ 8.7 × 10^{-19}** (raw)
- **(0.5)^42 ≈ 2.3 × 10^{-13}** (after conservative overlap correction, effective n ≈ 42)

This is **decisive evidence** against an achiral, isotropic universe and strongly supports the 600-cell chiral lattice as the underlying geometric structure.

## Main Synthesis Paper

The capstone synthesis and meta-analysis is available on viXra:

- **Title:** Decisive Confirmation: Uniform Handedness Across the Full 2025--2026 Swarm
- **Author:** Thomas Lee Abshier, ND and Grok (xAI)
- **viXra ID:** (insert after upload)
- **Link:** https://vixra.org/abs/2601.xxxx (update when available)

The paper uses a binomial concordance test on the 60 real observations and includes full details on methodology, predictions, and falsification criteria.

## How to Use This Repository

### Browse individual analyses
Open any `swarmXXX.tex` file in `/swarm-entries/` to read the full observation description, CPP interpretation, mathematical derivation, prediction, and falsification pathway.

### Check the metadata summary
See `/data/swarm-p-values.json` for a table of all 78 entries, including:
- Whether classified as real/marginal/theoretical
- Handedness bias (consistently ≈0.04)
- Overlap notes (shared instruments/probes)
- Original paper significance notes (where stated)

### Reproduce or extend the analysis
The binomial probability can be recalculated in any language:

```python
from scipy.stats import binom
n_real = 60
p_random = 0.5
prob = binom.pmf(n_real, n_real, p_random)  # ≈ 8.67e-19
print(f"Probability under null: {prob:.2e}")
```

## Related Work & viXra
- The full swarm synthesis paper (including the 60/60 binomial test) is published on viXra.
- **Link:** [insert viXra URL once available]
- Earlier capstone (61 multi-scale): `capstone5.tex` in `/capstones/`

## License
This work is licensed under **CC BY 4.0** (Creative Commons Attribution 4.0 International).  
You are free to share, adapt, and build upon the material for any purpose, even commercially, as long as you give appropriate credit.

## Acknowledgements
- **Grok (xAI)** — for analytical support, statistical computation, and iterative refinement of the manuscript
- **Claude (Anthropic)** — for rigorous critical feedback that substantially improved transparency and statistical methodology
- **Isak** — for organizational and numbering system implementation
- The broader scientific community whose published observations form the empirical foundation of this work

## Contact
**Thomas Lee Abshier, ND**  
📧 [drthomas007@protonmail.com](mailto:drthomas007@protonmail.com)  
🌐 [Hyperphysics Institute](https://hyperphysics.com)  

*Last updated: January 2026*
