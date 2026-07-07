---
title: "Urban Spatial Universal Representation Integrating Multi-modal Data and Semi-supervised Graph Neural Networks"
authors:
- "Junxian Yu"
- "Wei Tu"
- "Jinzhou Cao"
- "Zhaoyue Cai"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# Urban Spatial Universal Representation Integrating Multi-modal Data and Semi-supervised Graph Neural Networks

**Author Information**  
Junxian Yu<sup>1</sup>, Wei Tu<sup>2</sup>, Jinzhou Cao<sup>3</sup>, Zhaoyue Cai<sup>1</sup>


<sup>1</sup> School of Architecture and Urban Planning, Shenzhen University, Shenzhen, Guangdong, China  

<sup>2</sup> Shenzhen Key Laboratory of Spatial Information Smart Sensing and Services, Shenzhen, Guangdong, China  

<sup>3</sup> School of Artificial Intelligence, Shenzhen Technology University, Shenzhen, Guangdong, China  



## Abstract

Facing the demand for multi-factor collaborative perception and integrated assessment in urban monitoring and physical examination, traditional paradigms that rely on single-modal data and task-specific independent modeling fail to capture inter-factor associations and show limited transferability under small-sample settings. This study aims to construct a method for urban spatial universal representation that integrates multi-modal data and semi-supervised graph neural networks. The framework first builds heterogeneous feature encoding mechanisms for visual, vector, and trajectory data; constructs an urban graph with spatial units as nodes and population flow relations as edges; and adopts semi-supervised graph neural networks to achieve deep fusion of multi-modal features with graph topology. Cross-task attention, dynamic multi-task relation modeling, and similarity-based feature weighting and fusion are then used to realize a progressive mapping from spatial universal representation to multi-task adaptation. Experiments on six urban tasks in Shenzhen—population distribution, travel flow, GDP, housing price level, land-use mix index, and PM2.5 concentration—show that the proposed model reaches an average prediction R² of 0.763, improving about 12%–19% over baselines; at the multi-task stage, further gains are observed on GDP, housing price, and PM2.5, with housing price R² rising from 0.54 to 0.79, validating the effectiveness of multi-task knowledge sharing. This work provides a transferable and reusable foundation for urban spatial universal representation in support of urban intelligent monitoring, physical examination, and evaluation, reveals the impact of task heterogeneity on universal representation performance, and points to directions for future improvement.



Keywords: Urban spatial representation,  Multi-modal data,  Semi-supervised learning,  Graph neural network,  Multi-task learning,  Urban physical examination




```{admonition} Presentation Information
:class: note

**Submission ID:** R0617  
**Session:** [Spatiotemporal Modeling and Graph Neural Networks](./Session_GSC-8/)  
**Theme:** GIScience Theory, Spatial Statistics \& Methods    
**Date:** Day 3, 22 July (Wednesday)  
**Time:** 10:45 – 12:00  
**Venue:** Town Plaza-02-Seminar Room 5 & 6 (SR-F)  
```