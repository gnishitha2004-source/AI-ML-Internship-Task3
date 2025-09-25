# 🧠 AI & ML Internship – Task 3  
## 📌 Linear Regression Implementation  

### 🎯 Objective  
The objective of this task is to *implement and understand simple & multiple linear regression* using Scikit-learn, Pandas, and Matplotlib.  
We explore the dataset, train regression models, evaluate their performance, and interpret the results.  

---

### 📂 Dataset  
- *Name:* Housing Price Prediction Dataset  
- *Source:* [Kaggle – Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)  
- *Description:* Contains housing features (area, number of rooms, etc.) and corresponding prices.  

---

### ⚙ Steps Followed  
1. *Import Libraries* → pandas, numpy, matplotlib, seaborn, scikit-learn.  
2. *Load Dataset* → Read CSV file into a DataFrame.  
3. *Preprocess Data*  
   - Checked for missing values.  
   - Handled categorical features (if any).  
   - Selected relevant features.  
4. *Train-Test Split* → Divided dataset into 80% training and 20% testing.  
5. *Model Building*  
   - Implemented *Simple Linear Regression* (price vs. one feature).  
   - Implemented *Multiple Linear Regression* (price vs. multiple features).  
6. *Evaluation Metrics*  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  
7. *Visualization*  
   - Plotted regression line for simple regression.  
   - Compared predicted vs. actual values.  

---

### 📊 Results  

- *Mean Absolute Error (MAE):* X.XX  
- *Mean Squared Error (MSE):* X.XX  
- *R² Score:* X.XX  

(Replace with your actual values from notebook)  

✅ The model shows a reasonable fit with positive R² score.  
✅ Coefficients indicate how each feature influences the target (house price).  

---

### 📈 Plots  
- Scatter plot with regression line (Simple Regression).  
- Predicted vs. Actual house prices.  

(You can insert screenshots from your notebook here if needed)  

---

### 🧾 Interpretation of Coefficients  
- *Intercept (β₀):* Baseline value of price when all features are 0.  
- *Coefficients (βᵢ):* Change in target variable for each unit increase in the respective feature.  
  - Example: If coefficient of Area = 150, then for every additional 1 sq. ft., price increases by 150 (keeping other factors constant).  

---

### ❓ Interview Questions & Answers  

1. *What assumptions does linear regression make?*  
   - Linearity between independent & dependent variables.  
   - Errors are normally distributed.  
   - Homoscedasticity (constant variance of errors).  
   - No multicollinearity among independent variables.  
   - Independence of observations.  

2. *How do you interpret the coefficients?*  
   - Each coefficient shows the expected change in target variable per unit change in the feature, holding others constant.  

3. *What is R² score and its significance?*  
   - R² = proportion of variance in target explained by the model.  
   - Higher R² means better model fit.  

4. *When would you prefer MSE over MAE?*  
   - *MSE* penalizes larger errors more, useful when big errors are unacceptable.  
   - *MAE* treats all errors equally, useful when robustness to outliers is needed.  

5. *How do you detect multicollinearity?*  
   - Correlation matrix (heatmap).  
   - Variance Inflation Factor (VIF) > 10 indicates high multicollinearity.  

6. *What is the difference between simple and multiple regression?*  
   - *Simple Regression:* One independent variable.  
   - *Multiple Regression:* Two or more independent variables.  

7. *Can linear regression be used for classification?*  
   - No, but related methods exist (e.g., Logistic Regression for classification).  

8. *What happens if you violate regression assumptions?*  
   - Model performance decreases.  
   - Coefficients may be biased or unreliable.  
   - Predictions may not generalize well.  

---

### 🚀 Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

### ✅ Conclusion  
- Implemented both simple & multiple linear regression.  
- Evaluated model using *MAE, MSE, R²*.  
- Understood how coefficients affect predictions.  
- Answered key theoretical interview questions related to regression.  

---

### 📎 Submission  
- GitHub Repository Link: [AI-ML-Internship-Task3](https://github.com/gnishitha2004-source/AI-ML-Internship-Task3/tree/main)  
- Task completed as per the internship guidelines.
