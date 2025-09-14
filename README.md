1️⃣ Project Title
# Used Car Price Prediction

2️⃣ Project Description
This project aims to predict the price of used cars based on various attributes like brand, model, year, mileage, engine specifications, and more. 
The project explores data cleaning, feature engineering, and predictive modeling using machine learning algorithms such as Random Forest, CatBoost, and LightGBM.

3️⃣ Dataset
The dataset contains information about used cars including:
- `id`: Unique identifier
- `brand`: Car brand
- `model`: Car model
- `model_year`: Year of manufacture
- `milage`: Mileage in km
- `fuel_type`: Fuel type
- `engine`: Engine specifications
- `transmission`: Transmission type
- `ext_col`: Exterior color
- `int_col`: Interior color
- `accident`: Accident history
- `clean_title`: Indicates if the car has a clean title
- `price`: Target variable (price of the car)

4️⃣ Features and Preprocessing
- Handled missing values in categorical and numeric columns
- Extracted numeric values from engine specifications (horsepower, engine size, cylinders)
- Encoded categorical variables for modeling
- Removed or kept features based on correlation and feature importance analysis

5️⃣ Modeling
- **CatBoost Regressor**: Handles categorical variables natively, used for better predictive performance
- 
Evaluation metric: Root Mean Squared Error (RMSE)

# Dependencies
- Python >= 3.8
- pandas
- numpy
- scikit-learn
- catboost
- lightgbm
- matplotlib
- seaborn

