# Ice Cream Sales Prediction (Polynomial Regression)

A machine learning project that demonstrates how to model non-linear relationships using **Polynomial Regression**. The pipeline reads temperature data, performs simple exploratory checks, transforms features, and compares a standard linear model against various degrees of polynomial functions to optimize prediction accuracy.

---

## 📌 Project Overview
The objective of this project is to predict ice cream sales based on ambient temperature. While a simple linear model assumes a straight-line trend, real-world sales patterns often bend or curve as temperatures shift. This project showcases how increasing a model's polynomial degree can dramatically improve its ability to capture these non-linear patterns.

---

## 📂 Data Source & Details
The analysis uses the **Ice Cream Selling Data** (`Ice_cream selling data.csv`) available on [Kaggle](https://www.kaggle.com/datasets/mirajdeepbhandari/polynomial-regression). 

The dataset consists of a localized sample (49 records) tracking two key continuous variables:
*   `temperature_(°c)`: The independent variable ($X$).
*   `ice_cream_sales_(units)`: The target variable ($y$).

---

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/ice-cream-sales-prediction.git](https://github.com/YOUR_USERNAME/ice-cream-sales-prediction.git)
   cd ice-cream-sales-prediction
