# DnD Monster Portfolio
This is a side project that I work on at a leisurely pace. I am including it in my portfolio because its fun to work on, and it covers a wide skillset that every data analyst should be able to demonstrate.

## Objectives
1. Show knowledge of io operations by performing effeicient api calls to DnD5eapi.co
2. Demonstrate understanding of pandas library and and database management principles by cleaning and restructuring data from api calls into normalized and queryable format
3. Show knowledge of psycopg2 by connecting to Postgresql database and importing data
4. Demonstrate data visualization fundamentals by extracting data into Tableau and drawing meaningful insights about DnD monster attributes

## How to Run
Running the "data to database.py" file will execute all the code (because there are numerous api calls, performance is currently a known issue. It will take a couple of minutes to run). Spreadsheets will be loaded into the folder you run the file in. These spreadsheets currently contain messy data that will be cleaned in future iterations.

## Known Issues
1. Performance: Because of the numerous api calls, threading will possibly be used in future iterations
2. Messy Data: Data Frames will be cleaned and normalized
3. Database Connection: Connection to Postgresql database still needs to be established
4. Tableau Dashboard: Monster dashboard will be created once the above issues are completed.
