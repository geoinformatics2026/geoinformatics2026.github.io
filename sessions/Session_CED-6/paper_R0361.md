---
title: "Estimating spatiotemporal mobility dependence networks during natural disasters using the disruption graphical lasso"
authors:
- "Christopher Wagner"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R0361.pdf
---

# Estimating spatiotemporal mobility dependence networks during natural disasters using the disruption graphical lasso

**Author Information**  
Christopher Wagner<sup>1</sup>


<sup>1</sup> University of California, Santa Barbara  



## Abstract

Natural disasters are occurring with increasing frequency, creating a growing need to understand human mobility patterns in response to these disruptive events. In particular, it is important to characterize how geographic locations become interdependent through shared resources and evacuation pathways that help mitigate cascading impacts across regions. One underutilized statistical framework for studying these relationships is the Gaussian graphical model, which provides a representation of the conditional dependence structure between different locations in the form of a network, where edges represent partial correlations after controlling for all other locations. Most existing approaches for estimating Gaussian graphical models, which build off the Graphical Lasso framework, either assume a static network or are not designed to accommodate abrupt structural changes caused by extreme events such as natural disasters. To address this limitation, we introduce the disruption graphical lasso, a disaster-aware estimator for spatiotemporal graphical models that incorporates a novel temporal shock penalty to capture sudden disruptions in network structure. The resulting convex optimization problem is solved through an alternating direction method of multipliers (ADMM) algorithm, making network estimation fast and scalable to large spatiotemporal datasets. We evaluate the proposed approach using human mobility data from the 2019 wildfire in Sonoma County, California. Our results demonstrate that the method provides an interpretable and computationally efficient framework for identifying mobility coupling between geographic locations and for analyzing evolving spatial interaction patterns during natural disasters.



Keywords: network analysis,  human mobility,  spatiotemporal modeling,  natural disaster response



Semantic Tags: human mobility; natural disaster response; network analysis; spatiotemporal modeling; graphical lasso; evacuation; spatial dependence; Gaussian graphical model


```{admonition} Presentation Information
:class: note

**Submission ID:** R0361  
**Session:** [Flood Emergency Response and Evacuation Modeling ](./Session_CED-6/)  
**Theme:** Climate, Environmental Hazards, and Disaster Risk    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 16:30 – 17:45  
**Venue:** TP-Lv2-SR-E (Room-3/4)  
```