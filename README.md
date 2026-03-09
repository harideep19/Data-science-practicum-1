Airbnb Rental Price Prediction using Machine Learning
Introduction
The main objective of the project is to build a machine learning model which can predict the Airbnb rental prices based on the historical data. The project follows an systematic data science process such as data preprocessing, exploratory data analysis, Feature engineering, model training and model comparison.
Workflow
Here the Airbnb prices vary on many independent factors like location, number of rooms, availability and revies, I treated this problem as regression problem since the target variable is price which is continuous. Then implemented multiple machine learning models after training multiple models, compared their performances with evaluation metrics such as R2 , MAE and MRSE to check the model which is performing well.

Models Used

Linear Regression (baseline)
Ridge Regression
Lasso Regression
Decision Tree
Random Forest
Gradient Boosting
Support Vector Regressor

Evaluation metrics 
R² score
MAE
RMSE


Results
After comparing all models, Gradient Boosting performed the best.
R² ≈ 0.55
MAE ≈ 39
RMSE ≈ 55



Tools Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

This project finally developed a machine learning model which will predict the rental prices of Airbnb by using the characteristics like room type, amenities and host information. After following a systematic data science process such as data preprocessing, feature engineering and testing the multiple regression models, gradient boosting model produced best performance which archived an R2 of 0.55 variation. The results show that machine learning will identify the patterns and supports the data driven decisions which helps the Airbnb Hosts to set the listing prices.


How to Run the Project

To run this project on your local system, follow these steps:

1. Clone the repository

git clone https://github.com/harideep19/Data-science-practicum-1.git

2. open Airbnb prices file

3. Install required libraries

pip install pandas numpy scikit-learn matplotlib seaborn 

4. Run the  all cells to see preprocessing, model training, and results.


