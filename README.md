# Analytical and Numerical Solutions to the Black-Scholes Equation

![Status](https://img.shields.io/badge/Status-Complete-success)
![Topic](https://img.shields.io/badge/Topic-Quantitative_Finance-blue)

## Overview
This repository contains a comprehensive mathematical project and presentation on the Black-Scholes option pricing model. It bridges continuous-time stochastic calculus, fundamental physics, and computational statistics to provide a rigorous, step-by-step derivation and numerical validation of the foundational PDE.

The materials are designed for an academic defense, moving from the conceptual limitations of standard calculus in jagged financial markets to the precise derivation of the closed-form Black-Scholes formula, concluding with empirical Monte Carlo validation.

## Key Mathematical Highlights
* **Stochastic Foundations:** Deriving Geometric Brownian Motion (GBM) and expanding Ito's Lemma through quadratic variation limits.
* **PDE Construction:** Building a locally risk-free, continuously hedged portfolio to isolate deterministic growth.
* **Domain Transformations:** Applying logarithmic moneyness and integrating factors to mathematically neutralize market drift and decay, collapsing the PDE into the fundamental 1D Heat Equation.
* **Fourier Analysis:** Utilizing the Dirac delta point source, spatial Fourier Transforms, and the Convolution Integral (via the Sifting Property) to resolve the exact option price.
* **Numerical Validation:** Integrating the risk-neutral logarithmic return and simulating independent market paths to demonstrate aggressive convergence to the analytical price.

## Repository Contents
* `Project_Report.pdf`: The complete, detailed academic report covering all mathematical derivations and numerical methods.
* `Presentation_Slides.pdf`: The final slide deck used for the academic panel defense.
* `presentation.tex`: The LaTeX Beamer source code used to generate the slides.
* `image_922092.png`: The empirical Monte Carlo convergence chart embedded in the presentation.

## Author
**Gurman Avtar** Indian Statistical Institute (ISI), Kolkata Centre  
Roll No: BSDCC2408

## References
1. Black, F., & Scholes, M. (1973). *The Pricing of Options and Corporate Liabilities*.
2. Hull, J. C. (2017). *Options, Futures, and Other Derivatives*.
3. Shreve, S. E. (2004). *Stochastic Calculus for Finance II*.
