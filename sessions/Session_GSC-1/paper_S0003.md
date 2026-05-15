---
title: "DirTraj: Behavior-Grounded OD-Conditioned Continuous-Time Route Prediction on Road Networks"
authors:
- "Xin Jin"

---

# DirTraj: Behavior-Grounded OD-Conditioned Continuous-Time Route Prediction on Road Networks

**Author Information**  
Xin Jin<sup>1</sup>


<sup>1</sup> The Chinese University of Hong Kong  



## Abstract

Trajectory prediction on urban road networks is important for a wide range of mobility applications, such as ride-hailing route anticipation, courier route forecasting, and navigation support. However, existing methods often struggle with irregularly sampled GPS observations and rarely model how drivers jointly balance destination direction and turning effort at intersections. This paper proposes DirTraj, a behavior-grounded OD-conditioned continuous-time forecasting framework that predicts the next road edge. DirTraj represents trajectories as sequences of network-constrained decisions enriched with two interpretable directional signals, namely goal-pointing and least-turning. A Neural Ordinary Differential Equation (Neural ODE) encoder evolves latent states continuously between observations, allowing the model to capture irregular temporal dynamics while respecting road-network feasibility. Behavioral analysis of real taxi trajectories in Shenzhen and Wuhan reveals that local route choices are shaped by the coexistence and occasional trade-offs between the two heuristics, which motivates their joint modeling. Experiments on large-scale datasets show that DirTraj consistently outperforms RNN-based, attention-based, and recent network-based baselines in next-edge prediction. Additional probe analysis further shows that the learned representation internalizes both directional semantics. These results indicate that integrating behavior-grounded directional decision cues with continuous-time latent dynamics provides an effective framework for OD-conditioned trajectory forecasting on road networks.



Keywords: trajectory prediction, network-based trajectory modeling, neural ordinary differential equations



Semantic Tags: trajectory prediction; road network; neural ordinary differential equations; origin-destination conditioned; continuous-time modeling; urban mobility; route forecasting


```{admonition} Presentation Information
:class: note

**Submission ID:** S0003  
**Session:** [Student competition - Part 1](./Session_GSC-1/)  
**Theme:** GIScience Theory, Spatial Statistics, and Computational Methods    
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30  
**Venue:** SR-F  
```