# DeepCAPE-Convective-Available-Potential-Energy-Prediction-using-Convolutional-Neural-Networks
DeepCAPE applies CNN to predict Convective Available Potential Energy using ERA5 meteorological data over Morocco. Complete pipeline from NetCDF processing to model evaluation with temporal validation strategies.

# Key Features
Data Pipeline: Processes NetCDF meteorological data using Xarray library

CNN Architecture: Implements 1D convolutional neural networks for regression

Temporal Validation: Uses mixed-date splitting strategy to avoid seasonal bias

Comprehensive Evaluation: Includes cross-validation, hyperparameter tuning, and seasonal performance analysis

Operational Focus: Designed with meteorological forecasting applications in mind

# Technical Stack
Data Processing: Xarray, Pandas, NumPy

Machine Learning: TensorFlow/Keras, scikit-learn

Visualization: Matplotlib, Seaborn

Data Format: NetCDF, CSV

# Project Structure
The repository contains implementations of all project phases:

Data preprocessing and conversion from NetCDF to DataFrame

Exploratory data analysis and feature engineering

CNN model development with hyperparameter tuning

Cross-validation and performance evaluation

Seasonal and temporal analysis of predictions

# Results Summary
The model achieved:

R² score of 0.5974 on test data

Mean Absolute Error of 37.27 J/kg

Significant improvement over traditional temporal splitting approaches

Best performance during summer conditions
