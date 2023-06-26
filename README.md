# Data-Analysis-Projects
## MySQL Covide Analysis:

This code explores COVID-19 data from the Our World in Data website.
The code uses a variety of SQL techniques, including joins, CTEs, temp tables, windows functions, aggregate functions, creating views, and converting data types.
The code first selects all data from the CovidDeaths table where the continent is not null. This ensures that only data from countries is included in the analysis. The code then calculates the following metrics:

Total cases
Total deaths
Total cases vs. total deaths (death percentage)
Total cases vs. population (percentage of the population infected)
Countries with the highest infection rate compared to the population
Countries with the highest death count per population
Continents with the highest death count per population
Global numbers (total cases, total deaths, death percentage)
Total population vs. vaccinations (percentage of the population that has received at least one Covid vaccine)
The code then uses a CTE, a temp table, and a view to store the data for later visualizations.

This code is a good example of how SQL can be used to explore and analyze large datasets. The code is well-organized and easy to follow, and it uses a variety of SQL techniques to extract insights from the data.
