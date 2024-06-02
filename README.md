# Dublin_Housing_Market_Prediction_ML

# Prediction of Property Prices of Dublin Housing Market using Ensemble Learning

## Project Overview

This project is a part of my MSc Research Project in Data Analytics at the National College of Ireland. The goal of this research is to predict the prices of residential properties in Dublin using data from the Property Services Regulatory Authority (PSRA) spanning from 2010 to 2021. The study explores the effectiveness of various machine learning models, including ensemble learning techniques, to identify the best model for predicting property prices.

## Data Source 
The data has been sourced from the Smart Dublin Open Data Repository. https://data.smartdublin.ie/dataset/dublin-residential-property-price-register


### Data Collection

The dataset was obtained from the PSRA, which includes information such as the date of sale, price, address, market price, VAT details, property description, and land area. The data covers residential property sales in Dublin from 2010 to 2021.

### Data Preprocessing

Data preprocessing involved cleaning the data to handle missing values and outliers, transforming categorical variables, and creating new features such as the year of sale and geographical coordinates. Techniques used include:

- Handling missing values and outliers
- Feature engineering to create new attributes
- Label encoding for categorical variables

### Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution and relationships between different variables. Visualizations such as bar charts, pie charts, and geographical maps were created to illustrate key patterns and insights.

### Model Building

The project explores various machine learning models to predict property prices, including:

- Multiple Linear Regression
- K Nearest Neighbours (KNN)
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

### Model Evaluation

The models were evaluated based on metrics such as R-Square, Root Mean Square Error (RMSE), and Mean Absolute Error (MAE). The Gradient Boosting Regressor was found to be the best-performing model with an R-Square value of 75.22%.

## Results

The Gradient Boosting Regressor outperformed other models in predicting property prices in Dublin, demonstrating the potential of ensemble learning techniques for real estate market analysis.

## Conclusion and Future Work

This research successfully identifies Gradient Boosting as the best technique for predicting property prices in Dublin. Future work could focus on deploying the model to provide a real-time property price prediction platform, enhancing data features, and applying the model to other regions.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


