# Breast Cancer Detection and Survival Analysis
## Overview
This project uses AI to detect breast cancer and predict patient survival outcomes, including survival status (alive or deceased) and estimated survival duration in months to live. It compares three machine learning models Logistic Regression (LR), Gaussian Naive Bayes (GNB), and K-Nearest Neighbors (KNN)—to identify the most efficient model. Logistic Regression (LR) was selected for final predictions due to its superior performance.
## Prerequisites

Python 3.8 or later
Required libraries: scikit-learn, pandas, matplotlib, numpy

## Installation
Install dependencies:pip install -r requirements.txt

## Usage

### Prepare the dataset:
1.Place your dataset (e.g., data.csv) in the project root or update file paths in scripts/main.py.
2.Run the model training and evaluation:python scripts/main.py

### For predictions on new data:
Update scripts/predict.py with new patient data.
Run:python scripts/predict.py

## Model Details

Models Evaluated: Logistic Regression (LR), Gaussian Naive Bayes (GNB), K-Nearest Neighbors (KNN)
Selected Model: Logistic Regression (LR) due to higher accuracy and reliability
Metrics: Accuracy, Precision, Recall

