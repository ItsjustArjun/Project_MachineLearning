# Car Price Prediction - Machine Learning Project

## Project Overview
A Chinese automobile company aims to enter the US market by setting up a local manufacturing unit. To compete with established US and European car manufacturers, they need insights into the factors influencing car prices in the American market. This project models car prices based on various independent variables, helping the company understand pricing dynamics and optimize their strategies accordingly.

## Objectives
- Identify the significant factors affecting car prices in the US market.
- Develop regression models to predict car prices.
- Compare model performances using evaluation metrics.
- Perform feature importance analysis to determine key predictors.
- Optimize the best model through hyperparameter tuning.

## Dataset
The dataset contains a large set of car specifications, including:
- Technical attributes (engine size, horsepower, mileage, etc.)
- Brand and model information
- Pricing details


## Steps Implemented
### 1. Data Loading and Preprocessing
- Read the dataset using Pandas.
- Handle missing values.
- Encode categorical features using One-Hot Encoding.
- Scale numerical features using StandardScaler.
- Split data into training and testing sets.

### 2. Model Implementation
Implemented and trained the following regression models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Regressor**

### 3. Model Evaluation
Compared model performances using:
- **R² Score** (Explains variance in car prices)
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**

### 4. Feature Importance Analysis
- Identified top 10 significant features affecting car prices.
- Visualized feature importance using bar plots.

### 5. Hyperparameter Tuning
- Applied GridSearchCV to optimize hyperparameters for the best-performing model.
- Evaluated improvements in prediction accuracy.

## Best Model Selection
The model with the highest **R² Score** and lowest **MSE/MAE** was selected as the best predictor of car prices. Feature importance analysis provided further insights into key influencing factors.


## Results & Insights
- The best model provides prediction of car prices based on key influencing factors.

- Feature importance analysis helps manufacturers adjust design and marketing strategies.

- Hyperparameter tuning improves model performance and prediction accuracy.