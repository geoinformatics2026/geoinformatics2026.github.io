---
title: "TransMode-LLM: Knowledge-Infused LLM Adaptation toward Individual Transportation Modes Recognition in GPS Trajectories"
authors:
- "Yang Zhan"
- "Yan Li"
- "Yu Zhang"
- "Zehao Yuan"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R0286.pdf
---

# TransMode-LLM: Knowledge-Infused LLM Adaptation toward Individual Transportation Modes Recognition in GPS Trajectories

**Author Information**  
Yang Zhan<sup>1</sup>, Yan Li<sup>2</sup>, Yu Zhang<sup>3</sup>, Zehao Yuan<sup>2</sup>


<sup>1</sup> School of Artificial Intelligence, Optics, and Electronics (iOPEN), Northwestern Polytechnical University  

<sup>2</sup> State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing, Wuhan University  

<sup>3</sup> Institute of AI for Industries, Chinese Academy of Sciences  



## Abstract

Large language models (LLMs) have recently demonstrated successful adaptability across various domains via instruction tuning, obtaining impressive capabilities. Identifying individual transportation modes from GPS trajectories is vital for smart city development, yet existing methods often lack the flexibility to handle complex urban scenarios or fail to fully leverage the reasoning capabilities of LLMs. In this work, we introduce the TransMode-LLM, a novel framework that seamlessly integrates transportation knowledge embedding with the instruction-tuning paradigm. Specifically, we introduce a segment-level transportation information modeling method. This method maps raw trajectories to road networks to capture eleven travel features (e.g., speed, acceleration) and five GIS features (e.g., proximity to bus/metro routes). Since LLMs cannot directly interpret this information, we present a transportation knowledge embedder. To bridge the modality gap, we employ a projection layer and a time prompt embedding mechanism to help the LLM understand travel behavior semantics and traffic cycles (workdays vs. non-workdays). To facilitate more accurate responses and instruction-following ability, we design a transportation mode instruction-tuning strategy to generate answers. Utilizing a frozen LLaMA-2 backbone with Low-Rank Adaptation (LoRA), the model is trained to generate textual answers following a specific instruction template, rather than performing simple regression. We also contribute HunMob-ChCh, a large-scale, continuous mobility dataset featuring 1,500 volunteers and nine transportation categories. Extensive experiments demonstrate that TransMode-LLM significantly outperforms 13 state-of-the-art baselines, including traditional deep learning and trajectory foundation models. It achieves an overall F1-score of 92.58% on workdays and 88.90% on non-workdays, proving its robustness and superior generalization. The results highlight the effectiveness of aligning domain-specific knowledge with the generative power of LLMs for advanced mobility data mining.



Keywords: Transportation Modes Recognition,  Multimodal Fusion,  GPS Trajectories,  Large Language Models,  Instruction Tuning



Semantic Tags: transportation mode recognition; GPS trajectory; large language model; multimodal fusion; instruction tuning; smart city; deep learning; urban mobility


```{admonition} Presentation Information
:class: note

**Submission ID:** R0286  
**Session:** [Urban Mobility, Travel Demand, and Spatiotemporal Transit Analytics ](./Session_TMU-3/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 16:30 – 17:45  
**Venue:** TP-Lv2-SR-E (Room-5/6)  
```