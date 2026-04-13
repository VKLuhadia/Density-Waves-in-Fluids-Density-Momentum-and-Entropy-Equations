# Density-Waves-in-Fluids-Density-Momentum-and-Entropy-Equations

This repository contains my Jupyter Notebook project on the dynamics of density waves in fluids, developed for the Continuum Mechanics (PH 562) course under Professor Anirban Sain at the Indian Institute of Technology, Bombay.

## Overview
This project explores the mathematical derivation and visual modeling of the **Dynamic Structure Factor $S(k, \omega)$** in fluids. I start by formulating the exact linearized hydrodynamic equations from foundational conservation laws, then apply spatial and temporal Fourier transforms to analyze fluid behavior. The notebook culminates in Python-based visualizations of complex phase transitions, including critical opalescence and superfluidity.

## Key Concepts Explored
* **Linearized Conservation Laws:** Analyzing the continuity, momentum, and energy (entropy) equations for small-amplitude motions.
* **Thermodynamic Coupling:** Using exact thermodynamic relations and Maxwell equations to connect fluctuating variables ($p', S', T', \rho'$).
* **Velocity Splitting:** Separating transverse (shear waves) and longitudinal velocity components.
* **The Matrix & The Poles:** Evaluating the spectral denominators to locate the Rayleigh pole (thermal diffusion) and Brillouin poles (acoustic pressure waves).
* **Critical Phase Transitions:** Modeling critical opalescence and critical slowing down near a fluid's critical point, where specific heat diverges and thermal diffusivity collapses.
* **Second Sound in Superfluids:** Analyzing Liquid Helium-4's quantum phase transition below the Lambda point ($T_\lambda \approx 2.17$ K), where heat stops diffusing and instead propagates as a frictionless thermal wave known as "Second Sound."

## Visualizations and Models
The notebook includes mathematical implementations using `numpy` and `matplotlib` to simulate and plot:
1. **Scattering Dispersion Map:** A 2D contour plot mapping the intensity of the Dynamic Structure Factor across wavenumbers ($k$) and frequency shifts ($\omega$). It highlights the central Rayleigh diffusion peak against the theoretical Brillouin dispersion lines ($\pm ck$).
2. **Superfluid Transition:** A comparative spectral model of normal Liquid $^4$He ($T > T_\lambda$) versus Superfluid $^4$He ($T < T_\lambda$). The visualization conceptually demonstrates how the central Rayleigh peak vanishes and splits into a sharp "Second Sound" doublet upon entering the zero-viscosity state.

## Dependencies
To run the simulations and generate the plots locally, ensure you have the following installed:
* Python 3.x
* `numpy`
* `matplotlib`
* `jupyter` (to open and execute the `.ipynb` file)

## Usage
Clone the repository and launch Jupyter Notebook to run the analysis:
```bash
git clone <repository_url>
cd <repository_directory>
jupyter notebook PH562_22B2105.ipynb
