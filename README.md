# crop_yield_prediction

# 🌾 Agroclimatic Clustering for Crop Yield Prediction
This project focuses on enhancing the accuracy of crop yield prediction by clustering regions into agroclimatic zones based on climate, soil, and geographical characteristics. It combines unsupervised learning (K-Means) and supervised models (Random Forest,XGBOOST,Gradient Boost LSTM) for region-specific yield forecasting.

## 📌 Objective

- Segment agricultural regions into distinct agroclimatic zones.
- Improve crop yield prediction accuracy by using zone-specific models.
- Provide actionable insights for localized agricultural planning and management.

## 🧠 Problem Statement

Traditional crop yield prediction models often fail to account for region-specific variations in climate and soil. This project addresses the need for localized predictions by clustering regions into agroclimatic zones and building separate models for each zone.


## 🛠 Methodology

1. **Data Collection**  
   - Collected multi-year data on temperature, humidity, rainfall, wind speed, and soil nutrients (N, P, K).

2. **Preprocessing**  
   - Cleaned missing values  
   - Scaled numerical features using StandardScaler  
   - Encoded soil types  
   - Merged and structured data for clustering and modeling

3. **Agroclimatic Clustering**  
   - Applied K-Means clustering on climate and soil features  
   - Visualized zones using PCA

4. **Crop Yield Prediction**  
   - Built machine learning models like Random Forest, XGBoost, and CatBoost etc..,
   - Implemented an LSTM model and ARIMA for time-series yield forecasting  
   - Evaluated using R² and MSE metrics

## 📊 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- Jupyter Notebook

## 📈 Results & Inference

- Clustering helped uncover distinct regional patterns in climate and soil.
- Zone-specific yield prediction models performed better than generalized models.
- ARIMA captured temporal trends effectively for time-series forecasting.

## ✅ Key Takeaways

- Agroclimatic clustering enhances model accuracy and interpretability.
- Localized models are more practical for real-world farming decisions.
- Combining unsupervised and supervised learning leads to better performance.



