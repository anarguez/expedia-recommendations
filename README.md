# Expedia Hotel Recommendations

This project is an implementation of Kaggle Expedia Hotel Recommendation [competition](https://www.kaggle.com/c/expedia-hotel-recommendations/overview) based on a multiclass classification approach. The approach develops 4 different models and then combines them through soft voting.

## Jupyter Notebooks

* data_preprocessing.ipynb - Preprocessing of features and imputation of missing values
* feature_selection.ipynb - Compute features importances
* randomForest.ipynb - Using a Random Forest model for predicting class probabilities
* NB.ipynb - Using a Naive Bayes model for predicting class probabilities
* XGB.ipynb - Using a XGBoost model for predicting class probabilities
* MLP.ipynb - Using an MLP model for predicting class probabilities
* combine_models.ipynb - Ensemble models through soft voting
