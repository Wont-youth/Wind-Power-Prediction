# Wind-Power-Prediction

This repository is used for predicting the wind power energy. We are studying this task for a summer project.

The dataset is from https://github.com/Bob05757/Renewable-energy-generation-input-feature-variables-analysis. The paper is Solar and wind power data from the Chinese State Grid Renewable Energy Generation Forecasting Competition.

We utilize the dataset of first wind power plant (Wind farm site 1 (Nominal capacity-99MW).xlsx).

We mainly consider simple DNN, DNN, CNN and LSTM network to capture the time trend of wind power. The range of wind power is from 0 to 99 MW which is quite wide. Besides, we choose records of each hour adn make one-day head predition. 

However, we are having the problem of overfitting and still seeking some helpful suggestions. If we don't consider the time trend of wind power (like DNN_Simple.ipynb), the performance is pretty good. When we add the past wind power into the prediction features, the result is quite disappointing. 


