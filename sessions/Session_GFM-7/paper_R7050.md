---
title: "Environmental-Dissimilarity-Based Cross Validation Framework for Evaluating Geospatial Machine Learning Prediction"
authors:
- "Yanwen Wang"
- "Qian Li"
- "Ju Wang"
- "Na Li"
- "Qi Lv"

---

# Environmental-Dissimilarity-Based Cross Validation Framework for Evaluating Geospatial Machine Learning Prediction

**Author Information**  
Yanwen Wang<sup>1</sup>, Qian Li<sup>1</sup>, Ju Wang<sup>1</sup>, Na Li<sup>1</sup>, Qi Lv<sup>1</sup>


<sup>1</sup> College of Meteorology and Oceanography, National University of Defense Technology  



## Abstract

Accurate evaluation of geospatial machine learning prediction is critical for reliable inferences and following decision makings, yet traditional random cross-validation (CV) often yields overly optimistic evaluations when samples and prediction locations differ in their underlying data distributions—a common scenario due to realistic non-uniform sampling. While spatial CV methods address this by enforcing separation between training and validation subsets, they treat the entire prediction domain as homogeneous and also might produce overly pessimistic results when dissimilarity between samples and prediction locations is mild. To overcome the limitations of current CV evaluations, we propose the Environmental-Dissimilarity-Based Cross-Validation (EDB-CV) framework, which tailors evaluation strategies to the degree of environmental dissimilarity between samples and prediction locations. A representative implementation, Dissimilarity-Adaptive CV, uses an Adversarial Validation classifier to assign a dissimilarity score to every prediction location, then partitions them into “similar” and “different” categories using a dynamic threshold. Random CV is applied to “similar” locations for precise error estimation, while spatial CV is used for “different” ones to account for distributional shifts. Final evaluation result is synthesized via a weighted average based on the areal proportions of each CV results. Experiments on synthetic species abundance and real aboveground biomass datasets demonstrate that Dissimilarity-Adaptive CV consistently provides the most accurate out-of-sample error estimates by adaptively balancing optimism and pessimism, especially under realistic, moderately clustered sampling. EDB-CV thus offers a context-aware and spatially explicit approach to evaluating geospatial machine learning predictions.



Keywords: Evaluation,  Environmental Dissimilarity,  Cross Validation,  Geospatial Prediction,  Machine Learning



Semantic Tags: geospatial machine learning; cross-validation; environmental dissimilarity; model evaluation; spatial prediction; training-validation dissimilarity; overfitting; prediction domain


```{admonition} Presentation Information
:class: note

**Submission ID:** R7050  
**Session:** [GeoAI, Foundation Models, and Spatial Learning ](./Session_GFM-7/)  
**Theme:** GeoAI, Foundation Models, and Spatial Machine Learning    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** LT-1  
```