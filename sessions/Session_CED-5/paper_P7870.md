---
title: "Cross-Domain Knowledge Reuse from Remote Sensing Foundation Models for Flood-Damaged Building Extraction in Data-Constrained and Class-Imbalanced Scenarios"
authors:
- "Bowen Xiao"
- "Qingxiang Meng"
- "Yuanfu Gong"
- "Liang Zhou"
- "Yizhang Huang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_P7870.pdf
---

# Cross-Domain Knowledge Reuse from Remote Sensing Foundation Models for Flood-Damaged Building Extraction in Data-Constrained and Class-Imbalanced Scenarios

**Author Information**  
Bowen Xiao<sup>1</sup>, Qingxiang Meng<sup>1</sup>, Yuanfu Gong<sup>2</sup>, Liang Zhou<sup>3</sup>, Yizhang Huang<sup>3</sup>


<sup>1</sup> Wuhan University  

<sup>2</sup> Hubei Institute of Land Surveying and Mapping  

<sup>3</sup> Shanghai Electric Power Company  



## Abstract

Flood-induced building damage assessment from high- resolution remote sensing imagery plays a critical role in rapid disaster response and post-event recovery planning. However, mainstream deep learning approaches heavily depend on large- scale annotated datasets. In practical disaster scenarios, labeled data are often limited and exhibit severe class imbalance across damage categories and geographic regions. Under such data- constrained conditions, existing transfer learning strategies struggle to effectively align generic semantic representations with disaster-specific damage characteristics, resulting in unstable cross-region generalization. To address these challenges, we propose FDBA-Net, a structured cross-domain knowledge reuse framework that transfers semantic priors from remote sensing foundation models to flood-damaged building extraction tasks in data-constrained and class-imbalanced settings. The framework adopts a parameter-shared Siamese architecture to process bi- temporal imagery while preserving the representational capacity of a frozen foundation model. A Cross-Domain Knowledge Reuse Linking module adaptively aligns and fuses foundation-level features with task-specific representations through affinity-based feature filtering and residual integration. Furthermore, an object- oriented post-processing strategy refines pixel-wise predictions into instance-level damage labels, enhancing semantic consistency within building objects. A multi-task joint loss collaboratively optimizes building localization and damage classification branches. Experiments on the xBD-Flooded datasets demonstrate that FDBA-Net consistently outperforms state-of-the-art methods under severe class imbalance. These results indicate that structured cross-domain knowledge reuse from remote sensing foundation models provides a robust and scalable solution for disaster-oriented building damage extraction in real-world data- constrained scenarios.



Keywords: Flood-Damaged Building Extraction, Cross-Domain Knowledge Reuse, Remote Sensing Foundation Models



Semantic Tags: flood damage assessment; building extraction; deep learning; cross-domain transfer; foundation model; class imbalance; disaster response; remote sensing


```{admonition} Presentation Information
:class: note

**Submission ID:** P7870  
**Session:** [Flood Risk, Detection, and Urban Resilience ](./Session_CED-5/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 14:45 – 16:15  
**Venue:** TP-Lv2-SR-E (Room-3/4)  
```