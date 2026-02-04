Models: Logistic Regression, Random Forest, XGBoost, Support Vector Machine

Tools: Python, Scikit-learn, Pandas, Matplotlib, Jupyter Notebook

**Overview**

This project aims to predict the likelihood of a heart attack in individuals using machine learning models trained on medical records. By analyzing patient attributes such as age, cholesterol levels, resting ECG results, and exercise-induced angina, the system empowers early intervention and clinical decision support.

The ML-based approach assists healthcare professionals in identifying high-risk individuals, leading to faster diagnosis, preventive care, and reduced mortality rates.


**Dataset**

Public dataset from the UCI Heart Disease Repository

Features include: Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting Blood Sugar, Max Heart Rate, etc.

Preprocessed with outlier handling, label encoding, and feature scaling

Data split: 70% Train, 15% Validation, 15% Test


**Machine Learning Models**

Four classification algorithms were implemented and compared:

Logistic Regression: A baseline statistical model for binary classification.

Random Forest: An ensemble of decision trees for improved generalization.

XGBoost: Gradient boosting with regularization, robust to imbalance.

Support Vector Machine (SVM): Effective in high-dimensional spaces.

Each model was evaluated on both performance and interpretability.


**Model Training & Optimization**

Data Preprocessing

Imputation of missing values

Feature scaling via StandardScaler

One-hot encoding for categorical variables

Training Parameters

Cross-validation: 5-fold

Hyperparameter tuning with GridSearchCV

Evaluation metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC


**Key Results**

XGBoost achieved the highest AUC-ROC, indicating strong predictive power

Random Forest provided robust performance with feature importance insights

SVM excelled in precision, useful for minimizing false positives


**Impact & Importance**

Early Diagnosis: Predicts potential risk before a heart attack occurs

Clinical Support: Assists doctors with explainable model outputs

Scalability: Can be integrated into EHR (Electronic Health Records) systems

Preventive Healthcare: Encourages routine screening and awareness


**Future Plans:**

Integrate with real-time health monitoring devices

Deploy as a web/mobile tool for clinical use

Expand dataset with region-specific demographics

Apply SHAP/LIME for enhanced model explainability
