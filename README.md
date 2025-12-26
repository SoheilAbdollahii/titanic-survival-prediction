# 🚢 Titanic Survival Prediction: End-to-End ML Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Powerful-green?logo=xgboost)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

An advanced Data Science project that predicts the survival probability of Titanic passengers using a fine-tuned **XGBoost** classifier. This project covers everything from raw data exploration to a production-ready saved model.

---

## 📊 Project Roadmap

### 1. Exploratory Data Analysis (EDA)
Deep dive into the Titanic dataset to find correlations between features like `Sex`, `Pclass`, and `Fare` with the survival rate.

### 2. Professional Data Cleaning
- **Smart Imputation:** Age gaps filled using the median of grouped `Pclass` and `Sex`.
- **Feature Engineering:** - `Family_Size`: Combined siblings and parents.
  - `Is_Alone`: Created a binary feature for solo travelers.
- **Log Transformation:** Normalizing skewed `Fare` data using `np.log1p`.

### 3. Model Training & Optimization
Compared multiple algorithms (Logistic Regression, Random Forest, SVM) and selected **XGBoost** for the final model.
- **Hyperparameter Tuning:** Optimized using `GridSearchCV`.
- **Accuracy:** ~83% - 85% on unseen data.

---

## 🧠 Key Findings

- **Gender was the strongest predictor:** Females had a significantly higher survival rate.
- **Wealth mattered:** Passengers in 1st class had better access to lifeboats.
- **Age groups:** Children and elderly passengers were prioritized in certain classes.

---

## 🛠️ Installation & Usage

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/titanic-survival-prediction.git](https://github.com/YOUR_USERNAME/titanic-survival-prediction.git)
