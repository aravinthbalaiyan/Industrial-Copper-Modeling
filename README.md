# Industrial Copper Modeling Project ⚙

## Introduction
This project, titled "Industrial Copper Modeling," is an application of data analysis and machine learning techniques to address challenges in the copper industry. It involves building predictive models for both regression (predicting Selling Price) and classification (predicting the success or failure of leads), as well as creating an interactive web application using Streamlit for model deployment.

![ICM](https://github.com/aravinthbalaiyan/Industrial-Copper-Modeling/assets/144364538/f7318534-1983-47e6-8cd7-79b3f09be13c)

## Approach
- Data Understanding:
- Identify variable types (continuous, categorical) and their
  distributions.
- Handle categorical variables with '00000' values and treat reference   
  columns as categorical.
- Data preprocessing, including handling missing values and skewness.

## 1. EDA:
- Visualize outliers and skewness using Seaborn's boxplot, distplot, 
  violinplot.
- Feature engineering and identifying highly correlated columns.

## 2. Model Building and Evaluation:

## 3. Model GUI:
- Create an interactive Streamlit web application.
- Accept input data and perform necessary feature engineering.
- Display predictions for Selling Price or Status (Won/Lost).

## Getting Started
Dependencies
To run this project, you'll need:
Python (>=3.6)
Jupyter Notebook (optional, for exploring notebooks)
Libraries listed in requirements.txt

Install the dependencies using pip:
pip install -r requirements.txt

Usage
Clone this repository:
git clone [[https://github.com/yourusername/industrial-copper-modeling.git](https://github.com/aravinthbalaiyan/Industrial-Copper-Modeling/tree/main)](https://github.com/aravinthbalaiyan/Industrial-Copper-Modeling/tree/main)
cd industrial-copper-modeling
Place your dataset files in the data/ directory.

Explore the Jupyter notebooks in the notebooks/ directory for data analysis and model development.

To run the Streamlit app:
streamlit run src/app.py

Interact with the Streamlit app to make predictions and visualize results.

This project is licensed under the MIT License.







