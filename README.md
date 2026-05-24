# 🏦Loan Default Prediction

Machine Learning project for predicting loan default risk using multiple classification models including Logistic Regression, Random Forest, LightGBM, and XGBoost .

## 🎯Project Goal

The goal of this project is to predict whether a customer will default on a loan based on financial and demographic information.

This project includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Model training
- Hyperparameter tuning
- Model evaluation
- Explainability using SHAP

## 📊Dataset

Dataset: Loan Default Dataset

Source: "https://www.kaggle.com/datasets/yasserh/loan-default-dataset?utm_source=chatgpt.com"

Target variable:
- `Status`
    - 0 → Non-default
    - 1 → Default

## 🗂️Project Structure

```text
loan-default/
│
├── data/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_explainability.ipynb
├── main.py
├── pyproject.toml
└── README.md
```

## ⚙️Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- Plotly
- Matplotlib

## 🔄Workflow

1. Data Cleaning
2. Missing Value Handling
3. Exploratory Data Analysis
4. Feature Encoding
5. Model Training
6. Hyperparameter Tuning
7. Evaluation
8. Explainability with SHAP

## 🤖Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest
- LightGBM
- XGBoost

## 🏆Model Performance

| Model | Recall | Precision | F1-Score |
|---|---|---|---|
| Logistic Regression | 0.68 | 0.43 | 0.53 |
| Random Forest | 0.67 | 0.79 | 0.73 |
| LightGBM | 0.73 | 0.77 | 0.75 |
| XGBoost | 0.77 | 0.68 | 0.72 |

## 🧠Model Explainability

SHAP was used to interpret model predictions and identify the most important features affecting loan default risk.

## 🛠️Installation

Clone the repository:

```bash
git clone "git@github.com:HosseinMohebbi/loan-default-prediction.git"
cd loan-default
uv sync
```

## 👨‍💻Author

Hossein Mohebbi
