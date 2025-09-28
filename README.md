# Monte Carlo Sampling and Inverse Problems in Julia

This repository contains an interactive [Pluto.jl](https://github.com/fonsp/Pluto.jl) notebook that demonstrates **Monte Carlo Sampling** and **Metropolis–Hastings algorithms**, with applications to probability distributions and geophysical inverse problems.

The project combines **theory, visualization, and hands-on simulation** to provide an explainable and interactive way to learn sampling methods used in Bayesian statistics and computational mathematics.

---

## Features
- Implementation of **Monte Carlo Sampling** and **Metropolis–Hastings algorithm** from scratch in Julia.
- Interactive exploration of:
  - Prior and posterior probability distributions
  - Acceptance ratios for sampling efficiency
  - Random walk vs. local proposal distributions
- Visualization of sampling in **1D and 2D probability spaces**.
- Application to **geophysical gravity inversion problems**, showcasing the role of Bayesian inference in real-world physics.

---

##  Repository Contents
- `monte-carlo-sampling.jl` → Main Pluto.jl notebook with interactive UI and visualizations.
- Example plots include:
  - Density evolution
  - Acceptance vs. rejection history
  - Gravity inversion data fitting
