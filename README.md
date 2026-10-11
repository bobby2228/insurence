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




## Machine Learning Model Results

This project implements two machine learning algorithms on the Medical Insurance dataset.

### 1. Linear Regression — Insurance Charges Prediction

**Objective:** Predict medical insurance charges using age, sex, BMI, children, smoking status, and region.

| Evaluation Metric | Result |
|---|---:|
| MAE | 4,177.05 |
| MSE | 35,478,020.68 |
| RMSE | 5,956.34 |
| R² Score | 0.8069 |

**Conclusion:** The Linear Regression model explains approximately 80.69% of the variation in insurance charges on the test dataset.

### 2. Logistic Regression — Smoking Status Classification

**Objective:** Predict whether an individual is a smoker or non-smoker using age, sex, BMI, children, region, and insurance charges.

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 96.27% |
| Precision (Smoker) | 92.45% |
| Recall (Smoker) | 89.09% |
| F1 Score (Smoker) | 90.74% |

**Confusion Matrix Results:**
- True Negatives: 209
- False Positives: 4
- False Negatives: 6
- True Positives: 49

**Conclusion:** The Logistic Regression model achieved 96.27% accuracy on the test dataset, correctly classifying 258 out of 268 records. Insurance charges were included as an input feature, so the results should be interpreted in that context.

## Final Project Status

- Data Cleaning and Exploratory Data Analysis — Completed
- Feature Preprocessing — Completed
- Linear Regression — Completed
- Logistic Regression — Completed
- Model Evaluation and Visualization — Completed
