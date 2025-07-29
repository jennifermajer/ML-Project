**Predicting Depression Trajectories Following Cognitive Behavioral Therapy Using Machine Learning**

This repository contains code and documentation for a machine learning project aimed at predicting depression trajectories (remission, relapse, and recurrence) following initiation of Cognitive Behavioral Therapy (CBT)-based treatment for perinatal depression, using data derived from a cluster randomized trial (CRT) conducted in Pakistan.

**Background**

Perinatal depression affects approximately 25% of women in low- and middle-income countries and poses significant risks to maternal and child health. CBT has demonstrated short-term efficacy in reducing depressive symptoms; however, there is uncertainty about its long-term effectiveness, particularly regarding relapse and recurrence. The "Thinking Healthy" intervention, a CBT-based program implemented by minimally trained community health workers in Pakistan, significantly reduced depression at 6 months and 1 year postpartum. However, this effect diminished by the 7-year follow-up.

This project applies advanced machine learning techniques to identify predictors of long-term remission, relapse, and recurrence using longitudinal data from the original trial. The ultimate goal is to inform personalized, scalable strategies for maintaining mental health outcomes.

**Project Objectives**

Develop and evaluate predictive models using logistic regression, random forest, XGBoost, and neural networks.

Perform nested cross-validation with cluster stratification to robustly estimate model performance.

Utilize SHAP feature importance analysis to identify influential predictors and enhance interpretability.

Create hypothetical patient "phenotype profiles" to enhance clinical utility. 

**Repository Structure**
data/
- THP_clean.dta (original study data)
- dat_ml_6m_imputed.csv
- dat_ml_1y_imputed.csv
- dat_ml_7y_imputed.csv
scripts/
- data_cleaning.Rmd
- modeling.ipynb
README.md

data/: Contains raw and processed datasets.

scripts/: R Markdown file for cleaning and deriving outcomes using the original study data; Jupyter notebook for preprocessing, imputation, modeling, and evaluation.


**Usage**
TBD

**Key Results**
TBD

**Original Studies**

Baranov V, Bhalotra S, Biroli P, Maselko J. Maternal Depression, Women’s Empowerment, and Parental Investment: Evidence from a Randomized Controlled Trial. American Economic Review. 2020;110(3):824-59.

Rahman A, Malik A, Sikander S, Roberts C, Creed F. Cognitive behaviour therapy-based intervention by community health workers for mothers with depression and their infants in rural Pakistan: a cluster-randomised controlled trial. Lancet. 2008;372(9642):902-9.
