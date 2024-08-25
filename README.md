# Web-Scrapping

**Overview**
This repository contains a solution for a data scraping and analysis challenge based on the JustWatch website. JustWatch is a platform that provides information on movies and TV shows across various streaming services. The challenge involves scraping data using Python libraries, performing data filtering and analysis, and exporting the results.

**Website**
JustWatch URL: JustWatch Movies
Description
In this assignment, you will:

**Scrape Data:**
Use Selenium, BeautifulSoup, and Python to extract data directly from JustWatch. The data should be extracted from the HTML of the pages rather than via an API.
Data Filtering & Analysis:

Filter and analyze the scraped data using Pandas.

**Export Data:**

Save the filtered and analyzed data into a CSV file for further processing and reporting.

Tasks

1. Web Scraping
Using BeautifulSoup and Selenium, scrape the following information from JustWatch:

a. Movie Information
Movie title
Release year
Genre
IMDb rating
Streaming services available (e.g., Netflix, Amazon Prime, Hulu)
URL to the movie page on JustWatch
b. TV Show Information
TV show title
Release year
Genre
IMDb rating
Streaming services available (e.g., Netflix, Amazon Prime, Hulu)
URL to the TV show page on JustWatch
c. Scope
Scrape data for at least 50 movies and 50 TV shows.
You can start with popular content, specific genres, or any other entry point to ensure a diverse dataset.
2. Data Filtering & Analysis
After scraping, use Pandas to perform the following tasks:

a. Data Filtering
Filter the data to include only movies and TV shows released in the last 2 years from the current date.
Filter to include only movies and TV shows with an IMDb rating of 7 or higher.
b. Data Analysis
Calculate the average IMDb rating for the scraped movies and TV shows.
Identify the top 5 genres with the highest number of available movies and TV shows.
Determine the streaming service with the most significant number of offerings.
3. Data Export
Export the filtered and analyzed data to a CSV file.
Upload the CSV file to your Google Drive and share the link with view access in your Colab notebook.
Submission
Colab Notebook Link: Submit a link to your Google Colab notebook with your Python script.
Python Script: Ensure the Colab notebook contains the Python script in .py format with clear comments explaining the scraping, filtering, and analysis process.
Dataset Link: Include the Google Drive link to your dataset in the Colab notebook.
Notes
Error Handling: Properly handle errors and exceptions during web scraping to ensure a robust and reliable script.
Code Quality: Ensure your code is well-structured, easy to understand, and follows Python best practices.
Execution: Ensure that your code can be executed from start to finish without errors.
Evaluation Criteria
Correctness of Scraped Data: Ensure that the data scraped is accurate and complete.
Accuracy of Data Filtering & Analysis: Correctly apply filters and perform accurate data analysis.
Quality of Python Code: Ensure that your code is well-structured and adheres to best practices.
