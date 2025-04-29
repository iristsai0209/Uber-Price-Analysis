# Uber-Price-Analysis
# 🚕 Uber Fare Prediction Project

Predicting Uber fare amounts based on trip details using data cleaning, feature engineering, and machine learning models.

---

## 🔥 Project Highlights

- 🧹 **Data Cleaning**:  
  Removed missing values, corrected geographical inconsistencies, and eliminated extreme outliers.

- 🧠 **Feature Engineering**:  
  Extracted temporal features (hour, weekday, month) and calculated trip distance using the Haversine formula.

- 📊 **Exploratory Data Analysis (EDA)**:  
  Analyzed fare amount trends across different times of day, days of week, trip distances, and passenger counts.

- 🤖 **Modeling**:  
  Built and compared multiple regression models: Linear Regression, Decision Tree, Random Forest, and XGBoost.

- 🎯 **Model Tuning**:  
  Performed hyperparameter optimization using Grid Search and 10-fold Cross-Validation to improve model performance.

- 🏆 **Best Model**:  
  Random Forest achieved the best performance with MAE of $2.20 and R² of 0.747 on the test set.

- 📈 **Business Insights**:  
  Identified optimal ride booking times and factors influencing fare variability, offering actionable insights for users.

---

## 🛠️ Tech Stack

- **Python**: Pandas, NumPy, scikit-learn, XGBoost
- **Visualization**: Matplotlib, Seaborn
- **Model Evaluation**: GridSearchCV, Cross-Validation
