# Analytical and Numerical Solutions to the Black-Scholes Equation

![LaTeX](https://img.shields.io/badge/LaTeX-Beamer-blue)
![Status](https://img.shields.io/badge/Status-Complete-success)

## Overview
This repository contains a comprehensive mathematical presentation on the Black-Scholes option pricing model. It bridges continuous-time stochastic calculus, fundamental physics, and computational statistics to provide a rigorous, step-by-step derivation and numerical validation of the foundational PDE.

The presentation is designed for an academic defense, moving from the conceptual limitations of standard calculus in jagged financial markets to the precise derivation of the closed-form Black-Scholes formula, concluding with empirical Monte Carlo validation.

## Key Mathematical Highlights
* **Stochastic Foundations:** Deriving Geometric Brownian Motion (GBM) and expanding Ito's Lemma through quadratic variation limits.
* **PDE Construction:** Building a locally risk-free, continuously hedged portfolio to isolate deterministic growth.
* **Domain Transformations:** Applying logarithmic moneyness and integrating factors to mathematically neutralize market drift and decay, collapsing the PDE into the fundamental 1D Heat Equation.
* **Fourier Analysis:** Utilizing the Dirac delta point source, spatial Fourier Transforms, and the Convolution Integral (via the Sifting Property) to resolve the exact option price.
* **Numerical Validation:** Integrating the risk-neutral logarithmic return and simulating 100,000 independent market paths using vectorization to demonstrate aggressive convergence to the analytical price.

## Repository Contents
* `presentation.tex`: The complete LaTeX Beamer source code for the slide deck.
* `image_afb759.png`: The empirical convergence chart generated via Python/NumPy, embedded in the final slides to visualize Monte Carlo convergence.

## How to Compile the Presentation
The presentation is built using **LaTeX Beamer**. 

**Option 1: Overleaf (Recommended)**
1. Create a new blank project in [Overleaf](https://www.overleaf.com/).
2. Upload `presentation.tex` and `image_afb759.png` into the root directory.
3. Set the main document to `presentation.tex` and click **Recompile**.

**Option 2: Local LaTeX Environment**
Ensure you have a TeX distribution (like TeX Live or MiKTeX) installed.
Run the following commands in your terminal in the directory containing your files:
```bash
pdflatex presentation.tex
pdflatex presentation.tex
