# Understanding Food Insecurity in the United States Through Predictive Modeling
This project uses 2023 Current Population Survey Food Security Supplement (CPS-FSS) data from the U.S. Census Bureau to predict household food insecurity from demographic, socioeconomic, and household-level characteristics.

Three regularized logistic regression models (Lasso, Ridge, and Elastic Net) were trained using 10-fold cross-validation. Models performed well at identifying food-secure households but struggled to identify food-insecure households, likely due to class imbalance and heterogeneity among food-insecure populations.

## Methods

- 2023 CPS-FSS data
- Feature engineering and preprocessing
- Lasso, Ridge, and Elastic Net logistic regression
- 10-fold cross-validation
- Model evaluation using ROC AUC, sensitivity, and specificity
- R

## Paper
View my full paper and results [here.](https://docs.google.com/document/d/1nmlDaW9mVtaT7uLOvGSU3iUc9F4RGmgzTFoNUvwscwU/edit?usp=sharing)
