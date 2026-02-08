# Task 3 – Car Price Prediction

This project is part of the **Data Science Internship at OASIS INFOBYTE**.  
The goal of this task is to build a Machine Learning regression model that predicts the selling price of used cars based on vehicle features.

---

# Objective
To develop a regression model that accurately predicts the selling price of a car using factors such as present price, car age, fuel type, transmission type, and kilometers driven.

---

# Dataset Information

The dataset contains details of used cars.

### Features Used
- Present Price  
- Driven_kms  
- Fuel Type  
- Selling Type  
- Transmission  
- Owner  
- Car Age (engineered from Year)

Target variable: **Selling Price**

---

# Machine Learning Workflow

1. Load the dataset  
2. Remove unnecessary columns  
3. Perform feature engineering (Car Age)  
4. Encode categorical variables  
5. Split dataset into training and testing sets  
6. Train Random Forest Regressor  
7. Evaluate model performance  
8. Visualize feature importance  
9. Plot Actual vs Predicted prices  

---

# Model Used
**Random Forest Regressor**

Reason for using:
- Handles nonlinear relationships  
- Works well with mixed data types  
- Provides feature importance  
- High prediction accuracy  

---

# Results

- **Mean Absolute Error (MAE):** 0.64  
- **R² Score:** 0.958  
Model shows strong ability to predict used car prices.

---

# Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

# How to Run

1. Open the project folder. 
2. Launch Jupyter Notebook or open the notebook in Google Colab. 
3. Open the `.ipynb` file for the task. 
4. Upload the required dataset file when prompted (if not already included). 
5. Click **Runtime → Run All** (Colab) or **Run → Run All Cells** (Jupyter).

---

# File Structure

```bash
Task3_Car_Price_Prediction/
├── car_data.csv
├── car_price_prediction.py
└── README.md
```

---

