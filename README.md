# COVID Data Exploration Project
This project involves deep data exploration of global COVID-19 cases and vaccinations using SQL. It demonstrates data cleaning, transformation, and analysis techniques on real-world datasets from Our World in Data.

📂 Dataset
CovidDeaths.xlsx: Daily reported cases, deaths, and population by location.

CovidVaccinations.xlsx: Daily vaccination data by location.

Source: Our World in Data

🧠 Skills Demonstrated
SQL Joins

CTEs (Common Table Expressions)

Temp Tables

Aggregate & Window Functions

Data Type Conversion

Creating Views

🔍 Key Insights Extracted
Total Cases vs. Total Deaths
→ Calculated the death percentage to show the fatality rate per country.

Total Cases vs. Population
→ Analyzed the percentage of population infected by country.

Highest Infection Rates
→ Ranked countries by infection rate relative to population.

Highest Death Counts
→ Identified countries and continents with the most COVID-19 deaths.

Vaccination Progress
→ Used window functions and CTEs to calculate rolling vaccination stats.

Global Summary
→ Aggregated new cases, new deaths, and death percentages globally.

📊 Sample Queries
Countries with the highest percentage of population infected.

Rolling count of vaccinated people over time.

Continent-level death analysis.

Global death percentage trends.

🏗️ View Created
sql
Copy
Edit
Create View PercentPopulationVaccinated as
...
This view helps visualize the vaccination progress over time.

🚀 How to Use
Run the SQL scripts in a database environment (like SQL Server or MySQL with necessary adjustments). Load the data from the Excel files into two tables: CovidDeaths and CovidVaccinations.
