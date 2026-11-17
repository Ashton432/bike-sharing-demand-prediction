# Bike Sharing Demand Prediction

This project uses the Bike Sharing `day.csv` dataset to predict daily bike rental demand using linear regression.

The notebook cleans and explores the data, implements linear regression from scratch, and evaluates the model using mean squared error (MSE).

## Technologies Used
- Python
- NumPy
- pandas
- Matplotlib
- Google Colab

## Files
- `bike_sharing_regression.ipynb` - Main notebook containing the code
- `day.csv` - Dataset required to run the notebook

## How to Run
1. Open `bike_sharing_regression.ipynb` in Google Colab.
2. Upload `day.csv` into the Colab working directory.
3. Run all notebook cells from top to bottom.

## Results
The model achieved a training MSE of approximately 564,552 and a test MSE of approximately 620,125.

A fixed random seed is used for the train/test split to make the results reproducible.
