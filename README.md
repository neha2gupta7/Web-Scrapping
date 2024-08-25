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

**Web Scraping**

Using BeautifulSoup, scrape the following information from JustWatch:

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
