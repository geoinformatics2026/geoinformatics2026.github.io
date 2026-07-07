---
title: "RoadAgent: A Dual-Agent Framework for Topology-Aware Repair of Crowdsourced Road Networks"
authors:
- "Ce Hou"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# RoadAgent: A Dual-Agent Framework for Topology-Aware Repair of Crowdsourced Road Networks

**Author Information**  
Ce Hou<sup>1</sup>


<sup>1</sup> University of California, Berkeley  



## Abstract

While volunteered geographic information platforms like OpenStreetMap have democratized spatial data, they are currently facing an impact bottleneck constrained by heterogeneous data quality. Manual topological repair is prohibitively expensive, whereas traditional rulebased algorithms lack morphological adaptability, and pure deep learning models often generate physically invalid results that destroy graph structures. To overcome these limitations, we propose RoadAgent, a dual-agent automated repair framework. In this study, two versions of framework are proposed: a rule-based heuristic version (RoadAgent) and a Multi-Agent Reinforcement Learning optimized version (RoadAgent-MAPPO). This framework utilizes a NodeAgent for geometry simplification and an Edge-Agent for topology connection. Evaluated on crowdsourced road networks across five major Chinese cities, RoadAgent and RoadAgentMAPPO achieve state-of-the-art performance, significantly outperforming classical geometric and deep learning baselines. Specifically, it attains the lowest graph edit distance and connected component error, alongside the highest Edge F1-score and highly efficient inference. Beyond algorithmic innovation, this work advocates an AI-assisted paradigm that transforms laborious manual review into automated data governance, establishing a scalable digital foundation for global high-precision urban computing and the long-term sustainability of the open-source geographic ecosystem. The code is available at https://github.com/CeHouGIS/RoadAgent.



Keywords: Volunteered Geographic Information, Multi-Agent Reinforcement Learning, OpenStreetMap, GeoAI, Topological Repair




```{admonition} Presentation Information
:class: note

**Submission ID:** S0014  
**Session:** [Student competition - Part 1](./Session_GSC-1/)  
**Theme:** GIScience Theory, Spatial Statistics \& Methods    
**Date:** Day 1, 20 July (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** Stephen Riady Centre-01-Seminar Room 6 (SR-D)  
```