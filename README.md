# 🧬 Hepatitis C Prediction Using Machine Learning

This repository contains a machine learning project focused on predicting Hepatitis C infection based on medical diagnostic data. It applies data preprocessing, exploratory analysis, and classification models to build a robust predictive pipeline for early detection of Hepatitis C.

## 📌 Objectives

- Analyze medical test results and demographic data to predict Hepatitis C status.
- Apply classification algorithms and evaluate their performance.
- Identify key biomarkers contributing to Hepatitis C prediction.

## 🧪 Methodology

The workflow includes:

1. **Data Loading & Cleaning**
   - Handle missing values and rename ambiguous column names.
2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions and correlations among medical variables.
3. **Data Preprocessing**
   - Encode categorical variables and scale numeric features.
4. **Model Building**
   - Train multiple classification models (e.g., Logistic Regression, KNN, SVM).
5. **Evaluation**
   - Assess performance using accuracy, precision, recall, F1-score, and confusion matrix.

## 📊 Dataset Features

The dataset includes the following types of features:
- **Demographic:** Age, Sex
- **Biomarkers:** ALT, AST, ALP, BIL, CHE, CHOL, PROT, etc.
- **Target:** Category of Hepatitis C condition (Blood Donor, Suspect Blood Donor, Hepatitis, etc.)

> ℹ️ *Note: The dataset is derived from a publicly available medical dataset often used in bioinformatics and disease diagnosis research.*

## ✅ Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Naive Bayes  
- Decision Tree  
- Random Forest

## 🧠 Key Insights

- Certain liver function biomarkers such as **AST**, **ALT**, and **BIL** play significant roles in predicting Hepatitis C.
- Random Forest and SVM yielded the best performance on the test set.
- Feature scaling and proper encoding significantly improved model accuracy.

## 🛠️ Tools & Libraries

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Data visualization
- `scikit-learn` – Model training & evaluation
- `warnings`, `LabelEncoder`, `StandardScaler` – Preprocessing tools

## 📁 Repository Structure

```
📦hepatitis-c-prediction
 ┣ 📄Hepatitis C Prediction.ipynb   # Main Jupyter Notebook
 ┣ 📄README.md                      # Project documentation
 ┗ 📄requirements.txt               # Python dependencies (optional)
```

## 📬 Contact

For feedback, suggestions, or collaborations, feel free to reach out via mariamfalabi409@gmail.com or open an issue in the repo.
