# sql_lecture

--TABLE CREATION
-- Create a table with an id, a text column, and a numeric column.

--ROW CREATION
-- Insert two rows of data into your table.

--SELECT BASICS
-- Retrieve your two rows of data.

-- Filter the data to one row with a where clause.

-- Take off the where clause and select all of the data again.
-- Then order the data by one of the fields.

-- Flip the order.

-- Limit the data to one row.

--SELECT BASICS WITH REAL DATA
-- Now drop your table with the following command:
-- DROP TABLE table_name;

-- Import the city table by copying the statements from city.sql.

-- Select all of the cities with populations less than 1,000,000.

-- Further filter the results with extra conditions.

-- Select all of the cities from the United States.

-- Select all of the cities from North America.

-- Select all of the cities that end with 'town' or 'ton'.

-- Select the cities whose country codes contain a 'Z'.

-- NEED MORE PRACTICE?
-- Try importing the country database and selecting different rows and columns.

-- CALCULATIONS AND AGGREGATIONS

-- Copy the statements from country.sql and run them in chinook.

-- Calculate the population density of each country.

-- Which nation gained its independence first?

-- Count the number of nations with 'stan' in their name (or 'Guinea' or 'land').

-- Count the number of countries in Africa.

-- Count the number of nations which gained their independence after 1960.

-- Find the average life expectancy for European and Asian nations.

--MORE PRACTICE
-- Copy the countrylanguage table into chinook.

-- How many distinct languages does this table contain?

-- Which nation has the most recorded languages?

-- Which languages are spoken in the most nations?

-- Which language is most creolized?

--ONE FOR THE MONEY
-- Drop the tables above if you wish:
/_ drop table if exists country;
drop table if exists city;
drop table if exists countrylanguage;
_/
-- Copy the computer_jobs table into chinook, and do a little job research.

-- Which state, on average, pays computer workers the most?

-- Which field of computer science pays the most on average?

-- Which field has the most number of jobs?

-- How much do web developers make in your state?

-- Which state employs the most web developers?
