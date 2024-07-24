# Housing Market Analysis and Prediction

This project involves analyzing various economic indicators and their impact on the Housing Price Index using a Linear Regression model. Below are the steps undertaken in this project:

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
