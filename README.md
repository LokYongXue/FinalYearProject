# Final Year Project

## Reimplementation of GIWRF Feature Selection and LightGBM Integration on the TON_IoT Network Dataset


This project focuses on the reimplementation of the GIWRF (Gini Impurity-based Weighted Random Forest) feature selection technique based on a published research paper and its application to the TON_IoT Network Dataset. The dataset contains 46 features related to network traffic and IoT environments.

The GIWRF feature selection method was used to identify the most important features, reducing the original 46 features to the top 10 selected features for machine learning model training and evaluation. In addition, LightGBM (LGBM) was incorporated into the study due to its strong performance reported in previous research, allowing for a comprehensive comparison with other machine learning algorithms.

After evaluating the performance of multiple machine learning models, the top three performing models were selected and combined using a stacking ensemble technique. The objective was to investigate whether the ensemble approach could further improve classification performance compared to individual models.

## Project Objectives
1.To replicate the preprocessing and feature scaling pipeline adopted in the reference study to ensure methodological consistency. 

2. To reevaluate the performance of machine learning algorithms, including Decision Tree (DT), Adaptive Boosting (AdaBoost), Gradient Boosting Tree (GBT), Extreme Gradient Boosting (XGB), and Light Gradient Boosting Machine (LGBM). 

3. To implement ensemble learning techniques using a stacking approach with the top three performing algorithms identified from DT, AdaBoost, GBT, XGB, and LGBM after the Phase 1 performance analysis.

The dataset descriptions, labels, and sources are provided in File Description and Dataset Source.pdf.
