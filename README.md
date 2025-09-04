# 🌾 Crop Price Prediction

## 📌 Project Overview
This project aims to **analyze and preprocess crop price data** to understand patterns and prepare the dataset for building machine learning models.  
It is designed as a beginner-friendly data science project to demonstrate skills in **data preprocessing, cleaning, and exploratory analysis**.

## 📂 Repository Contents
- `crop_price_dataset.csv` → Raw dataset containing crop prices.  
- `data_preprocess.ipynb` → Jupyter/Colab notebook with data preprocessing steps.  
- `README.md` → Project documentation.  

## 🚀 Steps Performed
1. **Data Loading** – Read dataset into Pandas DataFrame.  
2. **Data Cleaning** – Handling missing values, removing duplicates, fixing inconsistencies.  
3. **Exploratory Data Analysis (EDA)** – Basic descriptive statistics and visualization.  
4. **Feature Preparation** – Preparing dataset for machine learning models (scaling, encoding if required).  

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib / Seaborn  
- Google Colab  

## 📊 Future Work
- Apply **Machine Learning models** (e.g., Linear Regression, Random Forest, XGBoost).  
- Predict **future crop prices** based on historical data.  
- Build a **web app** to make predictions user-friendly.  

## 🤝 How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/crop-price-prediction.git
# Week-2 Crop Price Prediction

## 📌 Aim
To apply **Machine Learning models** (starting with Linear Regression) on the preprocessed crop price dataset and evaluate performance.

---

## 📂 Dataset
- Same dataset used in Week-1 (crop price dataset with commodity, prices, state, district, etc.)
- Already preprocessed in **Week-1**:
  - Missing values handled
  - Duplicates removed
  - Outliers treated
  - Encoding applied

---

## ⚙️ Steps Performed
1. **Data Loading**
   - Re-used preprocessed dataset from Week-1.

2. **Feature & Target Selection**
   - **Target:** `avg_modal_price`  
   - **Features:** Remaining columns (prices, categorical encodings, etc.)

3. **Model Training**
   - Split dataset into:
     - **Train (80%)**
     - **Test (20%)**
   - Applied **Linear Regression** model from `scikit-learn`.

4. **Model Evaluation**
   - Calculated **Mean Squared Error (MSE)**
   - Calculated **R² Score**

---

## 📊 Results
- **Mean Squared Error (MSE):** ~ 3401.10  
- **R² Score:** ~ 0.9996  

✅ The model achieved a very high R² score, showing that it can predict average crop prices with excellent accuracy.

---

## 📌 Conclusion
- Completed **first ML model implementation** (Linear Regression).  
- Evaluated model performance with strong results.  
- This milestone covers **Week-2 (60% project completion)**.  
- Next steps: Experiment with advanced models (Random Forest, XGBoost, etc.) and compare results.

---

