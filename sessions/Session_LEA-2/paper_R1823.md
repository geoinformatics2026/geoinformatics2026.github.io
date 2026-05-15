---
title: "Spatially-explicit artificial intelligence framework for post-disaster telecommunication infrastructure network restoration"
authors:
- "Jiale Qian"
- "Nan Zhang"
- "Fan Zhang"
- "Yunyan Du"

---

# Spatially-explicit artificial intelligence framework for post-disaster telecommunication infrastructure network restoration

**Author Information**  
Jiale Qian<sup>1</sup>, Nan Zhang<sup>1</sup>, Fan Zhang<sup>2</sup>, Yunyan Du<sup>3</sup>


<sup>1</sup> School of Public Policy and Management, Tsinghua University  

<sup>2</sup> Institute of Remote Sensing and Geographical Information Systems, School of Earth and Space Sciences, Peking University  

<sup>3</sup> Institute of Geographic Sciences and Natural Resources Research, Chinese Academy of Sciences  



## Abstract

Natural disasters pose a significant threat to critical urban infrastructure, particularly  telecommunication networks, leading to widespread coverage loss that hampers emergency response. Rapid network recovery is a complex, large-scale spatial optimization problem, where traditional optimization approaches fail to scale to the vast decision spaces encountered in real urban networks, making them unsuitable for emergency response scenarios requiring immediate action. To address this challenge, this paper introduces a spatially-explicit artificial intelligence (AI) framework Fast-Restore that fundamentally integrates geographic intelligence with artificial intelligence for network restoration. The core innovation of Fast-Restore lies in recognizing that spatial relationships between base stations are not merely background information, but critical structural knowledge that can dramatically reduce computational complexity and improve decision quality. The framework transforms an astronomically large optimization problem into a tractable one by using geographic proximity to intelligently prune the search space, employing graph neural networks to learn spatial interdependencies between network components, and applying deep reinforcement learning to sequentially select optimal restoration actions based on geographic impact. We apply this framework to a real-world case study of a network comprising over 28,000 base stations affected by a typhoon. The system identified a 0.021 square degree coverage loss area. The Fast-Restore solver, by adjusting only 78 base stations, successfully restored over 79% of this lost coverage in under 16 minutes. The study demonstrates that the fusion of modern AI techniques with explicit geospatial analysis provides a powerful, efficient, and scalable solution for post-disaster infrastructure management, offering a valuable decision support tool for enhancing urban resilience.



Keywords: Disaster resilience,  Telecommunication infrastructure,  Network restoration,  Geospatial artificial intelligence,  Spatial optimization



Semantic Tags: disaster resilience; telecommunication infrastructure; network restoration; GeoAI; spatial optimization; reinforcement learning; emergency response


```{admonition} Presentation Information
:class: note

**Submission ID:** R1823  
**Session:** [GeoAI-Facilitated Energy Geographies](./Session_LEA-2/)  
**Theme:** Land, Ecology, Agriculture, and Sustainable Development    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15  
**Venue:** LT-2  
```