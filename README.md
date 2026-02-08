# 📊 COVID-19 Data Analysis & Future Forecasting

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📝 Project Overview
This project focuses on the **Exploratory Data Analysis (EDA)** and **Machine Learning Forecasting** of COVID-19 cases in India. 

The goal was to analyze the spread of the virus, visualize key trends (such as the impact of the "Second Wave" and vaccination rates), and predict future cases using Regression models. Additionally, a Classification model was built to identify high-risk days based on mortality rates.

## 📂 Dataset Details
The analysis is based on three key datasets:
1.  **`covid_19_india.csv`**: Daily confirmed cases, deaths, and cured numbers.
2.  **`covid_vaccine_statewise.csv`**: Vaccination progress across states.
3.  **`StatewiseTestingDetails.csv`**: Testing data.

## 🚀 Key Features
* **Data Cleaning:** Handled missing values, date format conversions, and calculated `Active Cases`.
* **EDA (Exploratory Data Analysis):**
    * Trend Analysis of Confirmed vs. Cured vs. Deaths.
    * State-wise impact analysis (Top 10 worst-hit states).
    * Correlation Heatmap to understand relationships between variables.
    * Outlier detection using Boxplots.
* **Machine Learning Models:**
    * **Linear Regression:** Forecasted confirmed cases for the next **30 days**.
    * **Logistic Regression:** Classified days as **"High Risk"** or **"Low Risk"** based on fatality rates.
* **Model Evaluation:**
    * Evaluated models using **MSE (Mean Squared Error)**, **MAE (Mean Absolute Error)**, and **R² Score**.

## 🛠️ Tools & Technologies Used
* **Language:** Python 🐍
* **IDE:** Google Colab
* **Libraries:**
    * `Pandas` & `NumPy` (Data Manipulation)
    * `Matplotlib` & `Seaborn` (Visualization)
    * `Scikit-Learn` (Machine Learning)
    * `Datetime` (Time-series handling)

## 📊 Analysis & Results

### 1. Future Forecasting (Linear Regression)
* **Objective:** Predict confirmed cases for the upcoming month.
* **Result:** The model identified a linear upward trend based on historical data.
* **Accuracy:** Achieved a high **R² Score** on the test dataset.

### 2. Risk Classification (Logistic Regression)
* **Objective:** Classify daily records into High Risk (1) or Low Risk (0).
* **Result:** Successfully classified days with higher-than-average deaths.

## 📷 Screenshots
*(Upload your project screenshots here, e.g., The Trend Graph, Heatmap, and Regression Plot)*

## 🔧 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/COVID19-Data-Analysis-Prediction.git](https://github.com/YourUsername/COVID19-Data-Analysis-Prediction.git)
    ```
2.  Open **Google Colab**.
3.  Upload the `.ipynb` file.
4.  Upload the dataset files to the Colab session.
5.  Run all cells to see the analysis and predictions.

## 👨‍🏫 Mentorship
This project was completed as part of the **BCA Semester 6 (Data Analytics)** curriculum under the guidance of **Dr. Snehal K Joshi**.

---
*Created by Uvesh Shaikh 
