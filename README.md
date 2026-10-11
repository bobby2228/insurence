# insurance-ml-project
# Medical Insurance Charges Prediction using Linear Regression

## Project Overview

This project predicts medical insurance charges using Linear Regression. It demonstrates exploratory data analysis, data preprocessing, model training, evaluation, and interpretation.

## Dataset

Source: [Medical Insurance Dataset](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv)

The dataset contains the following columns:

- `age` — Age of the individual
- `sex` — Gender
- `bmi` — Body Mass Index
- `children` — Number of dependents
- `smoker` — Smoking status
- `region` — Residential region
- `charges` — Medical insurance charges (prediction target)

## Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Jupyter Notebook.

## Project Workflow

1. Dataset loading and exploration
2. Missing-value and duplicate analysis
3. Univariate and bivariate visualizations
4. Feature selection and train/test split
5. Categorical encoding and numerical scaling
6. Linear Regression model training
7. Predictions and model evaluation
8. Residual analysis and coefficient interpretation

## Model Performance

| Metric | Value |
|---|---:|
| MAE | 4,177.05 |
| MSE | 35,478,020.68 |
| RMSE | 5,956.34 |
| R² Score | 0.8069 |

The model explains approximately **80.69% of the variation** in medical insurance charges in the test dataset.

## Key Findings

- Smoking status has a strong association with predicted insurance charges.
- Age and BMI show substantial positive associations.
- Sex and region have relatively smaller coefficients in the fitted model.
- The model provides a useful baseline, although prediction errors remain.

## How to Run

1. Clone the repository.
2. Create and activate a Python virtual environment.
3. Install dependencies using `pip install -r requirements.txt`.
4. Open the Jupyter Notebook in VS Code or Jupyter.
5. Run the notebook cells in order.

## Conclusion

This project demonstrates how Linear Regression can be applied to predict medical insurance charges and how evaluation metrics and model coefficients help interpret its performance.
