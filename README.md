# 🧠 AI & ML Internship – Task 3  
## 📌 Linear Regression Implementation  

### 🎯 Objective  
The objective of this task is to *implement and understand simple & multiple linear regression* using Python libraries such as Scikit-learn, Pandas, and Matplotlib.  
The task focuses on training a regression model, evaluating its performance, visualizing results, and understanding theoretical concepts.  

---

### 📂 Dataset  
- *Source:* Loaded directly in *Google Colab* (not Kaggle).  
- *Environment:* Google Colab + GitHub repository.  
- *Description:* The dataset includes independent features (X) and a dependent target variable (y) to demonstrate regression analysis.  

---

### ⚙ Steps Followed  
1. *Imported Libraries* → pandas, numpy, matplotlib, seaborn, scikit-learn.  
2. *Loaded Dataset* into a Pandas DataFrame.  
3. *Explored & Preprocessed Data*  
   - Checked dataset shape and info.  
   - Handled missing values if any.  
   - Selected independent variables (X) and target variable (y).  
4. *Train-Test Split*  
   - Split dataset into 80% training and 20% testing.  
5. *Model Training*  
   - Implemented *Simple Linear Regression* (1 feature vs. target).  
   - Implemented *Multiple Linear Regression* (multiple features vs. target).  
6. *Evaluation Metrics*  
   - Mean Absolute Error (MAE)  
   - Mean Squared Error (MSE)  
   - R² Score  
7. *Visualization*  
   - Scatter plot with regression line.  
   - Predicted vs. Actual comparison plot.  

---

### 📊 Results  

- *Mean Absolute Error (MAE):* X.XX  
- *Mean Squared Error (MSE):* X.XX  
- *R² Score:* X.XX  

👉 *(Replace X.XX with the actual values from your notebook before final submission.)*  

---

### 📈 Interpretation of Coefficients  
- *Intercept (β₀):* Baseline value of the target variable when all features = 0.  
- *Coefficient (βᵢ):* Expected change in the target variable for each 1-unit increase in the corresponding feature, keeping other features constant.  

---

### 📉 Visualizations  
- Regression line plotted for simple regression.  
- Scatter plot of predicted vs. actual values to check accuracy.  

---

### ❓ Interview Questions & Answers  

1. *What assumptions does linear regression make?*  
   - Linearity, no multicollinearity, independence of errors, homoscedasticity, normally distributed residuals.  

2. *How do you interpret the coefficients?*  
   - Each coefficient = change in target for a unit increase in that feature, keeping others constant.  

3. *What is R² score and its significance?*  
   - R² = proportion of variance in target explained by the model.  
   - Higher R² → better model fit.  

4. *When would you prefer MSE over MAE?*  
   - *MSE* penalizes larger errors more → better when large mistakes must be avoided.  
   - *MAE* is better when robustness to outliers is needed.  

5. *How do you detect multicollinearity?*  
   - Correlation matrix or Variance Inflation Factor (VIF).  
   - VIF > 10 → problematic multicollinearity.  

6. *What is the difference between simple and multiple regression?*  
   - Simple regression = one independent variable.  
   - Multiple regression = two or more independent variables.  

7. *Can linear regression be used for classification?*  
   - Not directly. For classification, we use logistic regression or classification algorithms.  

8. *What happens if you violate regression assumptions?*  
   - Coefficients may be biased.  
   - Predictions become unreliable.  
   - Model accuracy decreases.  

---

### 🚀 Tools & Libraries Used  
- Google Colab  
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

### ✅ Conclusion  
- Implemented both *Simple & Multiple Linear Regression*.  
- Evaluated the model using *MAE, MSE, and R² score*.  
- Interpreted regression coefficients and model results.  
- Answered important theoretical interview questions.  

---

### 📎 Submission  
- *GitHub Repository Link:* [AI-ML-Internship-Task3](https://github.com/gnishitha2004-source/AI-ML-Internship-Task3)  
- *Environment:* Google Colab + GitHub  

✅ Task 3 completed and ready for submission.
