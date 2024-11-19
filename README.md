# Car-Price
Vincent - What Drives the Price of a Car? 
Here's the `README.md` file in English:

---

# Used Car Price Analysis Using the CRISP-DM Process

## Introduction
The goal of this project is to predict the factors that influence the price of used cars and provide recommendations to a used car dealership to optimize their inventory. We followed the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, which is a widely recognized framework for conducting data mining projects effectively.

## CRISP-DM Process

### 1. Business Understanding
The objective is to identify the variables that most impact the price of used cars and provide actionable insights on what consumers value most in a used car.

### 2. Data Understanding
We worked with a dataset containing information on 426,000 used cars. The following steps were taken:
- Initial data exploration to examine columns and data structure.
- Identification of missing values.
- Analysis of variable distributions.

### 3. Data Preparation
Data preparation steps included:
- Cleaning the data and handling missing values.
- Encoding categorical variables such as `manufacturer`, `fuel`, and `transmission`.
- Creating new features if needed to improve model performance.

### 4. Modeling
Multiple models were tested, including:
- Linear Regression.
- Random Forest.
- XGBoost.

These models were used to assess the importance of different variables and their impact on car prices.

### 5. Evaluation
Model evaluation was conducted using metrics such as **R-squared**, Mean Absolute Error (MAE), and Mean Squared Error (MSE). The results were interpreted to ensure their relevance and usefulness for the client.

### 6. Deployment
The findings of this analysis were summarized in a report with clear recommendations for the dealership.

## Action Plan for the Analysis

### Exploratory Data Analysis (EDA)
- Study the distribution of car prices.
- Analyze correlations between numerical variables (e.g., `year`, `odometer`) and price.
- Visualize trends based on `manufacturer`, `condition`, and other key variables.

### Data Preparation
- Clean missing values by filling or removing them.
- Encode categorical variables for model compatibility.

### Modeling
- Test regression models to predict car prices.
- Evaluate variable importance and fine-tune models for optimal performance.

## Results and Conclusions

### Distribution of Car Prices
Most cars are priced below $100,000, with a significant concentration under $20,000.

### Key Correlations
- **Year of Manufacture**: Shows a moderate positive correlation with price, indicating that newer cars tend to be more expensive.
- **Mileage (Odometer)**: Shows a negative correlation with price, suggesting that cars with higher mileage tend to be less valuable.

### Recommendations for the Client
- **Focus on newer cars**: Vehicles from recent years generally command higher prices.
- **Monitor mileage**: Cars with lower mileage sell at better prices.
- **Target key features**: Identify models and manufacturers that are most valued by consumers.

