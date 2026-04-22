# radio_waves

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19688827.svg)](https://doi.org/10.5281/zenodo.19688827)

**Radio wave transport in solar wind including anisotropic scattering**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Overview

This package simulates radio wave propagation in the solar wind, including anisotropic scattering effects. It is based on the ray tracing and scattering models described in:

- Kontar, E. et al. (2019) – [ADS link](https://ui.adsabs.harvard.edu/abs/2019ApJ...884..122K/abstract)
- Kontar, E. et al. (2023) – [ADS link](https://ui.adsabs.harvard.edu/abs/2023ApJ...956..112K/abstract)

---

## Fixed Version for Ma et al. (2026)

**This release (`v1.0-nature-communications-2026`) is the exact version used in:**

Ma, S., Kontar, E., Clarkson, D., Chen, H., & Yan, Y. (2026). *Imaging spectroscopy reveals spike-like repeating radio burst pairs in the solar corona*. Nature Communications.

The code has been permanently archived on Zenodo with the DOI: [10.5281/zenodo.19688827](https://doi.org/10.5281/zenodo.19688827).

---

## Original Source

This repository is a **fork** of the original `radio_waves` package developed by Eduard Kontar and Daniel Clarkson:

- **Original repository:** [https://github.com/edkontar/radio_waves/](https://github.com/edkontar/radio_waves/)
- **Original license:** MIT License

No functional changes have been made to the core simulation code. This fork exists solely to provide a **permanently fixed and citable version** for reproducibility purposes.

---

## Usage

### IDL

```idl
rays_swind, qeps2_scaling=0.1, anis=0.25, r_init=1.75, asym=1., f_ratio=2.0

# radio_waves
radio wave transport in solar wind including anisotropic scattering 

Ray tracing and scattering based on the following papers:
https://ui.adsabs.harvard.edu/abs/2019ApJ...884..122K/abstract
https://ui.adsabs.harvard.edu/abs/2023ApJ...956..112K/abstract

Calling sequence, e.g. for LOFAR observations:

IDL> rays_swind, qeps2_scaling=0.1, anis=0.25, r_init=1.75, asym=1., f_ratio=2.0

updated June 2022

Python version by D. Clarkson https://github.com/edkontar/radio_waves/commits?author=d-clarkson



