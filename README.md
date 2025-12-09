# 🏠 Predicting House Prices with Linear Regression

This project demonstrates how to use Linear Regression to predict house prices based on housing features. It was completed as part of the **Oasis Infobyte Data Analytics Internship**.

## 📁 Dataset
- **Source**: [Kaggle - Housing Dataset](https://www.kaggle.com/datasets/ashydv/housing-dataset)
- The dataset includes various features such as number of bedrooms, area, furnishing status, and other factors that affect house prices.

## 🎯 Project Objective
Build and evaluate a linear regression model to predict house prices and gain practical experience in:
- Data preprocessing
- Feature engineering
- Model training and evaluation
- Visualization and interpretation

## 🛠️ Tools and Libraries Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## 🔍 Workflow Summary

1. **Data Loading**  
   Loaded the housing data using Pandas.

2. **Data Exploration**  
   Reviewed structure, checked for missing values, and visualized relationships using pairplots.

3. **Data Preprocessing**  
   Encoded categorical variables using one-hot encoding (`pd.get_dummies`).

4. **Feature Selection**  
   Removed the target variable `price` from features.

5. **Model Training**  
   Trained a Linear Regression model using scikit-learn.

6. **Model Evaluation**  
   Evaluated the model using:
   - **Mean Squared Error (MSE)**: `1.75 Trillion` (high due to rupee scale)
   - **R-squared Score**: `0.65` (indicates a decent fit)

7. **Visualization**  
   Created a scatter plot comparing actual vs predicted prices.

## 📊 Evaluation Result

- **Mean Squared Error (MSE)**: `1,754,318,687,330.66`
- **R-squared Score (R²)**: `0.65`

This indicates the model captures about 65% of the variation in housing prices — a decent performance for a basic linear model.

## 📌 Key Learnings

- Applied linear regression to a real-world problem.
- Practiced data cleaning and feature encoding techniques.
- Learned to evaluate regression models using R² and MSE.
- Built visualizations to understand model accuracy.

Feel free to explore the notebook and run it yourself in Colab or Jupyter. If you found this helpful, give a ⭐ to support the project!

