# Bayesian MCMC Analysis of Magnetic Fields in Galaxy Superclusters

This repository contains a tutorial and reproducible workflow for analyzing **magnetic fields in galaxy superclusters** using **Bayesian statistics**.  
The analysis is based on **RM-Synthesis** of LOFAR observations and demonstrates:

- Selection of real polarized sources from RM catalogs
- Inspection of Faraday depth spectra (FDFs) and Q/U parameters
- Cross-checks with polarization and NVSS maps
- Removal of duplicates and construction of clean catalogs
- **Bayesian inference of rotation measures (RMs)** using MCMC with `emcee`

---

## Why Bayesian?
Astrophysical data often contain significant uncertainties and noise.  
Bayesian methods allow us to:
- Incorporate prior knowledge about expected RM distributions
- Sample from full posterior distributions of parameters with `emcee`
- Quantify credible intervals and correlations between parameters
- Visualize posteriors with `corner` plots for interpretation

---

## Tools & Libraries
- Python (NumPy, Pandas, Matplotlib, SciPy)
- `emcee` — affine-invariant MCMC ensemble sampler
- `corner` — posterior visualization
- `astropy` — astrophysical utilities

---

## Context
This project is inspired by ongoing research in cosmic magnetism,  
using LOFAR observations to understand magnetic fields in large-scale structures.  
It provides a hands-on example of how **Bayesian MCMC methods can be applied in astrophysics**.
