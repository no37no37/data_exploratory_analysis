# SQL Data Exploration Project
The project focuses on analyzing COVID-19 data and preparing it for visualization in Tableau. 
It includes data cleaning tasks, data importing, and SQL queries to extract insights from the dataset.

The project explores SQL and its applications in data analysis. 
The objective is to perform extensive data exploration and cleaning using SQL and visualize the processed data in Tableau. 
The project is designed to be beginner-friendly, allowing users to come up with their own queries and insights.

# Dataset
The dataset covers data from early 2020 onwards, and ensured that all relevant information is included. 
In this SQL queries, primary focus is on total cases, new cases, total deaths, new deaths, total vaccinations, people vaccinated, and population.

# Importing Datasets into SQL
1. Downloaded the dataset in Excel format.
2. Import the Excel files into the "Portfolio Project" database.
3. Create two tables named "Covid Deaths" and "Covid Vaccinations" and imported the respective datasets.

# Data Exploration
- Before analyzing the data, the correctness of the dataset is verified through a quick query. All columns from the "Portfolio Project" table are selected and ordered appropriately. 
- Specific columns such as location, date, total cases, new cases, total deaths, and population are focused on. Percentages, such as the percentage of people who died among the infected, 
  are calculated to gain insights into the severity of the disease across regions and timeframes.
- Total cases are compared to population and other percentage-based metrics are analyzed. Data can be filtered by country to explore region-specific statistics.
- Countries with the highest infection rates relative to their population are identified, and the death count in those countries is analyzed. By grouping the data based on population 
  and location, valuable information about the impact of COVID-19 worldwide is obtained.
- The death percentage globally is examined by excluding location and continent. This analysis provides insights into the overall severity of the disease across all countries.
- To enhance the analysis, the "Covid Deaths" and "Covid Vaccinations" tables are joined based on location and date. This allows for a comparison of the total population with 
  the number of vaccinations administered. A temporary table is created for efficient calculations.
