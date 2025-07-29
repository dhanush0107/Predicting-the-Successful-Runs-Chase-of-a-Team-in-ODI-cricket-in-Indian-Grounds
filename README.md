# 🏏 ODI Run Chase Prediction on Indian Grounds

This project uses **machine learning models** to predict the probability of a successful run chase in ODI matches played in Indian stadiums.  
The model analyzes historical data of ODI cricket and considers match conditions, target scores, overs left, wickets in hand, and venue factors.

---

## 📂 Files in Repository
- `ODI_RunChase_Prediction.ipynb` → Jupyter Notebook with preprocessing, feature engineering, and model training  
- `README.md` → Documentation of the project  

---

## ⚙️ Libraries Used
The following Python libraries were used:
- **pandas** → Data manipulation  
- **numpy** → Numerical operations  
- **matplotlib** & **seaborn** → Data visualization  
- **scikit-learn** → Machine learning models  
- **xgboost** → Gradient boosting for classification  

---

## 📝 Workflow
1. **Data Collection** → Historical ODI match data from Indian grounds  
2. **Data Preprocessing** → Handling missing values, encoding categorical features (teams, venues, etc.)  
3. **Feature Engineering** → Overs left, required run rate, wickets in hand, ground factor  
4. **Model Building** → Logistic Regression, Random Forest, XGBoost  
5. **Model Evaluation** → Accuracy, Precision, Recall, F1-Score, ROC-AUC  
