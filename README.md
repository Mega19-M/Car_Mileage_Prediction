# Car Mileage Prediction 

This project is completed as part of the Artificial Intelligence and Machine Learning (AI/ML) Internship at **NeuroTech Solutions**.

## 📌 Project Overview
The objective of this project is to build and evaluate a Machine Learning model using **Linear Regression** to predict vehicle fuel efficiency in Miles Per Gallon (MPG) based on numerical vehicle attributes.

## 📊 Dataset
* **Source:** Auto MPG dataset (via Seaborn / UCI Machine Learning Repository).
* **Features Used:** `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, and `model_year`.
* **Target Variable:** `mpg` (Miles Per Gallon).

## 🛠️ Tech Stack & Libraries
* **Programming Language:** Python
* **Platform:** Google Colab / Jupyter Notebook
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## 📈 Model Performance
* **Mean Absolute Error (MAE):** 2.4668 MPG
* **R² Score:** 0.8244 (indicating that ~82.4% of the variance in fuel efficiency is explained by the model)

## 📉 Visualizations Included
1. **Correlation Heatmap:** To analyze linear relationships across features.
2. **Scatter Plot with Regression Line:** Showing the strong negative impact of vehicle weight on fuel economy.
3. **Box Plot:** Illustrating the upward trend in fuel efficiency across vehicle model years (1970–1982).

## 📝 Key Insight
Based on model coefficients and feature analysis, **vehicle weight** and **model year** are the most influential factors determining fuel efficiency—heavier cars consume significantly more fuel, while newer model years reflect notable improvements in fuel economy over time.

---
**Author:** Mega M  
**Internship Domain:** AI & ML (NeuroTech Solutions)
