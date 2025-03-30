# Vehicle Price Prediction

# Overview
This project aims to build a machine learning model that predicts vehicle prices based on various features like make, model, year, mileage, and more. The dataset consists of vehicle specifications and pricing data, and the goal is to provide an accurate prediction model.

# Features
- **Data Cleaning & Preprocessing**: Handling missing values, outliers, and categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualizing key insights using graphs.
- **Feature Engineering**: Extracting useful features from available data.
- **Model Training & Optimization**:
  - Random Forest
  - XGBoost
  - Ensemble Learning (Combining multiple models)
  - Hyperparameter tuning with GridSearchCV
  - Cross-validation (K-Fold)
- **Model Evaluation**: Comparing models using metrics like RMSE, MAE, and R2-score.
- **Feature Importance Analysis**: Understanding which features influence price predictions the most.
- **Logging with MLflow**: Tracking model performance and experiment results.

# Dataset
- **Source**: Provided dataset
- **Columns**:
  - `name`: Full name of the vehicle, including make, model, and trim.
  - `description`: Brief description of key features.
  - `make`: Manufacturer of the vehicle (e.g., Ford, Toyota, BMW).
  - `model`: Specific model name.
  - `year`: Manufacturing year.
  - `price`: Price of the vehicle (target variable).
  - `engine`: Engine details (type, specifications).
  - `cylinders`: Number of cylinders in the engine.
  - `fuel`: Type of fuel used (Gasoline, Diesel, Electric, etc.).
  - `mileage`: Vehicle mileage.
  - `transmission`: Transmission type (Automatic, Manual).
  - `trim`: Trim level indicating different feature sets.
  - `body`: Body style (SUV, Sedan, Pickup Truck, etc.).
  - `doors`: Number of doors.
  - `exterior_color`: Exterior color.
  - `interior_color`: Interior color.
  - `drivetrain`: Drivetrain type (All-wheel Drive, Front-wheel Drive, etc.).

# Installation
### Prerequisites
Ensure you have Python and the required libraries installed.
```bash
pip install pandas numpy scikit-learn xgboost matplotlib seaborn optuna mlflow
```

### Running the Project
1. Clone the repository:
```bash
git clone https://github.com/Revati07/Vehicle-Price-Prediction.git
```
2. Navigate to the project folder:
```bash
cd Vehicle-Price-Prediction
```
3. Run the Jupyter Notebook:
```bash
jupyter notebook
```
4. Open `Vehicle_Price_Prediction.ipynb` and execute the cells.

# Results
- **Best Model**: Random Forest/XGBoost (after hyperparameter tuning)
- **Performance Metrics**:
  - RMSE: XXX
  - MAE: XXX
  - R2-score: XXX
- **Feature Importance**: Identified most influential features affecting price prediction.

# Future Enhancements
- Improve model accuracy with deep learning (Neural Networks).
- Deploy the model as a web application (Flask, FastAPI, or Streamlit).
- Integrate more real-world data for better generalization.

# Author
- **Revati Mahajan**  
  [LinkedIn](https://www.linkedin.com/in/revatimahajan) | [GitHub](https://github.com/Revati07)

