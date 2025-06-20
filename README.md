#  Maternal Health Risk Predictor

---

##  Author
**Meron Assefa**

---

##  Project Description

This project predicts maternal health risk levels — categorized as **Low**, **Mid**, or **High** — using key physiological data. It applies supervised machine learning techniques to classify the risk level based on six input features:

- Age  
- Systolic Blood Pressure  
- Diastolic Blood Pressure  
- Blood Sugar (BS)  
- Body Temperature  
- Heart Rate  

The main goal is to support **early detection** of potential complications during pregnancy by providing automated predictions using health indicators.

---

##  Dataset Information

- **Dataset Name**: Maternal Health Risk Data Set  
- **Source**: [Kaggle - by andrewmvd](https://www.kaggle.com/datasets/andrewmvd/maternal-health-risk-data)  
- **Target Variable**: `RiskLevel`  
- **Feature Columns**: All others listed above

---

##  Machine Learning Algorithms Used

The following classification algorithms were implemented and compared:

- **Logistic Regression**: A linear classifier using one-vs-rest (OvR) strategy  
- **Naive Bayes (GaussianNB)**: A probabilistic model based on Bayes' Theorem

Both models were evaluated based on accuracy, precision, recall, F1-score, and confusion matrices.

---

##  Machine Learning Libraries Used

- `pandas` – data manipulation  
- `numpy` – numerical operations  
- `seaborn` and `matplotlib` – data visualization  
- `scikit-learn` – model training, preprocessing, evaluation

---

##  How to Use This Project

1. **Download or Clone the Repository**  
   Make sure the dataset CSV is in the same folder as the notebook.

2. **Open the Jupyter Notebook**  
   File: `health_risk_predictor.ipynb`

3. **Run All Cells in Order**  
   The notebook includes:
   - Data cleaning and preprocessing  
   - Feature scaling using `StandardScaler`  
   - Model training and prediction  
   - Evaluation and visual comparison of results

4. **Optional:**  
   You can customize the models or try other algorithms like Decision Trees, KNN, or Random Forest to improve performance.

---

##  Results

Logistic Regression outperformed Naive Bayes, especially in identifying **high-risk cases**, based on macro-averaged precision and recall. Visualizations such as boxplots, heatmaps, and classification bar charts helped interpret the data and results.

---

##  Files Included

- `health_risk_predictor.ipynb` – main notebook  
- `Maternal Health Risk Data Set.csv` – dataset file  
- `.png` files – exported plots (confusion matrix, classification metrics, etc.)
