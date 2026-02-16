# Web-Scrapping
## API Web Scraping – Beginner Project
# About This Project
This project shows how to get data from an API using Python.
Instead of scraping data from HTML pages, we directly fetch structured data (JSON format) from an API and convert it into a table using Pandas.
The project is created in:
"APIWEBSCRAPING.ipynb"
## What I Learned
What an API is
How to send a request using Python
How to get JSON data
How to convert JSON data into a Pandas DataFrame
## Tools Used
Python
Jupyter Notebook
requests library
pandas library
## Basic Steps Used in This Project
Step 1: Import Requests Library
Step 2: Store API URL
Step 3: Send GET Request
Step 4: Check Status Code
Step 5: Convert Response to JSON
Step 6: Check JSON Structure
Step 7: Extract Required Fields
We extracted:
Title
Description
Category
Category ID
Slug
Website
Logo Link
Step 8: Convert to Pandas DataFrame
## Common Error
JSONDecodeError
This error happens when:
          The API URL is wrong
          The server does not return JSON
## What I Learned
How to fetch data from an API
How to handle JSON responses
How to navigate nested JSON structures
How to extract specific fields
How to convert API data into a Pandas DataFrame
