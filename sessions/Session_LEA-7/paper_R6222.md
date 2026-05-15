---
title: "Self-Supervised Spatio-Temporal Transformer Foundation Model for UAV-Based Yield Prediction in Crop Breeding"
authors:
- "Guofeng Yang"
- "Ling Qing"
- "Yong He"

---

# Self-Supervised Spatio-Temporal Transformer Foundation Model for UAV-Based Yield Prediction in Crop Breeding

**Author Information**  
Guofeng Yang<sup>1</sup>, Ling Qing<sup>1</sup>, Yong He<sup>2</sup>


<sup>1</sup> Southwest University  

<sup>2</sup> Zhejiang University  



## Abstract

Crop yield prediction and efficient selection of superior genotypes remain central challenges in modern breeding, hindered by environmental variability, management heterogeneity, and the cost of high-throughput phenotyping. We propose an integrated yield prediction and decision-support framework that combines multi-source UAV remote sensing, temporal growth modeling, advanced deep learning, and a multimodal large language model (MLLM) to improve accuracy, robustness, and interpretability across genotypes, growth stages, and environments. UAV platforms equipped with hyperspectral, multispectral, RGB, and LiDAR sensors capture complementary signals of crop physiology, canopy structure, and field heterogeneity. We derive plot-level phenotypes (chlorophyll-related indices, leaf area index, plant height, canopy coverage, and weed stress) and organize them into multimodal time series from vegetative stages to maturity. We introduce a self-supervised spatio-temporal foundation model (STFM) with lightweight task adapters for long-sequence yield prediction. The STFM uses a hierarchical temporal Transformer: multi-sensor features are tokenized into a unified sequence with time-gap aware positional encoding for irregular flight intervals. Multi-head self-attention captures long-range dependencies, and attention pooling aggregates key time windows for yield regression. To model spatial heterogeneity, a graph attention / neighborhood message passing module is applied per time step, with graphs built from geographic adjacency or experimental replicates to suppress environmental noise. Gated cross-modal fusion and modality dropout improve robustness under missing modalities. Pretraining optimizes masked reconstruction and temporal contrastive (InfoNCE) objectives on large unlabeled UAV time series; fine-tuning freezes the backbone and trains only parameter-efficient adapters (Adapter/LoRA) and task heads using a joint regression–ranking loss to optimize yield prediction and Top-k genotype selection. The MLLM aligns model outputs with agronomic knowledge to generate breeder-oriented explanations and hypotheses. Across multi-genotype, multi-environment wheat trials, the framework reduces the RMSE of yield predictions to 0.2–1.0 t/ha, increases R2 by 0.05–0.20, and boosts Top-k selection accuracy by 8%–25%.



Keywords: UAV remote sensing,  Crop yield prediction,  Spatio-temporal Transformer,  Self-supervised learning,  Multimodal large language model



Semantic Tags: crop yield prediction; UAV remote sensing; spatio-temporal transformer; self-supervised learning; multimodal large language model; crop breeding; hyperspectral imagery


```{admonition} Presentation Information
:class: note

**Submission ID:** R6222  
**Session:** [Crop Mapping and Precision Agriculture ](./Session_LEA-7/)  
**Theme:** Land, Ecology, Agriculture, and Sustainable Development    
**Date:** Day 3 — 22 July 2026 (Wednesday)  
**Time:** 09:00 – 10:30  
**Venue:** LT-2  
```