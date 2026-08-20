# Software Defect Prediction Using Machine Learning

## 📌 Project Overview

Software defects can increase maintenance costs and affect software quality. This project uses machine learning to predict whether a software module is likely to contain defects based on software metrics such as lines of code, code complexity, branching, development effort, operators, operands, and other characteristics.

The project uses the **JM1 Software Defect Dataset** and implements a **Decision Tree Classifier** for binary classification.

---

## 🎯 Objective

The main objectives of this project are:

- Clean and preprocess software-metric data.
- Perform Exploratory Data Analysis (EDA).
- Identify software characteristics associated with defects.
- Build a Decision Tree classification model.
- Evaluate the model using classification metrics.
- Identify important features influencing defect prediction.
- Demonstrate how predictive analytics can help prioritize software testing.

---

## 📊 Dataset

The project uses the **JM1 software defect dataset**.

The dataset contains software metrics describing individual software modules, including:

- Lines of Code
- Cyclomatic Complexity
- Branch Count
- Development Effort
- Operators and Operands
- Code-related metrics
- Defect Status

### Dataset Distribution

| Class | Description | Count |
|------|-------------|------:|
| 0 | Non-Defective | 6,905 |
| 1 | Defective | 2,007 |

The dataset is therefore imbalanced, with more non-defective modules than defective modules.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Preparation
   ↓
Train-Test Split
   ↓
Decision Tree Classifier
   ↓
Hyperparameter Tuning using GridSearchCV
   ↓
Model Evaluation
   ↓
Feature Importance Analysis
   ↓
Final Defect Prediction
