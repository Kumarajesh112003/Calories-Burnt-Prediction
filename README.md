# 🔥 Calories Burnt Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting the number of calories burned during physical activity using a machine learning regression model. The model utilizes personal and physiological data to provide accurate calorie expenditure predictions.

## 📂 Dataset Description
The dataset used for training includes the following features:

| Column         | Description                                   |
|----------------|-----------------------------------------------|
| User_ID        | Unique identifier for each user               |
| Gender         | Gender of the individual (male/female)        |
| Age            | Age in years                                  |
| Height         | Height in centimeters                         |
| Weight         | Weight in kilograms                           |
| Duration       | Duration of the activity in minutes           |
| Heart_Rate     | Heart rate during the activity (bpm)          |
| Body_Temp      | Body temperature in Celsius                   |
| Calories       | Target variable - calories burned             |

## ⚙️ Technologies Used
- Python
- Pandas & NumPy for data handling
- Matplotlib & Seaborn for visualization
- XGBoost (XGBRegressor) for model training and prediction
- Scikit-learn for preprocessing and evaluation
- Jupyter Notebook for experimentation

## 🧪 Model Workflow

1. Data Preprocessing
   - Encoded categorical feature (Gender) to numerical format (male → 0, female → 1)
   - Standardized numerical features using StandardScaler
   - Handled missing or inconsistent data

2. Model Training
   - Trained using XGBRegressor from the xgboost library
   - Performed train-test split for model validation
   - Tuned hyperparameters for optimal performance

3. Evaluation
   - Evaluated the model using:
     - Mean Absolute Error (MAE)

## 📈 Sample Results
- MAE: 1.48

## 🚀 Future Improvements
- Implement real-time predictions using Streamlit or Flask
- Experiment with feature selection and dimensionality reduction
- Compare performance with other regressors like Random Forest or Linear Regression
