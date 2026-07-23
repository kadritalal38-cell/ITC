# 🌌 Informational Time Cosmology (ITC) Simulation & Torus Topology

[![Python Version](https://shields.io)](https://python.org)
[![License: CC BY-NC-ND](https://shields.io)](https://creativecommons.org)

An advanced, high-precision computational astrophysics framework designed to model cosmic web dynamics under a **Torus Topological Space ($T^3$)** and benchmark alternative cosmological paradigms using Bayesian inference.

---

## ⚖️ LEGAL NOTICE & COPYRIGHT / تحذير قانوني وحقوق الملكية

### 🔴 English Notice:
**Copyright © 2026 Mohammad Talal Kadri. All Rights Reserved.**  
This software, source code, mathematical algorithms, and the underlying theoretical framework of **Informational Time Cosmology (ITC)** are the intellectual property of the author, **Mohammad Talal Kadri** (Researcher in Physics). 

* **Permitted Use:** This code is published strictly for academic review, open-science verification, and educational purposes.
* **Prohibitions:** Any unauthorized copying, distribution, modification, public performance, or commercial exploitation of this software or its cosmological methodology without explicit written consent from the copyright holder is strictly prohibited and constitutes an infringement of global intellectual property laws.
* **License:** Licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)**.

### 🔴 بيان تحذير قانوني (باللغة العربية):
**جميع حقوق الطبع والنشر محفوظة © 2026 للباحث محمد طلال قادري.**  
إن هذا البرنامج، الشفرة البرمجية (Source Code)، الخوارزميات الرياضية، والإطار النظري الأساسي لـ **كونيات الزمن المعلوماتي (ITC)** هي ملكية فكرية حصرية ومحمية قانونياً للمؤلف والباحث في الفيزياء **محمد طلال قادري**.

* **الاستخدام المسموح:** نُشر هذا الكود حصرياً لأغراض المراجعة الأكاديمية، والبحث العلمي المفتوح، والاستخدام التعليمي غير الربحي.
* **المحظورات القانونية:** يُحظر حظراً تاماً وقاطعاً نسخ هذا البرنامج، أو إعادة توزيعه، أو تعديله، أو استغلاله تجارياً، أو اقتباس خوارزمياته الفريدة دون إذن كتابي صريح ومسبق من مالك الحقوق. أي مخالفة لذلك تعرّض صاحبها للمساءلة والملاحقة القضائية الدولية بتهمة انتهاك حقوق الملكية الفكرية وسرقة المصنفات العلمية.

---

## 📋 Table of Contents
- [Project Overview & Torus Topology](#-project-overview--torus-topology)
- [Mathematical Framework](#-mathematical-framework)
- [Key Features & Core Pipeline](#-key-features--core-pipeline)
- [Bayesian Inference Architecture](#-bayesian-inference-architecture)
- [Installation & Requirements](#-installation--requirements)

---

## 💡 Project Overview & Torus Topology
The **Informational Time Cosmology (ITC)** framework explores cosmic web evolution, gravitational lensing, and multi-wavelength hydrostatic properties. To simulate a finite yet boundless universe without artificial boundary edge-effects, this core pipeline maps the 3D spatial coordinates of **1,500+ galaxies** onto a **Torus ($T^3$) manifold**. 

By applying periodic boundary conditions across the toroidal surface, particles and fields interacting near the boundary seamlessly wrap around, preserving global gravitational and thermodynamic equilibrium.

---

## 📐 Mathematical Framework (Torus Mapping)
The transformation of flat Cartesian cosmic coordinates $(x, y, z)$ into a parametric Torus geometry is computed using:

$$X = (R + r \cos(\theta)) \cos(\phi)$$
$$Y = (R + r \cos(\theta)) \sin(\phi)$$
$$Z = r \sin(\theta)$$

Where:
* $R$ is the major radius (distance from the center of the tube to the center of the torus).
* $r$ is the minor radius (the radius of the tube itself) mapped from the cosmic scale.
* $\theta, \phi$ are the poloidal and toroidal angles derived from periodic constraints.

---

## ✨ Key Features & Core Pipeline

### 🔹 Phase 1: Real Cosmological Redshift Calculation
* Evaluates precise lookback time intervals and estimates deep-space cosmological redshifts (`z_real_observed`).
* Integrates realistic constants for Planck Hubble configurations ($H_0 = 67.4$) and modern JWST observational alignments ($H_0 = 73.0$).

### 🔹 Phase 2: Multi-Wavelength Hydrostatic Clustering
* Simulates multi-wavelength phenomena including gravitational shear profiles observed via JWST (`real_jwst_shear`) and gas density parameters aligned with Chandra X-ray outputs.
* Tracks hidden energy fluxes and bounded phase frequencies across multi-spectral spaces.

### 🔹 Phase 3: 2D Spatial Paradox Resolution & Toroidal Projections
* Establishes high-resolution 2D coordinate meshgrids to resolve spatial variations.
* Computes complex sub-structures for both lensing and gas fields mixed with localized Gaussian noise patterns.

### 🔹 Phase 4: Large-Scale Structure Dynamics & Torus Filament Tracing
* Constructs a massive 3D Cosmic Web hosting over **1,500 modeled galaxies**.
* Performs spatial grouping, toroidal filament tracing, and cluster routing using customized interference metrics (`itc_interference_weight`).

### 🔹 Phase 5: Global AICc Metric Benchmarking
* Executes high-fidelity log-likelihood processing across multiple theories using `mpmath` at **50 decimal places**.
* Uses the **Corrected Akaike Information Criterion (AICc)** to statistically bench and rank the predictive power of **ITC** vs **$\Lambda$CDM** and **MOND**.

### 🔹 Phase 6: Future Temporal Horizon Dispersion
* Runs a massive multi-epoch forecast extending over a **4-Billion-Year future horizon** (`future_time_delta`).
* Models long-term dissipation constants and tracks the divergence of future expansion paths across alternative universes.

---

## 🎲 Bayesian Inference Architecture (PyMC Models)
The codebase constructs four distinct probabilistic graphs sampled concurrently using MCMC:
* **`model_itc_real`:** Inferring unified spatial resistance variables (`T_resistance`) and data coordination bounds.
* **`joint_itc_model`:** Constrained multi-source alignment merging JWST lensing likelihoods and Chandra X-ray distributions.
* **`bullet_itc_model`:** A specialized likelihood setup mimicking the **Bullet Cluster**, isolating physical offsets between dark matter potentials and gaseous thermal footprints.
* **`LSS_itc_model`:** Modeling Baryon Acoustic Oscillations (**BAO**) center variations, power-law limits, and cosmic correlation decays.

---

## 🛠️ Tech Stack & Libraries
* **`mpmath`**: Configured to `mp.dps = 50` for ultra-precise high-precision calculations.
* **`pymc`** & **`arviz`**: Statistical execution graph modeling and MCMC trace diagnostics.
* **`numpy`** & **`scipy`**: Vectorized arrays, tensor handling, and fundamental probability distributions.
* **`plotly`** & **`matplotlib`**: Structured subplots and multi-dimensional analytical chart rendering.

---

## 💻 Installation & Requirements
Ensure you are running **Python 3.9+**. Install all necessary academic dependencies via `pip`:
```bash
pip install numpy scipy pymc arviz mpmath plotly matplotlib
```

---

## 🚀 Usage
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd ITC
   ```
2. **Execute the central simulation script:**
   ```bash
   python ITC.py
   ```
