# Medical Insurance Cost Prediction

This project analyzes the key drivers of medical insurance charges and builds predictive models to estimate individual healthcare costs.

## Project Objective

The goal of this project is to understand how demographic and lifestyle variables such as age, BMI, smoking status, number of children, and region influence medical insurance charges, and to compare regression models for cost prediction.

## Dataset

- Observations: 1,338
- Features: `age`, `sex`, `bmi`, `children`, `smoker`, `region`
- Target: `charges`

## Workflow

1. Data loading and quality checks
2. Exploratory data analysis
3. Feature engineering
4. Model training and comparison
5. Feature importance and interpretation
6. Key insights and business implications

## Models Used

- Linear Regression
- Huber Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

## Key Insights

- Smoking is the strongest driver of medical insurance charges.
- BMI and age have meaningful effects on cost, including nonlinear relationships.
- Tree-based models outperform basic linear approaches on this dataset.

## Project Structure

```text
medical-insurance-cost-prediction/
├── .gitignore
├── README.md
├── requirements.txt
├── data/
│   └── insurance.csv
└── notebooks/
    ├── insurance_cost_prediction_final.ipynb   ← main portfolio notebook
    └── insurance_cost_prediction.ipynb         ← extended exploratory analysis
```

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/pbuix06/medical-insurance-cost-prediction.git
cd medical-insurance-cost-prediction
```

### 2. Create and activate a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Open Jupyter
```bash
jupyter notebook
```

Then open the main portfolio notebook:

```text
notebooks/insurance_cost_prediction_final.ipynb
```

## Resume Summary

Built a machine learning project to analyze medical insurance cost drivers using exploratory data analysis, feature engineering, and regression modeling in Python.

## Notes

This project is intended as a clean, portfolio-ready version of a healthcare cost prediction workflow.
