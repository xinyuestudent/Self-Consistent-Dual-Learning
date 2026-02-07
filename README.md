# Dual-Path Consistency Learning for Chemical Composition Analysis from Near-Infrared Spectra

> **Code will be released immediately upon paper acceptance.**

This repository implements a novel **dual-learning framework** for self-calibrating near-infrared (NIR) spectroscopy. It jointly trains:
- •	A consistency-regularized framework improves NIR regression under calibration-limited conditions

- •	Training-time spectral reconstruction enforces calibration stability without inference overhead

- •	Angular and Beer–Lambert-inspired constraints support physical plausibility and robustness

- •	Extensive experiments show improved accuracy and stability on real-world NIR datasets


The two components are linked via a **spectral-angle cycle-consistency loss**, enabling bidirectional self-validation, improved robustness to data heterogeneity, and adherence to spectroscopic physics (e.g., Beer–Lambert law).

🔬 Key Highlights

Consistently high accuracy: Achieves R² > 0.91 across 10 targets from four NIR datasets.

Up to 51% RMSE reduction compared to classical regressors, with zero test-time cost from dual path.

Physics-aware training via Beer–Lambert-inspired constraint and angular alignment.

Modular MASL backbone integrates Conv, GRU, and Attention for robust spectral feature extraction.

### 📄 Paper
> **Dual-Path Consistency Learning for Chemical Composition Analysis from Near-Infrared Spectra**  
> submitting

### 🚀 Coming Soon
- Training code  
- Pretrained models  
- Inference scripts for soil property prediction & spectrum generation

Stay tuned!
