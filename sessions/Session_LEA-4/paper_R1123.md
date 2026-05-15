---
title: "FGCBAM-RAFT: Optical Flow Estimation with Flow-Guided Attention for Natural Rivers"
authors:
- "Xue Yang"
- "Xiaolan Chen"

---

# FGCBAM-RAFT: Optical Flow Estimation with Flow-Guided Attention for Natural Rivers

**Author Information**  
Xue Yang<sup>1</sup>, Xiaolan Chen<sup>1</sup>


<sup>1</sup> China University of Geosciences (Wuhan)  



## Abstract

In recent years, non-contact vision-based measurement technology, with its advantages of safety and high efficiency, has gradually become a core method for emergency flow velocity monitoring during river flood seasons. However, illumination fluctuations, sparse water surface textures, and severe local deformations in real-world field environments can easily lead to the degradation of image features, which severely restricts the final accuracy of flow velocity inversion. To address the common limitations of matching failure and insufficient robustness in traditional optical flow algorithms when dealing with the aforementioned strong environmental interferences and highly dynamic water surface scenes, this paper proposes an optical flow-guided attention mechanism model (FGCBAM-RAFT). This design breaks the "motion blind zone" of conventional attention mechanisms and innovatively introduces real-time optical flow priors into the computational dimensions of channel and spatial features, achieving a deep coupling between static visual representations and dynamic physical motions. Meanwhile, the adaptive gating mechanism and cold-start strategy built into the module not only effectively shield against error interference from inaccurate optical flow during the early stages of training, but also endow the network with the ability to dynamically adjust attention intensity. This mechanism significantly enhances the model's focusing accuracy on high-frequency dynamic details such as complex water wave textures, and improves the robustness and accuracy of non-contact flow measurement. To verify the effectiveness of the proposed method, comparative experiments were conducted on multiple natural river datasets. Quantitative and qualitative evaluation results demonstrate that the proposed method achieves improvements in both prediction accuracy and algorithmic robustness across the vast majority of natural river scenes.



Keywords: Optical Flow Estimation,  Attention Mechanism,  Non-contact Velocimetry,  Surface Velocity,  Flow-Guided



Semantic Tags: river flow velocity; optical flow estimation; attention mechanism; non-contact measurement; surface velocity; deep learning; flood monitoring


```{admonition} Presentation Information
:class: note

**Submission ID:** R1123  
**Session:** [Ecosystem Monitoring and Land Surface Dynamics ](./Session_LEA-4/)  
**Theme:** Land, Ecology, Agriculture, and Sustainable Development    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SR-D  
```