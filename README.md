# Heart Disease Classification

End-to-end binary classification project that predicts the presence of heart disease from clinical and physiological patient attributes.

## Project overview

The project uses a 303-patient heart-disease dataset with 13 input features and compares several supervised classification algorithms before tuning and evaluating the strongest model.

## Workflow

- Exploratory data analysis and visualization
- Train/test splitting
- Comparison of:
  - Logistic Regression
  - K-Nearest Neighbors
  - Random Forest
- Hyperparameter tuning with `RandomizedSearchCV` and `GridSearchCV`
- ROC/AUC analysis
- Confusion-matrix analysis
- Precision, recall, F1-score, and accuracy evaluation
- Cross-validation
- Feature-importance / coefficient interpretation

## Selected result

The tuned Logistic Regression model achieved:

- **Test accuracy:** 85.2%
- **5-fold cross-validation accuracy:** 84.5%
- **5-fold cross-validation precision:** 82.1%
- **5-fold cross-validation recall:** 92.1%
- **5-fold cross-validation F1-score:** 86.7%

## Technologies

Python, pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook.

## Data

The project uses the UCI Heart Disease dataset:

https://archive.ics.uci.edu/dataset/45/heart+disease

A copy of the processed dataset is included in the repository.

## Usage

1. Create the environment from `mp_env.yml` if desired.
2. Open `end-to-end-heart-disease-classification.ipynb`.
3. Run the notebook cells in order.
