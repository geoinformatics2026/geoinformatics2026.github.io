---
title: "Beyond Visual Structure: Contextual Limits of Cross-City Urban Perception Modeling from Street-Level Semantics"
authors:
- "Aohua Tian"
- "Mark Lindquist"

---

# Beyond Visual Structure: Contextual Limits of Cross-City Urban Perception Modeling from Street-Level Semantics

**Author Information**  
Aohua Tian<sup>1</sup>, Mark Lindquist<sup>1</sup>


<sup>1</sup> University of Michigan  



## Abstract

Recent advances in computer vision and the widespread availability of street-level imagery have enabled large-scale quantitative modeling of subjective urban perception, such as safety, livability, and vibrancy. Most existing approaches implicitly assume that the relationship between visual features and human perception is universal and transferable across cities. This paper challenges this assumption by examining whether perception–feature mappings learned in one city can generalize to others with distinct cultural and morphological contexts.  We construct a cross-city experimental framework using street view imagery from two highly contrasting cities—Ann Arbor, USA and Zibo, China. Semantic features are extracted via a pre-trained semantic segmentation pipeline, capturing proportional representations of key urban elements. To obtain scalable yet reliable perception labels, we introduce an LLM-based proxy scoring strategy that aggregates multiple independent model evaluations and filters ambiguous samples through uncertainty-aware standard deviation thresholding.  Using an interpretable regression framework, we systematically evaluate in-domain learning, cross-city transferability, and temporal robustness across weekday/weekend and morning/afternoon conditions. Results show that urban perception is strongly learnable within individual cities, but cross-city transfer exhibits systemic failure, often yielding near-zero or negative explanatory power. Temporal alignment provides negligible improvement compared to spatial transfer, indicating that city context dominates over time-of-day variation. Feature attribution analysis further reveals that identical visual elements can exert contradictory effects on perception across cities.  These findings suggest that urban perception is not a direct function of visual structure alone, but a context-dependent interpretation shaped by local socio-spatial norms. We argue for a shift from global perception models toward locally calibrated, context-aware urban AI systems.



Keywords: Urban Perception Modeling,  Street-Level Imagery,  Semantic Segmentation,  Cross-City Generalization,  Context-Aware Urban Analytics,  Large Language Models,  Explainable Machine Learning



```{admonition} Presentation Information
:class: note

**Submission ID:** 7127  
**Session:** [Perception Perceived Street Path](./Session_G6/) 
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00
**Venue:** room 6
```