# House Price Prediction

This project focuses on building a machine learning model to predict house prices based on various features such as location, size, number of rooms, and other relevant attributes.

## Project Overview

The workflow followed in this project includes:
- Data loading and inspection
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering (including one-hot encoding for categorical variables)
- Model training using multiple regression algorithms
- Model evaluation and comparison

The goal is to achieve accurate price predictions while keeping the model generalizable to unseen data.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Machine Learning Models Implemented

- Linear Regression  
- Lasso Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- K-Nearest Neighbors Regressor  
- XGBoost Regressor  

Hyperparameter tuning is performed using GridSearchCV where applicable.

## Model Evaluation

Model performance is evaluated using:
- Train-test split
- Cross-validation
- Mean Absolute Percentage Error (MAPE)

MAPE is used to understand the average prediction error in percentage terms.

## Dataset

The dataset contains house-related attributes and a target variable representing house prices.  
Categorical features such as location are transformed using one-hot encoding.

## How to Run the Project

1. Clone the repository
2. Install the required dependencies
3. Open the Jupyter Notebook
4. Run the cells in order to reproduce the results

## Results

Among the tested models, ensemble-based methods such as Random Forest and XGBoost provided better prediction accuracy compared to basic regression models.

## Future Improvements

- Use more advanced feature selection techniques
- Try deep learning-based regression models
- Improve handling of outliers
- Deploy the model using a web framework

## Author

Rakshith S
