---
title: "GLCNet: Global-Local Correlation Network for Alpha Earth Foundation-Guided Remote Sensing Image Super-Resolution"
authors:
- "Hexin Wang"
- "Xiaojuan Li"
- "Tao Wang"
- "Yu Bai"
- "Lianwang Yin"

---

# GLCNet: Global-Local Correlation Network for Alpha Earth Foundation-Guided Remote Sensing Image Super-Resolution

**Author Information**  
Hexin Wang<sup>1</sup>, Xiaojuan Li<sup>1</sup>, Tao Wang<sup>1</sup>, Yu Bai<sup>1</sup>, Lianwang Yin<sup>2</sup>


<sup>1</sup> Capital Normal University  

<sup>2</sup> Moganshan Geospatial Information Laboratory  



## Abstract

High-resolution remote sensing imagery is fundamentally essential for precise geographic object identification and comprehensive Earth observation analysis. However, acquiring such high-quality data is frequently constrained by physical hardware limitations, long revisit cycles, and prohibitive costs. Consequently, Super-Resolution (SR) technology has emerged as a crucial computational solution to enhance spatial resolution. Despite recent advancements, traditional SR models rely heavily on low-level optical features. This over-reliance frequently results in the generation of artifacts that are visually plausible but geomorphologically and structurally inaccurate, limiting their reliability. Recently, the Alpha Earth Foundation (AEF) model has demonstrated exceptional capabilities in extracting robust, multi-modal semantic priors across vast geographic areas. To break the bottleneck of traditional SR networks that lack macroscopic global awareness, we pioneer the integration of AEF into the SR pipeline and propose the Global-Local Correlation Network (GLCNet). Methodologically, our architecture processes information progressively. First, a dedicated Global Branch extracts hierarchical macro-structural and land-cover semantics from the AEF model, while a concurrent Local Branch captures high-frequency optical details from the low-resolution inputs. Subsequently, to bridge the domain gap between macro-semantics and micro-details, we design a bidirectional Correlation Module employing cross-attention mechanisms. This module utilizes AEF's global priors to explicitly and dynamically guide local texture generation, ensuring physical structural constraints. Finally, a progressive reconstruction module, optimized with Generative Adversarial Network (GAN) strategies and Unsharp Masking, synthesizes the correlated features into high-fidelity images. Extensive experiments demonstrate that GLCNet significantly outperforms existing state-of-the-art methods in both quantitative metrics and perceptual quality. By rigorously preserving complex geometric structures and authentic textures, this method provides a highly reliable data foundation for demanding downstream geoinformatics applications, including high-precision urban infrastructure monitoring, disaster damage assessment, and fine-grained land cover mapping.



Keywords: Remote Sensing Image Super-Resolution,  Global-Local Correlation,  Alpha Earth Foundation,  Multimodal Feature Fusion



```{admonition} Presentation Information
:class: note

**Submission ID:** 4253  
**Session:** [Resolution Imagery Super Image](./Session_B3/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 14:45 – 16:15
**Venue:** room 3
```