# Airbnb Price Prediction & HR Promotion Clustering  
*(Single Notebooks Project — Cheong_Wei_En_ML_Assignment.ipynb)*

This repository contains a combined machine learning notebook that covers **two major tasks**:

1. **Airbnb Price Prediction** (Supervised Learning — Regression)  
2. **HR Workforce Segmentation for Promotion Insights** (Unsupervised Learning — Clustering)

Both tasks were completed in a single notebook:  
📄 **Cheong_Wei_En_ML_Assignment.ipynb**

---

# 🏘️ Part 1 — Airbnb Price Prediction

## 🎯 Objective  
Predict Airbnb listing prices based on features such as location, room type, availability, and property attributes.

## 🧼 Data Preparation  
- Handled missing values  
- Removed extreme outliers with quantile trimming  
- Applied One-Hot Encoding to categorical columns  
- Conducted EDA such as correlations & distribution plots  

## 🤖 Models Used  
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting  
- XGBoost  
- AdaBoost  
- **Stacking / Voting Ensembles**  
- Hyperparameter tuning using **GridSearchCV**

## 📈 Performance  
- **Best model RMSE ≈ 45.6**  
- Important price drivers include:
  - Room type  
  - Neighbourhood  
  - Availability  
  - Minimum nights  

## 💡 Insights  
- Entire homes/apartments generally have higher prices  
- Certain neighbourhoods have consistently higher demand  
- Hosts can optimise pricing by adjusting availability and property type

---

# 👥 Part 2 — HR Promotion Clustering

## 🎯 Objective  
Use unsupervised learning to segment employees into clusters that help infer promotion readiness **without using promotion labels**.

## 🧼 Preprocessing  
- Removed employee identifiers  
- Encoded categorical columns  
- Standardised numerical features  
- Reduced dimensionality using **PCA**

## 🤖 Clustering Methods  
- **K-Means**  
- **Hierarchical Clustering**  
- Evaluated using **Silhouette Score**

## 📈 Results  
- **Hierarchical Clustering achieved silhouette ≈ 0.78**  
- Identified two main workforce clusters:
  - **Cluster A:** Younger, sales-oriented employees  
  - **Cluster B:** Older, experienced staff across diverse departments  
- Useful for HR policy planning and team restructuring

---

# 📂 Repository Structure
```
Cheong_Wei_En_ML_Assignment.ipynb
README.md
```
- Notebook contains **both the regression and clustering tasks**.
- Dataset sources not included to keep repository size small; please refer to the notebook for EDA and data loading.

---

# 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- PCA, Clustering Algorithms  

---

# 🚀 Future Improvements

- Try advanced models like CatBoost or LightGBM for price prediction  
- Add geospatial features for Airbnb (distance to MRT, attractions)  
- Explore more clusters (k>2) and apply cluster profiling for HR insights  
- Add SHAP or LIME for better model interpretability  

---

# 👤 Author

**Cheong Wei En**  
Data Science Student @ Ngee Ann Polytechnic  
LinkedIn: https://www.linkedin.com/in/cheong-wei-en-222911303

