# Uber Fare Prediction Project

Predicting Uber fare amounts based on trip details using data cleaning, feature engineering, and machine learning models.

---

## Project Highlights

- Data Cleaning:  
  Removed missing values, corrected geographical inconsistencies, and eliminated extreme outliers.

- Feature Engineering:  
  Extracted temporal features (hour, weekday, month) and calculated trip distance using the Haversine formula.

- Exploratory Data Analysis (EDA):  
  Analyzed fare amount trends across different times of day, days of week, trip distances, and passenger counts.

- Modeling:  
  Built and compared multiple regression models: Linear Regression, Decision Tree, Random Forest, and XGBoost.

- Model Tuning:  
  Performed hyperparameter optimization using Grid Search and 10-fold Cross-Validation to improve model performance.

- Best Model:  
  Random Forest achieved the best performance with MAE of $2.20 and R² of 0.747 on the test set.

- Business Insights:  
  Identified optimal ride booking times and factors influencing fare variability, offering actionable insights for users.

I worked on analyzing Uber ride data to understand what affects the fare price. I started by cleaning the data like fixing missing or incorrect locations and removing unrealistic trips. I then added helpful information like what time and day the ride happened, and calculated how far each trip was. I explored patterns like when fares tend to be higher and how factors like distance and number of passengers impact cost. After testing different prediction models, the Random Forest model performed best, accurately estimating fares. From this, we found the best times to book rides and key reasons fares go up or down and insights that can help both users and businesses make smarter decisions.
