# Beautiful Soup Challenge
This repository will be used for the Module 9 SQL challenge.

## Description

For this beautiful soup challenge, I completed two parts of the project: web scraping and data analysis. For the data scraping part of the project I used the automated browsing library with Splinter and HTML parsing with Beautiful Soup. I used the following URL to scrape data from: https://static.bc-edx.com/data/web/mars_news/index.html. This URL contains data from NASA about Mars news. My first task was to loop through each article and grabbing the title and preview text. I then put all that information into a json file for later use. That was all for the web scraping part of the project.

Moving on to the data analysis part of the project, I scraped data from the same website but a different directory that contained a table: https://static.bc-edx.com/data/web/mars_facts/temperature.html. Within the websites table, I pulled all of the rows of data and stored it into a Pandas dataframe with the same headings as the table on the website. I saved the data from the pandas dataframe into a csv so I could access the data later without having to scrape the data all over again. Now the data analysis part begins. Using the to_datetime() and astype() functions, I updated all the datatypes of the columns of data to match what they should be. I then answered the next 5 questions using past knowledge of :

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average the minimum daily temperature for all of the months.
    * Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average the daily atmospheric pressure of all the months.
    * Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.

## Installation

Feel free to download the Python Jupyter files I provided to look over and run the python script.

## Contributing

Pull requests are welcome. For major changes or additions to the project, please open an issue first
to discuss what you would like to change/recommend.
