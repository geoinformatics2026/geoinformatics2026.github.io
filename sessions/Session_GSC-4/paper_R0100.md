---
title: "Paying for 3D: When Richer Spatial Representation Yields Little Gain"
authors:
- "Po-Yu Yeh"
- "Tzu-Cheng Cheng"
- "Peng-Hsiang Jen"
- "Chun-Hsiang Chan"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Paying for 3D: When Richer Spatial Representation Yields Little Gain

**Author Information**  
Po-Yu Yeh<sup>1</sup>, Tzu-Cheng Cheng<sup>2</sup>, Peng-Hsiang Jen<sup>1</sup>, Chun-Hsiang Chan<sup>1</sup>


<sup>1</sup> National Taiwan Normal University  

<sup>2</sup> National Taiwan University  



## Abstract

Recent work in geographic information science adopts richer spatial representations, including 3D city models and expanded contextual variables, under the belief that greater representational complexity yields better analytical outcomes. Yet richer representations raise computational cost, complicate real-time processing, and create friction for operational GIS systems, while their benefits are uncertain, especially when moving from 2D to 3D changes how proximity is measured. To clarify whether increased representational complexity is worthwhile, this study formalizes spatial representations as a rule for measuring distance and analyzes a broad class of distance-dependent methods, including accessibility measures, spatial optimization, and kernel-based inference. We assume representational refinement as a bi-Leibniz bounded perturbation of the induced metric, quantified by metric distortion, and show that consequences remain stable when pairwise distances change modestly. Based on the stability, we derive an explicit upper bound on the Value of Representation (VoR), defined as the performance gain achieved by refining representation, implying that improvement is limited unless refinement substantially reshapes the underlying distance structure. Furthermore, we present an easy example using kernel density estimation by comparing 2D and 3D induced distances and the resulting density surfaces, and we observe output deviations consistent with the predicted stability. Overall, this result offers a theoritical pre-check for representational refinement via metric distortion to check if added complexity is likely to deliver meaningful gains, enabling cost aware and energy aware choices in sustainability oriented workflows such as city scale accessibility monitoring, service coverage planning, and spatial decision support where unnecessary representational upgrades translate into avoidable computation, latency, and operational overhead.



Keywords: Spatial representation,  Representation complexity,  Metric distortion,  GIScience theory




```{admonition} Presentation Information
:class: note

**Submission ID:** R0100  
**Session:** [Geographical Principles in Spatial Analysis and Modeling](./Session_GSC-4/)  
**Theme:** GIScience Theory, Spatial Statistics \& Methods    
**Date:** Day 2, 21 July (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Lecture Theatre 51 (LT-51)  
```