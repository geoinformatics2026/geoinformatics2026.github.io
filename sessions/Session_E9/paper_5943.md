---
title: "A wind-physics informed neural network with spatial-temporal-variable fusion for predicting multiple air pollutants"
authors:
- "Xinmeng Zhou"
- "Qingfeng Guan"

---

# A wind-physics informed neural network with spatial-temporal-variable fusion for predicting multiple air pollutants

**Author Information**  
Xinmeng Zhou<sup>1</sup>, Qingfeng Guan<sup>1</sup>


<sup>1</sup> School of Geography and Information Engineering, China University of Geosciences, Wuhan, 430078, China  



## Abstract

Accurate forecasting of air quality is essential for urban sustainability and public health, yet remains challenging due to the complex interplay of meteorological dynamics and inter-pollutant interactions. Existing data-driven models often overlook the physical laws governing pollutant diffusion, typically treating wind fields as static inputs and failing to capture their dynamic spatial continuity. Here we propose a Wind-Physics Informed Neural Network with Spatial-Temporal-Variable Fusion (WPINN-STVF) for multi-pollutant prediction. Our framework introduces a wind-aware graph construction mechanism that dynamically encodes wind-guided pollutant diffusion paths into the topological structure, effectively capturing directional transport. This is coupled with a multi-dimensional feature extraction and fusion scheme that simultaneously learns and integrates temporal dependencies, spatial correlations, and variable interactions. We validate our approach on datasets from Beijing, Wuhan, and London, demonstrating that WPINN-STVF consistently outperforms eight state-of-the-art baselines, achieving error reductions of up to 23% for 24-hour forecasts and significant improvements in long-term predictions (R² increases of 2–13 percentage points). This physics-informed paradigm not only enhances the reliability of fine-scale air quality forecasts but also provides a generalizable strategy for integrating heterogeneous physical processes into deep learning models for broader urban computing tasks.



Keywords: Air quality prediction,  Wind field modeling,  Multi-source information fusion



```{admonition} Presentation Information
:class: note

**Submission ID:** 5943  
**Session:** [Epidemic Diffusion Reconstruction Observation](./Session_E9/) 
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15
**Venue:** room 9
```