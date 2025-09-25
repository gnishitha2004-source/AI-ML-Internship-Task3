# Linear Regression — AI & ML Internship Task 3

This repository contains the implementation of **Task 3: Linear Regression** for the AI & ML Internship.

## 📌 Objective
Implement and understand **Simple** and **Multiple Linear Regression** using Python (Scikit-learn, Pandas, Matplotlib).

## 📂 Contents
- `linear_regression_notebook.ipynb`: Colab-ready notebook with complete workflow.
- `predictions_sample.csv`: Sample predictions (Actual vs Predicted values).
- `README.md`: This file.

## ⚙️ Steps Performed
1. **Dataset Loading**: Used California Housing dataset (from `sklearn.datasets`) as a proxy for house price prediction.  
2. **Exploratory Data Analysis (EDA)**: Summary statistics, correlations, visualizations.  
3. **Preprocessing**: Feature-target split, train-test split.  
4. **Simple Linear Regression**: One feature (`MedInc`) vs target (`MedHouseValue`).  
   - Trained model  
   - Regression line plotted  
   - Evaluated with MAE, MSE, R²  
5. **Multiple Linear Regression**: All features vs target.  
   - Trained model  
   - Coefficients inspected  
   - Actual vs Predicted plot  
   - Residual analysis  
6. **Evaluation Metrics**: Compared MAE, MSE, R² between simple and multiple regression.  
7. **Interpretation & Assumptions**: Explained coefficients and regression assumptions.  
8. **Interview Q&A**: Common linear regression interview questions answered.

## 📊 Results
- **Simple Regression (MedInc only)** achieved decent accuracy but limited explanatory power.  
- **Multiple Regression (all features)** gave higher R² and lower errors, showing the benefit of using more predictors.  

## 📖 Interview Questions Covered
1. Assumptions of linear regression  
2. How to interpret coefficients  
3. R² score and its significance  
4. MSE vs MAE — when to prefer which  
5. Detecting multicollinearity  
6. Simple vs multiple regression  
7. Linear regression for classification?  
8. Violating regression assumptions  

## 🚀 How to Run
1. Open the notebook in **Google Colab**:  
   - Go to [Google Colab](https://colab.research.google.com/)  
   - Upload `linear_regression_notebook.ipynb`  
   - Run all cells  

2. Or clone this repo and run locally:  
```bash
git clone <your-repo-link>.git
cd <your-repo-name>
pip install -r requirements.txt  # (pandas, numpy, scikit-learn, matplotlib)
jupyter notebook linear_regression_notebook.ipynb
```

## 📝 Notes
- Dataset used: California Housing dataset (`sklearn.datasets.fetch_california_housing`)  
- No Kaggle login or API keys required.  
- Code is **ready-to-run** in Colab.  
