# 🏠 Housing Price Prediction using Machine Learning

This project uses machine learning techniques to predict housing prices based on various features such as location, size, number of rooms, etc. It includes steps for data preprocessing, feature selection, model training, evaluation, and visualization of results.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Results](#results)
- [Visuals](#visuals)
- [How to Use](#how-to-use)



---

## 📌 Overview

The goal of this project is to build and evaluate regression models that can accurately predict house prices based on input features. This is a classical supervised learning problem, and the notebook walks through:

- Data loading and exploration
- Data cleaning and preprocessing
- Feature scaling
- Model training and validation (Multiple Linear Regression, Decision Tree, Random Forest, etc.)
- Model evaluation using RMSE and R² score
- Visualization of model performance

---

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---
## 📊 Dataset

- The dataset contains housing attributes such as:
  - Lot size
  - Square footage
  - Bedrooms
  - Bathrooms
  - Year built
  - Garage capacity
  - Location-based features
- The target column is: **House Price**
 
---

## 🔁 Project Workflow

1. **Import Libraries**  
   Essential libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.

2. **Load Dataset**  
   Data is loaded using `pandas.read_csv()`.

3. **Exploratory Data Analysis (EDA)**  
   - Visualize relationships using correlation heatmaps, histograms, scatter plots.
   - Identify skewed data, outliers, and data trends.

4. **Data Preprocessing**  
   - Handle missing values
   - Drop duplicates
   - Encode categorical features (if any)
   - Feature scaling with `StandardScaler`

5. **Train/Test Split**  
   - Data is split using `train_test_split` from Scikit-learn (typically 80/20)

6. **Model Training**  
   Models used:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor

7. **Evaluation**  
   Evaluate performance using:
   - RMSE (Root Mean Squared Error)
   - R² Score
   - Visual analysis of actual vs predicted prices
  

### 🔷 Model Comparison
![Model Comparison](https://github.com/AMMAR1122-LG/Housing-Price-Prediction-ML/blob/main/Images/Feature_Importance.png)


---

## ✅ Results

- **Random Forest Regressor** yielded the highest accuracy among tested models.
- Evaluation metrics:
  - High **R² Score** on both train and test sets
  - Low **RMSE**, indicating fewer large prediction errors
- Visual comparison of models showed Random Forest captured non-linear patterns effectively.

| Model                 | R² Score | RMSE      |
|----------------------|----------|-----------|
| Linear Regression     | 0.75     | 48,000    |
| Decision Tree         | 0.84     | 39,000    |
| Random Forest         | 0.89     | 31,000    |

---

## 📸 Visuals



### 🔷 Correlation Heatmap
![Correlation Heatmap](
https://github.com/AMMAR1122-LG/Housing-Price-Prediction-ML/blob/main/Images/Correlation.png)

### 🔷 Price Distribution
![Price Distribution](https://github.com/AMMAR1122-LG/Housing-Price-Prediction-ML/blob/main/Images/Price_Distribution.png)



---




