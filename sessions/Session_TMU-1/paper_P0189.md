---
title: "A Diffusion Transformer Framework with Geographical Information Enhancement for Trajectory Generation"
authors:
- "Juelin Li"
- "Meng Zhou"
- "Jiongxu Chen"
- "Jincheng Jiang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_P0189.pdf
---

# A Diffusion Transformer Framework with Geographical Information Enhancement for Trajectory Generation

**Author Information**  
Juelin Li<sup>1</sup>, Meng Zhou<sup>1</sup>, Jiongxu Chen<sup>1</sup>, Jincheng Jiang<sup>1</sup>


<sup>1</sup> Sun Yat-sen University  



## Abstract

The generation of realistic human trajectories is crucial for urban planning, mobility pattern analysis, and traffic management. However, it faces significant challenges including data sparsity, privacy concerns, and the difficulty of capturing complex spatiotemporal dependencies. This paper proposes a trajectory generation framework based on the Diffusion Transformer (DiT) architecture that effectively addresses these limitations. The approach first employs a convolutional autoencoder integrated with a geographical information enhancement module to extract local trajectory features and transform data into a lower-dimensional latent space. Then it utilizes modified DiT blocks enhanced with Rotary Position Encoding (RoPE) to explicitly model the temporal relationships within trajectory sequences during the diffusion process. Experimental results using a real-world trajectory dataset from Chengdu, China demonstrate that the model outperforms state-of-the-art methods in generating statistically consistent trajectories while preserving privacy. It provides a solution in the field of trajectory generation by effectively combining diffusion models with transformer architectures for enhanced spatiotemporal modeling.



Keywords: human mobility, trajectory generation, geographical information, diffusion transformer model



Semantic Tags: human mobility; trajectory generation; spatiotemporal modeling; diffusion transformer; generative model; convolutional autoencoder; privacy-preserving data; urban planning; traffic management; data sparsity; deep learning


```{admonition} Presentation Information
:class: note

**Submission ID:** P0189  
**Session:** [Geospatial Innovations for Sustainable Transportation and Urban Mobility](./Session_TMU-1/)  
**Theme:** Transportation, Mobility, and Urban Infrastructure    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** TP-Lv2-SR-E (Room-5/6)  
```