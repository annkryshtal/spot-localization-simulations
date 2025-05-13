# Spot Localization in Retina: Simulated Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains simulation code and analysis exploring mechanisms of **spatial response localization** in retinal ganglion cells (RGCs). The work was originally developed during my research in the **Schwartz Lab** at **Northwestern University** and focuses on the role of population statistics and receptive field (RF) organization in spatial encoding.

All code and data in this repository are based on simulated models and do **not** include unpublished biological recordings and more detailed analysis.

---

## 🧠 Project Overview

RGCs exhibit localized responses to visual stimuli, but the underlying mechanisms that determine the precision of this localization remain an open question. In this project, I explored how factors such as neural variability, signal integration, and noise correlations may influence spot localization precision.

### Key Objectives:
- Understand how population activity encodes the position of localized visual stimuli.
- Evaluate the effect of variability and correlation structures on decoding accuracy.
- Build and analyze simulated models of RGCs and downstream integration.

---

## 📁 Contents

| File | Description |
|------|-------------|
| `integral_num_var_mean_simulated.ipynb` | Performs numerical analysis of variance and mean estimation for a simulated neural population model, particularly focusing on how stimulus-dependent noise and tuning curve parameters affect statistical properties of the population response. |
| `noise_corr_model_simulation.ipynb` | Simulates and analyzes noise correlations in neural spike trains across a spatially organized grid. It includes the generation of hexagonal grids to mimic RGCs alignment, neural spike train simulation, noise correlation analysis, application of dimensionality reduction techniques like PCA, and other computational methods to explore how well single spot stimuli could be localized in the retina. |

---

## 🧪 Environment & Requirements

- Python ≥ 3.8
- Jupyter
- `numpy`, `matplotlib`, `scipy`, `scikit-learn`

## 🔖 License
This project is licensed under the MIT License. You are free to use, modify, and share this code with proper attribution.

## 👩‍🔬 Acknowledgements
This work was developed during my research stay in the Schwartz Lab, Northwestern University, under the supervision of Prof. Gregory W Schwartz. The project builds on our shared interest in computational models of retinal and cortical processing.

