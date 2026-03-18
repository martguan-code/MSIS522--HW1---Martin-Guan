# MSIS522--HW1---Martin-Guan
# MSIS 522 HW1: COVID-19 Patient Outcomes & Risk Stratification

## Overview
This repository contains the complete end-to-end data science workflow for predicting patient mortality based on the instructor-curated COVID-19 dataset[cite: 10, 197]. [cite_start]The project fulfills the requirements for MSIS 522: Analytics and Machine Learning[cite: 2, 3]. It covers descriptive analytics, predictive modeling comparing multiple algorithms, SHAP-based model explainability, and a fully deployed Streamlit web application
## Repository Contents

| File/Folder | Description |
| :--- | :--- |
| `app.py` | The main Streamlit application code containing all four required tabs
| `covid_data.csv` |The dataset containing anonymized patient records and comorbidities
| `requirements.txt` | The list of Python dependencies required to run the application reproducibly
| `metrics_results.json` | A JSON file storing the evaluation metrics for all trained models. |
| `scaler.joblib` | The saved StandardScaler object used for data normalization
| `*_model.joblib` | Saved machine learning models (Logistic Regression, Decision Tree, Random Forest, XGBoost)
| `mlp_model.keras` |]The saved Keras Multi-Layer Perceptron neural network model

## How to Run Locally
# Clone the repo
git clone https://github.com/martguan-code/MSIS522--HW1---Martin-Guan---updated

# Enter the folder
cd MSIS522--HW1---Martin-Guan---updated

# Install dependencies
pip install -r requirements.txt

# Run the dashboard
python -m streamlit run streamlit_app.py


## Deployed Application
can't DEPLOYED, please refer to the section: Run Locally
