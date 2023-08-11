# Hotels-analysis-python-power-Bi-
![Screenshot 2023-08-11 212412](https://github.com/NoorhanHamed/Hotels-analysis-python-/assets/113361240/f13e067b-65f4-4c8a-9700-1440588d7f01)














As a data analyst dealing with large amounts of data, the task of preprocessing and cleaning the data is 
crucial and often time-consuming.
After completing the data preprocessing and cleaning steps, the next phase is analysis. 
In this phase, you can apply various analytical techniques to derive meaningful insights and answer key 
questions relevant to the business.
# Provide your answers to the below questions and add any metrics that you find important
- Hotels with highest profitability and losses.
- Countries with highest profitability and losses.
- Total Sales per country.
- Cluster the data by room nights into three categories: high demand, mid demand, and low demand 
in a new column and identify the distribution.Finally, the visualization step is crucial for presenting the findings and insights in a clear




#### Technical Documentation for the Code

The code is written in Python and consists of the following major parts:

#### Importing Libraries
The required libraries are imported in this section. The libraries used in this code are numpy, pandas, seaborn, geopy, and geopandas.

#### Reading the Dataset
The dataset is read from an Excel file using the pandas library and stored in a pandas DataFrame.

#### Preprocessing
This section includes various preprocessing steps such as converting the Date column to datetime datatype, creating separate columns for year and month, checking for duplicate values, dropping duplicates, and creating a profit column by subtracting the cost from the sale column. It also includes extracting the country name from the hotel name using geopy and geopandas libraries.

#### Analysis
This section includes univariate and bivariate analysis of the dataset using seaborn library. It includes analyzing the Roomnights, Sale, Cost, and Profit columns using various statistical measures and visualizations. It also includes detecting outliers using the datasist library.

#### Answers to Questions and Metrics
This section answers the questions related to the highest profitability and losses for hotels and countries, the total sales per country, and clustering the data by room nights into three categories: high demand, mid demand, and low demand. It includes grouping the data by hotel name and country name using pandas and calculating the sum of the profit and sale columns. It also includes creating a new column for room demand based on the number of room nights.

#### Saving Modified Dataset
The modified version of the dataset is saved in an Excel file using pandas.


## Dashboard using power BI 

