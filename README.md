# Flight Fare Prediction

## Project Summary

### Goal: Predict flight ticket prices using Machine Learning.

- **Dataset:** Flight Fare dataset containing airline, source, destination, journey date, duration, and number of stops.
- **Target Variable:** Price.
- **Key Insights:** Analyzed fare variations based on airlines, routes, travel dates, and journey duration.

---

**1. Requirements:**
- Python, Google Colab
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, LightGBM.

**2. Exploratory Data Analysis:**
- Analyzed feature distributions and statistical summaries.
- Studied price variations across airlines, sources, and destinations.
- Used histograms, countplots, and boxplots.

**3. Data Preprocessing:**
- Handled missing values.
- Extracted date and time features.
- Converted flight duration into minutes.
- Encoded categorical features and scaled numerical features.
- Applied log transformation to the target variable.

**4. Machine Learning Models:**
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- LightGBM Regressor

**5. Model Evaluation:**

- **Best Model:** LightGBM Regressor
- **R² Score:** 82.43%
- **MAE:** ₹1,174.18
- **RMSE:** ₹1,914.87
- **5-Fold Cross-Validation R²:** 88.54%

**6. Conclusion:**

LightGBM achieved the best performance among the four models. This project helped me gain practical experience in data preprocessing, feature engineering, model training, and evaluation.
