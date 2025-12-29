Project Title:
House Price Prediction Using Multiple Linear Regression

Objective:
To predict house prices based on house area, number of bedrooms, and number of bathrooms using a machine learning regression model.

Dataset:
Source: Kaggle – House Prices: Advanced Regression Techniques
File used: house_price_dataset.csv
Target Variable: SalePrice

Features Used:
- GrLivArea (Living area in square feet)
- BedroomAbvGr (Number of bedrooms)
- FullBath (Number of bathrooms)

Methodology:
1. Loaded and explored the dataset using pandas
2. Selected relevant features and target variable
3. Split the dataset into training (80%) and testing (20%) sets
4. Trained a Multiple Linear Regression model
5. Evaluated the model using MAE, RMSE, and R² score
6. Added user input functionality to predict house prices

Model Evaluation Results:
- MAE: ~35,788
- RMSE: ~52,975
- R² Score: ~0.63

Conclusion:
The project demonstrates how multiple linear regression can be used to predict house prices. The model provides reasonable accuracy and can be further improved with additional features and advanced techniques.
