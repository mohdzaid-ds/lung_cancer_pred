# lung_cancer_pred
Lung cancer survival prediction model using Random Forest and XGBoost to analyze patient features and predict survival outcomes for better clinical insights.”

# Lung Cancer Survival Prediction

## Description
This project predicts whether a lung cancer patient will survive or not based on clinical and demographic features such as age, treatment type, smoking history, family history, and cancer stage. The project uses machine learning models like Random Forest and XGBoost to provide insights that can help in early decision-making.

---

## Features
- Age, Gender, Smoking Status, Family History  
- Treatment Type and Stage of Cancer  
- Other clinical and demographic data  

---

## Dataset
- The dataset contains patient records with features and survival status (Survived column).  
- Class imbalance is handled using techniques like SMOTE.  

---

## Project Steps
1. *Data Preprocessing*
   - Handling missing values  
   - Encoding categorical features  
   - Scaling numerical features  
   - Removing unnecessary columns  

2. *Exploratory Data Analysis (EDA)*
   - Distribution plots and heatmaps  
   - Correlation analysis with target variable  

3. *Model Training*
   - Random Forest and XGBoost classifiers  
   - Hyperparameter tuning using GridSearchCV / RandomizedSearchCV  

4. *Evaluation*
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
   - Feature importance analysis  

5. *Deployment*
   - Save trained model using joblib or pickle  
  
