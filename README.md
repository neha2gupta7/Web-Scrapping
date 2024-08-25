# Web-Scrapping
Overview
This challenge involves scraping data from the JustWatch website and performing data analysis and filtering using Python libraries. JustWatch is a platform that aggregates streaming content across various services. Your goal is to scrape data for movies and TV shows, analyze it, and export the results.

Website
JustWatch URL: JustWatch Movies
Description
JustWatch allows users to search for movies and TV shows across multiple streaming services like Netflix, Amazon Prime, Hulu, etc. This assignment requires you to scrape data directly from JustWatch (not using APIs) and handle it using Python libraries.

Tasks
1. Web Scraping
Using Selenium, BeautifulSoup, and Python, scrape the following data from JustWatch:

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
You can start with popular content or a specific genre to ensure diversity in your dataset.
2. Data Filtering & Analysis
After scraping, use Pandas to perform the following tasks:

a. Data Filtering
Only include movies and TV shows released in the last 2 years from the current date.
Only include movies and TV shows with an IMDb rating of 7 or higher.
b. Data Analysis
Calculate the average IMDb rating for the scraped movies and TV shows.
Identify the top 5 genres with the highest number of available movies and TV shows.
Determine the streaming service with the most significant number of offerings.
3. Data Export
Export the filtered and analyzed data to a CSV file.
Save the CSV file to your Google Drive folder and share the link in your Colab notebook with view access to anyone.
Submission Requirements
Google Colab Link:

Submit a link to your Google Colab notebook containing your Python script.
Python Script:

Your Colab notebook should include your Python script in .py format.
Ensure clear comments explaining the scraping, filtering, and analysis process.
Error Handling:

Your script should handle errors and exceptions robustly to ensure it runs without issues.
Code Quality:

Ensure your code is well-structured, easy to understand, and follows Python best practices.
Dataset Link:

Include the dataset Google Drive link in your Colab notebook.
Evaluation Criteria
Correctness of Scraped Data: Ensure the data scraped is accurate and complete.
Accuracy of Data Filtering & Analysis: Correctly apply filters and perform accurate data analysis.
Quality of Python Code: Well-structured, clear, and executable code.
Notes
Web Scraping Ethics: Be respectful of the website’s scraping policies and avoid overloading their servers.
Documentation: Ensure your code and methodology are well-documented for clarity.
