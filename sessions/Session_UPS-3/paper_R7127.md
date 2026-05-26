---
title: "Beyond Visual Structure: Contextual Limits of Cross-City Urban Perception Modeling from Street-Level Semantics"
authors:
- "Aohua Tian"
- "Mark Lindquist"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R7127.pdf
---

# Beyond Visual Structure: Contextual Limits of Cross-City Urban Perception Modeling from Street-Level Semantics

**Author Information**  
Aohua Tian<sup>1</sup>, Mark Lindquist<sup>1</sup>


<sup>1</sup> University of Michigan  



## Abstract

Recent advances in computer vision and the widespread availability of street-level imagery have enabled large-scale quantitative modeling of subjective urban perception, such as safety, livability, and vibrancy. Most existing approaches implicitly assume that the relationship between visual features and human perception is universal and transferable across cities. This paper challenges this assumption by examining whether perception–feature mappings learned in one city can generalize to others with distinct cultural and morphological contexts. We construct a cross-city experimental framework using street view imagery from two highly contrasting cities—Ann Arbor, USA and Zibo, China. Semantic features are extracted via a pre-trained semantic segmentation pipeline, capturing proportional representations of key urban elements. To obtain scalable yet reliable perception labels, we introduce an LLM-based proxy scoring strategy that aggregates multiple independent model evaluations and filters ambiguous samples through uncertainty-aware standard deviation thresholding. Using an interpretable regression framework, we systematically evaluate in-domain learning, cross-city transferability, and temporal robustness across weekday/weekend and morning/afternoon conditions. Results show that urban perception is strongly learnable within individual cities, but cross-city transfer exhibits systemic failure, often yielding near-zero or negative explanatory power. Temporal alignment provides negligible improvement compared to spatial transfer, indicating that city context dominates over time-of-day variation. Feature attribution analysis further reveals that identical visual elements can exert contradictory effects on perception across cities. These findings suggest that urban perception is not a direct function of visual structure alone, but a context-dependent interpretation shaped by local socio-spatial norms. We argue for a shift from global perception models toward locally calibrated, context-aware urban AI systems.



Keywords: Urban Perception Modeling,  Street-Level Imagery,  Semantic Segmentation,  Cross-City Generalization,  Context-Aware Urban Analytics,  Large Language Models,  Explainable Machine Learning



Semantic Tags: urban perception modeling; street view imagery; semantic segmentation; cross-city generalization; context-aware analytics; large language model; explainable machine learning


```{admonition} Presentation Information
:class: note

**Submission ID:** R7127  
**Session:** [Street View Analytics and Urban Perception Modeling ](./Session_UPS-3/)  
**Theme:** Urban Analytics, Planning, and Socioeconomic Dynamics    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45  
**Venue:** SRC-Lv1-SR-A (Room-1/2)  
```