

# Titanic Survival Prediction

### Logistic Regression | Machine Learning Project

Predicting passenger survival on the Titanic dataset using **Univariate** and **Multivariate Logistic Regression**.

</div>

---

## 📌 Project Overview

This project explores how Logistic Regression can be used to predict whether a Titanic passenger survived. It includes a simple model using `fare` and a multivariate model using passenger class, age, fare, family size, and encoded sex.

## 🎯 Objectives

- Practice data cleaning and preprocessing.
- Explore a binary classification problem.
- Train and evaluate Logistic Regression models.
- Compare univariate and multivariate model performance.

## 📂 Project Workflow

1. Load the Titanic dataset using Seaborn.
2. Handle missing values.
3. Prepare the target variable, `survived`.
4. Train a **univariate model** using `fare`.
5. Train a **multivariate model** using `pclass`, `age`, `fare`, `sibsp`, and `sex_encoded`.
6. Evaluate the models using accuracy and confusion matrices.

## 🧰 Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Install dependencies

```bash
pip install pandas numpy seaborn matplotlib scikit-learn jupyter
```

### 3. Run the notebook

Open `ML_Practice-2 (Logistic_Regression).ipynb` in Jupyter Notebook or JupyterLab and run the cells.

## 📊 Model Evaluation

The notebook evaluates predictions with:

- Accuracy score
- Confusion matrix
- Logistic Regression coefficients and intercept

Actual results depend on running the notebook in your environment.

## 🗂️ Repository Structure

```text
your-repository/
├── README.md
├── titanic_survival_logo.png
└── ML_Practice-2 (Logistic_Regression).ipynb
```

## 📝 Notes

- The notebook uses Seaborn's built-in Titanic dataset.
- The target column is `survived` (`0` = did not survive, `1` = survived).
- The multivariate model encodes `sex` as a numeric feature.

---

<div align="center">

**Made for learning Machine Learning and Logistic Regression**

</div>
