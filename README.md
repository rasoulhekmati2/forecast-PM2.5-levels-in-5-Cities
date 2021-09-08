# forecast-PM2.5-levels-in-5-Cities
forecast the number of days that are high for PM2.5 levels 

The goal is to create a model to forecast PM2.5 levels in China. We ultimately would forecast the number of days that are high for PM2.5.

Methods: 1) Linear Regression, 2)Decision Tree, 3)Random Forest, 4)MLP NN, 5)XGBoost, 6)Keras MLP,7)RNN-LSTM 

Note: No fine tuning has been conducted and so the performances are not comparable

Summary: Removing/interpolating the nans and ouliers, Encoding the categorical features, Mutual Information to study the feature importance, 
Train and test the 7 models, Benchmark the methods, define "high" using elbow method, reporting the percent of days with high PM2.5 
