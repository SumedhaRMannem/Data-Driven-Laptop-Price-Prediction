# Data-Driven Laptop Price Prediction 

##  Project Overview
This project explores various machine learning techniques to predict laptop prices based on key hardware specifications. Using historical pricing data, we develop and evaluate multiple regression models to provide accurate price predictions, helping both buyers and sellers make informed decisions. 

##  Objective
- **Enhance market transparency** by leveraging AI-driven price predictions.
- **Assist buyers** in finding the best-priced laptops based on specifications.
- **Help sellers** optimize pricing strategies based on market trends.

##  Dataset
The dataset, sourced from Kaggle, contains laptop specifications such as:
- `Company`
- `TypeName`
- `ScreenResolution`
- `CPU`
- `RAM`
- `Memory`
- `GPU`
- `Operating System`
- `Weight`
- `Price`
- `HDD`, `SSD`, `GPU Brand`, etc.

## ⚖️ Methodology
The project follows a structured machine learning pipeline:

### 1. **Data Preprocessing**
- Handling missing values, removing duplicates, and transforming categorical data.
- Feature engineering (creating binary indicators for touchscreen, IPS panels, etc.).
- Extracting screen resolution and calculating Pixels Per Inch (PPI).

### 2. **Exploratory Data Analysis (EDA)**
- Distribution analysis of laptop prices across brands and features.
- Correlation analysis to determine key price influencers.

### 3. **Machine Learning Models**
Implemented and compared multiple regression models:
- ✅ **Linear Regression**
- ✅ **Ridge Regression**
- ✅ **Decision Tree Regression**
- ✅ **Support Vector Regression (SVR)**
- ✅ **Random Forest Regression**
- ✅ **Gradient Boosting Regression**
- ✅ **XGBoost Regression**
- ✅ **Stacking Regressor**

#### **Best Model:** \U0001F4C8 *Random Forest Regression* achieved the highest accuracy with an **R² score of 0.886** and lowest **Mean Absolute Error (MAE) of 0.158**.

### 4. **Price Prediction**
- Predicting laptop prices based on user-defined specifications.
- Generating price insights using the best-performing model.

##  Key Findings
- The **Random Forest model** performed the best, explaining **88.6%** of variance in laptop prices.
- **RAM, CPU, and Screen Resolution** were identified as the most significant price-influencing features.
- The model provides **competitive price predictions**, making it useful for both consumers and retailers.

##  Tech Stack
- **Python** \U0001F40D
- **Pandas, NumPy** for data processing
- **Scikit-learn, XGBoost** for machine learning
- **Matplotlib, Seaborn** for data visualization
- **Jupyter Notebook** for experimentation

##  Future Improvements
- Expand dataset with more laptop listings.
- Implement deep learning-based price prediction models.
- Build a web interface to allow users to input specifications and get price predictions.

---

###  Contributors
**Sumedha Reddy Mannem**  
**Course:** Machine Learning CSCI_6364_80  
**Instructor:** David W. Trott, Ph.D. 

---