# Housing Price Prediction

## Project Overview
This project focuses on predicting housing prices based on various socioeconomic and geographical factors. Using multiple regression techniques, including Linear Regression and robust methods like RANSAC, this project aims to build an accurate model for predicting the median house value. Understanding the relationship between these factors and housing prices can help in real estate decision-making and market analysis.

## Project Structure
The project follows standard machine learning steps:
1. **Data Loading and Preprocessing**: Load the data, handle missing values, and prepare the dataset for modeling.
2. **Exploratory Data Analysis (EDA)**: Visualize relationships between features and the target variable (house value).
3. **Modeling**: Implement multiple regression models, including Linear Regression and RANSAC regression, to predict housing prices.
4. **Evaluation**: Evaluate and compare model performance to select the best approach for predicting house values.

## Dataset Description
The dataset is provided in CSV format and includes the following columns:

- **id**: Unique identifier for each entry
- **longitude**: Longitude coordinate of the house location
- **latitude**: Latitude coordinate of the house location
- **housing_median_age**: Median age of the housing in the area
- **total_rooms**: Total number of rooms in the area
- **total_bedrooms**: Total number of bedrooms in the area
- **population**: Population of the area
- **households**: Number of households in the area
- **median_income**: Median income of the area’s population
- **median_house_value**: Median house value in the area (target variable)

## Goals
- **Analyze** the data to understand the factors that influence housing prices.
- **Build and Compare** multiple regression models to predict median house values accurately.
- **Identify** key factors driving housing prices to inform real estate and economic insights.

## Models Used
The following regression models are implemented:
1. **Linear Regression**: A basic linear approach to modeling the relationship between input features and house prices.
2. **RANSAC Regression**: A robust regression technique that is less sensitive to outliers, providing more reliable predictions in certain cases.

## Methodology
1. **Data Preprocessing**: Clean the data by handling missing values, normalizing features as necessary, and preparing the data for analysis.
2. **Exploratory Analysis**: Use visualizations to explore trends and relationships, such as income vs. median house value, population density, and geographic location.
3. **Model Training**: Train both Linear Regression and RANSAC Regression models on the data.
4. **Model Evaluation**: Evaluate each model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²) to compare performance and robustness.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn (optional, for visualization)


