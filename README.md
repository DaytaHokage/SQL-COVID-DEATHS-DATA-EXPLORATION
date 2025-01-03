# SQL-COVID-DEATHS-DATA-EXPLORATION

## Overview
This project explores Covid-19 data using SQL. It demonstrates various SQL skills and techniques, such as joins, Common Table Expressions (CTEs), temporary tables, window functions, aggregate functions, views, and data type conversions. The dataset includes information on Covid-19 cases, deaths, and vaccinations, offering insights into infection rates, death percentages, and vaccination progress.

## Key Features
- **Data Filtering:** Extracting relevant data using conditions and sorting.
- **Comparative Analysis:**
  - Total cases vs. total deaths to calculate death percentages.
  - Total cases vs. population to determine infection rates.
- **Ranking and Aggregation:**
  - Identifying countries and continents with the highest infection and death rates.
  - Global summary of total cases and deaths, along with death percentages.
- **Vaccination Analysis:**
  - Exploring vaccination progress across locations and continents.
  - Calculating the percentage of the population vaccinated using CTEs and temporary tables.
- **Data Preparation for Visualization:** Creating a SQL view for seamless integration with visualization tools.

## SQL Concepts Used
- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Views
- Data Type Conversion

## Dataset
1. **CovidDeaths:** Contains information about Covid-19 cases, deaths, and population data.
2. **CovidVaccinations:** Includes data on Covid-19 vaccination progress.

## Queries and Insights
1. **Data Exploration:**
   - Basic overview of the dataset.
   - Filtering to exclude irrelevant rows.
2. **Analysis of Covid-19 Impact:**
   - Death percentage among confirmed cases.
   - Infection percentage relative to population.
3. **Geographical Insights:**
   - Countries and continents with the highest infection and death rates.
4. **Vaccination Progress:**
   - Rolling total of vaccinated individuals by location.
   - Percentage of population vaccinated.
5. **Global Metrics:**
   - Summary of global cases, deaths, and death percentage.

## How to Use
1. Clone this repository to your local machine.
2. Import the `PortfolioProject` database into your SQL environment.
3. Run the SQL queries sequentially to explore the data and generate insights.
4. Utilize the `PercentPopulationVaccinated` view for visualization and further analysis.

## Future Work
- Integrating the SQL view with visualization tools like Power BI or Tableau for better representation.
- Expanding the analysis to include time-series trends and predictions.

## License
This project is open-source and available under the MIT License.

