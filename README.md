#  Hybrid Mixed-Effect Diffusion Model (H-MED)
## A proposed interpretable deep learning framework integrating mixed-effects regression with diffusion-based modeling

<img width="2656" height="1062" alt="graphical_abstract" src="https://github.com/user-attachments/assets/2804f7de-373a-445f-a23c-e6b4288a1bd1" />

**H-MED** (Hybrid Mixed-Effect Diffusion Model) is a **newly proposed** architecture to address the challenges of modeling large-scale **longitudinal air quality data**. Unlike traditional deep learning approaches that behave as black boxes, **H-MED is explicitly designed to be both powerful and interpretable**.

H-MED integrates:

- **Mixed-effects regression** (for country-level and longitudinal heterogeneity),
- **Gaussian Process Regression (GPR)** (for smooth uncertainty structure),
- **LSTM networks** (for temporal sequence modeling),
- **Diffusion models** (for generative forecasting and uncertainty quantification),

into a **single, unified, interpretable deep learning framework**.

This hybrid design allows H-MED to maintain **the statistical interpretability of mixed-effects models** while achieving **state-of-the-art deep learning accuracy** through diffusion-based learning.

The method is introduced in:

**Tanriverdi, I. & Yozgatligil, C. (2025). _Hybrid Mixed-Effect Diffusion model (H-MED) for longitudinal air quality analysis_. Environmental Modelling & Software.**  
https://doi.org/10.1016/j.envsoft.2025.106746




---

## Key Features

- **Proposed by our team** as the first diffusion-based framework for longitudinal environmental data  
- **Interpretable deep learning**: mixed-effects structure provides statistical clarity, diffusion layers provide DL flexibility  
- **Hybrid architecture** combining mixed-effects regression with advanced sequence and diffusion models  
- **15–20% higher accuracy** than HITS, DCRNN, ST-GCN, and DeepAR  
- **Efficient** (average runtime: **5.69 seconds**)  
- **Country-level random effects** for capturing longitudinal variation  
- **Diffusion-driven uncertainty quantification**  
- **SHAP-based interpretability** (global + local explanations)  
- Scalable to **61-country, multi-year datasets (2013–2023)**  

---

<img width="1003" height="616" alt="H_MED architecture" src="https://github.com/user-attachments/assets/1b7bf78c-6b57-428a-b6e5-e4684c7df58f" />












