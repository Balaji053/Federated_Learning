# Federated_Learning

*Prediction of Solar Radiation on given weather data
These datasets are meteorological data from the HI-SEAS weather station from four months (September through December 2016)
•	Dataset consists different features like
•	Solar radiation [W/m^2]
•	Temperature [F]
•	Atmospheric pressure [Hg]
•	Humidity [%]
•	Wind speed [miles/h]
•	Wind direction [degrees]
Our objective is to derive an ML model to forecast the solar radiation as a function of available features.
Dataset: 
https://www.kaggle.com/code/enricobaldasso/prediction-of-solar-radiation-data/input

Results:
Model Performances on Solar Radiation Prediction:
Type of Model	    With Federated Learning	      Without Federated Learning
Linear Regression	RMSE: 193.74                    RMSE: 193.44
                  R2: 0.62                        R2: 0.62
                  MAE: 146.50                     MAE: 146.72	
                  

Multi-Layer Perceptron	Mean Absolute Error (MAE):        Mean Absolute Error (MAE):
                        65.75033116335385	                     58.33900969015126

Ridge Regression	RMSE: 193.45                    RMSE: 193.44
                  R2: 0.62                        R2: 0.62
                  MAE: 146.50                     MAE: 146.50
                  

Recurrent Neural Network	Mean Absolute Error (MAE):           Mean Absolute Error (MAE):
                          165.62572284290644	                   110.38326333556199



