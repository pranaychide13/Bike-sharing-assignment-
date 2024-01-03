
Bike Demand Prediction Project

This project aims to build a multiple linear regression model to predict the demand for shared bikes in the American market. The dataset used for this analysis contains information on various factors that may influence bike demand, such as weather conditions, holidays, and seasons.

Problem Statement

The bike-sharing provider BoomBikes has experienced a decline in revenues during the Covid-19 pandemic and wants to develop a strategy to accelerate its revenue once the lockdown measures are lifted. The company has partnered with a consulting firm to understand the factors that impact the demand for shared bikes and to identify significant variables in predicting bike demand.

Dataset

The dataset used for this project consists of daily bike demand data in the American market, along with several independent variables. These variables include year, holiday, season, weather conditions, and other factors that may affect bike rentals.

Business Goal

The primary goal of this analysis is to model the demand for shared bikes and identify the significant variables that contribute to the variations in demand. By understanding these factors, BoomBikes can adjust its business strategy to meet demand levels effectively and provide an exceptional customer experience.

Approach

The analysis begins with data exploration and preprocessing, including handling missing values, scaling numeric variables, and creating dummy variables for categorical variables. Feature selection is performed using the Recursive Feature Elimination (RFE) approach, and a multiple linear regression model is built using the selected features.

The model's performance is evaluated using various metrics such as root mean squared error (RMSE) and R-squared. Assumptions of linear regression, including linearity, homoscedasticity, and normality of residuals, are checked to ensure the validity of the model.

Results and Conclusions

Based on the analysis, the model demonstrates a strong performance in predicting bike demand, with a high R-squared value indicating that the selected variables can effectively explain the variations in demand. The top three features that significantly contribute to explaining the demand for shared bikes are `season_spring`, `season_summer`, `season_winter`, `weathersit_light_snow`, `weathersit_mist`, `holiday`

The insights gained from this analysis can help BoomBikes in formulating strategies to meet demand levels, optimizing inventory management, and improving customer satisfaction. The model also provides valuable information about the impact of weather conditions, holidays, and other factors on bike rentals.

Repository Structure

data: Contains the dataset used for the analysis.

notebooks: Jupyter notebooks used for data preprocessing, feature selection, model building, and evaluation.


README.md: This file providing an overview of the project.

Instructions

To run the Jupyter notebooks and reproduce the analysis, please follow these steps:

Clone the repository to your local machine.

Install the required dependencies by running pip install -r requirements.txt.

Open the Jupyter notebooks in the notebooks directory and execute the cells sequentially.

Contributors

pranay ramesh chide  
pranayrchide@gmail.com
