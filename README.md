# risk_prediction_for_loan_application
# Machine Learning-Based Risk Prediction Model for Loan Applications

## 📌 Project Overview
This project focuses on predicting loan default risk using machine learning techniques. The goal is to identify whether a customer is likely to default on a loan based on their financial and credit-related information. This helps financial institutions make better loan approval decisions and reduce risk.

---

## 🎯 Objectives
- To analyse customer financial data using exploratory data analysis (EDA)
- To preprocess and prepare the dataset for modelling
- To implement machine learning models for loan default prediction
- To evaluate model performance using multiple metrics
- To improve performance using hyperparameter tuning

---

## 📊 Dataset
- Dataset: **Home Credit Default Risk (Kaggle)**
- Records: ~307,000 customer entries
- Features:
  - Financial (income, credit, annuity)
  - Demographic (gender, education, family details)
- Target Variable:
  - `0` → No Default
  - `1` → Default

---

## ⚙️ Technologies Used
- Python
- Google Colab
- Libraries:
  - Pandas, NumPy (Data Processing)
  - Matplotlib (Visualization)
  - Scikit-learn (Machine Learning)
  - XGBoost (Advanced Model)

---

## 🔍 Methodology
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing (handling missing values, encoding, scaling)
3. Train-Test Split (80:20)
4. Model Training:
   - Logistic Regression
   - Random Forest
   - XGBoost
5. Hyperparameter Tuning (GridSearchCV)
6. Model Evaluation

---

## 🤖 Models Used
- Logistic Regression (Baseline Model)
- Random Forest (Ensemble Model)
- XGBoost (Boosting Model)

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

## 📊 Results
- Logistic Regression: Basic performance
- Random Forest: Improved results
- XGBoost: Best performance

👉 **Best Model:** XGBoost  
👉 **ROC-AUC Score:** ~0.75  

---

## 📉 Key Insights
- Dataset is imbalanced (more non-default cases)
- Financial features are strong predictors
- Ensemble models outperform simple models

---

## 🔧 Hyperparameter Tuning
- Applied using GridSearchCV
- Improved performance of Random Forest and XGBoost
- XGBoost remained the best model after tuning

---

## 🚀 Conclusion
Machine learning models can effectively predict loan default risk. Among the models tested, XGBoost achieved the best performance. However, the results suggest that further improvements are possible with better feature engineering and additional data.

---

## 🔮 Future Work
- Include more financial and behavioural features
- Handle class imbalance using advanced techniques
- Apply deep learning models
- Test on real-world banking datasets


---

## 👨‍🎓 Author
**Jaya Krishna Katta**  
MSc Data Science  
University of Hertfordshire  

---


## 📚 References
- Yeh & Lien (2009)
- Lessmann et al. (2015)
- Chen & Guestrin (2016)
- Brown & Mues (2012)
- Khandani et al. (2010)

---
