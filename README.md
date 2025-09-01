# Vehicle-Quantity-Prediction
This notebook focuses on predicting vehicle quantities using machine learning models. It applies regression, time-series forecasting, and deep learning methods to train and evaluate prediction accuracy.
, numpy, matplotlib, seaborn for data wrangling & visualization.\

Uses ML libraries: sklearn, statsmodels, and tensorflow/keras.

Load Data

Reads vehicle dataset (CSV assumed).

Prepares time-series and numerical features.

Feature Scaling

Applies MinMaxScaler for normalization of features before feeding into models.

Models Applied

Support Vector Regression (SVR)

Random Forest Regressor

Linear Regression

SARIMAX (Seasonal ARIMA for time-series forecasting)

Neural Networks (TensorFlow/Keras)

Model Evaluation

Uses metrics:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

R² Score

Visualization

Plots predictions vs. actual values.

Shows trends in vehicle quantity across time.

Comparison of Models

Compares regression, time-series, and neural network results.

Identifies the best-performing model for predictions.
