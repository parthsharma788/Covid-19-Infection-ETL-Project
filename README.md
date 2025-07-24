# Covid-19-Infection-ETL-Project

### Project Description
The goal of this project is to illustrate Extract Transform Load (ETL) using Python and SQL. ETL is a process commonly done in computing, which takes raw data, cleans it and stores it for later use. The extraction phase targets and retrieves the data. Transform manipulates and cleans the data. Then load stores the data, typically in a data warehouse.

### Data
 https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases 

### Data Cleanup and Analysis

Developing a cleaning function in python that would select the data in the month of March 2020. This was applied to all datasets that I have.
All of the dates that have in the data sets we treated as values through the pd.melt function in Pandas.
Found a way of finding the daily increase with respect to each table. This value was converted from a float to an integer

### LOADING STEPS

I pushed the Pandas DataFrame to the local PostgreSQL server so I can retrieve and query the data in our Jupyter Notebook
Analysis / SQL Queries In this part, I want to find:

Top 5 countries with the most/least confirmed cases

Top 5 countries with the most/least deaths

Top 5 countries with the most/least recovered

Date in March with the most confirmed/deaths/recovered

👨‍💻 Author - Parth Sharma
📧 Email: Parthsharma2300@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/parth-sharma-8288a7283

⭐ If you found this helpful, consider giving it a star!
