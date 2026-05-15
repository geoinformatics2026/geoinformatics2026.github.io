---
title: "Machine Learning Retrieval of Chromophoric Dissolved Organic Matter (CDOM) in Poyang Lake Using Sentinel-2 Reflectance Simulated from In-situ Hyperspectral Measurements"
authors:
- "Jian Xu"
- "Mengting Xu"
- "Dan Gao"
- "Chaoyang Fang"

---

# Machine Learning Retrieval of Chromophoric Dissolved Organic Matter (CDOM) in Poyang Lake Using Sentinel-2 Reflectance Simulated from In-situ Hyperspectral Measurements

**Author Information**  
Jian Xu<sup>1</sup>, Mengting Xu<sup>1</sup>, Dan Gao<sup>2</sup>, Chaoyang Fang<sup>2</sup>


<sup>1</sup> School of Geography and Environment, Jiangxi Normal University  

<sup>2</sup> Key Laboratory of Poyang Lake Wetland and Watershed Research, Ministry of Education, Jiangxi Normal University  



## Abstract

Chromophoric dissolved organic matter (CDOM) is an optically active component of dissolved organic matter that plays an important role in aquatic biogeochemical processes and carbon cycling. Accurate retrieval of CDOM from satellite observations is therefore essential for monitoring water quality in large inland lakes. In this study, a machine learning–based approach was developed to estimate CDOM in Poyang Lake, the largest freshwater lake in China, using simulated Sentinel-2 multispectral data. A total of 114 in-situ measurements of water surface reflectance and CDOM absorption coefficients were collected during field campaigns. The measured hyperspectral reflectance was convolved with the spectral response functions of the Sentinel-2 MultiSpectral Instrument (MSI) to simulate satellite band reflectance. Six machine learning algorithms, including Random Forest (RF), Support Vector Regression (SVR), Multi-Layer Perceptron (MLP), K-Nearest Neighbors (KNN), Gradient Boosting Decision Tree (GBDT), and Extreme Gradient Boosting (XGBoost), were developed and compared for CDOM retrieval. Simulated Sentinel-2 band reflectance and their band ratios were used as input features, while the CDOM absorption coefficient at 355 nm (ag(355)) served as the target variable. Model hyperparameters were optimized using grid search combined with five-fold cross-validation. The results indicate that XGBoost achieved the best accuracy, with an overall R² (coefficient of determination) of 0.942, a root mean square error (RMSE) of 0.091 m⁻¹, and a %RMSE of 4.05%. When applied to actual Sentinel-2 imagery, the model maintained strong predictive capability (R²=0.856, RMSE=0.182 m⁻¹, %RMSE=7.85%), demonstrating good stability and generalization ability. These results highlight the potential of integrating Sentinel-2 remote sensing and advanced machine learning algorithms for reliable mapping of CDOM in large and optically complex inland waters. This study provides a practical framework for satellite-based CDOM monitoring and contributes to improved understanding of carbon dynamics and water quality in Poyang Lake and similar freshwater systems.



Keywords: CDOM,  Sentinel-2 MSI,  Machine learning,  XGBoost,  Inland water remote sensing,  Poyang Lake



Semantic Tags: water quality; CDOM retrieval; Sentinel-2; machine learning; XGBoost; hyperspectral simulation; inland lake; Poyang Lake; China


```{admonition} Presentation Information
:class: note

**Submission ID:** R8356  
**Session:** [Water Quality and Inland Water Monitoring](./Session_REE-4/)  
**Theme:** Remote Sensing, Earth Observation, and Environmental Monitoring    
**Date:** Day 2 — 21 July 2026 (Tuesday)  
**Time:** 13:00 – 14:30  
**Venue:** SR-B  
```