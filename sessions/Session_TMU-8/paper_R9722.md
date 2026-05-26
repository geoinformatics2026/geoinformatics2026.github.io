---
title: "Adaptive Physics-Informed Learning for Traffic Data Imputation with Spatiotemporal Heterogeneity Modeling"
authors:
- "Jiazheng Chen"
- "Xiaoyue Luo"
- "Shifen Cheng"
- "Peixiao Wang"
- "Feng Lu"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R9722.pdf
---

# Adaptive Physics-Informed Learning for Traffic Data Imputation with Spatiotemporal Heterogeneity Modeling

**Author Information**  
Jiazheng Chen<sup>1</sup>, Xiaoyue Luo<sup>1</sup>, Shifen Cheng<sup>1</sup>, Peixiao Wang<sup>1</sup>, Feng Lu<sup>1</sup>


<sup>1</sup> Institute of Geographic Sciences and Natural Resources Research  



## Abstract

Traffic data imputation is a fundamental task in intelligent transportation systems. Existing physics-informed deep learning methods typically employ shared feature extraction networks and global traffic flow parameters, ignoring the spatiotemporal heterogeneity of speed-flow coupling strength and station-level variation in fundamental diagram parameters. To address this, we propose the Adaptive Physics-Informed Spatiotemporal Heterogeneity Learning Network (API-HNet). API-HNet introduces a learnable bidirectional coupling mechanism based on cosine similarity to model heterogeneous speed-flow interactions. It treats free-flow speed and jam density as station-level learnable parameters and embeds them into a physics-consistency loss for end-to-end optimization physics-consistency loss. Experiments on real-world datasets from Shanghai and Seattle demonstrate that API-HNet outperforms nine baseline methods under random and block missing scenarios, reducing RMSE and MAE by 2% to 16% with comparable inference speed. The model also captures dynamic variations in coupling strength and learns spatial patterns of station-level parameters consistent with traffic flow theory, thereby enhancing physical interpretability.



Keywords: Traffic data imputation,  Spatiotemporal heterogeneity,  Physics-informed deep learning,  Intelligent transportation systems,  Fundamental diagram



Semantic Tags: traffic data imputation; spatiotemporal heterogeneity; physics-informed deep learning; intelligent transportation; fundamental diagram; speed-flow coupling; bidirectional coupling; station-level variation


```{admonition} Presentation Information
:class: note

**Submission ID:** R9722  
**Session:** [Intelligent Transportation Systems and Autonomous Driving ](./Session_TMU-8/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** SRC-Lv2-SR-D (Room-8)  
```