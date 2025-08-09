# Regression-models-for-predict-house-sale-price-interval
Create a regression model for a house sale price having the narrowest overall prediction intervals.

To determine the house price prediction interval, I conducted several experiments using different regression models, and obtained different results.

I worked on this project by trying several models, namely Ridge Regression Model, LightGBM Regressor, Catboost Regressor, Quantille Catboost, Quantille Multilayer Perceptron (MLP) neural network, and Stacking Quantille with Catboost and LGBM Base models and Ridge as the meta model.
Here are the details of the Kaggle public score results from the regression model I did:
1. Ridge Regressor : 814837.49
2. LightGBM : 727019.68
3. Catboost : 667798.10
4. Quantille Catboost : 457291.92
5. Quantille NN (MLP) : 5433819.18
6. Stacking Quantille : 544888.61

Since the best score is calculated using the smallest score, based on this experiment, the most effective and best model out of all the models I tried is the Quantile Catboost Model with a score of 457291.92


Reference : 
https://www.kaggle.com/competitions/prediction-interval-competition-ii-house-price/submissions#
