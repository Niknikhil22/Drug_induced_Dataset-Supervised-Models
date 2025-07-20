# 📊 Regression Model Evaluation and Comparison

This project compares the performance of multiple regression models using key evaluation metrics: **R² Score** and **RMSE (Root Mean Squared Error)**. The goal is to identify the best-performing model(s) for a given dataset based on predictive accuracy and error.

---

## 🧠 Models Compared
- Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- XGBoost Regressor
- LightGBM Regressor
- CatBoost Regressor
- K-Nearest Neighbors Regressor
- SVR (Support Vector Regressor)

---

## 📈 Metrics Used
1. **R² Score**  
   Indicates how well the predictions match the actual values. Ranges from `-∞ to 1`. A higher R² score indicates better model performance.

2. **RMSE (Root Mean Squared Error)**  
   Measures the average magnitude of errors in predictions. Lower RMSE indicates better performance.

---

## 📊 Visualizations

Two bar plots are created for comparative evaluation:

- **R² Score Bar Plot**:  
  Models with positive R² scores are shown in green, others in red.

- **RMSE Score Bar Plot**:  
  Lower RMSE scores (better performance) are shown in green, higher ones in red.

Each bar is labeled with its exact score for easy interpretation.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost, LightGBM, CatBoost (for gradient boosting models)

---

## 📂 Files

- `Code File.ipynb`: Main Jupyter Notebook with model training and evaluation.
- `r2_barplot.png`: R² score bar chart.
- `rmse_barplot.png`: RMSE score bar chart.

---

## ✅ How to Run

1. Clone the repository or download the notebook.
2. Ensure all required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm catboost
