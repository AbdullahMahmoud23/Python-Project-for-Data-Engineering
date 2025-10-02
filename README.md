# Python Project for Data Engineering
# ETL pipeline

## Introduction
In this practice project, you will use the skills acquired through the course and *create a complete ETL pipeline* for accessing data from a website and processing it to meet the requirements.

## Project Scenario
An international firm that is looking to expand its business in different countries across the world has recruited you. You have been hired as a junior Data Engineer and are tasked with creating an automated script that can extract the list of all countries in order of their GDPs in billion USDs (rounded to 2 decimal places), as logged by the International Monetary Fund (IMF). Since IMF releases this evaluation twice a year, this code will be used by the organization to extract the information as it is updated.

You can find the required data on this webpage.

The required information needs to be made accessible as a JSON file 'Countries_by_GDP.json' as well as a table 'Countries_by_GDP' in a database file 'World_Economies.db' with attributes 'Country' and 'GDP_USD_billion.'

Your boss wants you to demonstrate the success of this code by running a query on the database table to display only the entries with more than a 100 billion USD economy. Also, log the entire process of execution in a file named 'etl_project_log.txt'.

You must create a Python code 'etl_project_gdp.py' that performs all the required tasks.

## Objectives
You have to complete the following tasks for this project

1. Write a data extraction function to retrieve the relevant information from the required URL.

2. Transform the available GDP information into 'Billion USD' from 'Million USD'.

3. Load the transformed information into the required CSV file and as a database file.

4. Run the required query on the database.

5. Log the progress of the code with appropriate timestamps.

## Initial setup
Before you start building the code, you need to install the required libraries for it.

The libraries needed for the code are as follows:

1. **requests** - The library used for accessing the information from the URL.

2. **bs4** - The library containing the BeautifulSoup function used for webscraping.

3. **pandas** - The library used for processing the extracted data, storing it to required formats and communicating with the databases.

4. **sqlite3** - The library required to create a database server connection.

5. **numpy** - The library required for the mathematical rounding operation as required in the objectives.

6. **datetime** - The library containing the function datetime used for extracting the timestamp for logging purposes.


## Conclusion

In this project, you performed complex Extract, Transform, and Loading operations on real world data. By now, you should be able to:

1. Extract relevant information from websites using Webscraping and requests API.

2. Transform the data to a required format.

3. Load the processed data to a local file or as a database table.

4. Query the database table using Python.

5. Create detailed logs of all operations conducted.
