---
title: "A Generative AI Framework for MRT Station Crowd Dynamics and Retail Inventory Management"
authors:
- "Wei-Zhi Wang"
- "Yi-Chung Chen"
- "Yi-Wun Lin"

exports:
  - format: pdf
    template: arxiv_nips
    output: 
---

# A Generative AI Framework for MRT Station Crowd Dynamics and Retail Inventory Management

**Author Information**  
Wei-Zhi Wang<sup>1</sup>, Yi-Chung Chen<sup>1</sup>, Yi-Wun Lin<sup>2</sup>


<sup>1</sup> National Chung Hsing University  

<sup>2</sup> Newscan Co., Ltd.  



## Abstract

As data-driven decision-making becomes central to urban transit and commerce, pedestrian flow forecasting and retail replenishment planning at MRT stations have emerged as critical research topics. Traditional supervised models often struggle with accuracy and flexibility when facing dynamic conditions or sparse data. To address these limitations, this study proposes a two-stage generative forecasting framework integrating Conditional GAN (CGAN) and Diffusion Models. Using data from nine major Taipei Metro stations, the research first designs a condition vector—incorporating weather, holidays, and time periods—as input for the CGAN to generate scene-consistent pedestrian flow data. Subsequently, a Diffusion model is employed to estimate dynamic demand and provide optimized procurement recommendations for retail outlets. Experimental results demonstrate that the proposed CGAN × Diffusion architecture significantly outperforms baseline models (including GAN, CTGAN, and LSTM+XGBoost) across key metrics such as MAE and MAPE. Finally, the framework is integrated into an interactive Streamlit platform, enabling users to perform custom simulations and visualize procurement strategies. This system demonstrates the feasibility and scalability of generative AI in converging transportation and retail sectors, offering a robust technical direction for future smart operations and strategic planning.



Keywords: Spatio-Temporal Passenger Flow Prediction, Smart Retail, Product Demand Modeling, Generative Adversarial Networks (GANs), Conditional Diffusion Models (CDM)




```{admonition} Presentation Information
:class: note

**Submission ID:** P0856  
**Session:** [Urban Mobility, Travel Demand, and Spatiotemporal Transit Analytics](./Session_TMU-3/)  
**Theme:** Transportation, Mobility \& Urban Infrastructure    
**Date:** Day 1, 20 July (Monday)  
**Time:** 16:30 – 18:00  
**Venue:** Town Plaza-02-Seminar Room 5 & 6 (SR-F)  
```