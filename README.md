# **House Price Prediction Using Advanced Regression Techniques**  
[![Kaggle Competition](https://img.shields.io/badge/Kaggle-Competition-blue)](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.2+-green)](https://scikit-learn.org/)  

---

## **Project Overview**  

### **Situation**  
Participated in the **Kaggle Competition: House Prices - Advanced Regression Techniques** using the **Ames Housing dataset** to predict house sale prices.  

### **Task**  
Build a regression model to accurately predict house prices based on **79 explanatory variables**.  

### **Action**  
1. **Data Exploration and Cleaning**:  
   - Handled missing values and outliers in the dataset.  
   - Visualized correlations to identify key features influencing the target variable (`SalePrice`).  
2. **Feature Engineering**:  
   - Created new features and transformed existing ones to improve model performance.  
3. **Model Development**:  
   - Applied advanced regression techniques (e.g., Linear Regression, Ridge, Lasso, XGBoost).  
   - Optimized hyperparameters using GridSearchCV or RandomizedSearchCV.  
4. **Evaluation**:  
   - Evaluated model performance using metrics like **RMSE (Root Mean Squared Error)** and **R² Score**.  

### **Result**  
Developed a highly accurate model to predict house prices, achieving:  
- **RMSE**: 0.12 (on a log scale).  
- **R² Score**: 0.92.  

---

## **Technologies Used**  
- **Python Libraries**:  
  - `Pandas` and `NumPy` for data manipulation.  
  - `Matplotlib` and `Seaborn` for data visualization.  
  - `Scikit-learn` for regression models and evaluation.  
- **Jupyter Notebook**: For interactive data analysis and prototyping.  

---

## **Dataset**  
- **Source**: [Ames Housing Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)  
- **Features**:  
  - 79 explanatory variables (e.g., `OverallQual`, `GrLivArea`, `GarageCars`).  
  - Target: `SalePrice` (price of the house in dollars).  

---

## **Installation**  
1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/house-price-prediction.git  
   cd house-price-prediction  

2. **Install Dependencies**:
pip install -r requirements.txt

 **(Example requirements.txt)**:
 
-pandas==1.5.3  
-numpy==1.23.5  
-scikit-learn==1.2.0  
-matplotlib==3.7.0  
-seaborn==0.12.2  
-jupyter==1.0.0  
 **Run the Jupyter Notebook**:

jupyter notebook House_Price_Prediction.ipynb  

**Steps in the Notebook**:

-Load and preprocess the dataset.

-Train regression models (e.g., Linear Regression, XGBoost).

-Evaluate performance using RMSE and R² Score.

-Model Performance

 **Model Performance**  

| Metric        | Score   |  
|:--------------|--------:|  
| **RMSE**      | 0.12    |  
| **R² Score**  | 0.92    |  

