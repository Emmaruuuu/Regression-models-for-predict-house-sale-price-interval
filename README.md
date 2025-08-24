# Regression-models-for-predict-house-sale-price-interval
**Description**
As mentioned, in regression it is not unusual to focus on what are called point predictions (representing central tendency). However, in this competition we are interested in producing a prediction interval (an indication of dispersion).

This task is to create a regression model having the narrowest (most "efficient") overall prediction intervals

**Evaluation**
Performance of model using the mean of the Winkler Interval score (https://otexts.com/fpp3/distaccuracy.html#winkler-score). 

**Modelling**
To determine the house price prediction interval, I conducted several experiments using different regression models, and obtained different results.

I worked on this project by trying several models, namely Ridge Regression Model, LightGBM Regressor, Catboost Regressor, Quantille Catboost, Quantille Multilayer Perceptron (MLP) neural network, and Stacking Quantille with Catboost and LGBM Base models and Ridge as the meta model.
Here are the details of the Kaggle public score results from the regression model I did:
1. Ridge Regressor : 814837.49
2. LightGBM : 727019.68
3. Catboost : 667798.10
4. Quantille Catboost : 457291.92
5. Quantille NN (MLP) : 5433819.18
6. Stacking Quantille : 544888.61

Since the best score is calculated using the smallest score, based on this experiment, the most effective and best model out of all the models I tried is the Quantile Catboost Model with the results of RMSE: 113859.8960, R2: 0.9258, Coverage: 93.21% and WIS: 1922371.4223 and a kaggle score of 457291.92

Reference : 
https://www.kaggle.com/competitions/prediction-interval-competition-ii-house-price/submissions#
