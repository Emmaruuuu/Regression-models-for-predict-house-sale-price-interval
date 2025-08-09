# Regression-models-for-predict-house-sale-price-interval
Create a regression model for a house sale price having the narrowest overall prediction intervals.

Untuk menentukan prediksi interval harga rumah, saya melakukan beberapa kali percobaan menggunakan model regressi yang berbeda, dan mendapatkan hasil yang berbeda-beda pula.

Saya mengerjakan projek ini dengan mencoba beberapa model yaitu Ridge Regression Model, LightGBM Regressor, Catboost Regressor, Quantille Catboost, Quantille Multilayer Perceptron (MLP) neural network, dan Stacking Quantille dengan Base model Catboost dan LGBM serta Ridge sebagai meta modelnya. 
Berikut adalah rincian hasil public score Kaggle dari model regressi yang saya lakukan :
1. Ridge Regressor : 814837.49
2. LightGBM : 727019.68
3. Catboost : 667798.10
4. Quantille Catboost : 457291.92
5. Quantille NN (MLP) : 5433819.18
6. Stacking Quantille : 544888.61

Karena score yang terbaik adalah terhitung dengan score yang terkecil, maka dengan percobaan ini, model yang paling efektif dan terbaik dari semua model yang saya coba adalah Quantille Catboost Model dengan besar score yaitu 457291.92.


Reference : 
https://www.kaggle.com/competitions/prediction-interval-competition-ii-house-price/submissions#
