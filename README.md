# 🧾 Credit Card Default Prediction

This project predicts whether a credit card holder is likely to default in the upcoming month. It was developed as part of the **Finance Club Open Project Summer 2025** by **Meenakshi (22116053)**.

## 🎯 Objective

Develop a robust classification model to assist financial institutions in detecting potential defaulters early using:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Dimensionality Reduction with PCA
- Handling class imbalance using SMOTE
- Evaluation via precision, recall, F1 & F2 scores

## 📊 Dataset

- **Source**: Preprocessed credit card client data
- **Target**: `next_month_default` (binary classification)

## 🔧 Techniques Used

### 📌 Preprocessing
- Null value handling
- Feature scaling using `StandardScaler` and `MinMaxScaler`
- PCA (95% variance retained)
- SMOTE for oversampling defaulter class

### 📈 Models Used
- **Logistic Regression**
- **Decision Tree**
- **Random Forest** ✅ (Best F1-score)
- **K-Nearest Neighbors (KNN)**
- **XGBoost**

### 🏅 Evaluation Metrics
- **Recall**: Prioritized due to high cost of missing a defaulter
- **F1 & F2 Scores**: Used to balance recall and precision
- **Threshold Optimization**: Best at 0.5514 for maximizing F1

## 🏆 Final Model: Random Forest

## 💼 Business Impact
- Enables proactive credit risk intervention
- Identifies key behavioral indicators of default
- Supports data-driven loan approval strategies

## 📁 Files
- `credit_card.ipynb`: Full code and analysis
- `report_open_project_22116053.pdf`: Project report


