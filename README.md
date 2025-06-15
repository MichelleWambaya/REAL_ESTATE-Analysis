#  Real Estate Data Analytics in Kenya – Project Notes

This project presents a data analytics case study using a fictional real estate dataset from Kenya. It aims to extract insights and build predictive models that estimate property prices using machine learning.

---

##  1. Project Overview

This notebook simulates a dataset for Kenyan housing properties and applies analytics to:

- Understand housing market trends  
- Identify key features affecting pricing  
- Predict property prices using machine learning  

---

##  2. Data Generation

A synthetic dataset was generated to resemble real-world Kenyan housing data, including:

- `Bedrooms`, `Bathrooms`, `Size_sqm`, `Proximity_CBD_km`  
- `Location`: Nairobi, Mombasa, Kisumu, Eldoret  
- `House_Type`: Apartment, Bungalow, Maisonette  
- `Price_KES`: Simulated price values based on features  

The data was generated with logical patterns, such as larger or better-located houses costing more.

---

##  3. Exploratory Data Analysis (EDA)

Key insights from the dataset:

- **Size and price** are positively correlated  
- **Proximity to CBD** inversely affects price  
- **Nairobi and Mombasa** tend to have higher average prices  
- **House type** influences pricing (e.g., Maisonettes are more expensive)  

Tools used include bar plots, scatter plots, boxplots, and correlation heatmaps.

---

##  4. Feature Engineering

Selected features:

- `Bedrooms`, `Bathrooms`, `Size_sqm`, `Proximity_CBD_km`  
- Target: `Price_KES`  

These features are both interpretable and relevant to home buyers and sellers in Kenya.

---

##  5. Machine Learning Models

### 🔹 Linear Regression

- Assumes a linear relationship between features and price  
- Easy to interpret and a good baseline  
- Metrics:   
  - **Mean Absolute Error (MAE)**  
  - **R² Score**  

### 🔹 Random Forest Regressor

- Ensemble model combining multiple decision trees  
- Captures non-linear relationships  
- More accurate and robust than linear models  
- Outputs feature importance scores  

#### Sample Evaluation:
```
Random Forest MAE: 387,412
Random Forest R² Score: 0.82
```
---

## 📈 6. Visual Insights

- **Scatter plot** of actual vs predicted values shows model accuracy  
- **Line plot** highlights the prediction trend vs true prices  
- **Feature importance** ranks input variables' impact on price  

---

##  7. Next Steps

- Add features like `property age`, `amenities`, or `land rates`  
- Include geospatial data (coordinates, zones)  
- Tune Random Forest parameters for better results  
- Build an interactive dashboard using Streamlit  

---

##  8. Conclusion

This project demonstrates how data analytics and machine learning can be applied to Kenya's real estate market. Even with synthetic data, we gain valuable insights into how features influence property value and how predictive models can support pricing decisions.

