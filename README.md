# SeaLevelRisePrediction
Using the LIDAR elevation data to develop a short-term Sea Level Rise (SLR) forecast model

## Abstract
Global Warming has been a concerning problem across the globe, rising temperatures are melting the glaciers and causing sea level rise (SLR). This project focuses on the California Coast with a population of 26.3 million (N.O.A.A, 2022). The SLR can cause huge loss to people and assets around the coast. Hence, it is essential to introduce effective community planning and evacuation strategies. Existing climatic models use satellite and weather station data to predict potential SLR. This project uses elevation data from Light Detection and Ranging (LiDAR) to develop a short-term Sea Level Rise (SLR) forecast model and show the effects of it on the population and assets. Various climatic factors that impact sea level like the temperature, precipitation was identified and collected along with LiDAR data making this a multivariate time series forecast machine learning problem. The models proposed are Convolutional Neural Networks (CNN-LSTM), Adaptive Neuro-Fuzzy Inference System (ANFIS), Multi-Layer Perceptron (MLP) to predict SLR and Vector Auto Regression (VAR), Multiple linear regression (MLR) to estimate the corresponding asset loss. The models are evaluated using R2 score, Root Mean Square Error (RMSE), Mean Absolute Percentage Error (MAPE). Based on the comparative analysis, CNN-LSTM with RMSE of 0.133 and R2 of 98%, MLR with RMSE of 0.04 and R2 of 99% were identified as the best models for SLR prediction and Asset loss estimation respectively. A web portal was designed to view the future SLR, Asset and population loss.
Keywords: Sea Level Rise, LiDAR, CNN-LSTM, California Coast, Multivariate Timeseries forecast

## Project Architecture
![image](https://user-images.githubusercontent.com/22653266/211885918-af87cba9-405f-4538-a9ae-27b3d6017b5a.png)

## Data Sources
<img width="1151" alt="Screen Shot 2023-01-11 at 10 17 57 AM" src="https://user-images.githubusercontent.com/22653266/211886200-d59616f6-7cd5-43d9-8648-277d199c5af2.png">
