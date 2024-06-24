# State-of-Health Estimation for Li-ion Batteries using Process Mining

**Participants:** Yunseo Kim, Yeonsu Kim
**Writer:** Yeonsu Kim
**Date:** 2023-12-17

This repository contains the project assignment for the Knowledge Service Engineering course (Prof. Lim Chi-Hyeon) during the Fall 2023 semester. The project uses process mining techniques to estimate the State of Health (SoH) of Li-ion batteries.

## Introduction
Accurately estimating the SoH of Li-ion batteries is crucial for optimizing their performance and reliability. This project applies process mining techniques to select meaningful features from data generated during battery degradation, aiming to enhance the accuracy of SoH predictions.

## Methodology
1. **Feature Engineering**: Identifying and selecting relevant features for analysis.
2. **Process Mining**: Analyzing and visualizing data to uncover patterns and inefficiencies.
3. **Machine Learning**: Utilizing models to predict, classify, and identify anomalies based on extracted patterns.

## Dataset
The dataset from Sandia National Labs (SNL) focuses on commercial 18650 LFP cells cycled to 80% of their maximum capacity. Rigorous testing was conducted to ensure accuracy.

## Results
The study demonstrated that process mining-based feature selection significantly improves the performance of SoH prediction models, including Ridge Regression, Gaussian Process Regression (GPR), and Support Vector Regression (SVR).

## Conclusion
We achieved more accurate and meaningful battery state evaluations by extracting features using process mining. This approach shows potential for broader applications in various fields.

## References
1. Gandoman F. H., et al. (2019). Concept of reliability and safety assessment of lithium-ion batteries in electric vehicles: Basics, progress, and challenges. Applied Energy.
2. Mikolajczak C., et al. (2012). Lithium-ion batteries hazard and use assessment. Springer Science Business Media.
3. Fei, Z., Yang, F., Tsui, K. L., Li, L., Zhang, Z. (2021). Early prediction of battery lifetime via a machine learning-based framework. Energy, 225, 120205.
4. Yang, D., Zhang, X., Pan, R., Wang, Y., Chen, Z. (2018). A novel Gaussian process regression model for state-of-health estimation of lithium-ion battery using charging curve. Journal of Power Sources, 384, 387-395.
5. Ziolkowski, T., Koschmider, A., Schubert, R., Renz, M. (2022). Process Mining for Time Series Data.
6. Koschmider, A., Janssen, D., Mannhardt, F. (2020). Framework for Process Discovery from Sensor Data.
