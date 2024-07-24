# Housing Market Analysis and Prediction

This project involves analyzing various economic indicators and their impact on the Housing Price Index using a Linear Regression model. Below are the steps undertaken in this project:

### Objective

Identify publicly available data for key factors that influence U.S. home prices nationally and develop a data science model to explain how these factors have impacted home prices over the past 20 years.

### Project Aim

Create a data science model to predict U.S. home prices based on significant economic factors over the last two decades.

### Steps

#### Data Collection
- **Data Source:** Utilize the S&P Case-Shiller Home Price Index as a proxy for home prices, sourced from the Federal Reserve Economic Data (FRED) website.
- **Key Factors:** Gather publicly available data on factors influencing home prices nationally, including Per Capita GDP, Consumer Price Index (CPI), Construction Material Costs, Median Income, Subsidies, and Population Demographics.

#### Data Cleaning and Processing
- Clean and process the data by addressing missing values, converting date formats, and handling outliers.

#### Exploratory Data Analysis (EDA)
- Conduct EDA to understand the distribution of variables, identify correlations, and visualize trends over time.

#### Model Selection
- Explore various regression models, including Linear Regression, ElasticNet, Random Forest, Gradient Boosting, Support Vector Regression (SVR), and XGBoost.

#### Model Training and Evaluation
- Train each model using a subset of the data and evaluate performance using metrics such as Mean Squared Error (MSE) and R-squared.

#### Feature Importance
- Analyze feature importance for models like Random Forest, XGBoost, and Gradient Boosting to understand the factors influencing home prices.

#### Model Comparison
- Compare the performance of different models based on metrics such as Mean Squared Error (MSE) and R-squared to select the best-performing model for accurate predictions and insights into the factors influencing home prices over the last 20 years.

#### Visualization
- Create visualizations to illustrate the relationships between actual and predicted home prices for each model.
- Visualize the importance of different features or coefficients in influencing home prices.

### Conclusion
- Identify the most effective model based on low MSE and high R-squared values.
- Draw conclusions about the key factors that have historically influenced U.S. home prices.

### Overall Implication
The project contributes to understanding the key factors influencing U.S. home prices over the last 20 years and provides a foundation for building robust predictive models in the real estate domain.

### Results
The project focuses on understanding and predicting patterns rather than merely describing historical trends or providing actionable recommendations.

## Data Sources
We have downloaded the following datasets from the Federal Reserve Economic Data (FRED):

1. [Housing Price Index](https://fred.stlouisfed.org/series/CSUSHPISA) - Target variable.
2. [Household Income](https://fred.stlouisfed.org/series/MEHOINUSA672N) - `household` column.
3. [Consumer Price Index](https://fred.stlouisfed.org/series/MEDCPIM158SFRBCLE) - `consumer_price_index` column.
4. [New House Supply](https://fred.stlouisfed.org/series/MSACSR) - `new_house_supply` column.
5. [Unemployment Rate](https://fred.stlouisfed.org/series/UNRATE) - `unemployment_rate` column.
6. [Working Age Population](https://fred.stlouisfed.org/series/LFWA64TTUSM647S) - `working_age_population` column.
7. [Interest Rate](https://fred.stlouisfed.org/series/MORTGAGE30US) - `interest_rate` column.
8. [Per Capita GDP](https://fred.stlouisfed.org/series/A939RX0Q048SBEA) - `per_capita_GDP` column.
9. [Total Number of Households](https://fred.stlouisfed.org/series/TTLHH) - `total_number_of_households` column.
10. [Housing Subsidy](https://fred.stlouisfed.org/series/L312051A027NBEA) - `housing_subsidy` column.

## Steps to Reproduce the Analysis

1. **Download Data**: Download the data from the above sources and upload the files into Google Colab.

2. **Rename Columns**: Rename columns for easier comprehension.

3. **Merge DataFrames**:
   - Merge monthly data columns into a single DataFrame.
   - Merge annual data columns into a separate DataFrame.
   - Merge both monthly and annual DataFrames.

4. **Clean Dataset**: Handle NaN values and clean the dataset.

5. **Generate CSV**: Export the cleaned dataset to a CSV file for further preparation.

6. **Exploratory Data Analysis (EDA)**: Perform EDA and data visualization to understand the dataset better.

7. **Model Building**: Develop a Linear Regression model to predict the Housing Price Index.

## Conclusion

Summarize the findings and implications of the analysis and model predictions.

This README provides an overview of the steps taken in the project. Detailed explanations and code implementation can be found in the corresponding notebooks and scripts in this repository.
