#Linear Regression on Szeged weather Dataset

#Aim

To build a Linear Regression model to predict **Temperature (°C)** using **Apparent Temperature (°C)** and evaluate the model using R² score.

#Dataset

https://www.kaggle.com/datasets/budincsevity/szeged-weather

#Technologies Used

Python
Numpy
Pandas
Scikit-learn
Matplotlib

## Methodology

1. Downloaded dataset using KaggleHub
2. Loaded and explored the dataset
3. Selected:
   - Feature: Apparent Temperature (°C)
   - Target: Temperature (°C)
4. Split data into training and testing sets (80:20)
5. Trained a Linear Regression model
6. Evaluated model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
7. Visualized actual vs predicted values

#Results

MAE: 0.8819966667734273
MSE: 1.3368092329158878
R² Score: 0.9854945773998551
