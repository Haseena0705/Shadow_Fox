# 🚗 Car Price Prediction

This project aims to predict the **selling price of cars** using a **Random Forest Regressor** model.

## 📘 Overview
The model is trained on a dataset containing car details such as manufacturing year, present price, kilometers driven, fuel type, seller type, and transmission.  
After preprocessing, the model learns to estimate accurate resale values based on these parameters.

## 🧠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab  

## 🧩 Project Structure
Project2_car_price_prediction/
│
├── notebooks/
│ └── car_price_prediction.ipynb # Jupyter/Colab notebook
│
├── scripts/
│ └── data_preprocessing.py # Script for data cleaning (if needed)
│
├── data/
│ └── car.csv # Dataset used
│
├── models/
│ └── random_forest_model.pkl # Saved trained model (optional)
│
├── results/
│ └── evaluation_metrics.txt # Model performance metrics
│
└── README.md # Project documentation


## ⚙️ How It Works
1. **Data Loading & Cleaning** – Reads the dataset and handles categorical variables.  
2. **Feature Engineering** – Creates new features such as `Car_Age`.  
3. **Model Training** – Uses Random Forest Regressor for prediction.  
4. **Evaluation** – Assesses performance using R² score.  
5. **Prediction** – Predicts selling price for new inputs.

## 📈 Model Performance
- **R² Score:** 0.96 (on test data)
- The model provides highly accurate predictions for car resale prices.

## ✍️ Author
**Haseena Tawfeeqa**  
Developed as part of the **ShadowFox AI/ML Internship Project 2**
