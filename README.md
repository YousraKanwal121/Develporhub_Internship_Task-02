# 🏦 Bank Marketing Campaign Prediction
This project analyzes a bank marketing dataset to predict whether a customer will subscribe to a term deposit based on demographics, account details, and past interactions. It applies multiple classification models (Logistic Regression, Random Forest, Gradient Boosting, SVM) and evaluates them using Accuracy, F1-Score, ROC-AUC, and Confusion Matrices. Explainable AI techniques (SHAP) are used to interpret model predictions and understand customer behavior for targeted marketing strategies.
---

## 📂 Dataset
**Bank Marketing Dataset (UCI Machine Learning Repository)**  
Contains customer demographic, account, and past interaction information.  
The goal is to predict whether a customer will subscribe to a term deposit.  

---

## 🎯 Objectives
- Predict customer subscription to term deposits using historical data  
- Apply multiple classification models to improve prediction accuracy  
- Evaluate models using Accuracy, F1-Score, ROC-AUC, and Confusion Matrices  
- Use SHAP to interpret model predictions and understand customer behavior  
- Suggest targeted marketing strategies based on insights  

---

## 🛠️ Tools & Libraries
- **Python**  
- **Pandas, NumPy** for data handling  
- **Scikit-learn** for modeling  
- **Matplotlib, Seaborn** for visualization  
- **SHAP** for model interpretability  

---

## 🔍 Methodology
1. **Data Loading & Cleaning**  
   - Load CSV file and inspect dataset  
   - Check for missing values (none found)  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of categorical and numerical features  
   - Analysis of target variable (`deposit`)  

3. **Feature Encoding**  
   - Label Encoding for all categorical features  
   - Target variable encoded for modeling  

4. **Train-Test Split**  
   - Split dataset into training (70%) and testing (30%) sets  

5. **Model Training**  
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting  
   - Support Vector Machine (SVM)  

6. **Model Evaluation**  
   - Accuracy, F1-Score, ROC-AUC  
   - Confusion Matrix visualization  

7. **Explainable AI**  
   - Use SHAP to explain at least 5 individual predictions  
   - Understand features driving subscription behavior  

---

## 📊 Results & Insights
- Different models produce varying accuracy; Gradient Boosting and Random Forest often perform best  
- Confusion matrices help identify misclassification patterns  
- SHAP explanations reveal key features influencing customer decisions:  
  - Age, balance, previous campaign outcomes, contact type, and job category  
- Insights can guide targeted marketing strategies to improve term deposit subscriptions  

---

## 📈 Marketing Strategies
- **High probability customers** → Personalized offers and promotions  
- **Low probability customers** → Retention campaigns, education about term deposits  
- Feature-based segmentation allows **more efficient resource allocation**  

---

## ✅ Skills Demonstrated
- Classification modeling with multiple algorithms  
- Feature encoding and preprocessing  
- Model evaluation using multiple metrics  
- Model interpretability using SHAP  
- Data-driven marketing insights and strategy development  

---

## 🚀 Conclusion
This project demonstrates how machine learning can be used to predict bank customer behavior and provide actionable insights for marketing campaigns.  
By applying multiple models and using explainable AI, we can better understand why customers subscribe and optimize marketing efforts accordingly.  

