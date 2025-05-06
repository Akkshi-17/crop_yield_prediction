# 🌾📊 Agroclimatic Clustering for Crop Yield Prediction

This project aims to enhance crop yield prediction by segmenting regions into agroclimatic zones using machine learning and time series forecasting techniques. It integrates climatic and soil-based features to improve prediction accuracy and assist in smarter agricultural planning.

---

## 📌 Project Objective

To predict crop yield more accurately by:

- Clustering regions based on similar agroclimatic conditions (climate + soil).
- Applying supervised ML and deep learning models within these clusters.
- Leveraging historical climate and soil data from **Andhra Pradesh** and **Tamil Nadu** (2004–2021).

---

## 📂 Dataset

The dataset includes:

- **Climate data:** temperature, rainfall, humidity, wind speed.  
- **Soil data:** nitrogen (N), phosphorus (P), potassium (K), soil type.  
- **Crop data:** crop name, production, area, yield, year, district, state.  

**Data Source:** Collected from public repositories and agriculture datasets available on GitHub and governmental portals.

---

## 🧹 Data Preprocessing

- Handled missing values  
- Label encoded categorical features  
- Normalized numerical variables  
- Applied PCA for dimensionality reduction before clustering  

---

## 🧠 Methodology

### Agroclimatic Clustering

- Applied **K-Means** clustering to group similar climatic-soil regions.

### Crop Yield Prediction Models

- **Random Forest**  
- **Gradient Boosting**  
- **XGBoost**  
- **ARIMA (Time-Series)**  
- **LSTM (Deep Learning)**  

> ⚡ Gradient Boosting showed the best performance among ML models.

---

## 📈 Results

- **Gradient Boosting** achieved the highest accuracy for crop yield prediction.
- **LSTM** effectively captured temporal trends for future forecasting.
- Visualized yield trends, cluster distributions, and feature importance.

---

## 📊 Visualizations

- Cluster maps of agroclimatic zones  
- Year-wise and district-wise crop yield graphs  
- Feature importance from models  
- Performance metrics of all models  

---

## ✅ Key Takeaways

- Clustering based on agroclimatic features significantly improves model performance.
- Soil and climate variables are crucial for region-specific crop management.
- Time-series models add robustness for dynamic forecasting.

---

## 🔮 Future Work

- Expand dataset to more states or entire India.
- Incorporate real-time weather APIs for continuous prediction.
- Explore AutoML frameworks for automated model tuning.

---

## 💻 Technologies Used

- Python (Pandas, NumPy)  
- Scikit-learn  
- TensorFlow/Keras (for LSTM)  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 🧑‍💻 Author

**Bandla Akkshitha**  
M.Sc. Data Science, SASTRA Deemed University  
📧 [akkshi17@gmail.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/aab7311a7)
