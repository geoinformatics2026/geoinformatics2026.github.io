---
title: "Refined Reconstruction of Geophysical Fields: Integrating Elevation-Informed Diffusion Processes with Enhanced Feature Spaces"
authors:
- "Qian Li"
- "Liwen Wang"
- "Ju Wang"
- "Xuan Peng"

---

# Refined Reconstruction of Geophysical Fields: Integrating Elevation-Informed Diffusion Processes with Enhanced Feature Spaces

**Author Information**  
Qian Li<sup>1</sup>, Liwen Wang<sup>1</sup>, Ju Wang<sup>1</sup>, Xuan Peng<sup>1</sup>


<sup>1</sup> College of Meteorology and Oceanography, National University of Defense Technology  



## Abstract

High-precision reconstruction of geophysical fields is essential for faithfully representing complex atmospheric processes such as cloud evolution, storm development, and orographic modulation of circulation. Yet many deep learning downscaling and super-resolution methods still struggle to recover fine-scale structures and to exploit elevation information beyond simple channel concatenation, which often underutilizes terrain–atmosphere interactions and produces overly smooth or biased fields. In this study, we propose an elevation-informed reconstruction framework that couples Conditional Variational Autoencoders (CVAEs) with diffusion modeling to enhance both feature representation and final field fidelity. The CVAE stage learns a multi-level, feature-rich latent space explicitly conditioned on elevation, enabling the model to encode topographic influences during feature extraction rather than treating elevation as an auxiliary afterthought. These optimized elevation-aware features are then passed into a diffusion process designed to iteratively refine meteorological fields. The diffusion component is implemented with a U-Net backbone and an additional decoder to further improve detail recovery, allowing progressive denoising and reconstruction guided by the learned feature space. Experiments are conducted using ERA5 data over East Asia and adjacent regions (20°–45°N, 100°–125°E), focusing on 850-hPa geopotential height fields and evaluating a 4× spatial upscaling from 1° × 1° to 0.25° × 0.25°. Results demonstrate that the proposed CVAE–diffusion approach better preserves sharp gradients, localized vortices, and terrain-related structures compared with classic learning-based baselines. Quantitatively, the method achieves a notable improvement over Super-Resolution Convolutional Neural Network (SRCNN), reducing RMSE by 13.89% for 850-hPa geopotential height reconstruction. Additional analyses indicate that multi-level elevation conditioning contributes to more physically consistent spatial detail, while diffusion-based refinement mitigates artifacts and improves high-frequency structure recovery. Overall, integrating elevation-conditioned feature optimization with diffusion-driven reconstruction provides an effective pathway for producing high-fidelity, high-resolution geophysical fields and offers a promising foundation for subsequent applications in environmental modeling and weather prediction.



Keywords: Geophysical Fields Reconstruction,  Conditional Variational Autoencoder,  Diffusion Modelling,  Terrain–atmosphere interaction



```{admonition} Presentation Information
:class: note

**Submission ID:** 0206  
**Session:** [Epidemic Diffusion Reconstruction Observation](./Session_E9/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15
**Venue:** room 9
```