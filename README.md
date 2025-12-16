# Self-Calibrating Near-Infrared Spectroscopy via Dual Learning

> **Code will be released immediately upon paper acceptance.**

This repository implements a novel **dual-learning framework** for self-calibrating near-infrared (NIR) spectroscopy. It jointly trains:
- An **interpretable CNN-LSTM-Attention predictor** for accurate chemical property estimation (e.g., soil organic carbon, clay, water content), and  
- A **physically constrained 1D diffusion model** that generates realistic NIR spectra conditioned on predicted chemistry.

The two components are linked via a **spectral-angle cycle-consistency loss**, enabling bidirectional self-validation, improved robustness to data heterogeneity, and adherence to spectroscopic physics (e.g., Beer–Lambert law).

### 🔬 Key Highlights
- **State-of-the-art performance**: R² > 0.93 across four soil indicators (Carbon, Clay, Soil Water, Nitrogen).  
- **59% lower RMSE** for Soil Water vs. deep CNNs, with **38% fewer FLOPs**.  
- **Interpretable attention maps** align with known molecular vibrations (e.g., O–H, C–H).  
- Enables **synthetic data generation** for calibration, augmentation, and anomaly detection.

### 📄 Paper
> **Physics-driven Dual Learning with Beer–Lambert–Guided Diffusion for Chemical Composition Analysis and NIR Spectral Generation**  
> Submitted to *Neuracomputing*, Dec 15, 2025.

### 🚀 Coming Soon
- Training code  
- Pretrained models  
- Inference scripts for soil property prediction & spectrum generation

Stay tuned!
