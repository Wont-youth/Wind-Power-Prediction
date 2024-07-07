# Wind-Power-Prediction

This repository is used for predicting the wind power energy. We are doing the task for a summer project right now.

The dataset is from https://github.com/Bob05757/Renewable-energy-generation-input-feature-variables-analysis. The paper title is Solar and wind power data from the Chinese State Grid Renewable Energy Generation Forecasting Competition.

We utilize the dataset of first wind power plant (Wind farm site 1 (Nominal capacity-99MW).xlsx).

We mainly use DNN, CNN and LSTM network. However, we are having the problem of overfitting and still seeking some helpful suggestions. If we don't consider the time trend of wind power (like code_DNN_Simple.ipynb), the effect is alright. When we add the past wind power into the prediction features, the result is not quite good. 


