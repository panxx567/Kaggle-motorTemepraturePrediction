# Kaggle-motorTemepraturePrediction
This is a taks from Kaggle, which requires a prediction for the temperature of some components of a motor. Savgol-filter and linearRegression are used

The dataset is from Kaggle. There are four target features, three components are related to stator temperature and one to rotor temperature. I just predict the temperature of stator (pm)

Savgol-filter is used to reduce the noise of ambient. Profile_id and torque are dropped because of the requirement from kaggle taks.

Only a baseline regression is used.
