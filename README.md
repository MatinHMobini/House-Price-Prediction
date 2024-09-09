# 🏡 House Price Prediction Project

## Overview
This project involves predicting house prices based on a housing dataset that includes a variety of features such as the geographical location, total rooms, population, and proximity to water. The dataset has been sourced from **Kaggle**. The primary goal is to apply regression models to predict the median house value, visualize important relationships in the dataset, and analyze key factors influencing house prices.

## 🛠️ Features & Methods
1. **Data Preprocessing**: 
   - Handling missing values.
   - Encoding categorical variables (e.g., "ocean_proximity").
   - Feature scaling using **StandardScaler** to normalize features for machine learning models.
  
2. **Exploratory Data Analysis**:
   - Visualization of important features to understand correlations between house prices and various factors like proximity to the ocean, number of rooms, and household size.
  
3. **📊 Machine Learning Models**:
   - **Linear Regression**: A basic model used as a benchmark for predictions.
   - **Random Forest**: The final model used to predict house prices due to its ability to generalize well and avoid overfitting.
  
4. **Model Evaluation**:
   - **Root Mean Squared Error (RMSE)** was used to evaluate the performance of the models.
   - Cross-validation techniques were applied to ensure robust evaluation.

5. **GridSearchCV Optimization**:
   - Applied **GridSearchCV** to find the best hyperparameters for the **Random Forest model**, which resulted in a highest score of **0.8110646277869668** using a 5-fold cross-validation technique.

## 📈 Visualizations

### 1. Scatterplot: House Prices vs. Proximity to Water
A scatterplot showing house prices based on the latitude and longitude coordinates. The color of the points represents the median house value, with houses closer to the ocean generally being more expensive.

![Scatterplot Example](https://github.com/user-attachments/assets/13e08d9d-ca5b-416a-b35b-c8c326e74b7d)

### 2. Correlation Heatmap
A heatmap showing the correlations between house prices and various features in the dataset, such as total rooms, population, and proximity to the ocean. This helps in understanding the strength of the relationships between different variables and house prices.

![Heatmap Example](https://github.com/user-attachments/assets/d39c43bd-c728-4d4c-a5a9-31199ba7c9f9)

### 3. Histograms of Key Features
Histograms provide an overview of the distributions of several key variables in the dataset, such as the total number of rooms, population, and median income.

![Histograms Example](https://github.com/user-attachments/assets/74672e0b-f16d-4553-8d50-19301044643a)

This gives insights into the spread and central tendencies of the various features used in the machine learning models.

## 💡 Results

After fitting various models, the **Random Forest model** produced the most accurate predictions with an RMSE of **50,414**. 

## Conclusions

- Houses closer to the ocean tend to have higher prices, as shown in the scatter plot of latitude vs. longitude.
- The feature **median_income** had the strongest correlation with house prices.
- Other features such as the total number of rooms and the number of households also had moderate correlations with the house prices.
- Random Forest proved to be the most reliable model for this prediction task, producing realistic RMSE scores and handling the variability in the dataset effectively.

## 🚀 Languages/Technologies Used
- **Python**: For data manipulation and building machine learning models.
- **Pandas**: For data preprocessing and manipulation.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For implementing machine learning algorithms, including Linear Regression, Random Forest, and **GridSearchCV** for hyperparameter tuning.
- **Matplotlib** & **Seaborn**: For data visualization and plotting graphs.
- **Jupyter Notebook**: For interactive coding and experimentation.
- The data is from https://www.kaggle.com/datasets/camnugent/california-housing-prices 

---

Thank you for viewing!
