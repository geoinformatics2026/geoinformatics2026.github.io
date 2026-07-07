---
title: "Cross-Regional Building Damage Mapping with Prototype-Based Spatial Representation Learning"
authors:
- "Liwei Zou"
- "Wenping Yin"
- "Hao Li"
- "Wufan Zhao"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Cross-Regional Building Damage Mapping with Prototype-Based Spatial Representation Learning

**Author Information**  
Liwei Zou<sup>1</sup>, Wenping Yin<sup>2</sup>, Hao Li<sup>3</sup>, Wufan Zhao<sup>1</sup>


<sup>1</sup> Urban Governance and Design Thrust, Society Hub, Hong Kong University of Science and Technology (Guangzhou)  

<sup>2</sup> School of Environment and Spatial Informatics, China University of Mining and Technology  

<sup>3</sup> Department of Geography, National University of Singapore  



## Abstract

Climate change is intensifying natural hazards and increasing the frequency of disruptive urban damage events. Rapid and reliable building damage mapping is essential for emergency response, resource allocation, and reconstruction planning. Traditional approaches rely on field surveys or region-specific supervised models, which are time-consuming and difficult to generalize across disaster contexts. Recent advances in vision foundation models (FMs) have demonstrated strong representational capability in remote sensing, offering new opportunities for scalable disaster assessment. However, damage mapping remains challenging. Post-disaster annotations are limited in quantity and heterogeneous in quality, and damage patterns vary due to differences in urban morphology, construction materials, and hazard intensity across regions. These factors constrain representation consistency and limit transferability. To address these challenges, we propose a prototype-based spatial representation learning framework for cross-regional building damage mapping. It is implemented as a transferable segmentation model based on DINOv3 with a lightweight decoder. Rather than treating annotation noise as purely detrimental, we build on the insight that even imperfect annotations contain meaningful structural information that can guide transferable representation learning. As a solution, the framework incorporates a prototype consistency mechanism that aligns pixel features with class-specific prototypes representing typical damaged and intact patterns, such as debris textures and intact roof surfaces. These prototypes are derived from labeled imagery embeddings through pixel-wise clustering. This representation-level regularization enhances class separability, mitigates noisy supervision, and strengthens cross-domain generalization. Experiments across multiple cities affected by the 2023 Turkey-Syria earthquake demonstrate improved cross-regional consistency and predictive stability. Compared with direct transfer, the proposed framework improves mIoU from 0.6851 to 0.6932 under cross-domain evaluation, indicating stronger transferability and robustness to regional variation. These findings highlight the value of structured spatial representation learning for reliable cross-regional damage assessment in real-world disaster response scenarios, towards responsible development and usage of GeoAI at scale.



Keywords: Building Damage Mapping,  Vision Foundation Models,  Spatial Representation Learning,  Cross-Domain Transfer,  Remote Sensing Analysis




```{admonition} Presentation Information
:class: note

**Submission ID:** R1577  
**Session:** [GeoAI and Data Science for Disaster Resilience](./Session_CED-1/)  
**Theme:** Climate, Env. Hazards \& Disaster Risk    
**Date:** Day 1, 20 July (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** Town Plaza-02-Seminar Room 3 & 4 (SR-E)  
```