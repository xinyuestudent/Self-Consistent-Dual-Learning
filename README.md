# Physics-Guided Self-Consistent Dual Learning for Data-Efficient Near-Infrared Spectral Regression

> **Code will be released immediately upon paper acceptance.**

This repository implements a novel **dual-learning framework** for self-calibrating near-infrared (NIR) spectroscopy. It jointly trains:
- We propose a self-consistent dual learning framework for inverse regression of physically constrained one-dimensional sensor signals.

- The model incorporates physics-inspired cycle consistency and angular alignment constraints to improve regression stability and interpretability.

- A hybrid MASL backbone combines convolutional, recurrent, and attention-based modules to capture local patterns, sequential dependencies, and global relevance.

- Extensive experiments on four real-world NIR datasets demonstrate consistent improvements over state-of-the-art baselines across multiple sensing domains.

The two components are linked via a **spectral-angle cycle-consistency loss**, enabling bidirectional self-validation, improved robustness to data heterogeneity, and adherence to spectroscopic physics (e.g., Beer–Lambert law).

🔬 Key Highlights

Consistently high accuracy: Achieves R² > 0.91 across 10 targets from four NIR datasets.

Up to 51% RMSE reduction compared to classical regressors, with zero test-time cost from dual path.

Physics-aware training via Beer–Lambert-inspired constraint and angular alignment.

Modular MASL backbone integrates Conv, GRU, and Attention for robust spectral feature extraction.

### 📄 Paper
> **Physics-Guided Self-Consistent Dual Learning for Data-Efficient Near-Infrared Spectral Regression**  
> submitting

### 🚀 Coming Soon
- Training code  
- Pretrained models  
- Inference scripts for soil property prediction & spectrum generation

Stay tuned!
