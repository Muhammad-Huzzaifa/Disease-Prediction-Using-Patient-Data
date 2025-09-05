# Disease Prediction Using Patient Data

This project predicts the presence of heart disease using patient data and machine learning models. It demonstrates data preprocessing, model training, evaluation, and model saving for future use.

## Dataset
- `heart_disease.csv`: Contains patient data for heart disease prediction.

## Features
- Data preprocessing and normalization
- Binary classification of heart disease
- Model training using Logistic Regression and Random Forest
- Hyperparameter tuning for Random Forest
- Model evaluation and accuracy reporting
- Model persistence using joblib

## Usage

1. Install dependencies:
	```bash
	pip install -r requirements.txt
	```

2. Run the Jupyter notebook:
	```bash
	jupyter notebook disease_prediction.ipynb
	```

3. The notebook will:
	- Load and preprocess the dataset
	- Train and evaluate models
	- Save trained models as `log_reg.pkl` and `rand_forst.pkl`

## Files
- `disease_prediction.ipynb`: Main notebook with code and explanations
- `heart_disease.csv`: Dataset file
- `log_reg.pkl`: Saved Logistic Regression model
- `rand_forst.pkl`: Saved Random Forest model

## Requirements
See `requirements.txt` for Python package dependencies.

## Author
Muhammad Huzaifa
