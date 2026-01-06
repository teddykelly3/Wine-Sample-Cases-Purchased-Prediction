# Predicting The Number of Sample Wine Cases Purchased by Distribution Companies

## Author
Teddy Kelly

## Overview
This project analyzes data on commercially available wines to predict the number of
sample cases purchased by wine distribution companies after sampling the wine. I use
two types of count regressions (Poisson and negative binomial) and multivariate linear
regressions to predict how many sample cases are purchased for each wine.

## Other Files
Wine_Cases_Purchased_Prediction.qmd
- R quarto file that contains all of the code used for the project.
  
Wine_Cases_Purchased_Prediction.pdf
- Paper containing exploratory data analysis, data visualizations, data cleaning,
methodology, regressions, results, and interpretations.


## Data
- File: wine-data-1-1.csv
- Contains data on about 12,000 commercially available wines that were taste tested by wine
distribution companies. Most of the feature variables used for prediction are related to the chemical
properties of the wine
- The wine rating given by the taste testers and consumers' rating on the label appeal of the wines are
also given.
- **Dependent Variable**: Number of Sample Cases purchased by wine distribution companies
after sampling the wine.

## Methods
- Count Regression (Poisson and negative binomial regression)
- Multivariate linear regression
- Confusion matrices to evaluate model prediction accuracy
- Diagnostic testing to confirm model validity

## Tools
- R Studio(tidyverse, ggplot2, glm, stargazer)

## Results
- The 2nd multivariate regression model has the highest prediction accuracy at about 40.47%, meaning
that it correctly classified the number of sample cases of wine purchased from 40.47% of the wines in the data.
- The independent variables `wine rating` and `label appeal` had the two strongest positive economic magnitudes,
meaning that increases in wine rating or label appeal more significantly affects the number of cases
purchased than is the case for changes in the chemical properties of the wines.



