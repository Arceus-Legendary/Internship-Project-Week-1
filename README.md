# House Price Prediction

## Internship Project - Week 1

This project was completed as part of my Machine Learning Internship assignment.

The objective of this project is to predict house prices using various house-related features such as area, number of bedrooms, bathrooms, parking availability, and other amenities.

---

## Problem Statement

Real estate buyers and sellers often rely on guesswork when estimating the value of a property. The goal of this project is to build machine learning models that can predict house prices based on available property features and identify which factors influence house prices the most.

---

## Dataset

Dataset Source:

https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

Dataset File:

* Housing.csv

The dataset contains information about:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room
* Basement
* Air Conditioning
* Preferred Area
* Furnishing Status
* House Price (Target Variable)

---

## Project Workflow

### 1. Data Loading and Exploration

* Loaded dataset using Pandas
* Displayed first 10 rows
* Checked dataset dimensions
* Identified target and feature columns
* Checked missing values

### 2. Data Cleaning

* Removed duplicate rows
* Handled missing values
* Converted categorical features using one-hot encoding
* Prepared dataset for machine learning

### 3. Model Building

Two regression models were trained:

#### Linear Regression

Performance:

* MAE: 970043
* RMSE: 1324507
* R² Score: 0.653

#### Random Forest Regressor

Performance:

* MAE: 1013969
* RMSE: 1398116
* R² Score: 0.613

---

## Results

The Linear Regression model performed slightly better than the Random Forest model on this dataset.

Key factors affecting house prices include:

* Area
* Bathrooms
* Air Conditioning
* Stories
* Parking Availability

---

## Visualizations

The project includes:

1. Distribution of House Prices
2. Correlation Heatmap
3. Actual vs Predicted House Prices

All charts are available inside the `charts/` folder.

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Folder Structure

```text
HousePricePrediction_AryanParashar/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    └── actual_vs_predicted.png
```

---

## Author

Aryan Parashar

Machine Learning Internship Project - Week 1
