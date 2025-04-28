# cmsc408-fa2024-hw9-template

## Overview

- This assignment involves analyzing World Bank development indicators using SQL queries to explore population data across different regions and time periods. The work focuses on understanding female population percentages globally and by region from 1960 to 2020.
Files Included

1.  SQL Query Scripts: Contains all the SQL queries used for data analysis

2.  Results: Output tables showing the analysis results

## Key Tasks Completed
- Data Preparation

1. Created local copies of WDI tables in a personal schema

2. Verified table structures and data availability

3. Built a stacked version of the data for easier analysis


## Technical Skills Demonstrated

1. SQL query construction with complex joins

2. Data aggregation and percentage calculations

3. Pivoting operations with CASE statements

4. Handling of NULL values and division by zero

5. Formatting output for readability


## Files 
- Project files are stored in the following directory:
/homework-6/
    ├── README.md
    ├── _quarto.yml
    ├── my-ddl.sql
    ├── report.qmd
    ├── report.html
    ├── etc...

## PreReqs

To have this up and running you'll need the following:

- VSCode
- Quarto
- Pipx
- Jupyter
- Python/ Python 3 
- Poetry

If anything is missing, follow this link for the setup guide: <https://vcu-ssg.github.io/ssg-quarto-python-setup/finalsteps.html>


## Final Touches

Once you've completed everything, just run either:
- poetry run quarto render report.qmd 
- quarto render report.qmd

Your html file should be generated and you'll be able to enjoy your project. Have Fun!
