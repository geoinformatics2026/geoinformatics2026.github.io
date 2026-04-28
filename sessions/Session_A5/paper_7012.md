---
title: "Decoupling Traffic-Induced and Geometry-Induced Collision Risks in Maritime Chokepoints: A Joint Spatial Point Process Approach"
authors:
- "Jiaxiang Cai"

---

# Decoupling Traffic-Induced and Geometry-Induced Collision Risks in Maritime Chokepoints: A Joint Spatial Point Process Approach

**Author Information**  
Jiaxiang Cai<sup>1</sup>


<sup>1</sup> Institute of High Performance Computing, A*STAR  



## Abstract

The rapid growth in global maritime traffic places extraordinary pressure on critical chokepoints such as the Singapore Strait, where over 1\,000 vessel transits occur daily. Maintaining a safe Distance to Closest Point of Approach (DCPA) between vessels is paramount, yet conventional grid-based risk heatmaps suffer from preferential sampling bias. More critically, existing models cannot mathematically distinguish whether an area is dangerous due to high traffic volume or due to inherent geographic hazards such as narrow channels and shoals. In this paper, we propose a Joint Spatial Log-Gaussian Cox Process (LGCP) framework that simultaneously models ship traffic intensity and collision risk marks over a continuous spatial domain. A shared latent Gaussian field links traffic volume directly to the observed DCPA, while an independent residual field captures purely geographic risk. Applying Integrated Nested Laplace Approximations (INLA) with the Stochastic Partial Differential Equation (SPDE) approach to one month of high-fidelity Automatic Identification System (AIS) data from the Singapore Strait, we estimate a statistically significant negative linkage parameter ($\beta = -0.031$, 95\% CI: $[-0.034, -0.028]$), quantifying exactly how crowding compresses safety margins. Furthermore, we reveal a stark spatial-scale decoupling: traffic-induced risk operates at a macro-scale ($\sim$\SI{12.4}{\kilo\metre} range), whereas geographic risk is highly localized ($\sim$\SI{2.6}{\kilo\metre} range). The resulting decoupled risk maps provide dynamic cost-layers for Marine Autonomous Surface Ship (MASS) path-planning and enable Vessel Traffic Services (VTS) to deploy targeted, cause-specific interventions.



Keywords: Maritime Traffic,  Log-Gaussian Cox Process,  Spatial Statistics,  Collision Risk,  Autonomous Surface Ships,  INLA-SPDE



```{admonition} Presentation Information
:class: note

**Submission ID:** 7012  
**Session:** [Traffic Facade Voxel Crowd](./Session_A5/) 
**Date:** Day 1 — 20 July 2026 (Monday)  
**Time:** 13:00 – 14:30
**Venue:** room 5
```