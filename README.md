 Heart Disease Prediction using Machine Learning

 📌 Project Overview

This project aims to predict whether a patient is at risk of heart disease using Machine Learning classification models. Multiple algorithms were trained, evaluated, and compared to identify the most suitable model for medical prediction tasks.

---

 Dataset

- Dataset: Heart Disease Dataset
- Target Variable: HeartDiseaseorAttack
- Problem Type: Binary Classification

---

 Data Preprocessing

The following preprocessing steps were applied before training the models:

- Data Cleaning
- Feature Scaling using StandardScaler
- Train-Test Split
- Handling Class Imbalance using:
  - `class_weight='balanced'`
  - `scale_pos_weight` (for XGBoost)

---

 Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression
- XGBoost
- Decision Tree
- Gradient Boosting
- Soft Voting Ensemble

---

 Hyperparameter Optimization

To improve model performance, hyperparameter tuning was applied using **RandomizedSearchCV** with **5-Fold Cross Validation**.

---

 Evaluation Metrics

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

Since this is a medical prediction task, **Recall** was considered one of the most important evaluation metrics to reduce false negatives and improve disease detection.

---

 Results

The project compared the performance of several machine learning algorithms and implemented a **Soft Voting Ensemble** model to improve overall prediction stability and robustness.

---

 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Google Colab

---

 Author

Rasha Ahmed

Faculty of Computer Science and Artificial Intelligence

Minya University
