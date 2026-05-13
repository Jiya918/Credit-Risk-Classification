# Credit-Risk-Classification
Predicting loan default risk using XGBoost and SMOTE.

📌 Overview

This project predicts whether a loan applicant is likely to default or repay the loan using machine learning techniques.

📊 Dataset
100,000+ loan records
Features include: income, credit score, debt, loan amount, employment history
⚙️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
XGBoost
SMOTE (imbalanced data handling)
Matplotlib, Seaborn
🔄 Workflow
Data cleaning & preprocessing
Handling missing values & outliers
Encoding categorical variables
SMOTE for class imbalance
Model training (Logistic Regression, Random Forest, XGBoost)
Threshold tuning for recall improvement
Evaluation using ROC-AUC
📈 Results
ROC-AUC Score: 0.77
Improved recall for risky loans using threshold tuning
Balanced trade-off between precision and recall
💡 Key Insight

Credit score and income were the most influential factors in predicting loan default risk.

🚀 Outcome

Built a production-style ML pipeline for credit risk analysis suitable for financial institutions.

### Libraries used:
pandas
numpy
scikit-learn
xgboost
imbalanced-learn
matplotlib
seaborn

### Key Skills Used:
- **Data Cleaning:** Handled missing values and outliers.
- **Handling Imbalance:** Used SMOTE to balance the dataset.
- **Algorithms:** Compared Random Forest and XGBoost.
- **Business Focus:** Optimized for Recall to catch high-risk loans.

### How to use:
Open the `notebook.ipynb` file to see the full analysis and visualizations.
