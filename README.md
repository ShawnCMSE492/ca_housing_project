
# ca housing project

End to End ML Project - Chapter 2 of Hands‑On Machine Learning with Scikit‑Learn, Keras & TensorFlow.  


## Background & Objective

- The goal is a model with the capability to estimate 1990 CA district house prices from publicly available attributes (median income, rooms, latitude/longitude, etc). A well designed ML model helps with quick evaluations, automation, increased accuracy for downstream endeavors. 

- Target: median_house_value

- Evaluation criterion: Minimize RMSE (root mean squared error).

## ML Project workflow:  

- Split data to prevent information leakage.
- Explore/Visualize data to understand distributions, patterns, and data quality.
- Feature Engineering: to scale attributes that represent rates/ratios. OneHotEncode, Imputation, fix skews to gaussian distributions.
- Preprocess: with a scikit‑learn Pipeline so transformations are consistent, automated, and reproducable.
- Model: LinearRegressor, DecisionTree, RandomForest, SVR
- Evaluate: with cross‑validation before touching the test set.
