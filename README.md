# **Polynomial Linear Regression: Truth or Bluff - Salary Prediction**  
This project demonstrates the use of **Polynomial Linear Regression** to predict the salary of employees based on their position in a company. The model helps to identify whether a proposed salary is realistic or a "bluff" by modelling the non-linear relationship between position and salary using polynomial regression.

## **🛠 Technologies Used**  
**Programming Language:** Python  
**Libraries:**  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

## **📊 Project Overview**  
- **Goal:** Predict employee salary based on their position, and determine whether a proposed salary is a bluff.  
- **Dataset:** Contains data on employee position and corresponding salary.  

## **🔑 Key Learnings**  
- **Understanding Polynomial Regression:**  
  - Modeled the relationship between position and salary using higher-degree polynomials to capture the non-linear behaviour.  
  - The equation used was:  
    **𝑦 = 𝑏₀ + 𝑏₁𝑥₁ + 𝑏₂𝑥₂² + ... + 𝑏ₙ𝑥ₙⁿ.**  

- **Data Preprocessing:**  
  - The data was scaled to fit a polynomial curve accurately.  
  - Used **Scikit-learn's PolynomialFeatures** to generate polynomial features from the data.  

- **Model Training:**  
  - Built and trained the polynomial regression model using **Scikit-learn**.  
  - Ensured good model evaluation by splitting the dataset into training and testing sets.  

- **Visualization:**  
  - Visualized the polynomial regression curve using **Matplotlib** to observe the fit and detect the true or bluff nature of the salary.  

## **🚀 Results**  
- Developed a model that predicts salaries for a given position and identifies whether the proposed salary is bluff or truthful.  
- Demonstrated the power of polynomial regression to capture complex non-linear relationships between position and salary.  
- Emphasized the importance of feature scaling and polynomial transformation for accurate model fitting.
