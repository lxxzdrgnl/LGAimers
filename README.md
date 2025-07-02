# Pregnancy Success Prediction Project

This repository has the code and documents for a project made during the LG Aimers Hackathon. The goal of the project was to predict how likely patients with infertility problems are to get pregnant.

## Objective

To develop a reliable predictive model to estimate the likelihood of pregnancy success using clinical, demographic, and lifestyle data from infertile patients.

## Dataset

The dataset used in this project includes anonymized clinical records featuring:

* Demographic information
* Medical history
* Lifestyle and behavioral characteristics

Extensive preprocessing steps were carried out, including missing value imputation, categorical variable encoding, and feature scaling.

## Approach

* **Model Development:** Multiple machine learning algorithms were evaluated, including RandomForest and Linear Discriminant Analysis (LDA).
* **Ensemble Learning:** Implemented ensemble methods to combine predictions from multiple models.
* **Hyperparameter Tuning:** Optimized model parameters using Optuna to enhance predictive accuracy.
* **Final Model:** Constructed a robust final prediction model using a VotingClassifier, leveraging the strengths of the best-performing algorithms.
