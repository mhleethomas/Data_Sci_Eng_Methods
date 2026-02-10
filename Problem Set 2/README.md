---
# Problem Set 2: Classification, Model Evaluation, and Regularization (Boston, Caravan, Carseats, Default)

This problem set uses the Boston, Caravan, Carseats, and Default datasets to practice classification workflows, model evaluation, and regularization techniques. The tasks focus on preparing data, fitting models, interpreting results, and comparing performance.

## Table of Contents
1. [Overview of Questions](#overview-of-questions)
2. [Data Descriptions](#data-descriptions)
3. [Installation](#installation)
4. [Usage Instructions](#usage-instructions)
5. [Expected Results](#expected-results)
6. [Dependencies](#dependencies)

---

## Overview of Questions
Typical tasks include:
1. **Classification Models**: Fit and interpret logistic regression and other classifiers.
2. **Model Evaluation**: Use confusion matrices, accuracy, sensitivity/specificity, and ROC/AUC.
3. **Feature Engineering**: Handle categorical predictors and scaling where needed.
4. **Regularization**: Apply ridge and lasso to reduce overfitting and compare model performance.
5. **Model Comparison**: Evaluate multiple approaches across datasets.

---

## Data Descriptions
1. **Boston Housing Data**: Suburb characteristics with `crim` and other predictors used for classification or regression tasks.
2. **Caravan Data**: Customer attributes used to predict product purchase behavior.
3. **Carseats Data**: Store-level predictors used for classification or regression targets.
4. **Default Data**: Credit default indicator with financial predictors.

---

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage Instructions
1. Open [problem_set_2.ipynb](problem_set_2.ipynb) in this folder.
2. Execute cells top-to-bottom.
3. Review printed metrics and plots to answer each question.

---

## Expected Results
- **Model outputs**: coefficients, p-values, or feature importances.
- **Evaluation artifacts**: confusion matrices, ROC curves, AUC scores.
- **Comparisons**: performance differences between baseline and regularized models.

---

## Dependencies
This project requires:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `statsmodels`
- `scikit-learn`
