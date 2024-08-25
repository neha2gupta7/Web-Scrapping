# Web-Scrapping

**Overview**
This repository provides a solution for a data scraping and analysis challenge based on the JustWatch website. JustWatch is a popular platform that aggregates information on movies and TV shows across various streaming services such as Netflix, Amazon Prime, Hulu, etc. The challenge involves scraping data using Python libraries, performing data filtering and analysis, and exporting the results for further use.

**Website**
JustWatch URL: JustWatch Movies

**Description**

In this assignment, the goal is to:

Scrape Data:

Use Selenium, BeautifulSoup, and Python to extract data directly from the JustWatch website. Data should be extracted from the HTML of the pages rather than via an API.

Data Filtering & Analysis:

Utilize Pandas to filter and analyze the scraped data.

**Tasks**
**1. Web Scraping**
Using BeautifulSoup, scrape the following information from JustWatch:

**a. Movie Information**

Movie Title: The title of the movie.

Release Year: The year the movie was released.

Genre: The genre of the movie.

IMDb Rating: The IMDb rating of the movie.

Streaming Services Available: Services where the movie is available (e.g., Netflix, Amazon Prime, Hulu).

URL to Movie Page: Direct link to the movie page on JustWatch.

**b. TV Show Information**

TV Show Title: The title of the TV show.

Release Year: The year the TV show was released.

Genre: The genre of the TV show.

IMDb Rating: The IMDb rating of the TV show.

Streaming Services Available: Services where the TV show is available (e.g., Netflix, Amazon Prime, Hulu).

URL to TV Show Page: Direct link to the TV show page on JustWatch.

c. Scope

Data Volume: Scrape data for at least 50 movies and 50 TV shows.

Entry Point: You may start with popular content, specific genres, or any other entry point to ensure a diverse dataset.

**2. Data Filtering & Analysis**
   
After scraping, perform the following tasks using Pandas:

a. Data Filtering

Filter by Release Date: Include only movies and TV shows released in the last 2 years from the current date.

Filter by IMDb Rating: Include only movies and TV shows with an IMDb rating of 7 or higher.

b. Data Analysis

Average IMDb Rating: Calculate the average IMDb rating for the scraped movies and TV shows.

Top Genres: Identify the top 5 genres with the highest number of available movies and TV shows.

Top Streaming Service: Determine which streaming service has the most significant number of offerings.

**Requirements**

Libraries: Selenium, BeautifulSoup, Pandas

Python Version: Ensure compatibility with Python 3.x
