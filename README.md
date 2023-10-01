# Advanced Analytics
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/laurentpauwels/advancedanalytics.git/HEAD)

Repository for Jupyter Notebook teaching materials. Click the `lauch binder` button above to start `binder`, the interactive computational environments for this GitHub repository. The materials are programmed with the statistical computing language `R`.

## Content

1. `anova.ipynb`: Box Plot, Analysis of the Variance (ANOVA), and Multiple Comparaison appied to a dataset on `./data/diet.csv`.
2. `robustErrors.ipynb`: Covariance Matrix Estimation Under Heteroskedasticity, such as Heteroskedasticity-consistent Covariance matrix estimators HC0, HC1, HC2, HC3, and Clustered Standard Errors. The dataset used is `./data/cps09mar.txt` and `./data/DDK2011.csv`.
3. `instrumentalVariables.ibynb`: Estimation with instrumental variables in `R`, Wu-Hausman tests, Sargan tests, and weak instrument tests.
4. `linearProbabilityModel.ipynb`: Linear probability models and their shortcomings.
5. `maximumLikelihood.ipynb`: A practical revision of Maximum Likelihood principles and programming implementation. 
6. `generalisedLinearModels.ipynb`: Binary choice models, link functions (normal and logistic), regressions, odds ratio, marginal effects, predicted probabilities, goodness-of-fit, and confusion matrix.
7. `multinomialLogit.ipynb`: Multinomial Logit and unordered data, marginal effetcs, conditional logit, odds ratio, and mixed logit. 
8. `tobit.ipynb`: Tobit model, censored data, Heckman 2-steps estimation.
9. `machineLearning.ipynb`: basic intro to ML and classification, training data, CART model, random forest, gradient boosting, ROC curve, and variable importance. The models are applied to `./data/loan_risk.csv` dataset.

- `data` folder contains the relevant data.
- `doc` folder contains documentation for the `cps09mar` and `DDK2011` datasets