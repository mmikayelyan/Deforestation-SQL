# Deforestation_SQL
SQL project that uses queries to study deforestation worldwide.

# Project Overview
In this project, I used SQL to explore data related to deforestation around the world in order to find which countries and regions around the world appear to have forests that have been shrinking in size, along with which countries and regions have the largest forest area, both in terms of amount and percent of total area.

# The Datasets
I used datasets provided by [The World Bank](https://www.worldbank.org/en/home), containing a global deforestation overview between 1990 and 2016. You can find the datasets in the data folder, which consist of three CSV files. 

# Outcomes
I've written SQL queries to provide the following information:
1. GLOBAL SITUATION
- What was the total forest area (in sq km) of the world in 1990? Please keep in mind that you can use the country record denoted as “World" in the region table.
- What was the total forest area (in sq km) of the world in 2016? Please keep in mind that you can use the country record in the table is denoted as “World.”
- What was the change (in sq km) in the forest area of the world from 1990 to 2016?
- What was the percent change in forest area of the world between 1990 and 2016?
- If you compare the amount of forest area lost between 1990 and 2016, to which country's total area in 2016 is it closest to?
2. REGIONAL OUTLOOK
- What was the percent forest of the entire world in 2016? Which region had the HIGHEST percent forest in 2016, and which had the LOWEST, to 2 decimal places?
- What was the percent forest of the entire world in 1990? Which region had the HIGHEST percent forest in 1990, and which had the LOWEST, to 2 decimal places?
- Based on the table you created, which regions of the world DECREASED in forest area from 1990 to 2016?
3. COUNTRY-LEVEL DETAIL
- Which 5 countries saw the largest amount decrease in forest area from 1990 to 2016? What was the difference in forest area for each?
- Which 5 countries saw the largest percent decrease in forest area from 1990 to 2016? What was the percent change to 2 decimal places for each?
- If countries were grouped by percent forestation in quartiles, which group had the most countries in it in 2016?
- List all of the countries that were in the 4th quartile (percent forest > 75%) in 2016.
- How many countries had a percent forestation higher than the United States in 2016?

As a result of the above, I have prepared a report to help understand the global deforestation overview between 1990 and 2016.

# Requirements

* Language: SQL

# Get started with the project

The first step is to download the DB and the DB.sqbpro files. The second step is to open the DB.sqbpro as a project in SQLite. Scripts for running the queries are also attached to the report.

# Author

 * [Manuk Mikayelyan](https://github.com/mmikayelyan) - Sole author for this program.
 
 # Acknowledgements

* [Udacity](https://udacity.com) - Udacity's Data Analyst Nanodegree program and [Masterschool](https://www.masterschool.com/) instructors were extremely helpful while I was pursuing this project.
* [devart](https://www.devart.com/dbforge/sql/sqlcomplete/self-join-in-sql-server.html) - Understanding SQL Server SELF JOIN By Practical Examples
* [w3schools](https://www.w3schools.com/sql/sql_join_self.asp) - SQL Self Join
* [dpriver](https://www.dpriver.com/pp/sqlformat.htm) - Instant SQL Formatter
