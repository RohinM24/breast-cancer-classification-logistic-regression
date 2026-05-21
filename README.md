# Breast Cancer Classification Using Logistic Regression

## Project Overview

This project focuses on developing a machine learning classification model capable of predicting whether a breast tumour is malignant or benign using the Breast Cancer Wisconsin Diagnostic Dataset.

The project was completed as part of the PDAN8411 Programming for Data Analytics Portfolio of Evidence (POE) and follows a complete end-to-end machine learning workflow including:
- exploratory data analysis (EDA)
- preprocessing
- feature scaling
- multicollinearity assessment
- feature selection
- Logistic Regression modelling
- ROC-AUC evaluation
- hyperparameter tuning
- cross-validation
- model comparison

The goal of the project is to explore how machine learning techniques can support healthcare decision-making and early breast cancer detection.

---

# Dataset

Dataset Used:
- Breast Cancer Wisconsin Diagnostic Dataset

Dataset Sources:
- UCI Machine Learning Repository
- Kaggle

Dataset Characteristics:
- 569 observations
- 30 numerical predictor variables
- Binary classification target:
  - Malignant (1)
  - Benign (0)

The dataset contains tumour measurement features related to:
- radius
- texture
- perimeter
- area
- smoothness
- concavity
- symmetry
- fractal dimensions

---

# Technologies and Libraries Used

## Programming Language
- Python

## Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

# Machine Learning Workflow

## 1. Data Loading and Inspection
- Dataset loading
- Dataset structure inspection
- Summary statistics

## 2. Data Cleaning
- Missing value analysis
- Removal of unnecessary columns
- Target variable encoding

## 3. Exploratory Data Analysis (EDA)
- Diagnosis distribution analysis
- Correlation analysis
- Pairplot analysis
- Correlation heatmap
- Histogram analysis
- Outlier detection using boxplots

## 4. Preprocessing
- Train-test split
- Feature scaling using StandardScaler
- Data leakage prevention
- Multicollinearity assessment

## 5. Baseline Logistic Regression Model
- Model training
- Prediction generation
- Baseline evaluation

## 6. Model Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- ROC-AUC analysis

## 7. Feature Selection
- Recursive Feature Elimination (RFE)
- Selected feature modelling
- Feature importance analysis

## 8. Hyperparameter Tuning
- GridSearchCV
- Cross-validation
- Recall-focused optimisation

## 9. Final Model Comparison
- Baseline model comparison
- Tuned model comparison
- Healthcare-focused evaluation

---

# Key Findings

- The dataset demonstrated strong suitability for binary healthcare classification.
- Tumour size and concavity-related variables were the strongest predictors of malignancy.
- Logistic Regression achieved strong classification performance across multiple evaluation metrics.
- Feature selection improved model interpretability while maintaining predictive capability.
- Hyperparameter tuning and cross-validation improved model robustness and recall performance.
- Recall was prioritised throughout the project due to the healthcare risks associated with false negative predictions.

---

# Healthcare Relevance

This project demonstrates how machine learning classification techniques can assist healthcare professionals by supporting:
- early breast cancer detection
- diagnostic decision-making
- predictive healthcare analytics

Special consideration was given to:
- recall optimisation
- false negative reduction
- model interpretability
- ethical healthcare implications

---

# Repository Structure

```text
├── data/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── Breast Cancer Classification.ipynb
```

---

# Example Visualisations

The project includes:
- Correlation Heatmaps
- Pairplots
- Histograms
- Boxplots
- Confusion Matrices
- ROC Curves
- Model Comparison Graphs

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/breast-cancer-classification-logistic-regression.git
```

Navigate into the project directory:

```bash
cd breast-cancer-classification-logistic-regression
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
Breast Cancer Classification.ipynb
```

---

# Future Improvements

Potential future improvements include:
- testing additional classification algorithms
- advanced feature engineering
- SHAP explainability analysis
- deployment using Streamlit or Flask
- integration with larger healthcare datasets

---

# References

- UCI Machine Learning Repository
- Scikit-learn Documentation
- pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

# Artificial Intelligence Usage Declaration

ChatGPT was used in accordance with IIE and Emeritus guidelines for academic support and responsible AI-assisted learning.

AI assistance was used for:
- conceptual understanding
- workflow planning
- debugging support
- code explanation
- interpretation guidance
- academic structuring

All final coding implementation, analysis, interpretation, evaluation, and submission content were reviewed, understood, and validated by the student.

---

# Author

Rohin Maharaj

Programming for Data Analytics (PDAN8411)

2026
