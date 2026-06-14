# House Price Prediction Report

## Problem Statement

The objective of this project was to develop a machine learning model capable of predicting house prices based on housing characteristics and amenities.

## Dataset

Housing Dataset from Kaggle.

## Methodology

### Data Preprocessing

1. Loaded the dataset using Pandas.
2. Checked for missing values.
3. Converted categorical variables into numerical format.
4. Verified data quality before model training.

### Feature Selection

Selected housing attributes such as:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Air Conditioning
* Furnishing Status

The target variable was house price.

### Train-Test Split

Split the dataset into training and testing sets using an 80:20 ratio.

### Model Training

Used Random Forest Regressor from Scikit-Learn to train the prediction model.

### Model Evaluation

Evaluated model performance using:

* Mean Absolute Error (MAE)
* R² Score

## Results

* MAE: 1024081.03
* R² Score: 0.6128

The model successfully learned patterns from the housing data and generated price predictions for unseen properties.

## Sample Prediction

The trained model predicted a house price of approximately ₹47.7 Lakhs for a sample property configuration.

## Conclusion

The project demonstrated the complete machine learning workflow, including preprocessing, feature selection, model training, evaluation, and prediction. Random Forest Regression produced reasonable prediction performance and showed the practical application of machine learning in real estate price estimation.
