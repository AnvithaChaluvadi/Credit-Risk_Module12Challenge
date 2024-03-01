# Module 12 Report

## Overview of the Analysis

Classifying credit risk proves challenging given its imbalanced nature, primarily due to the prevalence of healthy loans compared to risky ones. To tackle this issue, I will be training and evaluating models for imbalanced classes, employing various techniques. A dataset with historical lending data has been generously provided by an online peer-to-peer lending company. My goal is to create a model proficient in distinguishing the creditworthiness of borrowers, utilizing machine learning in this analysis.

The Logistic Regression Algorithm is the optimal tool for our machine learning model, given its wide application in predicting the probability of a target variable in classification problems. Its popularity and success in various domains underscore its reliability. This algorithm is particularly well-suited for our task, ensuring a robust and accurate model as we navigate the intricacies of forecasting and classifying relevant variables in our dataset.

Checking the balance of the labels variable using the value_counts function is also a crucial step in a machine learning project. Moreover, value_counts helps detect such imbalances, highlighting potential challenges that need to be addressed.

## Results

* Machine Learning Model 1:
  * Model 1 Balance Accuracy: 96.8%
  * Precision
    * Healthy Loans: 100%
    * High-Risk Loans: 84%
  * Recall scores: 
    * Healthy Loans: 99%
    * High-Risk Loans: 94%

<p align="center">
<img src = Images/classification1.png width =40% height 30%=/>
</p>



* Machine Learning Model 2:
  * Model 1 Balance Accuracy: 99.4%
  * Precision
    * Healthy Loans: 100%
    * High-Risk Loans: 84%
  * Recall scores: 
    * Healthy Loans: 99%
    * High-Risk Loans: 99%

<p align="center">
<img src = Images/classification2.png width =40% height 30%=/>
</p>

## Summary

Both Model 1 and Model 2 exhibit high balanced accuracy. However, Model 2 outperforms Model 1 (99.4% vs. 96.8%). Precision for healthy and high-risk loans is the same for both models. Model 2 demonstrates higher recall for high-risk loans, indicating better performance in identifying high-risk instances.

Based on the information found, I recommend Model 2. It performs better overall, boasting higher balanced accuracy and improved recall for high-risk loans. If the goal is to correctly identify high-risk loans, Model 2 is the preferred choice. Nevertheless, if maintaining high precision for high-risk loans is more crucial, Model 1 is recommended.

