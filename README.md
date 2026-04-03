# Healthcare Correlation & Regression Analysis

## 📌 Overview

This project analyzes the relationship between **age** and **blood pressure** using statistical and machine learning techniques.

The goal is to understand:

* Whether a relationship exists between the variables
* How strong this relationship is
* Whether it is statistically significant
* How well we can model and predict blood pressure

---

## 📊 Methods & Techniques

### 🔹 Exploratory Analysis

* Data visualization (scatter plots)
* Trend identification

### 🔹 Correlation Analysis

* Pearson correlation coefficient
* Statistical significance (p-value)

### 🔹 Linear Regression (Machine Learning)

* Model fitting using `scikit-learn`
* Interpretation of slope and intercept
* Prediction of blood pressure values
* R² score evaluation

### 🔹 Advanced Statistical Regression

* Ordinary Least Squares (OLS) using `statsmodels`
* Hypothesis testing on model coefficients
* p-values for statistical significance
* Confidence intervals for parameter estimation

---

## 🧠 Key Results & Insights

* Strong positive relationship between **age and blood pressure**

* Regression coefficient (slope) indicates:

  > Blood pressure increases with age

* Statistical analysis shows:

  * Extremely low p-value → relationship is **highly significant**
  * Confidence interval does not include zero → **robust effect**

* Model performance:

  * R² ≈ 0.70 → model explains ~70% of variability

---

## 🏥 Interpretation (Healthcare Context)

* Age is a significant predictor of blood pressure
* The model can be used for:

  * Risk estimation
  * Trend analysis
  * Clinical data exploration

---

## 🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* SciPy
* Scikit-learn
* Statsmodels

---

## 📁 Project Structure

```
correlation-regression-healthcare/
│
├── healthcare-correlation-regression-analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 📈 Future Improvements

* Multiple regression (adding more features)
* Model validation (train/test split)
* Residual analysis and diagnostics
* Application to real-world datasets

---

## ⭐ Notes

This project demonstrates:

* Statistical thinking
* Data analysis workflow
* Machine learning fundamentals
* Interpretation of model results

---
