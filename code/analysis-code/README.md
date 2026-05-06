# analysis-code
This directory contains the core statistical and machine learning workflows for the project. The scripts here move from initial descriptive statistics into model fitting, with a primary focus on using Random Forest to predict antimicrobial resistance (AMR) genotypes. \

📂 Workflow & File Descriptions \
To maintain the integrity of the data pipeline, scripts should be run in the following order:\
\
- 02_descriptive-analysis.qmd\
Generates summary statistics and contingency tables.\
Focuses on the distribution of resistance phenotypes across different metadata categories.\
\
- 03_model-fitting.qmd\
Initial exploration of various model engines.\
Standardizes the data for training and testing.\
\
- 04_random-forest.qmd\
The primary predictive analysis.\
Includes hyperparameter tuning, feature importance plots, and final model evaluation.\
\
- 05_cross-validation.qmd\
Robustness checks using k-fold cross-validation.\
Ensures the Random Forest model generalizes well across the dataset.\
\
- 06_logistic-regression.qmd\
Model comparison to RF 
