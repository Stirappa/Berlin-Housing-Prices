# 🏙️ Berlin Housing Prices — Machine Learning Project
### *Inspired by the Kaggle “House Prices: Advanced Regression Techniques” Competition*

This project is inspired by the well-known Kaggle Housing Prices competition, but instead of using the Iowa dataset, the goal here is to apply a similar machine-learning pipeline specifically to the **Berlin real-estate market**.

The project focuses on understanding what drives apartment and house prices in Berlin, preparing a clean dataset, performing exploratory data analysis (EDA), engineering useful real-estate features, and building predictive models capable of estimating property prices.

This repository is ideal for anyone learning:

- Data cleaning  
- Feature engineering  
- Categorical encoding  
- Regression modeling  
- Real-world ML workflows  
- Jupyter Notebook data science projects  

---

## 📦 Project Files

```
├── Berlin Housing Prices.ipynb     # Main notebook
├── README.md                       # Project documentation
├── LICENSE
└── real_estate_listings_clean.csv  
```

---

## 🎯 Project Motivation

Berlin is one of Europe’s most dynamic and rapidly growing housing markets. Factors influencing prices include:

- Location (Bezirk / district)  
- Apartment size  
- Age of building  
- Energy efficiency  
- Number of rooms  
- Zipcode  
- price per area

Inspired by the Kaggle house price regression challenge, the main goals were:

1. Recreate a similar machine learning workflow  
2. Adapt it to Berlin housing characteristics  
3. Train models that predict real-world property prices  
4. Practice and demonstrate end-to-end data science skills  

---

## 🧹 1. Data Cleaning & Preparation

### ✔ Handling missing values
Missing data was not found. But features has been encoded, or removed depending on the importance of the feature.

### ✔ Removing irrelevant columns
Columns that provide no predictive value—like listing URLs—were removed.

### ✔ Standardizing and encoding categorical features
Districts, energy-efficiency labels, and building types were cleaned and encoded using **Numeric Representation**.

### ✔ Feature normalization
Applied where necessary depending on the model.

---

## 📊 2. Exploratory Data Analysis (EDA)

Visualizations included:

- Price distribution  
- Surface area and room distributions  
- Correlation heatmap  
- District-level comparisons  
- Outlier detection  

### Key Insights

- District strongly influences price  
- Area (m²) is the strongest numeric predictor  
- Energy-efficient homes tend to be more expensive  
- Luxury districts show notable outliers  

---

## 🧱 3. Feature Engineering

Engineered or transformed features include:

- Energy label → numerical scoring  
- Price per square meter  
- Building age categories  
- Room count categories  

Effective feature engineering significantly improved model performance.

---

## 🤖 4. Machine Learning Models

Models evaluated:

### 🔹 Gradient Boosting Regressor  
Captures complex, non-linear patterns and handles encoding well.

### 🔹 Optional Future Models  
- LightGBM  

## 📐 5. Evaluation Metrics

To evaluate the models, we used:

- **MAE** — Mean Absolute Error  
- **RMSE** — Root Mean Squared Error  

---

## 🧾 6. Results Summary

General findings:

- Random Forest performed best  
- Area (m²) and district were the most influential features  
- Energy efficiency had moderate influence  
- Feature engineering improved accuracy significantly  

---

## 🔮 Future Improvements

- Add geographic coordinates  
- Build interactive maps (Folium, Plotly)  
- Use hyperparameter tuning  
- Train advanced boosting models  
- Deploy a Streamlit price predictor app  

---

## 🙌 Acknowledgements

- Inspired by the Kaggle Housing Price Competition  
- Built with Python, Pandas, Matplotlib, Scikit-Learn  
- Thanks to the open-source community  

