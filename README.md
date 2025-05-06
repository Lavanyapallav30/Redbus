#Red Bus Details Scraping

This project scrapes bus details, preprocesses the data, stores it in a database using SQL, and provides an interactive streamlit application for users to filter and view bus information.

Features:
RedBus_Details_Scraping - Scrapes bus route details and saves them as a CSV file.
Data_Preprocessing - Cleans and processes the scraped.
SQL - Stores the processed data in a MySQL database.
App - Provides a Streamlit-based UI to explore bus details interactively.

Prerequisites
Python
MySQL Server

Required Python libraries:
pip install selenium pandas mysql-connector-python streamlit

Usage
Step 1: Run the Scraper
python RedBus_scrap
This will generate a CSV file with bus route details.

Step 2: Data Preprocessing
Open RB_data_cleaning.ipynb in Jupyter Notebook and run all cells to clean the data. NOTE: You need to look at the bus type as it may change.

Step 3: Load Data into MySQL
Run the SQL scripts in RB_SQL.ipynb to create the necessary database and import the processed data.

Step 4: Launch the Application
streamlit run app.py
This starts the interactive streamlit app where you can filter and sort buses in various ways.
