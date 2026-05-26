---
title: "From voice to authority: divergence-based participatory optimization for land use layouts generation"
authors:
- "Yun Han"
- "Xiaohu Zhang"

exports:
  - format: pdf
    template: arxiv_nips
    output: pdf/paper_R7218.pdf
---

# From voice to authority: divergence-based participatory optimization for land use layouts generation

**Author Information**  
Yun Han<sup>1</sup>, Xiaohu Zhang<sup>1</sup>


<sup>1</sup> The Department of Urban Planning and Design; The University of Hong Kong  



## Abstract

High-density urban renewal can intensify socio-political marginalization when rising land values and tight timelines shift attention from everyday services to redevelopment value. When participatory feedback is not encoded in a comparable and computable form---because it remains fragmented and qualitative---vulnerable groups' needs are more likely to be sidelined. This thesis develops an auditable participation-to-optimization pipeline that converts heterogeneous stakeholder preferences into computable inputs for multi-objective optimization of land use and building layout. The study proposes an agent-orchestrated, LLM-assisted consensus framework for renewal planning, with a constant, auditable optimization core and updatable participation modules across iterations. Orchestration agents manage a traceable generate--optimize--evaluate loop, while LLM-based behavioral agents approximate residents' preferences and decision-making. Phase I builds a dual-track preference model: scenario simulations establish a testable baseline of trade-offs, then stated-preference evidence fine-tunes the model while preserving inter-group heterogeneity. Phase II extends NSGA-II with plan-realistic constraints (e.g., building height limits, FAR controls, and setbacks) and incorporates economic feasibility alongside social accessibility objectives; the decision space and procedural layout generator remain constant so outcome changes are attributable to preference updates. Phase III updates objective weights based on stakeholder evaluations of Pareto-optimal plans and stops when inter- and intra-group divergence falls below a threshold, enabling analysis of convergence patterns, disagreement, and the trade-offs implied by consensus. A Hong Kong case study shows that this agent-orchestrated, divergence-aware loop can reduce inter-group disagreement while maintaining feasibility and improving daily-service accessibility at a controlled economic cost.



Keywords: Generative urban design,  Participatory optimization,  Land use layout,  Divergence-based consensus



Semantic Tags: participatory urban design; generative urban design; land use layout; divergence-based consensus; multi-objective optimization; stakeholder preferences; urban renewal


```{admonition} Presentation Information
:class: note

**Submission ID:** R7218  
**Session:** [Urban Planning, Renewal, and Socioeconomic Transformation ](./Session_UPS-4/)  
**Theme:** Urban Analytics, Planning, and Socioeconomic Dynamics    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SRC-Lv1-SR-A (Room-1/2)  
```