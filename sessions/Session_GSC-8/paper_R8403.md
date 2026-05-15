---
title: "A Structure-Guided Diffusion Framework for Spatiotemporal Inference under Incomplete Observations"
authors:
- "Xiaoyue Luo"
- "Shifen Cheng"
- "Feng Lu"

---

# A Structure-Guided Diffusion Framework for Spatiotemporal Inference under Incomplete Observations

**Author Information**  
Xiaoyue Luo<sup>1</sup>, Shifen Cheng<sup>1</sup>, Feng Lu<sup>1</sup>


<sup>1</sup> Institute of Geographic Sciences and Natural Resources Research, Chinese Academy of Sciences  



## Abstract

Diffusion models, with stable training, generative distribution modeling, and principled uncertainty quantification, have shown great promise for spatiotemporal inference under incomplete observations. Structured spatiotemporal information is crucial for enhancing the accuracy and reliability of diffusion-based inference; however, under conditions of missing data and sparse supervision, it remains challenging to continuously inject and preserve such structure throughout the multi-step denoising process. Specifically: (i) existing conditional diffusion approaches typically use only sparse observations or their local features as conditioning signals, whose constraining effect tends to diminish over the course of iterative reverse denoising, making it difficult for the generated results to consistently preserve spatial correlations and regional heterogeneity; (ii) under sparse supervision, high-dimensional spatiotemporal denoising networks often require a large number of parameters to capture complex patterns, while effective learning signals are available only at a limited set of observed locations, leading to a pronounced mismatch between model capacity and supervision, reduced learning efficiency, and unstable inference. To address these issues, this paper proposes a structure-guided tensorized diffusion framework (DiffSDH). Its core innovations are: first, structural information characterized by spatiotemporal dependencies and heterogeneity is continuously injected into the reverse denoising process to improve the reliability and stability of inference under sparse observations; second, a parameter-efficient tensorized denoising architecture is designed, leveraging efficient denoising strategies to enhance learning efficiency under limited supervision. Experiments on real-world datasets demonstrate that DiffSDH significantly outperforms state-of-the-art baselines across diverse data types and missing-rate scenarios. In the data imputation task, DiffSDH achieves RMSE and MAE improvements ranging from 24.37% to 64.00%; in forecasting tasks, the performance gains range from 8.22% to 61.41%. Notably, under high missing rates and irregular observation patterns, DiffSDH not only delivers substantial gains in quantitative metrics such as RMSE and MAE, but also produces spatial patterns that are more consistent with underlying physical processes.



Keywords: Spatiotemporal inference,  Diffusion model,  Spatiotemporal heterogeneity,  Tensor decomposition



Semantic Tags: spatiotemporal inference; diffusion model; missing data; tensor decomposition; spatiotemporal heterogeneity; uncertainty quantification; incomplete observation; structure-guided inference


```{admonition} Presentation Information
:class: note

**Submission ID:** R8403  
**Session:** [Spatiotemporal Modeling and Graph Neural Networks](./Session_GSC-8/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** SR-D  
```