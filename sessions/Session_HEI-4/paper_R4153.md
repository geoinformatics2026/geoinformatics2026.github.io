---
title: "Optimizing Spatiotemporal Epidemic Control under Incomplete Observation"
authors:
- "Ling Yin"
- "Shang Wang"
- "Yuxiao Luo"
- "Yunduan Cui"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R4153.pdf
---

# Optimizing Spatiotemporal Epidemic Control under Incomplete Observation

**Author Information**  
Ling Yin<sup>1</sup>, Shang Wang<sup>1</sup>, Yuxiao Luo<sup>2</sup>, Yunduan Cui<sup>1</sup>


<sup>1</sup> Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences  

<sup>2</sup> Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences; The Hong Kong Polytechnic University  



## Abstract

Incomplete spatiotemporal observations of infections pose a major challenge to real-world epidemic control. Limited testing, reporting delays, underreporting, and asymptomatic infections distort perceived outbreak dynamics and can lead to suboptimal interventions. To address this issue, we propose a three-stage framework for spatiotemporal epidemic control under incomplete observations, integrating observation modeling, state reconstruction, and policy optimization. We first extend a metapopulation SEIQR model to capture spatiotemporally heterogeneous reporting rates and missing-observation mechanisms, and define three observability regimes: full observation, stationary partial observation, and non-stationary partial observation. We then develop ODE-DynNet, a hybrid reconstruction model that embeds mechanistic ordinary differential equation constraints into a graph-based spatiotemporal neural network to infer latent infection states from distorted observations in the non-stationary partial observation setting. Based on the reconstructed states, we formulate coordinated multi-regional intervention as a multi-agent reinforcement learning problem and optimize policies using multi-agent proximal policy optimization (MAPPO) with a mobility-flow-based, responsibility-aware reward to enhance inter-regional coordination. Experiments on a community-level mobility network in Shenzhen show that ODE-DynNet consistently outperforms mechanistic and data-driven baselines in reconstruction accuracy of real infections. Policies optimized from reconstructed states reduce the overall epidemic control cost by 88% compared with direct policy optimization under incomplete observations, approaching the performance achieved under full information. Further experiments across varying transmission intensities and missing-observation rates confirm the robustness and generalizability of the proposed framework. Our results demonstrate that mechanism-guided state reconstruction of infections can substantially improve epidemic control under severe observational uncertainty.



Keywords: epidemic control,  incomplete observation,  reinforcement learning,  spatiotemporal optimization



Semantic Tags: epidemic control; spatiotemporal optimization; reinforcement learning; incomplete observation; SEIQR model; public health intervention; metapopulation model; underreporting


```{admonition} Presentation Information
:class: note

**Submission ID:** R4153  
**Session:** [Spatial Epidemiology and Disease Modeling ](./Session_HEI-4/)  
**Theme:** Health, Equity, and Human-Environment Interactions    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SRC-Lv1-SR-C (Room-5)  
```