# Deep-learning-projects

#Weather feature prediction using LSTM

This is a real-life weather dataset. The data is hourly measurements
of weather features in 4 different locations. The five measured variables are: Wind speed in 0.1m/s, Wind
direction in degrees (360 North, 90 East, 0 No wind), Temperature in 0.1C, Dew Point in 0.1C, Air Pressure
in 0.1hpa. The dataset has the shape (Time steps x Cities x Features).The last 168 samples (one week
recording) for test case and the remaining ones have been used for training the model.The data is scaled your before training and
scale  back to be able to compare  predictions with real measurements.

Implemented a (deep) neural networks model for “Temperature” prediction of the last city. 

