# Customer Service Satisfaction (CSAT) Analysis and Prediction

This project analyzes customer service satisfaction (CSAT) data for Flipkart, with the goal of understanding key drivers of customer satisfaction and building predictive machine learning models to improve service quality.

---

## Project Overview

- **Objective:** Analyze Flipkart customer service interactions, identify key factors affecting satisfaction, and build predictive models to classify customer satisfaction levels.
- **Dataset:** Flipkart customer service feedback and interaction data.
- **Techniques Used:** Data cleaning, exploratory data analysis (EDA), univariate/bivariate/multivariate visualizations, feature engineering, multiple ML algorithms, hyperparameter tuning (GridSearchCV, RandomSearchCV), and model evaluation.
- **Outcome:** A comprehensive analysis report with detailed insights and production-grade ML models ready for deployment.

---

## Features

- Detailed data cleaning and preprocessing
- Extensive exploratory data analysis with 15+ insightful visualizations
- Multiple machine learning models implemented and compared
- Model performance visualization and evaluation metrics
- Hyperparameter tuning and cross-validation for improved accuracy
- Well-commented, production-ready Jupyter notebook code

---

## Pre-trained Model

A pre-trained model is saved as `xgboost_csat_model.joblib`.  
You can load it with:

```python
import joblib
model = joblib.load("xgboost_csat_model.joblib")
```

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/amarssingh/CSAT-Prediction-Model.git
cd flipkart-csat-analysis
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

---

## Usage

 - Open the Jupyter notebook Flipkart_CSAT_Analysis.ipynb

 - Follow the step-by-step analysis and model implementation

 - Visualizations and model results are presented inline

 - Modify the notebook to test with different parameters or datasets

---

## Acknowledgments

 - Flipkart Dataset 

 - Thanks to the open-source data science community for libraries and tools used.
