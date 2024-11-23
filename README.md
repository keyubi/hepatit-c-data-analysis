# Hepatitis C Prediction

## Introduction

Hepatitis C is a serious liver disease caused by the Hepatitis C virus (HCV), which can lead to chronic liver conditions like fibrosis, cirrhosis, and liver cancer. In this project, we analyze clinical data from Hepatitis C patients and healthy blood donors, focusing on various biochemical and body measurements, including:

- Albumin (ALB)
- Alkaline Phosphatase (ALP)
- Alanine Transaminase (ALT)
- Aspartate Transaminase (AST)
- Bilirubin (BIL)
- Cholinesterase (CHE)
- Cholesterol (CHOL)
- Creatinine (CREA)
- Gamma-Glutamyl Transferase (GGT)
- Protein (PROT)

The goal of this analysis is to explore the distribution of these clinical measures, examine their relationships with different health conditions, and use statistical tests and machine learning models to predict liver health conditions.

## Dataset

The dataset used in this analysis contains both clinical data of Hepatitis C patients and healthy blood donors. It includes various biochemical markers related to liver function and overall health.

## Objectives

- **Exploratory Data Analysis (EDA)**: Understand the distribution of clinical biomarkers and explore relationships between these biomarkers and different health conditions.
- **Statistical Analysis**: Conduct statistical tests (e.g., correlation analysis, ANOVA) to examine relationships between biomarkers and disease states.
- **Machine Learning**: Build predictive models to classify individuals based on their clinical biomarkers. We use Logistic Regression and Linear Regression models for prediction.

## Key Findings

1. **Biomarker Variability**: 
   - Key biomarkers such as ALB, ALP, ALT, and GGT exhibit significant differences across health categories, emphasizing their role in reflecting liver function and disease severity.
   
2. **Statistical Relationships**: 
   - Correlation analyses show moderate positive relationships, such as between ALB and PROT, indicating their shared reliance on liver functionality.
   - ANOVA tests reveal significant variations in markers like ALP and Bilirubin (BIL) across different health conditions.

3. **Machine Learning Outcomes**: 
   - The Logistic Regression model showed promising results in predicting healthy individuals (Blood Donors) but faced challenges in accurately classifying Hepatitis and Fibrosis categories, largely due to dataset imbalance.
   - Linear Regression was moderately effective in predicting ALB levels, although there is potential for improvement.

4. **Gender-Based Differences**: 
   - T-tests revealed significant differences in ALB levels between males and females, while PROT levels showed no significant gender-related variation.

## Installation

To run this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   https://github.com/keyubi/hepatitis-c-prediction.git

## Link for the Kaggle
   ```bash
https://www.kaggle.com/code/kubtem/hepatitis-c-prediction-by-kubtem

