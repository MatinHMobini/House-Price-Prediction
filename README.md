# House Price Prediction Project 🏡

This project focuses on building a machine learning model to predict house prices using various features such as location, population, and other relevant variables. The project involves data preprocessing, feature engineering, model training, evaluation, and visualization of results.

## Project Overview

The project aims to develop a predictive model that estimates housing prices based on a dataset that contains housing features like:

- **Latitude** and **Longitude**: Geographical coordinates.
- **Median Income**: A key predictor for housing prices.
- **House Age**: The age of houses in the area.
- **Number of Rooms**: Total rooms in a house.
- **Population**: The population of the area.
- **Proximity to Ocean**: Categorical feature indicating proximity to the ocean.

## Key Features and Workflow

1. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables (e.g., `ocean_proximity`).
   - Scaled the numerical features using `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**:
   - Created scatterplots to visualize geographic distribution of house prices.
   - Generated histograms for a quick overview of feature distributions.
   - Displayed heatmaps to understand correlations between different features.

3. **Modeling**:
   - **Linear Regression** and **Random Forest** were used for prediction.
   - Cross-validation was performed to ensure model reliability.

4. **Evaluation**:
   - **Root Mean Squared Error (RMSE)** was calculated to evaluate model performance.

## Results

- **Random Forest** model outperformed **Linear Regression** with a lower RMSE.
- The feature engineering and scaling improved model accuracy.
- Visualizations provided insights into key factors affecting house prices.

## Requirements

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## How to Run

1. Clone the repository.
2. Install required dependencies.
3. Open the `House_Prediction.ipynb` notebook in Jupyter and run all cells to train and evaluate the model.

## Visualizations

- **Heatmap of Feature Correlations**:
  ![Heatmap](./heatmap.png)
  
- **Geographical Distribution of House Prices**:
  ![Scatter Plot](./scatter.png)
